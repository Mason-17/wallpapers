pkgname="Wallpapers"
pkgver="3.0"
pkgrel="1"
pkgdesc="A huge wallpaper pack, installable with pacman!"
arch=("x86_64")
url="https://github.com/Mason-17/wallpapers"
license=("custom")
source=("https://github.com/Mason-17/wallpapers/releases/download/$pkgver/wallpapers.tar.xz")
sha512sums=("SKIP")
package() {
	install -Dm644 abstract/* -t "$pkdir/usr/share/backgrounds/viper/abstract/"
	install -Dm644 anime/* -t "$pkdir/usr/share/backgrounds/viper/anime/"
	install -Dm644 catppuccin/* -t "$pkdir/usr/share/backgrounds/viper/catppuccin/"
	install -Dm644 dragons/* -t "$pkdir/usr/share/backgrounds/viper/dragons/"
	install -Dm644 evangelion/* -t "$pkdir/usr/share/backgrounds/viper/evangelion/"
	install -Dm644 exodia/* -t "$pkdir/usr/share/backgrounds/viper/exodia/"
	install -Dm644 gruvbox/* -t "$pkdir/usr/share/backgrounds/viper/gruvbox/"
	install -Dm644 halo/* -t "$pkdir/usr/share/backgrounds/viper/halo/"
	install -Dm644 landscapes/* -t "$pkgdir/usr/share/backgrounds/viper/landscapes/"
	install -Dm644 linux/* -t "$pkdir/usr/share/backgrounds/viper/linux/"
	install -Dm644 mechs/* -t "$pkgdir/usr/share/backgrounds/viper/mechs/"
	install -Dm644 misc/* -t "$pkdir/usr/share/backgrounds/viper/misc/"
	install -Dm644 sonic/* -t "$pkgdir/usr/share/backgrounds/viper/sonic/"
	install -Dm644 star-wars/* -t "$pkdir/usr/share/backgrounds/viper/star-wars/"
	install -Dm644 warhammer-40k/* -t "$pkgdir/usr/share/backgrounds/viper/warhammer-40k/"
}
