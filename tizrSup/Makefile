TOP=..
include $(TOP)/configure/CONFIG
#=======================================

# Install .dbd and .db files
DB += tizr.db
DBD += inhibitor.dbd
DBD += tizr.dbd

# Sequence file
LIBRARY_IOC = TIZR
TIZR_SRCS += inhibitor.st
TIZR_LIBS += seq pv
TIZR_LIBS += $(EPICS_BASE_IOC_LIBS)

#=======================================
include $(TOP)/configure/RULES