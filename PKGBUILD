# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.57
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

sha256sums_x86_64=('25a929e0a77d3ac3df59651cc81d734516996f9c3be7dcbb10d3477a66a3b684')
sha256sums_aarch64=('74a1db53827d991d921248a94608ccd608af5b7f1112cab2a59eee3fda1780d8')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
