#
.PHONY:		build

#
VERSION!=	cat manifest.json | jq -r ".version"

#
build::
	zip -r ../ptt-over18-${VERSION}.zip . -x ".git/*"
