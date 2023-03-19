idf_component_register(SRCS "ESP32 Web Server with WiFi and ADC.c"
                    INCLUDE_DIRS "."
	            EMBED_FILES "silder.html")

#spiffs_create_partition_image(storage ../library FLASH_IN_PROJECT)