TOP=../..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE

#----------------------------------------------------
#  Optimization of db files using dbst (DEFAULT: NO)
#DB_OPT = YES

#----------------------------------------------------
# Create and install (or just install)
# databases, templates, substitutions like this

#----------------------------------------------------
# Create and install (or just install)
# Archive files, templates, substitutions like this
#
ARCHIVE += archive_ads.archive
REQ += autosave_ads.req

DB += GattPlc.db
DB_INSTALLS += $(IOCADMIN)/db/iocSoft.db
DB_INSTALLS += $(AUTOSAVE)/db/save_restoreStatus.db
DB_INSTALLS += $(ASYN)/db/asynRecord.db

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

