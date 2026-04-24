# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.33
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

sha256sums_x86_64=('155588a77c10154b14aeae3f1b25a88445a39b8ca921f6e0dfed783cd4040105')
sha256sums_aarch64=('b21f55519b7242922cc5a6ed7b276e00a501517f3d29926a14c2bfa5e487bed3')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
