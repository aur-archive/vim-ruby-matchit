# Maintainer: TDY <tdy@archlinux.info>

pkgname=vim-ruby-matchit
pkgver=0.1
_src_id=848
pkgrel=1
pkgdesc="Matchit for Ruby, inspired by 'matchit.vim' that comes with Vim"
arch=('any')
url="http://www.vim.org/scripts/script.php?script_id=290"
license=('GPL')
groups=('vim-plugins')
depends=('vim')
source=(${pkgname#*-}-$pkgver.vim::http://www.vim.org/scripts/download_script.php?src_id=$_src_id)
md5sums=('2d4aa07b6d9fd48013c93f08d0cdf331')

package() {
  install -Dm644 "$srcdir/${pkgname#*-}-$pkgver.vim" \
    "$pkgdir/usr/share/vim/vimfiles/ftplugin/ruby/${pkgname#*-}.vim"
}

# vim:set ts=2 sw=2 et:
