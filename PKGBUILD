# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.108
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

sha256sums_x86_64=('0e950d6b527f02a8d52717a9c206a6812c3d2c4db9183d23d34eeec18e1fdc30')
sha256sums_aarch64=('c6255fec99410d140091f99a8da25372daa45a6e0ebbf660644dc89c9f18cb1b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
