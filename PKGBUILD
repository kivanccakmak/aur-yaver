# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.72
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

sha256sums_x86_64=('e1a227af8e1b0df86a3878894ba3cf303c7f036d719ed79f15a2aea9d98f5a5f')
sha256sums_aarch64=('bce42ca1fda5875933dc5237f26f7cca2c9f4168f88e0c5fc43e64c5e8ab119f')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
