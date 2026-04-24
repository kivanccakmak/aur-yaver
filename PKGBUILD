# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.36
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

sha256sums_x86_64=('f5fcbfc91fe6660c77d4dcb522ed3dba91dff71859ed94616e58f4d3ec5da4ac')
sha256sums_aarch64=('a80b02bb5b8b330e04ea8cbd675e99256cf991b16b8ea779f3310763199e02df')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
