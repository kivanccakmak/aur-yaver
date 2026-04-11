# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.80.0
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('MIT')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('0ed0ec33ad94e0d2c3a3a2b7bc4bdb8f13790bb8f3cba23a3a70b4d0c654020c')
sha256sums_aarch64=('9b4bbd06cbeda3ac4c98847639835c9eb9fa9310f8688699fc05605c02ec9468')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
