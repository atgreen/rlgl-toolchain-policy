# rlgl-toolchain-policy

This is a [Red Light Green
Light](https://github.com/atgreen/red-light-green-light) policy repo
for the [moxie-elf GNU
toolchain](http://moxielogic.org/blog/pages/toolchain.html).

[Red Light Green
Light](https://github.com/atgreen/red-light-green-light) (rlgl) is a
general-purpose, git-centric policy evaluation and enforcement tool.
In this case we are using rlgl to evaluate the results of a DejaGnu
testsuite run.  This allows us to document and annotate test failures
as we work through fixing them.  We also use the rlgl output to catch
regressions from a baseline by calling out all of the known problems
at a certain point in time.

The nightly moxie-elf GCC test runs use this policy with the hosted
rlgl service at [https://rl.gl](https://rl.gl). Results are posted to
the gcc-testresults mailing list here:
https://gcc.gnu.org/ml/gcc-testresults/ .  Look at recent moxie-elf
test results for _GREEN_ or _RED_ policy checks, and the corresponding
links.






