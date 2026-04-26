# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.48
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

sha256sums_x86_64=('d298affacd97f4bbb08255163a2f3eb4f3f232286b01171b0cdfd71bc9ec073e')
sha256sums_aarch64=('2ed3c0bc50c46303c2e4a7fd03a602db814c4103195e0faa177d2dee13b309c1')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
