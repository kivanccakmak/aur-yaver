# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.54.0
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('MIT')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('cd44a1717c29fcc4b94dbaaa97dadede1ae316535ddfb7cbfdcd0e67ac67e709')
sha256sums_aarch64=('92adbf42a07a8d1abcf5591bedc01d96a771f4fd1e736752e00bd47fb8d25d5d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
    install -Dm644 /dev/null "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
