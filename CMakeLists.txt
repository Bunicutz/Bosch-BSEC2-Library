# Force the ESP-IDF build pipeline to expose the Bosch dependency trees
idf_component_register(
    SRCS "bsec2.h"
    INCLUDE_DIRS "."
    REQUIRES "https://github.com/Bunicutz/Bosch-BME68x-Library.git"
)
