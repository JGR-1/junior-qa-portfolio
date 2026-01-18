Automatic page refresh resets user-selected translation tone

Bug type: UX / Usability

Severity: Low

Priority: Medium

Steps to reproduce:
1. Select a language that has different tone options
2. Use the page for some time
3. Let the page set idle for a few seconds
4. Try to translate again

Expected result:
- Page should mantain user preference even on reload or micro reloads

Actual result:
- Page micro reloads every few minutes, and the tone is resetted, so the user has to select the tone again.

Enviorment:
- Chrome 120
- Windows 10

Source: https://www.bing.com/translator
