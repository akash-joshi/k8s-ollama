## Why did you choose minikube for the demo instead of kind or k3s?
- Consistent behavior across platforms
- Simplicity and ease of use
- Compatibility with most k8s tools and workflows

## Is the Ollama container running as root? What are the security implications?
- Yup, and that's highly unsecure and discouraged in production.
- One must go through the documentation of Pod Security Standards to decide the security context of the container - https://kubernetes.io/docs/concepts/security/pod-security-standards/.

## How do you handle access control and API authentication?
- We don't. This is a demo. In production, you should use network policies and role-based auth in k8s to secure your cluster.

## Why LoadBalancer instead of NodePort or ClusterIP?
- ClusterIp is only accessible within the cluster.
- NodePort requires manual port mapping and is more complex for demos.
LoadBalancer has:
- Easy external access for demos
- Works well with minikube service
- Simulates cloud-provider setups locally

## What monitoring and observability solutions have you implemented?
- None. In production, you should use Prometheus, Grafana, and other monitoring tools.