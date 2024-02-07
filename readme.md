
# Awesome Cloud HPC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

A curated list of cloud HPC.

## Contents

- [CSP-Solution](#CSP-Solution)
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

## CSP-Solution

- [Amazon Web Services](https://aws.amazon.com/hpc/)
- [Microsoft Azure](https://azure.microsoft.com/en-us/solutions/high-performance-computing)
- [Google GCP](https://cloud.google.com/solutions/hpc)
- [Oracle OCI](https://www.oracle.com/cloud/hpc/)
- [Naver NCP](https://www.ncloud.com/solution/type/hpc)
- [Samsung SDS SCP](https://cloud.samsungsds.com/serviceportal/offerings/hpc.html)

## Management Tool

- [AWS ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/) - Open source cluster management tool for deploying and managing HPC clusters ([Repository](https://github.com/aws/aws-parallelcluster)).
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure CycleCloud](https://learn.microsoft.com/en-us/azure/cyclecloud/) - Secure and flexible cloud HPC and Big Compute environments.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HPC OnDemand Platform](https://azure.github.io/az-hop/) - Azure-based HPC cluster solution with features like Terraform, Ansible, Packer integration, job scheduling, autoscaling, and monitoring ([Repository](https://github.com/Azure/az-hop), [Marketplace](https://azuremarketplace.microsoft.com/marketplace/apps/azhpc.azhop)).
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP HPC Toolkit](https://cloud.google.com/hpc-toolkit) - Google Cloud's open-source software for deploying high-performance computing environments on GCP, featuring customizable Terraform modules and Packer integration. ([Repository](https://github.com/GoogleCloudPlatform/hpc-toolkit)).
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Alibaba E-HPC](https://www.alibabacloud.com/product/ehpc) - Alibaba Cloud's computing service for resource management, job submission, performance analysis, and VNC in E-HPC console.
<a href="#"><img src="https://img.shields.io/badge/Alibaba_Cloud-FF6A00?style=flat&logo=alibabacloud&logoColor=white" alt="alibaba cloud" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [OCI HPC Cluster](https://cloudmarketplace.oracle.com/marketplace/listing/67628143) - Automated HPC cluster deployment on OCI.
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [OCI HPC File System (HFS)](https://cloudmarketplace.oracle.com/marketplace/listing/75560175) - Solution for deploying various HPC file servers on OCI. Automated HPC cluster deployment on OCI.
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a> 
- [KT Cloud HPC](https://cloud.kt.com/product/productDetail?prodId=P000000015) - KT Cloud's HPC management product integrating Altair's solutions.
- [SCP HPC Cluster](https://www.samsungsds.com/en/compute-hpccluster/hpccluster.html) - HPC cluster environment on SCP.
- [CloudyCluster](https://cloudycluster.com) - Turn-Key Cloud HPC elastic orchestration with a familiar hpc look and feel.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>


## IaaS-Server 

- [Amazon EC2 Hpc7g](https://aws.amazon.com/ec2/instance-types/hpc7g/) - HPC-optimized instances powered by AWS Graviton3E processors.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 Hpc7a](https://aws.amazon.com/ec2/instance-types/hpc7a/) - HPC-optimized instances powered by 4th Generation AMD EPYC processors.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 Hpc6id](https://aws.amazon.com/ec2/instance-types/hpc6i/) - HPC-optimized instances powered by 3rd Generation Intel Xeon Scalable processors.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 P5](https://aws.amazon.com/ec2/instance-types/p5/) -  GPU instances powerd by NVIDIA H100 GPUs.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 P4](https://aws.amazon.com/ec2/instance-types/p4/) -  GPU instances powerd by NVIDIA A100(80Gb,40Gb) GPUs.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 P3](https://aws.amazon.com/ec2/instance-types/p3/) -  GPU instances powerd by NVIDIA V100 GPUs.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon EC2 G5](https://aws.amazon.com/ec2/instance-types/g5/) -  GPU instances powerd by NVIDIA A10G GPUs and 2nd Gen AMD EPYC processors.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HBv4-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hbv4-series) - HPC-optimized instances powered by 4th Generation AMD EPYC processors.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HBv3-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hbv3-series) - HPC-optimized instances powered by 3rd Generation AMD EPYC processors.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HBv2-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hbv2-series) - HPC-optimized instances powered by 2nd Generation AMD EPYC processors.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HB-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hb-series) - HPC-optimized instances powered by 1st Generation AMD EPYC processors.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HC-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hc-series) - HPC-optimized instances powered by 1st Generation Intel Xeon Scalable processors.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HX-series](https://learn.microsoft.com/en-us/azure/virtual-machines/hx-series) - Optimized instances for workloads that require significant memory capacity with twice the memory capacity as HBv4.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NDm H100 v5-series](https://learn.microsoft.com/en-us/azure/virtual-machines/nd-h100-v5-series) - GPU instances powerd by NVIDIA H100 GPUs.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NDm A100 v4-series](https://learn.microsoft.com/en-us/azure/virtual-machines/ndm-a100-v4-series) - GPU instances powerd by NVIDIA A100(80Gb) GPUs and 3rd Generation AMD EPYC processors.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NC A100 v4-series](https://learn.microsoft.com/en-us/azure/virtual-machines/nc-a100-v4-series) - GPU instances powerd by NVIDIA A100(40Gb) GPUs and 3rd Generation AMD EPYC processors.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NCv3-series](https://learn.microsoft.com/en-us/azure/virtual-machines/ncv3-series) - GPU instances powerd by NVIDIA V100 GPUs.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NCasT4_v3-series](https://learn.microsoft.com/en-us/azure/virtual-machines/nct4-v3-series) - GPU instances powerd by NVIDIA T4 GPUs and 2nd Gen AMD EPYC CPUs.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP H3 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#h3_series) - CPU instances powerd by 4th Generation Intel Xeon Scalable processors.
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP C2D machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#c2d_series) - CPU instances powerd by 3rd Generation AMD EPYC processors.
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP C2 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#c2_series) - CPU instances powerd by 2nd Geration Intel Xeon Scalable processors.
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP A3 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#a3_series) - GPU instances powerd by NVIDIA H100 GPUs.
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP A2 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#a2_series) - GPU instances powerd by NVIDIA A100(80Gb,40Gb) GPUs.
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP G2 machine-series](https://cloud.google.com/compute/docs/compute-optimized-machines#h3_series) - GPU instances powerd by NVIDIA L4 GPUs.
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

 
## IaaS-Network

- [Elastic Fabric Adapter](https://aws.amazon.com/hpc/efa/) - Network interface for Amazon EC2 instances that enables customers to run applications requiring high levels of inter-node communications at scale.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertial-align:top margin: 0 6px;"></a>
- [Azure InfiniBand](https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/enable-infiniband) - RDMA capable HB-series and N-series VMs communicate over the InfiniBand network.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

## IaaS-Storage
- [Amazon FSx for Lustre](https://aws.amazon.com/fsx/lustre/) - Fully managed shared storage with the scalability and performance of the popular Lustre file system.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Amazon FSx for OpenZFS](https://aws.amazon.com/fsx/openzfs/) - Fully managed shared storage built on the popular OpenZFS file system.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure NetApp Files](https://azure.microsoft.com/en-us/products/netapp/) - Enterprise-grade Azure file shares, powered by NetApp.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HPC Cache](https://azure.microsoft.com/en-us/products/hpc-cache) File caching for HPC.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure Managed Lustre](https://azure.microsoft.com/en-us/products/managed-lustre) - Managed, pay-as-you-go file system for high-performance computing (HPC) and AI workloads.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP Parallel Store](https://cloud.google.com/parallelstore) - Based on Intel DAOS and delivers up to 6.3x greater read throughput performance compared to competitive Lustre scratch offerings.
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP File Store](https://cloud.google.com/filestore) - High-performance, fully managed file storage.
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

## IaaS-Image
- [GCP HPC-ready VM](https://cloud.google.com/compute/docs/instances/create-hpc-vm) - CentOS 7.9 or Rocky Linux 8 based VM image that is optimized for tightly coupled HPC workloads [Marketplace CentOS 7](https://console.cloud.google.com/marketplace/product/click-to-deploy-images/hpc-vm-image-centos-7) [Marketplace Rocky Linux 8](https://console.cloud.google.com/marketplace/product/click-to-deploy-images/hpc-vm-image-rocky-linux-8?q=search&referrer=search).
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Flight Solo](https://www.openflighthpc.org/latest/docs/flight-solo/) - HPC-ready, platform-agnostic image approach to deploying HPC resources powerd by alcesflight.
<a href="https://aws.amazon.com/marketplace/pp/prodview-q5u533n6b34oc?sr=0-3&ref_=beagle&applicationId=AWSMPContessa"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/Openstack-%23f01742.svg?style=flat&logo=openstack&logoColor=white" alt="openstack" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [HPC Pack 2019](https://cloudinfrastructureservices.co.uk/how-to-setup-hpc-pack-2019-cluster-in-azure-aws-gcp/)(Cloud Infrastructure Services) -  Microsoft HPC Pack 2019 image powered by Cloud Infrastructure Services ([Marketplace(Azure)](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/cloud-infrastructure-services.hpc2019-windows-server-2019), [Marketplace(AWS)](https://aws.amazon.com/marketplace/pp/prodview-hxo3dtqd4srdk), [Marketplace(GCP)](https://console.cloud.google.com/marketplace/product/cloud-infrastructure-services/hpc2019-windows-2019)).
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>


## PaaS 

- [AWS Batch](https://aws.amazon.com/batch/) - Fully managed batch computing service.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure Batch](https://azure.microsoft.com/en-us/products/batch/) - Cloud-scale job scheduling and compute management.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [GCP Batch](https://cloud.google.com/batch/) - Fully managed batch service to schedule, queue, and execute batch jobs on Google's infrastructure.
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [NICE EnginFrame](https://aws.amazon.com/hpc/enginframe/) - Unified interface to submit jobs for both on-premises and cloud workflow.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Research and Engineering Studio](https://aws.amazon.com/hpc/res/) - Open source, easy-to-use web-based portal for administrators to create and manage secure cloud-based research and engineering environments on AWS.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [NICE DCV](https://aws.amazon.com/ko/hpc/dcv/) - High-performance remote display protocol that provides customers with a secure way to deliver remote desktops and application streaming.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Rntier Cloud](https://www.rntiercloud.com) - R&D cloud platform enabling easy and quick access to complex HPC simulations, vGPU-based remote 3D design, and multi-GPU deep learning environments via a web browser.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a> `NCP`
- [Covalent](https://www.covalent.xyz) - Pythonic workflow orchestration platform for scaling workloads from your laptop to any compute backend ([Repository](https://github.com/AgnostiqHQ/covalent)).
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Skypilot](https://skypilot.readthedocs.io) - Framework for running LLMs, AI, and batch jobs on any cloud, offering maximum cost savings, highest GPU availability, and managed execution ([Repository](https://github.com/skypilot-org/skypilot)).
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
`IBM Cloud` `SCP`

## SaaS

- [Rescale](https://rescale.com) - Hybrid-cloud platform offering turnkey HPC with extensive(1000+) ecosystem integrations and API connections to major PLM, SPDM, and data storage systems([Repository](https://github.com/rescale)).
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
`NCP`
- [Nimbix](https://www.nimbix.net) - A comprehensive cloud computing solution powered by Atos, offering access to the HyperHub Application Marketplace with over 1,000 high-performance applications and workflows for diverse industries ([Repository](https://github.com/nimbix)).
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=black" alt="oci" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Uber Cloud](https://www.theubercloud.com) - A platform featuring HD 3D graphics desktop GUI, BYOL simulation software support, scalable container-based architecture, and automated cloud computing on AWS, Azure, Google, and HPE.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
<a href="#"><img src="svg/dev/services/gcp.svg" alt="gcp" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Scala Computing](https://www.scalacomputing.com) - Optimized, automated cloud-based HPC resource management platform with integrated network simulation and EDA tools, offering flexible, on-demand computing, secure workflows, and global infrastructure access.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [TAESUNG Cloud](https://www.tscloud.co.kr/CloudService) - Offering Ansys applications as a service in a cloud-based SaaS.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Gompute](https://www.atnorth.com/hpc/gompute)
- [Simscale](https://www.simscale.com)
- [CFD FEA Service SRL](https://cfdfeaservice.it)
- [PACE on Cloud](https://landing.pace-on-cloud.com)
- [Sabalcore](https://www.sabalcore.com)

## CAE and EDA ISV

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

## Blog Documentation YouTube

- [AWS HPC Blog](https://aws.amazon.com/blogs/hpc/)
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Day 1 HPC](https://day1hpc.com) - AWS engineering's hpc communutiy site.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [HPC Tech Shorts](https://www.youtube.com/channel/UChSIn5kcWQvJxW17KIjdLVw) - Day 1 HPC YouTube Channel.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure High Performance Computing (HPC) Blog](https://techcommunity.microsoft.com/t5/azure-high-performance-computing/bg-p/AzureHighPerformanceComputingBlog)
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>


## Repository

- [AWS Parallel Cluster UI](https://github.com/aws/aws-parallelcluster-ui) - Front-end for AWS ParallelCluster.
<a href="#"><img src="svg/dev/services/aws.svg" alt="aws" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azure HPC](https://github.com/Azure/azurehpc) - Easy automation scripts for building a HPC environment in Azure.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>
- [Azhpc-images](https://github.com/Azure/azhpc-images) - Installation scripts for HPC images in Azure Marketplace, specifically CentOS-HPC, Ubuntu-HPC, and AlmaLinux-HPC.
<a href="#"><img src="svg/dev/services/azure.svg" alt="azure" height="20px" style="vertical-align:bottom; margin: 0 6px;"></a>

### Azure Cyclecloud
- [Azure CycleCloud Slurm](https://github.com/Azure/cyclecloud-slurm)
- [Azure CycleCloud PBSPro](https://github.com/Azure/cyclecloud-pbspro)
- [Azure CycleCloud LSF](https://github.com/Azure/cyclecloud-lsf)
- [Azure CyclcCloud Beegfs](https://github.com/Azure/cyclecloud-beegfs)
- [Azure CycleCloud Symphony](https://github.com/Azure/cyclecloud-symphony)
- [Azure CycleCloud GridEngine](https://github.com/Azure/cyclecloud-gridengine)
- [Azure CycleCloud HPC Pack](https://github.com/Azure/cyclecloud-hpcpack)
- [Azure CycleCloud Autoscaling Library](https://github.com/Azure/cyclecloud-scalelib)


