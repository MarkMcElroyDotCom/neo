# FlexPage for NEO 1.1.0

This branch adds **FlexPage** to the book page menu. A FlexPage can sit before, between, or after chapters. Its heading is directly editable, so writers can use titles such as “Publisher’s Foreword” without adding a new fixed page type for every possibility.

FlexPages stay out of chapter numbering and story word counts. They appear by title in the outline and book contents, and their title and body are included in exports. Their body uses no drop cap or automatic first-line indent.

The custom build can check for official NEO releases but does not automatically install them over this feature. To incorporate future upstream improvements, merge or rebase from Hugh Howey’s repository and rebuild.

For isolated testing, `NEO_TEST_LIBRARY_DIR` and `NEO_TEST_USER_DATA_DIR` can point a launch at disposable folders.
