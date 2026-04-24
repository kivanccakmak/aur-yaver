# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.28
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

sha256sums_x86_64=('b7bb5948ac12e5c2d384e8044617b7ba9ad0c622032f0e2bf7547d715330479e')
sha256sums_aarch64=('5aa01b9e746d39c4d4c4cafec19223e0858da336886b4a4cac78ca09cf1884a7')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
