idf_component_register(SRCS "basic.c" "main.c"
                       INCLUDE_DIRS "."
                       REQUIRES esp_netif esp_eth lwip)