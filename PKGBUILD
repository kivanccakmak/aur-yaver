# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.8
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

sha256sums_x86_64=('3190b1ceb7ec8730c1f8ac88592c5f08458468c94a209e9fd09504cea44766dd')
sha256sums_aarch64=('c9ec7b3b084c75ffca466511aeec9d63340ad8963ba9dc153ccd6629bfd72184')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
