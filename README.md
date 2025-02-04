# PHP Foreach Loop Pass-by-Reference Bug

This repository demonstrates a subtle bug in PHP related to the use of pass-by-reference in `foreach` loops.  When processing an array of strings using a `foreach` loop with references (`&`), modifications within the loop affect the original array elements, potentially leading to unexpected behavior.

The `bug.php` file contains code that showcases this issue. The `bugSolution.php` file provides a corrected version.

This example highlights the importance of understanding PHP's pass-by-reference mechanism and the potential pitfalls when dealing with mutable data structures.