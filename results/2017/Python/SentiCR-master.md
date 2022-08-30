Linting project at  F:\Python3.8env/data/2017/SentiCR-master
No .mllint.yml or pyproject.toml found in project folder, using default configuration
---

🏃 Running - Code Quality (0.00 ms)
🏃 Running - Testing (0.00 ms)
🏃 Running - Version Control (0.00 ms)
🏃 Running - Dependency Management (0.51 ms)
🏃 Running - Continuous Integration (CI) (0.51 ms)
✔️ Done - Testing (0.51 ms)
✔️ Done - Dependency Management (0.51 ms)
🏃 Running - Version Control - Git (0.00 ms)
⏳ Waiting - Version Control (0.51 ms)
🏃 Running - Version Control - DVC (0.00 ms)
✔️ Done - Version Control - DVC (0.00 ms)
🏃 Running - Code Quality - Pylint (0.00 ms)
🏃 Running - Code Quality - Mypy (0.00 ms)
🏃 Running - Code Quality - Black (0.00 ms)
🏃 Running - Code Quality - isort (0.00 ms)
🏃 Running - Code Quality - Bandit (0.00 ms)
⏳ Waiting - Code Quality (5 ms)
✔️ Done - Version Control - Git (65 ms)
✔️ Done - Version Control (66 ms)
🏃 Running - Version Control (66 ms)
✔️ Done - Continuous Integration (CI) (242 ms)
✔️ Done - Code Quality - isort (1.05 s)
✔️ Done - Code Quality - Bandit (2.17 s)
✔️ Done - Code Quality - Black (2.39 s)
✔️ Done - Code Quality - Pylint (6.14 s)
✔️ Done - Code Quality - Mypy (6.78 s)
✔️ Done - Code Quality (6.79 s)
🏃 Running - Code Quality (6.79 s)

✔️ All done!

---

1 ML Project Report
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────

┌──────────────────────┬────────────────────────────────────────┐
│[1mProject[0m               │[1mDetails[0m                                 │
╞══════════════════════╪════════════════════════════════════════╡
│Date                  │Sat, 20 Aug 2022 15:48:50 +0800         │
├──────────────────────┼────────────────────────────────────────┤
│Path                  │F:\Python3.8env/data/2017/SentiCR-master│
├──────────────────────┼────────────────────────────────────────┤
│Config                │default                                 │
├──────────────────────┼────────────────────────────────────────┤
│Default               │Yes                                     │
├──────────────────────┼────────────────────────────────────────┤
│Number of Python files│3                                       │
├──────────────────────┼────────────────────────────────────────┤
│Lines of Python code  │349                                     │
└──────────────────────┴────────────────────────────────────────┘
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
1.1.3 Code Quality (code-quality) — [1m24.1[0m%

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
│  ❌  │  0.0%│     1│Mypy reports no issues with this project        │code-quality/mypy/no-issues                     │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │  0.0%│     1│Black reports no issues with this project       │code-quality/black/no-issues                    │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │  0.0%│     1│isort reports no issues with this project       │code-quality/isort/no-issues                    │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │  0.0%│     0│isort is properly configured                    │code-quality/isort/is-configured                │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │ 92.8%│     1│Bandit reports no issues with this project      │code-quality/bandit/no-issues                   │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│      │ [3mTotal[23m│      │                                                │                                                │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │ [1m24.1[0m%│      │Code Quality                                    │code-quality                                    │
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

Pylint reported [1m128[0m issues with your project:
• SentiCR-master\SentiCR\SentiCR.py:64,0 - [3m(C0301)[23m Line too long (105/100)
• SentiCR-master\SentiCR\SentiCR.py:65,0 - [3m(C0301)[23m Line too long (104/100)
• SentiCR-master\SentiCR\SentiCR.py:66,0 - [3m(C0301)[23m Line too long (107/100)
• SentiCR-master\SentiCR\SentiCR.py:67,0 - [3m(C0301)[23m Line too long (108/100)
• SentiCR-master\SentiCR\SentiCR.py:68,0 - [3m(C0301)[23m Line too long (117/100)
• SentiCR-master\SentiCR\SentiCR.py:69,0 - [3m(C0301)[23m Line too long (107/100)
• SentiCR-master\SentiCR\SentiCR.py:105,0 - [3m(W0311)[23m Bad indentation. Found 5 spaces, expected 4
• SentiCR-master\SentiCR\SentiCR.py:106,0 - [3m(W0311)[23m Bad indentation. Found 9 spaces, expected 8
• SentiCR-master\SentiCR\SentiCR.py:107,0 - [3m(W0311)[23m Bad indentation. Found 5 spaces, expected 4
• SentiCR-master\SentiCR\SentiCR.py:110,0 - [3m(C0301)[23m Line too long (104/100)
• SentiCR-master\SentiCR\SentiCR.py:161,0 - [3m(W0311)[23m Bad indentation. Found 25 spaces, expected 24
• SentiCR-master\SentiCR\SentiCR.py:192,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• SentiCR-master\SentiCR\SentiCR.py:234,0 - [3m(C0301)[23m Line too long (101/100)
• SentiCR-master\SentiCR\SentiCR.py:240,0 - [3m(C0301)[23m Line too long (121/100)
• SentiCR-master\SentiCR\SentiCR.py:375,0 - [3m(C0305)[23m Trailing newlines
• SentiCR-master\SentiCR\SentiCR.py:110,66 - [3m(W1401)[23m Anomalous backslash in string: '('. String constant might be
  missing an r prefix.
• SentiCR-master\SentiCR\SentiCR.py:110,68 - [3m(W1401)[23m Anomalous backslash in string: ')'. String constant might be
  missing an r prefix.
• SentiCR-master\SentiCR\SentiCR.py:1,0 - [3m(C0114)[23m Missing module docstring
• SentiCR-master\SentiCR\SentiCR.py:1,0 - [3m(C0103)[23m Module name "SentiCR" doesn't conform to snake_case naming style
• SentiCR-master\SentiCR\SentiCR.py:2,0 - [3m(E0401)[23m Unable to import 'sklearn.model_selection'
• SentiCR-master\SentiCR\SentiCR.py:3,0 - [3m(E0401)[23m Unable to import 'sklearn.metrics'
• SentiCR-master\SentiCR\SentiCR.py:4,0 - [3m(E0401)[23m Unable to import 'sklearn.metrics'
• SentiCR-master\SentiCR\SentiCR.py:5,0 - [3m(E0401)[23m Unable to import 'sklearn.metrics'
• SentiCR-master\SentiCR\SentiCR.py:6,0 - [3m(E0401)[23m Unable to import 'sklearn.metrics'
• SentiCR-master\SentiCR\SentiCR.py:12,0 - [3m(E0401)[23m Unable to import 'nltk'
• SentiCR-master\SentiCR\SentiCR.py:13,0 - [3m(E0401)[23m Unable to import 'xlrd'
• SentiCR-master\SentiCR\SentiCR.py:20,0 - [3m(E0401)[23m Unable to import 'sklearn.neural_network'
• SentiCR-master\SentiCR\SentiCR.py:21,0 - [3m(E0401)[23m Unable to import 'sklearn.feature_extraction.text'
• SentiCR-master\SentiCR\SentiCR.py:22,0 - [3m(E0401)[23m Unable to import 'sklearn.svm'
• SentiCR-master\SentiCR\SentiCR.py:23,0 - [3m(E0401)[23m Unable to import 'sklearn.linear_model'
• SentiCR-master\SentiCR\SentiCR.py:24,0 - [3m(E0401)[23m Unable to import 'sklearn.naive_bayes'
• SentiCR-master\SentiCR\SentiCR.py:25,0 - [3m(E0401)[23m Unable to import 'sklearn.ensemble'
• SentiCR-master\SentiCR\SentiCR.py:26,0 - [3m(E0401)[23m Unable to import 'sklearn.ensemble'
• SentiCR-master\SentiCR\SentiCR.py:27,0 - [3m(E0401)[23m Unable to import 'sklearn.ensemble'
• SentiCR-master\SentiCR\SentiCR.py:28,0 - [3m(E0401)[23m Unable to import 'sklearn.tree'
• SentiCR-master\SentiCR\SentiCR.py:30,0 - [3m(E0401)[23m Unable to import 'nltk.stem.snowball'
• SentiCR-master\SentiCR\SentiCR.py:31,0 - [3m(E0401)[23m Unable to import 'imblearn.over_sampling'
• SentiCR-master\SentiCR\SentiCR.py:34,0 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:41,0 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:47,0 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:82,5 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• SentiCR-master\SentiCR\SentiCR.py:83,5 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• SentiCR-master\SentiCR\SentiCR.py:94,0 - [3m(C0103)[23m Constant name "grammar" doesn't conform to UPPER_CASE naming style
• SentiCR-master\SentiCR\SentiCR.py:102,32 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• SentiCR-master\SentiCR\SentiCR.py:104,0 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:104,24 - [3m(C0103)[23m Argument name "s" doesn't conform to snake_case naming style
• SentiCR-master\SentiCR\SentiCR.py:104,0 - [3m(W0102)[23m Dangerous default value contractions_dict (builtins.list) as
  argument
• SentiCR-master\SentiCR\SentiCR.py:104,27 - [3m(W0621)[23m Redefining name 'contractions_dict' from outer scope (line 78)
• SentiCR-master\SentiCR\SentiCR.py:112,0 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:112,15 - [3m(C0103)[23m Argument name "s" doesn't conform to snake_case naming style
• SentiCR-master\SentiCR\SentiCR.py:131,0 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:132,4 - [3m(R1705)[23m Unnecessary "elif" after "return", remove the leading "el" from
  "elif"
• SentiCR-master\SentiCR\SentiCR.py:138,0 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:138,20 - [3m(W0621)[23m Redefining name 'comments' from outer scope (line 335)
• SentiCR-master\SentiCR\SentiCR.py:141,8 - [3m(C0103)[23m Variable name "st" doesn't conform to snake_case naming style
• SentiCR-master\SentiCR\SentiCR.py:149,16 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• SentiCR-master\SentiCR\SentiCR.py:156,32 - [3m(R1714)[23m Consider merging these comparisons with "in" to "pos in ('ADV',
  'ADJ', 'VERB')"
• SentiCR-master\SentiCR\SentiCR.py:141,4 - [3m(R1702)[23m Too many nested blocks (7/5)
• SentiCR-master\SentiCR\SentiCR.py:155,28 - [3m(W0612)[23m Unused variable 'i'
• SentiCR-master\SentiCR\SentiCR.py:173,0 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:174,4 - [3m(W0621)[23m Redefining name 'comments' from outer scope (line 335)
• SentiCR-master\SentiCR\SentiCR.py:183,0 - [3m(C0115)[23m Missing class docstring
• SentiCR-master\SentiCR\SentiCR.py:183,0 - [3m(R0903)[23m Too few public methods (0/2)
• SentiCR-master\SentiCR\SentiCR.py:189,0 - [3m(C0115)[23m Missing class docstring
• SentiCR-master\SentiCR\SentiCR.py:199,4 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:202,8 - [3m(R1705)[23m Unnecessary "elif" after "return", remove the leading "el" from
  "elif"
• SentiCR-master\SentiCR\SentiCR.py:199,4 - [3m(R0911)[23m Too many return statements (9/6)
• SentiCR-master\SentiCR\SentiCR.py:224,4 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:229,12 - [3m(W0621)[23m Redefining name 'comments' from outer scope (line 335)
• SentiCR-master\SentiCR\SentiCR.py:236,8 - [3m(C0103)[23m Variable name "X_train" doesn't conform to snake_case naming style
• SentiCR-master\SentiCR\SentiCR.py:237,8 - [3m(C0103)[23m Variable name "Y_train" doesn't conform to snake_case naming style
• SentiCR-master\SentiCR\SentiCR.py:243,8 - [3m(C0103)[23m Variable name "X_resampled" doesn't conform to snake_case naming
  style
• SentiCR-master\SentiCR\SentiCR.py:243,21 - [3m(C0103)[23m Variable name "Y_resampled" doesn't conform to snake_case naming
  style
• SentiCR-master\SentiCR\SentiCR.py:250,4 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:251,8 - [3m(W0621)[23m Redefining name 'workbook' from outer scope (line 330)
• SentiCR-master\SentiCR\SentiCR.py:252,8 - [3m(W0621)[23m Redefining name 'sheet' from outer scope (line 331)
• SentiCR-master\SentiCR\SentiCR.py:253,8 - [3m(W0621)[23m Redefining name 'oracle_data' from outer scope (line 332)
• SentiCR-master\SentiCR\SentiCR.py:255,12 - [3m(W0621)[23m Redefining name 'cell_num' from outer scope (line 334)
• SentiCR-master\SentiCR\SentiCR.py:256,12 - [3m(W0621)[23m Redefining name 'comments' from outer scope (line 335)
• SentiCR-master\SentiCR\SentiCR.py:261,4 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:267,4 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:278,0 - [3m(C0116)[23m Missing function or method docstring
• SentiCR-master\SentiCR\SentiCR.py:278,38 - [3m(C0103)[23m Argument name "ALGO" doesn't conform to snake_case naming style
• SentiCR-master\SentiCR\SentiCR.py:278,0 - [3m(R0914)[23m Too many local variables (18/15)
• SentiCR-master\SentiCR\SentiCR.py:278,38 - [3m(W0621)[23m Redefining name 'ALGO' from outer scope (line 323)
• SentiCR-master\SentiCR\SentiCR.py:299,8 - [3m(W0621)[23m Redefining name 'precision' from outer scope (line 350)
• SentiCR-master\SentiCR\SentiCR.py:300,8 - [3m(W0621)[23m Redefining name 'recall' from outer scope (line 350)
• SentiCR-master\SentiCR\SentiCR.py:301,8 - [3m(W0621)[23m Redefining name 'f1score' from outer scope (line 350)
• SentiCR-master\SentiCR\SentiCR.py:302,8 - [3m(W0621)[23m Redefining name 'accuracy' from outer scope (line 350)
• SentiCR-master\SentiCR\SentiCR.py:279,4 - [3m(C0103)[23m Variable name "kf" doesn't conform to snake_case naming style
• SentiCR-master\SentiCR\SentiCR.py:349,14 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• SentiCR-master\SentiCR\SentiCR.py:361,15 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• SentiCR-master\SentiCR\SentiCR.py:370,10 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• SentiCR-master\SentiCR\SentiCR.py:371,10 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• SentiCR-master\SentiCR\SentiCR.py:372,10 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• SentiCR-master\SentiCR\SentiCR.py:373,10 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• SentiCR-master\SentiCR\SentiCR.py:8,0 - [3m(C0411)[23m standard import "import random" should be placed before "from
  sklearn.model_selection import KFold"
• SentiCR-master\SentiCR\SentiCR.py:9,0 - [3m(C0411)[23m standard import "import csv" should be placed before "from
  sklearn.model_selection import KFold"
• SentiCR-master\SentiCR\SentiCR.py:10,0 - [3m(C0411)[23m standard import "import re" should be placed before "from
  sklearn.model_selection import KFold"
• SentiCR-master\SentiCR\SentiCR.py:14,0 - [3m(C0411)[23m standard import "from statistics import mean" should be placed
  before "from sklearn.model_selection import KFold"
• SentiCR-master\SentiCR\SentiCR.py:18,0 - [3m(C0411)[23m standard import "import argparse" should be placed before "from
  sklearn.model_selection import KFold"
• SentiCR-master\SentiCR\SentiCR.py:20,0 - [3m(C0412)[23m Imports from package sklearn are not grouped
• SentiCR-master\SentiCR\SentiCR.py:361,15 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• SentiCR-master\SentiCR\SentiCR.py:24,0 - [3m(W0611)[23m Unused MultinomialNB imported from sklearn.naive_bayes
• SentiCR-master\SentiCR\SenticrTest.py:8,0 - [3m(C0301)[23m Line too long (121/100)
• SentiCR-master\SentiCR\SenticrTest.py:10,0 - [3m(C0301)[23m Line too long (106/100)
• SentiCR-master\SentiCR\SenticrTest.py:12,0 - [3m(C0301)[23m Line too long (102/100)
• SentiCR-master\SentiCR\SenticrTest.py:13,0 - [3m(C0301)[23m Line too long (113/100)
• SentiCR-master\SentiCR\SenticrTest.py:17,0 - [3m(C0301)[23m Line too long (121/100)
• SentiCR-master\SentiCR\SenticrTest.py:19,0 - [3m(C0301)[23m Line too long (103/100)
• SentiCR-master\SentiCR\SenticrTest.py:20,0 - [3m(C0301)[23m Line too long (117/100)
• SentiCR-master\SentiCR\SenticrTest.py:23,0 - [3m(C0301)[23m Line too long (115/100)
• SentiCR-master\SentiCR\SenticrTest.py:28,0 - [3m(C0304)[23m Final newline missing
• SentiCR-master\SentiCR\SenticrTest.py:1,0 - [3m(C0114)[23m Missing module docstring
• SentiCR-master\SentiCR\SenticrTest.py:1,0 - [3m(C0103)[23m Module name "SenticrTest" doesn't conform to snake_case naming
  style
• SentiCR-master\posthoc\simulation.py:98,0 - [3m(C0301)[23m Line too long (132/100)
• SentiCR-master\posthoc\simulation.py:135,0 - [3m(C0301)[23m Line too long (106/100)
• SentiCR-master\posthoc\simulation.py:138,0 - [3m(C0301)[23m Line too long (108/100)
• SentiCR-master\posthoc\simulation.py:141,0 - [3m(C0304)[23m Final newline missing
• SentiCR-master\posthoc\simulation.py:1,0 - [3m(C0114)[23m Missing module docstring
• SentiCR-master\posthoc\simulation.py:1,0 - [3m(E0401)[23m Unable to import 'mysql.connector'
• SentiCR-master\posthoc\simulation.py:3,0 - [3m(E0401)[23m Unable to import 'scipy.stats'
• SentiCR-master\posthoc\simulation.py:4,0 - [3m(E0401)[23m Unable to import 'pandas'
• SentiCR-master\posthoc\simulation.py:5,0 - [3m(E0401)[23m Unable to import 'pandas'
• SentiCR-master\posthoc\simulation.py:31,4 - [3m(C0103)[23m Constant name "multi_sql" doesn't conform to UPPER_CASE naming
  style
• SentiCR-master\posthoc\simulation.py:134,11 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• SentiCR-master\posthoc\simulation.py:134,11 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• SentiCR-master\posthoc\simulation.py:2,0 - [3m(W0611)[23m Unused numpy imported as np

1.1.3.3 Details — Mypy reports no issues with this project — ❌

Mypy reported [1m64[0m issues with your project:
• SentiCR-master\posthoc\simulation.py:1,1 - Error: Cannot find implementation or library stub for module named
  "mysql.connector"  [import]
• SentiCR-master\posthoc\simulation.py:1,1 - Error: Cannot find implementation or library stub for module named "mysql"
  [import]
• SentiCR-master\posthoc\simulation.py:3,1 - Error: Cannot find implementation or library stub for module named
  "scipy.stats"  [import]
• SentiCR-master\posthoc\simulation.py:3,1 - Error: Cannot find implementation or library stub for module named "scipy"
  [import]
• SentiCR-master\posthoc\simulation.py:4,1 - Error: Cannot find implementation or library stub for module named
  "pandas"  [import]
• SentiCR-master\SentiCR\SentiCR.py:2,1 - Error: Cannot find implementation or library stub for module named
  "sklearn.model_selection"  [import]
• SentiCR-master\SentiCR\SentiCR.py:3,1 - Error: Cannot find implementation or library stub for module named
  "sklearn.metrics"  [import]
• SentiCR-master\SentiCR\SentiCR.py:12,1 - Error: Cannot find implementation or library stub for module named "nltk"
  [import]
• SentiCR-master\SentiCR\SentiCR.py:12,1 - Note: See [https://mypy.readthedocs.io/en/stable/running_mypy.html#missing-i
  mports](https://mypy.readthedocs.io/en/stable/running_mypy.html#missing-imports)
• SentiCR-master\SentiCR\SentiCR.py:13,1 - Error: Cannot find implementation or library stub for module named "xlrd"
  [import]
• SentiCR-master\SentiCR\SentiCR.py:20,1 - Error: Cannot find implementation or library stub for module named
  "sklearn.neural_network"  [import]
• SentiCR-master\SentiCR\SentiCR.py:21,1 - Error: Cannot find implementation or library stub for module named
  "sklearn.feature_extraction.text"  [import]
• SentiCR-master\SentiCR\SentiCR.py:22,1 - Error: Cannot find implementation or library stub for module named
  "sklearn.svm"  [import]
• SentiCR-master\SentiCR\SentiCR.py:23,1 - Error: Cannot find implementation or library stub for module named
  "sklearn.linear_model"  [import]
• SentiCR-master\SentiCR\SentiCR.py:24,1 - Error: Cannot find implementation or library stub for module named
  "sklearn.naive_bayes"  [import]
• SentiCR-master\SentiCR\SentiCR.py:25,1 - Error: Cannot find implementation or library stub for module named
  "sklearn.ensemble"  [import]
• SentiCR-master\SentiCR\SentiCR.py:28,1 - Error: Cannot find implementation or library stub for module named
  "sklearn.tree"  [import]
• SentiCR-master\SentiCR\SentiCR.py:30,1 - Error: Cannot find implementation or library stub for module named
  "nltk.stem.snowball"  [import]
• SentiCR-master\SentiCR\SentiCR.py:31,1 - Error: Cannot find implementation or library stub for module named
  "imblearn.over_sampling"  [import]
• SentiCR-master\SentiCR\SentiCR.py:34,1 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:41,1 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:47,1 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:49,13 - Error: Call to untyped function "stem_tokens" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:77,1 - Error: Need type annotation for "emodict" (hint: "emodict: List[<type>] =
  ...")  [var-annotated]
• SentiCR-master\SentiCR\SentiCR.py:78,1 - Error: Need type annotation for "contractions_dict" (hint:
  "contractions_dict: List[<type>] = ...")  [var-annotated]
• SentiCR-master\SentiCR\SentiCR.py:88,25 - Error: Incompatible types in assignment (expression has type "Dict[str,
  str]", variable has type "List[Any]")  [assignment]
• SentiCR-master\SentiCR\SentiCR.py:89,13 - Error: Incompatible types in assignment (expression has type "Dict[str,
  str]", variable has type "List[Any]")  [assignment]
• SentiCR-master\SentiCR\SentiCR.py:102,51 - Error: "List[Any]" has no attribute "keys"  [attr-defined]
• SentiCR-master\SentiCR\SentiCR.py:104,1 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:105,6 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:112,1 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:120,1 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:131,1 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:138,1 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:144,12 - Error: Call to untyped function "negated" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:154,48 - Error: Call to untyped function "negated" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:157,55 - Error: Call to untyped function "prepend_not" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:173,1 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:175,16 - Error: Call to untyped function "expand_contractions" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:176,16 - Error: Call to untyped function "remove_url" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:177,16 - Error: Call to untyped function "replace_all" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:178,16 - Error: Call to untyped function "handle_negation" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:184,5 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:190,5 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:193,32 - Error: Call to untyped function "read_data_from_oracle" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:196,22 - Error: Call to untyped function "create_model_from_training_data" in typed
  context  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:199,5 - Error: Function is missing a return type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:224,5 - Error: Function is missing a return type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:229,24 - Error: Call to untyped function "preprocess_text" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:245,15 - Error: Call to untyped function "get_classifier" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:250,5 - Error: Function is missing a return type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:256,22 - Error: Call to untyped function "SentimentData" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:261,5 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:262,17 - Error: Call to untyped function "preprocess_text" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:267,5 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:270,21 - Error: Call to untyped function "preprocess_text" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:278,1 - Error: Function is missing a type annotation  [no-untyped-def]
• SentiCR-master\SentiCR\SentiCR.py:292,26 - Error: Call to untyped function "SentiCR" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:297,16 - Error: Call to untyped function "get_sentiment_polarity_collection" in
  typed context  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:335,20 - Error: Call to untyped function "SentimentData" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SentiCR.py:340,17 - Error: Incompatible types in assignment (expression has type "ndarray[Any,
  dtype[Any]]", variable has type "List[SentimentData]")  [assignment]
• SentiCR-master\SentiCR\SentiCR.py:350,48 - Error: Call to untyped function "ten_fold_cross_validation" in typed
  context  [no-untyped-call]
• SentiCR-master\SentiCR\SenticrTest.py:3,20 - Error: Call to untyped function "SentiCR" in typed context
  [no-untyped-call]
• SentiCR-master\SentiCR\SenticrTest.py:27,11 - Error: Call to untyped function "get_sentiment_polarity" in typed
  context  [no-untyped-call]

1.1.3.4 Details — Black reports no issues with this project — ❌

Black reported [1m3[0m files in your project that it would reformat:
• SentiCR-master\SentiCR\SenticrTest.py
• SentiCR-master\posthoc\simulation.py
• SentiCR-master\SentiCR\SentiCR.py

Black can fix these issues automatically when you run black . in your project.

1.1.3.5 Details — isort reports no issues with this project — ❌

isort reported [1m3[0m files in your project that it would fix:
• SentiCR-master\posthoc\simulation.py - Imports are incorrectly sorted and/or formatted.
• SentiCR-master\SentiCR\SentiCR.py - Imports are incorrectly sorted and/or formatted.
• SentiCR-master\SentiCR\SenticrTest.py - Imports are incorrectly sorted and/or formatted.

isort can fix these issues automatically when you run isort . in your project.

1.1.3.6 Details — isort is properly configured — ❌

isort is not properly configured. In order to be compatible with [Black](https://github.com/psf/black), which mllint
also recommends using, you should configure isort to use the black profile. Furthermore, we recommend centralising your
configuration in your pyproject.toml

Thus, ensure that your pyproject.toml contains at least the following section:

┃ [tool.isort]
┃ profile = "black"

1.1.3.7 Details — Bandit reports no issues with this project — ❌

Bandit reported [1m1[0m issues with your project:
• SentiCR-master\posthoc\simulation.py:8 - [3m(B106, severity: LOW, confidence: MEDIUM)[23m - Possible hardcoded password:
  'password' [More Info](https://bandit.readthedocs.io/en/1.7.4/plugins/b106_hardcoded_password_funcarg.html)

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

---
❌ rules unsuccessful:	21
Your project is still lacking in quality and could do with some improvements.
Use mllint describe with each rule's slug to learn more about what you can do to get the rules to pass and improve the quality of your ML project.

took: 6.8596336s
