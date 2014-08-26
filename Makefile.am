SUBDIRS = src

deb:
	checkinstall -t debian --install=no --fstrans \
	--pkgname=$(PACKAGE_TARNAME) \
	--pkgversion=$(PACKAGE_VERSION) \
	--pkggroup=admin \
	--pkglicense=GPL \
	--maintainer='"Daniel Miranda <danielkza2@gmail.com>"' \
	--requires=lxc,lxc-templates,bash,libc6