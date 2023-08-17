#How to run tekton pipeline:

1) add logic to **build.yaml**;
2) apply:
```bash
kubectl apply -f build.yaml
```
3) run pipeline by Headlamp UI OR by command
```bash
kubectl apply -f pipelinerun.yaml
```
