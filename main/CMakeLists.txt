idf_component_register(SRCS "main.c"
							"mon.c"
							"nyan_64x32.c"

                    INCLUDE_DIRS ".")
 target_compile_options(${COMPONENT_TARGET} PUBLIC -DNO_GFX)				