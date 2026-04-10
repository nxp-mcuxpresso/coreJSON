#
# Copyright 2024-2026 NXP
#
# SPDX-License-Identifier: BSD-3-Clause
#

if (CONFIG_MCUX_COMPONENT_middleware.freertos.corejson)
    mcux_add_source(
        SOURCES ../corejson-upstream/source/core_json.c
                ../corejson-upstream/source/include/core_json.h
    )
    mcux_add_include(
        INCLUDES ../corejson-upstream/source/include
    )
endif()
