# SPDX-FileCopyrightText: 2023-2025 Andy Curtis <contactandyc@gmail.com>
# SPDX-FileCopyrightText: 2024-2025 Knode.ai
# SPDX-License-Identifier: Apache-2.0
cmake_minimum_required(VERSION 3.10)

# Project Configuration
project(a-bitset-library VERSION 0.1.1)

# Variables
set(INCLUDE_DIR_NAME "a-bitset-library")
set(EXTRA_FILES README.md AUTHORS NEWS.md CHANGELOG.md LICENSE NOTICE)
set(CUSTOM_PACKAGES a-memory-library)

# Source files
file(GLOB SOURCE_FILES src/*.c)

find_package(a-cmake-library REQUIRED)

include(LibraryConfig)
include(LibraryBuild)
