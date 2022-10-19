# *****************************************************************************
# Filename:			Makefile.am
# Description:
# Copyright(c):
# Author(s):		Jay Cotton, Claude Sylvain
# Created:			26 Mars 2011
# Last modified:	17 April 2011
# Notes:
# *****************************************************************************


#AUTOMAKE_OPTOINS = foreign

#AM_CFLAGS = -g -D_TGT_M_X86 -D_TGT_OS_CYGWIN32
AM_CFLAGS = -D_TGT_M_X86 -D_TGT_OS_CYGWIN32 -Wall  -Wextra  -Walloc-zero  -Walloca -fsanitize=address -fsanitize=undefined -fno-sanitize-recover=all -fsanitize=float-divide-by-zero -fsanitize=float-cast-overflow -fno-sanitize=null -fno-sanitize=alignment -Wno-unused-parameter

bin_PROGRAMS = asm8080

asm8080_SOURCES = asm_dir.c  exp_parser.c  main.c  opcode.c  util.c msg.c

#asm8080_CPPFLAGS = -D_TGT_M_X86 -D_TGT_OS_CYGWIN32


