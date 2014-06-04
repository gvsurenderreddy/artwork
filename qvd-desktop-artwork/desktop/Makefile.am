deskdir=/etc/skel/.config

desk_DATA = config 




install: install-data

install-data: 
	test -d $(DESTDIR)/$(deskdir) || mkdir -p $(DESTDIR)/$(deskdir)
	cp -pr $(desk_DATA) $(DESTDIR)/$(deskdir)

clean: 
	rm Makefile


