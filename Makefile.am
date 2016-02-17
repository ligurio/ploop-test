PACKAGE_BUGREPORT = "devel@openvz.org"

TEST_LOG_DRIVER = env AM_TAP_AWK='$(AWK)' $(SHELL) \
                  $(top_srcdir)/build-aux/tap-driver.sh

TESTS = tests/t00001-mount-raw-ploop \
        tests/t00002-take-snapshot-raw-ploop

EXTRA_DIST = $(TESTS)
