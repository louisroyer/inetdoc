ifndef $(MAIN_DIR)
MAIN_DIR = $(HOME)/inetdoc
endif

PNGTARGET = $(addsuffix .png,$(basename $(wildcard *.odg)))

# Type(s) de traitement
PROCESS = symlink $(PNGTARGET)

SYMLINKS = \
	$(MAIN_DIR)/presentations/os-arch-hints/images/kernel-network-subsystem.png \
	$(MAIN_DIR)/images/thumbs/thumb010.png

all: $(PROCESS)

include $(MAIN_DIR)/common/Makefile.Rules
