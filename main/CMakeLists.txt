# idf_component_register(SRCS "main.c" "component/ssd1306.c" "component/ssd1306_i2c.c"  "component/ssd1306_spi.c"
idf_component_register(SRCS "main_.c" "component/ssd1306_.c" 
                       INCLUDE_DIRS "." "./component")
