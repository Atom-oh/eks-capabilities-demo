# eks-capabilities-demo

Manifests used for the blog series on Amazon EKS Capabilities (managed Argo CD, kro, ACK) at https://blog.atomai.click/.

- `apps/demo-web`: tiny nginx app synced by Argo CD
- `argocd/`: Application and ApplicationSet (destination cluster name `eks-cap-demo`)
- `kro/`: ResourceGraphDefinition example (from the kubernetes-docs examples)
- `ack/`: ACK resources and IAMRoleSelector examples

No account IDs or secrets are stored here. Replace placeholders such as `<ACCOUNT_ID>` before applying.
