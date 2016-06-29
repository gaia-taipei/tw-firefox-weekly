##  ~ 06/24
[Firefox]
* [r?] [Bug 1203292](http://bugzil.la/1203292) - Replace permissions dropdown with 'x' icon in Permissions main view in Control Center
 * Fixed issue of panel cannot be auto-shrink in permission panel XBL.
 * Clean up latest review issues and update svg icons to glyphs.svg.
 * (Reviewer doesn't reply this week)
* [r?] [Bug 1229340](http://bugzil.la/1229340) - Overflow scrollbar causes an offset between animations and the time header in the animation timeline
 * It seems not so easy to stick scrubber handle (see https://bugzilla.mozilla.org/show_bug.cgi?id=1229340#c16), but I finally found a way to workaround it through CSS solution.
 * Remove above CSS workaround for scrubber handle.
 * I'm trying to fix test failures since unfortunately my patch ran into an edge case.
