# Bot Office
Live office view of Austin's bots. The page reads `status.json` and re-checks it every 60 seconds.
To refresh: rewrite `status.json` (same shape; `lastActive: null` and `task: null` mean unknown), commit, push to `main`.
