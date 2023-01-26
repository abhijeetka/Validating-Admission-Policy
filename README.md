# Validating-Admission-Policy
Validating Admission Policy , new feature in k8s 1.26 release


enable configuration in kube api server.

```
--feature-gates=ValidatingAdmissionPolicy=true
--runtime-config=admissionregistration.k8s.io/v1alpha1=true
```

