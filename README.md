# Awesome-Cloud-Capacity-Planning

# Top Cloud Capacity Planning Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Cloud Resource Optimization, Rightsizing, Cost Allocation, Autoscaling Intelligence, FinOps & Workload Efficiency*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Capacity Planning**. These tools analyze utilization, recommend rightsizing, allocate costs, automate scaling, and help organizations optimize cloud spend and performance.

**Examples** include Apptio Cloudability, IBM Turbonomic, Densify, CloudBolt, CloudHealth by VMware, Flexera One, CloudCheckr, ParkMyCloud, StormForge, and ScaleOps (the category leaders).

**Open-source emphasis**: Full multi-cloud capacity planning and automated optimization remain largely commercial. The strongest open options center on **OpenCost** (CNCF) for Kubernetes cost allocation, plus native Kubernetes autoscalers and observability stacks. This section expands those projects and is realistic about the commercial gap for enterprise FinOps platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Apptio Cloudability](https://www.apptio.com/products/cloudability/)**  
  Leading FinOps and cloud cost management platform for visibility, allocation, rightsizing recommendations, and multi-cloud spend optimization.

- **[IBM Turbonomic](https://www.ibm.com/products/turbonomic)**  
  Application resource management platform that continuously analyzes and optimizes compute, storage, and network capacity across hybrid environments.

- **[Densify](https://www.densify.com/)**  
  Capacity planning and optimization platform focused on machine-learning-driven rightsizing and resource efficiency for cloud and container workloads.

- **[CloudBolt](https://www.cloudbolt.io/)**  
  Hybrid cloud management and orchestration platform with cost, capacity, and self-service provisioning capabilities.

- **[CloudHealth by VMware / Broadcom](https://cloud.vmware.com/)**  
  Multi-cloud cost and capacity management platform for visibility, governance, and optimization (product branding may vary under Broadcom).

- **[Flexera One](https://www.flexera.com/)**  
  IT asset and cloud management platform including FinOps, rightsizing, and hybrid capacity planning features.

- **[CloudCheckr](https://cloudcheckr.com/)**  
  Cloud management platform for cost optimization, security, and inventory visibility across public clouds.

- **[ParkMyCloud / Turbonomic-related scheduling](https://www.ibm.com/)**  
  Scheduling and park/unpark automation for non-production resources to reduce idle cloud spend (often associated with broader IBM optimization portfolios).

- **[StormForge](https://www.stormforge.io/)**  
  Kubernetes optimization platform using machine learning for resource recommendations and performance/cost efficiency.

- **[ScaleOps](https://scaleops.com/)**  
  Kubernetes-focused automation platform for rightsizing, bin-packing, and continuous capacity optimization.

## Open-Source GitHub Projects
- **[OpenCost](https://github.com/opencost/opencost)**  
  Leading CNCF open-source cost monitoring and allocation engine for Kubernetes and cloud spend—real-time allocation by namespace, workload, and cloud resources (Apache 2.0).

- **[Kubecost (open components / related)](https://www.kubecost.com/)**  
  Commercial platform built on the OpenCost engine; open allocation models and community editions support Kubernetes cost visibility.

- **[Kubernetes Horizontal Pod Autoscaler (HPA)](https://github.com/kubernetes/kubernetes)**  
  Native open-source autoscaling based on CPU/memory or custom metrics for capacity responsiveness.

- **[Kubernetes Vertical Pod Autoscaler (VPA)](https://github.com/kubernetes/autoscaler)**  
  Open-source component that recommends or applies CPU/memory requests and limits based on observed usage.

- **[Cluster Autoscaler](https://github.com/kubernetes/autoscaler)**  
  Open-source tool that automatically adjusts the size of Kubernetes clusters based on pending pods and utilization.

- **[Prometheus + Grafana capacity dashboards](https://github.com/prometheus/prometheus)**  
  Foundational open observability stack used for utilization metrics, capacity trends, and custom planning views.

- **[KEDA (Kubernetes Event-driven Autoscaling)](https://github.com/kedacore/keda)**  
  Open-source event-driven autoscaler for Kubernetes that scales based on external metrics and queues.

- **[Goldilocks](https://github.com/FairwindsOps/goldilocks)**  
  Open-source tool that uses VPA recommendations to help rightsize Kubernetes resource requests.

- **[Cloud provider open billing and usage exporters](https://github.com/)**  
  Community exporters that feed cloud billing and utilization data into Prometheus or OpenCost-style pipelines.

- **[Documentation and FinOps open playbooks](https://opencost.io/)**  
  Guides for deploying OpenCost, combining it with native autoscalers, and building basic capacity visibility without commercial platforms.

### Additional Strong Open-Source Options
- Deploying **OpenCost** for Kubernetes and multi-cloud cost allocation and showback.
- Combining **HPA + VPA + Cluster Autoscaler** (and optionally KEDA) for automated capacity response.
- Using **Prometheus/Grafana** for custom utilization and capacity trend analysis.
- Accepting that advanced multi-cloud recommendations, automated actions, reserved-instance planning, enterprise FinOps workflows, and support still favor commercial platforms (Cloudability, Turbonomic, Densify, Flexera, StormForge, ScaleOps, etc.).
- Focusing open-source efforts on Kubernetes-first environments, transparency, and cost-efficient visibility.

**Frameworks for building custom systems**: Collect metrics with Prometheus → allocate costs with OpenCost → rightsize via VPA/Goldilocks recommendations → scale with HPA/Cluster Autoscaler → report in Grafana. Suitable for platform and FinOps engineering teams. Many enterprises still adopt commercial capacity platforms for automation and multi-cloud governance.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Capacity and cost tools influence production resources and spend. Open-source deployments require careful validation of recommendations before automated changes. This list is not financial or operational advice.

---
**Made for FinOps practitioners, platform engineers, and open-source cloud advocates.**
Let's keep capacity efficient, visible, and as open as practical.
