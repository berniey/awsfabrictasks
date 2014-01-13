History
=======


Version 1.2.0
-------------
- Multitag Support
  As explained in https://github.com/espenak/awsfabrictasks/pull/11
  Thanks to Lucas Hrabovsky

Version 1.1.1
-----------
- Make ec2_list_instances work with boto 2.6.0 as well as earlier versions
  (https://github.com/espenak/awsfabrictasks/pull/9).
  Closes https://github.com/espenak/awsfabrictasks/issues/7
  Thanks to Mr. Russ Ferriday

Version 1.1
-----------
- Prevent clash caused by addition of -t to underlying options
  (https://github.com/espenak/awsfabrictasks/pull/8).
  Thanks to Mr. Russ Ferriday

Version 1.0.14
--------------
- Support for user_data in in Ec2LaunchInstance
  (https://github.com/espenak/awsfabrictasks/pull/4)
  Thanks to Mr. Russ Ferriday
- Methods in awsfabrictasks.conf that makes it easier to unittest code.

Version 1.0.13
--------------
- More S3 tasks, including sync-up/download directories.
- EC2 rsync upload and download. Deprecates ec2_rsync.
- Bash completion script.

Version 1.0.12
--------------
- Basic S3 tasks.

Version 1.0.11
--------------
- Improves RDS support.

Version 1.0.10
--------------
- Adds retry support when adding tags in Ec2LaunchInstance.

Version 1.0.9
-------------
- Adds name protection to Ec2LaunchInstance (prevent duplicate names).

Version 1.0.8
-------------
- Bugfix release for 1.0.7.

Version 1.0.7
-------------
- Experimental support for RDS
- Experimental support for groups of AWS instances in the awsenv module.

Version 1.0.6
-------------
- Helper function to create a remote file from string.
- Include Name-tag behind header when listing instances.

Version 1.0.5
-------------
- Added the ability to match any tag, not just name
  (https://github.com/espenak/awsfabrictasks/pull/1).
  Thanks to Mr. Russ Ferriday


Version 1.0.4
-------------

- Warn when awsfab is not used.
- More documentation.
- Documentation on readthedocs.com.


Version 1.0.3 --- first publicly available version
--------------------------------------------------

- A usable set of ec2 tasks.
- The awsfab wrapper.
