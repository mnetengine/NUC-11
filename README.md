# NUC11-Hackintosh
 
Intel NUC 11, Quad-Core Intel Core i7-1165 G7
iGPU is not working,
AMD RX 6650 XT 8 GB,

32 GB 3200 MHz DDR4.

 

There is only a small issue, when the system is booting you will lose display for a short time until the GPU driver is loaded, that is the same issue with Windows too, I disabled the iGPU, and did not see any improvement.
Also if you connect the HDMI cable to the iGPU, the computer will encounter a problem and will be rebooted, to prevent that you have to delete the external GPU from the Device Properties.

for those users who have intel NUC 11 and want to use eGPU, I will upload my EFI, hope it helps people.
