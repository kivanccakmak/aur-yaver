# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.41
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

sha256sums_x86_64=('c5a7649b8f6a6b9f1cd66998fac6b2ae6455ea8eee8383f58849204069c5ac2f')
sha256sums_aarch64=('58a1779c0b3f7a70b08bae560f113e1bfe95143f035cee001f12d1ccd9a67512')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
