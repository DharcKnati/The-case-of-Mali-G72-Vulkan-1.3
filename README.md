# The-case-of-Mali-G72-Vulkan-1.3
This is a desperately try of make devs see older gpus are capable 

# My Investigation:
the clear situation where i'm with is, my a505gn shows 88 vk exts using the r38p1 driver, but utilizing a vendor from unoffical port of oneui 6 it makes the driver exposes 89 (+1) vk exts. i have a print where i counted exactly 142 vk exts (+54) hidden exts, maybe could allow the use of vulkan 1.3, also the use from your compat_layer for dx12 on mali gpu. i already counted all VK_EXT & VK_KHR from driver r32p1 and are less than on r38p1. the point i'm trying to say is i see mali g52 gpus with vulkan 1.3 enabled and the case of the exynos 2400 where via a magisk module the .xml on /vendor/etc/permissions folder substitute the file for another copy from it which changed the vulkan 1.1 hex for 1.3 and looks like that worked for exynos 2400 users

![Screenshot](images/screenshot1.png)
![Screenshot](images/screenshot.png)
![Screenshot](images/screenshot.png)
