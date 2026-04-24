# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.29
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

sha256sums_x86_64=('b9c745507f5ddf5cf393cbc58a3c00892fdffa2ccb886d93874b0919fa19b2f1')
sha256sums_aarch64=('d38723b2fe8056e1d60d1a75a7d0b9dff65a0da67b357efa14c29b2251fd4aa0')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
