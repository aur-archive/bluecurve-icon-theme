# Maintainer: Charles Bos <charlesbos1 AT gmail>
# Contributor: Shawn Dellysse <sdellysse@radford.edu>

pkgname=bluecurve-icon-theme
pkgver=8.0.2_10.fc20
pkgrel=10
pkgdesc="Red Hat Icons from Fedora 10"
arch=('any')
url="https://fedorahosted.org/bluecurve/"
license=('GPL')
groups=('redhat-artwork')
optdepends=(
  'gnome-icon-theme: for inheriting missing icons'
)
source=('ftp://rpmfind.net/linux/fedora/linux/releases/20/Everything/x86_64/os/Packages/b/bluecurve-icon-theme-8.0.2-10.fc20.noarch.rpm')
sha256sums=('e345c3c7f9a47b1aeb2941750dcef548575cc72ef1cfec6a8452906327d78cd9')

package() {
  cp -R "$srcdir/usr" "$pkgdir"
}
