SUBDIRS = src

doc-pak: README LICENSE INSTALL
	mkdir -p $@
	cp $? $@/

deb: description-pak doc-pak
	checkinstall -t debian --install=no --fstrans \
	--pkgname=$(PACKAGE_TARNAME) \
	--pkgversion=$(PACKAGE_VERSION) \
	--pkggroup=admin \
	--pkglicense=GPL \
	--maintainer='"Daniel Miranda <danielkza2@gmail.com>"' \
	--requires=libc6,bash,lxc,lxc-templates,openssl

mostlyclean-local:
	-rm -rf doc-pak
