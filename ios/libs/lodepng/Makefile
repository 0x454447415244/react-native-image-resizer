STATICLIB=liblodepng.a

OBJS = lodepng.o

all: static

static: $(STATICLIB)

$(STATICLIB): $(OBJS)
	$(AR) $(ARFLAGS) $@ $^