pkgname=mesa-tweaks-blend
pkgver=2022.11.30
pkgrel=1
pkgdesc='Currently relevant tweaks for Mesa such as ray tracing enablement'
url='https://github.com/blend-os/mesa-tweaks-blend'
arch=('any')
license=('Public domain')
optdepends=('mesa'
            'vulkan-radeon'
            'lib32-mesa'
						'lib32-vulkan-radeon')
source=('mesa.sh')
sha256sums=('0d7185df16797acbb13cc45f3f1607f5ebd5c401fc8da9243c03e0ec0449efab')

package() {
	install -d "$pkgdir"/etc/profile.d/
	install -m644 "$srcdir"/mesa.sh "$pkgdir"/etc/profile.d/
}
