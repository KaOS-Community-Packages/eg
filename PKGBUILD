
pkgname=eg
pkgver=0.1.2
pkgrel=1
pkgdesc="eg will give you useful examples right at the command line. Think of it as a companion tool for man."
arch=('x86_64')
url="https://github.com/srsudar/eg"
license=('MIT')
depends=('python3')
options=(!emptydirs)
source=("https://github.com/srsudar/eg/archive/v${pkgver}.tar.gz")
sha512sums=('2d701331ab204919458fb31a2be93cfa569578717bfa8b62a270c0e5c3c6926e7ceb010f77cf220061c04c626c04005d13967098b52e4391c6f8744540204178')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  python3 setup.py install --root="$pkgdir/" --optimize=1 --prefix="/usr"
}

# vim:set ts=2 sw=2 et:
