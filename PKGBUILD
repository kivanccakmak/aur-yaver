# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.115
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

sha256sums_x86_64=('10e587eeda77efff8a93b04e106a69c3b5adf03ab624ea6e06f8e264d5fc912d')
sha256sums_aarch64=('baad8d4084b6fefc0b8a76481a4400e2681b5cac55c6f73dbcdc45502341c214')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
