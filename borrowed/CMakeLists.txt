ADD_SUBDIRECTORY(libc)
ADD_SUBDIRECTORY(goffice)

SET_LOCAL_DIST(borrowed_DIST_local CMakeLists.txt Makefile.am README)
SET(borrowed_DIST ${borrowed_DIST_local} ${libc_DIST} ${goffice_DIST} PARENT_SCOPE)
