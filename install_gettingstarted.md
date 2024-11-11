## Install Omniverse Launcher

A bit tough to find "omniverse-launcher-linux.AppImage" - suspect they are targeting IT managed installs.   Found it here: https://docs.omniverse.nvidia.com/isaacsim/latest/installation/install_workstation.html

sudo apt install libfuse2

Move app image to Desktop, make it executable 

Follow the tutorial: https://docs.omniverse.nvidia.com/isaacsim/latest/installation/install_workstation.html

Ignoring this warning for now:
```
An input-output memory management unit (IOMMU) appears to be enabled on this system.
On bare-metal Linux systems, CUDA and the display driver do not support IOMMU-enabled PCIe peer to peer memory copy.
If you are on a bare-metal Linux system, please disable the IOMMU. Otherwise you risk image corruption and program instability.
This typically can be controlled via BIOS settings (Intel Virtualization Technology for Directed I/O (VT-d) or AMD I/O Virtualization Technology (AMD-Vi)) and kernel parameters (iommu, intel_iommu, amd_iommu).
Note that in virtual machines with GPU pass-through (vGPU) the IOMMU needs to be enabled.
Since we can not reliably detect whether this system is bare-metal or a virtual machine, we show this warning in any case when an IOMMU appears to be enabled.
```

## VS Code setup

Install "Isaac Sim VS Code Edition".  See https://docs.omniverse.nvidia.com/isaacsim/latest/advanced_tutorials/tutorial_advanced_code_editors.html

## Nucleus setup

Installing Nucleus Workstation
You can install Nucleus Workstation using the Omniverse Launcher. To do this, you can:
1. Open the Omniverse Launcher 
2. Click the Nucleus tab 
3. Click Add Local Nucleus Service 
4. Set your data path - accepted default for now
5. Enter your local administrator account credentials 
6. Click Complete Setup 

This will then need to download ~350 MB locally.

After installing Nucleua, the Ommiverse launcher wouldn't work, just a blank window.  Restarted computer and it is back.

Now the localhost is showing up in Isaac Sim.  (Requires good internet)

( Didn't have to, but good to know aboutthe cleanup tool
https://docs.omniverse.nvidia.com/utilities/latest/cleanup-tool.html )

## Adding assets



## Extensions


https://docs.omniverse.nvidia.com/isaacsim/latest/advanced_tutorials/tutorial_extension_templates.html


    