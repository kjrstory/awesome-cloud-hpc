
# Awesome Cloud HPC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

A curated list of cloud HPC.

## Contents

- [Solution](#CSP-Solution)
- [Management Tool](#Management-Tool)
- [IaaS-Server](#IaaS-Server)
- [IaaS-Network](#IaaS-Network)
- [IaaS-Storage](#IaaS-Storage)
- [IaaS-Image](#IaaS-Image)
- [PaaS](#PaaS)
- [CAE and EDA ISV](#CAE-and-EDA-ISV)
- [SaaS](#SaaS)
- [Job Scheduler](#Job-Scheduler)
- [Blog, Documentation, YouTube](#Blog-Documentation-YouTube)
- [Repository](#Repository)

## Solution

- [Amazon Web Services](https://aws.amazon.com/hpc/)
- [Google GCP](https://cloud.google.com/solutions/hpc)
- [HUAWEI Cloud](https://www.huaweicloud.com/intl/en-us/solution/highperformance/)
- [IBM Cloud](https://www.ibm.com/high-performance-computing)
- [Microsoft Azure](https://azure.microsoft.com/en-us/solutions/high-performance-computing)
- [Naver NCP](https://www.ncloud.com/solution/type/hpc)
- [Oracle OCI](https://www.oracle.com/cloud/hpc/)
- [Samsung SDS SCP](https://cloud.samsungsds.com/serviceportal/offerings/hpc.html)

## Management Tool

- [Alibaba E-HPC](https://www.alibabacloud.com/product/ehpc) - Alibaba Cloud's computing service for resource management, job submission, performance analysis, and VNC in E-HPC console.
<a href="#"><img src="https://img.shields.io/badge/Alibaba_Cloud-FF6A00?style=flat&logo=alibabacloud&logoColor=white" alt="alibaba cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [AWS ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/) - Open source cluster management tool for deploying and managing HPC clusters ([Repository](https://github.com/aws/aws-parallelcluster)).
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [AWS Parallel Cluster UI](https://github.com/aws/aws-parallelcluster-ui) - Front-end for AWS ParallelCluster.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure CycleCloud](https://learn.microsoft.com/en-us/azure/cyclecloud/) - Secure and flexible cloud HPC and Big Compute environments.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HPC OnDemand Platform](https://azure.github.io/az-hop/) - Azure-based HPC cluster solution with features like Terraform, Ansible, Packer integration, job scheduling, autoscaling, and monitoring ([Repository](https://github.com/Azure/az-hop), [Marketplace](https://azuremarketplace.microsoft.com/marketplace/apps/azhpc.azhop)).
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [CloudyCluster](https://cloudycluster.com) - Turn-Key Cloud HPC elastic orchestration with a familiar hpc look and feel.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Cluster Toolkit](https://cloud.google.com/cluster-toolkit) - Google Cloud's open-source software for deploying AI/ML and high-performance computing environments on GCP, featuring customizable Terraform modules and Packer integration. ([Repository](https://github.com/GoogleCloudPlatform/cluster-toolkit)).
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Flight Environment](https://www.openflighthpc.org/latest/docs/flight-environment/) - The Flight User Suite for improved HPC access through CLI tools, the Flight Web Suite as a web interface for HPC end-users, and the Flight Admin Tools for administrative HPC environment configuration.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Openstack-%23f01742.svg?style=flat&logo=openstack&logoColor=white" alt="openstack" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [HPC-NOW](https://github.com/zhenrong-wang/hpc-now) - The platform aims to simplify the process of starting and managing HPC workloads in the cloud.
<a href="#"><img src="https://img.shields.io/badge/Alibaba_Cloud-FF6A00?style=flat&logo=alibabacloud&logoColor=white" alt="alibaba cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Tencent_Cloud-3399ff?style=flat" alt="tencent cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/HUAWEI_CLOUD-FF0000?style=flat&logo=huawei&logoColor=white" alt="HUAWEI CLOUD" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Baidu Cloud-0080ff?style=flat" alt="Baidu Cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [JedAI Cloud](https://define-technology.com/jedai-cloud/) - Optimized HPC stacks enable easy cluster management and on-demand HPC through pre-integrated solutions, delivering bare metal infrastructure, virtualized services, and containerized apps via a single management interface by Define Tech.

- [KT Cloud HPC](https://cloud.kt.com/product/productDetail?prodId=P000000015) - KT Cloud's HPC management product integrating Altair's solutions.
<a href="#"><img src="https://img.shields.io/badge/kt_cloud-ff1a1a?style=flat" alt="kt cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Microsoft HPC Pack](https://learn.microsoft.com/en-us/powershell/high-performance-computing) - Creation and management tool of HPC clusters, enabling the use of Windows or Linux nodes on-premises and cloud resources in Azure.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [OCI HPC Cluster](https://cloudmarketplace.oracle.com/marketplace/listing/67628143) - Automated HPC cluster deployment on OCI.
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [OCI HPC File System (HFS)](https://cloudmarketplace.oracle.com/marketplace/listing/75560175) - Solution for deploying various HPC file servers on OCI. Automated HPC cluster deployment on OCI.
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a> 

- [SCP HPC Cluster](https://www.samsungsds.com/en/compute-hpccluster/hpccluster.html) - HPC cluster environment on SCP.
<a href="#"><img src="https://img.shields.io/badge/SCP-0066ff?style=flat" alt="scp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Scyld Cloud Manager](https://www.penguinsolutions.com/products/software/scyld-cloud-manager) - Comprehensive management platform to cloud-enable Enterprise HPC.


## IaaS-Server 

- [Amazon EC2 Hpc7g](https://aws.amazon.com/ec2/instance-types/hpc7g/) - HPC-optimized instances powered by AWS Graviton3E processors.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 Hpc7a](https://aws.amazon.com/ec2/instance-types/hpc7a/) - HPC-optimized instances powered by 4th Generation AMD EPYC processors.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 Hpc6id](https://aws.amazon.com/ec2/instance-types/hpc6i/) - HPC-optimized instances powered by 3rd Generation Intel Xeon Scalable processors.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 P5](https://aws.amazon.com/ec2/instance-types/p5/) -  GPU instances powerd by NVIDIA H100 GPUs.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 P4](https://aws.amazon.com/ec2/instance-types/p4/) -  GPU instances powerd by NVIDIA A100(80Gb,40Gb) GPUs.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 P3](https://aws.amazon.com/ec2/instance-types/p3/) -  GPU instances powerd by NVIDIA V100 GPUs.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 G5](https://aws.amazon.com/ec2/instance-types/g5/) -  GPU instances powerd by NVIDIA A10G GPUs and 2nd Gen AMD EPYC processors.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HBv4-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hbv4-series) - HPC-optimized instances powered by 4th Generation AMD EPYC processors.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HBv3-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hbv3-series) - HPC-optimized instances powered by 3rd Generation AMD EPYC processors.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HBv2-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hbv2-series) - HPC-optimized instances powered by 2nd Generation AMD EPYC processors.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HB-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hb-series) - HPC-optimized instances powered by 1st Generation AMD EPYC processors.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HC-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hc-series) - HPC-optimized instances powered by 1st Generation Intel Xeon Scalable processors.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HX-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hx-series) - Optimized instances for workloads that require significant memory capacity with twice the memory capacity as HBv4.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NDm H100 v5-series](https://learn.microsoft.com/en-us/azure/virtual-machines/nd-h100-v5-series) - GPU instances powerd by NVIDIA H100 GPUs.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NDm A100 v4-series](https://learn.microsoft.com/en-us/azure/virtual-machines/ndm-a100-v4-series) - GPU instances powerd by NVIDIA A100(80Gb) GPUs and 3rd Generation AMD EPYC processors.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NC A100 v4-series](https://learn.microsoft.com/en-us/azure/virtual-machines/nc-a100-v4-series) - GPU instances powerd by NVIDIA A100(40Gb) GPUs and 3rd Generation AMD EPYC processors.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NCv3-series](https://learn.microsoft.com/en-us/azure/virtual-machines/ncv3-series) - GPU instances powerd by NVIDIA V100 GPUs.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NCasT4_v3-series](https://learn.microsoft.com/en-us/azure/virtual-machines/nct4-v3-series) - GPU instances powerd by NVIDIA T4 GPUs and 2nd Gen AMD EPYC CPUs.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP H3 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#h3_series) - CPU instances powerd by 4th Generation Intel Xeon Scalable processors.
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP C2D machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#c2d_series) - CPU instances powerd by 3rd Generation AMD EPYC processors.
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP C2 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#c2_series) - CPU instances powerd by 2nd Geration Intel Xeon Scalable processors.
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP A3 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#a3_series) - GPU instances powerd by NVIDIA H100 GPUs.
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP A2 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#a2_series) - GPU instances powerd by NVIDIA A100(80Gb,40Gb) GPUs.
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP G2 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#h3_series) - GPU instances powerd by NVIDIA L4 GPUs.
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Super Computing Cluster](https://www.alibabacloud.com/en/product/scc) - Based on ECS Bare Metal Instance powered by Alibaba Cloud, utilizes high-speed RDMA-based connections to enhance network performance and acceleration ratio in large-scale clusters, providing high-bandwidth and low-latency networks.
<a href="#"><img src="https://img.shields.io/badge/Alibaba_Cloud-FF6A00?style=flat&logo=alibabacloud&logoColor=white" alt="alibaba cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

## IaaS-Network

- [Azure InfiniBand](https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/enable-infiniband) - RDMA capable HB-series and N-series VMs communicate over the InfiniBand network.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Compute Clusters](https://docs.oracle.com/en-us/iaas/Content/Compute/Tasks/compute-clusters.htm)([Cluster Networks with Instance Pools](https://docs.oracle.com/en-us/iaas/Content/Compute/Tasks/managingclusternetworks.htm)) - Group of high performance computing (HPC), GPU, or optimized instances that are connected with a high-bandwidth, ultra low-latency network. <a href="#"> <img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black"> </a>

- [Elastic Fabric Adapter](https://aws.amazon.com/hpc/efa/) - Network interface for Amazon EC2 instances that enables customers to run applications requiring high levels of inter-node communications at scale.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertial-align:top margin: 0 6px;"></a>

## IaaS-Storage

- [Amazon FSx for Lustre](https://aws.amazon.com/fsx/lustre/) - Fully managed shared storage with the scalability and performance of the popular Lustre file system.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon FSx for OpenZFS](https://aws.amazon.com/fsx/openzfs/) - Fully managed shared storage built on the popular OpenZFS file system.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HPC Cache](https://azure.microsoft.com/en-us/products/hpc-cache) File caching for HPC on Azure.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure Managed Lustre](https://azure.microsoft.com/en-us/products/managed-lustre) - Managed, pay-as-you-go file system for high-performance computing (HPC) and AI workloads.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NetApp Files](https://azure.microsoft.com/en-us/products/netapp/) - Enterprise-grade Azure file shares, powered by NetApp.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP File Store](https://cloud.google.com/filestore) - High-performance, fully managed file storage.
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP Parallel Store](https://cloud.google.com/parallelstore) - Based on Intel DAOS and delivers up to 6.3x greater read throughput performance compared to competitive Lustre scratch offerings.
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

## IaaS-Image

- [Azhpc-images](https://github.com/Azure/azhpc-images) - Installation scripts for HPC images in Azure Marketplace, specifically CentOS-HPC, Ubuntu-HPC, and AlmaLinux-HPC.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Flight Solo](https://www.openflighthpc.org/latest/docs/flight-solo/) - HPC-ready, platform-agnostic image approach to deploying HPC resources powerd by alcesflight.
<a href="https://aws.amazon.com/marketplace/pp/prodview-q5u533n6b34oc?sr=0-3&ref_=beagle&applicationId=AWSMPContessa"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Openstack-%23f01742.svg?style=flat&logo=openstack&logoColor=white" alt="openstack" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP HPC-ready VM](https://cloud.google.com/compute/docs/instances/create-hpc-vm) - CentOS 7.9 or Rocky Linux 8 based VM image that is optimized for tightly coupled HPC workloads [Marketplace CentOS 7](https://console.cloud.google.com/marketplace/product/click-to-deploy-images/hpc-vm-image-centos-7) [Marketplace Rocky Linux 8](https://console.cloud.google.com/marketplace/product/click-to-deploy-images/hpc-vm-image-rocky-linux-8?q=search&referrer=search).
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>


- [HPCBOX](https://www.drizti.com/hpcbox.html) - Desktop-centric, intelligent workflow cloud HPC platform for automating and executing your application pipelines ([Marketplace](https://azuremarketplace.microsoft.com/en-us/marketplace/apps?search=hpcbox)).
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>


- [HPC Pack 2019](https://cloudinfrastructureservices.co.uk/how-to-setup-hpc-pack-2019-cluster-in-azure-aws-gcp/)(Cloud Infrastructure Services) -  Microsoft HPC Pack 2019 image powered by Cloud Infrastructure Services ([Marketplace(Azure)](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/cloud-infrastructure-services.hpc2019-windows-server-2019), [Marketplace(AWS)](https://aws.amazon.com/marketplace/pp/prodview-hxo3dtqd4srdk), [Marketplace(GCP)](https://console.cloud.google.com/marketplace/product/cloud-infrastructure-services/hpc2019-windows-2019)).
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [NVIDIA Virtual Machine Images](https://catalog.ngc.nvidia.com/orgs/nvidia/collections/nvidia_vmi) - Operating system environment for running NVIDIA GPU accelerated software in the cloud.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Alibaba_Cloud-FF6A00?style=flat&logo=alibabacloud&logoColor=white" alt="alibaba cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OVHcloud-%23123F6D.svg?style=flat&logo=ovh&logoColor=#123F6D" alt="OVHcloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

## PaaS 

- [AWS Batch](https://aws.amazon.com/batch/) - Fully managed batch computing service.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Batch](https://azure.microsoft.com/en-us/products/batch/)(Azure) - Cloud-scale job scheduling and compute management.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Batch](https://cloud.google.com/batch/)(GCP) - Fully managed batch service to schedule, queue, and execute batch jobs on Google's infrastructure.
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Batch Compute](https://www.alibabacloud.com/ko/product/batch-compute) - Cloud service for massive simultaneous batch processing on Alibaba Cloud.
<a href="#"><img src="https://img.shields.io/badge/Alibaba_Cloud-FF6A00?style=flat&logo=alibabacloud&logoColor=white" alt="alibaba cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Covalent](https://www.covalent.xyz) - Pythonic workflow orchestration platform for scaling workloads from your laptop to any compute backend ([Repository](https://github.com/AgnostiqHQ/covalent)).
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [NICE DCV](https://aws.amazon.com/ko/hpc/dcv/) - High-performance remote display protocol that provides customers with a secure way to deliver remote desktops and application streaming.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [NICE EnginFrame](https://aws.amazon.com/hpc/enginframe/) - Unified interface to submit jobs for both on-premises and cloud workflow.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Research and Engineering Studio](https://aws.amazon.com/hpc/res/) - Open source, easy-to-use web-based portal for administrators to create and manage secure cloud-based research and engineering environments on AWS.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Rntier Cloud](https://www.rntiercloud.com) - R&D cloud platform enabling easy and quick access to complex HPC simulations, vGPU-based remote 3D design, and multi-GPU deep learning environments via a web browser.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/NCP-03cf5d?style=flat" alt="ncp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>


- [Scyld Cloud Central™](https://www.penguinsolutions.com/solutions/cloud/scyld-cloud-central) - Fully managed, cloud-based, end-to-end solution for high performance computing that makes it easier and faster for end-users, developers, and data scientists to deploy pure HPC, pure AI, and converged HPC/AI workloads on high-performance clusters.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Scyld ClusterWare](https://www.penguinsolutions.com/products/software/scyld-clusterware) - Intelligent suite of management functionality, including node provisioning, image customization, and cluster monitoring, while serving as a platform for additional software and schedulers.

- [Scyld Cloud Workstation](https://www.penguinsolutions.com/products/software/scyld-cloud-workstation) - Unparalleled performance and a breadth of features that allow it to stand out as a solution for remote access.

- [Skypilot](https://skypilot.readthedocs.io) - Framework for running LLMs, AI, and batch jobs on any cloud, offering maximum cost savings, highest GPU availability, and managed execution ([Repository](https://github.com/skypilot-org/skypilot)).
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/IBM%20Cloud-1261FE?style=flat&logo=IBM%20Cloud&logoColor=white" alt="ibm cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/SCP-0066ff?style=flat" alt="scp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>



## SaaS

- [CloudHPC](https://cloudhpc.cloud) - On-demand cloud computing for CAE engineering simulations powered by CFD FEA SERVICE.

- [dicehub](https://dicehub.com) - Real-time collaborative CFD (Computational Fluid Dynamics) simulations platform which simplifies your engineering workflow, offers massive parallel scaling and runs in web browser.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [EPIC](https://epic.zenotech.com/) - Primarily for CFD applications, available on the web and created by Zenotech, which also includes Zenotech's ZCFD.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Kaleidosim](https://kaleidosim.com) - Enabling of browser-based access to HPC software through advanced cloud orchestration technology.

- [Luminary Cloud](https://www.luminarycloud.com) - A cloud-based, pay-per-use SaaS simulation platform with a fast, GPU-powered, cloud-native CFD solver and comprehensive high-fidelity capabilities.

- [Nimbix](https://www.nimbix.net) - A comprehensive cloud computing solution powered by Atos, offering access to the HyperHub Application Marketplace with over 1,000 high-performance applications and workflows for diverse industries ([Repository](https://github.com/nimbix)).
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [OnScale Solve](https://onscale.com/solve/features) - The cloud engineering simulation platform built by engineers for engineers.
- [Rescale](https://rescale.com) - Hybrid-cloud platform offering turnkey HPC with extensive(1000+) ecosystem integrations and API connections to major PLM, SPDM, and data storage systems([Repository](https://github.com/rescale)).
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/NCP-03cf5d?style=flat" alt="ncp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Sabalcore](https://www.sabalcore.com) - User-friendly, pay-as-you-go high performance computing cloud service with a full-featured, light-weight client that doesn't require a browser.
- [Scala Computing](https://www.scalacomputing.com) - Optimized, automated cloud-based HPC resource management platform with integrated network simulation and EDA tools, offering flexible, on-demand computing, secure workflows, and global infrastructure access.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Simscale](https://www.simscale.com) - Cloud-based computer-aided engineering (CAE) software for computational fluid dynamics, finite element analysis, and thermal simulations, using open source codes in its backend ([Repository(SDK)](https://github.com/SimScaleGmbH)).

- [SyncHPC](https://www.syncious.com/synchpc.html) - Powerful and flexible hybrid HPC and VDI management platform that provides a comprehensive solution for managing high-performance computing (HPC) and Virtual Desktop Infrastructure (VDI) resources.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/IBM%20Cloud-1261FE?style=flat&logo=IBM%20Cloud&logoColor=white" alt="ibm cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [TAESUNG Cloud](https://www.tscloud.co.kr/CloudService) - Offering Ansys applications as a service in a cloud-based SaaS.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

## CAE and EDA ISV

- [3DEXPERIENCE platform on ther cloud](https://www.3ds.com/cloud) - Complete suite of industry-leading apps and software(CATIA, SIMULIA, DELMIA, 3DEXCITE, etc.) powered by Dassalut Systèmes.
  
- [Altair One](https://altair.com/altair-one) - Cloud Gateway offering dynamic and collaborative access to simulation and data analytics technology, along with scalable HPC and cloud resources.
- [Altair Unlimited](https://altair.com/altair-unlimited) - A turnkey, state-of-the-art private appliance available in both on-premises and cloud-based formats, offering unlimited access to a wide range of Altair HyperWorks solver software.
- [Ansys Cloud Direct](https://www.ansys.com/products/cloud/ansys-cloud) - Cloud-based interactive workstations and HPC clusters, with flexible licensing that can be accessed from desktop.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Ansys Gateway by AWS](https://www.ansys.com/products/cloud/ansys-gateway) - Cloud-based solution for managing Ansys Simulation & CAD/CAE developments via a web browser.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Cadence OnCloud Platform](https://www.cadence.com/en_US/home/solutions/cadence-cloud/oncloud.html) - SaaS software platform for all your system design and simulation needs that can operate on any hardware, removing the requirement to run and maintain expensive infrastructure hardware.

- [Cloud Passport](https://www.cadence.com/en_US/home/solutions/cadence-cloud/cloud-passport.html) - Cloud-ready tools powered by Cadence that have been optimized for use in customers' own cloud environment.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Managed Cloud Service](https://www.cadence.com/en_US/home/solutions/cadence-cloud/managed-cloud-service.html) - EDA-optimized platform powered by Cadence that provides a fully integrated and proven cloud environment to jump-start product design, verification, and implementation.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Palladium and Protium Cloud](https://www.cadence.com/en_US/home/solutions/cadence-cloud/palladium-protium-cloud.html) - Emulation and prototyping offering provides pre-silicon hardware system verification and debug powered by Cadence.

- [Simcenter Cloud HPC](https://plm.sw.siemens.com/en-US/simcenter/integration-solutions/cloud-hpc) - Part of the Xcelerator as a Service(XaaS) offering powered by Siemens, offers increased flexibility and scalability for CFD simulations with no additional setup needed.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Synopsys Cloud](https://www.synopsys.com/cloud.html) - Platform that enables delivery of EDA tools, IP and infrastructure for end-to-end chip design through a browser.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

## Job Scheduler

- [Altair Access](https://altair.com/access) - HPC Job Submission Portal for Researchers and Engineers.
- [Altair Control](https://altair.com/control) - HPC Administrator's Control Center for Managing, Optimizing, and Forecasting Resources with seamless cloud bursting capabilities. 
- [Altair Grid Engine](https://altair.com/grid-engine) - Distributed Resource Management and Optimization.
- [Altair HPCWorks](https://altair.com/altair-hpcworks) - High-Performance Computing (HPC) and Cloud Platform by Altair.
- [Altair NavOps](https://altair.com/altair-navops) - Cloud Migration, Automation, and Spend Management for HPC.
- [Altair PBS-Professional](https://altair.com/pbs-professional) - Industry-leading Workload Manager and Job Scheduler for HPC and High-throughput Computing.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OTC-cc0099?style=flat" alt="Open Telekom Cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/HUAWEI_CLOUD-FF0000?style=flat&logo=huawei&logoColor=white" alt="HUAWEI CLOUD" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Openstack-%23f01742.svg?style=flat&logo=openstack&logoColor=white" alt="openstack" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [IBM Spectrun LSF Suites](https://www.ibm.com/products/hpc-workload-management) - Workload management platform and job scheduler for HPC with dynamic HPC cloud support for all major cloud providers ([Repository](https://github.com/IBM/ibm-spectrum-scale-cloud-install)).
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/IBM%20Cloud-1261FE?style=flat&logo=IBM%20Cloud&logoColor=white" alt="ibm cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Slurm on Google Cloud Platform](https://github.com/GoogleCloudPlatform/slurm-gcp) - Open-source software solution that enables setting up Slurm clusters on Google Cloud Platform with ease.
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Slurm Power Saving Guide](https://slurm.schedmd.com/power_save.html) - Suspending and resuming nodes as needed, and supports cloud integration with providers like AWS, GCP, and Azure for workload management and cloud bursting.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>


## Resource

- [AWS HPC Blog](https://aws.amazon.com/blogs/hpc/)
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure High Performance Computing (HPC) Blog](https://techcommunity.microsoft.com/t5/azure-high-performance-computing/bg-p/AzureHighPerformanceComputingBlog)
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Day 1 HPC](https://day1hpc.com) - AWS engineering's hpc communutiy site.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [GCP HPC Blog](https://cloud.google.com/blog/topics/hpc)
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [HPC Tech Shorts](https://www.youtube.com/channel/UChSIn5kcWQvJxW17KIjdLVw) - Day 1 HPC YouTube Channel.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Oracle Cloud Infrastructure Blog(Performance Solutions)](https://blogs.oracle.com/cloud-infrastructure/category/oci-performance-solutions)
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>


## Recipes

- [Azure HPC](https://github.com/Azure/azurehpc) - Easy automation scripts for building a HPC environment in Azure.
<a href="#"><img src="https://img.shields.io/badge/Azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Cloud MPI](https://github.com/GoogleCloudPlatform/hpc-tools) - Collection of scripts for optimizing MPI performance in tightly coupled HPC workloads on GCP Compute Engines. 
<a href="#"><img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [Dynamic EC2 budget control](https://github.com/aws-samples/dynamic-ec2-budget-control) - Dynamic EC2 cores allocation limit for each business unit (BU), automatically adapted according to a past time frame (e.g. one week) spending on AWS Parallel Cluster.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

- [HPC Recipes for AWS](https://github.com/aws-samples/aws-hpc-recipes) - Example recipes that demonstrate how to build HPC systems using AWS ParallelCluster, Research and Engineering Studio on AWS, and other AWS products.
<a href="#"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>


### Azure CycleCloud
- [Azure CycleCloud Slurm](https://github.com/Azure/cyclecloud-slurm)
- [Azure CycleCloud PBSPro](https://github.com/Azure/cyclecloud-pbspro)
- [Azure CycleCloud LSF](https://github.com/Azure/cyclecloud-lsf)
- [Azure CyclcCloud Beegfs](https://github.com/Azure/cyclecloud-beegfs)
- [Azure CycleCloud Symphony](https://github.com/Azure/cyclecloud-symphony)
- [Azure CycleCloud GridEngine](https://github.com/Azure/cyclecloud-gridengine)
- [Azure CycleCloud HPC Pack](https://github.com/Azure/cyclecloud-hpcpack)
- [Azure CycleCloud Autoscaling Library](https://github.com/Azure/cyclecloud-scalelib)

