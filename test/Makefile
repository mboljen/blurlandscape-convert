
SCRIPT = ../bin/blurlandscape-convert
OPTS = --yes

INFILE = apple.jpg

OUTFILES = apple-dither.jpg apple-mirror.jpg apple-random.jpg apple-16x9.jpg apple-9x16.jpg

test: $(OUTFILES)

%-dither.jpg: %.jpg
	$(SCRIPT) $(OPTS) --out=dither $^

%-mirror.jpg: %.jpg
	$(SCRIPT) $(OPTS) --method=mirror --out=mirror $^

%-random.jpg: %.jpg
	$(SCRIPT) $(OPTS) --method=random --out=random $^

%-16x9.jpg: %.jpg
	$(SCRIPT) $(OPTS) --ratio=16:9 --out=16x9 $^

%-9x16.jpg: %.jpg
	$(SCRIPT) $(OPTS) --ratio=9:16 --out=9x16 $^

clean:
	$(RM) $(OUTFILES)

.PHONY: clean test
