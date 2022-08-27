# OpenCore Hackintosh HP AL132TX Kaby Lake

This is a ready to go OpenCore configuration for HP Pavilion 14 AL132TX. 
Use ```OpenCore-0.8.3-RELEASE/Utilities/macrecovery/macrecovery.py```
to download your preffered recovery image and you're ready to go. Create a folder named ```com.apple.recovery.boot``` and put the recovery inside the folder then put both the ```EFI``` and ```com.apple.recovery.boot``` in your USB or Boot Installer Drive and boot.

For details refer to https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites
------------------------------------------

#### Working 100% - Tested with latest macOS Monterey 12.5[Updated]

* LAN driver currently not working but WLAN works flawlesly

![Screen Shot 2022-05-06 at 6 04 30 PM](https://user-images.githubusercontent.com/43669876/167128579-f0fd5b7a-6d00-416f-93dc-66678f7a1f79.png)
### To set your Serial No and UIID
Refer to this guide https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#using-gensmbios
and update the following configurations inside PlatformInfo >> Generic
![Screen Shot 2022-07-31 at 4 22 21 PM](https://user-images.githubusercontent.com/43669876/182022133-e3d15077-9305-45bb-9789-6ce2ac3e6f2e.png)


For battery patch use this repo https://github.com/h9419/HP_Pavilion_14_bf100_Hackintosh [I will update the patched EFI Soon]

## Disclaimer:
None of these drivers or softwares, whatsoever are owned by me or any of my associations.
These are the cherry picked collections of many opensource projects with their own sharable licences available under their authority and contains no proprietary codes to my knowledge.
This compilation is strictly intended for demonstration and learning purpose only, any use of it either commercial or personal is not my responsibility, use at your own risk
