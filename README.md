$ pip install commoncode==32.4.0

$ make test

-> Run the test suite
.venv/bin/python manage.py test --noinput
Found 839 test(s).
Creating test database for alias 'default'...
System check identified no issues (0 silenced).
....s...................................................................ss................s.ss.............ss.s....s.ss..........................................................................................................................................................................s.....[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
.[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
/Volumes/nexB/repos/scancode.io/.venv/lib/python3.13/site-packages/formattedcode/output_cyclonedx.py:809: CycloneDxPluginNoPackagesWarning: The --cyclonedx-xml option will not output any component/dependency data as there are no package data in the present scan. To get package data please rerun the scan with --package or --system-package CLI options enabled.
  bom = CycloneDxBom.from_codebase(codebase)
/Volumes/nexB/repos/scancode.io/.venv/lib/python3.13/site-packages/formattedcode/output_cyclonedx.py:839: CycloneDxPluginNoPackagesWarning: The --cyclonedx-xml option will not output any component/dependency data as there are no package data in the present scan. To get package data please rerun the scan with --package or --system-package CLI options enabled.
  bom = CycloneDxBom.from_codebase(codebase)
...........[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
.x...........s........sss..............................................................................................................s.........................................................................................................................ssss..s.s[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
WARNING: Files are missing a SHA1 attribute. Incomplete SPDX document created.
WARNING: Files are missing a SHA1 attribute. Incomplete SPDX document created.
.[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
WARNING: Files are missing a SHA1 attribute. Incomplete SPDX document created.
WARNING: Files are missing a SHA1 attribute. Incomplete SPDX document created.
[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
WARNING: Files are missing a SHA1 attribute. Incomplete SPDX document created.
WARNING: Files are missing a SHA1 attribute. Incomplete SPDX document created.
..s.....ss............s..[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
WARNING: Files are missing a SHA1 attribute. Incomplete SPDX document created.
WARNING: Files are missing a SHA1 attribute. Incomplete SPDX document created.
.....[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
F[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
F.[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
F[DEPRECATION WARNING] The --csv option is deprecated and will be replaced by new CSV and tabular output formats in the next ScanCode release. Visit https://github.com/nexB/scancode-toolkit/issues/3043 to provide inputs and feedback.
.......................................................................................................................................................................................................................................
======================================================================
FAIL: test_scanpipe_scan_package_pipeline_integration (scanpipe.tests.test_pipelines.PipelinesIntegrationTest.test_scanpipe_scan_package_pipeline_integration)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "/Volumes/nexB/repos/scancode.io/scanpipe/tests/test_pipelines.py", line 720, in test_scanpipe_scan_package_pipeline_integration
    self.assertPipelineResultEqual(expected_file, scancode_file)
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/Volumes/nexB/repos/scancode.io/scanpipe/tests/test_pipelines.py", line 698, in assertPipelineResultEqual
    self.assertEqual(expected_data, result_data)
    ~~~~~~~~~~~~~~~~^^^^^^^^^^^^^^^^^^^^^^^^^^^^
AssertionError: {'hea[813 chars]s': [], 'warnings': [], 'extra_data': {'spdx_l[16805 chars][]}]} != {'hea[813 chars]s': ['ERROR: failed to run pre-scan plugin: fa[19736 chars][]}]}
Diff is 39981 characters long. Set self.maxDiff to None to see it.

======================================================================
FAIL: test_scanpipe_scan_package_pipeline_integration_multiple_packages (scanpipe.tests.test_pipelines.PipelinesIntegrationTest.test_scanpipe_scan_package_pipeline_integration_multiple_packages)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "/Volumes/nexB/repos/scancode.io/scanpipe/tests/test_pipelines.py", line 759, in test_scanpipe_scan_package_pipeline_integration_multiple_packages
    self.assertPipelineResultEqual(expected_file, scancode_file)
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/Volumes/nexB/repos/scancode.io/scanpipe/tests/test_pipelines.py", line 698, in assertPipelineResultEqual
    self.assertEqual(expected_data, result_data)
    ~~~~~~~~~~~~~~~~^^^^^^^^^^^^^^^^^^^^^^^^^^^^
AssertionError: {'hea[813 chars]s': [], 'warnings': [], 'extra_data': {'spdx_l[28178 chars][]}]} != {'hea[813 chars]s': ['ERROR: failed to run pre-scan plugin: fa[31289 chars][]}]}
Diff is 62265 characters long. Set self.maxDiff to None to see it.

======================================================================
FAIL: test_scanpipe_scan_package_single_file (scanpipe.tests.test_pipelines.PipelinesIntegrationTest.test_scanpipe_scan_package_single_file)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "/Volumes/nexB/repos/scancode.io/scanpipe/tests/test_pipelines.py", line 814, in test_scanpipe_scan_package_single_file
    self.assertPipelineResultEqual(expected_file, scancode_file)
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/Volumes/nexB/repos/scancode.io/scanpipe/tests/test_pipelines.py", line 698, in assertPipelineResultEqual
    self.assertEqual(expected_data, result_data)
    ~~~~~~~~~~~~~~~~^^^^^^^^^^^^^^^^^^^^^^^^^^^^
AssertionError: {'hea[813 chars]s': [], 'warnings': [], 'extra_data': {'spdx_l[53413 chars][]}]} != {'hea[813 chars]s': ['ERROR: failed to run pre-scan plugin: fa[56236 chars][]}]}
Diff is 131973 characters long. Set self.maxDiff to None to see it.

----------------------------------------------------------------------
Ran 839 tests in 64.683s

FAILED (failures=3, skipped=28, expected failures=1)
Destroying test database for alias 'default'...
make: *** [test] Error 1
