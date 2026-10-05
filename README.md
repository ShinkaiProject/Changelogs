# Shinkai Project Changelogs

# October 05, 2026
- fixing biometric bottomsheet insets
- add back Hide ADB and developer setting enable status
- re-add the spoof option feature
- add option toggling suggestions button
- Allow toggle to kill Flash SMS messages
- SystemUI: Screen recorder: keep recordings decodable on-device
- services/display: Allow sunlight HBM to react to ambient lux on manual brightness
- re-add disable data indicator and 4G icon
- Revamp Shinkai walls
- Settings: change Logo on Android Version
- Bluetooth: accept proprietary L2CAP option 0x7F on config
- GameSpace: Introduce Auto Hide Toolbar And Adjust Auto Hide Toolbar Transition Animation
- LMOFreeform: Revamp UI and Migrate to M3E

# September 03, 2026
- intial Version "heptakaideka" Android 17
- introduce New GameSpace And Now Integrate with SideBar
- Update ShinkaiWalls With new style icon App
- introduce new local Backup And Restore App native
- Update ProgressBar PackageInstaller to SquigglyProgressBar 
- update New UI per-app Volume

# August 03, 2026
- introducing Shinkai Walls
- GameSpace: Revamp UI
- Drop all about play integrity fix (we have fenrir hell yeah)
- fixup: Bring back bar battery show percent
- add shinkai project logo on about phone 
- Add Hide ADB & Developer Option Status
- add Partial Screenshot
- also added the shinkai project logo in recovery mode 

# July 13, 2026
- base: support per-app volume
- services: Fixing per-app volume ux
- Adding multi-media focus support
- VolumeHaptics: Tune the primitives
- SystemUI: Introduce Adaptive Playback
- allowing spl downgrade by default
- recovery: Skip verifying packages altogether
- recovery: Make recovery usable on user builds
- recovery: add support for changing slots
- recovery: Add support for AIDL bootcontrol HAL in slot switch option
- recovery: fix PNG color type for logo (RGBA -> Grayscale)


# July 10, 2026

- Revert: Disable blurs during critical thermal state
- Revert: adjust the threshold for disabling blur on thermal status
- Add Charging info on lockscreen
- SystemUI: Fixup FOD
- base: Add private DNS tile
- SystemUI: Add refresh rate tile
- SystemUI: Implement burn-in protection for status bar
- [AAPM] Check radio interface for 2G availability
- wm: don't disable rot hint on low_ram
- fw/b: Suggestion Popup: Tint properly
- SystemUI: Constrain keyguard indication area burn-in offset
- SystemUI: Introduce ringer qs tile
- SystemUI: add volume tile
- base: Rework lock gesture feature
- SystemUI: update ringer tile background color
- base: Adjust card corner radius to 32dp
- SystemUI: Add blur QS tile
- SystemUI: Add haptic feedback for qs footer actions
- SettingsLib: fixing platform apps storage info
- GameSpace: Add auto enable DND if you launch Game
- GameSpace: Drop Notification Tile


## initial version - hekkaideka

- Enable landscape lockscreen flag
- add Support For Game Space 
- add support for LMOFreeform service
- Enable Clone App 
- add Option to disable Data Disabled Indicator icon
- Allow using 4G icon instead of LTE
- add perf activity anim override
- Introduce Force LTE_CA override
- Introduce GamesPropsUtils
