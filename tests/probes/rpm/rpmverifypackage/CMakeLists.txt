if(ENABLE_PROBES_LINUX)
	add_oscap_test("test_probes_rpmverifypackage.sh")
	add_oscap_test("test_probes_rpmverifypackage_offline.sh")
endif()
