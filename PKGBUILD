# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.95.5
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('7dc27204eb683a00944447feecc22775fc5c491e89304b15fcf9d23bc38df95f')
sha256sums_aarch64=('97e6edcc37a0952da29c1f15200fc74af6db14c0bbe3b44399f4b75c74314509')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
