# Copyright (c) 2024 IHU Liryc, Université de Bordeaux, Inria.
# License: BSD-3-Clause

add_subdirectory(package)

if(PYMED_STANDALONE)
    add_subdirectory(standalone)
endif()
