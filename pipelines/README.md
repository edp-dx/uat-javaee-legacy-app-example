# How to run tekton pipeline:

1) Add logic to **build.yaml**;
2) Apply:
```bash
kubectl apply -f build.yaml
```
3) Run pipeline by [Headlamp UI](https://edp-headlamp-dx-dev.eks-sandbox.aws.main.edp.projects.epam.com/c/main/edp/components/dx-dev/javaee-legacy-app-example) or by command:
```bash
kubectl apply -f pipelinerun.yaml
```
