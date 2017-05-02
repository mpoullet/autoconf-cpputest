# Comment like in a normal Makefile

bin_PROGRAMS = demo-cpputest

# All files should be added so that make dist take them in the tarball
# We do a non-recursive make so add the path to each file too
demo_cpputest_SOURCES = src/FirstTestGroup.cpp \
                        src/AllTests.cpp

# C preprocessor
AM_CPPFLAGS = $(CPPUTEST_CFLAGS)
# C++ compiler
AM_CXXFLAGS = -Wall -Wextra -Werror -pedantic

demo_cpputest_LDADD = $(CPPUTEST_LIBS)

