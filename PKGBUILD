# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.6
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

sha256sums_x86_64=('1d570074b9c7c217c08bcfbe232b130643934438fcbf2ba99541b9724f6f69dd')
sha256sums_aarch64=('ed4409e1d417f5f3fb09e3fb6fee5083e7857462a60dac105fc95a7f03af7e51')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
