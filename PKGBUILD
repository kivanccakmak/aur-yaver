# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.81
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

sha256sums_x86_64=('7859c2fa2db910e43446ccd5f3686fc7fc182ea353b21ab2cafcef57103b3d47')
sha256sums_aarch64=('ab3ffed994f55f9d52fffdd60d045f426cbe799b8317702e38844cf85d43db8d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
