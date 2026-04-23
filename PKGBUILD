# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.17
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

sha256sums_x86_64=('a77bb9afacc3534dac28d45df9328c5f4a152b41316ea995f958269ea73fba87')
sha256sums_aarch64=('81f6226dedef6ecc9dbff9d3bedc652280338fce0894f2e74eea343ec8bf2ed5')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
