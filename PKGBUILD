# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.113
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

sha256sums_x86_64=('f34cab4801db960a67222590041d9b1f3a4b590d4711694644ca84d70b2e2b48')
sha256sums_aarch64=('ce158bfc3c0256883ef82c39e40374cfa7d1cd31a33e0b110739def7ff5939d4')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
