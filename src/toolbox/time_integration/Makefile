##
## File:        Makefile.in
## Copyrights:  (c) 2005 The Trustees of Princeton University and Board of
##                  Regents of the University of Texas.  All rights reserved.
##              (c) 2009 Kevin T. Chu.  All rights reserved.
## Revision:    $Revision$
## Modified:    $Date$
## Description: makefile for time-integration subroutines
##

SRC_DIR = .

BUILD_DIR = ../../..
include $(BUILD_DIR)/config/Makefile.config

all:  includes library

includes:  
	cp -f $(SRC_DIR)/lsm_tvd_runge_kutta1d.h $(BUILD_DIR)/include/
	cp -f $(SRC_DIR)/lsm_tvd_runge_kutta2d.h $(BUILD_DIR)/include/
	cp -f $(SRC_DIR)/lsm_tvd_runge_kutta2d_local.h $(BUILD_DIR)/include/
	cp -f $(SRC_DIR)/lsm_tvd_runge_kutta3d.h $(BUILD_DIR)/include/
	cp -f $(SRC_DIR)/lsm_tvd_runge_kutta3d_local.h $(BUILD_DIR)/include/

library:  lsm_tvd_runge_kutta1d.o       \
          lsm_tvd_runge_kutta2d.o       \
          lsm_tvd_runge_kutta2d_local.o \
          lsm_tvd_runge_kutta3d.o       \
          lsm_tvd_runge_kutta3d_local.o

clean:
	rm -f *.o 

