AUTOMAKE_OPTIONS=foreign
lib_LTLIBRARIES=libsharedDatabaseInterfacesharedlogger.la
libsharedDatabaseInterfacesharedlogger_la_CXXFLAGS=-I$(srcdir)/../../../include/public \
	-I$(engine_dir)/shared/library/sharedCompression/include/public \
	-I$(engine_dir)/shared/library/sharedDebug/include/public \
	-I$(engine_dir)/shared/library/sharedFile/include/public \
	-I$(engine_dir)/shared/library/sharedFoundation/include/public \
	-I$(engine_dir)/shared/library/sharedFoundationTypes/include/public \
	-I$(engine_dir)/shared/library/sharedMath/include/public \
	-I$(engine_dir)/shared/library/sharedMemoryManager/include/public \
	-I$(engine_dir)/shared/library/sharedSynchronization/include/public \
	-I$(engine_dir)/shared/library/sharedThread/include/public \
	-I$(stlport_dir)/stlport \
	-I$(archive_dir)/include \
	-I$(fileInterface_dir)/include/public \
	-Wno-ctor-dtor-privacy
libsharedDatabaseInterfacesharedlogger_la_SOURCES=DbLogEvent.cpp \
	DbLogEvent.h \
	DbLogger.cpp \
	DbLogger.h \
	DbTaskSaveLog.cpp \
	DbTaskSaveLog.h

libsharedDatabaseInterfacesharedlogger_la_LDFLAGS=-avoid-version

include $(engine_dir)/../make_include/engine.include
