#
# Copyright (c) 2020 Nordic Semiconductor
#
# SPDX-License-Identifier: LicenseRef-Nordic-5-Clause
#

target_include_directories(app PRIVATE .)

target_sources(app PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/icmp_ping.c)
target_sources(app PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/icmp_ping_shell.c)
