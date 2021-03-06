---
title: Restore
nav_order: 4
layout: page
description: ""
parent: Usage
---

# Restore Files from Backup

**Note:** This article assumes you have Vorta correctly configured and making backups.  If you need help with this, please check out the other [Usage](/usage) articles in the sidebar, or visit the [Download](/download) page for different install options.

## Step 1 - Launch Vorta

To begin restoring files a snapshot, launch Vorta and click on the **Archives** tab.

<img src="/assets/images/vorta/restore1.png" alt="" width="500" />

There are two ways to restore files with Vorta, *Extracting* and *Mounting*.  Both accomplish the same goal, but one may be preferable over the other depending on the situation.  This guide will cover both methods.

## Step 2a - Extracting from an Archive

After opening the **Archives** tab in Vorta and selecting the snapshot you would like to restore from, click on the **Extract** button at the bottom.  After a short wait, the following window should pop up with the files from your backup.

<img src="/assets/images/vorta/restore2.png" alt="" width="500" />

This is the *full path* of the your backup snapshot--meaning, its the folder you backed up, and all the folders leading up to it.  Go through the dialogs and select the folder that you would like to be restored and click on the **Extract** button.

The next window that comes asks for the *Extraction Point*, or the location you would like to extract your backup into.  Select a location and continue.

<img src="/assets/images/vorta/restore3.png" alt="" width="500" />

Depending how large the extraction is and where its located,  this may take anywhere from a few minutes to a few hours.  Be patient and let Vorta work its magic.  When your extraction is completed, the following message will appear at the bottom of Vorta.

<img src="/assets/images/vorta/restore4.png" alt="" width="500" />

Voilà!  After Vorta is done extracting, your selected files should be in the directory that you chose.

<img src="/assets/images/vorta/restore5.png" alt="" width="500" />

## Step 2b - Mounting a Snapshot

After opening the **Archives** tab in Vorta and selecting the snapshot you would like to restore from, click on the **Mount** button at the bottom.  After a short wait, the following window should pop up.

<img src="/assets/images/vorta/restore6.png" alt="" width="500" />

Select a mount directory, this will be the directory that Vorta will use to give you access to that backup as if it was still on your filesystem.  Make sure it is an empty directory.  If you're not familiar with mounting remote directories, think of it as plugging it a flash drive with your backups on it, and the folder you choose will be the place on your system that you access the files on it from.  None of this is permanent, as the folder can always be unmounted and changed later.

Once the snapshot is finished mounting, the following message should appear in Vorta:

<img src="/assets/images/vorta/restore7.png" alt="" width="500" />

This means you are now able to access the snapshot you selected via the mount folder that you chose.  Using your favorite file manager, you can now copy and paste the files you would like to restore, directly from the archive!

<img src="/assets/images/vorta/restore8.png" alt="" width="500" />

*Note:* The speed of this depends on whether your backups are local or remote, and the speed of your connection.

When you are finished restoring your files, close out all of your active windows, and hit the **Unmount** button.
