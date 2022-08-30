Linting project at  F:\Python3.8env/data/2017/Reimplement-cleaned_version
No .mllint.yml or pyproject.toml found in project folder, using default configuration
---

🏃 Running - Version Control (0.00 ms)
🏃 Running - Dependency Management (0.00 ms)
🏃 Running - Continuous Integration (CI) (0.00 ms)
🏃 Running - Code Quality (0.00 ms)
⏳ Waiting - Version Control (0.00 ms)
🏃 Running - Testing (0.00 ms)
🏃 Running - Version Control - Git (0.00 ms)
🏃 Running - Version Control - DVC (0.00 ms)
✔️ Done - Dependency Management (0.00 ms)
✔️ Done - Testing (0.00 ms)
✔️ Done - Version Control - DVC (0.52 ms)
🏃 Running - Code Quality - Pylint (0.00 ms)
🏃 Running - Code Quality - Mypy (0.00 ms)
🏃 Running - Code Quality - Black (0.00 ms)
🏃 Running - Code Quality - isort (0.00 ms)
🏃 Running - Code Quality - Bandit (0.00 ms)
⏳ Waiting - Code Quality (6 ms)
✔️ Done - Version Control - Git (51 ms)
🏃 Running - Version Control (51 ms)
✔️ Done - Version Control (51 ms)
✔️ Done - Continuous Integration (CI) (222 ms)
✔️ Done - Code Quality - Mypy (1.08 s)
✔️ Done - Code Quality - isort (1.89 s)
✔️ Done - Code Quality - Black (2.62 s)
✔️ Done - Code Quality - Bandit (2.65 s)
✔️ Done - Code Quality - Pylint (9.16 s)
🏃 Running - Code Quality (9.17 s)
✔️ Done - Code Quality (9.17 s)

✔️ All done!

---

1 ML Project Report
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────

┌──────────────────────┬─────────────────────────────────────────────────────┐
│[1mProject[0m               │[1mDetails[0m                                              │
╞══════════════════════╪═════════════════════════════════════════════════════╡
│Date                  │Sat, 20 Aug 2022 15:48:40 +0800                      │
├──────────────────────┼─────────────────────────────────────────────────────┤
│Path                  │F:\Python3.8env/data/2017/Reimplement-cleaned_version│
├──────────────────────┼─────────────────────────────────────────────────────┤
│Config                │default                                              │
├──────────────────────┼─────────────────────────────────────────────────────┤
│Default               │Yes                                                  │
├──────────────────────┼─────────────────────────────────────────────────────┤
│Number of Python files│18                                                   │
├──────────────────────┼─────────────────────────────────────────────────────┤
│Lines of Python code  │1379                                                 │
└──────────────────────┴─────────────────────────────────────────────────────┘
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
1.1.3 Code Quality (code-quality) — [1m28.6[0m%

┌──────┬──────┬──────┬────────────────────────────────────────────────┬────────────────────────────────────────────────┐
│Passed│ Score│Weight│Rule                                            │Slug                                            │
╞══════╪══════╪══════╪════════════════════════════════════════════════╪════════════════════════════════════════════════╡
│  ❌  │  0.0%│     1│Project should use code quality linters         │code-quality/use-linters                        │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ✅  │100.0%│     1│All code quality linters should be installed in │code-quality/linters-installed                  │
│      │      │      │the current environment                         │                                                │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │  0.0%│     1│Pylint reports no issues with this project      │code-quality/pylint/no-issues                   │
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
│  ❌  │ [1m28.6[0m%│      │Code Quality                                    │code-quality                                    │
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

Pylint reported [1m173[0m issues with your project:
• Reimplement-cleaned_version\Figures\1\figure1.py:88,11 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean
  print(performance[:4])? (<unknown>, line 88)
• Reimplement-cleaned_version\Figures\2\figure2.py:1,0 - [3m(C0114)[23m Missing module docstring
• Reimplement-cleaned_version\Figures\2\figure2.py:3,0 - [3m(E0401)[23m Unable to import 'sklearn.tree'
• Reimplement-cleaned_version\Figures\2\figure2.py:5,0 - [3m(E0401)[23m Unable to import 'pandas'
• Reimplement-cleaned_version\Figures\2\figure2.py:11,0 - [3m(C0103)[23m Constant name "data_folder" doesn't conform to
  UPPER_CASE naming style
• Reimplement-cleaned_version\Figures\2\figure2.py:13,0 - [3m(C0116)[23m Missing function or method docstring
• Reimplement-cleaned_version\Figures\2\figure2.py:32,0 - [3m(C0116)[23m Missing function or method docstring
• Reimplement-cleaned_version\Figures\2\figure2.py:36,8 - [3m(W0621)[23m Redefining name 'mres' from outer scope (line 78)
• Reimplement-cleaned_version\Figures\2\figure2.py:37,17 - [3m(E0602)[23m Undefined variable 'xrange'
• Reimplement-cleaned_version\Figures\2\figure2.py:44,0 - [3m(C0116)[23m Missing function or method docstring
• Reimplement-cleaned_version\Figures\2\figure2.py:44,15 - [3m(W0621)[23m Redefining name 'filename' from outer scope (line
  76)
• Reimplement-cleaned_version\Figures\2\figure2.py:49,14 - [3m(R1734)[23m Consider using [] instead of list()
• Reimplement-cleaned_version\Figures\2\figure2.py:50,8 - [3m(C0103)[23m Variable name "c" doesn't conform to snake_case
  naming style
• Reimplement-cleaned_version\Figures\2\figure2.py:50,13 - [3m(E0602)[23m Undefined variable 'xrange'
• Reimplement-cleaned_version\Figures\2\figure2.py:68,0 - [3m(C0115)[23m Missing class docstring
• Reimplement-cleaned_version\Figures\2\figure2.py:68,0 - [3m(C0103)[23m Class name "solution_holder" doesn't conform to
  PascalCase naming style
• Reimplement-cleaned_version\Figures\2\figure2.py:70,8 - [3m(C0103)[23m Attribute name "id" doesn't conform to snake_case
  naming style
• Reimplement-cleaned_version\Figures\2\figure2.py:69,23 - [3m(C0103)[23m Argument name "id" doesn't conform to snake_case
  naming style
• Reimplement-cleaned_version\Figures\2\figure2.py:69,23 - [3m(W0622)[23m Redefining built-in 'id'
• Reimplement-cleaned_version\Figures\2\figure2.py:68,0 - [3m(R0903)[23m Too few public methods (0/2)
• Reimplement-cleaned_version\Figures\2\figure2.py:76,4 - [3m(C0103)[23m Constant name "filename" doesn't conform to
  UPPER_CASE naming style
• Reimplement-cleaned_version\Figures\2\figure2.py:79,13 - [3m(E0602)[23m Undefined variable 'xrange'
• Reimplement-cleaned_version\Figures\2\figure2.py:83,4 - [3m(W0404)[23m Reimport 'numpy' (imported line 2)
• Reimplement-cleaned_version\Figures\2\figure2.py:4,0 - [3m(C0411)[23m standard import "from os import listdir" should be
  placed before "import numpy as np"
• Reimplement-cleaned_version\Figures\2\figure2.py:6,0 - [3m(C0411)[23m standard import "from random import shuffle" should be
  placed before "import numpy as np"
• Reimplement-cleaned_version\Figures\2\figure2.py:83,4 - [3m(C0412)[23m Imports from package numpy are not grouped
• Reimplement-cleaned_version\Figures\3__init__.py:1,0 - [3m(C0103)[23m Module name "3" doesn't conform to snake_case naming
  style
• Reimplement-cleaned_version\Figures\3\figure4.py:34,0 - [3m(C0301)[23m Line too long (113/100)
• Reimplement-cleaned_version\Figures\3\figure4.py:35,0 - [3m(C0301)[23m Line too long (125/100)
• Reimplement-cleaned_version\Figures\3\figure4.py:36,0 - [3m(C0301)[23m Line too long (114/100)
• Reimplement-cleaned_version\Figures\3\figure4.py:47,0 - [3m(C0301)[23m Line too long (113/100)
• Reimplement-cleaned_version\Figures\3\figure4.py:48,0 - [3m(C0301)[23m Line too long (125/100)
• Reimplement-cleaned_version\Figures\3\figure4.py:49,0 - [3m(C0301)[23m Line too long (114/100)
• Reimplement-cleaned_version\Figures\3\figure4.py:56,0 - [3m(C0301)[23m Line too long (113/100)
• Reimplement-cleaned_version\Figures\3\figure4.py:57,0 - [3m(C0301)[23m Line too long (125/100)
• Reimplement-cleaned_version\Figures\3\figure4.py:58,0 - [3m(C0301)[23m Line too long (128/100)
• Reimplement-cleaned_version\Figures\3\figure4.py:1,0 - [3m(C0114)[23m Missing module docstring
• Reimplement-cleaned_version\Figures\3\figure4.py:28,0 - [3m(C0103)[23m Constant name "right" doesn't conform to UPPER_CASE
  naming style
• Reimplement-cleaned_version\Figures\3\figure4.py:29,0 - [3m(C0103)[23m Constant name "top" doesn't conform to UPPER_CASE
  naming style
• Reimplement-cleaned_version\Figures\3\figure4.py:64,0 - [3m(C0413)[23m Import "from matplotlib.lines import Line2D" should
  be placed at the top of the module
• Reimplement-cleaned_version\Figures\3\figure4_2.py:40,7 - [3m(E0001)[23m invalid syntax (<unknown>, line 40)
• Reimplement-cleaned_version\Figures\4\figure5.py:4,0 - [3m(C0301)[23m Line too long (146/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:5,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:6,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:7,0 - [3m(C0301)[23m Line too long (140/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:8,0 - [3m(C0301)[23m Line too long (145/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:9,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:10,0 - [3m(C0301)[23m Line too long (138/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:11,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:12,0 - [3m(C0301)[23m Line too long (139/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:13,0 - [3m(C0301)[23m Line too long (147/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:14,0 - [3m(C0301)[23m Line too long (148/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:15,0 - [3m(C0301)[23m Line too long (150/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:16,0 - [3m(C0301)[23m Line too long (151/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:17,0 - [3m(C0301)[23m Line too long (147/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:18,0 - [3m(C0301)[23m Line too long (150/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:19,0 - [3m(C0301)[23m Line too long (151/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:20,0 - [3m(C0301)[23m Line too long (152/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:21,0 - [3m(C0301)[23m Line too long (151/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:22,0 - [3m(C0301)[23m Line too long (150/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:23,0 - [3m(C0301)[23m Line too long (126/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:24,0 - [3m(C0301)[23m Line too long (148/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:25,0 - [3m(C0301)[23m Line too long (149/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:26,0 - [3m(C0301)[23m Line too long (149/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:48,0 - [3m(C0301)[23m Line too long (108/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:52,0 - [3m(C0301)[23m Line too long (106/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:70,0 - [3m(C0301)[23m Line too long (108/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:72,0 - [3m(C0301)[23m Line too long (118/100)
• Reimplement-cleaned_version\Figures\4\figure5.py:1,0 - [3m(C0114)[23m Missing module docstring
• Reimplement-cleaned_version\Figures\4\figure5.py:30,0 - [3m(C0413)[23m Import "import numpy as np" should be placed at the
  top of the module
• Reimplement-cleaned_version\Figures\4\figure5.py:31,0 - [3m(W0404)[23m Reimport 'matplotlib.pyplot' (imported line 1)
• Reimplement-cleaned_version\Figures\4\figure5.py:31,0 - [3m(C0413)[23m Import "import matplotlib.pyplot as plt" should be
  placed at the top of the module
• Reimplement-cleaned_version\Figures\4\figure5.py:39,0 - [3m(C0103)[23m Constant name "space" doesn't conform to UPPER_CASE
  naming style
• Reimplement-cleaned_version\Figures\4\figure5.py:41,0 - [3m(C0103)[23m Constant name "width" doesn't conform to UPPER_CASE
  naming style
• Reimplement-cleaned_version\Figures\4\figure5.py:66,43 - [3m(E0602)[23m Undefined variable 'xrange'
• Reimplement-cleaned_version\Figures\4\figure5.py:31,0 - [3m(C0412)[23m Imports from package matplotlib are not grouped
• Reimplement-cleaned_version\Figures\5\figure6.py:4,0 - [3m(C0301)[23m Line too long (146/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:5,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:6,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:7,0 - [3m(C0301)[23m Line too long (140/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:8,0 - [3m(C0301)[23m Line too long (145/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:9,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:10,0 - [3m(C0301)[23m Line too long (138/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:11,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:12,0 - [3m(C0301)[23m Line too long (139/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:13,0 - [3m(C0301)[23m Line too long (147/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:14,0 - [3m(C0301)[23m Line too long (148/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:15,0 - [3m(C0301)[23m Line too long (150/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:16,0 - [3m(C0301)[23m Line too long (151/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:17,0 - [3m(C0301)[23m Line too long (147/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:18,0 - [3m(C0301)[23m Line too long (150/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:19,0 - [3m(C0301)[23m Line too long (151/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:20,0 - [3m(C0301)[23m Line too long (152/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:21,0 - [3m(C0301)[23m Line too long (151/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:22,0 - [3m(C0301)[23m Line too long (150/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:23,0 - [3m(C0301)[23m Line too long (126/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:24,0 - [3m(C0301)[23m Line too long (148/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:25,0 - [3m(C0301)[23m Line too long (149/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:26,0 - [3m(C0301)[23m Line too long (149/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:44,0 - [3m(C0301)[23m Line too long (109/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:47,0 - [3m(C0301)[23m Line too long (107/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:68,0 - [3m(C0301)[23m Line too long (118/100)
• Reimplement-cleaned_version\Figures\5\figure6.py:1,0 - [3m(C0114)[23m Missing module docstring
• Reimplement-cleaned_version\Figures\5\figure6.py:30,0 - [3m(C0413)[23m Import "import numpy as np" should be placed at the
  top of the module
• Reimplement-cleaned_version\Figures\5\figure6.py:31,0 - [3m(W0404)[23m Reimport 'matplotlib.pyplot' (imported line 1)
• Reimplement-cleaned_version\Figures\5\figure6.py:31,0 - [3m(C0413)[23m Import "import matplotlib.pyplot as plt" should be
  placed at the top of the module
• Reimplement-cleaned_version\Figures\5\figure6.py:36,0 - [3m(C0103)[23m Constant name "space" doesn't conform to UPPER_CASE
  naming style
• Reimplement-cleaned_version\Figures\5\figure6.py:38,0 - [3m(C0103)[23m Constant name "width" doesn't conform to UPPER_CASE
  naming style
• Reimplement-cleaned_version\Figures\5\figure6.py:61,43 - [3m(E0602)[23m Undefined variable 'xrange'
• Reimplement-cleaned_version\Figures\5\figure6.py:31,0 - [3m(C0412)[23m Imports from package matplotlib are not grouped
• Reimplement-cleaned_version\Figures\5\figure6b.py:4,0 - [3m(C0301)[23m Line too long (146/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:5,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:6,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:7,0 - [3m(C0301)[23m Line too long (140/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:8,0 - [3m(C0301)[23m Line too long (145/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:9,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:10,0 - [3m(C0301)[23m Line too long (138/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:11,0 - [3m(C0301)[23m Line too long (156/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:12,0 - [3m(C0301)[23m Line too long (139/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:13,0 - [3m(C0301)[23m Line too long (147/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:14,0 - [3m(C0301)[23m Line too long (148/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:15,0 - [3m(C0301)[23m Line too long (150/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:16,0 - [3m(C0301)[23m Line too long (151/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:17,0 - [3m(C0301)[23m Line too long (147/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:18,0 - [3m(C0301)[23m Line too long (150/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:19,0 - [3m(C0301)[23m Line too long (151/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:20,0 - [3m(C0301)[23m Line too long (152/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:21,0 - [3m(C0301)[23m Line too long (151/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:22,0 - [3m(C0301)[23m Line too long (150/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:23,0 - [3m(C0301)[23m Line too long (126/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:24,0 - [3m(C0301)[23m Line too long (148/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:25,0 - [3m(C0301)[23m Line too long (149/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:26,0 - [3m(C0301)[23m Line too long (149/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:67,0 - [3m(C0301)[23m Line too long (118/100)
• Reimplement-cleaned_version\Figures\5\figure6b.py:1,0 - [3m(C0114)[23m Missing module docstring
• Reimplement-cleaned_version\Figures\5\figure6b.py:30,0 - [3m(C0413)[23m Import "import numpy as np" should be placed at the
  top of the module
• Reimplement-cleaned_version\Figures\5\figure6b.py:31,0 - [3m(W0404)[23m Reimport 'matplotlib.pyplot' (imported line 2)
• Reimplement-cleaned_version\Figures\5\figure6b.py:31,0 - [3m(C0413)[23m Import "import matplotlib.pyplot as plt" should be
  placed at the top of the module
• Reimplement-cleaned_version\Figures\5\figure6b.py:43,0 - [3m(C0103)[23m Constant name "space" doesn't conform to UPPER_CASE
  naming style
• Reimplement-cleaned_version\Figures\5\figure6b.py:45,0 - [3m(C0103)[23m Constant name "width" doesn't conform to UPPER_CASE
  naming style
• Reimplement-cleaned_version\Figures\5\figure6b.py:60,43 - [3m(E0602)[23m Undefined variable 'xrange'
• Reimplement-cleaned_version\Figures\5\figure6b.py:31,0 - [3m(C0412)[23m Imports from package matplotlib are not grouped
• Reimplement-cleaned_version\Figures\5\figure6c.py:43,7 - [3m(E0001)[23m invalid syntax (<unknown>, line 43)
• Reimplement-cleaned_version\Figures\6\discussion1.py:78,11 - [3m(E0001)[23m invalid syntax (<unknown>, line 78)
• Reimplement-cleaned_version\Statistics__init__.py:1,0 - [3m(C0103)[23m Module name "Statistics" doesn't conform to
  snake_case naming style
• Reimplement-cleaned_version\Statistics\run_stats.py:1,0 - [3m(C0114)[23m Missing module docstring
• Reimplement-cleaned_version\Statistics\run_stats.py:1,0 - [3m(E0401)[23m Unable to import 'sk'
• Reimplement-cleaned_version\Statistics\run_stats.py:4,0 - [3m(W0105)[23m String statement has no effect
• Reimplement-cleaned_version\Statistics\run_stats.py:8,26 - [3m(R1732)[23m Consider using 'with' for resource-allocating
  operations
• Reimplement-cleaned_version\Statistics\run_stats.py:8,26 - [3m(W1514)[23m Using open without explicitly specifying an
  encoding
• Reimplement-cleaned_version\Statistics\run_stats.py:2,0 - [3m(C0411)[23m standard import "import pickle" should be placed
  before "from sk import rdivDemo"
• Reimplement-cleaned_version\Statistics\sk.py:121,9 - [3m(E0001)[23m invalid syntax (<unknown>, line 121)
• Reimplement-cleaned_version\merge_pickle.py:29,0 - [3m(C0304)[23m Final newline missing
• Reimplement-cleaned_version\merge_pickle.py:1,0 - [3m(C0114)[23m Missing module docstring
• Reimplement-cleaned_version\merge_pickle.py:5,0 - [3m(C0116)[23m Missing function or method docstring
• Reimplement-cleaned_version\merge_pickle.py:7,23 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Reimplement-cleaned_version\merge_pickle.py:7,23 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Reimplement-cleaned_version\merge_pickle.py:8,30 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Reimplement-cleaned_version\merge_pickle.py:8,30 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Reimplement-cleaned_version\merge_pickle.py:9,29 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Reimplement-cleaned_version\merge_pickle.py:9,29 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Reimplement-cleaned_version\merge_pickle.py:14,8 - [3m(C0103)[23m Variable name "r1" doesn't conform to snake_case naming
  style
• Reimplement-cleaned_version\merge_pickle.py:26,23 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Reimplement-cleaned_version\merge_pickle.py:26,23 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Reimplement-cleaned_version\policies.py:20,0 - [3m(C0304)[23m Final newline missing
• Reimplement-cleaned_version\policies.py:1,0 - [3m(C0114)[23m Missing module docstring
• Reimplement-cleaned_version\policies.py:12,12 - [3m(R1705)[23m Unnecessary "elif" after "return", remove the leading "el"
  from "elif"
• Reimplement-cleaned_version\progressive_sampling.py:118,15 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you
  mean print(file, end=" ")? (<unknown>, line 118)
• Reimplement-cleaned_version\projective_sampling.py:61,15 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you
  mean print(filename, end=" ")? (<unknown>, line 61)
• Reimplement-cleaned_version\rank_based_sampling.py:130,15 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you
  mean print(file, end=" ")? (<unknown>, line 130)
• Reimplement-cleaned_version\rank_based_sampling.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==figure6:[2:35]
  ┃ ==figure6b:[2:34]
  ┃ data = [
  ┃     # datasetname, dumbmre, dumbstd, dumbevals, randommre, randomstd, randomevals, atrimre, atristd, atrievals,
  ┃ accuracy from figure1 of the paper
  ┃     ["./Data/Apache_AllMeasurements.csv", 10.7923400483, 4.30570224034, 29.5, 10.4947292635, 2.20430123136, 16.0,
  ┃ 7.54820448973, 1.02106706701, 49.0, 7.17],
  ┃     ["./Data/BDBC_AllMeasurements.csv", 110.479335881, 187.802451244, 38.0, 11.8572934856, 4.30291195193, 42.5,
  ┃ 1.40528125434, 0.835513510745, 186.0, 0.48],
  ┃     ["./Data/Dune.csv", 14.9476364347, 2.94470453023, 36.0, 10.4241382255, 0.852644275258, 99.0, 10.7840541533,
  ┃ 1.06376053277, 117.0, 6.25],
  ┃     ["./Data/HSMGP_num.csv", 28.4925806894, 6.3190261939, 26.5, 10.2280499171, 0.462206395751, 444.0, 10.877402825,
  ┃ 0.742661331947, 383.0, 6.88],
  ┃     ["./Data/SQL_AllMeasurements.csv", 5.86748929191, 0.484176841033, 22.0, 6.13162555204, 0.841248582473, 10.0,
  ┃ 5.47668186009, 0.326518039763, 66.0, 4.41],
  ┃     ["./Data/WGet.csv", 9.67864308777, 11.9126425088, 27.0, 11.2691693847, 10.6807762614, 16.5, 12.1150493787,
  ┃ 12.0269102756, 23.0, 4.71],
  ┃     ["./Data/X264_AllMeasurements.csv", 6.43736284941, 4.22374067851, 31.5, 9.8685240802, 1.42535845389, 12.5,
  ┃ 0.751253662102, 0.187911591044, 151.0, 0.19],
  ┃     ["./Data/lrzip.csv", 95.3716768331, 184.552495732, 28.0, 12.9970921642, 4.34355122863, 87.5, 24.5860492819,
  ┃ 9.95373861074, 49.0, 6.07],
  ┃     ["./Data/rs-6d-c3_obj1.csv", 421.042970956, 522.879249452, 32.0, 13.7337428323, 8.5542189313, 599.5,
  ┃ 12.1311203278, 3.82724520753, 678.0, 8.4],
  ┃     ["./Data/rs-6d-c3_obj2.csv", 3650.66714862, 8035.48329532, 27.5, 13.5995547003, 5.83251455828, 687.5,
  ┃ 11.7792618959, 5.9591126095, 835.0, 9.01],
  ┃     ["./Data/sol-6d-c2-obj1.csv", 643.593480935, 1743.01883524, 37.0, 43.6706927286, 22.377177188, 577.0,
  ┃ 59.6853689508, 32.0536509917, 188.0, 38.08],
  ┃     ["./Data/sol-6d-c2-obj2.csv", 2653.46711207, 3944.90370138, 33.5, 80.6249317966, 23.9129599203, 576.0,
  ┃ 153.869243982, 107.110325652, 251.0, 76.52],
  ┃     # ["./Data/sort_256_obj2.csv", 11.5712032183, 3.87771922132, 25.5, 10.0586679798, 2.44405242568, 26.0,
  ┃ 20.862548876, 3.74071290731, 4.0, 6.79],
  ┃     ["./Data/wc+rs-3d-c4-obj1.csv", 34.8070233671, 28.5367725653, 23.5, 17.6727526682, 6.0489703848, 43.0,
  ┃ 19.3442173065, 4.76740956441, 28.0, 10.46],
  ┃     ["./Data/wc+rs-3d-c4-obj2.csv", 4219.83055425, 17355.9942052, 19.0, 105.583909043, 129.957739811, 43.0,
  ┃ 232.074858955, 518.975346651, 45.0, 76.55],
  ┃     ["./Data/wc+sol-3d-c4-obj1.csv", 37.1469049896, 25.4539940247, 26.0, 20.8223753716, 12.4935049708, 43.0,
  ┃ 27.8280265354, 15.9387424543, 28.0, 12.36],
  ┃     ["./Data/wc+sol-3d-c4-obj2.csv", 3731.3645478, 8159.94720512, 21.0, 138.098828117, 160.052893102, 43.0,
  ┃ 50.5793154978, 62.3850186383, 56.0, 46.08],
  ┃     ["./Data/wc+wc-3d-c4-obj1.csv", 31.6497529061, 30.7841955488, 26.0, 18.7216467377, 7.13603475529, 43.0,
  ┃ 26.8501276869, 11.9082288625, 27.0, 15.9],
  ┃     ["./Data/wc+wc-3d-c4-obj2.csv", 3159.59661431, 11636.1618333, 23.0, 93.9384111155, 91.27189707, 43.0, 90, 0.0,
  ┃ 48, 48.75],
  ┃     ["./Data/wc-3d-c4_obj2.csv", 12402.4561374, 31085.8027157, 28.5, 52.5777728899, 42.782323966, 155.0,
  ┃ 895.991096589, 2555.03744773, 59.0, 44.45],
  ┃     ["./Data/wc-6d-c1-obj1.csv", 141.305549567, 117.172292763, 26.5, 10.8449550879, 1.44458681925, 388.5,
  ┃ 13.1048972691, 3.33600531343, 361.0, 7.44],
  ┃     ["./Data/wc-6d-c1-obj2.csv", 690.812872709, 2068.20619916, 28.0, 10.4653064851, 0.63580925096, 336.0,
  ┃ 20.5970699707, 7.97878382382, 125.0, 8.47],
  ┃
  ┃
  ┃ ]
  ┃
  ┃
  ┃ import numpy as np
  ┃ import matplotlib.pyplot as plt
  ┃ data = sorted(data, key=lambda x: x[-1])
  ┃ N = len(data)
  ┃ dumb_evals = [d[3] for d in data]

• Reimplement-cleaned_version\rank_based_sampling.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==figure5:[2:35]
  ┃ ==figure6:[2:33]
  ┃ data = [
  ┃     # datasetname, dumbmre, dumbstd, dumbevals, randommre, randomstd, randomevals, atrimre, atristd, atrievals,
  ┃ accuracy from figure1 of the paper
  ┃     ["./Data/Apache_AllMeasurements.csv", 10.7923400483, 4.30570224034, 29.5, 10.4947292635, 2.20430123136, 16.0,
  ┃ 7.54820448973, 1.02106706701, 49.0, 7.17],
  ┃     ["./Data/BDBC_AllMeasurements.csv", 110.479335881, 187.802451244, 38.0, 11.8572934856, 4.30291195193, 42.5,
  ┃ 1.40528125434, 0.835513510745, 186.0, 0.48],
  ┃     ["./Data/Dune.csv", 14.9476364347, 2.94470453023, 36.0, 10.4241382255, 0.852644275258, 99.0, 10.7840541533,
  ┃ 1.06376053277, 117.0, 6.25],
  ┃     ["./Data/HSMGP_num.csv", 28.4925806894, 6.3190261939, 26.5, 10.2280499171, 0.462206395751, 444.0, 10.877402825,
  ┃ 0.742661331947, 383.0, 6.88],
  ┃     ["./Data/SQL_AllMeasurements.csv", 5.86748929191, 0.484176841033, 22.0, 6.13162555204, 0.841248582473, 10.0,
  ┃ 5.47668186009, 0.326518039763, 66.0, 4.41],
  ┃     ["./Data/WGet.csv", 9.67864308777, 11.9126425088, 27.0, 11.2691693847, 10.6807762614, 16.5, 12.1150493787,
  ┃ 12.0269102756, 23.0, 4.71],
  ┃     ["./Data/X264_AllMeasurements.csv", 6.43736284941, 4.22374067851, 31.5, 9.8685240802, 1.42535845389, 12.5,
  ┃ 0.751253662102, 0.187911591044, 151.0, 0.19],
  ┃     ["./Data/lrzip.csv", 95.3716768331, 184.552495732, 28.0, 12.9970921642, 4.34355122863, 87.5, 24.5860492819,
  ┃ 9.95373861074, 49.0, 6.07],
  ┃     ["./Data/rs-6d-c3_obj1.csv", 421.042970956, 522.879249452, 32.0, 13.7337428323, 8.5542189313, 599.5,
  ┃ 12.1311203278, 3.82724520753, 678.0, 8.4],
  ┃     ["./Data/rs-6d-c3_obj2.csv", 3650.66714862, 8035.48329532, 27.5, 13.5995547003, 5.83251455828, 687.5,
  ┃ 11.7792618959, 5.9591126095, 835.0, 9.01],
  ┃     ["./Data/sol-6d-c2-obj1.csv", 643.593480935, 1743.01883524, 37.0, 43.6706927286, 22.377177188, 577.0,
  ┃ 59.6853689508, 32.0536509917, 188.0, 38.08],
  ┃     ["./Data/sol-6d-c2-obj2.csv", 2653.46711207, 3944.90370138, 33.5, 80.6249317966, 23.9129599203, 576.0,
  ┃ 153.869243982, 107.110325652, 251.0, 76.52],
  ┃     # ["./Data/sort_256_obj2.csv", 11.5712032183, 3.87771922132, 25.5, 10.0586679798, 2.44405242568, 26.0,
  ┃ 20.862548876, 3.74071290731, 4.0, 6.79],
  ┃     ["./Data/wc+rs-3d-c4-obj1.csv", 34.8070233671, 28.5367725653, 23.5, 17.6727526682, 6.0489703848, 43.0,
  ┃ 19.3442173065, 4.76740956441, 28.0, 10.46],
  ┃     ["./Data/wc+rs-3d-c4-obj2.csv", 4219.83055425, 17355.9942052, 19.0, 105.583909043, 129.957739811, 43.0,
  ┃ 232.074858955, 518.975346651, 45.0, 76.55],
  ┃     ["./Data/wc+sol-3d-c4-obj1.csv", 37.1469049896, 25.4539940247, 26.0, 20.8223753716, 12.4935049708, 43.0,
  ┃ 27.8280265354, 15.9387424543, 28.0, 12.36],
  ┃     ["./Data/wc+sol-3d-c4-obj2.csv", 3731.3645478, 8159.94720512, 21.0, 138.098828117, 160.052893102, 43.0,
  ┃ 50.5793154978, 62.3850186383, 56.0, 46.08],
  ┃     ["./Data/wc+wc-3d-c4-obj1.csv", 31.6497529061, 30.7841955488, 26.0, 18.7216467377, 7.13603475529, 43.0,
  ┃ 26.8501276869, 11.9082288625, 27.0, 15.9],
  ┃     ["./Data/wc+wc-3d-c4-obj2.csv", 3159.59661431, 11636.1618333, 23.0, 93.9384111155, 91.27189707, 43.0, 90, 0.0,
  ┃ 48, 48.75],
  ┃     ["./Data/wc-3d-c4_obj2.csv", 12402.4561374, 31085.8027157, 28.5, 52.5777728899, 42.782323966, 155.0,
  ┃ 895.991096589, 2555.03744773, 59.0, 44.45],
  ┃     ["./Data/wc-6d-c1-obj1.csv", 141.305549567, 117.172292763, 26.5, 10.8449550879, 1.44458681925, 388.5,
  ┃ 13.1048972691, 3.33600531343, 361.0, 7.44],
  ┃     ["./Data/wc-6d-c1-obj2.csv", 690.812872709, 2068.20619916, 28.0, 10.4653064851, 0.63580925096, 336.0,
  ┃ 20.5970699707, 7.97878382382, 125.0, 8.47],
  ┃
  ┃
  ┃ ]
  ┃
  ┃
  ┃ import numpy as np
  ┃ import matplotlib.pyplot as plt
  ┃
  ┃
  ┃ data = sorted(data, key=lambda x: x[-1])
  ┃
  ┃
  ┃ N = len(data)

• Reimplement-cleaned_version\rank_based_sampling.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==figure6:[35:42]
  ┃ ==figure6b:[42:50]
  ┃ space = 7
  ┃ ind = np.arange(space, space*(len(data)+1), space)  # the x locations for the groups
  ┃ width = 1.5        # the width of the bars
  ┃
  ┃
  ┃ fig, ax = plt.subplots()
  ┃ rects1 = ax.bar(ind, dumb_evals, width, color='#f0f0f0', log=True, label='Rank-based')


1.1.3.3 Details — Mypy reports no issues with this project — ✅

Congratulations, Mypy is happy with your project!

1.1.3.4 Details — Black reports no issues with this project — ❌

Black reported [1m7[0m files in your project that it would reformat:
• Reimplement-cleaned_version\Figures\2\figure2.py
• Reimplement-cleaned_version\merge_pickle.py
• Reimplement-cleaned_version\Figures\4\figure5.py
• Reimplement-cleaned_version\policies.py
• Reimplement-cleaned_version\Figures\5\figure6.py
• Reimplement-cleaned_version\Figures\3\figure4.py
• Reimplement-cleaned_version\Figures\5\figure6b.py

Black can fix these issues automatically when you run black . in your project.

1.1.3.5 Details — isort reports no issues with this project — ❌

isort reported [1m13[0m files in your project that it would fix:
• Reimplement-cleaned_version\merge_pickle.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\progressive_sampling.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\projective_sampling.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\rank_based_sampling.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\Figures\1\figure1.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\Figures\2\figure2.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\Figures\4\figure5.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\Figures\5\figure6.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\Figures\5\figure6b.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\Figures\5\figure6c.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\Figures\6\discussion1.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\Statistics\run_stats.py - Imports are incorrectly sorted and/or formatted.
• Reimplement-cleaned_version\Statistics\sk.py - Imports are incorrectly sorted and/or formatted.

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
    line 14: cannot unmarshal !!map into string line 16: cannot unmarshal !!map into string, output:

┃ errors:
┃ - filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\1\figure1.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\3\figure4_2.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\5\figure6c.py
┃   reason: syntax error while parsing AST from file
┃ - filename:
┃ F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\6\discussion1.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Statistics\sk.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\progressive_sampling.py
┃ 
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\projective_sampling.py
┃   reason: syntax error while parsing AST from file
┃ - filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\rank_based_sampling.py
┃   reason: syntax error while parsing AST from file
┃ generated_at: '2022-08-20T07:48:33Z'
┃ metrics:
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\1\figure1.py:
┃     loc: 101
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\2\figure2.py:
┃     CONFIDENCE.HIGH: 1
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 1
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 73
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\3\__init__.py:
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
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\3\figure4.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 56
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\3\figure4_2.py:
┃     loc: 71
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\4\figure5.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 49
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\5\figure6.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 46
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\5\figure6b.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 49
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\5\figure6c.py:
┃     loc: 53
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\6\discussion1.py:
┃     loc: 167
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Statistics\__init__.py:
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
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Statistics\run_stats.py:
┃     CONFIDENCE.HIGH: 2
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 1
┃     SEVERITY.MEDIUM: 1
┃     SEVERITY.UNDEFINED: 0
┃     loc: 15
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Statistics\sk.py:
┃     loc: 486
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\merge_pickle.py:
┃     CONFIDENCE.HIGH: 4
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 1
┃     SEVERITY.MEDIUM: 3
┃     SEVERITY.UNDEFINED: 0
┃     loc: 22
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\policies.py:
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
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\progressive_sampling.py:
┃     loc: 118
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\projective_sampling.py:
┃     loc: 84
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\rank_based_sampling.py:
┃     loc: 125
┃     nosec: 0
┃     skipped_tests: 0
┃   _totals:
┃     CONFIDENCE.HIGH: 7
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 3
┃     SEVERITY.MEDIUM: 4
┃     SEVERITY.UNDEFINED: 0
┃     loc: 1533
┃     nosec: 0
┃     skipped_tests: 0
┃ results:
┃ - code: 60     train_indexes, test_indexes = indexes[:int(0.5*len(indexes))], indexes[int(.5*len(indexes)):]\n61
┃ assert(len(train_indexes)
┃     + len(test_indexes) == len(indexes)), "Something is wrong"\n62     train_set =
┃     [content[i] for i in train_indexes]\n
┃   col_offset: 4
┃   filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Figures\2\figure2.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 703
┃     link: https://cwe.mitre.org/data/definitions/703.html
┃   issue_severity: LOW
┃   issue_text: Use of assert detected. The enclosed code will be removed when compiling
┃     to optimised byte code.
┃   line_number: 61
┃   line_range:
┃   - 61
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b101_assert_used.html
┃   test_id: B101
┃   test_name: assert_used
┃ - code: 1 from sk import rdivDemo\n2 import pickle\n3 \n4 """\n
┃   col_offset: 0
┃   filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Statistics\run_stats.py
┃ 
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 502
┃     link: https://cwe.mitre.org/data/definitions/502.html
┃   issue_severity: LOW
┃   issue_text: Consider possible security implications associated with pickle module.
┃   line_number: 2
┃   line_range:
┃   - 2
┃   - 3
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_imports.html#b403-import-pickle
┃   test_id: B403
┃   test_name: blacklist
┃ - code: 7 \n8 dict_result = pickle.load(open("merged.p", "r"))\n9 files = sorted(dict_result.keys())\n
┃   col_offset: 14
┃   filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\Statistics\run_stats.py
┃ 
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 502
┃     link: https://cwe.mitre.org/data/definitions/502.html
┃   issue_severity: MEDIUM
┃   issue_text: Pickle and modules that wrap it can be unsafe when used to deserialize
┃     untrusted data, possible security issue.
┃   line_number: 8
┃   line_range:
┃   - 8
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_calls.html#b301-pickle
┃   test_id: B301
┃   test_name: blacklist
┃ - code: 1 from __future__ import division\n2 import pickle\n3 \n4 \n5 def merge_pickle(rank_pickle,
┃     progressive_pickle, projective_pickle):\n
┃   col_offset: 0
┃   filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\merge_pickle.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 502
┃     link: https://cwe.mitre.org/data/definitions/502.html
┃   issue_severity: LOW
┃   issue_text: Consider possible security implications associated with pickle module.
┃   line_number: 2
┃   line_range:
┃   - 2
┃   - 3
┃   - 4
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_imports.html#b403-import-pickle
┃   test_id: B403
┃   test_name: blacklist
┃ - code: 6     pickle_folder = "PickleLocker/"\n7     rank = pickle.load(open(pickle_folder
┃     + rank_pickle, "r"))\n8     progressive = pickle.load(open(pickle_folder + progressive_pickle,
┃     "r"))\n
┃   col_offset: 11
┃   filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\merge_pickle.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 502
┃     link: https://cwe.mitre.org/data/definitions/502.html
┃   issue_severity: MEDIUM
┃   issue_text: Pickle and modules that wrap it can be unsafe when used to deserialize
┃     untrusted data, possible security issue.
┃   line_number: 7
┃   line_range:
┃   - 7
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_calls.html#b301-pickle
┃   test_id: B301
┃   test_name: blacklist
┃ - code: 7     rank = pickle.load(open(pickle_folder + rank_pickle, "r"))\n8     progressive
┃     = pickle.load(open(pickle_folder + progressive_pickle, "r"))\n9     projective
┃     = pickle.load(open(pickle_folder + projective_pickle, "r"))\n
┃   col_offset: 18
┃   filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\merge_pickle.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 502
┃     link: https://cwe.mitre.org/data/definitions/502.html
┃   issue_severity: MEDIUM
┃   issue_text: Pickle and modules that wrap it can be unsafe when used to deserialize
┃     untrusted data, possible security issue.
┃   line_number: 8
┃   line_range:
┃   - 8
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_calls.html#b301-pickle
┃   test_id: B301
┃   test_name: blacklist
┃ - code: 8     progressive = pickle.load(open(pickle_folder + progressive_pickle, "r"))\n9     projective
┃     = pickle.load(open(pickle_folder + projective_pickle, "r"))\n10 \n
┃   col_offset: 17
┃   filename: F:\Python3.8env/data/2017/Reimplement-cleaned_version\Reimplement-cleaned_version\merge_pickle.py
┃   issue_confidence: HIGH
┃   issue_cwe:
┃     id: 502
┃     link: https://cwe.mitre.org/data/definitions/502.html
┃   issue_severity: MEDIUM
┃   issue_text: Pickle and modules that wrap it can be unsafe when used to deserialize
┃     untrusted data, possible security issue.
┃   line_number: 9
┃   line_range:
┃   - 9
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_calls.html#b301-pickle
┃   test_id: B301
┃   test_name: blacklist


---
❌ rules unsuccessful:	19
Your project is still lacking in quality and could do with some improvements.
Use mllint describe with each rule's slug to learn more about what you can do to get the rules to pass and improve the quality of your ML project.

took: 9.2799343s
