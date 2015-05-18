# ==============================================================================
# LAPACK CMake File
# ==============================================================================

# include subdirectories -------------------------------------------------------
ADD_SUBDIRECTORY(flapackd)
IF(LIBS_COMPLEX)
    ADD_SUBDIRECTORY(flapackz)
ENDIF(LIBS_COMPLEX)

