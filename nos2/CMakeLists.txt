cmake_minimum_required(VERSION 3.22)
set(BOARD qemu_x86)
set(DTC_OVERLAY_FILE app.overlay)
find_package(Zephyr)
project(nos2_app)

target_sources(app PRIVATE src/main.c)