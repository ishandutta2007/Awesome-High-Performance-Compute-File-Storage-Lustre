# Awesome-High-Performance-Compute-File-Storage-Lustre

# Awesome-High-Performance-Compute-File-Storage-Lustre ⚡ 🗄️

<p align="center">
  <img src="assets/banner.svg" alt="Awesome High Performance Compute File Storage Lustre Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-High-Performance-Compute-File-Storage-Lustre"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-High-Performance-Compute-File-Storage-Lustre?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-High-Performance-Compute-File-Storage-Lustre/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-High-Performance-Compute-File-Storage-Lustre?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-High-Performance-Compute-File-Storage-Lustre/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-High-Performance-Compute-File-Storage-Lustre?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top High-Performance Compute File Storage (Lustre) Ecosystem

**Curated List of Commercial HPC File Storage Platforms & Open-Source Parallel File Systems**  
*Focused on Lustre, Parallel File Systems, HPC Storage, AI/ML Data Pipelines, Burst Buffer, Multi-Tier Storage & Self-Hosted HPC Storage*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **high-performance compute file storage platforms**, **open-source parallel file systems**, and **Lustre-compatible storage solutions**. Whether you are looking for enterprise-grade commercial solutions (such as *Amazon FSx for Lustre*, *DDN EXAScaler*, and *Weka.io*), or self-hostable open-source alternatives (like *Lustre*, *BeeGFS*, and *OrangeFS*), this list covers category leaders, parallel I/O, and privacy-respecting HPC storage infrastructure.

**Key Market Context:**
- **Lustre** is the **dominant parallel file system for HPC**, powering **60%+ of TOP500 supercomputers** with **hundreds of GB/s throughput** and **petabyte-scale capacity**.
- **Amazon FSx for Lustre** provides **fully managed Lustre** with **sub-millisecond latencies**, **hundreds of GB/s throughput**, and **S3 integration** — no HPC storage expertise required.
- **BeeGFS** is the **leading open-source alternative to Lustre**, with **ease of deployment**, **excellent metadata performance**, and **used by 40% of HPC sites** in Europe.

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The HPC file storage market spans **hyperscaler managed Lustre services** (Amazon FSx for Lustre, Azure Managed Lustre) that provide **fully managed parallel file systems with cloud integration**, **enterprise HPC storage platforms** (DDN EXAScaler, Weka.io, Vast Data) that offer **exascale-class performance and AI/ML optimization**, and **traditional HPC storage vendors** (IBM Spectrum Scale, Panasas, Qumulo) that provide **proven parallel file systems with enterprise support**. **Amazon FSx for Lustre** charges **$0.145/GB-month for SSD** and **$0.025/GB-month for HDD** . **Azure Managed Lustre** charges **$0.25/GiB-month for Premium tier** . **DDN EXAScaler Cloud** uses **custom enterprise pricing** . **Weka.io** charges **$0.10/GB-month for cloud deployment** .

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Amazon FSx for Lustre](https://aws.amazon.com/fsx/lustre/)** ☁️ | Amazon | ~$2.0 Trillion | **$0.145/GB-month** (SSD); **$0.025/GB-month** (HDD)  | **Free tier: limited** | **AWS-native managed Lustre** — **Fully managed parallel file system** . **Sub-millisecond latencies** and **hundreds of GB/s throughput** . **S3 integration for data repositories** . **Scratch and Persistent deployment types** . |
| **[Azure Managed Lustre](https://azure.microsoft.com/en-us/products/managed-lustre/)** 🔷 | Microsoft | ~$3.90 Trillion | **$0.25/GiB-month** (Premium)  | **Free tier: limited** | **Azure-native managed Lustre** — **Fully managed parallel file system** . **High-throughput for HPC and AI workloads** . **Blob Storage integration** . |
| **[DDN EXAScaler Cloud](https://www.ddn.com/)** 🟢 | DDN | Private | **Custom enterprise pricing**  | **Demo available** | **Enterprise Lustre platform** — **Exascale-class performance** . **AI/ML optimization** . **Used by TOP500 supercomputers** . |
| **[Weka.io](https://www.weka.io/)** ⚡ | WekaIO | Private | **$0.10/GB-month** (cloud) | **Free trial available** | **Software-defined parallel file system** — **Hardware-agnostic** . **Scales to hundreds of petabytes** . **10s of millions of IOPS** . **<300 microsecond latency** . |
| **[Panasas ActiveStor](https://www.panasas.com/)** 🔵 | Panasas | Private | **Custom enterprise pricing**  | **Demo available** | **Enterprise HPC storage** — **PanFS parallel file system** . **Proven reliability and performance** . |
| **[IBM Spectrum Scale](https://www.ibm.com/products/spectrum-scale)** 🏢 | IBM | ~$200 Billion | **Custom enterprise pricing**  | **Free trial available** | **Enterprise parallel file system** — **Formerly GPFS** . **Scales to exabytes** . **Multi-protocol support** . |
| **[Vast Data Cloud](https://www.vastdata.com/)** 🌊 | Vast Data | ~$9.1 Billion | **Custom enterprise pricing**  | **Demo available** | **Disaggregated storage architecture** — **All-flash, exabyte-scale** . **AI/ML and HPC optimization** . |
| **[NetApp Cloud Volumes](https://cloud.netapp.com/)** 🔷 | NetApp | ~$20 Billion | **Custom enterprise pricing**  | **30-day free trial**  | **Enterprise NAS in the cloud** — **Full ONTAP feature set** . **Multi-cloud support** . |
| **[Qumulo File Fabric](https://qumulo.com/)** 📊 | Qumulo | Private | **AWS PAYG: $0.0263/TB-hour**  | **Trial available** | **Scale-out file storage** — **Petabyte-scale** with **real-time analytics** . **API-first architecture** . |
| **[Dell PowerScale Cloud](https://www.dell.com/en-us/dt/storage/powerscale.htm)** 🔷 | Dell Technologies | ~$60 Billion | **Custom enterprise pricing**  | **Demo available** | **Enterprise NAS in the cloud** — **OneFS operating system** . **Scales to 100+ PB** . |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[Lustre](https://github.com/lustre/lustre)** [![Stars](https://img.shields.io/github/stars/lustre/lustre?style=social&color=white)](https://github.com/lustre/lustre/stargazers)  
  **The dominant parallel file system for HPC**, GPL-2.0 licensed. **Powers 60%+ of TOP500 supercomputers** — **hundreds of GB/s throughput** and **petabyte-scale capacity** . **Object Storage Targets (OSTs)** for data and **Metadata Targets (MDTs)** for metadata . **Client-side caching and parallel I/O** . **The definitive open-source HPC file system** . ⚡

- **[BeeGFS](https://github.com/ThinkParQ/beegfs)** [![Stars](https://img.shields.io/github/stars/ThinkParQ/beegfs?style=social&color=white)](https://github.com/ThinkParQ/beegfs/stargazers)  
  **The leading open-source alternative to Lustre**, GPL-2.0 licensed. **Ease of deployment and excellent metadata performance** . **Used by 40% of HPC sites in Europe** . **The most accessible open-source parallel file system** . 🐝

- **[OrangeFS](https://github.com/orangefs/orangefs)** [![Stars](https://img.shields.io/github/stars/orangefs/orangefs?style=social&color=white)](https://github.com/orangefs/orangefs/stargazers)  
  **Parallel virtual file system**, LGPL-2.1 licensed. **The open-source continuation of PVFS** . **Scales to petabytes** . **Used in HPC and research environments** . 🍊

- **[Ceph](https://github.com/ceph/ceph)** [![Stars](https://img.shields.io/github/stars/ceph/ceph?style=social&color=white)](https://github.com/ceph/ceph/stargazers)  
  **Unified distributed storage system**, LGPL-2.1 / GPL-2.0 / BSD-3-Clause licensed. **CephFS** provides POSIX-compliant distributed file system . **The dominant open-source storage platform** for cloud infrastructure and Kubernetes (via Rook) . 🐙

- **[GlusterFS](https://github.com/gluster/glusterfs)** [![Stars](https://img.shields.io/github/stars/gluster/glusterfs?style=social&color=white)](https://github.com/gluster/glusterfs/stargazers)  
  **Distributed file system capable of scaling to several petabytes**, GPL-2.0 / LGPL-3.0 licensed. **Aggregates storage bricks over TCP/IP into one large parallel network file system** . **The most widely deployed open-source scale-out NAS solution** . 🧱

- **[DAOS](https://github.com/daos-stack/daos)** [![Stars](https://img.shields.io/github/stars/daos-stack/daos?style=social&color=white)](https://github.com/daos-stack/daos/stargazers)  
  **Exascale-class distributed storage stack**, Apache-2.0 licensed. **Intel-led** — **designed for next-generation HPC and AI workloads** with **NVMe and PMEM support** . **The most advanced open-source exascale storage** . 🔬

- **[MooseFS](https://github.com/moosefs/moosefs)** [![Stars](https://img.shields.io/github/stars/moosefs/moosefs?style=social&color=white)](https://github.com/moosefs/moosefs/stargazers)  
  **Petabyte-scale distributed file system**, GPL-3.0 licensed. **Fault-tolerant, highly performing, scalable network distributed storage** . **POSIX-compliant** . 📦

- **[LizardFS](https://github.com/lizardfs/lizardfs)** [![Stars](https://img.shields.io/github/stars/lizardfs/lizardfs?style=social&color=white)](https://github.com/lizardfs/lizardfs/stargazers)  
  **Open-source distributed file system**, GPL-3.0 licensed. **MooseFS fork** with additional features . **Fault-tolerant with replication** . 🦎

- **[EOS (CERN)](https://github.com/cern-eos/eos)** [![Stars](https://img.shields.io/github/stars/cern-eos/eos?style=social&color=white)](https://github.com/cern-eos/eos/stargazers)  
  **Highly scalable distributed storage system for large amounts of data**, open-source. **Developed at CERN for high-energy physics experiments (LHC)** . **Egress of 1 TB/s** . **The most production-proven exabyte-scale open-source storage system** . 🏛️

- **[OpenZFS](https://github.com/openzfs/zfs)** [![Stars](https://img.shields.io/github/stars/openzfs/zfs?style=social&color=white)](https://github.com/openzfs/zfs/stargazers)  
  **Advanced file system and volume manager**, CDDL-1.0 licensed. **11K+ GitHub stars** — **data integrity, snapshots, and replication** . **The most robust open-source file system for HPC storage** . 🗄️

- **[SeaweedFS](https://github.com/seaweedfs/seaweedfs)** [![Stars](https://img.shields.io/github/stars/seaweedfs/seaweedfs?style=social&color=white)](https://github.com/seaweedfs/seaweedfs/stargazers)  
  **Fast distributed storage system for blobs, objects, files, and data lake**, Apache-2.0 licensed. **Millions of files** supported . **Filer with POSIX-compliant mount** . **The most scalable open-source file and object store** . 🌿

- **[GPFS (Open Source Components)](https://github.com/IBM/GPFS)** [![Stars](https://img.shields.io/github/stars/IBM/GPFS?style=social&color=white)](https://github.com/IBM/GPFS/stargazers)  
  **IBM Spectrum Scale open-source components**, open-source. **The open-source components of IBM's GPFS** . **The enterprise parallel file system used in HPC** . 🏢

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new HPC file storage platforms or open-source parallel file system software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-High-Performance-Compute-File-Storage-Lustre&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-High-Performance-Compute-File-Storage-Lustre&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this HPC file storage repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow HPC engineers, storage architects, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Lustre powers 60%+ of TOP500 supercomputers** with **hundreds of GB/s throughput** and **petabyte-scale capacity** . **Amazon FSx for Lustre charges $0.145/GB-month for SSD** . **Azure Managed Lustre charges $0.25/GiB-month for Premium** .
- **BeeGFS is the leading open-source alternative to Lustre** — **used by 40% of HPC sites in Europe** . **Ceph and GlusterFS provide general-purpose scale-out storage** for HPC and cloud .
- **Open-source HPC file systems are not turnkey** — they require **HPC infrastructure, high-speed networking (InfiniBand or 100GbE), and HPC storage expertise** . **Lustre requires MGS, MDS, OSS, and client configuration** . **BeeGFS requires management, metadata, and storage services** . **Always validate performance and failover with a proof-of-concept** before production deployment . ⚡

---

<p align="center">
  <b>Made with ❤️ for HPC engineers, storage architects, and open-source parallel file system advocates.</b>
</p>
