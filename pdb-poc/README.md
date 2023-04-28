# PodDisruptionBudget & GitOps Proof-of-Concept

## Scenario

This scenario is meant to demonstrate the interaction between a GitOps-managed application and how a PodDisruptionBudget can be applied to multiple Pods across distinct Deployments using arbitrary selectors in order to control the restart logic of those Pods once a change has been pushed to the backing git repository.

## Results

EXPERIMENT FAILED: https://kubernetes.io/docs/concepts/workloads/pods/disruptions/#:~:text=Pods%20which%20are,specific%20workload%20resource.
