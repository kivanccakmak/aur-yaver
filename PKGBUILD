# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.58
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

sha256sums_x86_64=('fc224bf08bc707126a5f7179eb647e65dd09142ebc0c7b2c6cf87b7e3b953160')
sha256sums_aarch64=('0333be4099ec4fa9cabb41bd625a2b7561211dfa7bee0dfa1847e0afdaee1cdb')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
