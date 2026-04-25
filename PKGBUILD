# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.39
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

sha256sums_x86_64=('180fce001e9c85dd64ee04bf8e8b6d6d1c84d7444866de5f07b374aab95f2605')
sha256sums_aarch64=('3a287610c1f55be4c0528df9f13a9b9395974ac987c4e5a4c7738ee2b6c475ae')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
