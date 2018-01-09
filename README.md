VovCoin (VOV)

boost
 bootstrap.bat mingw
 patch -p1 boost_1_53_0.mingw.patch 
 b2 --build-type=complete --with-chrono --with-filesystem --with-program_options --with-system --with-thread toolset=gcc stage
 