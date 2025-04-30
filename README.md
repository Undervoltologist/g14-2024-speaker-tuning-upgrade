# g14-2024-speaker-tuning-upgrade
Tutorial on how to upgrade the G14 2024's Cirrus Logic Speaker Firmware and the Dolby Driver to the G14 2025's and get free audio gains.

# How did I do it?
I downloaded the Cirrus Logic and Dolby Drivers at the G14 2025's driver support page: https://rog.asus.com/laptops/rog-zephyrus/rog-zephyrus-g14-2025/helpdesk_download/
The Dolby Driver already had the same speaker ID, so I just updated it without issue. However, Cirrus Logic changed the firmware tuning files and named them as GA403K instead of mine, which is the GA403. Hence, I just copy-pasted the 2025 tuning .bin's from it's folder and put them into the 2024's folder and renamed them to the 2024. Then I updated the Cirrus Logic driver and it just somehow worked.

2024:
Asus_GA403_10431B13_240426 
DEV_0285_SUBSYS_10431B13_PCI_SUBSYS_1B131043

2025:
ASUS_GA403K_10431044_241108 
DEV_0285_SUBSYS_10431044_PCI_SUBSYS_10441043
