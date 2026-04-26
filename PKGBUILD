# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.56
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

sha256sums_x86_64=('f27646a47630b07d718c9077f3c2d7cee1f0e5bb088a2498c521e65ba12adaa2')
sha256sums_aarch64=('ba36599941db2fbebdabb21619e51b97d4cb260f1f7df978193e98732a1a5fb6')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
