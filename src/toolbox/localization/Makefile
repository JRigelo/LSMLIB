##
## File:        Makefile.in
## Copyrights:  (c) 2005 The Trustees of Princeton University and Board of
##                  Regents of the University of Texas.  All rights reserved.
##              (c) 2009 Kevin T. Chu.  All rights reserved.
## Revision:    $Revision$
## Modified:    $Date$
## Description: makefile for localization subroutines
##

SRC_DIR = .

BUILD_DIR = ../../..
include $(BUILD_DIR)/config/Makefile.config

all:  includes library

includes:  
	cp -f $(SRC_DIR)/lsm_localization2d.h $(BUILD_DIR)/include/
	cp -f $(SRC_DIR)/lsm_localization3d.h $(BUILD_DIR)/include/

library: lsm_localization2d.o lsm_localization3d.o

clean:
	rm -f *.o 

