# envoy-ratelimit-chart

Helm chart for https://github.com/envoyproxy/ratelimit

## Install

```
helm dependency update
helm upgrade ratelimit . --namespace istio-system --values myvalues.yaml --install
```
