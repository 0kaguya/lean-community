# modified from `lean-bin`

pkgname=lean-community
pkgver=3.18.4
pkgrel=2
pkgdesc='Lean Theorem Prover'
arch=('x86_64' 'i386')
url='https://leanprover-coummunity.github.io'
license=('Apache')
depends=('lua>=5.2')
provides=('lean')
conflicts=('lean-git' 'lean-bin' 'lean')
source=("https://github.com/leanprover-community/lean/releases/download/v${pkgver}/lean-${pkgver}-linux.tar.gz")
sha256sums=('6bb6ae5b606a52aa2d02421cbaf53ac156027036cccda94a9d394bb0019fbb94')

package() {
    mkdir -p "$pkgdir/usr"
    cp -r "$srcdir/lean-$pkgver-linux"/* "$pkgdir/usr"
}

