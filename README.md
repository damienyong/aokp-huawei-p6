AOKP-HUAWEI-ASCEND-P6
=======

device tree for HuaweiAscendP6 based on CM11 by surdu_petru

Do not compile and flash, there are some errors, which must be corrected !


Initializing Repository

Init core trees without any device/kernel/vendor :

repo init -u https://github.com/AOKP/platform_manifest.git -b kitkat

repo sync

copy files from my github in the repro

. build/envsetup.sh hwp6_u06
