# AWS S3 Bucket Versioning Project

##  Project Overview

Implemented Amazon S3 Versioning to preserve multiple versions of objects stored in an S3 bucket. This project demonstrates how versioning helps protect data against accidental deletion, overwrites, and application failures.

##  AWS Services Used

* Amazon S3

##  Project Objectives

* Understand Amazon S3 Versioning
* Preserve multiple versions of objects
* Protect data from accidental overwrites
* Learn object recovery concepts

##  Steps Followed

1. Created an Amazon S3 bucket
2. Enabled Bucket Versioning
3. Uploaded the first version of an object
4. Modified the file content locally
5. Uploaded the same file again
6. Enabled "Show versions" to view multiple object versions
7. Verified that Amazon S3 stored multiple versions of the same object

##  Versioning Demonstration

* Version 1: `This is Version 1.`
* Version 2: `This is Version 2.`
* Additional versions can be stored without overwriting previous copies.

##  Outcome

Successfully enabled Amazon S3 Versioning and verified that multiple versions of the same object were preserved within the bucket. This provides enhanced data durability and recovery capabilities.

##  Key Learnings

* Amazon S3 Versioning
* Object Version IDs
* Data Protection
* Object Recovery
* Storage Durability
* File Overwrite Prevention

##  Future Enhancements

* Enable MFA Delete
* Configure Lifecycle Policies for older versions
* Implement Cross-Region Replication
* Automate backups using versioned buckets
