# PIXEL NEST AI V2

A responsive, black-and-gold productivity workspace prototype.

## Current features
- Overview dashboard
- Task manager
- Daily planner
- Writing Studio (local demonstration logic)
- Study Helper (local demonstration logic)
- Notes
- AI Assistant interface (sample responses only; not connected to a live AI model)

## Run locally
Open `index.html` in a modern web browser.

## Important before public launch
This is a front-end prototype. The assistant, writing, and study features do not yet call a real AI model. A secure server-side backend must be added before enabling live AI. Never put an AI provider API key in `index.html`, browser JavaScript, GitHub, or a public repository. Configure secrets only as server-side environment variables in the hosting provider. Add usage limits and abuse protection before allowing public access because AI API calls may cost money.

## Deployment
This static prototype can be deployed to a static hosting provider after uploading the repository. Live AI functionality requires a separate backend/API integration.
