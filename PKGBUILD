# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.41.0
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('MIT')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64")

sha256sums_x86_64=('c467f09a927d1a7768164aa7712ced9d4a14306768370cb4f6c74b8edf0dce7c')
sha256sums_aarch64=('c816741928d3f914b00d544e4065ccf9e566794701aeae530a373196ed09149f')

package() {
    if [ "$CARCH" = "x86_64" ]; then
        install -Dm755 yaver-linux-amd64 "$pkgdir/usr/bin/yaver"
    else
        install -Dm755 yaver-linux-arm64 "$pkgdir/usr/bin/yaver"
    fi
}
