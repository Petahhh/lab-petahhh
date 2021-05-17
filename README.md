LAB - Petahhh's Markdown Sample
=====================

This workshop demos all the different features a workshop can have.

If you already have the Educates operator installed and configured, to
deploy and view this sample workshop, run:

```
kubectl apply -f https://raw.githubusercontent.com/petahhh/lab-petahhh/master/resources/workshop.yaml
kubectl apply -f https://raw.githubusercontent.com/petahhh/lab-petahhh/master/resources/training-portal.yaml
```

This will deploy a training portal hosting just this workshop. To get the
URL for accessing the training portal run:

```
kubectl get trainingportal/lab-petahhh
```
