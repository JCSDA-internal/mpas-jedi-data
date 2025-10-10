# (C) Copyright 2021-2025 UCAR.
#
# This software is licensed under the terms of the Apache Licence Version 2.0
# which can be obtained at http://www.apache.org/licenses/LICENSE-2.0.

cmake_minimum_required( VERSION 3.12 )
project( mpas-jedi-data VERSION 3.1.0 DESCRIPTION "MPAS-JEDI Tier 1 Test Files" )

find_package(ecbuild QUIET)
include(ecbuild_system NO_POLICY_SCOPE)
ecbuild_declare_project()
set(CMAKE_DIRECTORY_LABELS ${PROJECT_NAME})
ecbuild_install_project(NAME ${PROJECT_NAME})
ecbuild_print_summary()
