<div align="center">
  <img width="500px" alt="logo" src="logo_index.png"/></a>
  <br/>
  <p><i> NVIDIA vGPU Archive is a project inspired by <a href = "https://msdn.itellyou.cn/" >MSDN ITellYou</a> </i></p>

  <img src="https://flat.badgen.net/static/Last Updated/2025-06-25/green" /> <img src="https://flat.badgen.net/static/Total Size/1.94 TB/red" /> <img src="https://flat.badgen.net/static/Driver Counts/1433/blue" /> <img src="https://flat.badgen.net/static/Non-Driver Count/125/black" /> <img src="https://flat.badgen.net/static/Duplicate Ratio/13.67%25/orange" />

</div>

> [!NOTE]
> Currently, we only have this GitHub repository and a related Internet Archive account. We do not plan to open any other social media accounts, such as Discord or Telegram, as we welcome open and upfront discussions.  
>
> If you have found an issue with drivers or wish to request new drivers, kindly raise an issue.

## Description 

The **vGPU Archive Index** serves as a programmatically generated catalog of NVIDIA vGPU drivers uploaded to the Internet Archive. The project focuses on preserving older drivers and devices by indexing these files and ensuring they are accessible for future use.

- **Automated Archiving**: Built on Python scripts, the repository uses [Archiver](https://github.com/nvidiavgpuarchive/archiver) for automating the scraping and uploading of drivers, simplifying the process of maintaining the index.
- **Preservation First**: The priority is to archive as many drivers as possible; maintaining an up-to-date index, while desirable, is a secondary focus.
- **Dynamic Updates**: Due to the nature of this project, the project might break from time to time.

> Why not just download the driver from [NVIDIA's Driver Search](https://www.nvidia.com/en-us/drivers/)?

The NVIDIA driver search interface is quite limited—it primarily focuses on consumer hardware and only lists a subset of the available drivers. Additionally, some drivers, such as GRID drivers for Windows with WDDM mode, are not readily available from NVIDIA's site. These drivers provide specific functionality critical for certain use cases, making this archive essential for preservation.

### Integrity and Verification
All drivers uploaded to the Internet Archive are checked rigorously for integrity:
- **Checksum Matching**: Each file’s checksum is validated before and after the upload.
- **Compressed Files**: The integrity of compressed files is verified for zip files.

Note: When you download from internet archive, either via torrent or http, you are getting a zip file that includes all files in the archive bucket including the core driver zip and other trivial files such as metadata. All checksums and virustotal scans refers to the core driver file enclosed in the "overall" zip. So don't be alarmed if the md5 checksum doesn't match up, double check.

If you encounter a broken archive, raise an issue and we'll fix it asap.

### Repository Overview
- **Index**: See below. You may use the index to narrow down and locate what you are looking for in <5 clicks.
- **Search**: Type `/` to search in the whole repo, title, filename or md5.
- **dump.json**: A JSON file that fully describes this repo so you can access the information programmatically.
- **Driver Catalogue**: Located in the "Non-Drivers / Misc" section, provides devices id and driver compatibility information.

Downloading via **torrents** is highly recommended:
- The torrent files are seeded by the Internet Archive (via HTTP sources), which ensures high download speeds on top of IA bandwidth.
- Using torrents ensures that the archived content remains available even after potential takedown requests.

## Index

### Drivers

| Platform Name | Last Updated |   Latest Entry |  Count | Filter | 
|---|:-------:|:-------:|:----:|:---:|  
| Citrix Hypervisor | 2025-06-17|    [View Latest](/details/2c5630_Complete_vGPU_18.3_package_for_Citrix_Hypervisor_8.2_including_supported_guest_drivers.md) |  229 |  [Apply](/index/Driver/Citrix_Hypervisor.md) |
| Citrix XenServer | 2025-01-16|    [View Latest](/details/52280a_Complete_vGPU_17.5_package_for_Citrix_XenServer_8_including_supported_guest_drivers.md) |  22 |  [Apply](/index/Driver/Citrix_XenServer.md) |
| Huawei UVP | 2019-03-18|    [View Latest](/details/470f9d_NVIDIA_vGPU_for_UVP.md) |  7 |  [Apply](/index/Driver/Huawei_UVP.md) |
| Linux KVM | 2025-06-17|    [View Latest](/details/a4c9ed_Complete_vGPU_18.3_package_for_Linux_KVM_including_supported_guest_drivers.md) |  105 |  [Apply](/index/Driver/Linux_KVM.md) |
| Microsoft Azure Local | 2025-06-17|    [View Latest](/details/73bdf2_Complete_vGPU_18.3_package_for_Microsoft_Azure_Local_including_supported_guest_drivers.md) |  8 |  [Apply](/index/Driver/Microsoft_Azure_Local.md) |
| Microsoft Azure Stack HCI | 2024-10-22|    [View Latest](/details/b60ff0_Complete_vGPU_16.8_package_for_Microsoft_Azure_Stack_HCI_22H2_including_supported_guest_drivers.md) |  18 |  [Apply](/index/Driver/Microsoft_Azure_Stack_HCI.md) |
| Microsoft Hyper-V Server | 2025-06-17|    [View Latest](/details/63b066_Complete_vGPU_18.3_DDA_GPU_driver_package_for_Microsoft_platforms.md) |  262 |  [Apply](/index/Driver/Microsoft_Hyper-V_Server.md) |
| Microsoft Windows Server | 2025-06-17|    [View Latest](/details/f6e112_Complete_vGPU_18.3_package_for_Microsoft_Windows_Server_including_supported_guest_drivers.md) |  4 |  [Apply](/index/Driver/Microsoft_Windows_Server.md) |
| Nutanix AHV | 2022-01-31|    [View Latest](/details/da8660_NVIDIA_vGPU_for_AHV_5.11.md) |  66 |  [Apply](/index/Driver/Nutanix_AHV.md) |
| NVIDIA Control Panel | 2024-01-16|    [View Latest](/details/239cac_Standalone_NVIDIA_Control_Panel.md) |  1 |  [Apply](/index/Driver/NVIDIA_Control_Panel.md) |
| Red Hat Enterprise Linux KVM | 2025-06-17|    [View Latest](/details/044570_Complete_vGPU_18.3_package_for_Red_Hat_Enterprise_Linux_KVM_10.0_including_supported_guest_drivers.md) |  426 |  [Apply](/index/Driver/Red_Hat_Enterprise_Linux_KVM.md) |
| Ubuntu KVM | 2025-06-17|    [View Latest](/details/3522de_Complete_vGPU_18.3_package_for_Ubuntu_KVM_including_supported_guest_drivers.md) |  44 |  [Apply](/index/Driver/Ubuntu_KVM.md) |
| VMware vSphere | 2025-06-18|    [View Latest](/details/efaf83_Complete_vGPU_18.3_package_for_VMware_vSphere_9.0_including_supported_guest_drivers.md) |  234 |  [Apply](/index/Driver/VMware_vSphere.md) |
| XenServer | 2025-06-17|    [View Latest](/details/f3f24e_Complete_vGPU_18.3_package_for_XenServer_8.4_including_supported_guest_drivers.md) |  7 |  [Apply](/index/Driver/XenServer.md) |


### Non-Drivers / Misc

| Platform Name | Last Updated |  Count | Filter | 
|---|:-------:|:-------:|:----:| 
| vGPU Driver Catalog | 2025-05-28|   1 |  [Apply](/index/NonDriver/vGPU_Driver_Catalog.md) |
| Citrix Hypervisor | 2025-05-22|   17 |  [Apply](/index/NonDriver/Citrix_Hypervisor.md) |
| Container | 2025-05-22|   14 |  [Apply](/index/NonDriver/Container.md) |
| DLS Base OS | 2023-10-20|   2 |  [Apply](/index/NonDriver/DLS_Base_OS.md) |
| DLS 2.0.1 Container | 2022-08-29|   1 |  [Apply](/index/NonDriver/DLS_2.0.1_Container.md) |
| Linux KVM | 2025-05-22|   18 |  [Apply](/index/NonDriver/Linux_KVM.md) |
| Linux | 2025-06-25|   9 |  [Apply](/index/NonDriver/Linux.md) |
| Microsoft Hyper-V | 2025-05-22|   17 |  [Apply](/index/NonDriver/Microsoft_Hyper-V.md) |
| Red Hat Enterprise Linux OS | 2025-05-22|   12 |  [Apply](/index/NonDriver/Red_Hat_Enterprise_Linux_OS.md) |
| Ubuntu | 2023-05-04|   1 |  [Apply](/index/NonDriver/Ubuntu.md) |
| VMware vCenter | 2025-02-18|   8 |  [Apply](/index/NonDriver/VMware_vCenter.md) |
| VMware vRealize Operations | 2024-09-19|   7 |  [Apply](/index/NonDriver/VMware_vRealize_Operations.md) |
| VMware vSphere | 2025-05-22|   17 |  [Apply](/index/NonDriver/VMware_vSphere.md) |
| OTHER | 2020-01-10|   1 |  [Apply](/index/NonDriver/OTHER.md) |

