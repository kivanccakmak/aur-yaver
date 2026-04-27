# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.88
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

sha256sums_x86_64=('c09f67adfc66f5df82f44b0e8bd1fad280e89d8852439f12eff495dc945d6641')
sha256sums_aarch64=('c2a48c564a87f14901baaebb828be64d5b0a39724a695444bb707f12dc180d9d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
