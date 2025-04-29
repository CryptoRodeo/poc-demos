# Apply Issue CRD

```bash
kubectl apply -f issue-crd.yaml
```

# Apply example Issue CR
```bash
kubectl apply -f example-issue-a.yaml
```
```bash
kubectl apply -f example-issue-b.yaml
```

# Ensure Issues exist
```bash
kubectl get isu
```

# Filter Issues using labels
```bash
kubectl get isu -l 'component.name=app-component-a'  
```
```bash
kubectl get isu -l 'component.name=app-component-b'  
```

# View Issue data
```bash
kubectl describe issue -l 'component.name=app-component-a'
```
