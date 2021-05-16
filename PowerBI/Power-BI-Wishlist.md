I've had a personal wishlist for years while using Power BI, and continue to watch the features gradually get added over time.
This file serves to track them and document resolutions.

## Resolution Types:
<br>ET - External Tool (This is not addressed in the core product)
<br>PR - Partially Resolved (There is a partial solution to the issue)
<br>FX - Fixed

### #1 - Ability to identify and remove unused columns and measures from a dataset, including linked reports if it's a shared dataset.
  ET - The BPA tool inside Tabular Editor can identify columns and measure not used within that dataset (but not linked reports) and they can be removed manually.

### #2 - Ability to branch-and-merge Power BI (pbix) files

### #3 - Ability to version-control PBIX files on desktop (view changes, rollback to previous version)
  PR - (2021-05-15) Microsoft [Announced](https://powerbi.microsoft.com/en-us/blog/announcing-support-for-backup-and-restore-of-power-bi-datasets/) a [Backup and Restore feature](https://docs.microsoft.com/en-us/power-bi/admin/service-premium-backup-restore-dataset) in premium capacities. This partially meets the need for some users.

### #4 - Ability to version-control Datasets on Power BI Service (view changes, rollback to previous version)

### #5 - Ability to version-control Dataflows on Power BI Service (view changes, rollback to previous version)
  ET - Can be accomplished by tracking json definitions with change-control software like git

### #6 - Ability to version-control Reports on Power BI Service (view changes, rollback to previous 

### ~~#7 - Prevent visuals and other onjects from jumping out of layer order when clicked~~
  PR - Could be addressed on objects with bookmark actions and bookmarks on selected visuals to turn clicks into null-navigation events
<br>  FX - Maintain Layer Order was added as a formatting option in September 2020


(More coming soon)
