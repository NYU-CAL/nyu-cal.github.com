

index.html : _layouts/default.html _content/index.md _content/sidebar.md _content/header.md
	m4 $< \
	-DMAIN_CONTENT="esyscmd(markdown _content/index.md)" \
	-DLEFT_SIDEBAR="esyscmd(markdown _content/sidebar.md)" \
	-DRIGHT_SIDEBAR= \
	-DHEADER_TEXT="esyscmd(markdown _content/header.md)" \
	-DFOOTER_TEXT= > $@


