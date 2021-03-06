Change Log
==========

Version 1.0.1 *(2013-02-05)*
----------------------------

 * New assertions:
   * `android.app.Instrumentation.ActivityMonitor`
   * `android.app.Instrumentation.ActivityResult`
   * `android.app.ListActivity`
   * `android.preference.CheckBoxPreference`
   * `android.preference.DialogPreference`
   * `android.preference.EditTextPreference`
   * `android.preference.ListPreference`
   * `android.preference.MultiSelectListPreference`
   * `android.preference.PreferenceActivity`
   * `android.preference.Preference`
   * `android.preference.PreferenceGroup`
   * `android.preference.PreferenceScreen`
   * `android.preference.RingtonePreference`
   * `android.preference.SwitchPreference`
   * `android.preference.TwoStatePreference`
   * `android.util.AttributeSet`
   * `android.util.Pair`
 * Added convenience methods for orientations to `Display`, `LinearLayout`, and
   `GridLayout`.
 * Added error and ellipsis checks for `TextView`.
 * Added column name checks for `Cursor`.
 * `LinearLayout` and `AdapterView` assertions now correctly extend from `ViewGroup` assertions.
 * Added `TextView` text assertions for empty, contains, starts with, and ends with.
 * Added general `hasVisibility(int)` assertion for `View`.
 * Correct spelling of `isNotInvisible` assertions for `View`.
 * Support for generics by assertions classes (e.g., `LruCacheAssert<K, V>`).
 * Support using string resource ID for most text assertions.


Version 1.0.0 *(2013-01-17)*
----------------------------

Initial release.
