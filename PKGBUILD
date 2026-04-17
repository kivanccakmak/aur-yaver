# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.95.4
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('1f4c7dbf406e92d806d19fa4ed00317930869a9b8e6ae8b69d27e6f92d37eb94')
sha256sums_aarch64=('0536a6d43197958467fed207630a068a5fe05182969f39ea1ee936ef25d7316f')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
