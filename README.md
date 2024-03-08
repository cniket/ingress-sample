# ingress-sample

This is a sample application repo with ingress configuration template. It consist of TWO apps blue and green and an ingress resource with backend as those two apps.

The ingress has few annotations and `ingressClassName: alb` assuming [AWS Load Balancer Controller](https://github.com/kubernetes-sigs/aws-load-balancer-controller) is deployed in the cluster. The parameters can be changed specific to any other ingresscontroller deployed in the cluster.
