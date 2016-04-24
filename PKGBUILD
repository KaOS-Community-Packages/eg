
pkgname=eg
pkgver=0.1.2
pkgrel=1
pkgdesc="eg will give you useful examples right at the command line. Think of it as a companion tool for man."
arch=('x86_64')
url="https://github.com/srsudar/eg"
license=('MIT')
depends=('python3')
options=(!emptydirs)
source=('https://github.com/srsudar/eg/archive/v0.1.1.tar.gz')
sha512sums=('56bdfa64288cf0d976150479398317cc692aef00043edcd364f0ac33ae807d5da0bc419e52fbc90213e6ce332031da8125b7f92fd5618454d52fa12306a36b9b')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  python3 setup.py install --root="$pkgdir/" --optimize=1 --prefix="/usr"
}

# vim:set ts=2 sw=2 et:
