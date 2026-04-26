# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.54
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

sha256sums_x86_64=('72281d7c7c1573de4f89c8bf3cd88e1dc20e4b1fe1b99e8c092fbea4a86985ab')
sha256sums_aarch64=('ee20259549531cf0f3b7125ea0d4f1f38e93667e2faacb10b253f2a2b087abdc')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
