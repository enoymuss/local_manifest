LineageOS 17.1 for Exynos3475 devices
------------------------------------

Create directories

	$ mkdir lineage-17.1
	$ cd lineage-17.1
 
.repo/local_manifests/


	$ repo sync --force-sync -q -c

-------------
 
_Building from source_
---------------

	$ . build/envsetup.sh
	$ lunch lineage_DEVICE-userdebug
	$ mka bacon
