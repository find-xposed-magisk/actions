| Module Name | Relative Path | Functionality | Dependencies |
| --- | --- | --- | --- |
| Keep Actions Active | .github/workflows/keep-actions-active.yml | Updates the root keepalive marker monthly and commits it to keep repository activity current. | GitHub Actions, actions/checkout@v4, GITHUB_TOKEN contents write permission |
| xixu-me-xget Sync Fork | .github/workflows/(web_proxy)-xixu-me-xget _Sync Fork.yaml | Syncs xixu-me/xget fork and release data; schedule moved off the hour to reduce cron congestion. | GitHub Actions, actions/checkout@v2, actions/setup-node@v2 |
| Keepalive Marker | keepalive.txt | Stores the latest keepalive timestamp. | keep-actions-active workflow |
