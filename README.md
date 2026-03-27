# Synapse Studio ???

Synapse Studio is a next-generation AI-powered code and web builder that combines a React frontend, Express backend, and multiple AI provider integrations in a single repository.

## ?? Quick start

1. Install dependencies:
   `ash
   npm install
   `
2. Copy .env.example to .env and set your keys.
3. Run development:
   `ash
   npm run dev
   `
4. Open: http://localhost:5000

## ?? Features

- Vite + React frontend
- Express backend (API + static serve)
- AI provider fallback (Ollama, Gemini, OpenAI, Claude, Groq, Perplexity)
- Real-time code workspace and terminal
- Design editor + dashboard + authentication

## ?? Project structure

- client/: frontend app source
- server/: backend API and services
- data/: local JSON storage files
- shared/: schema and types

## ??? Scripts

- 
pm run dev: start frontend + backend dev server
- 
pm run build: build production frontend
- 
pm start: run Express server for production
- 
pm test: run test suite (if configured)

## ?? Environment variables

`env
SESSION_SECRET=change_me
OLLAMA_API_URL=http://localhost:11434
OLLAMA_MODEL=qwen2.5-coder:1.5b
GEMINI_API_KEY=your_gemini_key
OPENAI_API_KEY=your_openai_key
`

## ?? Deployment

1. Push to GitHub:
   `ash
   git add .
   git commit -m  docs: update README
   git push origin main
   `
2. Deploy with Vercel (via dashboard or ercel --prod).

## ?? Notes

- Add .local and 
ode_modules to .gitignore.
- Keep secrets out of Git.
