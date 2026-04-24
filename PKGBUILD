# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.30
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

sha256sums_x86_64=('786f89125002dfccbcd955d2fafb20450930583b91bb01668ac1325897f056fe')
sha256sums_aarch64=('7d60819e760ffd28295b0d14525fc777d829e78deddac46ae42243634d9451ff')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
