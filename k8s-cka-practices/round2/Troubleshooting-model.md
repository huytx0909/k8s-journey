# Troubleshooting application
- Visualise the graph stack and validate one by one
  - For example: User - frontendUI - frontendService - frontendPod - backendService - backendPod

# Troubleshooting cluster
- Validate PKI
- Validate node

# Troubleshooting control plane
 - [K8s-101] Troubleshooting control plane

# Troubleshooting networking
 - [file](Troubleshoot-networking.md)
 
# Troubleshooting worker node
 - journalctl -u kubelet -f 
 - systemctl status kubelet
 - systemctl restart kubelet
 - /var/lib/kubelet
 - /etc/kubernetes/manifest/kubelet
