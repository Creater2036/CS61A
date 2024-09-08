This file holds the tests that you create. Remember to import the python file(s)
you wish to test, along with any other modules you may need.
Run your tests with "python3 ok -t --suite SUITE_NAME --case CASE_NAME -v"
--------------------------------------------------------------------------------

Suite 1

    >>> from scheme_reader import *
    >>> from scheme_forms import *
    >>> from scheme_eval_apply import *
    >>> from scheme_utils import *
    >>> from scheme_classes import *
    >>> from scheme_builtins import *
    >>> from scheme_tokens import *
    >>> from scheme import *
    >>> from pair import *

    >>> (cond ((= 4 3)) (3))
    3

    Case Example
        >>> scheme_read(Buffer(tokenize_lines(['nil'])))
        nil

