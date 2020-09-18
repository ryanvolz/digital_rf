**Added:**

* Add new `digital_rf_get_timestamp_floor` and `digital_rf_get_sample_ceil` functions that can be used to convert between a timestamp and sample index, given the rational sample rate. These have been made available so that users can perform these calculations in a way that is consistent with what is done internally.

**Changed:**

* <news item>

**Deprecated:**

* The `digital_rf_get_unix_time` function is now deprecated, as it relies on a `long double` sample rate. Use `digital_rf_get_unix_time_rational` instead.

**Removed:**

* <news item>

**Fixed:**

* Fix incorrect file bound calculation in `digital_rf_get_subdir_file` on platforms that have a `long double` that is different from amd64, notably at least the aarch64 ARM platform.

**Security:**

* <news item>
