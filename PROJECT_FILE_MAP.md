# Project File Map

| Path | Purpose |
|---|---|
| `frontend/index.html` | Full English-first responsive dashboard and browser-side application code |
| `backend/server.js` | Express server, database initialization, authentication, seller-scoped API routes, and static frontend hosting |
| `backend/services/aiStudioService.js` | Server-side Google Gemini chat, marketing copy, and image-generation adapter |
| `tests/static.test.js` | Automated static regression checks for project structure, syntax, UI hooks, and safety guards |
| `package.json` | Node.js metadata, dependencies, start/dev/test scripts, and runtime version |
| `.env.example` | Safe template for environment variables; contains placeholders only |
| `.gitignore` | Excludes secrets, dependencies, logs, and generated local files from Git |
| `.nvmrc` | Suggested Node.js major version for version managers |
| `README.md` | Main project overview and local setup instructions |
| `AI_SETUP.md` | Google Gemini setup checklist |
| `API_REFERENCE.md` | Backend API route overview |
| `DEPLOY_GUIDE.md` | Node.js/PostgreSQL deployment and verification instructions |
| `GITHUB_UPLOAD_GUIDE.md` | GitHub upload structure and secret-handling instructions |
| `TEST_REPORT.md` | Automated test results and test scope limitations |

## Not included as working live integrations

Marketplace OAuth, live product/listing publishing, order sync, courier booking/tracking, email verification, password reset, and account recovery require additional provider-specific or production-hardening work. A connection setting or UI control is not proof that an external action is live.
