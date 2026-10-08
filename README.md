# turbo-token-exfil fixture

**Security research / proof-of-concept fixture for a coordinated vulnerability disclosure report.**
This repository exists solely to demonstrate, in an authorized laboratory setting, how a
repository-controlled `remoteCache.apiUrl` field in `turbo.json` selects the destination of
Turborepo's remote-cache requests. All credentials used here (repository secret, receipts in
the accompanying report) are synthetic canary values created for this research; no real
account, real token, real cache endpoint, or Vercel production system is involved. The pull
request in this repository changes only `turbo.json`. Not affiliated with any malicious use.
