# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.1
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

sha256sums_x86_64=('08776ba90146b54a4a48f8a777eff4d566ed732360e955796fbe0956903f5ced')
sha256sums_aarch64=('6f3385534e7435e66692cac690e5fbf82ed84994f1ce11761f116c496b9f85f3')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
