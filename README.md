# Framework MTK Patches
Patches for framework to run correctly on MTK, fixes videocodecs too.

## Source commit (TextureVuew rebind GL texture, if AHB content has changed)
https://github.com/phhusson/platform_frameworks_base/commit/b13732f6a801d85390feb025d678e2b14effc915

## How to apply
`cd (path to directory with sources)/frameworks/base`  
`patch -p0 < (path to directory with a patches)/*.patch`
