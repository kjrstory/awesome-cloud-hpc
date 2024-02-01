
# Awesome Cloud HPC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

A curated list of cloud HPC.

## Contents

- [CSP - Solution](#CSP---Solution)
- [CSP - Management](#CSP---Management)
- [CSP - IaaS(Server)](#CSP---IaaS(Server))
- [CSP - IaaS(Network)](#CSP---IaaS(Network))
- [CSP - IaaS(Storage)](#CSP---IaaS(Storage))
- [CSP - IaaS(etc.)](#CSP---IaaS(etc.))
- [CSP - PaaS](#CSP---PaaS)
- [Platform](#Platform)
- [CAE,EDA ISV](#CAE,EDA-ISV)
- [SaaS](#SaaS)
- [Job Scheduler](#Job-Scheduler)
- [Blog, Documentation, YouTube](#Blog,-Documentation,-YouTube)
- [Repository](#Repository)

## CSP - Solution

- [Amazon Web Services](https://aws.amazon.com/hpc/)
- [Microsoft Azure](https://azure.microsoft.com/en-us/solutions/high-performance-computing)
- [Google GCP](https://cloud.google.com/solutions/hpc)
- [Oracle OCI](https://www.oracle.com/cloud/hpc/)
- [Naver NCP](https://www.ncloud.com/solution/type/hpc)
- [Samsung SDS SCP](https://cloud.samsungsds.com/serviceportal/offerings/hpc.html)

## CSP - Management

- [AWS ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/) - Open source cluster management tool for deploying and managing HPC clusters on AWS ([Repository](https://github.com/aws/aws-parallelcluster)). ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
- [Azure CycleCloud](https://learn.microsoft.com/en-us/azure/cyclecloud/) - Secure and flexible cloud HPC and Big Compute environments on Azure. ![Azure](svg/dev/services/azure.svg)
- [Azure HPC OnDemand Platform](https://azure.github.io/az-hop/) - Azure-based HPC cluster solution with features like Terraform, Ansible, Packer integration, job scheduling, autoscaling, and monitoring ([Repository](https://github.com/Azure/az-hop), [Marketplace](https://azuremarketplace.microsoft.com/marketplace/apps/azhpc.azhop)).
- [GCP HPC Toolkit](https://cloud.google.com/hpc-toolkit) - Google Cloud's open-source software for deploying high-performance computing environments on GCP, featuring customizable Terraform modules and Packer integration. ([Repository](https://github.com/GoogleCloudPlatform/hpc-toolkit)).
- [Alibaba E-HPC](https://www.alibabacloud.com/product/ehpc) - Alibaba Cloud's computing service for resource management, job submission, performance analysis, and VNC in E-HPC console.
- [OCI HPC Cluster](https://cloudmarketplace.oracle.com/marketplace/listing/67628143) - Automated HPC cluster deployment on OCI.
- [OCI HPC File System (HFS)](https://cloudmarketplace.oracle.com/marketplace/listing/75560175) - Solution for deploying various HPC file servers on OCI. 
- [KT Cloud HPC](https://cloud.kt.com/product/productDetail?prodId=P000000015) - KT Cloud's HPC management product integrating Altair's solutions.
- [SCP HPC Cluster](https://www.samsungsds.com/en/compute-hpccluster/hpccluster.html) - HPC cluster environment on SCP.

## CSP - IaaS(Server) 

- [Amazon EC2 Hpc7g](https://aws.amazon.com/ec2/instance-types/hpc7g/) - HPC-optimized instances powered by AWS Graviton3E processors on AWS. <a href="#"> 
   <img src="svg/dev/services/aws.svg" alt="aws" style="vertical-align:bottom margin:6px 4px">
  </a>  
- [Amazon EC2 Hpc7a](https://aws.amazon.com/ec2/instance-types/hpc7a/) - HPC-optimized instances powered by 4th Generation AMD EPYC processors on AWS. ![AWS](svg/dev/services/aws.svg)
- [Amazon EC2 Hpc6id](https://aws.amazon.com/ec2/instance-types/hpc6i/) - HPC-optimized instances powered by 3rd Generation Intel Xeon Scalable processors on AWS.
- [Amazon EC2 P5](https://aws.amazon.com/ec2/instance-types/p5/) -  GPU instances powerd by NVIDIA H100 GPus on AWS.
- [Amazon EC2 P4](https://aws.amazon.com/ec2/instance-types/p4/) -  GPU instances powerd by NVIDIA A100(80Gb,40Gb) GPus on AWS.
- [Amazon EC2 P3](https://aws.amazon.com/ec2/instance-types/p3/) -  GPU instances powerd by NVIDIA V100 GPus on AWS.
- [Amazon EC2 G5](https://aws.amazon.com/ec2/instance-types/g5/) -  GPU instances powerd by NVIDIA A10G GPus and 2nd Gen AMD EPYC processors on AWS.
- [Azure HBv4-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hbv4-series) - HPC-optimized instances powered by 4th Generation AMD EPYC processors on Azure.
- [Azure HBv3-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hbv3-series) - HPC-optimized instances powered by 3rd Generation AMD EPYC processors on Azure.
- [Azure HBv2-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hbv2-series) - HPC-optimized instances powered by 2nd Generation AMD EPYC processors on Azure.
- [Azure HB-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hb-series) - HPC-optimized instances powered by 1st Generation AMD EPYC processors on Azure.
- [Azure HC-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hc-series) - HPC-optimized instances powered by 1st Generation Intel Xeon Scalable processors Azure.
- [Azure HX-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hx-series) - Optimized instances for workloads that require significant memory capacity with twice the memory capacity as HBv4.
- [Azure NDm H100 v5-series](https://learn.microsoft.com/en-us/azure/virtual-machines/nd-h100-v5-series) - GPU instances powerd by NVIDIA H100 GPUs on Azure.
- [Azure NDm A100 v4-series](https://learn.microsoft.com/en-us/azure/virtual-machines/ndm-a100-v4-series) - GPU instances powerd by NVIDIA A100(80Gb) GPUs and 3rd Generation AMD EPYC processors on Azure.
- [Azure NC A100 v4-series](https://learn.microsoft.com/en-us/azure/virtual-machines/nc-a100-v4-series) - GPU instances powerd by NVIDIA A100(40Gb) GPUs and 3rd Generation AMD EPYC processors on Azure.
- [Azure NCv3-series](https://learn.microsoft.com/en-us/azure/virtual-machines/ncv3-series) - GPU instances powerd by NVIDIA V100 GPUs on Azure.
- [Azure NCasT4_v3-series](https://learn.microsoft.com/en-us/azure/virtual-machines/nct4-v3-series) - GPU instances powerd by NVIDIA T4 GPUs and 2nd Gen AMD EPYC CPUs on Azure.
- [GCP H3 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#h3_series) - CPU instances powerd by 4th Generation Intel Xeon Scalable processors on GCP.
- [GCP C2D machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#c2d_series) - CPU instances powerd by 3rd Generation AMD EPYC processors on GCP.
- [GCP C2 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#c2_series) - CPU instances powerd by 2nd Geration Intel Xeon Scalable processors on GCP.
- [GCP A3 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#a3_series) - GPU instances powerd by NVIDIA H100 GPUs on GCP.
- [GCP A2 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#a2_series) - GPU instances powerd by NVIDIA A100(80Gb,40Gb) GPUs on GCP.
- [GCP G2 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#h3_series) - GPU instances powerd by NVIDIA L4 GPUs on GCP.

 
## CSP - IaaS(Network)

- [Elastic Fabric Adapter](https://aws.amazon.com/hpc/efa/) - Network interface for Amazon EC2 instances that enables customers to run applications requiring high levels of inter-node communications at scale on AWS.
- [Azure InfiBand](https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/enable-infiniband)

## CSP - IaaS(Storage)
- [Amazon FSx for Lustre](https://aws.amazon.com/fsx/lustre/) - Fully managed shared storage with the scalability and performance of the popular Lustre file system on AWS.
- [Amazon FSx for OpenZFS](https://aws.amazon.com/fsx/openzfs/) - Fully managed shared storage built on the popular OpenZFS file system.
- [Azure NetApp Files](https://azure.microsoft.com/en-us/products/netapp/)
- [Azure HPC Cache](https://azure.microsoft.com/en-us/products/hpc-cache)
- [Azure Managed Lustre](https://azure.microsoft.com/en-us/products/managed-lustre) - Managed, pay-as-you-go file system for high-performance computing (HPC) and AI workloads on Azure.
- [GCP Parallel Store](https://cloud.google.com/parallelstore) - Based on Intel DAOS and delivers up to 6.3x greater read throughput performance compared to competitive Lustre scratch offerings.
- [GCP File Store](https://cloud.google.com/filestore) - High-performance, fully managed file storage on GCP.

## CSP - IaaS(etc.)
- [GCP HPC-ready VM](https://cloud.google.com/compute/docs/instances/create-hpc-vm) - CentOS 7.9 or Rocky Linux 8 based VM image that is optimized for tightly coupled HPC workloads.
- [OCI Compute Clusters](https://docs.oracle.com/en-us/iaas/Content/Compute/Tasks/compute-clusters.htm) - Group of high performance computing (HPC), GPU, or optimized instances that are connected with a high-bandwidth, ultra low-latency network. 
- [Openflight Flight Solo](https://www.openflighthpc.org/latest/docs/flight-solo/) - HPC-ready, platform-agnostic image approach to deploying HPC resources.

## CSP - PaaS 

- [AWS Batch](https://aws.amazon.com/batch/) - Fully managed batch computing service on AWS.
- [Azure Batch](https://azure.microsoft.com/en-us/products/batch/) - Cloud-scale job scheduling and compute management.
- [NICE EnginFrame](https://aws.amazon.com/hpc/enginframe/) - Unified interface to submit jobs for both on-premises and cloud workflow.
- [Research and Engineering Studio](https://aws.amazon.com/hpc/res/) - Open source, easy-to-use web-based portal for administrators to create and manage secure cloud-based research and engineering environments on AWS.
- [GCP Batch](https://cloud.google.com/batch/) - Fully managed batch service to schedule, queue, and execute batch jobs on Google's infrastructure.

## Platform

- [NICE DCV](https://aws.amazon.com/ko/hpc/dcv/) - High-performance remote display protocol that provides customers with a secure way to deliver remote desktops and application streaming.
- [CloudyCluster](https://cloudycluster.com) - Turn-Key Cloud HPC elastic orchestration with a familiar hpc look and feel.
- [Rntier Cloud](https://www.rntiercloud.com)
- [Openflight Flight Environment](https://www.openflighthpc.org/latest/docs/flight-environment/)  
- [Covalent](https://www.covalent.xyz) - Pythonic workflow orchestration platform for scaling workloads from your laptop to any compute backend.
- [Skypilot](https://skypilot.readthedocs.io) - Framework for running LLMs, AI, and batch jobs on any cloud, offering maximum cost savings, highest GPU availability, and managed execution.


## CAE,EDA ISV

- [Ansys Cloud Direct](https://www.ansys.com/products/cloud/ansys-cloud) - On-demand, cloud-based computing resources, including both interactive workstations and HPC clusters.
- [Ansys Gateway](https://www.ansys.com/products/cloud/ansys-gateway) - Solution for developers, designers, and engineers who want to manage their complete Ansys Simulation & CAD/CAE developments in the cloud.
- [Simcenter Cloud HPC](https://plm.sw.siemens.com/en-US/simcenter/integration-solutions/cloud-hpc) 
- [Synopsys Cloud](https://www.synopsys.com/cloud.html)
- [Cadence Manged Cloud Service](https://www.cadence.com/en_US/home/solutions/cadence-cloud/managed-cloud-service.html) - EDA-optimized platform that provides a fully integrated and proven cloud environment to jump-start product design, verification, and implementation.
- [Cadence Palladium and Protium Cloud](https://www.cadence.com/en_US/home/solutions/cadence-cloud/palladium-protium-cloud.html)
- [Cadence OnCloud Platform](https://www.cadence.com/en_US/home/solutions/cadence-cloud/oncloud.html) - SaaS software platform for all your system design and simulation needs that can operate on any hardware, removing the requirement to run and maintain expensive infrastructure hardware.
- [Altair One](https://altair.com/altair-one) 
- [Altair Unlimited](https://altair.com/altair-unlimited)
- [Altair Unlimited Virtual Appliance](https://altair.com/altair-unlimited-virtual-appliance)
- [Simulia Cloud](https://www.3ds.com/products-services/simulia/products/simulia-cloud)


## SaaS

- [Rescale](https://rescale.com) - Cloud-based platform for computational engineering and R&D.
- [Nimbix](https://www.nimbix.net)  
- [Gompute](https://www.atnorth.com/hpc/gompute)
- [Uber Cloud](https://www.theubercloud.com)
- [Scala Computing](https://www.scalacomputing.com)
- [TAESUNG Cloud](https://www.etsne.com/CloudService)
- [Simscale](https://www.simscale.com)
- [CFD FEA Service SRL](https://cfdfeaservice.it)
- [PACE on Cloud](https://landing.pace-on-cloud.com)
- [Sabalcore](https://www.sabalcore.com)

## Job Scheduler

- [Altair HPCWorks Platform](https://altair.com/altair-hpcworks) - High-Performance Computing (HPC) and Cloud Platform by Altair.
- [Altair Access](https://altair.com/access) - HPC Job Submission Portal for Researchers and Engineers.
- [Altair Control](https://altair.com/control) - HPC Administrator's Control Center for Managing, Optimizing, and Forecasting Resources.
- [Altair NavOps](https://altair.com/altair-navops) - Cloud Migration, Automation, and Spend Management for HPC.
- [Altair Grid Engine](https://altair.com/grid-engine) - Distributed Resource Management and Optimization.
- [Altair PBS-Professional](https://altair.com/pbs-professional) - Industry-leading Workload Manager and Job Scheduler for HPC and High-throughput Computing.
- [IBM LSF Suite](https://www.ibm.com/products/hpc-workload-management)
- [Slurm Cloud Computing](https://slurm.schedmd.com/elastic_computing.html)
- [MS HPC Pack](https://learn.microsoft.com/en-us/powershell/high-performance-computing/overview?view=hpc19-ps) 

## Blog, Documentation, YouTube

- [AWS HPC Blog](https://aws.amazon.com/blogs/hpc/)
- [Day 1 HPC](https://day1hpc.com) - AWS engineering's hpc communutiy site.
- [HPC Tech Shorts](https://www.youtube.com/channel/UChSIn5kcWQvJxW17KIjdLVw) - Day 1 HPC YouTube Channel.
- [Azure High Performance Computing (HPC) Blog](https://techcommunity.microsoft.com/t5/azure-high-performance-computing/bg-p/AzureHighPerformanceComputingBlog)


## Repository

- [AWS Parallel Cluster UI](https://github.com/aws/aws-parallelcluster-ui) - Front-end for AWS ParallelCluster.
- [Azure HPC](https://github.com/Azure/azurehpc) - Easy automation scripts for building a HPC environment in Azure.
- [Azhpc-images](https://github.com/Azure/azhpc-images) - Installation scripts for HPC images in Azure Marketplace, specifically CentOS-HPC, Ubuntu-HPC, and AlmaLinux-HPC.

### Azure Cyclecloud
- [Azure CycleCloud Slurm](https://github.com/Azure/cyclecloud-slurm)
- [Azure CycleCloud PBSPro](https://github.com/Azure/cyclecloud-pbspro)
- [Azure CycleCloud LSF](https://github.com/Azure/cyclecloud-lsf)
- [Azure CyclcCloud Beegfs](https://github.com/Azure/cyclecloud-beegfs)
- [Azure CycleCloud Symphony](https://github.com/Azure/cyclecloud-symphony)
- [Azure CycleCloud GridEngine](https://github.com/Azure/cyclecloud-gridengine)
- [Azure CycleCloud HPC Pack](https://github.com/Azure/cyclecloud-hpcpack)
- [Azure CycleCloud Autoscaling Library](https://github.com/Azure/cyclecloud-scalelib)


