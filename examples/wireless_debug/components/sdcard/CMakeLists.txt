
idf_component_register(SRCS "./sdcard.c"
                    INCLUDE_DIRS "." "./include"
                    PRIV_INCLUDE_DIRS "./utils"
                    REQUIRES mcommon mwifi mdebug
)