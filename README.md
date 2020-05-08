
# Reclaimable Resources Details Dashboard for vRealize Operations 8.0 and 8.1
---------

Use this [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html) dashboard to identify reclaimable resources in your enviroment.

## Dashboard
![Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/images/Dashboard.png)

## Installation
1. Import the super metrics at `Administration` / `Configuration` / `Super Metrics` / `Import Super Metric`  
![Import Super Metric](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/images/Supermetric_Import.png)
2. Click `Browse...` then select the file named [supermetric.json](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/supermetric.json)
3. For each Super Metric listed in the [Super Metrics section](#Super-Metrics), click on the vertical kebab and select edit.  
![Policy Metrics](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/images/Supermetric_Edit.png)
4. Enable the Super Metric for each Policy shown in the `Enable in a Policy` stage of the wizard.
![Policy Library](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/images/Supermetric_Policy.png)
5. Repeat the previous 2 steps for the remaining Super Metrics listed in the [Super Metrics section](#Super-Metrics).
6. Import the view at `Dashboards` / `Views` / `Import...`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/images/View_Import.png)
7. Click `Browse...` then select the file named [Views.zip](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/raw/master/Views.zip)
8. The included views are listed in the [Views section](#Views)
9. Import the dashboard at `Dashboards` / `Actions` / `Manage Dashboards` / `Import Dashboards`  
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/images/Dashboard_Import.png)
10. Click `Browse...` then select the file named [Dashboard.zip](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/raw/master/Dashboard.zip)
11. The dashboard should now be available in in the dashboard list  
![Dashboard List](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/images/Dashboard_List.png)
12. The included dashboards are listed in the [Dashboards section](#Dashboards)

## Dashboards
| Dashboard Name | Dashboard Path |
|--|--|
| Reclaimable Resources Details | Shared Dashboards (GBrandon)/Cost |

## Views
| View Name | Name on Dashboard | View Type |
|--|--|--|
| Reclaimable Powered Off VMs | Reclaimable Powered Off VMs | List |
| Reclaimable Idle VMs | Reclaimable Idle VMs | List |
| Reclaimable VM Snapshots Details | Reclaimable VM Snapshots Details | List |
| Datastores with Orphaned Disks | Datastores with Orphaned Disks | List |

## Super Metrics
| Super Metric Name | Object Type |
|--|--|
| Potential Savings from Idle VMs | vSphere World |
| Potential Savings from Orphaned Disks | Datacenter |
| Potential Savings from Orphaned Disks | Custom Datacenter |
| Potential Savings from Orphaned Disks | Cluster Compute Resource |
| Potential Savings from Orphaned Disks | vSphere World |
| Potential Savings from Powered Off VMs | vSphere World |
| Potential Savings from VM Snapshots | vSphere World |
| Reclaimable Disk Space from Idle VMs | Datacenter |
| Reclaimable Disk Space from Idle VMs | Custom Datacenter |
| Reclaimable Disk Space from Idle VMs | vSphere World |
| Reclaimable Disk Space from Orphaned Disks | Datacenter |
| Reclaimable Disk Space from Orphaned Disks | Custom Datacenter |
| Reclaimable Disk Space from Orphaned Disks | vSphere World |
| Reclaimable Disk Space from Powered Off VMs | Datacenter |
| Reclaimable Disk Space from Powered Off VMs | Custom Datacenter |
| Reclaimable Disk Space from Powered Off VMs | vSphere World |
| Reclaimable Disk Space from VM Snapshots | Datacenter |
| Reclaimable Disk Space from VM Snapshots | Custom Datacenter |
| Reclaimable Disk Space from VM Snapshots | vSphere World |
| Reclaimable Memory from Idle VMs | Datacenter |
| Reclaimable Memory from Idle VMs | Custom Datacenter |
| Reclaimable Memory from Idle VMs | vSphere World |
| Reclaimable vCPUs from Idle VMs | Datacenter |
| Reclaimable vCPUs from Idle VMs | Custom Datacenter |
| Reclaimable vCPUs from Idle VMs | vSphere World |

## Support

This dashboard requires vRealize Operation 8.0 or 8.1 Advanced or Enterprise edition.

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/issues) for feedback.

## Changelog
2020-03-19
* Initial release

2020-04-30
* Added Potential Savings chart

2020-05-08
* Added Summary Super Metrics
