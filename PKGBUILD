# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.43.0
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('MIT')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64")

sha256sums_x86_64=('69e603a8cdd669512eac2255bb8e968f7194d28acc72c4eb27fecfce105de258')
sha256sums_aarch64=('1f2de53802729fcaf28d7164beba7aa44892e88691cfc133a67a28ecae950417')

package() {
    if [ "$CARCH" = "x86_64" ]; then
        install -Dm755 yaver-linux-amd64 "$pkgdir/usr/bin/yaver"
    else
        install -Dm755 yaver-linux-arm64 "$pkgdir/usr/bin/yaver"
    fi
    install -Dm644 /dev/null "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
