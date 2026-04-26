# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.53
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

sha256sums_x86_64=('71724384de4765f22319606077b0a8325bf27a38c7924dbfa0a2819912ab8edd')
sha256sums_aarch64=('b3cdb14da22fa154f83c6e71622e979c2bc9c564de8d813fcc4a107321ada574')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
