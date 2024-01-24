# kyverno-poc
1. Playground environment to showcase some of Kyverno's abilities
2. Configured for a kubeadm cluster. For platform spesific (EKS, AKS, etc.) config, please see docs. 
3. HA installation with helm. Multiple replicas of core components.
4. Mix and match of validate and mutate rules simulating an enterprise cluster.
5. Kyverno helm chart has out-of-the-box observability options. 
6. Metrics are exposed from Kyverno's main components. Config is made to scrape them.
7. Alerts are configured upon policy fail events.
8. Traces are enabled them and sent to jaeger backend already present in the cluster.

Kyverno Threat Model docs --> https://kyverno.io/docs/security/#threat-model