# CPI‑Triage‑AI (Launchpad‑ready)
## Build & Push Images
docker build -f docker/Dockerfile.train -t <your-registry>/<repo>:cpi-triage-ai-train .
docker build -f docker/Dockerfile.serve -t <your-registry>/<repo>:cpi-triage-ai-serve .
docker push <your-registry>/<repo>:cpi-triage-ai-train
docker push <your-registry>/<repo>:cpi-triage-ai-serve
