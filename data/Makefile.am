SUBDIRS = countries display fonts extensions keymaps skin_default skin_fallback_1080 rc_models

dist_pkgdata_DATA = \
	black.mvi \
	encoding.conf \
	freesat.t1 \
	freesat.t2 \
	groupedservices \
	iso-639-3.pck \
	keymap.xml \
	keytranslation.xml \
	menu.xml \
	otv_00820000_fbff_16a8.dict \
	otv_011a0000_0002_07d4.dict \
	otv_06180000_1000_0011.dict \
	otv_06400000_00a9_0003.dict \
	prev.png \
	radio.mvi \
	rcpositions.xml \
	setup.xml \
	skin.xml \
	skin_default.xml \
	skin_subtitles.xml \
	startwizard.xml \
	unicable.xml

iso-639-3.pck: $(srcdir)/iso-639-3.tab
	python $(srcdir)/convert-iso-639-3.py $< $@
