# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.85
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

sha256sums_x86_64=('092f259414ae745b48ea88eaa55857f449c76bd8a99440e8f6cb882c137fa988')
sha256sums_aarch64=('f131a863925fcc65143ece0283955df9189d2940bb864b21705d9e53c4fecf87')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
