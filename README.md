
# Reclaimable Resources Details Dashboard for vRealize Operations 8.0 and 8.1
---------

Use this [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html) dashboard to identify reclaimable resources in your enviroment.

## Dashboard
![Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/Dashboard.png)

## Installation
1. Import the view at `Dashboards` / `Views` / `Import...`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/Import_View.png)
2. Click `Browse...` then select the file named [Views.zip](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/raw/master/Views.zip)
3. The included views are listed in the [Views section](#Views)
4. Import the dashboard at `Dashboards` / `Actions` / `Manage Dashboards` / `Import Dashboards`  
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/Import_Dashboard.png)
5. Click `Browse...` then select the file named [Dashboard.zip](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/raw/master/Dashboard.zip)
6. The dashboard should now be available in in the dashboard list  
![Dashboard List](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/master/Dashboard_List.png)
7. The included dashboards are listed in the [Dashboards section](#Dashboards)

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

## Support

This dashboard requires vRealize Operation 8.0 or 8.1 Advanced or Enterprise edition.

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_resources_details/issues) for feedback.

## Changelog
2020-03-19
* Initial release

2020-04-30
* Added Potential Savings chart
