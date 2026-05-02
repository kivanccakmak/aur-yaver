# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.116
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

sha256sums_x86_64=('ac31347d1570129718410786feb376c29712336b59d191fac259f118837f11ee')
sha256sums_aarch64=('89c9f590e500e3664a7f3608d82d511ed3989c1839a69ab4674e4e81629c51f1')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
