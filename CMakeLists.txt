cmake_minimum_required(VERSION 3.20.0)

set(BOARD adafruit_feather_nrf52840)
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})
project(passr)

target_sources(app PRIVATE src/main.c)
