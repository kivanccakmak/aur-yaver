# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.82
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

sha256sums_x86_64=('80b35084e46df9029ae70cff9ccd74331ec526fc1120c4c9386b73ca55420819')
sha256sums_aarch64=('4ccd790355964f56e39b8823e265e42e4825b3541478dbec6b0be34a685938de')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
