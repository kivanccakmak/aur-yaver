# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.9
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

sha256sums_x86_64=('3f888cb79a38cdffcaeee66263948a203b729e53fe37720ccb3474df49c98ec8')
sha256sums_aarch64=('51aef68b577c7b8a64866b65095c991262d6b55a4b9b0a1b3bfc9f6105017b21')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
