PACKAGENAME="foxxy-welcome"

all:

clean:

install:
	chmod -R 0755 $(PACKAGENAME)/*
	chmod +x $(PACKAGENAME)/usr/bin/foxxy-welcome
	chmod +x $(PACKAGENAME)/usr/share/foxxy-welcome/browser
	chown root:root $(PACKAGENAME)/*
	cp -rf $(PACKAGENAME)/* $(DESTDIR)/

