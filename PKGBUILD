# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.61
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

sha256sums_x86_64=('4410e5d4f15ecdc9ec753d901b2abb3f2dc7551bb814f1951e38c2f51fd3a9c0')
sha256sums_aarch64=('0a06ca42e5ebfd4e846ecdded7d8acdfacab22086712ffed2b290b509cd5df91')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
