# Linter Summary

Linting was performed using [Solium](https://github.com/duaraghav8/Solium) on the unchanged proxy repository code. 

The default Solium linter options were used, which correspond to the [official Solidity style guide](http://solidity.readthedocs.io/en/develop/style-guide.html#). 

Output was generated using both the `gcc` and `pretty` options.

The following error and warning counts were found:

## UportRegistry.sol

1 error, 11 warnings found.

The errors were reviewed, and all were related to whitespace in some form. 

__Recommendation:__ This is not a significant issue for security purposes, but the use of a linter during standard testing is encouraged.  

