_`Some keyword may be useful sometime`_

> _`continue-on-error: false/true: to specify should continue run the next step or not if error occur._

> _`timeout-minutes:360 - the maximum number of minutes to let a workflow run before GitHub automatically cancels it. Default 360`_

_`Strategy ? Which we can specify in a certain job`_

- _Matrix strategies: a matrix strategy lets you use variables in a single job definition to automatically create multiple job runs that are based on the combinations of the variables. For example, you can use a matrix strategy to test your code in multiple versions of a language or on multiple operating systems._

- _Include keyword:  For each object in the include list, the key:value pairs in in the object will be added to each of the matrix combinations if none of the key:value pairs overwrite any of the original matrix values. Of the object cannot be added to any of the matrix combinations, a new matrix combination will be created instead._

- _Exclude keyword:  To remove specific configurations defined in the matrix. An exclude configuration only has to be a partial match for it to be excluded._