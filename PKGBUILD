# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.75.0
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('MIT')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('45ea39879fbb6e71c72d3abd2131023ede902b49a7df8989c21c8fec7c6e0828')
sha256sums_aarch64=('3e9a51a8fe719af61a8d1943d91dff67d74623790bba2e505c9a0416a4e33c4a')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
