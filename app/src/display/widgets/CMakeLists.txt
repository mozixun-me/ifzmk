# Copyright (c) 2020 The ZMK Contributors
# SPDX-License-Identifier: MIT

target_sources_ifdef(CONFIG_ZMK_WIDGET_BATTERY_STATUS app PRIVATE battery_status.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_OUTPUT_STATUS app PRIVATE output_status.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_LAYER_STATUS app PRIVATE layer_status.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_WPM_STATUS app PRIVATE wpm_status.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_BONGO_CAT app PRIVATE bongo_cat.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_BONGO_CAT app PRIVATE bongo_cat_images.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_LUNA app PRIVATE luna.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_LUNA app PRIVATE luna_images.c)
