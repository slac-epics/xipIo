TOP=../

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#========================================
# Build the IOC application
DBD += xipIo.dbd

# Install include
INC += xipIo.h

# Source files (for depends target):
LIBSRCS += xipIo.c

# Link everything into a library:
LIBRARY_IOC_vxWorks = xipIo
LIBRARY_IOC_RTEMS   = xipIo
LIBRARY_IOC_Linux   = xipIo

#========================================
include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE


