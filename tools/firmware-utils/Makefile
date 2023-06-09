#
# Copyright (C) 2006-2020 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

PKG_NAME:=firmware-utils
PKG_RELEASE:=1

PKG_SOURCE_PROTO:=git
PKG_SOURCE_URL=https://github.com/TomerCo/firmware-utils.git
PKG_SOURCE_DATE:=2022-10-22
PKG_SOURCE_VERSION:=92b26cc7d3e27ea5d99d9207544e83f7d67d29b5
PKG_MIRROR_HASH:=skip

include $(INCLUDE_DIR)/host-build.mk
include $(INCLUDE_DIR)/cmake.mk

$(eval $(call HostBuild))
