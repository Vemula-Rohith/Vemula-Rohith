# Hi, I'm Rohith 👋

I'm a DevOps engineer interested in Kubernetes infrastructure, networking, and reliability. I like tracing production issues to their root cause and contributing the fixes upstream.

## Open source contributions

- **[Calico operator](https://github.com/tigera/operator/pull/5290)** — Fixed a startup race that could give new pods the wrong network MTU when Calico auto-detects it. The operator now waits for the MTU file before creating the pod interface.
- **[MetalLB](https://github.com/metallb/metallb/pull/3134)** — Stopped the speaker from repeating `nodeAssigned` events on every reconcile. Events now reflect actual announcement changes.
- **[Submariner](https://github.com/submariner-io/submariner/pull/4216)** — Fixed stale Prometheus connection metrics so they report each cable’s current status and update counts when cables disconnect or are replaced.

All three contributions have been merged upstream.

## Projects

- **[KubeRadar](https://github.com/Vemula-Rohith/kuberadar)** — A Go CLI for diagnosing Kubernetes pods and deployments, with output that can be used in CI.

## Areas I work in

Kubernetes · Go · Linux · CNI · cluster networking · infrastructure troubleshooting

Feel free to explore my repositories or reach out through GitHub.
