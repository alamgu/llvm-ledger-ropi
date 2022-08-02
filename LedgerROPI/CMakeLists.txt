include(GNUInstallDirs)

add_library(LedgerROPI MODULE Pass.cpp)
install(TARGETS LedgerROPI
  LIBRARY
  DESTINATION "${CMAKE_INSTALL_LIBDIR}"
  )
