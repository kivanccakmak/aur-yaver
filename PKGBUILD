# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.95.7
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('d112f09136f2e3b32d7c1a43dec1608f8c62b750b033a02fdc392c957c8b0930')
sha256sums_aarch64=('9596b1ea4b47998fce592ec181edb82102aa96fa38a2a8b36b11e7abc22aba00')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
