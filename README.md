# Larus flight data for CI

Recorded Larus sensor flights used by the regression tests of the Larus
software (larus-breeze/sw_tools#49). The flight logs are release assets,
not files in this repository.

| Release | File | Content | SHA256 |
|---|---|---|---|
| [testdata-v1](https://github.com/dspreitz/larus_flight_data/releases/tag/testdata-v1) | `flight_01.lrsx` | 4 h cross-country flight, sensor firmware 0.7.6, single GNSS, no external magnetometer, 98 MB | `a79b443ea3cac4adb909de5c2a49fc6284b0c2af06ab2ee8b45b59b749662674` |

The flight is published with the permission of the pilot and the Larus
maintainers, for testing the Larus software. A license for other uses has
not been chosen yet.

Used by:
- `sensor_data_analyzer/tests/flight_regression.py` in sw_tools (fixed reference values);
- the before/after comparison in the CI of sw_algorithms_lib.
