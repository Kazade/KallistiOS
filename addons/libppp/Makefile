# libppp Makefile
#

TARGET = libppp.a
OBJS = ppp.o lcp.o pap.o ipcp.o

# Make sure everything compiles nice and cleanly (or not at all).
KOS_CFLAGS += -W -pedantic -std=c99 -I$(KOS_BASE)/kernel/net -Werror -Wextra

# Uncomment the line below to enable all manner of debugging output.
KOS_CFLAGS += -DPPP_DEBUG

include $(KOS_BASE)/addons/Makefile.prefab
