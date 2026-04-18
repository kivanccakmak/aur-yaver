# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.9
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('d909ad62b13c91c3b64d564ca4da8d246435d65b6d846d0b6b2ffc3c50fea153')
sha256sums_aarch64=('8035a722a73ab765a7479839044db080926d47895624ea19bfbba683e021dc22')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
