
set(COMPONENT_ADD_INCLUDEDIRS include include)
set(COMPONENT_SRCDIRS library)

set(COMPONENT_REQUIRES  freertos)
set(COMPONENT_PRIV_REQUIRES esp32)

register_component()