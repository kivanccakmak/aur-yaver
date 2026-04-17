# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.95.2
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('2c97cbb2e5e954083adce960e59e3a1d485e162b63b8dfcede75c313997238cd')
sha256sums_aarch64=('561274b787b239d9360f446fd7686faae53de31be77b3a653809a6773640faeb')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
