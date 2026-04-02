Week 5 AI Simulator - Vercel Ready
Suggested simulator name: Tough Conversations
This package is ready for GitHub and Vercel.
Files
`index.html`
`api/chat.js`
`vercel.json`
`package.json`
Deploy
Upload all files to the root of your GitHub repo
Import the repo into Vercel
Add environment variable:
`ANTHROPIC_API_KEY`
Redeploy
Notes
Frontend calls `/api/chat`
Anthropic key stays server-side
Speaker playback uses browser speech synthesis with male/female voice preference by character
Microphone stays on until clicked again to stop
Scenario cards render on the landing page
