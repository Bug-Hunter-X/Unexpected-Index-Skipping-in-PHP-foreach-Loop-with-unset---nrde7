# PHP Foreach Loop with unset() Bug
This repository demonstrates an uncommon bug in PHP related to using `unset()` within a `foreach` loop that iterates over an array.  Modifying the array during iteration can lead to unexpected index skipping and potentially incorrect results.

The `bug.php` file contains the buggy code, while `bugSolution.php` provides a corrected version that avoids this issue.

This issue is subtle and can be difficult to identify, especially in larger codebases.  Understanding this behavior is crucial for writing robust and predictable PHP code.