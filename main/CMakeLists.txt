idf_component_register(SRCS main.cpp model.cc
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES M5Unified esp-tflite-micro)