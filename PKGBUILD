# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.112
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

sha256sums_x86_64=('5b5d32148e756de20559e247f7bcfddf2db46147d4f2f048e3e8769ef033037b')
sha256sums_aarch64=('5c32bf4f2a72330d624bb8bbd9c9d1e78931fd08e7b78474cc842bbaf33dba2d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
