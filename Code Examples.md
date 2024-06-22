# C++ in Python

```Python
import ROOT
ROOT.gInterpreter.ProcessLine('#include "c2pyexample.h"')
a = ROOT.A(123)
ROOT.printA(a)
```

```C++
TPython::Exec("print(1 + 1)")
auto b = (TBrowser*)TPython::Eval("ROOT.TBrowser()")
TPython::Prompt()
```
