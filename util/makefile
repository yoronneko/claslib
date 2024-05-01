SUBDIRS = $(wildcard */)

all:   $(SUBDIRS)
test:  $(SUBDIRS)
clean: $(SUBDIRS)

FORCE:

$(SUBDIRS): FORCE
	$(MAKE) -C $@ $(MAKECMDGOALS)

# EOF
