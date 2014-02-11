gridwalk
========

Provides a test bed to experiment with multi-threaded / parallel algorithm development on the CPU or GPU using OpenCL and Java.

This code accompanies an introductory presentation I made at AnDevCon and OnAndroidConf at the end of 2013. You can view the video from OnAndroidConf here:
http://www.youtube.com/watch?v=XQCYWmYCJWo

This code of course runs on the desktop / J2SE and the CPU based portions run on all Android devices. The OpenCL Java part runs only where OpenCL is available which as of now is only reliably the ODROID-XU development board. 

As things go shortly after my presentation a few things changed professionally that has me occupied full time working on a next gen OpenGL based video engine for Android which I plan to announce for licensing soon. Also, due to OpenCL / work group limitations of the PowerVR 5 series GPU found in the ODROID-XU I am eagerly awaiting this years mobile SoCs to continue deep exploration of OpenCL on Android. I've found GLSL to be plenty fine for the advanced image processing pipeline in the forthcoming video engine that I'll be releasing. 

The PowerVR 6 series, Qualcomm Adreno 4xx, and Tegra K1 will be the first generation of mobile GPUs that bring massive power to the mobile space. It is a bummer that OpenCL was not exposed on Android at the same time of the arrival of OpenGL ES 3.0 (or full profile!) as all mobile GPU vendors have supporting drivers ready to be exposed. Hopefully OEMs will take notice and start exposing these drivers without waiting for Google to catch up.

If you really want access to the code early just get in contact. It will be posted later this year for sure along with more unique demos including Renderscript comparisons.
