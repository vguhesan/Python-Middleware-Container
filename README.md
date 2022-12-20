# Python-Middleware-Container

This code creates a FastAPI Python middleware component with a backend PostgreSQL database spun up as a Docker Desktop container using Dev Containers.

Steps:

- Checkout the code via `git clone {https_repo_url}`.
- Change directory into project. Example: `cd Python-Middleware-Container` (your directory may vary depending on where you cloned the repository)
- Ensure that you have Docker Desktop running in the background with "Kubernetes" enabled.
- Start VSC (with the "Dev Containers" extension enabled.). Example: `code .`
- Click on "><" icon bottom left and choose "Reopen in Container".
- After it opens your Project under "Remote Container", you should see a "Python Middleware Container" group in Docker Desktop.
- Open a Terminal within VSC and run the following to spin up a "Python FastAPI Middleware Server". `uvicorn app:app --reload` (refer to https://fastapi.tiangolo.com/ for decumentation on how to start FastAPI example.)
- Visit "http://127.0.0.1:8000" on your host system browser to see the middleware "default-page" in action.
