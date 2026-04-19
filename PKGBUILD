# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.4
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

sha256sums_x86_64=('5ffad274264ccd408b136152a9d887a264a792f0613d015deb8fdee8b39bb155')
sha256sums_aarch64=('753219618b4ce08887c9386ac6555cf27c4289f28ae28a1419e3458283a12034')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
