thisdir = class/System.Runtime.Serialization.Json
SUBDIRS = 
include ../../build/rules.make

LIBRARY = System.Runtime.Serialization.Json.dll
LIB_REFS = System System.Xml System.Runtime.Serialization System.Core
LIB_MCS_FLAGS =

TEST_MCS_FLAGS = $(LIB_MCS_FLAGS)

EXTRA_DISTFILES = $(RESOURCE_FILES)

VALID_PROFILE := $(filter 2.1, $(FRAMEWORK_VERSION))
ifndef VALID_PROFILE
LIBRARY_NAME = dummy-System.Runtime.Serialization.Json.dll
NO_INSTALL = yes
NO_SIGN_ASSEMBLY = yes
endif

include ../../build/library.make
