shared-mono-lr.bin: shared-mono.dix
	apertium-validate-dictionary $<
	lt-comp lr $< $@

shared-mono-rl.bin: shared-mono.dix
	apertium-validate-dictionary $<
	lt-comp rl $< $@

apertiumdir = $(prefix)/share/apertium/apertium-shared
dist_apertium_DATA = \
	shared-mono-lr.bin \
	shared-mono-rl.bin

CLEANFILES = *.bin
