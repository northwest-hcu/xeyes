# How to work GUI app on docker on Windows
1. Install docker.
2. Enable wsl.
3. Install X Server like VcXsrv.
4. `docker compose -f compose.yaml build`
5. `docker compose -f compose.yaml up`

※On Windows, you can't use WSLg as X Server for docker. It just works GUI apps on your WSL.