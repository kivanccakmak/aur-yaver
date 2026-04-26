# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.49
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

sha256sums_x86_64=('0d39004052d230bb6fd35941ff83c38dedce7fe9de144a3917e5a6a7b135daae')
sha256sums_aarch64=('476772eee7dcc14654924da5fe7bcada80f1f50fbd8e5f7448cd676d9c89d12f')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
