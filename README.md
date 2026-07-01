# voice-mic-bridge
Static microphone-capture page for the WorkWave Voice AI Onboarding Agent (Apps Script web app).
Apps Script serves its UI in a sandboxed iframe that blocks the mic; this page runs as a normal popup
(full mic access), does browser speech-to-text, and postMessages transcripts back to the opener.
**No secrets here.** Served via GitHub Pages.
