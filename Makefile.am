AM_CPPFLAGS = -I./include/msdk/include/ -I./include 

library_includedir=$(includedir)/msdk/
library_include_HEADERS =                 \
	include/msdk/include/mfxastructures.h \
	include/msdk/include/mfxaudio.h       \
	include/msdk/include/mfxaudio++.h     \
	include/msdk/include/mfxcommon.h      \
	include/msdk/include/mfxdefs.h        \
	include/msdk/include/mfxenc.h         \
	include/msdk/include/mfxjpeg.h        \
	include/msdk/include/mfxla.h          \
	include/msdk/include/mfxmvc.h         \
        include/msdk/include/mfxpak.h         \
	include/msdk/include/mfxplugin.h      \
	include/msdk/include/mfxplugin++.h    \
	include/msdk/include/mfxsession.h     \
	include/msdk/include/mfxstructures.h  \
	include/msdk/include/mfxvideo.h       \
	include/msdk/include/mfxvideo++.h     \
        include/msdk/include/mfxvp8.h         \
	include/msdk/include/mfxvstructures.h

AM_CXXFLAGS = -Wall -Wextra -DMINGW_HAS_SECURE_API=1 
#-DMFX_DISPATCHER_LOG=1 
#-DDISPATCHER_LOG_REGISTER_FILE_WRITER=1

lib_LTLIBRARIES = libmfx.la
libmfx_la_SOURCES =              \
	src/main.cpp                 \
	src/mfx_critical_section.cpp \
	src/mfx_dispatcher.cpp       \
	src/mfx_dispatcher_log.cpp   \
	src/mfx_dxva2_device.cpp     \
	src/mfx_function_table.cpp   \
	src/mfx_library_iterator.cpp \
	src/mfx_load_dll.cpp         \
	src/mfx_load_plugin.cpp      \
	src/mfx_plugin_hive.cpp      \
	src/mfx_win_reg_key.cpp

