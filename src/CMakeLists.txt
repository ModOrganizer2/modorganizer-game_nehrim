cmake_minimum_required(VERSION 3.16)

add_library(game_nehrim SHARED)
mo2_configure_plugin(game_nehrim
    WARNINGS OFF
    PRIVATE_DEPENDS gamebryo)
mo2_install_target(game_nehrim)
