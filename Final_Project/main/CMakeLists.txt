idf_component_register(SRCS "adc.c" "wifi_app.c" "http_server.c" "main.c" "led_rgb.c" "uart.c" "isr.c" "servo.c" "schedule_register.c"
                    INCLUDE_DIRS "."
                    EMBED_FILES webpage/app.css webpage/app.js webpage/favicon.ico webpage/index.html webpage/jquery-3.3.1.min.js)
