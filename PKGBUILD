# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.109
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

sha256sums_x86_64=('e50f31a01a06859a5391d3ce34787d09f9f46c07b0f2a4a936a9c88d2f3a857d')
sha256sums_aarch64=('43fb57dca3628bcb6fb70cfba09dec60ca13352920df1ce9d5210a6e24667342')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
