APP = test-bg1

include $(SDK_DIR)/Makefile.defs

OBJS = $(ASSETS).gen.o main.o
ASSETDEPS += *.png $(ASSETS).lua

include $(TC_DIR)/test/sdk/Makefile.rules

SIFTULATOR_FLAGS += -n 1

include $(SDK_DIR)/Makefile.rules
