# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.55
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

sha256sums_x86_64=('8ab82ba72c763ccfb361d9c6e31789119f5801e7616d73d1067d2ee4ebd85b3a')
sha256sums_aarch64=('7359fa1646da6bb8cb525f5b9b6009430efe6a52f0f51e8c8c7b66ccf9b8669b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
