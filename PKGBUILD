# Generated by gem2arch
# Maintainer: LeeF

_gemname=activeresource
pkgname=ruby-enterprise-activeresource-235
pkgver=2.3.5
pkgrel=1
pkgdesc="Think Active Record for web resources."
arch=('i686' 'x86_64')
url="http://www.rubyonrails.org"
license=('MIT')
depends=('ruby-enterprise' 'ruby-enterprise-activesupport-235')
makedepends=('ruby-enterprise')
source=(http://gems.rubyforge.org/gems/$_gemname-$pkgver.gem)
noextract=($_gemname-$pkgver.gem)
md5sums=('d66534fe7c40498d6fa7229122f74f23')

build() {
  cd $srcdir
  local _gemdir=`ruby -rubygems -e'puts Gem.default_dir'`
  gem install --ignore-dependencies --no-rdoc --no-ri -i "$pkgdir$_gemdir" $_gemname-$pkgver.gem
}
