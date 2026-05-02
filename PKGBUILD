# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.118
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

sha256sums_x86_64=('cbfc2aaa753e6324eddaff319c45392a2737519d8cdd807275a2e696a48a0d9c')
sha256sums_aarch64=('d0221b4cc5a8fea2f5f21fd757049900cbd5a0a2be9c4ccaad66be2d4341e5ea')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
