include ../Makefile.inc

SOURCE_DIR=../../projectbuendia.openmrs/omod/target
TARGET_DIR=$(EXTRA_ROOT)/usr/share/buendia/openmrs/modules

$(EXTRA_ROOT): $(TARGET_DIR)/buendia-server.omod $(TARGET_DIR)/xforms-4.3.1.omod

$(TARGET_DIR)/buendia-server.omod:
	mkdir -p $(TARGET_DIR)
	cp $(SOURCE_DIR)/projectbuendia.openmrs-*.omod $@

$(TARGET_DIR)/xforms-4.3.1.omod:
	mkdir -p $(TARGET_DIR)
	cp $(TOP)/modules/xforms-4.3.1.jar $@