# Autoconf Requirements
# Initialize, The Project and Provide Version Info
AC_INIT([loggerc],[0.0.1],[sahoorajesh.d@gmail.com],[loggercpp],[http://cppforeverystudent.blogspot.com/2014/08/loggercpp.html])
# Force autoconf to be at least this version number:
AC_PREREQ([2.68])
# Safe check of source files
AC_CONFIG_SRCDIR([hello.c])
# Putconfigure Result here so that we can easily include in our project
AC_CONFIG_HEADER([config.h])
# Put autotools auxiliary files in a subdir, so they don't clutter top dir:
AC_CONFIG_AUX_DIR([build-aux])

# Enable "automake" to simplify creating makefiles:
AM_INIT_AUTOMAKE([1.11 -Wall -Werror])
AC_CONFIG_FILES([Makefile])

# Look for a C compiler:
AC_PROG_CC

# Perhaps check for: (more) programs, libraries, header files, types,
# structures, compiler characteristics, library functions, system services.

# Do final output.
AC_OUTPUT

