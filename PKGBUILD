# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.70
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

sha256sums_x86_64=('62bb46f9096d408ed2c7498a46f9ec7e563392b3455fd7318dc9a64649b185d6')
sha256sums_aarch64=('401f8684b0ce0dfe4e4c83a42c73281168fba112777a0858802e69c921c4cab6')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
