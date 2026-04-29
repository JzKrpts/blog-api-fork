### Project Structure

## Frontend Javascript (Vue) -> MonoRepo Structure
```
blog-api/ (Workspace Root)
├── .github/          # CI/CD workflows
├── backend/          # All Python code (Django/FastAPI)
│   ├── src/          # Source code
│   ├── tests/
│   └── pyproject.toml
├── frontend/         # All JS/TS code (React/Next.js)
│   ├── src/
│   └── package.json
├── .gitignore
├── uv.lock           # Root lockfile if using uv workspaces
└── pyproject.toml    # Root manifest linking members

```