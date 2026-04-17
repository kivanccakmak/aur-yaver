# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.95.3
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('bae44d1c0d8e855c57c4919ee3b19adc24ffe32deb447ca39a06df8cee0f5e12')
sha256sums_aarch64=('52fe7215d2f128848143a157faf641d1414b88a0e4c8a268f874e2c614a33ca9')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
