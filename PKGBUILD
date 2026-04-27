# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.66
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

sha256sums_x86_64=('9492ab164d9d9d30af30fb23f04463a630658ccbce50e1a23d65af6bcb4a0161')
sha256sums_aarch64=('780a39486e90a7454d909d91ff39e075055a1ac79e48c2b169ec59d20cd892e6')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
