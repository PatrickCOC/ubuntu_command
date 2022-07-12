# System limit for number of file watchers reached

```
Internal watch failed: ENOSPC: System limit for number of file watchers reached, watch '...path'
```

## solved
```
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
```