#
.PHONY:		build

#
VERSION!=	cat manifest.json | jq -r ".version"

#
build::
	zip -r ../ptt-over-18-${VERSION}.zip . -x ".git/*"
