add_library(NOD
            aes.cpp
            DiscBase.cpp
            DiscGCN.cpp
            DiscIOISO.cpp
            DiscIOWBFS.cpp
            DiscWii.cpp
            FileIOFILE.cpp
            FileIOMEM.cpp
            NOD.cpp
            WideStringConvert.cpp
            ${NOD_HEADERS})
set_source_files_properties(aes.cpp PROPERTIES COMPILE_FLAGS -maes)