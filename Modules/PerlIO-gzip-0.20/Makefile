NAME = PerlIO-gzip
VERSION = 0.20

include ../Makefile.inc

custompatching:
	sed -e 's#@SDKROOT@#$(SDKROOT)#g' "$(MYSRC)/perlio-gzip-use-sdk.patch" | patch -d "$(DIR)" -p1
