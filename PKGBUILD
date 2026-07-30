# / AArch64 Xiaomi Pad 5
# Maintainer: Xander-trav

buildarch=8

pkgbase=linux-nabu
pkgver=6.18.41
pkgrel=1
_srcname="linux-${pkgver%.*}"
_kernelname=${pkgbase#linux}
_desc="AArch64 Xiaomi Pad 5"
arch=('aarch64')
url="http://www.kernel.org/"
license=('GPL-2.0-only')
makedepends=('xmlto' 'docbook-xsl' 'kmod' 'inetutils' 'bc' 'git' 'uboot-tools' 'dtc' 'python3' 'systemd-ukify' 'sbsigntools')
options=('!strip')
source=("https://www.kernel.org/pub/linux/kernel/v6.x/${_srcname}.tar.xz"
        "https://www.kernel.org/pub/linux/kernel/v6.x/patch-${pkgver}.xz"
        'config'
        '0001-arm64-dts-rockchip-disable-pwm0-on-rk3399-firefly.patch'
        '0002-pps-Compatibility-hack-should-be-X86-specific.patch'
        '0003-Revert-arm64-dts-rockchip-Move-rk3568-PCIe3-MSI-to-u.patch'
        '0004-serial-amba-pl011-add-arm-pl011-axi-binding-for-RP1.patch'
        '0005-arm64-dts-rpi5-add-RP1-UART0-GPIO14-15-console.patch'
        '0006-SM8150-Add-uart13-node.patch'
        '0007-SM8150-Add-device-tree-for-Xiaomi-Pad-5.patch'
        '0008-drm-Add-drm-notifier-support.patch'
        '0009-drm-dsi-emit-panel-turn-on-off-signal-to-touchscreen.patch'
        '0010-Input-Add-nt36523-touchscreen-driver.patch'
        '0011-nt36xxx-Fix-module-autoload.patch'
        '0012-NABU-Added-novatek-touchscreen-node.patch'
        '0013-drm-panel-nt36523-Add-Xiaomi-Pad-5-CSOT-panel.patch'
        '0014-NABU-Enable-gpu-dsi0-and-dsi1.-Added-panel-and-backl.patch'
        '0015-SM8150-Add-apr-nodes.patch'
        '0016-ASoC-qcom-SM8150-Add-machine-driver.patch'
        '0017-NABU-Add-sound-nodes.patch'
        '0018-power-supply-Add-driver-for-Qualcomm-PMIC-fuel-gauge.patch'
        '0019-power-qcom_fg-Add-initial-pm8150b-support.patch'
        '0020-arm64-dts-qcom-pm8150b-Add-fuel-gauge.patch'
        '0021-NABU-Add-pmic-fg-and-battery-nodes.patch'
        '0022-SM8150-Add-slimbus-nodes.patch'
        '0023-arm64-dts-add-wcd9340-device-tree-binding-for-sm8150.patch'
        '0024-ASoC-qcom-SM8150-Add-slimbus-audio-support-Also-adde.patch'
        '0025-ASoC-qcom-sm8150-Fix-compilation-in-v6.7.0.patch'
        '0026-NABU-Add-wcd9340-and-microphone-dais.patch'
        '0027-drm-msm-dsi-change-sync-mode-to-sync-on-DSI0-rather-.patch'
        '0028-input-nt36xxx-Enable-pen-support.patch'
        '0029-drm-panel-nt36523-Enable-120fps-for-nabu-csot.patch'
        '0030-NABU-Add-pm8150b-type-c-node-and-enable-otg.patch'
        '0031-NABU-Add-fsa4480-node.patch'
        '0032-NABU-Enable-secondary-usb-and-keyboard-MCU.patch'
        '0033-input-nt36523-Remove-fw-boot-delay.-Should-be-fine-b.patch'
        '0034-NABU-Add-flash-led-node.patch'
        '0035-NABU-Add-ln8000-fast-charge-IC-for-testing.-If-it-sa.patch'
        '0036-NABU-Add-hall-sensor-for-magnetic-cover-detection.-H.patch'
        '0037-NABU-DISABLED-Set-panel-rotation.-https-gitlab.com-s.patch'
        '0038-NABU-Remove-framebuffer-initialized-by-XBL-https-git.patch'
        '0039-NABU-Remove-deprecated-usb_1_role_switch_out-node.patch'
        '0040-of-property-fix-remote-endpoint-parse.patch'
        '0041-drivers-gpu-drm-drm_notifier.c-add-include-drm-drm_n.patch'
        '0042-arch-arm64-boot-dts-qcom-sm8150-xiaomi-nabu.dts-add-.patch'
        '0043-arch-arm64-boot-dts-qcom-sm8150-xiaomi-nabu.dts-add-.patch'
        '0044-arch-arm64-boot-dts-qcom-sm8150.dtsi-change-reset-na.patch'
        '0045-NABU-enable-rtc.patch'
        '0046-NABU-disable-Sensor-Low-Power-Island.patch'
        '0047-NABU-enable-ln8000-charger-driver.patch'
        '0048-clk-qcom-gcc-change-halt_check-for-gcc_ufs_phy_tx-rx.patch'
        '0049-clk-qcom-clk-regmap-Add-udelay-in-clk_enable_regmap-.patch'
        '0050-nt36xxx-add-pen-input-resolution.patch'
        '0051-arch-arm64-boot-dts-qcom-sm8150-add-ufs-dependecy-on.patch'
        '0052-arch-arm64-boot-dts-qcom-sm8150-disable-broken-crypt.patch'
        '0053-nt36xxx-Change-pen-resolution-This-is-done-to-be-abl.patch'
        'linux.preset')
sha256sums=('9106a4605da9e31ff17659d958782b815f9591ab308d03b0ee21aad6c7dced4b'
            '28c327c663991f98233fb900d0ae9d92e41c5120aa4a21a2290773b672a2b2fb'
            'SKIP'
            '3cc4e31aef52c091b86609f2750069cad44a089c3b9228585d2375b72967d076'
            'b0ac7e7828601b034c5f82cf5d0bf7a0fdc67fc79644fc4ebd2ac20c167c13a7'
            '9b7bbd201e08602a829fb1293541764863dddcc4f046e5befd801a9af78ca9e9'
            'ca9adf0aed11a8b2372998477cc9e91ea3564cef7066d6ddc4fd0007dbe5d4e5'
            '9884639546f2d7612518ba8e4d0b01ca2c5f919370059f2c71542a7adc031901'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP'
            'SKIP')

prepare() {
  cd $_srcname

  echo "Setting version..."
  echo "-$pkgrel" > localversion.10-pkgrel
  echo "${pkgbase#linux}" > localversion.20-pkgname

  # add upstream patch
  if [[ -f ../patch-${pkgver} ]]; then
    git apply --whitespace=nowarn ../patch-${pkgver}
  fi

  # ALARM patches
  git apply ../0001-arm64-dts-rockchip-disable-pwm0-on-rk3399-firefly.patch
  git apply ../0002-pps-Compatibility-hack-should-be-X86-specific.patch
  git apply ../0003-Revert-arm64-dts-rockchip-Move-rk3568-PCIe3-MSI-to-u.patch
  git apply ../0004-serial-amba-pl011-add-arm-pl011-axi-binding-for-RP1.patch
  git apply ../0005-arm64-dts-rpi5-add-RP1-UART0-GPIO14-15-console.patch

  # nabu patches (0006+)
  for src in "${source[@]}"; do
    src="${src%%::*}"
    src="${src##*/}"
    [[ $src = *.patch ]] || continue
    [[ $src = 000[1-5]-* ]] && continue
    msg2 "Applying nabu patch: $src..."
    patch -Np1 < "../$src"
  done

  cat "${srcdir}/config" > ./.config
  make olddefconfig
}

build() {
  cd ${_srcname}

  # get kernel version
  make prepare
  make -s kernelrelease > version

  # build!
  unset LDFLAGS
  make ${MAKEFLAGS} Image Image.gz modules
  # Generate device tree blobs with symbols to support applying device tree overlays in U-Boot
  make ${MAKEFLAGS} DTC_FLAGS="-@" dtbs
}

_package_common() {
  echo "Installing boot image and dtbs..."
  install -Dm644 arch/arm64/boot/Image "${pkgdir}/boot/vmlinux-${kernver}"
  install -Dm644 arch/arm64/boot/Image.gz "${pkgdir}/boot/vmlinuz-${kernver}"
  install -Dm644 arch/arm64/boot/dts/qcom/sm8150-xiaomi-nabu.dtb "${pkgdir}/boot/dtb-${kernver}"

  echo "Installing modules..."
  make INSTALL_MOD_PATH="$pkgdir/usr" INSTALL_MOD_STRIP=1 DEPMOD=/doesnt/exist modules_install

  # remove build link
  rm "$pkgdir/usr/lib/modules/$kernver/build"
}

_package() {
  pkgdesc="The Linux Kernel and modules - ${_desc}"
  depends=('coreutils' 'linux-firmware' 'kmod' 'mkinitcpio>=0.7')
  optdepends=('wireless-regdb: to set the correct wireless channels of your country')
  provides=("linux=${pkgver}" "KSMBD-MODULE" "WIREGUARD-MODULE")
  conflicts=('linux')
  install=${pkgname}.install

  cd $_srcname
  local kernver="$(<version)"

  _package_common

  # sed expression for following substitutions
  local _subst="
    s|%PKGBASE%|${pkgbase}|g
    s|%KERNVER%|${kernver}|g
  "

  # install mkinitcpio preset file
  sed "${_subst}" ../linux.preset |
    install -Dm644 /dev/stdin "${pkgdir}/etc/mkinitcpio.d/${pkgbase}.preset"

  # rather than use another hook (90-linux.hook) rely on mkinitcpio's 90-mkinitcpio-install.hook
  # which avoids a double run of mkinitcpio that can occur
  install -d "${pkgdir}/usr/lib/initcpio/"
  echo "dummy file to trigger mkinitcpio to run" > "${pkgdir}/usr/lib/initcpio/$(<version)"
}

_package-uki() {
  pkgdesc="The Linux Kernel and modules - ${_desc} (UKI)"
  depends=('coreutils' 'linux-firmware' 'kmod')
  optdepends=('wireless-regdb: to set the correct wireless channels of your country')
  provides=("linux=${pkgver}" "KSMBD-MODULE" "WIREGUARD-MODULE")
  conflicts=('linux')

  cd $_srcname
  local kernver="$(<version)"

  _package_common

  if [[ ! -f "$SB_SIGN_KEY" || ! -f "$SB_SIGN_CERT" ]]; then
    error "**********************************************"
    error "To build UKI version, you MUST provide:"
    error "1. SB_SIGN_KEY:    Path to private key"
    error "2. SB_SIGN_CERT:   Path to certificate"
    error "Set these via environment variables:"
    error "   export SB_SIGN_KEY=/path/to/key"
    error "   export SB_SIGN_CERT=/path/to/cert"
    error "**********************************************"
    exit 1
  fi

  local cmdline_quiet="quiet splash loglevel=3 systemd.show_status=auto rd.udev.log_level=3 vt.global_cursor_default=0"
  local cmdline_root="root=PARTLABEL=linux rw"
  local cmdline_console="console=tty0"
  local cmdline_other="systemd.gpt_auto=no cryptomgr.notests"

  mkdir -p "${pkgdir}/boot/efi/EFI/arch"
  ukify build \
    --linux="${pkgdir}/boot/vmlinux-${kernver}" \
    --cmdline="${cmdline_console} ${cmdline_root} ${cmdline_quiet} ${cmdline_other}" \
    --uname="${kernver}" \
    --devicetree="${pkgdir}/boot/dtb-${kernver}" \
    --os-release="Arch Linux ARM" \
    --secureboot-private-key="$SB_SIGN_KEY" \
    --secureboot-certificate="$SB_SIGN_CERT" \
    --output="${pkgdir}/boot/efi/EFI/arch/uki-${kernver}.efi"
}

_package-headers() {
  pkgdesc="Header files and scripts for building modules for linux kernel - ${_desc}"
  provides=("linux-headers=${pkgver}")
  conflicts=('linux-headers')

  cd $_srcname
  local builddir="$pkgdir/usr/lib/modules/$(<version)/build"

  echo "Installing build files..."
  install -Dt "$builddir" -m644 .config Makefile Module.symvers System.map \
    localversion.* version vmlinux
  install -Dt "$builddir/kernel" -m644 kernel/Makefile
  install -Dt "$builddir/arch/arm64" -m644 arch/arm64/Makefile
  cp -t "$builddir" -a scripts

  mkdir -p "$builddir"/{fs/xfs,mm}

  echo "Installing headers..."
  cp -t "$builddir" -a include
  cp -t "$builddir/arch/arm64" -a arch/arm64/include
  install -Dt "$builddir/arch/arm64/kernel" -m644 arch/arm64/kernel/asm-offsets.s
  mkdir -p "$builddir/arch/arm"
  cp -t "$builddir/arch/arm" -a arch/arm/include

  install -Dt "$builddir/drivers/md" -m644 drivers/md/*.h
  install -Dt "$builddir/net/mac80211" -m644 net/mac80211/*.h

  install -Dt "$builddir/drivers/media/i2c" -m644 drivers/media/i2c/msp3400-driver.h
  install -Dt "$builddir/drivers/media/usb/dvb-usb" -m644 drivers/media/usb/dvb-usb/*.h
  install -Dt "$builddir/drivers/media/dvb-frontends" -m644 drivers/media/dvb-frontends/*.h
  install -Dt "$builddir/drivers/media/tuners" -m644 drivers/media/tuners/*.h

  install -Dt "$builddir/drivers/iio/common/hid-sensors" -m644 drivers/iio/common/hid-sensors/*.h

  echo "Installing KConfig files..."
  find . -name 'Kconfig*' -exec install -Dm644 {} "$builddir/{}" \;

  echo "Removing unneeded architectures..."
  local arch
  for arch in "$builddir"/arch/*/; do
    [[ $arch = */arm64/ || $arch == */arm/ ]] && continue
    echo "Removing $(basename "$arch")"
    rm -r "$arch"
  done

  echo "Removing documentation..."
  rm -r "$builddir/Documentation"

  echo "Removing broken symlinks..."
  find -L "$builddir" -type l -printf 'Removing %P\n' -delete

  echo "Removing loose objects..."
  find "$builddir" -type f -name '*.o' -printf 'Removing %P\n' -delete

  echo "Stripping build tools..."
  local file
  while read -rd '' file; do
    case "$(file -bi "$file")" in
      application/x-sharedlib\;*)
        strip -v $STRIP_SHARED "$file" ;;
      application/x-archive\;*)
        strip -v $STRIP_STATIC "$file" ;;
      application/x-executable\;*)
        strip -v $STRIP_BINARIES "$file" ;;
      application/x-pie-executable\;*)
        strip -v $STRIP_SHARED "$file" ;;
    esac
  done < <(find "$builddir" -type f -perm -u+x ! -name vmlinux -print0)

  echo "Adding symlink..."
  mkdir -p "$pkgdir/usr/src"
  ln -sr "$builddir" "$pkgdir/usr/src/$pkgbase"
}

pkgname=("${pkgbase}" "${pkgbase}-headers" "${pkgbase}-uki")
for _p in ${pkgname[@]}; do
  eval "package_${_p}() {
    _package${_p#${pkgbase}}
  }"
done
