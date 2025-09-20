# Tell ZMK about this shield
set(SHIELD_NAME my_6x18)

# Add keymap file
zmk_keymap_file(${CMAKE_CURRENT_SOURCE_DIR}/${SHIELD_NAME}.keymap)
