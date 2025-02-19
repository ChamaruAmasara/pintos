# Makefile for program source directory in GNU NLS utilities package.
# Copyright (C) 1995, 1996, 1997 by Ulrich Drepper <drepper@gnu.ai.mit.edu>
# Copyright (C) 2003-2016 Free Software Foundation, Inc.
#
# This file may be copied and used freely without restrictions.  It can
# be used in projects which are not available under the GNU Public License
# but which still want to provide support for the GNU gettext functionality.
# Please note that the actual code is *not* freely available.

PACKAGE = opcodes
VERSION = 2.27

SHELL = /bin/sh


srcdir = ../../../../src/binutils-2.27/opcodes/po
top_srcdir = ../../../../src/binutils-2.27/opcodes
VPATH = ../../../../src/binutils-2.27/opcodes/po
top_builddir = ..

prefix = /home/chamaru/Desktop/pintos/src/Desktop/pintos/src/misc/toolchain-build.sh/x86_64
exec_prefix = ${prefix}
datadir = $(prefix)/
localedir = $(datadir)/locale
gnulocaledir = $(prefix)/share/locale
gettextsrcdir = $(prefix)/share/gettext/po
subdir = po

DESTDIR =

INSTALL = /usr/bin/install -c
INSTALL_DATA = /usr/bin/install -c -m 644
MKINSTALLDIRS = $(top_builddir)/../../../src/binutils-2.27/opcodes/../mkinstalldirs

CC = gcc
GENCAT = 
GMSGFMT = PATH=../src:$$PATH /usr/bin/msgfmt
MSGFMT = /usr/bin/msgfmt
XGETTEXT = PATH=../src:$$PATH /usr/bin/xgettext
MSGMERGE = PATH=../src:$$PATH msgmerge

DEFS = -DHAVE_CONFIG_H
CFLAGS = -g -O2
CPPFLAGS = 

INCLUDES = -I.. -I$(top_srcdir)/intl

COMPILE = $(CC) -c $(DEFS) $(INCLUDES) $(CPPFLAGS) $(CFLAGS) $(XCFLAGS)

SOURCES = cat-id-tbl.c
POFILES =  $(srcdir)/fr.po $(srcdir)/sv.po $(srcdir)/tr.po $(srcdir)/es.po $(srcdir)/da.po $(srcdir)/de.po $(srcdir)/id.po $(srcdir)/pt_BR.po $(srcdir)/ro.po $(srcdir)/nl.po $(srcdir)/fi.po $(srcdir)/vi.po $(srcdir)/ga.po $(srcdir)/zh_CN.po $(srcdir)/it.po $(srcdir)/uk.po
GMOFILES =  $(srcdir)/fr.gmo $(srcdir)/sv.gmo $(srcdir)/tr.gmo $(srcdir)/es.gmo $(srcdir)/da.gmo $(srcdir)/de.gmo $(srcdir)/id.gmo $(srcdir)/pt_BR.gmo $(srcdir)/ro.gmo $(srcdir)/nl.gmo $(srcdir)/fi.gmo $(srcdir)/vi.gmo $(srcdir)/ga.gmo $(srcdir)/zh_CN.gmo $(srcdir)/it.gmo $(srcdir)/uk.gmo
DISTFILES = ChangeLog Makefile.in.in POTFILES.in $(PACKAGE).pot \
stamp-cat-id $(POFILES) $(GMOFILES) $(SOURCES)

POTFILES = \
     ../../../../src/binutils-2.27/opcodes/aarch64-asm-2.c \
     ../../../../src/binutils-2.27/opcodes/aarch64-asm.c \
     ../../../../src/binutils-2.27/opcodes/aarch64-asm.h \
     ../../../../src/binutils-2.27/opcodes/aarch64-dis-2.c \
     ../../../../src/binutils-2.27/opcodes/aarch64-dis.c \
     ../../../../src/binutils-2.27/opcodes/aarch64-dis.h \
     ../../../../src/binutils-2.27/opcodes/aarch64-gen.c \
     ../../../../src/binutils-2.27/opcodes/aarch64-opc-2.c \
     ../../../../src/binutils-2.27/opcodes/aarch64-opc.c \
     ../../../../src/binutils-2.27/opcodes/aarch64-opc.h \
     ../../../../src/binutils-2.27/opcodes/aarch64-tbl.h \
     ../../../../src/binutils-2.27/opcodes/alpha-dis.c \
     ../../../../src/binutils-2.27/opcodes/alpha-opc.c \
     ../../../../src/binutils-2.27/opcodes/arc-dis.c \
     ../../../../src/binutils-2.27/opcodes/arc-ext.c \
     ../../../../src/binutils-2.27/opcodes/arc-opc.c \
     ../../../../src/binutils-2.27/opcodes/arm-dis.c \
     ../../../../src/binutils-2.27/opcodes/avr-dis.c \
     ../../../../src/binutils-2.27/opcodes/bfin-dis.c \
     ../../../../src/binutils-2.27/opcodes/cgen-asm.c \
     ../../../../src/binutils-2.27/opcodes/cgen-bitset.c \
     ../../../../src/binutils-2.27/opcodes/cgen-dis.c \
     ../../../../src/binutils-2.27/opcodes/cgen-opc.c \
     ../../../../src/binutils-2.27/opcodes/cr16-dis.c \
     ../../../../src/binutils-2.27/opcodes/cr16-opc.c \
     ../../../../src/binutils-2.27/opcodes/cris-dis.c \
     ../../../../src/binutils-2.27/opcodes/cris-opc.c \
     ../../../../src/binutils-2.27/opcodes/crx-dis.c \
     ../../../../src/binutils-2.27/opcodes/crx-opc.c \
     ../../../../src/binutils-2.27/opcodes/d10v-dis.c \
     ../../../../src/binutils-2.27/opcodes/d10v-opc.c \
     ../../../../src/binutils-2.27/opcodes/d30v-dis.c \
     ../../../../src/binutils-2.27/opcodes/d30v-opc.c \
     ../../../../src/binutils-2.27/opcodes/dis-buf.c \
     ../../../../src/binutils-2.27/opcodes/dis-init.c \
     ../../../../src/binutils-2.27/opcodes/disassemble.c \
     ../../../../src/binutils-2.27/opcodes/dlx-dis.c \
     ../../../../src/binutils-2.27/opcodes/epiphany-asm.c \
     ../../../../src/binutils-2.27/opcodes/epiphany-desc.c \
     ../../../../src/binutils-2.27/opcodes/epiphany-desc.h \
     ../../../../src/binutils-2.27/opcodes/epiphany-dis.c \
     ../../../../src/binutils-2.27/opcodes/epiphany-ibld.c \
     ../../../../src/binutils-2.27/opcodes/epiphany-opc.c \
     ../../../../src/binutils-2.27/opcodes/epiphany-opc.h \
     ../../../../src/binutils-2.27/opcodes/fr30-asm.c \
     ../../../../src/binutils-2.27/opcodes/fr30-desc.c \
     ../../../../src/binutils-2.27/opcodes/fr30-desc.h \
     ../../../../src/binutils-2.27/opcodes/fr30-dis.c \
     ../../../../src/binutils-2.27/opcodes/fr30-ibld.c \
     ../../../../src/binutils-2.27/opcodes/fr30-opc.c \
     ../../../../src/binutils-2.27/opcodes/fr30-opc.h \
     ../../../../src/binutils-2.27/opcodes/frv-asm.c \
     ../../../../src/binutils-2.27/opcodes/frv-desc.c \
     ../../../../src/binutils-2.27/opcodes/frv-desc.h \
     ../../../../src/binutils-2.27/opcodes/frv-dis.c \
     ../../../../src/binutils-2.27/opcodes/frv-ibld.c \
     ../../../../src/binutils-2.27/opcodes/frv-opc.c \
     ../../../../src/binutils-2.27/opcodes/frv-opc.h \
     ../../../../src/binutils-2.27/opcodes/ft32-dis.c \
     ../../../../src/binutils-2.27/opcodes/ft32-opc.c \
     ../../../../src/binutils-2.27/opcodes/h8300-dis.c \
     ../../../../src/binutils-2.27/opcodes/h8500-dis.c \
     ../../../../src/binutils-2.27/opcodes/h8500-opc.h \
     ../../../../src/binutils-2.27/opcodes/hppa-dis.c \
     ../../../../src/binutils-2.27/opcodes/i370-dis.c \
     ../../../../src/binutils-2.27/opcodes/i370-opc.c \
     ../../../../src/binutils-2.27/opcodes/i386-dis.c \
     ../../../../src/binutils-2.27/opcodes/i386-gen.c \
     ../../../../src/binutils-2.27/opcodes/i386-init.h \
     ../../../../src/binutils-2.27/opcodes/i386-opc.c \
     ../../../../src/binutils-2.27/opcodes/i386-opc.h \
     ../../../../src/binutils-2.27/opcodes/i386-tbl.h \
     ../../../../src/binutils-2.27/opcodes/i860-dis.c \
     ../../../../src/binutils-2.27/opcodes/i960-dis.c \
     ../../../../src/binutils-2.27/opcodes/ia64-asmtab.c \
     ../../../../src/binutils-2.27/opcodes/ia64-asmtab.h \
     ../../../../src/binutils-2.27/opcodes/ia64-dis.c \
     ../../../../src/binutils-2.27/opcodes/ia64-gen.c \
     ../../../../src/binutils-2.27/opcodes/ia64-opc-a.c \
     ../../../../src/binutils-2.27/opcodes/ia64-opc-b.c \
     ../../../../src/binutils-2.27/opcodes/ia64-opc-d.c \
     ../../../../src/binutils-2.27/opcodes/ia64-opc-f.c \
     ../../../../src/binutils-2.27/opcodes/ia64-opc-i.c \
     ../../../../src/binutils-2.27/opcodes/ia64-opc-m.c \
     ../../../../src/binutils-2.27/opcodes/ia64-opc.c \
     ../../../../src/binutils-2.27/opcodes/ia64-opc.h \
     ../../../../src/binutils-2.27/opcodes/ip2k-asm.c \
     ../../../../src/binutils-2.27/opcodes/ip2k-desc.c \
     ../../../../src/binutils-2.27/opcodes/ip2k-desc.h \
     ../../../../src/binutils-2.27/opcodes/ip2k-dis.c \
     ../../../../src/binutils-2.27/opcodes/ip2k-ibld.c \
     ../../../../src/binutils-2.27/opcodes/ip2k-opc.c \
     ../../../../src/binutils-2.27/opcodes/ip2k-opc.h \
     ../../../../src/binutils-2.27/opcodes/iq2000-asm.c \
     ../../../../src/binutils-2.27/opcodes/iq2000-desc.c \
     ../../../../src/binutils-2.27/opcodes/iq2000-desc.h \
     ../../../../src/binutils-2.27/opcodes/iq2000-dis.c \
     ../../../../src/binutils-2.27/opcodes/iq2000-ibld.c \
     ../../../../src/binutils-2.27/opcodes/iq2000-opc.c \
     ../../../../src/binutils-2.27/opcodes/iq2000-opc.h \
     ../../../../src/binutils-2.27/opcodes/lm32-asm.c \
     ../../../../src/binutils-2.27/opcodes/lm32-desc.c \
     ../../../../src/binutils-2.27/opcodes/lm32-desc.h \
     ../../../../src/binutils-2.27/opcodes/lm32-dis.c \
     ../../../../src/binutils-2.27/opcodes/lm32-ibld.c \
     ../../../../src/binutils-2.27/opcodes/lm32-opc.c \
     ../../../../src/binutils-2.27/opcodes/lm32-opc.h \
     ../../../../src/binutils-2.27/opcodes/lm32-opinst.c \
     ../../../../src/binutils-2.27/opcodes/m10200-dis.c \
     ../../../../src/binutils-2.27/opcodes/m10200-opc.c \
     ../../../../src/binutils-2.27/opcodes/m10300-dis.c \
     ../../../../src/binutils-2.27/opcodes/m10300-opc.c \
     ../../../../src/binutils-2.27/opcodes/m32c-asm.c \
     ../../../../src/binutils-2.27/opcodes/m32c-desc.c \
     ../../../../src/binutils-2.27/opcodes/m32c-desc.h \
     ../../../../src/binutils-2.27/opcodes/m32c-dis.c \
     ../../../../src/binutils-2.27/opcodes/m32c-ibld.c \
     ../../../../src/binutils-2.27/opcodes/m32c-opc.c \
     ../../../../src/binutils-2.27/opcodes/m32c-opc.h \
     ../../../../src/binutils-2.27/opcodes/m32r-asm.c \
     ../../../../src/binutils-2.27/opcodes/m32r-desc.c \
     ../../../../src/binutils-2.27/opcodes/m32r-desc.h \
     ../../../../src/binutils-2.27/opcodes/m32r-dis.c \
     ../../../../src/binutils-2.27/opcodes/m32r-ibld.c \
     ../../../../src/binutils-2.27/opcodes/m32r-opc.c \
     ../../../../src/binutils-2.27/opcodes/m32r-opc.h \
     ../../../../src/binutils-2.27/opcodes/m32r-opinst.c \
     ../../../../src/binutils-2.27/opcodes/m68hc11-dis.c \
     ../../../../src/binutils-2.27/opcodes/m68hc11-opc.c \
     ../../../../src/binutils-2.27/opcodes/m68k-dis.c \
     ../../../../src/binutils-2.27/opcodes/m68k-opc.c \
     ../../../../src/binutils-2.27/opcodes/m88k-dis.c \
     ../../../../src/binutils-2.27/opcodes/mcore-dis.c \
     ../../../../src/binutils-2.27/opcodes/mcore-opc.h \
     ../../../../src/binutils-2.27/opcodes/mep-asm.c \
     ../../../../src/binutils-2.27/opcodes/mep-desc.c \
     ../../../../src/binutils-2.27/opcodes/mep-desc.h \
     ../../../../src/binutils-2.27/opcodes/mep-dis.c \
     ../../../../src/binutils-2.27/opcodes/mep-ibld.c \
     ../../../../src/binutils-2.27/opcodes/mep-opc.c \
     ../../../../src/binutils-2.27/opcodes/mep-opc.h \
     ../../../../src/binutils-2.27/opcodes/metag-dis.c \
     ../../../../src/binutils-2.27/opcodes/microblaze-dis.c \
     ../../../../src/binutils-2.27/opcodes/microblaze-opc.h \
     ../../../../src/binutils-2.27/opcodes/micromips-opc.c \
     ../../../../src/binutils-2.27/opcodes/mips-dis.c \
     ../../../../src/binutils-2.27/opcodes/mips-opc.c \
     ../../../../src/binutils-2.27/opcodes/mips16-opc.c \
     ../../../../src/binutils-2.27/opcodes/mmix-dis.c \
     ../../../../src/binutils-2.27/opcodes/mmix-opc.c \
     ../../../../src/binutils-2.27/opcodes/moxie-dis.c \
     ../../../../src/binutils-2.27/opcodes/moxie-opc.c \
     ../../../../src/binutils-2.27/opcodes/msp430-decode.c \
     ../../../../src/binutils-2.27/opcodes/msp430-dis.c \
     ../../../../src/binutils-2.27/opcodes/mt-asm.c \
     ../../../../src/binutils-2.27/opcodes/mt-desc.c \
     ../../../../src/binutils-2.27/opcodes/mt-desc.h \
     ../../../../src/binutils-2.27/opcodes/mt-dis.c \
     ../../../../src/binutils-2.27/opcodes/mt-ibld.c \
     ../../../../src/binutils-2.27/opcodes/mt-opc.c \
     ../../../../src/binutils-2.27/opcodes/mt-opc.h \
     ../../../../src/binutils-2.27/opcodes/nds32-asm.c \
     ../../../../src/binutils-2.27/opcodes/nds32-dis.c \
     ../../../../src/binutils-2.27/opcodes/nios2-dis.c \
     ../../../../src/binutils-2.27/opcodes/nios2-opc.c \
     ../../../../src/binutils-2.27/opcodes/ns32k-dis.c \
     ../../../../src/binutils-2.27/opcodes/or1k-asm.c \
     ../../../../src/binutils-2.27/opcodes/or1k-desc.c \
     ../../../../src/binutils-2.27/opcodes/or1k-dis.c \
     ../../../../src/binutils-2.27/opcodes/or1k-ibld.c \
     ../../../../src/binutils-2.27/opcodes/or1k-opc.c \
     ../../../../src/binutils-2.27/opcodes/pdp11-dis.c \
     ../../../../src/binutils-2.27/opcodes/pdp11-opc.c \
     ../../../../src/binutils-2.27/opcodes/pj-dis.c \
     ../../../../src/binutils-2.27/opcodes/pj-opc.c \
     ../../../../src/binutils-2.27/opcodes/ppc-dis.c \
     ../../../../src/binutils-2.27/opcodes/ppc-opc.c \
     ../../../../src/binutils-2.27/opcodes/rl78-decode.c \
     ../../../../src/binutils-2.27/opcodes/rl78-dis.c \
     ../../../../src/binutils-2.27/opcodes/rx-decode.c \
     ../../../../src/binutils-2.27/opcodes/rx-dis.c \
     ../../../../src/binutils-2.27/opcodes/s390-dis.c \
     ../../../../src/binutils-2.27/opcodes/s390-mkopc.c \
     ../../../../src/binutils-2.27/opcodes/s390-opc.c \
     ../../../../src/binutils-2.27/opcodes/score-dis.c \
     ../../../../src/binutils-2.27/opcodes/score-opc.h \
     ../../../../src/binutils-2.27/opcodes/score7-dis.c \
     ../../../../src/binutils-2.27/opcodes/sh-dis.c \
     ../../../../src/binutils-2.27/opcodes/sh-opc.h \
     ../../../../src/binutils-2.27/opcodes/sh64-dis.c \
     ../../../../src/binutils-2.27/opcodes/sh64-opc.c \
     ../../../../src/binutils-2.27/opcodes/sh64-opc.h \
     ../../../../src/binutils-2.27/opcodes/sparc-dis.c \
     ../../../../src/binutils-2.27/opcodes/sparc-opc.c \
     ../../../../src/binutils-2.27/opcodes/spu-dis.c \
     ../../../../src/binutils-2.27/opcodes/spu-opc.c \
     ../../../../src/binutils-2.27/opcodes/sysdep.h \
     ../../../../src/binutils-2.27/opcodes/tic30-dis.c \
     ../../../../src/binutils-2.27/opcodes/tic4x-dis.c \
     ../../../../src/binutils-2.27/opcodes/tic54x-dis.c \
     ../../../../src/binutils-2.27/opcodes/tic54x-opc.c \
     ../../../../src/binutils-2.27/opcodes/tic6x-dis.c \
     ../../../../src/binutils-2.27/opcodes/tic80-dis.c \
     ../../../../src/binutils-2.27/opcodes/tic80-opc.c \
     ../../../../src/binutils-2.27/opcodes/tilegx-dis.c \
     ../../../../src/binutils-2.27/opcodes/tilegx-opc.c \
     ../../../../src/binutils-2.27/opcodes/tilepro-dis.c \
     ../../../../src/binutils-2.27/opcodes/tilepro-opc.c \
     ../../../../src/binutils-2.27/opcodes/v850-dis.c \
     ../../../../src/binutils-2.27/opcodes/v850-opc.c \
     ../../../../src/binutils-2.27/opcodes/vax-dis.c \
     ../../../../src/binutils-2.27/opcodes/visium-dis.c \
     ../../../../src/binutils-2.27/opcodes/visium-opc.c \
     ../../../../src/binutils-2.27/opcodes/w65-dis.c \
     ../../../../src/binutils-2.27/opcodes/w65-opc.h \
     ../../../../src/binutils-2.27/opcodes/xc16x-asm.c \
     ../../../../src/binutils-2.27/opcodes/xc16x-desc.c \
     ../../../../src/binutils-2.27/opcodes/xc16x-desc.h \
     ../../../../src/binutils-2.27/opcodes/xc16x-dis.c \
     ../../../../src/binutils-2.27/opcodes/xc16x-ibld.c \
     ../../../../src/binutils-2.27/opcodes/xc16x-opc.c \
     ../../../../src/binutils-2.27/opcodes/xc16x-opc.h \
     ../../../../src/binutils-2.27/opcodes/xgate-dis.c \
     ../../../../src/binutils-2.27/opcodes/xgate-opc.c \
     ../../../../src/binutils-2.27/opcodes/xstormy16-asm.c \
     ../../../../src/binutils-2.27/opcodes/xstormy16-desc.c \
     ../../../../src/binutils-2.27/opcodes/xstormy16-desc.h \
     ../../../../src/binutils-2.27/opcodes/xstormy16-dis.c \
     ../../../../src/binutils-2.27/opcodes/xstormy16-ibld.c \
     ../../../../src/binutils-2.27/opcodes/xstormy16-opc.c \
     ../../../../src/binutils-2.27/opcodes/xstormy16-opc.h \
     ../../../../src/binutils-2.27/opcodes/xtensa-dis.c \
     ../../../../src/binutils-2.27/opcodes/z80-dis.c \
     ../../../../src/binutils-2.27/opcodes/z8k-dis.c \
     ../../../../src/binutils-2.27/opcodes/z8k-opc.h \
     ../../../../src/binutils-2.27/opcodes/z8kgen.c

CATALOGS = 
CATOBJEXT = 
INSTOBJEXT = 

.SUFFIXES:
.SUFFIXES: .c .o .po .pox .gmo .mo .msg .cat

.c.o:
	$(COMPILE) $<

.po.pox:
	$(MAKE) $(PACKAGE).pot
	$(MSGMERGE) $< $(srcdir)/$(PACKAGE).pot -o $*.pox

.po.mo:
	$(MSGFMT) -o $@ $<

.po.gmo:
	file=`echo $* | sed 's,.*/,,'`.gmo \
	  && rm -f $$file && $(GMSGFMT) -o $$file $<

.po.cat:
	sed -f ../intl/po2msg.sed < $< > $*.msg \
	  && rm -f $@ && $(GENCAT) $@ $*.msg


all: all-no

all-yes: $(CATALOGS) # $(PACKAGE).pot
all-no:

$(srcdir)/$(PACKAGE).pot: $(POTFILES)
	$(XGETTEXT) --default-domain=$(PACKAGE) --directory=$(top_srcdir) \
	  --add-comments --keyword=_ --keyword=N_ \
	  --msgid-bugs-address=bug-binutils@gnu.org \
	  --files-from=$(srcdir)/POTFILES.in
	rm -f $(srcdir)/$(PACKAGE).pot
	mv $(PACKAGE).po $(srcdir)/$(PACKAGE).pot

$(srcdir)/cat-id-tbl.c: stamp-cat-id; @:
$(srcdir)/stamp-cat-id: $(PACKAGE).pot
	rm -f cat-id-tbl.tmp
	sed -f ../intl/po2tbl.sed $(srcdir)/$(PACKAGE).pot \
		| sed -e "s/@PACKAGE NAME@/$(PACKAGE)/" > cat-id-tbl.tmp
	if cmp -s cat-id-tbl.tmp $(srcdir)/cat-id-tbl.c; then \
	  rm cat-id-tbl.tmp; \
	else \
	  echo cat-id-tbl.c changed; \
	  rm -f $(srcdir)/cat-id-tbl.c; \
	  mv cat-id-tbl.tmp $(srcdir)/cat-id-tbl.c; \
	fi
	cd $(srcdir) && rm -f stamp-cat-id && echo timestamp > stamp-cat-id


install: install-exec install-data
install-exec:
install-info:
install-html:
install-pdf:
install-data: install-data-no
install-data-no: all
install-data-yes: all
	if test -r $(MKINSTALLDIRS); then \
	  $(MKINSTALLDIRS) $(DESTDIR)$(datadir); \
	else \
	  $(top_srcdir)/mkinstalldirs $(DESTDIR)$(datadir); \
	fi
	@catalogs='$(CATALOGS)'; \
	for cat in $$catalogs; do \
	  cat=`basename $$cat`; \
	  case "$$cat" in \
	    *.gmo) destdir=$(gnulocaledir);; \
	    *)     destdir=$(localedir);; \
	  esac; \
	  lang=`echo $$cat | sed 's/\$(CATOBJEXT)$$//'`; \
	  dir=$(DESTDIR)$$destdir/$$lang/LC_MESSAGES; \
	  if test -r $(MKINSTALLDIRS); then \
	    $(MKINSTALLDIRS) $$dir; \
	  else \
	    $(top_srcdir)/mkinstalldirs $$dir; \
	  fi; \
	  if test -r $$cat; then \
	    $(INSTALL_DATA) $$cat $$dir/$(PACKAGE)$(INSTOBJEXT); \
	    echo "installing $$cat as $$dir/$(PACKAGE)$(INSTOBJEXT)"; \
	  else \
	    $(INSTALL_DATA) $(srcdir)/$$cat $$dir/$(PACKAGE)$(INSTOBJEXT); \
	    echo "installing $(srcdir)/$$cat as" \
		 "$$dir/$(PACKAGE)$(INSTOBJEXT)"; \
	  fi; \
	  if test -r $$cat.m; then \
	    $(INSTALL_DATA) $$cat.m $$dir/$(PACKAGE)$(INSTOBJEXT).m; \
	    echo "installing $$cat.m as $$dir/$(PACKAGE)$(INSTOBJEXT).m"; \
	  else \
	    if test -r $(srcdir)/$$cat.m ; then \
	      $(INSTALL_DATA) $(srcdir)/$$cat.m \
		$$dir/$(PACKAGE)$(INSTOBJEXT).m; \
	      echo "installing $(srcdir)/$$cat as" \
		   "$$dir/$(PACKAGE)$(INSTOBJEXT).m"; \
	    else \
	      true; \
	    fi; \
	  fi; \
	done
	if test "$(PACKAGE)" = "gettext"; then \
	  if test -r $(MKINSTALLDIRS); then \
	    $(MKINSTALLDIRS) $(DESTDIR)$(gettextsrcdir); \
	  else \
	    $(top_srcdir)/mkinstalldirs $(DESTDIR)$(gettextsrcdir); \
	  fi; \
	  $(INSTALL_DATA) $(srcdir)/Makefile.in.in \
			  $(DESTDIR)$(gettextsrcdir)/Makefile.in.in; \
	else \
	  : ; \
	fi

# Define this as empty until I found a useful application.
installcheck:

uninstall:
	catalogs='$(CATALOGS)'; \
	for cat in $$catalogs; do \
	  cat=`basename $$cat`; \
	  lang=`echo $$cat | sed 's/\$(CATOBJEXT)$$//'`; \
	  rm -f $(DESTDIR)$(localedir)/$$lang/LC_MESSAGES/$(PACKAGE)$(INSTOBJEXT); \
	  rm -f $(DESTDIR)$(localedir)/$$lang/LC_MESSAGES/$(PACKAGE)$(INSTOBJEXT).m; \
	  rm -f $(DESTDIR)$(gnulocaledir)/$$lang/LC_MESSAGES/$(PACKAGE)$(INSTOBJEXT); \
	  rm -f $(DESTDIR)$(gnulocaledir)/$$lang/LC_MESSAGES/$(PACKAGE)$(INSTOBJEXT).m; \
	done
	rm -f $(DESTDIR)$(gettextsrcdir)/po-Makefile.in.in

check: all

cat-id-tbl.o: ../intl/libgettext.h

html dvi pdf ps info tags TAGS ID:

mostlyclean:
	rm -f core core.* *.pox $(PACKAGE).po *.old.po cat-id-tbl.tmp
	rm -fr *.o

clean: mostlyclean

distclean: clean
	rm -f Makefile Makefile.in POTFILES *.mo *.msg *.cat *.cat.m

maintainer-clean: distclean
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."
	rm -f $(GMOFILES)

distdir = ../$(PACKAGE)-$(VERSION)/$(subdir)
dist distdir: update-po $(DISTFILES)
	dists="$(DISTFILES)"; \
	for file in $$dists; do \
	  ln $(srcdir)/$$file $(distdir) 2> /dev/null \
	    || cp -p $(srcdir)/$$file $(distdir); \
	done

update-po: Makefile
	$(MAKE) $(PACKAGE).pot
	PATH=`pwd`/../src:$$PATH; \
	cd $(srcdir); \
	catalogs='$(CATALOGS)'; \
	for cat in $$catalogs; do \
	  cat=`basename $$cat`; \
	  lang=`echo $$cat | sed 's/\$(CATOBJEXT)$$//'`; \
	  mv $$lang.po $$lang.old.po; \
	  echo "$$lang:"; \
	  if $(MSGMERGE) $$lang.old.po $(PACKAGE).pot -o $$lang.po; then \
	    rm -f $$lang.old.po; \
	  else \
	    echo "msgmerge for $$cat failed!"; \
	    rm -f $$lang.po; \
	    mv $$lang.old.po $$lang.po; \
	  fi; \
	done

POTFILES: POTFILES.in
	( if test 'x$(srcdir)' != 'x.'; then \
	    posrcprefix='$(top_srcdir)/'; \
	  else \
	    posrcprefix="../"; \
	  fi; \
	  rm -f $@-t $@ \
	    && (sed -e '/^#/d' -e '/^[ 	]*$$/d' \
		    -e "s@.*@	$$posrcprefix& \\\\@" < $(srcdir)/$@.in \
		| sed -e '$$s/\\$$//') > $@-t \
	    && chmod a-w $@-t \
	    && mv $@-t $@ )

POTFILES.in: # ../Makefile
	cd .. && $(MAKE) po/POTFILES.in

Makefile: Make-in ../config.status POTFILES
	cd .. \
	  && CONFIG_FILES=$(subdir)/Makefile.in:$(subdir)/Make-in \
	     CONFIG_HEADERS= $(SHELL) ./config.status

# Tell versions [3.59,3.63) of GNU make not to export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
