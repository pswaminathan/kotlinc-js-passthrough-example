Demonstrating a rules_kotlin issue with compiling JS libraries.

* Action: Build src:jvm and src:js
* Expected: Both src:jvm and src:js get `-Xmulti-platform` specified by `x_multi_platform` argument to `:kt_kotlinc_options`
* Actual: src:jvm succeeds, src:js doesn't get this option
