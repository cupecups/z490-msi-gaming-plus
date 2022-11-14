# z490-msi-gaming-plus


 - An `iMac19,x` or `iMac20,x` SMBIOS
 - Acidanthera's FeatureUnlock kext (<https://github.com/acidanthera/FeatureUnlock>)
After this, run these commands:
```bash
$ defaults write com.apple.AppleGVA gvaForceAMDKE -boolean yes
$ defaults write com.apple.sidecar.display LowLatency -bool True
$ defaults write com.apple.sidecar.display MinBitrate -int 250000000
$ defaults write com.apple.sidecar.display MaxBitrate -int 250000000
```
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
