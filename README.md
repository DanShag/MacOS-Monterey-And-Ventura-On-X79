# MacOS-Monterey-And-Ventura-On-X79

I recently installed Big Sur on my X79 PC, but I was able to build an EFI that can work with both Monterey and Ventura.

![MacOS Ventura](https://github.com/DanShag/tdworld.github.io/blob/main/images/photo_2024-11-08_20-35-00.jpg)

> _WARNING: SO FAR I CANNOT RUN ANYTHING HIGHER THAN MAC OS VENTURA, FOR EXAMPLE SONOMA OR SEQUOIA, I HAVE NOT YET FOUND A SOLUTION FOR THIS CONFIGURATION. I WILL POST A NEW REPOSITORY IF SOMETHING IS UPDATED_

Tested on hardware:
Machinist X79 (2.82H, C602 chipset, for someone this may be important)
Xeon E5-2650V2
GTX 1070 (Pascal, may also run on lower video cards, for example Maxwell)

## Installation instructions that I used for this EFI:
1. Run BDUTillity.exe, which is in the archive
2. Insert a flash drive, I recommend at least 16 or 32 gigabytes
3. Format your flash drive through the program
4. Go to the newly created "BDU" partition, delete everything that is there (this is not useful)
5. Move my EFI to the BDU partition, move back to the program and select PART2, click the Restore button and select your MacOS (HFS is needed file)
6. Wait for the operation to complete and boot from your flash drive.
7. Select the MacOS installer and install the system.

At this point, you should have successfully installed Monterey or Ventura.
If something went wrong, the installer freezes, or Kernel Panic occurs, you can contact me on Telegram: https://t.me/danyashag
