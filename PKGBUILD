# modified from `lean-bin`

pkgname=lean-community
pkgver=3.20.0
pkgrel=1
pkgdesc='Lean Theorem Prover'
arch=('x86_64' 'i386')
url='https://leanprover-coummunity.github.io'
license=('Apache')
depends=('lua>=5.2')
provides=('lean')
conflicts=('lean-git' 'lean-bin' 'lean')
source=("https://github.com/leanprover-community/lean/releases/download/v${pkgver}/lean-${pkgver}-linux.tar.gz")
sha256sums=('4a5b26d8eb5c82fec790db37b87204549f6667ce7097d7526df9e9692d1d4f14')

package() {
    mkdir -p "$pkgdir/usr"
    cp -r "$srcdir/lean-$pkgver-linux"/* "$pkgdir/usr"
}


