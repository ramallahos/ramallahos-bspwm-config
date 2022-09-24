# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-bspwm-config
pkgver=1
pkgrel=1
pkgdesc="BSPWM config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('bspwm' 'ramallahos-autostart')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/bspwm/"
    install -Dm 644 "bspwmrc" "${pkgdir}/etc/skel/.config/bspwm/bspwmrc"
}

