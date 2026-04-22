# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.16
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

sha256sums_x86_64=('e6310a7de80f489272da7fb62df36d50344126289b55e6a13a40029ec3dbeae6')
sha256sums_aarch64=('708568a1fb502ca3e988073e8e0ae5a4151a9fe46e8169afd51c9b16f2ab79a7')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
