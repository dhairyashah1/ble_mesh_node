idf_component_register(SRCS "test_panic_main.c"
                       INCLUDE_DIRS "."
                       REQUIRES spi_flash esp_psram esp_system esp_partition)
