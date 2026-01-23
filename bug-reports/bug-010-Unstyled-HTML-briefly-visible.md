Unstyled HTML briefly visible before CSS finishes loading

Bug type: UX

Severity: Low

Priority: Low

Steps to reproduce:
1. Be on any section of the site
2. Click an option on the left menu

Expected result:
- CSS should load simultaneously with HTML, without visible layout or style changes to the user.

Actual result:
- HTML content is rendered first, followed by CSS loading, causing a brief flash of unstyled content visible to the user.


Enviorment:
-  Chrome 120
-  Windows 10

Source: https://www.kassoon.com/
