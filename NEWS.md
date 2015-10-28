# burnr v0.0.1

* Added `NEWS.md` file. Existing users should check back here for changes.

* `rug.filter` function is renamed `composite` (#31).

* `ggplot.fhx` is now `get_ggplot`. This is more descriptive (#18). The following arguments for this function have been changed as a part of this fix: `plot.rug` is now `composite_rug`, `filter.min` is now `filter_min`, `filter.prop` is now `filter_prop`, `event.size` is now `event_size`, `rugbuffer.size` is now `rugbuffer_size`, `rugdivide.pos` is now `rugdivide_pos`.

* `read.fhx` function is renamed `read_fhx` (#18).

* `write.fhx` function is renamed `write_fhx` (#18).

* `order.fhx` is now `sort` (see method `sort.fhx`). Also, added a boolean argument `decreasing`, which defaults to FALSE. Previously this has been TRUE (#34).

* `+` with `fhx` objects, (`+.fhx`) is now `concatenate`. So, `a + b` should now be `concatenate(a, b)`. (#33)