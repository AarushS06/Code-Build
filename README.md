# Emergency Intelligence

A Vercel-ready static recreation of the Emergency Intelligence public response portal.

## Run locally

```bash
npx serve .
```

Or open `index.html` directly in a browser.

## Deploy on Vercel

1. Upload this folder to a new GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Keep the default settings: no build command and `.` as the output directory.
4. Click **Deploy**.

The project is plain HTML, CSS, and JavaScript, so it does not require a build step.

## Included interactions

The SOS and accident-report actions open responsive dialogs; case tracking validates and displays a simulated case status; hospital capacity shows a status toast; navigation, language selection, help, and responsive layouts are functional.

## Note

This is a front-end recreation of the supplied public page. The response, case tracking, and hospital data are demo interactions and are not connected to a live emergency dispatch system.
