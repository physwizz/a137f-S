#
# Copyright (C) 2015 MediaTek Inc.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 2 as
# published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# GNU General Public License for more details.
#

subdir-ccflags-y += -Idrivers/misc/mediatek/mtprof/
subdir-ccflags-y += -Idrivers/misc/mediatek/aee/mrdump/
subdir-ccflags-y += -Idrivers/misc/mediatek/aee/ipanic/
subdir-ccflags-y += -Idrivers/misc/mediatek/aee/aed/

obj-y	+= aee.o
aee-y	:=dummy.o
aee-$(CONFIG_MTK_AEE_FEATURE)	+= aee-common.o reboot-reason.o

KASAN_SANITIZE := n
