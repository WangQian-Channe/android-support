# Maintainer: Daniel Hillenbrand <codeworkx [at] bbqlinux [dot] org>
 
pkgname=android-support
pkgver=r19
pkgrel=1
pkgdesc='Android Support Package'
arch=('any')
url="https://developer.android.com/sdk/compatibility-library.html"
license=('custom')
depends=('android-sdk')
options=('!strip')
source=("http://dl-ssl.google.com/android/repository/support_${pkgver}.zip")
sha1sums=('54b8661595856a08f032d41bb139f375a7609308')
 
package() {
mkdir -p "${pkgdir}/opt/android-sdk/extras/android/"
mv "${srcdir}/support" "${pkgdir}/opt/android-sdk/extras/android/support"
 
chmod -R ugo+rX "${pkgdir}/opt"
}
