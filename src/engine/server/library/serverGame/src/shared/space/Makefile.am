AUTOMAKE_OPTIONS=foreign
lib_LTLIBRARIES=libserverGamesharedspace.la
libserverGamesharedspace_la_CXXFLAGS=\
	-I$(srcdir)/../../../include/public \
	-I$(srcdir)/../../../include/private \
	-I$(srcdir)/../../src/$(platform) \
	-I$(engine_dir)/server/library/serverMetrics/include/public \
	-I$(engine_dir)/server/library/serverNetworkMessages/include/public \
	-I$(engine_dir)/server/library/serverScript/include/public \
	-I$(engine_dir)/server/library/serverUtility/include/public \
	-I$(engine_dir)/shared/library/sharedCollision/include/public \
	-I$(engine_dir)/shared/library/sharedDebug/include/public \
	-I$(engine_dir)/shared/library/sharedFile/include/public \
	-I$(engine_dir)/shared/library/sharedFoundation/include/public \
	-I$(engine_dir)/shared/library/sharedFoundationTypes/include/public \
	-I$(engine_dir)/shared/library/sharedGame/include/public \
	-I$(engine_dir)/shared/library/sharedLog/include/public \
	-I$(engine_dir)/shared/library/sharedMath/include/public \
	-I$(engine_dir)/shared/library/sharedMathArchive/include/public \
	-I$(engine_dir)/shared/library/sharedMemoryManager/include/public \
	-I$(engine_dir)/shared/library/sharedMessageDispatch/include/public \
	-I$(engine_dir)/shared/library/sharedNetwork/include/public \
	-I$(engine_dir)/shared/library/sharedNetworkMessages/include/public \
	-I$(engine_dir)/shared/library/sharedObject/include/public \
	-I$(engine_dir)/shared/library/sharedRandom/include/public \
	-I$(engine_dir)/shared/library/sharedSkillSystem/include/public \
	-I$(engine_dir)/shared/library/sharedTerrain/include/public \
	-I$(engine_dir)/shared/library/sharedUtility/include/public \
	-I$(stlport_dir)/stlport \
	-I$(singleton_dir)/include \
	-I$(boost_dir) \
	-I$(udplibrary_dir) \
	-I$(soePlatform_dir)/CommodityAPI \
	-I$(archive_dir)/include \
	-I$(crypto_dir)/include \
	-I$(localization_dir)/include \
	-I$(localization_dir)/include \
	-I$(localizationArchive_dir)/include/public \
	-I$(fileInterface_dir)/include/public \
	-I$(unicode_dir)/include \
	-I$(unicodeArchive_dir)/include/public \
	-I$(game_dir)/shared/library/swgSharedUtility/include/public \
	-I$(game_dir)/server/application/SwgGameServer/include/public \
	-Wno-ctor-dtor-privacy
libserverGamesharedspace_la_SOURCES=\
	AiPilotManager.cpp \
	AiPilotManager.h \
	AiShipPilotData.cpp \
	AiShipPilotData.h \
	Missile.cpp \
	Missile.h \
	MissileManager.cpp \
	MissileManager.h \
	MiningAsteroidController.cpp \
	MiningAsteroidController.h \
	NebulaManagerServer.cpp \
	NebulaManagerServer.h \
	ProjectileManager.cpp \
	ProjectileManager.h \
	ServerAsteroidManager.cpp \
	ServerAsteroidManager.h \
	ServerShipComponentData.cpp \
	ServerShipComponentData.h \
	ServerShipTargeting.cpp \
	ServerShipTargeting.h \
	ShipAiEnemySearchManager.cpp \
	ShipAiEnemySearchManager.h \
	ShipAiReactionManager.cpp \
	ShipAiReactionManager.h \
	ShipClientUpdateTracker.cpp \
	ShipClientUpdateTracker.h \
	ShipComponentDataArmor.cpp \
	ShipComponentDataArmor.h \
	ShipComponentDataBooster.cpp \
	ShipComponentDataBooster.h \
	ShipComponentDataBridge.cpp \
	ShipComponentDataBridge.h \
	ShipComponentDataCapacitor.cpp \
	ShipComponentDataCapacitor.h \
	ShipComponentDataCargoHold.cpp \
	ShipComponentDataCargoHold.h \
	ShipComponentDataModification.cpp \
	ShipComponentDataModification.h \
	ShipComponentDataDroidInterface.cpp \
	ShipComponentDataDroidInterface.h \
	ShipComponentDataEngine.cpp \
	ShipComponentDataEngine.h \
	ShipComponentDataHangar.cpp \
	ShipComponentDataHangar.h \
	ShipComponentDataManager.cpp \
	ShipComponentDataManager.h \
	ShipComponentDataReactor.cpp \
	ShipComponentDataReactor.h \
	ShipComponentDataShield.cpp \
	ShipComponentDataShield.h \
	ShipComponentDataTargetingStation.cpp \
	ShipComponentDataTargetingStation.h \
	ShipComponentDataWeapon.cpp \
	ShipComponentDataWeapon.h \
	ShipInternalDamageOverTime.cpp \
	ShipInternalDamageOverTime.h \
	ShipInternalDamageOverTimeManager.cpp \
	ShipInternalDamageOverTimeManager.h \
	SpaceAttackSquad.cpp \
	SpaceAttackSquad.h \
	SpaceDockingManager.cpp \
	SpaceDockingManager.h \
	SpacePath.cpp \
	SpacePath.h \
	SpacePathManager.cpp \
	SpacePathManager.h \
	SpaceSquad.cpp \
	SpaceSquad.h \
	SpaceSquadManager.cpp \
	SpaceSquadManager.h \
	SpaceVisibilityManager.cpp \
	SpaceVisibilityManager.h \
	VisibleObjectNotification.cpp \
	VisibleObjectNotification.h
libserverGamesharedspace_la_LDFLAGS=-avoid-version

include $(engine_dir)/../make_include/engine.include
