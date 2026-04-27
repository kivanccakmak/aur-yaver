# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.65
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

sha256sums_x86_64=('bbe830ad8364a8cd2bc5985e6087ffefd2c54b88e2bc58e12d52ed572359aab9')
sha256sums_aarch64=('f26003e9cee5e8668eefd91a5bed5f4ed3568c3d5ae138aaf4a77ed2c32b60bd')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
