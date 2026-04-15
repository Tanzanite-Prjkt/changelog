# Changelog 15/04/2026
- Bump vulkan to 1.3
- Bump opengl, vulkan deqp level to 2024-03-01
- Upgrade mali blobs to latest blobs gpu 1.3
- overlay: Update multiple vibration strength levels overlay for 13
- overlay: Enable vibration intensity control
- Disable memcg
- Disable kmem cgroup accounting
- Set PELT HALFLIFE to 8ms before early init boot stage
- Explicitly set log_buf_len
- Set product marketname properly

# Changelog 10/04/2026
- Sync RCU settings
- sepolicy: address vendor_init sysfs denials
- init: disable multiple kswapd threads
- init: match cpuset with Pixel layout
- Allow games to use 120fps
- rootdir: Drop ext4 fstab entries of dynamic partitions
- Force to use EROFS
- rootdir: Set auto for mmcblk0p1
- sepolicy: Allow recovery to read and write exfat partitions
- sepolicy: Allow recovery to read sysfs to get mmc type
- rootdir: Add entry for mounting sdcard in recovery

# Changelog 07/04/2026
- Import Dolby media and Device media codecs from stock
- rootdir: Refactor CPU policies and tune kernel parameters
- bluetooth: Disable unsupported power stats reporting
- kernel: Update kernel to Chihiro to v1.4

# Changelog 03/04/2026
- sepolicy: Allow libperfmgr to write to cpu_dma_latency_device
- overlay: Kang some haptic configurations from zumapro
- overlay: Disable Auxilary Cameras
- audio: Configure Lineout, Handset and ADDA_DL_GAIN volumes
- dolby: Whitelist permissions for Dolby
- dolby: Implement DSPVolumeSynchronizer
- dolby: Add privapp-permissions-dolby.xml as a dependency

# Changelog 14/03/2026
- Defer refresh rate changes when screen is off
- Switch to NCM USB tethering
- Switch to libperfmgr from hardware/google
- Ensure 1.5 GB free space before creating zram backing device
- Hand back GPU Frequency control to gpufreqv2
- Allow games to use 120fps
- Rename default bluetooth name to full device name

# Changelog 12/03/2026
- udfps: Set up HBM and force-disable FOD
- dolby: Update dolby blobs from pdx237

# Changelog 09/03/2026
- Include preloader_raw eng
- Use the proper way to disable console service
- Set preferred refresh rate on keyguard to 60
- Stop declaring PRODUCT_VIRTUAL_AB_COW_VERSION
- Dynamically enable VAB compression
- Allow Audio HAL to search sysfs_power_supply
- Cleanup FrameworksResOverlay
- Import phase offsets from Motorola
- Raise the frequency of sampling regions in SurfaceFlinger
- Drop framerate multi threshold
- powerhint: Nuke GPU Block boost
- Allow fod to be enabled when display is off

# Changelog 05/03/2026
- Update blobs from OS2.0.213.0.VOGEUXM
- Switch to AIDL Codec2
- Switch to source-built C2 service
- add Smart Pixels feature support
- Reduce QS blur radius to 23dp

# Changelog 23/02/2026
- tanzanite: Set ro.config.vc_call_vol_steps to 11
- Import activity open/close animations
- audio: improve mute duration
- Add Opt out of speaker_layout_channel_mask field

# Changelog 17/02/2026
- Add some popular game packages to sched_lib_name
- Enable ScrollOptimizer
- Build DSPVolumeSynchronizer

# Changelog 14/02/2026
- audio: Import volumes audio policy from raven
- Revert "tanzanite: readjust audio configs"
- Update wifi hal interfaces combination
- Set all of the supported wifi HAL combinations
- aidl: fingerprint: Add jiiov module
- Switch to external_wpa_supplicant_8 mediatek
- Update kernel to 5.10.247 vanilla

# Changelog 09/02/2026
- Build mediaTek WiFi lib and enable OUI support on wpa_supplicant_8
- fixup! tanzanite: wifi: Use lib_driver_cmd_mt66xx
- Patch some blobs to depend on libtinyxml2-v34.so
- Add com.android.bluetooth context to seapp_contexts
- Update blobs and firmware from OS2.0.212.0.VOGEUXM
- Move to Lunaris Dolby 
