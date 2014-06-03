wallpapersdir=$(datadir)/qvd-desktop-artwork/wallpapers

wallpapers_DATA = wallpaper.jpg




install: install-data

install-data: 
	test -d $(DESTDIR)/$(wallpapersdir) || mkdir -p $(DESTDIR)/$(wallpapersdir)
	cp $(wallpapers_DATA) $(DESTDIR)/$(wallpapersdir)

clean: 
	rm Makefile


