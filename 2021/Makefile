CXX = clang++
CXXFLAGS += --stdlib=libc++
CXXFLAGS += $(shell cat compile_flags.txt)
CXXFLAGS += -O3 -g

DAYS = a01 a02 a03 a04 a05 a06 a07 a08 a09 a10 \
       a11 a12 a13 a14 a15 a16 a17 a18 a19 a20 \
       a21 a22 a23 a24 a25

.PHONY: clean

all: $(DAYS)

clean:
	rm -f $(DAYS)
