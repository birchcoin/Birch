Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in `./configure`
and tests weren't explicitly disabled.

After configuring, they can be run with `make check`.

To run the birchd tests manually, launch `src/test/test_birch`.

To add more birchd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the `test/` directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the birch-qt tests manually, launch `src/qt/test/test_birch-qt`

To add more birch-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
