# rpizw-camos
A fast booting OS for Raspberry Pi Zero W with camera support based on Arch Linux, built with Github Actions and have full CI / CD consideration

1. make toolchains available in github actions
https://github.com/Pro/raspi-toolchain
https://archlinuxarm.org/wiki/Distcc_Cross-Compiling
not sure if raspi-toolchain can be used directly in this use case?

2. customise crosstool configuration file to remove uncessary files for this use case, aiming to achieve a less than 100mb final installation

3. complie and build a version of arch linux for armv6 and output the .img back to this github repository

4. optimise boot time of the distribution by incorporating http://himeshp.blogspot.com/2018/08/fast-boot-with-raspberry-pi.html

5. reconfigurating the image with a script with github actions https://github.com/Nature40/pimod

6. have the final .img ready in this github repository
