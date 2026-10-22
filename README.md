# demo-env-handover

Documentation and handover for the demo platform environment.

## Environment

| Item | Value |
| --- | --- |
| Kubernetes namespace | `demo-app` |
| Helm release name | `demo-ingress` |
| Helm chart | `ingress-nginx/ingress-nginx` (upstream repo: https://kubernetes.github.io/ingress-nginx) |

The ingress-nginx controller is deployed in the `demo-app` namespace via the Helm release
`demo-ingress`, installed from the official `ingress-nginx` chart.

## Credits

This project stands on the shoulders of the upstream Kubernetes project. Credits:
Upstream Kubernetes project — GitHub organization login `kubernetes`,
profile URL https://github.com/kubernetes
