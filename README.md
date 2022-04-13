# mesa patch 
This PKGBUILD builds the current mesa version with a patch applied which disables the Vulkan WSI modifier support.
In my case, I was able to solve the problem with the error 'a key component of SteamVR isn't working properly' (Error 307) with this patch.
Thanks to @Zamundaaa for discovering the problematic commit:
https://gitlab.freedesktop.org/mesa/mesa/-/issues/5266

## How to use
This package is intended/tested for Arch. The installation is done by using: `makepkg -si`
