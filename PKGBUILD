# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.15
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('custom:FSL-1.1-Apache-2.0')
provides=('yaver')
depends=('nodejs')
optdepends=('npm: for yaver push (React Native to device)')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('b72c49e823e7d7e62657f0aeea4960fcfa6d5a6c8e349ae57f264b595a0c7c99')
sha256sums_aarch64=('12246452ca94eb2c4213830fd36b9fc97ffd7afc01d399faf05212654ccd214e')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
