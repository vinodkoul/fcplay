bin_PROGRAMS = fcplay

fcplay_SOURCES = fcplay.c

fcplay_CFLAGS = -I$(top_srcdir)/include \
		    $(TINYCOMPRESS_CFLAGS) \
		    $(AVCODEC_CFLAGS) \
		    $(AVFORMAT_CFLAGS) \
		    $(AVUTIL_CFLAGS) \
		    $(LIBDRM_CFLAGS)

fcplay_LDADD = $(TINYCOMPRESS_LIBS) \
		    $(AVCODEC_LIBS) \
		    $(AVFORMAT_LIBS) \
		    $(AVUTIL_LIBS) \
		    $(LIBDRM_LIBS)
