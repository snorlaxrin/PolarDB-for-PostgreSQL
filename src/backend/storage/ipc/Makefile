#
# Makefile for storage/ipc
#
# src/backend/storage/ipc/Makefile
#

subdir = src/backend/storage/ipc
top_builddir = ../../../..
include $(top_builddir)/src/Makefile.global

OBJS = barrier.o dsm_impl.o dsm.o ipc.o ipci.o latch.o pmsignal.o procarray.o \
	procsignal.o  shmem.o shmqueue.o shm_mq.o shm_toc.o sinval.o \
	sinvaladt.o standby.o

# POLAR objects
OBJS += polar_shmem.o polar_procpool.o
OBJS += polar_session_context.o

include $(top_srcdir)/src/backend/common.mk
