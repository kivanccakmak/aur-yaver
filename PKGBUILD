# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.42
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

sha256sums_x86_64=('6f841181315cb9161a741000dc187301060b2f94bd184f51ae0ef602f0fcf578')
sha256sums_aarch64=('a8e67b6b3bb87e73ea2904dd05aac45963aa37b5083aae02ffac6c579105f5bc')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
