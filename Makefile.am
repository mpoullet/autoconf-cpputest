# Comment like in a normal Makefile

bin_PROGRAMS = demo-cpputest

# All files should be added so that make dist take them in the tarball
# We do a non-recursive make so add the path to each file too
demo_cpputest_SOURCES = src/FirstTestGroup.cpp \
                        src/AllTests.cpp

# Flags for the C preprocessor
AM_CPPFLAGS = $(CPPUTEST_CFLAGS)
# Flags for the C++ compiler
AM_CXXFLAGS = -Wall -Wextra -Werror -pedantic

demo_cpputest_LDADD = $(CPPUTEST_LIBS)

