pkgname=plymouth-theme-seaglass
pkgver=1
pkgrel=3
pkgdesc="SeaGlass Plymouth boot splash theme"
arch=(any)
license=(MIT)
depends=(plymouth)

package() {
  local theme="$pkgdir/usr/share/plymouth/themes/seaglass"
  install -Dm644 -t "$theme" "$startdir/seaglass.plymouth" "$startdir"/assets/*.png "$startdir"/assets/loading/*.png
}
