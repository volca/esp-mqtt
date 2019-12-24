idf_component_register(SRCS "mqtt_client.c"
                            "lib/mqtt_msg.c"
                            "lib/mqtt_outbox.c"
                            "lib/platform_esp32_idf.c"
                            INCLUDE_DIRS include
                            PRIV_INCLUDE_DIRS "lib/include"
                            REQUIRES lwip nghttp mbedtls tcp_transport)
