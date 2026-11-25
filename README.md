# Hi, I'm Kazem 👋

**Cloud & AI Infrastructure Engineer** based in Turin, Italy.
Research Fellow at Politecnico di Torino · M.Sc. Computer Engineering.

I build Kubernetes platforms at the multi-cluster, scheduling and networking layer,
write controllers in Go, and automate infrastructure end to end. Now focused on the
infrastructure that runs AI: GPU compute, high-performance networking, and the
orchestration that ties them together.

---

### 🔬 Research & multi-cluster work

Where I spend most of my time: running workloads across many small clusters, from edge to cloud.

- 🤖 **[federation-autoscaler](https://github.com/netgroup-polito/federation-autoscaler)**: Cluster Autoscaler extension that borrows compute across federated clusters and exposes it as virtual nodes via Liqo. Go · kubebuilder · gRPC · mTLS. Validated on a 6-cluster k3s federation.
- 🔧 **[liqo-upgrade-operator](https://github.com/thisiskazem/liqo-upgrade-operator)**: Kubernetes operator for minimal-downtime Liqo upgrades, with health gates and automatic rollback. Helm chart on Artifact Hub.
- 🖥️ **[edge-infrastructure-ansible](https://github.com/thisiskazem/edge-infrastructure-ansible)**: Ansible automation for an edge computing testbed (k3s, Liqo peering, KubeVirt).
- 🌐 Contributor to **[Liqo](https://github.com/liqotech/liqo)** (CNCF ecosystem): resource reservation features and docs.

Currently working on AI workload optimization for telco edge data centers.

### 📦 Portfolio

> Three repos, one story: a small European logistics company shipping a service
> to Kubernetes. Each is a complete real-world scenario you can run on a laptop
> in about five minutes, no cloud account required.

- ⎈ **[gitops-k8s-platform](https://github.com/thisiskazem/gitops-k8s-platform)**: A commit becomes a running, monitored deployment. Go service → Docker → Helm → Argo CD → Prometheus, with multi-window SLO alerting. `make demo` brings the whole thing up on kind.
- ☁️ **[aws-landing-zone](https://github.com/thisiskazem/aws-landing-zone)**: The AWS account underneath it. VPC, EKS, IRSA, remote state, and a Terraform pipeline that authenticates with OIDC and stores no AWS credentials at all.
- 🐧 **[linux-fleet-automation](https://github.com/thisiskazem/linux-fleet-automation)**: Ansible roles for the Linux hosts around the cluster, plus a Bash auditor that verifies the hardening independently of the tool that applied it. Molecule proves idempotence.

---

### 🏅 Certifications

- **NVIDIA-Certified Associate: AI Infrastructure and Operations** (2026)
- **MikroTik MTCNA · MTCWE**
- 🎯 Next: NVIDIA **AI Operations (NCP-AIO)** · **AI Networking (NCP-AIN)**

### 🧰 Stack

**AI infrastructure:** `NVIDIA GPU stack` `DCGM` `MIG` `InfiniBand` `RoCE` `Slurm`<br>
**Kubernetes:** `Kubernetes` `Helm` `Kustomize` `KubeVirt` `Liqo` `Go` `kubebuilder`<br>
**Cloud & automation:** `AWS` `Terraform` `Ansible` `GitHub Actions` `Argo CD` `Docker`<br>
**Observability:** `Prometheus` `Grafana` `Kepler`<br>
**Foundations:** `Linux` `Networking` `Bash` `Python`

---

### 📫 Where to find me

- 💼 [LinkedIn](https://www.linkedin.com/in/kazembigdeli/)
- 📧 kazem26@gmail.com
