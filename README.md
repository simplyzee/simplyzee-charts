# SimplyZee Helm Charts

Collection of my helm charts

## Setup

To add the helm repository

```bash
helm repo add simplyzee https://charts.simplyzee.dev
helm repo update
helm search repo simplyzee
```

## Charts

| Chart | What it does |
|---|---|
| [kube-arr](https://github.com/simplyzee/kube-arr) | The *arr media stack: Sonarr, Radarr, Lidarr, Bazarr, Prowlarr, Jackett and Plex, Jellyfin or Emby, with optional cloud storage and transcodes as pods |
| [kube-rclone](https://github.com/simplyzee/kube-rclone) | Mount any rclone remote on every node |
| [kube-owasp-zap](https://github.com/simplyzee/kube-owasp-zap) | OWASP ZAP security scans as Jobs or CronJobs |

