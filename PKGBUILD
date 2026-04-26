# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.50
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

sha256sums_x86_64=('4e2eb95a2645bcd8df44b23d1c717460b4e176f95daa8cd3e320e4a4aca6068c')
sha256sums_aarch64=('917322bfa525b812c0ee428bfb0b88128e82d4fc346eb52a295aa3d45491b30f')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
