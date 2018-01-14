# POC for audio to speech

This is a quick and dirty poc for converting audio to text using google cloud speech api.

## getting started

1. Follow the authentication steps for google cloud api: [https://cloud.google.com/docs/authentication/getting-started)](https://cloud.google.com/docs/authentication/getting-started)
2. Create a project ID by following the steps in the link above ( you will need a credit card for billing).
3. Modify config.json file with the project ID generated on google cloud api.
4. Run `node index.js` in terminal ( you can add breakpoints and run debug mode if using vscode)

Once the transcript is completed you should see a the following line in the console as a result of converting the audio file located in `./resources/Imagination-einstein-mono.flac:

`Transcription: imagination is more important than knowledge`