# SPDX-License-Identifier: Apache-2.0
add_subdirectory_ifdef(CONFIG_SOC_ESP32 esp32)
add_subdirectory_ifdef(CONFIG_SOC_ESP32_NET esp32)
add_subdirectory_ifdef(CONFIG_SOC_ESP32C3 esp32c3)
add_subdirectory_ifdef(CONFIG_SOC_ESP32S2 esp32s2)
