# g14-2024-speaker-tuning-upgrade
Tutorial on how to upgrade the G14 2024's Cirrus Logic Speaker Firmware and the Dolby Driver to the G14 2025's and get free audio gains.

# Why?
In my opinion, G14/16 2024 had the best speakers ever except Macbooks, hence I got one especially for that. It sounded great, but still felt like Asus didn't work enough on it and rushed it. As the 2025 model was released, I was curious and wanted to see if they changed anything at all, and after checking the audio drivers and firmware on the support website, they definitely did. I somehow managed to install them, and voila, the extreme distortion I had around 90-150hz region was gone (very healthy for the speakers), and the treble was better, and as a result it's somehow more punchier and even more clearer and I'm very happy with it. The speaker hardware are exactly the same on 2024 and 2025, so the installation went somewhat smooth.

# How did I do it?
I downloaded the Cirrus Logic and Dolby Drivers at the G14 2025's driver support page: https://rog.asus.com/laptops/rog-zephyrus/rog-zephyrus-g14-2025/helpdesk_download/
The Dolby Driver already had the same speaker ID, so I just updated it without issue. However, Cirrus Logic changed the firmware tuning files and named them as GA403K instead of mine, which is the GA403. Hence, I just copy-pasted the 2025 tuning .bin's from it's folder and put them into the 2024's folder and renamed them to the 2024. Then I updated the Cirrus Logic driver and it just somehow worked.

I'll provide the modified drivers in releases so you can install them easily.

# Extras
2024 Speaker IDs:
Asus_GA403_10431B13_240426 
DEV_0285_SUBSYS_10431B13_PCI_SUBSYS_1B131043

2025 Speaker IDs:
ASUS_GA403K_10431044_241108 
DEV_0285_SUBSYS_10431044_PCI_SUBSYS_10441043

# DISCLAIMER
THIS IS UNSUPPORTED. You're manually installing firmware from a different model (2025) onto the 2024 version.
USE AT YOUR OWN RISK. I am not responsible for any issues caused by this.
KNOW WHAT YOU'RE DOING. This is not officially supported by ASUS and could be overwritten in future updates.
