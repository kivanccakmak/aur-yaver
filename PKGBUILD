# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.37
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

sha256sums_x86_64=('6967f536c7feb694094758bdf86ed082eebd56eab3bddbdcbc2787d90e5d0907')
sha256sums_aarch64=('d4e433a64bab65e8ad30e3f36341be8ce46bd74895f05ed86a9d1ff4f6622278')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
