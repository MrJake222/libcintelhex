add_library(cintelhex)

target_sources(cintelhex
        PUBLIC
        src/ihex_parse.c
        src/ihex_record.c
        )

target_include_directories(cintelhex
        PUBLIC include
        )