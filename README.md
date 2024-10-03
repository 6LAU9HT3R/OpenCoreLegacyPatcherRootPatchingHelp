# OpenCoreLegacyPatcherRootPatchingHelp
Can sombody please help me! I am tring to perform an Post-Install Root Patch with OpenCore-Patcher 2.0.2 on my iMac17. After updating to Seqouia 15 my iMac17 no longer connects to wifi, im connected VIA ethernet cabel right now. OCLP keeps displaying the following error code:
- Starting Patch Process
- Determining Required Patch set for Darwin 24
- Verifying whether Root Patching possible
- Patcher is capable of patching
- Local PatcherSupportPkg resources available, continuing...
Failed to mount root volume
Subprocess failed.
    Command: ['/Library/PrivilegedHelperTools/com.dortania.opencore-legacy-patcher.privileged-helper', '/sbin/mount', '-o', 'nobrowse', '-t', 'apfs', '/dev/disk2s4', '/System/Volumes/Update/mnt1']
    Return Code: 75
    Standard Output:
        mount_apfs: volume could not be mounted: Resource busy
        mount: /System/Volumes/Update/mnt1 failed with 75
    Standard Error:
        None

Failed to mount root volume
- Failed to mount root volume, cannot continue with patching!!!
