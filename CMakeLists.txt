#
# Copyright 2024 NXP
#
# SPDX-License-Identifier: MIT
#

if (CONFIG_MCUX_COMPONENT_middleware.freertos.corejson)
    mcux_add_source(
        SOURCES source/core_json.c source/include/core_json.h
    )
    mcux_add_include(
        INCLUDES source/include
    )
endif()
