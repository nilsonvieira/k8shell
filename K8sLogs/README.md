# Install k8slogs
```bash
curl -LO https://raw.githubusercontent.com/nilsonvieira/k8shell/main/K8sLogs/k8slogs && sudo install -m 0755 k8slogs /usr/local/bin/k8slogs
```

# How to Use

for use this script, after install you need execute:
```bash
k8slogs namespace name_of_pod
```

The logfile will be on Downloads user folder on subfolder Logs, with name_of_pod.log. For example:

**$HOME/Downloads/Logs/name_of_pod.log**
