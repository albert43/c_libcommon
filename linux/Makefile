#   Basic info

#   Only "debug" and "release" are available.
ifeq "$(BUILD_TYPE)" ""
    BUILD_TYPE=debug
endif

#   Version.
VERSION_MAJOR=2
VERSION_MINOR=0
VERSION_RELEASE=1
VERSION_BUILD=0

#   According to the target file type, the suffix of TARGET_NAME should be
#   Executable file : (no suffix)
#   Static library  : .a
#   Dynamic library : .so
TARGET_NAME=libcommon.a
CATEGORY_NAME=

#   Only "c" and "cpp" are available.
TARGET_LANGUAGE=c

DEP_ALSRC=
DEP_OPENSRC=

TARGET_CFLAGS=
TARGET_LFLAGS=-lpthread -ldl

#
#   Path
#
ifeq "$(REPOS_ROOT)" ""
    REPOS_ROOT=/repos
endif

include $(REPOS_ROOT)/makefile/source.mak
