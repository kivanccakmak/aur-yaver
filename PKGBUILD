# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.97
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

sha256sums_x86_64=('e318b3ed22b9694aa53c3af294b23894400963e98df83578e0129bb8b41a6b35')
sha256sums_aarch64=('c94b64cef1e23b6203f93416fe526bc7928b2be0f161e19757f1c5dac380767a')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
