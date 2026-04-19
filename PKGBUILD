# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.98.0
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

sha256sums_x86_64=('ab8999ea816ac190dc9767a09a275ce8b977a4c9466fb903fab87cbdfe9e87a0')
sha256sums_aarch64=('c346b9fb2a5b649dc54236b075d0913005f315a20a7912e9335d5d4c7802dd22')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
