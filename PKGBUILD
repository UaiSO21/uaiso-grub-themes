# Maintainer: Maurício de Lima <mauriciodelima.mol@gmail.com>

pkgname=uaiso-grub-themes
pkgver=$(date +%y.%m.%d)
pkgrel=$(date +%H%M)
arch=('any')
license=('GPL')
url="https://github.com/UaiSO21/uaiso-grub-themes"
pkgdesc="Grub theme UaiSO Evolve Orion"
source=("git+https://github.com/UaiSO21/uaiso-grub-themes.git")
md5sums=(SKIP)


package() {
    cp -r "${srcdir}/uaiso-grub-themes/boot/" "${pkgdir}/"
 }
