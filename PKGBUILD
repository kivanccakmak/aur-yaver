# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.44
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

sha256sums_x86_64=('fb472072b8936e732853812c4b737130795e3828bb8b313dd88e37a36c037f07')
sha256sums_aarch64=('ae34061729a6ad848cca5410273c523c1f250fdb41781819dfce3a3fb0473c5d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
