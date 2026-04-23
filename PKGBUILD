# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.20
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

sha256sums_x86_64=('f921aa9a751d28530d2d17987c8aeec6d9c0583aabcc0cead218ae660f1cfccd')
sha256sums_aarch64=('1fd7640adb1406c54a148edda2814b5e5a6106be26af94399bab1a5599707272')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
