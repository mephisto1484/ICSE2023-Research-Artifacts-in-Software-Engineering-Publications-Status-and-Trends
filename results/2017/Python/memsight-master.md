Linting project at  F:\Python3.8env/data/2017/memsight-master
No .mllint.yml or pyproject.toml found in project folder, using default configuration
---

🏃 Running - Dependency Management (0.00 ms)
🏃 Running - Continuous Integration (CI) (1.00 ms)
🏃 Running - Code Quality (1.00 ms)
🏃 Running - Testing (1.00 ms)
✔️ Done - Dependency Management (1.00 ms)
🏃 Running - Version Control (1.00 ms)
🏃 Running - Version Control - Git (0.00 ms)
🏃 Running - Version Control - DVC (0.00 ms)
⏳ Waiting - Version Control (1.00 ms)
✔️ Done - Testing (1.00 ms)
✔️ Done - Version Control - DVC (0.00 ms)
🏃 Running - Code Quality - Pylint (0.00 ms)
🏃 Running - Code Quality - Mypy (0.00 ms)
🏃 Running - Code Quality - Black (0.00 ms)
🏃 Running - Code Quality - isort (0.00 ms)
🏃 Running - Code Quality - Bandit (0.00 ms)
⏳ Waiting - Code Quality (5 ms)
✔️ Done - Version Control - Git (51 ms)
🏃 Running - Version Control (52 ms)
✔️ Done - Version Control (52 ms)
✔️ Done - Continuous Integration (CI) (213 ms)
✔️ Done - Code Quality - Mypy (1.50 s)
✔️ Done - Code Quality - isort (2.33 s)
✔️ Done - Code Quality - Black (2.71 s)
✔️ Done - Code Quality - Bandit (3.51 s)
✔️ Done - Code Quality - Pylint (6.76 s)
✔️ Done - Code Quality (6.77 s)
🏃 Running - Code Quality (6.77 s)

✔️ All done!

---

1 ML Project Report
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────

┌──────────────────────┬─────────────────────────────────────────┐
│[1mProject[0m               │[1mDetails[0m                                  │
╞══════════════════════╪═════════════════════════════════════════╡
│Date                  │Sat, 20 Aug 2022 15:48:30 +0800          │
├──────────────────────┼─────────────────────────────────────────┤
│Path                  │F:\Python3.8env/data/2017/memsight-master│
├──────────────────────┼─────────────────────────────────────────┤
│Config                │default                                  │
├──────────────────────┼─────────────────────────────────────────┤
│Default               │Yes                                      │
├──────────────────────┼─────────────────────────────────────────┤
│Number of Python files│65                                       │
├──────────────────────┼─────────────────────────────────────────┤
│Lines of Python code  │5489                                     │
└──────────────────────┴─────────────────────────────────────────┘
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────

1.1 Reports

1.1.1 Version Control (version-control) — [1m0.0[0m%

┌──────┬─────┬──────┬────────────────────────────────────────────────┬─────────────────────────────────────────────────┐
│Passed│Score│Weight│Rule                                            │Slug                                             │
╞══════╪═════╪══════╪════════════════════════════════════════════════╪═════════════════════════════════════════════════╡
│  ❌  │ 0.0%│     1│Project uses Git                                │version-control/code/git                         │
├──────┼─────┼──────┼────────────────────────────────────────────────┼─────────────────────────────────────────────────┤
│  ❌  │ 0.0%│     1│DVC: Project uses Data Version Control          │version-control/data/dvc                         │
├──────┼─────┼──────┼────────────────────────────────────────────────┼─────────────────────────────────────────────────┤
│  ❌  │ 0.0%│     1│DVC: Is installed                               │version-control/data/dvc-is-installed            │
├──────┼─────┼──────┼────────────────────────────────────────────────┼─────────────────────────────────────────────────┤
│  ❌  │ 0.0%│     1│DVC: Folder '.dvc' should be committed to Git   │version-control/data/commit-dvc-folder           │
├──────┼─────┼──────┼────────────────────────────────────────────────┼─────────────────────────────────────────────────┤
│  ❌  │ 0.0%│     1│DVC: Should have at least one remote data       │version-control/data/dvc-has-remote              │
│      │     │      │storage configured                              │                                                 │
├──────┼─────┼──────┼────────────────────────────────────────────────┼─────────────────────────────────────────────────┤
│  ❌  │ 0.0%│     1│DVC: Should be tracking at least one data file  │version-control/data/dvc-has-files               │
├──────┼─────┼──────┼────────────────────────────────────────────────┼─────────────────────────────────────────────────┤
│      │[3mTotal[23m│      │                                                │                                                 │
├──────┼─────┼──────┼────────────────────────────────────────────────┼─────────────────────────────────────────────────┤
│  ❌  │ [1m0.0[0m%│      │Version Control                                 │version-control                                  │
└──────┴─────┴──────┴────────────────────────────────────────────────┴─────────────────────────────────────────────────┘
1.1.2 Dependency Management (dependency-management) — [1m0.0[0m%

┌──────┬─────┬──────┬────────────────────────────────────────────────┬────────────────────────────┐
│Passed│Score│Weight│Rule                                            │Slug                        │
╞══════╪═════╪══════╪════════════════════════════════════════════════╪════════════════════════════╡
│  ❌  │ 0.0%│     1│Project properly keeps track of its dependencies│dependency-management/use   │
├──────┼─────┼──────┼────────────────────────────────────────────────┼────────────────────────────┤
│  ❌  │ 0.0%│     1│Project should only use one dependency manager  │dependency-management/single│
├──────┼─────┼──────┼────────────────────────────────────────────────┼────────────────────────────┤
│      │[3mTotal[23m│      │                                                │                            │
├──────┼─────┼──────┼────────────────────────────────────────────────┼────────────────────────────┤
│  ❌  │ [1m0.0[0m%│      │Dependency Management                           │dependency-management       │
└──────┴─────┴──────┴────────────────────────────────────────────────┴────────────────────────────┘
1.1.3 Code Quality (code-quality) — [1m29.8[0m%

┌──────┬──────┬──────┬────────────────────────────────────────────────┬────────────────────────────────────────────────┐
│Passed│ Score│Weight│Rule                                            │Slug                                            │
╞══════╪══════╪══════╪════════════════════════════════════════════════╪════════════════════════════════════════════════╡
│  ❌  │  0.0%│     1│Project should use code quality linters         │code-quality/use-linters                        │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ✅  │100.0%│     1│All code quality linters should be installed in │code-quality/linters-installed                  │
│      │      │      │the current environment                         │                                                │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │  8.9%│     1│Pylint reports no issues with this project      │code-quality/pylint/no-issues                   │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │  0.0%│     1│Pylint is configured for this project           │code-quality/pylint/is-configured               │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ✅  │100.0%│     1│Mypy reports no issues with this project        │code-quality/mypy/no-issues                     │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │  0.0%│     1│Black reports no issues with this project       │code-quality/black/no-issues                    │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │  0.0%│     1│isort reports no issues with this project       │code-quality/isort/no-issues                    │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │  0.0%│     0│isort is properly configured                    │code-quality/isort/is-configured                │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│      │ [3mTotal[23m│      │                                                │                                                │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │ [1m29.8[0m%│      │Code Quality                                    │code-quality                                    │
└──────┴──────┴──────┴────────────────────────────────────────────────┴────────────────────────────────────────────────┘
1.1.3.1 Details — Project should use code quality linters — ❌

Oh my, no code quality linters were detected in your project!

We recommend that you start using the following linters in your project to help you measure and maintain the quality of
your code:
• Pylint
• Mypy
• Black
• isort
• Bandit

This rule will be satisfied, iff for each of these linters:
• [1mEither[0m there is a configuration file for this linter in the project
• [1mOr[0m the linter is a dependency of the project

Specifically, we recommend adding each linter to the development dependencies of your dependency manager, e.g. using
poetry add --dev pylint or pipenv install --dev pylint

1.1.3.2 Details — Pylint reports no issues with this project — ❌

Pylint reported [1m500[0m issues with your project:
• memsight-master__init__.py:1,0 - [3m(C0103)[23m Module name "memsight-master" doesn't conform to snake_case naming style
• memsight-master\docs\env-setup\veritesting.py:5,0 - [3m(C0301)[23m Line too long (114/100)
• memsight-master\docs\env-setup\veritesting.py:20,0 - [3m(C0301)[23m Line too long (103/100)
• memsight-master\docs\env-setup\veritesting.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\docs\env-setup\veritesting.py:1,0 - [3m(E0611)[23m No name 'ExplorationTechnique' in module ''
• memsight-master\docs\env-setup\veritesting.py:11,8 - [3m(R1725)[23m Consider using Python 3 style super() without arguments
• memsight-master\docs\env-setup\veritesting.py:14,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\docs\env-setup\veritesting.py:15,8 - [3m(C0103)[23m Variable name "vt" doesn't conform to snake_case naming
  style
• memsight-master\docs\env-setup\veritesting.py:17,12 - [3m(C0103)[23m Variable name "pg" doesn't conform to snake_case naming
  style
• memsight-master\docs\env-setup\veritesting.py:3,0 - [3m(R0903)[23m Too few public methods (1/2)
• memsight-master\executor\executor.py:19,19 - [3m(E0001)[23m invalid syntax (<unknown>, line 19)
• memsight-master\executor\executor_config.py:14,15 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean
  print(e)? (<unknown>, line 14)
• memsight-master\explore.py:30,0 - [3m(C0304)[23m Final newline missing
• memsight-master\explore.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\explore.py:2,0 - [3m(E0401)[23m Unable to import 'executor'
• memsight-master\explore.py:3,0 - [3m(E0401)[23m Unable to import 'memory'
• memsight-master\explore.py:4,0 - [3m(E0401)[23m Unable to import 'memory'
• memsight-master\explore.py:5,0 - [3m(E0401)[23m Unable to import 'utils'
• memsight-master\explore.py:8,0 - [3m(W0404)[23m Reimport 'memory.factory' (imported line 3)
• memsight-master\explore.py:8,0 - [3m(E0401)[23m Unable to import 'memory.factory'
• memsight-master\explore.py:9,0 - [3m(E0401)[23m Unable to import 'utils'
• memsight-master\explore.py:7,0 - [3m(C0411)[23m standard import "import sys" should be placed before "from executor import
  executor"
• memsight-master\explore.py:10,0 - [3m(C0411)[23m standard import "import logging" should be placed before "from executor
  import executor"
• memsight-master\explore.py:4,0 - [3m(W0611)[23m Unused range_fully_symbolic_memory imported from memory
• memsight-master\explore.py:5,0 - [3m(W0611)[23m Unused parse_args imported from utils
• memsight-master\explore.py:8,0 - [3m(W0611)[23m Unused import memory.factory
• memsight-master\memory\angr_symbolic_memory.py:19,42 - [3m(C0303)[23m Trailing whitespace
• memsight-master\memory\angr_symbolic_memory.py:20,40 - [3m(C0303)[23m Trailing whitespace
• memsight-master\memory\angr_symbolic_memory.py:21,26 - [3m(C0303)[23m Trailing whitespace
• memsight-master\memory\angr_symbolic_memory.py:22,26 - [3m(C0303)[23m Trailing whitespace
• memsight-master\memory\angr_symbolic_memory.py:23,29 - [3m(C0303)[23m Trailing whitespace
• memsight-master\memory\angr_symbolic_memory.py:35,0 - [3m(C0301)[23m Line too long (153/100)
• memsight-master\memory\angr_symbolic_memory.py:37,0 - [3m(C0301)[23m Line too long (116/100)
• memsight-master\memory\angr_symbolic_memory.py:40,42 - [3m(C0303)[23m Trailing whitespace
• memsight-master\memory\angr_symbolic_memory.py:43,0 - [3m(C0301)[23m Line too long (130/100)
• memsight-master\memory\angr_symbolic_memory.py:44,0 - [3m(C0301)[23m Line too long (113/100)
• memsight-master\memory\angr_symbolic_memory.py:45,0 - [3m(C0301)[23m Line too long (109/100)
• memsight-master\memory\angr_symbolic_memory.py:49,0 - [3m(C0301)[23m Line too long (133/100)
• memsight-master\memory\angr_symbolic_memory.py:50,0 - [3m(C0301)[23m Line too long (112/100)
• memsight-master\memory\angr_symbolic_memory.py:51,0 - [3m(C0301)[23m Line too long (109/100)
• memsight-master\memory\angr_symbolic_memory.py:84,0 - [3m(C0304)[23m Final newline missing
• memsight-master\memory\angr_symbolic_memory.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\memory\angr_symbolic_memory.py:1,0 - [3m(C0410)[23m Multiple imports on one line (angr, logging)
• memsight-master\memory\angr_symbolic_memory.py:1,0 - [3m(E0401)[23m Unable to import 'angr'
• memsight-master\memory\angr_symbolic_memory.py:4,0 - [3m(E0401)[23m Unable to import 'claripy'
• memsight-master\memory\angr_symbolic_memory.py:5,0 - [3m(E0401)[23m Unable to import 'resource'
• memsight-master\memory\angr_symbolic_memory.py:9,0 - [3m(E0401)[23m Unable to import 'pyvex'
• memsight-master\memory\angr_symbolic_memory.py:10,0 - [3m(E0401)[23m Unable to import 'bitstring'
• memsight-master\memory\angr_symbolic_memory.py:17,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\memory\angr_symbolic_memory.py:19,4 - [3m(R0913)[23m Too many arguments (8/5)
• memsight-master\memory\angr_symbolic_memory.py:23,16 - [3m(W0613)[23m Unused argument 'endness'
• memsight-master\memory\angr_symbolic_memory.py:24,16 - [3m(W0613)[23m Unused argument 'check_permissions'
• memsight-master\memory\angr_symbolic_memory.py:39,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:43,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:43,4 - [3m(R0913)[23m Too many arguments (9/5)
• memsight-master\memory\angr_symbolic_memory.py:45,25 - [3m(C0321)[23m More than one statement on a single line
• memsight-master\memory\angr_symbolic_memory.py:49,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:49,4 - [3m(R0913)[23m Too many arguments (10/5)
• memsight-master\memory\angr_symbolic_memory.py:50,25 - [3m(C0321)[23m More than one statement on a single line
• memsight-master\memory\angr_symbolic_memory.py:54,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:57,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:61,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:61,4 - [3m(C0103)[23m Attribute name "id" doesn't conform to snake_case
  naming style
• memsight-master\memory\angr_symbolic_memory.py:65,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:68,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:71,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:74,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:79,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:83,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\angr_symbolic_memory.py:1,0 - [3m(C0411)[23m standard import "import angr, logging" should be placed
  before "import angr, logging"
• memsight-master\memory\angr_symbolic_memory.py:2,0 - [3m(C0411)[23m standard import "from itertools import product" should
  be placed before "import angr, logging"
• memsight-master\memory\angr_symbolic_memory.py:3,0 - [3m(C0411)[23m standard import "import struct" should be placed before
  "import angr, logging"
• memsight-master\memory\angr_symbolic_memory.py:5,0 - [3m(C0411)[23m standard import "import resource" should be placed
  before "import angr, logging"
• memsight-master\memory\angr_symbolic_memory.py:6,0 - [3m(C0411)[23m standard import "import pdb" should be placed before
  "import angr, logging"
• memsight-master\memory\angr_symbolic_memory.py:7,0 - [3m(C0411)[23m standard import "import sys" should be placed before
  "import angr, logging"
• memsight-master\memory\angr_symbolic_memory.py:8,0 - [3m(C0411)[23m standard import "import os" should be placed before
  "import angr, logging"
• memsight-master\memory\angr_symbolic_memory.py:11,0 - [3m(C0411)[23m standard import "import traceback" should be placed
  before "import angr, logging"
• memsight-master\memory\angr_symbolic_memory.py:12,0 - [3m(C0411)[23m standard import "import bisect" should be placed before
  "import angr, logging"
• memsight-master\memory\angr_symbolic_memory.py:2,0 - [3m(W0611)[23m Unused product imported from itertools
• memsight-master\memory\angr_symbolic_memory.py:3,0 - [3m(W0611)[23m Unused import struct
• memsight-master\memory\angr_symbolic_memory.py:4,0 - [3m(W0611)[23m Unused import claripy
• memsight-master\memory\angr_symbolic_memory.py:5,0 - [3m(W0611)[23m Unused import resource
• memsight-master\memory\angr_symbolic_memory.py:6,0 - [3m(W0611)[23m Unused import pdb
• memsight-master\memory\angr_symbolic_memory.py:7,0 - [3m(W0611)[23m Unused import sys
• memsight-master\memory\angr_symbolic_memory.py:8,0 - [3m(W0611)[23m Unused import os
• memsight-master\memory\angr_symbolic_memory.py:9,0 - [3m(W0611)[23m Unused import pyvex
• memsight-master\memory\angr_symbolic_memory.py:10,0 - [3m(W0611)[23m Unused Bits imported from bitstring
• memsight-master\memory\angr_symbolic_memory.py:11,0 - [3m(W0611)[23m Unused import traceback
• memsight-master\memory\angr_symbolic_memory.py:12,0 - [3m(W0611)[23m Unused import bisect
• memsight-master\memory\factory.py:10,0 - [3m(C0301)[23m Line too long (131/100)
• memsight-master\memory\factory.py:11,0 - [3m(C0301)[23m Line too long (135/100)
• memsight-master\memory\factory.py:15,0 - [3m(C0301)[23m Line too long (180/100)
• memsight-master\memory\factory.py:16,0 - [3m(C0304)[23m Final newline missing
• memsight-master\memory\factory.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\memory\factory.py:1,0 - [3m(C0410)[23m Multiple imports on one line (sys, os)
• memsight-master\memory\factory.py:4,0 - [3m(E0401)[23m Unable to import 'utils'
• memsight-master\memory\factory.py:4,0 - [3m(C0413)[23m Import "import utils" should be placed at the top of the module
• memsight-master\memory\factory.py:5,0 - [3m(E0401)[23m Unable to import 'range_fully_symbolic_memory'
• memsight-master\memory\factory.py:5,0 - [3m(C0413)[23m Import "import range_fully_symbolic_memory" should be placed at the
  top of the module
• memsight-master\memory\factory.py:7,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\factory.py:7,29 - [3m(W0613)[23m Unused argument 'angr_project'
• memsight-master\memory\factory.py:14,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\paged_memory.py:208,0 - [3m(C0305)[23m Trailing newlines
• memsight-master\memory\lib\paged_memory.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\memory\lib\paged_memory.py:3,0 - [3m(C0410)[23m Multiple imports on one line (sys, os)
• memsight-master\memory\lib\paged_memory.py:5,0 - [3m(E0401)[23m Unable to import 'memory'
• memsight-master\memory\lib\paged_memory.py:5,0 - [3m(C0413)[23m Import "import memory" should be placed at the top of the
  module
• memsight-master\memory\lib\paged_memory.py:7,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\paged_memory.py:9,8 - [3m(C0415)[23m Import outside toplevel (time)
• memsight-master\memory\lib\paged_memory.py:18,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\memory\lib\paged_memory.py:18,0 - [3m(R0205)[23m Class 'PagedMemory' inherits from object, can be safely
  removed from bases in python3
• memsight-master\memory\lib\paged_memory.py:26,4 - [3m(W0102)[23m Dangerous default value dict() (builtins.dict) as argument
• memsight-master\memory\lib\paged_memory.py:26,23 - [3m(W0621)[23m Redefining name 'memory' from outer scope (line 5)
• memsight-master\memory\lib\paged_memory.py:26,37 - [3m(R1735)[23m Consider using {} instead of dict()
• memsight-master\memory\lib\paged_memory.py:64,19 - [3m(R1735)[23m Consider using {} instead of dict()
• memsight-master\memory\lib\paged_memory.py:79,12 - [3m(C0103)[23m Variable name "p" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\paged_memory.py:84,4 - [3m(R0914)[23m Too many local variables (16/15)
• memsight-master\memory\lib\paged_memory.py:150,32 - [3m(C0103)[23m Variable name "v" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\paged_memory.py:152,40 - [3m(C0103)[23m Variable name "vv" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\paged_memory.py:125,8 - [3m(R1702)[23m Too many nested blocks (8/5)
• memsight-master\memory\lib\paged_memory.py:185,24 - [3m(C0103)[23m Variable name "v" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\paged_memory.py:187,32 - [3m(C0103)[23m Variable name "vv" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\paged_memory.py:125,8 - [3m(R1702)[23m Too many nested blocks (6/5)
• memsight-master\memory\lib\paged_memory.py:84,4 - [3m(R0912)[23m Too many branches (23/12)
• memsight-master\memory\lib\paged_memory.py:84,4 - [3m(R0915)[23m Too many statements (52/50)
• memsight-master\memory\lib\paged_memory.py:206,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\paged_memory.py:206,19 - [3m(W0621)[23m Redefining name 'memory' from outer scope (line 5)
• memsight-master\memory\lib\pitree\interval.py:30,0 - [3m(C0304)[23m Final newline missing
• memsight-master\memory\lib\pitree\interval.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\memory\lib\pitree\interval.py:1,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\memory\lib\pitree\interval.py:1,0 - [3m(R0205)[23m Class 'Interval' inherits from object, can be safely
  removed from bases in python3
• memsight-master\memory\lib\pitree\interval.py:8,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\interval.py:8,4 - [3m(C0103)[23m Method name "containsPoint" doesn't conform to snake_case
  naming style
• memsight-master\memory\lib\pitree\interval.py:9,15 - [3m(R1716)[23m Simplify chained comparison between the operands
• memsight-master\memory\lib\pitree\interval.py:11,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\interval.py:14,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\interval.py:17,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\intervaltree.py:105,15 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you
  mean print("\t"*tabs, "[", node.interval.begin, ",", node.interval.end, "]", "max =", node.max, "| bf =",
  node.balancing_factor, "| parent =", node.parent.interval)? (<unknown>, line 105)
• memsight-master\memory\lib\pitree\node.py:93,0 - [3m(C0301)[23m Line too long (123/100)
• memsight-master\memory\lib\pitree\node.py:101,0 - [3m(C0301)[23m Line too long (107/100)
• memsight-master\memory\lib\pitree\node.py:143,0 - [3m(C0304)[23m Final newline missing
• memsight-master\memory\lib\pitree\node.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\memory\lib\pitree\node.py:1,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\memory\lib\pitree\node.py:1,0 - [3m(R0205)[23m Class 'Node' inherits from object, can be safely removed from
  bases in python3
• memsight-master\memory\lib\pitree\node.py:12,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\node.py:15,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\node.py:16,8 - [3m(C0103)[23m Variable name "p" doesn't conform to snake_case naming style
• memsight-master\memory\lib\pitree\node.py:39,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\node.py:39,4 - [3m(C0103)[23m Method name "rotationRight" doesn't conform to snake_case
  naming style
• memsight-master\memory\lib\pitree\node.py:40,8 - [3m(C0103)[23m Variable name "z" doesn't conform to snake_case naming style
• memsight-master\memory\lib\pitree\node.py:41,8 - [3m(C0103)[23m Variable name "t" doesn't conform to snake_case naming style
• memsight-master\memory\lib\pitree\node.py:56,8 - [3m(C0103)[23m Variable name "lm" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\node.py:57,8 - [3m(C0103)[23m Variable name "rm" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\node.py:59,8 - [3m(C0103)[23m Variable name "lm" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\node.py:60,8 - [3m(C0103)[23m Variable name "rm" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\node.py:63,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\node.py:63,4 - [3m(C0103)[23m Method name "rotationLeft" doesn't conform to snake_case
  naming style
• memsight-master\memory\lib\pitree\node.py:64,8 - [3m(C0103)[23m Variable name "z" doesn't conform to snake_case naming style
• memsight-master\memory\lib\pitree\node.py:65,8 - [3m(C0103)[23m Variable name "t" doesn't conform to snake_case naming style
• memsight-master\memory\lib\pitree\node.py:80,8 - [3m(C0103)[23m Variable name "lm" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\node.py:81,8 - [3m(C0103)[23m Variable name "rm" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\node.py:83,8 - [3m(C0103)[23m Variable name "lm" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\node.py:84,8 - [3m(C0103)[23m Variable name "rm" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\node.py:88,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\node.py:96,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\node.py:101,11 - [3m(R1716)[23m Simplify chained comparison between the operands
• memsight-master\memory\lib\pitree\node.py:105,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\node.py:113,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\node.py:129,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\memory\lib\pitree\node.py:129,0 - [3m(R0205)[23m Class 'Root' inherits from object, can be safely removed
  from bases in python3
• memsight-master\memory\lib\pitree\node.py:138,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\node.py:129,0 - [3m(R0903)[23m Too few public methods (1/2)
• memsight-master\memory\lib\pitree\parser.py:26,15 - [3m(E0001)[23m invalid syntax (<unknown>, line 26)
• memsight-master\memory\lib\pitree\pitree.py:169,15 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean
  print("[pitree] tot size=%d bytes"          % tot_size                  + )? (<unknown>, line 169)
• memsight-master\memory\lib\pitree\profiler.py:14,15 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean
  print("----------------")? (<unknown>, line 14)
• memsight-master\memory\lib\pitree\runner.py:53,12 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean
  print("opening log file %s" % args[0])? (<unknown>, line 53)
• memsight-master\memory\lib\pitree\test.py:19,11 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean
  print("t")? (<unknown>, line 19)
• memsight-master\memory\lib\pitree\tester.py:74,19 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean
  print(msg)? (<unknown>, line 74)
• memsight-master\memory\lib\pitree\untree.py:57,0 - [3m(C0301)[23m Line too long (101/100)
• memsight-master\memory\lib\pitree\untree.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\memory\lib\pitree\untree.py:1,0 - [3m(C0103)[23m Constant name "untree_next_id" doesn't conform to
  UPPER_CASE naming style
• memsight-master\memory\lib\pitree\untree.py:3,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\memory\lib\pitree\untree.py:3,0 - [3m(R0205)[23m Class 'Untree' inherits from object, can be safely removed
  from bases in python3
• memsight-master\memory\lib\pitree\untree.py:8,4 - [3m(W0102)[23m Dangerous default value [] as argument
• memsight-master\memory\lib\pitree\untree.py:12,8 - [3m(C0103)[23m Constant name "untree_next_id" doesn't conform to
  UPPER_CASE naming style
• memsight-master\memory\lib\pitree\untree.py:12,8 - [3m(W0603)[23m Using the global statement
• memsight-master\memory\lib\pitree\untree.py:20,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\untree.py:25,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\untree.py:37,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\untree.py:37,21 - [3m(C0103)[23m Argument name "a" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\untree.py:37,24 - [3m(C0103)[23m Argument name "b" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\untree.py:42,12 - [3m(C0103)[23m Variable name "e" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\untree.py:48,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\untree.py:48,26 - [3m(C0103)[23m Argument name "e" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\untree.py:55,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\untree.py:57,8 - [3m(C0103)[23m Variable name "r" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\untree.py:59,46 - [3m(W0212)[23m Access to a protected member _id of a client class
• memsight-master\memory\lib\pitree\untree.py:60,32 - [3m(C0321)[23m More than one statement on a single line
• memsight-master\memory\lib\pitree\untree.py:60,32 - [3m(W0212)[23m Access to a protected member _do_log of a client class
• memsight-master\memory\lib\pitree\untree.py:60,67 - [3m(W0212)[23m Access to a protected member _id of a client class
• memsight-master\memory\lib\pitree\untree.py:64,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\untree.py:68,8 - [3m(C0103)[23m Variable name "e" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\pitree\untree.py:74,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\untree.py:78,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\pitree\untree.py:78,4 - [3m(W0211)[23m Static method with 'cls' as first argument
• memsight-master\memory\lib\pitree\untree.py:78,20 - [3m(W0613)[23m Unused argument 'cls'
• memsight-master\memory\lib\pitree\untree.py:78,25 - [3m(W0613)[23m Unused argument 'data'
• memsight-master\memory\lib\pitree\untree.py:82,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\memory\lib\pitree\untree.py:82,0 - [3m(R0205)[23m Class 'UntreeItem' inherits from object, can be safely
  removed from bases in python3
• memsight-master\memory\lib\pitree\untree.py:82,0 - [3m(R0903)[23m Too few public methods (0/2)
• memsight-master\memory\lib\range_map.py:179,0 - [3m(C0305)[23m Trailing newlines
• memsight-master\memory\lib\range_map.py:174,22 - [3m(W0511)[23m ToDo
• memsight-master\memory\lib\range_map.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\memory\lib\range_map.py:5,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\memory\lib\range_map.py:5,0 - [3m(R0205)[23m Class 'RangeMap' inherits from object, can be safely removed
  from bases in python3
• memsight-master\memory\lib\range_map.py:10,4 - [3m(W0102)[23m Dangerous default value [] as argument
• memsight-master\memory\lib\range_map.py:10,4 - [3m(W0102)[23m Dangerous default value {} as argument
• memsight-master\memory\lib\range_map.py:16,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\range_map.py:29,12 - [3m(C0103)[23m Variable name "t" doesn't conform to snake_case naming style
• memsight-master\memory\lib\range_map.py:47,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\range_map.py:51,12 - [3m(C0103)[23m Variable name "r" doesn't conform to snake_case naming style
• memsight-master\memory\lib\range_map.py:65,24 - [3m(C0103)[23m Variable name "r" doesn't conform to snake_case naming style
• memsight-master\memory\lib\range_map.py:79,20 - [3m(C0103)[23m Variable name "r" doesn't conform to snake_case naming style
• memsight-master\memory\lib\range_map.py:87,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\range_map.py:87,21 - [3m(C0103)[23m Argument name "r" doesn't conform to snake_case naming style
• memsight-master\memory\lib\range_map.py:111,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\range_map.py:151,26 - [3m(W0622)[23m Redefining built-in 'list'
• memsight-master\memory\lib\range_map.py:152,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• memsight-master\memory\lib\range_map.py:153,12 - [3m(C0103)[23m Variable name "o" doesn't conform to snake_case naming style
• memsight-master\memory\lib\range_map.py:158,32 - [3m(W0622)[23m Redefining built-in 'list'
• memsight-master\memory\lib\range_map.py:159,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• memsight-master\memory\lib\range_map.py:160,12 - [3m(C0103)[23m Variable name "o" doesn't conform to snake_case naming style
• memsight-master\memory\lib\range_map.py:165,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\range_map.py:166,8 - [3m(C0103)[23m Variable name "rm" doesn't conform to snake_case naming style
• memsight-master\memory\lib\range_map.py:169,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\range_map.py:171,12 - [3m(C0103)[23m Variable name "o" doesn't conform to snake_case naming style
• memsight-master\memory\lib\range_map.py:172,34 - [3m(W0212)[23m Access to a protected member _large_ranges of a client class
• memsight-master\memory\lib\range_map.py:169,28 - [3m(W0613)[23m Unused argument 'merge_conditions'
• memsight-master\memory\lib\range_tree.py:241,15 - [3m(E0001)[23m invalid syntax (<unknown>, line 241)
• memsight-master\memory\lib\sorted_collection.py:267,0 - [3m(C0301)[23m Line too long (103/100)
• memsight-master\memory\lib\sorted_collection.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\memory\lib\sorted_collection.py:3,0 - [3m(R0205)[23m Class 'SortedCollection' inherits from object, can be
  safely removed from bases in python3
• memsight-master\memory\lib\sorted_collection.py:85,12 - [3m(C2801)[23m Unnecessarily calls dunder method [1minit[0m. Instantiate
  class directly.
• memsight-master\memory\lib\sorted_collection.py:92,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\sorted_collection.py:93,8 - [3m(C2801)[23m Unnecessarily calls dunder method [1minit[0m. Instantiate
  class directly.
• memsight-master\memory\lib\sorted_collection.py:95,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\sorted_collection.py:101,26 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:111,15 - [3m(C0209)[23m Formatting a regular string which could be a
  f-string
• memsight-master\memory\lib\sorted_collection.py:120,27 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:122,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:126,20 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:129,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:133,20 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:136,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:140,21 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:143,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:147,27 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:150,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:154,21 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:156,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:162,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:165,25 - [3m(C0209)[23m Formatting a regular string which could be a
  f-string
• memsight-master\memory\lib\sorted_collection.py:169,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:172,25 - [3m(C0209)[23m Formatting a regular string which could be a
  f-string
• memsight-master\memory\lib\sorted_collection.py:176,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:179,25 - [3m(C0209)[23m Formatting a regular string which could be a
  f-string
• memsight-master\memory\lib\sorted_collection.py:183,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:186,25 - [3m(C0209)[23m Formatting a regular string which could be a
  f-string
• memsight-master\memory\lib\sorted_collection.py:190,8 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:193,25 - [3m(C0209)[23m Formatting a regular string which could be a
  f-string
• memsight-master\memory\lib\sorted_collection.py:199,14 - [3m(C0103)[23m Argument name "f" doesn't conform to snake_case
  naming style
• memsight-master\memory\lib\sorted_collection.py:208,12 - [3m(W0621)[23m Redefining name 'i' from outer scope (line 250)
• memsight-master\memory\lib\sorted_collection.py:208,15 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:215,12 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:222,12 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:229,12 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:236,12 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:243,12 - [3m(W0621)[23m Redefining name 'item' from outer scope (line 262)
• memsight-master\memory\lib\sorted_collection.py:273,11 - [3m(W0212)[23m Access to a protected member _keys of a client class
• memsight-master\memory\lib\sorted_collection.py:274,11 - [3m(W0212)[23m Access to a protected member _items of a client
  class
• memsight-master\memory\lib\sorted_collection.py:275,11 - [3m(W0212)[23m Access to a protected member _key of a client class
• memsight-master\memory\lib\sorted_collection.py:278,11 - [3m(W0212)[23m Access to a protected member _key of a client class
• memsight-master\memory\lib\sorted_collection.py:284,23 - [3m(R1736)[23m Unnecessary list index lookup, use 'item' instead
• memsight-master\memory\lib\sorted_collection.py:287,11 - [3m(W0212)[23m Access to a protected member _keys of a client class
• memsight-master\memory\lib\sorted_collection.py:288,11 - [3m(W0212)[23m Access to a protected member _items of a client
  class
• memsight-master\memory\lib\sorted_collection.py:310,4 - [3m(W0611)[23m Unused itemgetter imported from operator
• memsight-master\memory\lib\unpaged_memory.py:61,0 - [3m(C0305)[23m Trailing newlines
• memsight-master\memory\lib\unpaged_memory.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\memory\lib\unpaged_memory.py:3,0 - [3m(E0401)[23m Unable to import 'utils'
• memsight-master\memory\lib\unpaged_memory.py:5,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\memory\lib\unpaged_memory.py:5,0 - [3m(R0205)[23m Class 'PagedMemory' inherits from object, can be safely
  removed from bases in python3
• memsight-master\memory\lib\unpaged_memory.py:9,4 - [3m(W0102)[23m Dangerous default value dict() (builtins.dict) as argument
• memsight-master\memory\lib\unpaged_memory.py:9,37 - [3m(R1735)[23m Consider using {} instead of dict()
• memsight-master\memory\lib\unpaged_memory.py:9,23 - [3m(W0613)[23m Unused argument 'memory'
• memsight-master\memory\lib\unpaged_memory.py:31,16 - [3m(R1735)[23m Consider using {} instead of dict()
• memsight-master\memory\lib\unpaged_memory.py:32,12 - [3m(C0103)[23m Variable name "a" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\unpaged_memory.py:35,31 - [3m(R1735)[23m Consider using {} instead of dict()
• memsight-master\memory\lib\unpaged_memory.py:42,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\unpaged_memory.py:47,12 - [3m(C0103)[23m Variable name "a" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\unpaged_memory.py:49,16 - [3m(C0103)[23m Variable name "v" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\unpaged_memory.py:51,24 - [3m(C0103)[23m Variable name "vv" doesn't conform to snake_case naming
  style
• memsight-master\memory\lib\unpaged_memory.py:59,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\memory\lib\unpaged_memory.py:1,0 - [3m(W0611)[23m Unused import bisect
• memsight-master\memory\lib\unpaged_memory.py:3,0 - [3m(W0611)[23m Unused import utils
• memsight-master\memory\naive_fully_symbolic_memory.py:39,15 - [3m(E0001)[23m invalid syntax (<unknown>, line 39)
• memsight-master\memory\range_fully_symbolic_memory.py:62,11 - [3m(E0001)[23m invalid syntax (<unknown>, line 62)
• memsight-master\memory\simple_fully_symbolic_memory.py:375,19 - [3m(E0001)[23m invalid syntax (<unknown>, line 375)
• memsight-master\run.py:27,0 - [3m(C0304)[23m Final newline missing
• memsight-master\run.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\run.py:4,0 - [3m(E0401)[23m Unable to import 'executor'
• memsight-master\run.py:5,0 - [3m(E0401)[23m Unable to import 'memory'
• memsight-master\run.py:6,0 - [3m(E0401)[23m Unable to import 'memory'
• memsight-master\run.py:7,0 - [3m(E0401)[23m Unable to import 'utils'
• memsight-master\run.py:2,0 - [3m(W0611)[23m Unused import logging
• memsight-master\tests\angr-examples\CADET_00001\solve.py:101,11 - [3m(E0001)[23m invalid syntax (<unknown>, line 101)
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x00a\solve.py:40,8 - [3m(E0001)[23m invalid syntax
  (<unknown>, line 40)
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x01\solve.py:42,8 - [3m(E0001)[23m invalid syntax
  (<unknown>, line 42)
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x02\solve.py:42,8 - [3m(E0001)[23m invalid syntax
  (<unknown>, line 42)
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x03\solve.py:41,8 - [3m(E0001)[23m invalid syntax
  (<unknown>, line 41)
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x04\solve.py:60,8 - [3m(E0001)[23m invalid syntax
  (<unknown>, line 60)
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x05\solve.py:62,8 - [3m(E0001)[23m invalid syntax
  (<unknown>, line 62)
• memsight-master\tests\angr-examples\ais3_crackme\solve.py:54,11 - [3m(E0001)[23m invalid syntax (<unknown>, line 54)
• memsight-master\tests\angr-examples\asisctffinals2015_license\solve.py:87,11 - [3m(E0001)[23m invalid syntax (<unknown>,
  line 87)
• memsight-master\tests\angr-examples\cmu_binary_bomb\solve.py:290,11 - [3m(E0001)[23m invalid syntax (<unknown>, line 290)
• memsight-master\tests\angr-examples\codegate_2017-angrybird\solve.py:54,8 - [3m(E0001)[23m invalid syntax (<unknown>, line
  54)
• memsight-master\tests\angr-examples\defcamp_r100\solve.py:31,11 - [3m(E0001)[23m invalid syntax (<unknown>, line 31)
• memsight-master\tests\artificial\test_memory.py:14,15 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean
  print("Mismatch:")? (<unknown>, line 14)
• memsight-master\tests\binary\CROMU_00009.py:3,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:6,12 - [3m(C0303)[23m Trailing whitespace
• memsight-master\tests\binary\CROMU_00009.py:6,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:9,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:13,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:15,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:17,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:18,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:19,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:20,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:21,0 - [3m(C0303)[23m Trailing whitespace
• memsight-master\tests\binary\CROMU_00009.py:22,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:23,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:25,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:27,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:29,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:30,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:32,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:34,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:35,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:36,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:37,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:41,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:42,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:44,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:61,0 - [3m(C0304)[23m Final newline missing
• memsight-master\tests\binary\CROMU_00009.py:61,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\tests\binary\CROMU_00009.py:1,0 - [3m(C0103)[23m Module name "CROMU_00009" doesn't conform to snake_case
  naming style
• memsight-master\tests\binary\CROMU_00009.py:2,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\CROMU_00009.py:5,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\CROMU_00009.py:8,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\CROMU_00009.py:11,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\CROMU_00009.py:13,1 - [3m(C0415)[23m Import outside toplevel (claripy)
• memsight-master\tests\binary\CROMU_00009.py:13,1 - [3m(E0401)[23m Unable to import 'claripy'
• memsight-master\tests\binary\CROMU_00009.py:39,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\CROMU_00009.py:39,26 - [3m(C0103)[23m Argument name "pg" doesn't conform to snake_case naming
  style
• memsight-master\tests\binary\CROMU_00009.py:41,1 - [3m(C0415)[23m Import outside toplevel (pdb)
• memsight-master\tests\binary\CROMU_00009.py:42,1 - [3m(W1515)[23m Leaving functions creating breakpoints in production code
  is not recommended
• memsight-master\tests\binary\CROMU_00009.py:44,1 - [3m(W0105)[23m String statement has no effect
• memsight-master\tests\binary\CROMU_00009.py:61,1 - [3m(W0107)[23m Unnecessary pass statement
• memsight-master\tests\binary\CROMU_00009.py:39,11 - [3m(W0613)[23m Unused argument 'state'
• memsight-master\tests\binary\CROMU_00009.py:39,18 - [3m(W0613)[23m Unused argument 'params'
• memsight-master\tests\binary\CROMU_00009.py:39,26 - [3m(W0613)[23m Unused argument 'pg'
• memsight-master\tests\binary\CROMU_00009_a.py:3,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:6,23 - [3m(C0303)[23m Trailing whitespace
• memsight-master\tests\binary\CROMU_00009_a.py:6,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:7,0 - [3m(C0303)[23m Trailing whitespace
• memsight-master\tests\binary\CROMU_00009_a.py:9,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:13,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:16,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:17,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:18,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• memsight-master\tests\binary\CROMU_00009_a.py:19,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• memsight-master\tests\binary\CROMU_00009_a.py:20,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:21,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:22,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:23,0 - [3m(C0303)[23m Trailing whitespace
• memsight-master\tests\binary\CROMU_00009_a.py:24,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:26,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:30,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:31,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:33,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:50,0 - [3m(C0304)[23m Final newline missing
• memsight-master\tests\binary\CROMU_00009_a.py:50,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\CROMU_00009_a.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\tests\binary\CROMU_00009_a.py:1,0 - [3m(C0103)[23m Module name "CROMU_00009_a" doesn't conform to snake_case
  naming style
• memsight-master\tests\binary\CROMU_00009_a.py:2,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\CROMU_00009_a.py:5,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\CROMU_00009_a.py:8,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\CROMU_00009_a.py:11,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\CROMU_00009_a.py:13,1 - [3m(C0415)[23m Import outside toplevel (claripy)
• memsight-master\tests\binary\CROMU_00009_a.py:13,1 - [3m(E0401)[23m Unable to import 'claripy'
• memsight-master\tests\binary\CROMU_00009_a.py:17,1 - [3m(C0200)[23m Consider using enumerate instead of iterating with range
  and len
• memsight-master\tests\binary\CROMU_00009_a.py:18,2 - [3m(C0103)[23m Variable name "c" doesn't conform to snake_case naming
  style
• memsight-master\tests\binary\CROMU_00009_a.py:13,1 - [3m(W0611)[23m Unused import claripy
• memsight-master\tests\binary\CROMU_00009_a.py:28,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\CROMU_00009_a.py:28,26 - [3m(C0103)[23m Argument name "pg" doesn't conform to snake_case naming
  style
• memsight-master\tests\binary\CROMU_00009_a.py:30,1 - [3m(C0415)[23m Import outside toplevel (pdb)
• memsight-master\tests\binary\CROMU_00009_a.py:31,1 - [3m(W1515)[23m Leaving functions creating breakpoints in production
  code is not recommended
• memsight-master\tests\binary\CROMU_00009_a.py:33,1 - [3m(W0105)[23m String statement has no effect
• memsight-master\tests\binary\CROMU_00009_a.py:50,1 - [3m(W0107)[23m Unnecessary pass statement
• memsight-master\tests\binary\CROMU_00009_a.py:28,11 - [3m(W0613)[23m Unused argument 'state'
• memsight-master\tests\binary\CROMU_00009_a.py:28,18 - [3m(W0613)[23m Unused argument 'params'
• memsight-master\tests\binary\CROMU_00009_a.py:28,26 - [3m(W0613)[23m Unused argument 'pg'
• memsight-master\tests\binary\FAIL_00001.py:3,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\FAIL_00001.py:6,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\FAIL_00001.py:9,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\FAIL_00001.py:12,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\FAIL_00001.py:13,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\FAIL_00001.py:16,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\FAIL_00001.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\tests\binary\FAIL_00001.py:1,0 - [3m(C0103)[23m Module name "FAIL_00001" doesn't conform to snake_case
  naming style
• memsight-master\tests\binary\FAIL_00001.py:2,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\FAIL_00001.py:5,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\FAIL_00001.py:8,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\FAIL_00001.py:11,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\FAIL_00001.py:11,13 - [3m(W0613)[23m Unused argument 'state'
• memsight-master\tests\binary\FAIL_00001.py:15,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\FAIL_00001.py:15,11 - [3m(W0613)[23m Unused argument 'state'
• memsight-master\tests\binary\FAIL_00001.py:15,18 - [3m(W0613)[23m Unused argument 'params'
• memsight-master\tests\binary\array_O0.py:35,15 - [3m(E0001)[23m invalid syntax (<unknown>, line 35)
• memsight-master\tests\binary\basic-example.py:25,23 - [3m(E0001)[23m invalid syntax (<unknown>, line 25)
• memsight-master\tests\binary\bomb.py:40,9 - [3m(E0001)[23m invalid syntax (<unknown>, line 40)
• memsight-master\tests\binary\bomb4.py:28,11 - [3m(E0001)[23m invalid syntax (<unknown>, line 28)
• memsight-master\tests\binary\fail.py:29,9 - [3m(E0001)[23m invalid syntax (<unknown>, line 29)
• memsight-master\tests\binary\fail2.py:20,9 - [3m(E0001)[23m invalid syntax (<unknown>, line 20)
• memsight-master\tests\binary\fail3.py:29,9 - [3m(E0001)[23m invalid syntax (<unknown>, line 29)
• memsight-master\tests\binary\fail4.py:3,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:6,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:9,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:12,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:13,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:14,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:15,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:18,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:19,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:20,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:21,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• memsight-master\tests\binary\fail4.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\tests\binary\fail4.py:2,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\fail4.py:5,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\fail4.py:8,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\fail4.py:11,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\fail4.py:13,1 - [3m(C0415)[23m Import outside toplevel (claripy)
• memsight-master\tests\binary\fail4.py:13,1 - [3m(E0401)[23m Unable to import 'claripy'
• memsight-master\tests\binary\fail4.py:17,0 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\binary\fail4.py:17,26 - [3m(C0103)[23m Argument name "pg" doesn't conform to snake_case naming style
• memsight-master\tests\binary\fail4.py:18,1 - [3m(C0103)[23m Variable name "s" doesn't conform to snake_case naming style
• memsight-master\tests\binary\fail4.py:17,35 - [3m(W0613)[23m Unused argument 'verbose'
• memsight-master\tests\binary\fail5.py:34,9 - [3m(E0001)[23m invalid syntax (<unknown>, line 34)
• memsight-master\tests\binary\merge.py:38,15 - [3m(E0001)[23m invalid syntax (<unknown>, line 38)
• memsight-master\tests\binary\symbolic_access.py:16,120 - [3m(E0001)[23m inconsistent use of tabs and spaces in indentation
  (<unknown>, line 16)
• memsight-master\tests\pitree\bcolors.py:9,0 - [3m(C0304)[23m Final newline missing
• memsight-master\tests\pitree\bcolors.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\tests\pitree\bcolors.py:1,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\tests\pitree\bcolors.py:1,0 - [3m(C0103)[23m Class name "bcolors" doesn't conform to PascalCase naming style
• memsight-master\tests\pitree\bcolors.py:1,0 - [3m(R0903)[23m Too few public methods (0/2)
• memsight-master\tests\pitree\test_intervaltree.py:100,11 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you
  mean print("- Test 1")? (<unknown>, line 100)
• memsight-master\tests\pitree\test_pitree.py:84,11 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean
  print("- Test 1")? (<unknown>, line 84)
• memsight-master\tests\run-all-tests.py:9,0 - [3m(C0301)[23m Line too long (111/100)
• memsight-master\tests\run-all-tests.py:62,0 - [3m(C0301)[23m Line too long (108/100)
• memsight-master\tests\run-all-tests.py:74,0 - [3m(C0304)[23m Final newline missing
• memsight-master\tests\run-all-tests.py:1,0 - [3m(C0114)[23m Missing module docstring
• memsight-master\tests\run-all-tests.py:1,0 - [3m(C0103)[23m Module name "run-all-tests" doesn't conform to snake_case naming
  style
• memsight-master\tests\run-all-tests.py:4,0 - [3m(E0401)[23m Unable to import 'angr'
• memsight-master\tests\run-all-tests.py:8,0 - [3m(E0401)[23m Unable to import 'tests.artificial.test_memory'
• memsight-master\tests\run-all-tests.py:8,0 - [3m(C0413)[23m Import "from tests.artificial.test_memory import
  test_symbolic_access, test_store_with_symbolic_size, test_store_with_symbolic_addr_and_symbolic_size,
  test_concrete_merge, test_concrete_merge_with_condition, test_symbolic_merge" should be placed at the top of the
  module
• memsight-master\tests\run-all-tests.py:8,0 - [3m(E0611)[23m No name 'artificial' in module 'tests'
• memsight-master\tests\run-all-tests.py:12,0 - [3m(E0401)[23m Unable to import 'executor'
• memsight-master\tests\run-all-tests.py:12,0 - [3m(C0413)[23m Import "from executor import executor" should be placed at the
  top of the module
• memsight-master\tests\run-all-tests.py:13,0 - [3m(E0401)[23m Unable to import 'memory'
• memsight-master\tests\run-all-tests.py:13,0 - [3m(C0413)[23m Import "from memory import factory" should be placed at the top
  of the module
• memsight-master\tests\run-all-tests.py:15,0 - [3m(C0115)[23m Missing class docstring
• memsight-master\tests\run-all-tests.py:17,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:18,8 - [3m(C0103)[23m Variable name "p" doesn't conform to snake_case naming style
• memsight-master\tests\run-all-tests.py:24,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:27,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:27,4 - [3m(C0103)[23m Method name "test_array_O0" doesn't conform to snake_case
  naming style
• memsight-master\tests\run-all-tests.py:30,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:33,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:36,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:40,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:43,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:46,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:49,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:52,4 - [3m(C0116)[23m Missing function or method docstring
• memsight-master\tests\run-all-tests.py:60,12 - [3m(W0107)[23m Unnecessary pass statement
• memsight-master\tests\run-all-tests.py:55,20 - [3m(W0612)[23m Unused variable 'reg_memory'
• memsight-master\tests\run_all_tests.py:8,7 - [3m(E0001)[23m invalid syntax (<unknown>, line 8)
• memsight-master\utils.py:26,15 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean print("python " +
  sys.argv[0] + " [0|1] <binary>")? (<unknown>, line 26)
• memsight-master\utils.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==memsight-master.explore:[20:29]
  ┃ ==memsight-master.run:[14:23]
  ┃     explorer = executor.Executor(file)
  ┃     angr_project = explorer.project
  ┃
  ┃
  ┃     if t == 0:
  ┃         mem_memory, reg_memory = factory.get_angr_symbolic_memory(angr_project)
  ┃     elif t == 1:
  ┃         mem_memory, reg_memory = factory.get_range_fully_symbolic_memory(angr_project)
  ┃         mem_memory.verbose = False

• memsight-master\utils.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==memsight-master.memory.lib.paged_memory:[150:157]
  ┃ ==memsight-master.memory.lib.unpaged_memory:[49:56]
  ┃                                 if type(v) in (list,):
  ┃                                     for vv in v:
  ┃                                         assert type(vv) not in (list,)
  ┃                                         values.append(vv)
  ┃                                 else:
  ┃                                     values.append(v)


1.1.3.3 Details — Mypy reports no issues with this project — ✅

Congratulations, Mypy is happy with your project!

1.1.3.4 Details — Black reports no issues with this project — ❌

Black reported [1m18[0m files in your project that it would reformat:
• memsight-master\docs\env-setup\veritesting.py
• memsight-master\memory\lib\pitree\interval.py
• memsight-master\explore.py
• memsight-master\memory\factory.py
• memsight-master\memory\lib\pitree\node.py
• memsight-master\memory\lib\pitree\untree.py
• memsight-master\run.py
• memsight-master\memory\angr_symbolic_memory.py
• memsight-master\memory\lib\unpaged_memory.py
• memsight-master\memory\lib\range_map.py
• memsight-master\tests\binary\CROMU_00009_a.py
• memsight-master\tests\binary\fail4.py
• memsight-master\tests\binary\FAIL_00001.py
• memsight-master\tests\binary\CROMU_00009.py
• memsight-master\tests\pitree\bcolors.py
• memsight-master\memory\lib\paged_memory.py
• memsight-master\tests\run-all-tests.py
• memsight-master\memory\lib\sorted_collection.py

Black can fix these issues automatically when you run black . in your project.

1.1.3.5 Details — isort reports no issues with this project — ❌

isort reported [1m41[0m files in your project that it would fix:
• memsight-master\explore.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\run.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\utils.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\docs\env-setup\veritesting.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\executor\executor.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\executor\executor_config.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\angr_symbolic_memory.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\factory.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\naive_fully_symbolic_memory.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\range_fully_symbolic_memory.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\simple_fully_symbolic_memory.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\lib\paged_memory.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\lib\range_tree.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\lib\sorted_collection.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\lib\unpaged_memory.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\lib\pitree\intervaltree.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\lib\pitree\pitree.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\lib\pitree\profiler.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\lib\pitree\runner.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\lib\pitree\test.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\memory\lib\pitree\tester.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\run-all-tests.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\run_all_tests.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\angr-examples\ais3_crackme\solve.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\angr-examples\asisctffinals2015_license\solve.py - Imports are incorrectly sorted and/or
  formatted.
• memsight-master\tests\angr-examples\CADET_00001\solve.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\angr-examples\cmu_binary_bomb\solve.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\angr-examples\codegate_2017-angrybird\solve.py - Imports are incorrectly sorted and/or
  formatted.
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x00a\solve.py - Imports are incorrectly sorted
  and/or formatted.
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x01\solve.py - Imports are incorrectly sorted
  and/or formatted.
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x02\solve.py - Imports are incorrectly sorted
  and/or formatted.
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x03\solve.py - Imports are incorrectly sorted
  and/or formatted.
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x04\solve.py - Imports are incorrectly sorted
  and/or formatted.
• memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x05\solve.py - Imports are incorrectly sorted
  and/or formatted.
• memsight-master\tests\angr-examples\defcamp_r100\solve.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\artificial\test_memory.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\binary\bomb4.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\binary\merge.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\binary\symbolic_access.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\pitree\test_intervaltree.py - Imports are incorrectly sorted and/or formatted.
• memsight-master\tests\pitree\test_pitree.py - Imports are incorrectly sorted and/or formatted.

isort can fix these issues automatically when you run isort . in your project.

1.1.3.6 Details — isort is properly configured — ❌

isort is not properly configured. In order to be compatible with [Black](https://github.com/psf/black), which mllint
also recommends using, you should configure isort to use the black profile. Furthermore, we recommend centralising your
configuration in your pyproject.toml

Thus, ensure that your pyproject.toml contains at least the following section:

┃ [tool.isort]
┃ profile = "black"

1.1.4 Testing (testing) — [1m0.0[0m%

┌──────┬─────┬──────┬──────────────────────────────────────────┬────────────────────┐
│Passed│Score│Weight│Rule                                      │Slug                │
╞══════╪═════╪══════╪══════════════════════════════════════════╪════════════════════╡
│  ❌  │ 0.0%│     1│Project has automated tests               │testing/has-tests   │
├──────┼─────┼──────┼──────────────────────────────────────────┼────────────────────┤
│  ❌  │ 0.0%│     1│Project passes all of its automated tests │testing/pass        │
├──────┼─────┼──────┼──────────────────────────────────────────┼────────────────────┤
│  ❌  │ 0.0%│     1│Project provides a test coverage report   │testing/coverage    │
├──────┼─────┼──────┼──────────────────────────────────────────┼────────────────────┤
│  ❌  │ 0.0%│     1│Tests should be placed in the tests folder│testing/tests-folder│
├──────┼─────┼──────┼──────────────────────────────────────────┼────────────────────┤
│      │[3mTotal[23m│      │                                          │                    │
├──────┼─────┼──────┼──────────────────────────────────────────┼────────────────────┤
│  ❌  │ [1m0.0[0m%│      │Testing                                   │testing             │
└──────┴─────┴──────┴──────────────────────────────────────────┴────────────────────┘
1.1.4.1 Details — Project has automated tests — ❌

There are [1m0[0m test files in your project, but mllint was expecting at least [1m1[0m.

1.1.4.2 Details — Project passes all of its automated tests — ❌

No test report was provided.

Please update the testing.report setting in your project's mllint configuration to specify the path to your project's
test report.

When using pytest to run your project's tests, use the --junitxml=<filename> option to generate such a test report,
e.g.:

┃ pytest --junitxml=tests-report.xml

1.1.4.3 Details — Project provides a test coverage report — ❌

No test coverage report was provided.

Please update the testing.coverage.report setting in your project's mllint configuration to specify the path to your
project's test coverage report.

Generating a test coverage report with pytest can be done by adding and installing pytest-cov as a development
dependency of your project. Then use the following command to run your tests and generate both a test report as well as
a coverage report:

┃ pytest --junitxml=tests-report.xml --cov=path_to_package_under_test --cov-report=xml

1.1.4.4 Details — Tests should be placed in the tests folder — ❌

Tip for when you start implementing tests: create a folder called tests at the root of your project and place all your
Python test files in there, as per common convention.

1.1.5 Continuous Integration (ci) — [1m0.0[0m%

┌──────┬─────┬──────┬────────────────────────────────────────┬──────┐
│Passed│Score│Weight│Rule                                    │Slug  │
╞══════╪═════╪══════╪════════════════════════════════════════╪══════╡
│  ❌  │ 0.0%│     1│Project uses Continuous Integration (CI)│ci/use│
├──────┼─────┼──────┼────────────────────────────────────────┼──────┤
│      │[3mTotal[23m│      │                                        │      │
├──────┼─────┼──────┼────────────────────────────────────────┼──────┤
│  ❌  │ [1m0.0[0m%│      │Continuous Integration                  │ci    │
└──────┴─────┴──────┴────────────────────────────────────────┴──────┘
1.2 Errors

1 error(s) occurred while analysing your project:
• ❌ [1mCode Quality[0m - 1 error occurred:
  • Bandit failed to run: failed to parse Bandit's YAML output: yaml: unmarshal errors: line 2: cannot unmarshal !!map
    into string line 4: cannot unmarshal !!map into string line 6: cannot unmarshal !!map into string line 8: cannot
    unmarshal !!map into string line 10: cannot unmarshal !!map into string line 12: cannot unmarshal !!map into string
    line 14: cannot unmarshal !!map into string line 16: cannot unmarshal !!map into string line 18: cannot unmarshal
    !!map into string line 20: cannot unmarshal !!map into string line 22: cannot unmarshal !!map into string line 24:
    cannot unmarshal !!map into string line 26: cannot unmarshal !!map into string line 28: cannot unmarshal !!map into
    string line 30: cannot unmarshal !!map into string line 32: cannot unmarshal !!map into string line 34: cannot
    unmarshal !!map into string line 36: cannot unmarshal !!map into string line 38: cannot unmarshal !!map into string
    line 40: cannot unmarshal !!map into string line 42: cannot unmarshal !!map into string line 44: cannot unmarshal
    !!map into string line 46: cannot unmarshal !!map into string line 48: cannot unmarshal !!map into string line 50:
    cannot unmarshal !!map into string line 52: cannot unmarshal !!map into string line 54: cannot unmarshal !!map into
    string line 56: cannot unmarshal !!map into string line 58: cannot unmarshal !!map into string line 60: cannot
    unmarshal !!map into string line 62: cannot unmarshal !!map into string line 64: cannot unmarshal !!map into string
    line 66: cannot unmarshal !!map into string line 68: cannot unmarshal !!map into string line 70: cannot unmarshal
    !!map into string line 72: cannot unmarshal !!map into string line 74: cannot unmarshal !!map into string line 76:
    cannot unmarshal !!map into string line 78: cannot unmarshal !!map into string line 80: cannot unmarshal !!map into
    string, output:

┃ errors:
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\executor\executor.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\executor\executor_config.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\intervaltree.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\parser.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\pitree.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\profiler.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\runner.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\test.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\tester.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\range_tree.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\naive_fully_symbolic_memory.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\range_fully_symbolic_memory.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\simple_fully_symbolic_memory.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CADET_00001\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\cr
┃ ackme0x00a\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\cr
┃ ackme0x01\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\cr
┃ ackme0x02\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\cr
┃ ackme0x03\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\cr
┃ ackme0x04\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\cr
┃ ackme0x05\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\ais3_crackme\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename:
┃ F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\asisctffinals2015_license\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\cmu_binary_bomb\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename:
┃ F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\codegate_2017-angrybird\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\defcamp_r100\solve.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\artificial\test_memory.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\array_O0.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\basic-example.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\bomb.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\bomb4.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail2.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail3.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail5.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\merge.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\symbolic_access.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\pitree\test_intervaltree.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\pitree\test_pitree.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\run_all_tests.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\utils.py
┃   reason: syntax error while parsing AST from file
┃ generated_at: '2022-08-20T07:48:27Z'
┃ metrics:
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\__init__.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 0
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\docs\env-setup\veritesting.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 19
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\executor\__init__.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 0
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\executor\executor.py:
┃     loc: 175
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\executor\executor_config.py:
┃     loc: 24
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\explore.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 19
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\__init__.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 0
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\angr_symbolic_memory.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 64
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\factory.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 11
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\__init__.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 0
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\paged_memory.py:
┃     CONFIDENCE.HIGH: 2
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 2
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 144
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\__init__.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 0
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\interval.py:
┃     CONFIDENCE.HIGH: 1
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 1
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 22
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\intervaltree.py:
┃     loc: 101
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\node.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 127
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\parser.py:
┃     loc: 44
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\pitree.py:
┃     loc: 225
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\profiler.py:
┃     loc: 32
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\runner.py:
┃     loc: 45
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\test.py:
┃     loc: 49
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\tester.py:
┃     loc: 72
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\untree.py:
┃     CONFIDENCE.HIGH: 1
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 1
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 61
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\range_map.py:
┃     CONFIDENCE.HIGH: 2
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 2
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 116
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\range_tree.py:
┃     loc: 142
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py:
┃     CONFIDENCE.HIGH: 37
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 37
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 259
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\unpaged_memory.py:
┃     CONFIDENCE.HIGH: 2
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 2
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 43
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\naive_fully_symbolic_memory.py:
┃     loc: 729
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\range_fully_symbolic_memory.py:
┃     loc: 1193
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\simple_fully_symbolic_memory.py:
┃     loc: 287
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\run.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 18
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\__init__.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 0
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CADET_00001\solve.py:
┃     loc: 55
┃     nosec: 0
┃     skipped_tests: 0
┃   ? F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x0
┃ 0a\solve.py
┃   : loc: 23
┃     nosec: 0
┃     skipped_tests: 0
┃   ? F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x0
┃ 1\solve.py
┃   : loc: 62
┃     nosec: 0
┃     skipped_tests: 0
┃   ? F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x0
┃ 2\solve.py
┃   : loc: 73
┃     nosec: 0
┃     skipped_tests: 0
┃   ? F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x0
┃ 3\solve.py
┃   : loc: 88
┃     nosec: 0
┃     skipped_tests: 0
┃   ? F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x0
┃ 4\solve.py
┃   : loc: 107
┃     nosec: 0
┃     skipped_tests: 0
┃   ? F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\CSCI-4968-MBE\challenges\crackme0x0
┃ 5\solve.py
┃   : loc: 113
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\ais3_crackme\solve.py:
┃     loc: 33
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\asisctffinals2015_license\solve.py:
┃     loc: 59
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\cmu_binary_bomb\solve.py:
┃     loc: 215
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\codegate_2017-angrybird\solve.py:
┃     loc: 31
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\angr-examples\defcamp_r100\solve.py:
┃     loc: 22
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\artificial\__init__.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 0
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\artificial\test_memory.py:
┃     loc: 192
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\CROMU_00009.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 43
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\CROMU_00009_a.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 36
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\FAIL_00001.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 11
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\array_O0.py:
┃     loc: 27
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\basic-example.py:
┃     loc: 27
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\bomb.py:
┃     loc: 42
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\bomb4.py:
┃     loc: 19
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail.py:
┃     loc: 24
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail2.py:
┃     loc: 15
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail3.py:
┃     loc: 24
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail4.py:
┃     CONFIDENCE.HIGH: 3
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 3
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 16
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail5.py:
┃     loc: 27
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\merge.py:
┃     loc: 29
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\symbolic_access.py:
┃     loc: 18
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\pitree\bcolors.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 9
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\pitree\test_intervaltree.py:
┃     loc: 180
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\pitree\test_pitree.py:
┃     loc: 132
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\run-all-tests.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 51
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\run_all_tests.py:
┃     loc: 15
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/memsight-master\memsight-master\utils.py:
┃     loc: 95
┃     nosec: 0
┃     skipped_tests: 0
┃   _totals:
┃     CONFIDENCE.HIGH: 48
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 48
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 5934
┃     nosec: 0
┃     skipped_tests: 0
┃ results:
┃ - code: 152                                     for vv in v:\n153                                         assert
┃     type(vv) not in (list,)\n154                                         values.append(vv)\n
┃   col_offset: 40
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\paged_memory.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 153
┃   line_range:
┃   - 153
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 187                             for vv in v:\n188                                 assert
┃     type(vv) not in (list,)\n189                                 values.append(vv)\n
┃   col_offset: 32
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\paged_memory.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 188
┃   line_range:
┃   - 188
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 2     def __init__(self, begin, end, data=None):\n3         assert begin <=
┃     end\n4         self.begin  = begin\n
┃   col_offset: 8
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\interval.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 3
┃   line_range:
┃   - 3
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 20     def set_log(cls, log):\n21         assert Untree._log is None\n22         Untree._log
┃     = log\n
┃   col_offset: 8
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\pitree\untree.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 21
┃   line_range:
┃   - 21
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: '113         # old must be returned by query()\n114         assert old[0]
┃     == new[0] and old[1] == new[1]\n115 \n116         pos = self._find_by_id(self._large_ranges,
┃     id(old))\n'
┃   col_offset: 8
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\range_map.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 114
┃   line_range:
┃   - 114
┃   - 115
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: '173 \n174         assert False # ToDo\n175 \n'
┃   col_offset: 8
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\range_map.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 174
┃   line_range:
┃   - 174
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 251         for n in range(6):\n252             s = [choice(pool) for i in
┃     range(n)]\n253             sc = SortedCollection(s)\n
┃   col_offset: 17
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 330
┃     link: https://cwe.mitre.org/data/definitions/330.html
┃   issue_severity: LOW
┃   issue_text: Standard pseudo-random generators are not suitable for security/cryptographic
┃     purposes.
┃   line_number: 252
┃   line_range:
┃   - 252
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_calls.html#b311-random
┃   test_id: B311
┃   test_name: blacklist
┃ - code: 255             for probe in pool:\n256                 assert repr(ve2no(sc.index,
┃     probe)) == repr(slow_index(s, probe))\n257                 assert repr(ve2no(sc.find,
┃     probe)) == repr(slow_find(s, probe))\n
┃   col_offset: 16
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 256
┃   line_range:
┃   - 256
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 256                 assert repr(ve2no(sc.index, probe)) == repr(slow_index(s,
┃     probe))\n257                 assert repr(ve2no(sc.find, probe)) == repr(slow_find(s,
┃     probe))\n258                 assert repr(ve2no(sc.find_le, probe)) == repr(slow_find_le(s,
┃     probe))\n
┃   col_offset: 16
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 257
┃   line_range:
┃   - 257
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 257                 assert repr(ve2no(sc.find, probe)) == repr(slow_find(s,
┃     probe))\n258                 assert repr(ve2no(sc.find_le, probe)) == repr(slow_find_le(s,
┃     probe))\n259                 assert repr(ve2no(sc.find_lt, probe)) == repr(slow_find_lt(s,
┃     probe))\n
┃   col_offset: 16
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 258
┃   line_range:
┃   - 258
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 258                 assert repr(ve2no(sc.find_le, probe)) == repr(slow_find_le(s,
┃     probe))\n259                 assert repr(ve2no(sc.find_lt, probe)) == repr(slow_find_lt(s,
┃     probe))\n260                 assert repr(ve2no(sc.find_ge, probe)) == repr(slow_find_ge(s,
┃     probe))\n
┃   col_offset: 16
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 259
┃   line_range:
┃   - 259
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 259                 assert repr(ve2no(sc.find_lt, probe)) == repr(slow_find_lt(s,
┃     probe))\n260                 assert repr(ve2no(sc.find_ge, probe)) == repr(slow_find_ge(s,
┃     probe))\n261                 assert repr(ve2no(sc.find_gt, probe)) == repr(slow_find_gt(s,
┃     probe))\n
┃   col_offset: 16
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 260
┃   line_range:
┃   - 260
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 260                 assert repr(ve2no(sc.find_ge, probe)) == repr(slow_find_ge(s,
┃     probe))\n261                 assert repr(ve2no(sc.find_gt, probe)) == repr(slow_find_gt(s,
┃     probe))\n262             for i, item in enumerate(s):\n
┃   col_offset: 16
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 261
┃   line_range:
┃   - 261
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: '262             for i, item in enumerate(s):\n263                 assert
┃     repr(item) == repr(sc[i])        # test __getitem__\n264                 assert
┃     item in sc                       # test __contains__ and __iter__\n'
┃   col_offset: 16
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 263
┃   line_range:
┃   - 263
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: '263                 assert repr(item) == repr(sc[i])        # test __getitem__\n264                 assert
┃     item in sc                       # test __contains__ and __iter__\n265                 assert
┃     s.count(item) == sc.count(item)  # test count()\n'
┃   col_offset: 16
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 264
┃   line_range:
┃   - 264
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: '264                 assert item in sc                       # test __contains__
┃     and __iter__\n265                 assert s.count(item) == sc.count(item)  # test
┃     count()\n266             assert len(sc) == n                         # test __len__\n'
┃   col_offset: 16
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 265
┃   line_range:
┃   - 265
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: '265                 assert s.count(item) == sc.count(item)  # test count()\n266             assert
┃     len(sc) == n                         # test __len__\n267             assert list(map(repr,
┃     reversed(sc))) == list(map(repr, reversed(s)))    # test __reversed__\n'
┃   col_offset: 12
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 266
┃   line_range:
┃   - 266
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: '266             assert len(sc) == n                         # test __len__\n267             assert
┃     list(map(repr, reversed(sc))) == list(map(repr, reversed(s)))    # test __reversed__\n268             assert
┃     list(sc.copy()) == list(sc)          # test copy()\n'
┃   col_offset: 12
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 267
┃   line_range:
┃   - 267
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: '267             assert list(map(repr, reversed(sc))) == list(map(repr, reversed(s)))    #
┃     test __reversed__\n268             assert list(sc.copy()) == list(sc)          #
┃     test copy()\n269             sc.clear()                                  # test
┃     clear()\n'
┃   col_offset: 12
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 268
┃   line_range:
┃   - 268
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: '269             sc.clear()                                  # test clear()\n270             assert
┃     len(sc) == 0\n271 \n'
┃   col_offset: 12
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 270
┃   line_range:
┃   - 270
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 272     sd = SortedCollection('The quick Brown Fox jumped'.split(), key=str.lower)\n273     assert
┃     sd._keys == ['brown', 'fox', 'jumped', 'quick', 'the']\n274     assert sd._items
┃     == ['Brown', 'Fox', 'jumped', 'quick', 'The']\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 273
┃   line_range:
┃   - 273
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 273     assert sd._keys == ['brown', 'fox', 'jumped', 'quick', 'the']\n274     assert
┃     sd._items == ['Brown', 'Fox', 'jumped', 'quick', 'The']\n275     assert sd._key
┃     == str.lower\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 274
┃   line_range:
┃   - 274
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 274     assert sd._items == ['Brown', 'Fox', 'jumped', 'quick', 'The']\n275     assert
┃     sd._key == str.lower\n276     assert repr(sd) == "SortedCollection(['Brown', 'Fox',
┃     'jumped', 'quick', 'The'], key=lower)"\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 275
┃   line_range:
┃   - 275
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 275     assert sd._key == str.lower\n276     assert repr(sd) == "SortedCollection(['Brown',
┃     'Fox', 'jumped', 'quick', 'The'], key=lower)"\n277     sd.key = str.upper\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 276
┃   line_range:
┃   - 276
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 277     sd.key = str.upper\n278     assert sd._key == str.upper\n279     assert
┃     len(sd) == 5\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 278
┃   line_range:
┃   - 278
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 278     assert sd._key == str.upper\n279     assert len(sd) == 5\n280     assert
┃     list(reversed(sd)) == ['The', 'quick', 'jumped', 'Fox', 'Brown']\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 279
┃   line_range:
┃   - 279
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 279     assert len(sd) == 5\n280     assert list(reversed(sd)) == ['The',
┃     'quick', 'jumped', 'Fox', 'Brown']\n281     for item in sd:\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 280
┃   line_range:
┃   - 280
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 281     for item in sd:\n282         assert item in sd\n283     for i, item
┃     in enumerate(sd):\n
┃   col_offset: 8
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 282
┃   line_range:
┃   - 282
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 283     for i, item in enumerate(sd):\n284         assert item == sd[i]\n285     sd.insert('jUmPeD')\n
┃   col_offset: 8
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 284
┃   line_range:
┃   - 284
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 286     sd.insert_right('QuIcK')\n287     assert sd._keys ==['BROWN', 'FOX',
┃     'JUMPED', 'JUMPED', 'QUICK', 'QUICK', 'THE']\n288     assert sd._items == ['Brown',
┃     'Fox', 'jUmPeD', 'jumped', 'quick', 'QuIcK', 'The']\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 287
┃   line_range:
┃   - 287
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 287     assert sd._keys ==['BROWN', 'FOX', 'JUMPED', 'JUMPED', 'QUICK', 'QUICK',
┃     'THE']\n288     assert sd._items == ['Brown', 'Fox', 'jUmPeD', 'jumped', 'quick',
┃     'QuIcK', 'The']\n289     assert sd.find_le('JUMPED') == 'jumped', sd.find_le('JUMPED')\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 288
┃   line_range:
┃   - 288
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 288     assert sd._items == ['Brown', 'Fox', 'jUmPeD', 'jumped', 'quick',
┃     'QuIcK', 'The']\n289     assert sd.find_le('JUMPED') == 'jumped', sd.find_le('JUMPED')\n290     assert
┃     sd.find_ge('JUMPED') == 'jUmPeD'\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 289
┃   line_range:
┃   - 289
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 289     assert sd.find_le('JUMPED') == 'jumped', sd.find_le('JUMPED')\n290     assert
┃     sd.find_ge('JUMPED') == 'jUmPeD'\n291     assert sd.find_le('GOAT') == 'Fox'\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 290
┃   line_range:
┃   - 290
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 290     assert sd.find_ge('JUMPED') == 'jUmPeD'\n291     assert sd.find_le('GOAT')
┃     == 'Fox'\n292     assert sd.find_ge('GOAT') == 'jUmPeD'\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 291
┃   line_range:
┃   - 291
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 291     assert sd.find_le('GOAT') == 'Fox'\n292     assert sd.find_ge('GOAT')
┃     == 'jUmPeD'\n293     assert sd.find('FOX') == 'Fox'\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 292
┃   line_range:
┃   - 292
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 292     assert sd.find_ge('GOAT') == 'jUmPeD'\n293     assert sd.find('FOX')
┃     == 'Fox'\n294     assert sd[3] == 'jumped'\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 293
┃   line_range:
┃   - 293
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 293     assert sd.find('FOX') == 'Fox'\n294     assert sd[3] == 'jumped'\n295     assert
┃     sd[3:5] ==['jumped', 'quick']\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 294
┃   line_range:
┃   - 294
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 294     assert sd[3] == 'jumped'\n295     assert sd[3:5] ==['jumped', 'quick']\n296     assert
┃     sd[-2] == 'QuIcK'\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 295
┃   line_range:
┃   - 295
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 295     assert sd[3:5] ==['jumped', 'quick']\n296     assert sd[-2] == 'QuIcK'\n297     assert
┃     sd[-4:-2] == ['jumped', 'quick']\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 296
┃   line_range:
┃   - 296
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 296     assert sd[-2] == 'QuIcK'\n297     assert sd[-4:-2] == ['jumped', 'quick']\n298     for
┃     i, item in enumerate(sd):\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 297
┃   line_range:
┃   - 297
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 298     for i, item in enumerate(sd):\n299         assert sd.index(item) ==
┃     i\n300     try:\n
┃   col_offset: 8
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 299
┃   line_range:
┃   - 299
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 304     else:\n305         assert 0, 'Oops, failed to notify of missing value'\n306     sd.remove('jumped')\n
┃ 
┃   col_offset: 8
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 305
┃   line_range:
┃   - 305
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 306     sd.remove('jumped')\n307     assert list(sd) == ['Brown', 'Fox', 'jUmPeD',
┃     'quick', 'QuIcK', 'The']\n308 \n309     import doctest\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\sorted_collection.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 307
┃   line_range:
┃   - 307
┃   - 308
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 43 \n44         assert result_is_flat_list\n45         values = []\n
┃   col_offset: 8
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\unpaged_memory.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 44
┃   line_range:
┃   - 44
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 51                     for vv in v:\n52                         assert type(vv)
┃     not in (list,)\n53                         values.append(vv)\n
┃   col_offset: 24
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\memory\lib\unpaged_memory.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 52
┃   line_range:
┃   - 52
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: "18 \ts = state.se.eval_upto(params['f'], 5)\\n19 \tassert len(s) == 1\\n20\
┃     \ \tassert s[0] == 0x0\\n"
┃   col_offset: 1
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail4.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 19
┃   line_range:
┃   - 19
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: "19 \tassert len(s) == 1\\n20 \tassert s[0] == 0x0\\n21 \tassert len(pg.active)\
┃     \ == 0\\n"
┃   col_offset: 1
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail4.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 20
┃   line_range:
┃   - 20
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: "20 \tassert s[0] == 0x0\\n21 \tassert len(pg.active) == 0\\n"
┃   col_offset: 1
┃   filename: F:\Python3.8env/data/2017/memsight-master\memsight-master\tests\binary\fail4.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 21
┃   line_range:
┃   - 21
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used


---
❌ rules unsuccessful:	19
Your project is still lacking in quality and could do with some improvements.
Use mllint describe with each rule's slug to learn more about what you can do to get the rules to pass and improve the quality of your ML project.

took: 6.9897943s
