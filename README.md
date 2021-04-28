# lisp-halstead-metrics
Measuring Halstead metrics for Lisp source code. Made for fun, shared in the hopes that it might be interesting for others, but it is very un-

# Known issues
* Packages in the code that you want to get metrics for must exist in the system you run the metrics from (e.g. you must load Quicklisp libraries which the code uses).
* The tool assumes the code to be all straightforward expression-evaluation. There are no special cases for *defun*, *let*, etc. Thus, it should only be takes as an order-of-magnitude guess.
* The metrics themselves might be dubious, I don't really know the background.
