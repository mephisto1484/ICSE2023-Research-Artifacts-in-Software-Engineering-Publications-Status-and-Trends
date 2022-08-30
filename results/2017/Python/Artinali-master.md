Linting project at  F:\Python3.8env/data/2017/Artinali-master
No .mllint.yml or pyproject.toml found in project folder, using default configuration
---

🏃 Running - Code Quality (0.00 ms)
🏃 Running - Testing (0.00 ms)
🏃 Running - Version Control (0.00 ms)
🏃 Running - Dependency Management (0.00 ms)
🏃 Running - Continuous Integration (CI) (0.00 ms)
🏃 Running - Version Control - Git (0.00 ms)
⏳ Waiting - Version Control (0.00 ms)
✔️ Done - Testing (0.00 ms)
✔️ Done - Dependency Management (0.50 ms)
🏃 Running - Version Control - DVC (0.50 ms)
✔️ Done - Version Control - DVC (0.56 ms)
🏃 Running - Code Quality - Pylint (0.00 ms)
🏃 Running - Code Quality - Mypy (0.00 ms)
🏃 Running - Code Quality - Black (0.00 ms)
🏃 Running - Code Quality - isort (0.00 ms)
🏃 Running - Code Quality - Bandit (0.00 ms)
⏳ Waiting - Code Quality (5 ms)
✔️ Done - Version Control - Git (45 ms)
🏃 Running - Version Control (45 ms)
✔️ Done - Version Control (45 ms)
✔️ Done - Continuous Integration (CI) (179 ms)
✔️ Done - Code Quality - isort (818 ms)
✔️ Done - Code Quality - Mypy (2.07 s)
✔️ Done - Code Quality - Black (2.13 s)
✔️ Done - Code Quality - Bandit (2.44 s)
✔️ Done - Code Quality - Pylint (4.37 s)
🏃 Running - Code Quality (4.38 s)
✔️ Done - Code Quality (4.38 s)

✔️ All done!

---

1 ML Project Report
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────

┌──────────────────────┬─────────────────────────────────────────┐
│[1mProject[0m               │[1mDetails[0m                                  │
╞══════════════════════╪═════════════════════════════════════════╡
│Date                  │Sat, 20 Aug 2022 20:48:59 +0800          │
├──────────────────────┼─────────────────────────────────────────┤
│Path                  │F:\Python3.8env/data/2017/Artinali-master│
├──────────────────────┼─────────────────────────────────────────┤
│Config                │default                                  │
├──────────────────────┼─────────────────────────────────────────┤
│Default               │Yes                                      │
├──────────────────────┼─────────────────────────────────────────┤
│Number of Python files│6                                        │
├──────────────────────┼─────────────────────────────────────────┤
│Lines of Python code  │1120                                     │
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
1.1.3 Code Quality (code-quality) — [1m23.3[0m%

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
│  ❌  │ 86.6%│     1│Bandit reports no issues with this project      │code-quality/bandit/no-issues                   │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│      │ [3mTotal[23m│      │                                                │                                                │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │ [1m23.3[0m%│      │Code Quality                                    │code-quality                                    │
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

Pylint reported [1m1377[0m issues with your project:
• Artinali-master\IDS-src\DE-IDS.py:19,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:20,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:22,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:24,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:26,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:27,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\DE-IDS.py:28,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\DE-IDS.py:30,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:31,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:32,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:33,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:34,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:35,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:36,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:37,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:38,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:41,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:42,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:43,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:44,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\DE-IDS.py:45,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\DE-IDS.py:46,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\DE-IDS.py:110,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\DE-IDS.py:130,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• Artinali-master\IDS-src\DE-IDS.py:149,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• Artinali-master\IDS-src\DE-IDS.py:154,0 - [3m(C0301)[23m Line too long (116/100)
• Artinali-master\IDS-src\DE-IDS.py:162,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\DE-IDS.py:164,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• Artinali-master\IDS-src\DE-IDS.py:172,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• Artinali-master\IDS-src\DE-IDS.py:184,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• Artinali-master\IDS-src\DE-IDS.py:200,0 - [3m(C0301)[23m Line too long (104/100)
• Artinali-master\IDS-src\DE-IDS.py:231,0 - [3m(C0305)[23m Trailing newlines
• Artinali-master\IDS-src\DE-IDS.py:1,0 - [3m(C0114)[23m Missing module docstring
• Artinali-master\IDS-src\DE-IDS.py:1,0 - [3m(C0103)[23m Module name "DE-IDS" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:6,0 - [3m(C0410)[23m Multiple imports on one line (sys, os)
• Artinali-master\IDS-src\DE-IDS.py:7,0 - [3m(C0410)[23m Multiple imports on one line (shutil, errno)
• Artinali-master\IDS-src\DE-IDS.py:18,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\DE-IDS.py:18,0 - [3m(C0103)[23m Function name "readInputTrace" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(C0103)[23m Constant name "InputTrace1" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(C0103)[23m Constant name "Inv" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(C0103)[23m Constant name "lines1" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(C0103)[23m Constant name "lines2" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(C0103)[23m Constant name "in1" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(C0103)[23m Constant name "in2" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(C0103)[23m Constant name "DataInv" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(C0103)[23m Constant name "trace" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(C0103)[23m Constant name "baskets" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(W0602)[23m Using global for 'InputTrace1' but no assignment is done
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(W0602)[23m Using global for 'Inv' but no assignment is done
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(W0601)[23m Global variable 'lines1' undefined at the module level
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(W0601)[23m Global variable 'lines2' undefined at the module level
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(W0602)[23m Using global for 'in1' but no assignment is done
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(W0602)[23m Using global for 'in2' but no assignment is done
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(W0602)[23m Using global for 'DataInv' but no assignment is done
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(W0602)[23m Using global for 'trace' but no assignment is done
• Artinali-master\IDS-src\DE-IDS.py:19,2 - [3m(W0602)[23m Using global for 'baskets' but no assignment is done
• Artinali-master\IDS-src\DE-IDS.py:20,2 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:20,5 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\DE-IDS.py:20,5 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\DE-IDS.py:22,11 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\DE-IDS.py:22,11 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\DE-IDS.py:26,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:30,9 - [3m(R1721)[23m Unnecessary use of a comprehension, use list(split_seq(lines1,
  '::::::')) instead.
• Artinali-master\IDS-src\DE-IDS.py:31,2 - [3m(C0103)[23m Variable name "Inv_set" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:34,2 - [3m(C0103)[23m Variable name "Inv_set" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:41,11 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\DE-IDS.py:41,11 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\DE-IDS.py:43,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:20,2 - [3m(W0612)[23m Unused variable 'f'
• Artinali-master\IDS-src\DE-IDS.py:50,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\DE-IDS.py:50,0 - [3m(C0103)[23m Function name "DataEventGrouping" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\DE-IDS.py:50,23 - [3m(W0622)[23m Redefining built-in 'input'
• Artinali-master\IDS-src\DE-IDS.py:65,8 - [3m(W0622)[23m Redefining built-in 'next'
• Artinali-master\IDS-src\DE-IDS.py:51,4 - [3m(C0103)[23m Variable name "MergedLine" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\DE-IDS.py:52,4 - [3m(C0103)[23m Variable name "Eindex" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:54,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:62,8 - [3m(C0103)[23m Variable name "MergedLine" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\DE-IDS.py:66,4 - [3m(C0103)[23m Variable name "MergedLine" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\DE-IDS.py:55,8 - [3m(W0612)[23m Unused variable 'uline'
• Artinali-master\IDS-src\DE-IDS.py:74,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\DE-IDS.py:85,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\DE-IDS.py:85,14 - [3m(C0103)[23m Argument name "a" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:85,16 - [3m(C0103)[23m Argument name "b" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:88,4 - [3m(C0103)[23m Variable name "c" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:96,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:96,12 - [3m(C0103)[23m Variable name "p" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:97,12 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:103,4 - [3m(C0103)[23m Variable name "c" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:109,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\DE-IDS.py:109,0 - [3m(C0103)[23m Function name "AlarmAbnormality" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\DE-IDS.py:109,0 - [3m(R0914)[23m Too many local variables (34/15)
• Artinali-master\IDS-src\DE-IDS.py:112,4 - [3m(C0103)[23m Variable name "DataInv" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:113,4 - [3m(C0103)[23m Variable name "Coincident" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\DE-IDS.py:114,4 - [3m(C0103)[23m Variable name "DataInvClass" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\DE-IDS.py:115,13 - [3m(R1721)[23m Unnecessary use of a comprehension, use list(split_seq(in2,
  ':::')) instead.
• Artinali-master\IDS-src\DE-IDS.py:116,4 - [3m(C0103)[23m Variable name "Con_abnormality" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\DE-IDS.py:119,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:124,8 - [3m(C0103)[23m Variable name "traceClass" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\DE-IDS.py:125,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:125,12 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:127,12 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:127,16 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:141,28 - [3m(C0103)[23m Variable name "p" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:163,36 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:163,40 - [3m(C0103)[23m Variable name "s" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:165,48 - [3m(C0103)[23m Variable name "t" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:119,4 - [3m(R1702)[23m Too many nested blocks (13/5)
• Artinali-master\IDS-src\DE-IDS.py:186,21 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(abs_abnormality, '&&')) instead.
• Artinali-master\IDS-src\DE-IDS.py:119,4 - [3m(R1702)[23m Too many nested blocks (7/5)
• Artinali-master\IDS-src\DE-IDS.py:188,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:197,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:197,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:211,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\DE-IDS.py:211,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:212,8 - [3m(C0103)[23m Variable name "ABnumber" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:213,8 - [3m(C0103)[23m Variable name "ABnumber" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:214,8 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\DE-IDS.py:214,12 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\DE-IDS.py:215,31 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\IDS-src\DE-IDS.py:216,32 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\IDS-src\DE-IDS.py:109,0 - [3m(R0912)[23m Too many branches (20/12)
• Artinali-master\IDS-src\DE-IDS.py:109,0 - [3m(R0915)[23m Too many statements (88/50)
• Artinali-master\IDS-src\DE-IDS.py:214,12 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\DE-IDS.py:166,48 - [3m(W0612)[23m Unused variable 'string0'
• Artinali-master\IDS-src\DE-IDS.py:220,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\DE-IDS.py:220,9 - [3m(C0103)[23m Argument name "InputTrace" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\DE-IDS.py:220,9 - [3m(W0621)[23m Redefining name 'InputTrace' from outer scope (line 13)
• Artinali-master\IDS-src\DE-IDS.py:220,9 - [3m(W0613)[23m Unused argument 'InputTrace'
• Artinali-master\IDS-src\DE-IDS.py:7,0 - [3m(W0611)[23m Unused import shutil
• Artinali-master\IDS-src\DE-IDS.py:7,0 - [3m(W0611)[23m Unused import errno
• Artinali-master\IDS-src\DE-IDS.py:8,0 - [3m(W0611)[23m Unused import subprocess
• Artinali-master\IDS-src\Duration-IDS.py:4,0 - [3m(C0301)[23m Line too long (115/100)
• Artinali-master\IDS-src\Duration-IDS.py:18,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\Duration-IDS.py:27,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\Duration-IDS.py:28,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\Duration-IDS.py:29,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\Duration-IDS.py:30,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\Duration-IDS.py:31,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\Duration-IDS.py:32,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\Duration-IDS.py:33,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\Duration-IDS.py:34,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\Duration-IDS.py:35,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\Duration-IDS.py:39,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\Duration-IDS.py:70,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\Duration-IDS.py:92,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\Duration-IDS.py:118,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\Duration-IDS.py:148,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 4
• Artinali-master\IDS-src\Duration-IDS.py:150,0 - [3m(C0305)[23m Trailing newlines
• Artinali-master\IDS-src\Duration-IDS.py:1,0 - [3m(C0114)[23m Missing module docstring
• Artinali-master\IDS-src\Duration-IDS.py:1,0 - [3m(C0103)[23m Module name "Duration-IDS" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:5,0 - [3m(C0410)[23m Multiple imports on one line (sys, os)
• Artinali-master\IDS-src\Duration-IDS.py:6,0 - [3m(C0410)[23m Multiple imports on one line (shutil, errno)
• Artinali-master\IDS-src\Duration-IDS.py:11,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\Duration-IDS.py:11,0 - [3m(C0103)[23m Function name "readInputTrace" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(C0103)[23m Constant name "InputTrace" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(C0103)[23m Constant name "Inv" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(C0103)[23m Constant name "lines1" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(C0103)[23m Constant name "lines2" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(C0103)[23m Constant name "in1" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(C0103)[23m Constant name "in2" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(C0103)[23m Constant name "DataInv" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(C0103)[23m Constant name "trace" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(C0103)[23m Constant name "baskets" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(W0602)[23m Using global for 'InputTrace' but no assignment is done
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(W0602)[23m Using global for 'Inv' but no assignment is done
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(W0601)[23m Global variable 'lines1' undefined at the module level
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(W0601)[23m Global variable 'lines2' undefined at the module level
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(W0602)[23m Using global for 'in1' but no assignment is done
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(W0602)[23m Using global for 'in2' but no assignment is done
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(W0602)[23m Using global for 'DataInv' but no assignment is done
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(W0602)[23m Using global for 'trace' but no assignment is done
• Artinali-master\IDS-src\Duration-IDS.py:12,4 - [3m(W0602)[23m Using global for 'baskets' but no assignment is done
• Artinali-master\IDS-src\Duration-IDS.py:13,4 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\Duration-IDS.py:13,8 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\Duration-IDS.py:13,8 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\Duration-IDS.py:15,13 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\Duration-IDS.py:15,13 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\Duration-IDS.py:20,13 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\Duration-IDS.py:20,13 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\Duration-IDS.py:13,4 - [3m(W0612)[23m Unused variable 'f'
• Artinali-master\IDS-src\Duration-IDS.py:26,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\Duration-IDS.py:38,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\Duration-IDS.py:38,0 - [3m(C0103)[23m Function name "AlarmAbnormality" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\Duration-IDS.py:40,4 - [3m(C0103)[23m Variable name "Duration" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:41,13 - [3m(R1721)[23m Unnecessary use of a comprehension, use list(split_seq(in2,
  ':::')) instead.
• Artinali-master\IDS-src\Duration-IDS.py:43,4 - [3m(C0103)[23m Variable name "Duration" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:44,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\IDS-src\Duration-IDS.py:47,8 - [3m(C0103)[23m Variable name "DELTA" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:49,8 - [3m(C0103)[23m Variable name "DELTA" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:52,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\IDS-src\Duration-IDS.py:54,12 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\IDS-src\Duration-IDS.py:44,4 - [3m(R1702)[23m Too many nested blocks (6/5)
• Artinali-master\IDS-src\Duration-IDS.py:77,17 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(abnormality, '&&')) instead.
• Artinali-master\IDS-src\Duration-IDS.py:80,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\Duration-IDS.py:85,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\IDS-src\Duration-IDS.py:85,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\Duration-IDS.py:94,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\IDS-src\Duration-IDS.py:94,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\Duration-IDS.py:95,8 - [3m(C0103)[23m Variable name "ABnumber" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:96,8 - [3m(C0103)[23m Variable name "ABnumber" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\Duration-IDS.py:97,8 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\Duration-IDS.py:97,12 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\Duration-IDS.py:98,31 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\IDS-src\Duration-IDS.py:99,32 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\IDS-src\Duration-IDS.py:38,0 - [3m(R0912)[23m Too many branches (13/12)
• Artinali-master\IDS-src\Duration-IDS.py:97,12 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\Duration-IDS.py:104,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\Duration-IDS.py:104,0 - [3m(C0103)[23m Function name "GroupEvents" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\Duration-IDS.py:105,4 - [3m(C0103)[23m Variable name "C" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\Duration-IDS.py:106,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\IDS-src\Duration-IDS.py:109,12 - [3m(C0103)[23m Variable name "C" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\Duration-IDS.py:113,16 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\IDS-src\Duration-IDS.py:119,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\Duration-IDS.py:119,0 - [3m(C0103)[23m Function name "CalDuration" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\Duration-IDS.py:123,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\IDS-src\Duration-IDS.py:124,12 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\Duration-IDS.py:131,24 - [3m(C0103)[23m Variable name "d" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\Duration-IDS.py:121,4 - [3m(W0612)[23m Unused variable 'num_group_in_basket'
• Artinali-master\IDS-src\Duration-IDS.py:144,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\Duration-IDS.py:144,9 - [3m(C0103)[23m Argument name "InputTrace" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\Duration-IDS.py:144,9 - [3m(W0621)[23m Redefining name 'InputTrace' from outer scope (line 9)
• Artinali-master\IDS-src\Duration-IDS.py:144,9 - [3m(W0613)[23m Unused argument 'InputTrace'
• Artinali-master\IDS-src\Duration-IDS.py:6,0 - [3m(W0611)[23m Unused import shutil
• Artinali-master\IDS-src\Duration-IDS.py:6,0 - [3m(W0611)[23m Unused import errno
• Artinali-master\IDS-src\Duration-IDS.py:7,0 - [3m(W0611)[23m Unused import subprocess
• Artinali-master\IDS-src\TE-IDS.py:2,0 - [3m(C0301)[23m Line too long (112/100)
• Artinali-master\IDS-src\TE-IDS.py:23,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\TE-IDS.py:39,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:40,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:41,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\TE-IDS.py:42,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\TE-IDS.py:43,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\TE-IDS.py:44,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\TE-IDS.py:45,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\TE-IDS.py:46,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\TE-IDS.py:47,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\TE-IDS.py:51,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\TE-IDS.py:83,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\TE-IDS.py:84,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• Artinali-master\IDS-src\TE-IDS.py:88,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• Artinali-master\IDS-src\TE-IDS.py:89,0 - [3m(W0311)[23m Bad indentation. Found 23 spaces, expected 24
• Artinali-master\IDS-src\TE-IDS.py:89,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• Artinali-master\IDS-src\TE-IDS.py:91,0 - [3m(W0311)[23m Bad indentation. Found 23 spaces, expected 24
• Artinali-master\IDS-src\TE-IDS.py:92,0 - [3m(W0311)[23m Bad indentation. Found 27 spaces, expected 28
• Artinali-master\IDS-src\TE-IDS.py:93,0 - [3m(W0311)[23m Bad indentation. Found 27 spaces, expected 28
• Artinali-master\IDS-src\TE-IDS.py:105,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\TE-IDS.py:119,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\TE-IDS.py:184,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:185,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:187,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:188,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:189,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:190,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:193,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\TE-IDS.py:194,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\TE-IDS.py:195,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:197,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:216,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:218,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:219,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:220,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:221,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:222,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:223,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:224,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\IDS-src\TE-IDS.py:226,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\IDS-src\TE-IDS.py:227,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\IDS-src\TE-IDS.py:230,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\IDS-src\TE-IDS.py:231,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\IDS-src\TE-IDS.py:232,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:234,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:240,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:241,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:242,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:243,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:244,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:245,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:246,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:247,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:248,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:249,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:250,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:251,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:252,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:253,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:254,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:255,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:256,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:257,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:258,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:259,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:260,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\IDS-src\TE-IDS.py:265,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\IDS-src\TE-IDS.py:272,0 - [3m(C0305)[23m Trailing newlines
• Artinali-master\IDS-src\TE-IDS.py:1,0 - [3m(C0114)[23m Missing module docstring
• Artinali-master\IDS-src\TE-IDS.py:1,0 - [3m(C0103)[23m Module name "TE-IDS" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:6,0 - [3m(C0410)[23m Multiple imports on one line (sys, os)
• Artinali-master\IDS-src\TE-IDS.py:7,0 - [3m(C0410)[23m Multiple imports on one line (shutil, errno)
• Artinali-master\IDS-src\TE-IDS.py:12,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\TE-IDS.py:12,0 - [3m(C0103)[23m Function name "readInputTrace" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(C0103)[23m Constant name "InputTrace" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(C0103)[23m Constant name "Inv" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(C0103)[23m Constant name "lines1" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(C0103)[23m Constant name "lines2" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(C0103)[23m Constant name "in1" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(C0103)[23m Constant name "in2" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(C0103)[23m Constant name "DataInv" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(C0103)[23m Constant name "trace" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(C0103)[23m Constant name "baskets" doesn't conform to UPPER_CASE naming style
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(W0602)[23m Using global for 'InputTrace' but no assignment is done
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(W0602)[23m Using global for 'Inv' but no assignment is done
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(W0601)[23m Global variable 'lines1' undefined at the module level
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(W0601)[23m Global variable 'lines2' undefined at the module level
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(W0602)[23m Using global for 'in1' but no assignment is done
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(W0602)[23m Using global for 'in2' but no assignment is done
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(W0602)[23m Using global for 'DataInv' but no assignment is done
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(W0602)[23m Using global for 'trace' but no assignment is done
• Artinali-master\IDS-src\TE-IDS.py:13,4 - [3m(W0602)[23m Using global for 'baskets' but no assignment is done
• Artinali-master\IDS-src\TE-IDS.py:14,4 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:14,7 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\TE-IDS.py:14,7 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\TE-IDS.py:16,13 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\TE-IDS.py:16,13 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\TE-IDS.py:27,13 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\TE-IDS.py:27,13 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\TE-IDS.py:14,4 - [3m(W0612)[23m Unused variable 'f'
• Artinali-master\IDS-src\TE-IDS.py:38,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\TE-IDS.py:50,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\TE-IDS.py:50,0 - [3m(C0103)[23m Function name "AlarmAbnormality" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\TE-IDS.py:50,0 - [3m(R0914)[23m Too many local variables (23/15)
• Artinali-master\IDS-src\TE-IDS.py:54,11 - [3m(R1721)[23m Unnecessary use of a comprehension, use list(split_seq(in1,
  '::::::')) instead.
• Artinali-master\IDS-src\TE-IDS.py:55,4 - [3m(C0103)[23m Variable name "TimeInv" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:56,4 - [3m(C0103)[23m Variable name "Pair_set" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:57,4 - [3m(C0103)[23m Variable name "Freq_set" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:59,4 - [3m(C0103)[23m Variable name "Pair_set" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:61,4 - [3m(C0103)[23m Variable name "TimeInv" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:66,13 - [3m(R1721)[23m Unnecessary use of a comprehension, use list(split_seq(in2, ':::'))
  instead.
• Artinali-master\IDS-src\TE-IDS.py:67,4 - [3m(C0103)[23m Variable name "Con_abnormality" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\TE-IDS.py:71,4 - [3m(C0103)[23m Variable name "TimeInv" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:73,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\TE-IDS.py:78,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\TE-IDS.py:78,12 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:80,12 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\TE-IDS.py:80,16 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:73,4 - [3m(R1702)[23m Too many nested blocks (6/5)
• Artinali-master\IDS-src\TE-IDS.py:109,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\TE-IDS.py:120,17 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(abnormality, '&&')) instead.
• Artinali-master\IDS-src\TE-IDS.py:121,17 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(missing_pair, '&&')) instead.
• Artinali-master\IDS-src\TE-IDS.py:122,19 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(anomalous_pair, '&&')) instead.
• Artinali-master\IDS-src\TE-IDS.py:124,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:128,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:132,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:140,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\TE-IDS.py:140,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:148,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\TE-IDS.py:148,8 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:154,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\TE-IDS.py:154,8 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:160,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\TE-IDS.py:160,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:161,8 - [3m(C0103)[23m Variable name "ABnumber" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:162,8 - [3m(C0103)[23m Variable name "ABnumber" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:163,8 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:163,12 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\TE-IDS.py:164,31 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\IDS-src\TE-IDS.py:165,32 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\IDS-src\TE-IDS.py:167,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\TE-IDS.py:167,8 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:168,8 - [3m(C0103)[23m Variable name "ABnumber" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:169,8 - [3m(C0103)[23m Variable name "ABnumber" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:163,12 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\TE-IDS.py:170,8 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:170,12 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\TE-IDS.py:171,31 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\IDS-src\TE-IDS.py:172,32 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\IDS-src\TE-IDS.py:175,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• Artinali-master\IDS-src\TE-IDS.py:175,8 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:176,8 - [3m(C0103)[23m Variable name "ABnumber" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:177,8 - [3m(C0103)[23m Variable name "ABnumber" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:170,12 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\TE-IDS.py:178,8 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:178,12 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\IDS-src\TE-IDS.py:179,31 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\IDS-src\TE-IDS.py:180,32 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\IDS-src\TE-IDS.py:50,0 - [3m(R0912)[23m Too many branches (25/12)
• Artinali-master\IDS-src\TE-IDS.py:50,0 - [3m(R0915)[23m Too many statements (95/50)
• Artinali-master\IDS-src\TE-IDS.py:178,12 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\IDS-src\TE-IDS.py:57,4 - [3m(W0612)[23m Unused variable 'Freq_set'
• Artinali-master\IDS-src\TE-IDS.py:67,4 - [3m(W0612)[23m Unused variable 'Con_abnormality'
• Artinali-master\IDS-src\TE-IDS.py:79,12 - [3m(W0612)[23m Unused variable 'flag3'
• Artinali-master\IDS-src\TE-IDS.py:183,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\TE-IDS.py:183,0 - [3m(C0103)[23m Function name "immidiateEpairing" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\TE-IDS.py:185,2 - [3m(C0103)[23m Variable name "ImrelativeTime" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\TE-IDS.py:187,2 - [3m(C0103)[23m Variable name "Impaired" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:188,2 - [3m(C0103)[23m Variable name "ImETpaired" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\TE-IDS.py:193,4 - [3m(E1137)[23m 'ImrelativeTime' does not support item assignment
• Artinali-master\IDS-src\TE-IDS.py:194,4 - [3m(E1137)[23m 'Impaired' does not support item assignment
• Artinali-master\IDS-src\TE-IDS.py:195,2 - [3m(C0103)[23m Variable name "ImETpaired" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\TE-IDS.py:195,14 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• Artinali-master\IDS-src\TE-IDS.py:199,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\TE-IDS.py:200,4 - [3m(C0103)[23m Variable name "Time" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:210,10 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• Artinali-master\IDS-src\TE-IDS.py:215,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\TE-IDS.py:215,0 - [3m(C0103)[23m Function name "EventPairing" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\TE-IDS.py:220,2 - [3m(C0103)[23m Variable name "relativeTime" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\TE-IDS.py:221,2 - [3m(C0103)[23m Variable name "ETpaired" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:232,2 - [3m(C0103)[23m Variable name "ETpaired" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:232,12 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• Artinali-master\IDS-src\TE-IDS.py:218,2 - [3m(W0612)[23m Unused variable 'numofpaires'
• Artinali-master\IDS-src\TE-IDS.py:237,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\TE-IDS.py:237,0 - [3m(C0103)[23m Function name "CalculateRelTime" doesn't conform to snake_case
  naming style
• Artinali-master\IDS-src\TE-IDS.py:255,2 - [3m(W0622)[23m Redefining built-in 'min'
• Artinali-master\IDS-src\TE-IDS.py:240,2 - [3m(C0103)[23m Variable name "s" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:243,2 - [3m(C0103)[23m Variable name "s" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:245,2 - [3m(C0103)[23m Variable name "sinSec" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:247,2 - [3m(C0103)[23m Variable name "e" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:249,2 - [3m(C0103)[23m Variable name "e" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:250,2 - [3m(C0103)[23m Variable name "einSec" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:252,2 - [3m(C0103)[23m Variable name "Delta" doesn't conform to snake_case naming style
• Artinali-master\IDS-src\TE-IDS.py:257,2 - [3m(W0612)[23m Unused variable 'microsec'
• Artinali-master\IDS-src\TE-IDS.py:263,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\IDS-src\TE-IDS.py:263,9 - [3m(C0103)[23m Argument name "InputTrace" doesn't conform to snake_case naming
  style
• Artinali-master\IDS-src\TE-IDS.py:263,9 - [3m(W0621)[23m Redefining name 'InputTrace' from outer scope (line 10)
• Artinali-master\IDS-src\TE-IDS.py:263,9 - [3m(W0613)[23m Unused argument 'InputTrace'
• Artinali-master\IDS-src\TE-IDS.py:7,0 - [3m(W0611)[23m Unused import shutil
• Artinali-master\IDS-src\TE-IDS.py:7,0 - [3m(W0611)[23m Unused import errno
• Artinali-master\IDS-src\TE-IDS.py:8,0 - [3m(W0611)[23m Unused import subprocess
• Artinali-master\Invariant-Inf\DEMiner.py:2,0 - [3m(C0301)[23m Line too long (125/100)
• Artinali-master\Invariant-Inf\DEMiner.py:3,0 - [3m(C0301)[23m Line too long (126/100)
• Artinali-master\Invariant-Inf\DEMiner.py:4,0 - [3m(C0301)[23m Line too long (126/100)
• Artinali-master\Invariant-Inf\DEMiner.py:18,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:19,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:20,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:21,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:22,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:23,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:24,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:25,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:41,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:42,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:43,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:44,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:46,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:49,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:50,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:51,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:53,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:55,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:57,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:58,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:59,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:60,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:61,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:62,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:63,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:64,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:65,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:67,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:68,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:69,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:70,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:73,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:74,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:75,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:77,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:79,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:80,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:81,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:82,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:83,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:85,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:86,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:87,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:89,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:90,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:92,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:93,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:94,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:96,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:97,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:98,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:99,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:100,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:102,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:103,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:104,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:105,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:106,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:107,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:108,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:109,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:110,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:111,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:113,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:114,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:121,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:122,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:123,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:124,0 - [3m(W0311)[23m Bad indentation. Found 14 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:125,0 - [3m(W0311)[23m Bad indentation. Found 18 spaces, expected 20
• Artinali-master\Invariant-Inf\DEMiner.py:126,0 - [3m(W0311)[23m Bad indentation. Found 22 spaces, expected 24
• Artinali-master\Invariant-Inf\DEMiner.py:127,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:128,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:129,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:130,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:131,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:132,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:133,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:134,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:135,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:136,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:136,0 - [3m(C0325)[23m Unnecessary parens after 'return' keyword
• Artinali-master\Invariant-Inf\DEMiner.py:140,0 - [3m(C0301)[23m Line too long (166/100)
• Artinali-master\Invariant-Inf\DEMiner.py:141,0 - [3m(C0301)[23m Line too long (129/100)
• Artinali-master\Invariant-Inf\DEMiner.py:154,0 - [3m(C0301)[23m Line too long (101/100)
• Artinali-master\Invariant-Inf\DEMiner.py:155,0 - [3m(C0301)[23m Line too long (105/100)
• Artinali-master\Invariant-Inf\DEMiner.py:156,0 - [3m(C0301)[23m Line too long (351/100)
• Artinali-master\Invariant-Inf\DEMiner.py:157,0 - [3m(C0301)[23m Line too long (349/100)
• Artinali-master\Invariant-Inf\DEMiner.py:198,0 - [3m(C0301)[23m Line too long (119/100)
• Artinali-master\Invariant-Inf\DEMiner.py:199,0 - [3m(C0301)[23m Line too long (125/100)
• Artinali-master\Invariant-Inf\DEMiner.py:200,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:201,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:202,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:203,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:204,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:205,0 - [3m(W0311)[23m Bad indentation. Found 14 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:206,0 - [3m(W0311)[23m Bad indentation. Found 14 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:207,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:208,0 - [3m(W0311)[23m Bad indentation. Found 14 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:209,0 - [3m(W0311)[23m Bad indentation. Found 14 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:210,0 - [3m(W0311)[23m Bad indentation. Found 18 spaces, expected 20
• Artinali-master\Invariant-Inf\DEMiner.py:211,0 - [3m(W0311)[23m Bad indentation. Found 22 spaces, expected 24
• Artinali-master\Invariant-Inf\DEMiner.py:212,0 - [3m(W0311)[23m Bad indentation. Found 14 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:214,0 - [3m(W0311)[23m Bad indentation. Found 14 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:216,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:217,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:218,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:219,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:220,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:223,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:224,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:225,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:229,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:230,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:231,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:232,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:233,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:234,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:235,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:236,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:240,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:241,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:242,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:243,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:244,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:245,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:246,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:247,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:248,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:249,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:251,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:252,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:253,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:254,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:255,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:256,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:257,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:258,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:260,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:261,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:263,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:264,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:266,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:270,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:271,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:273,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:274,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:275,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:276,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:277,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:279,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:281,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:282,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:284,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:286,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:287,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:288,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:289,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:290,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:291,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:292,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:293,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:297,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:300,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:301,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:302,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:303,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:304,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:305,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:306,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:308,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:309,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:311,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:313,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:314,0 - [3m(C0301)[23m Line too long (128/100)
• Artinali-master\Invariant-Inf\DEMiner.py:315,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:316,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:317,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:319,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:320,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:322,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:323,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:325,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:326,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:327,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:329,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:330,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:331,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:332,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:333,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:334,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:335,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:336,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:337,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:338,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:339,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:340,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\DEMiner.py:341,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:344,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:346,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:349,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:351,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:359,0 - [3m(C0301)[23m Line too long (154/100)
• Artinali-master\Invariant-Inf\DEMiner.py:390,0 - [3m(C0325)[23m Unnecessary parens after 'return' keyword
• Artinali-master\Invariant-Inf\DEMiner.py:396,0 - [3m(C0301)[23m Line too long (123/100)
• Artinali-master\Invariant-Inf\DEMiner.py:402,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:408,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:409,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:410,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:411,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:412,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:413,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Artinali-master\Invariant-Inf\DEMiner.py:414,0 - [3m(W0311)[23m Bad indentation. Found 3 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:415,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:416,79 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:416,0 - [3m(W0311)[23m Bad indentation. Found 3 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:417,0 - [3m(W0311)[23m Bad indentation. Found 3 spaces, expected 12
• Artinali-master\Invariant-Inf\DEMiner.py:418,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DEMiner.py:423,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DEMiner.py:435,0 - [3m(C0305)[23m Trailing newlines
• Artinali-master\Invariant-Inf\DEMiner.py:1,0 - [3m(C0114)[23m Missing module docstring
• Artinali-master\Invariant-Inf\DEMiner.py:1,0 - [3m(C0103)[23m Module name "DEMiner" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:6,0 - [3m(C0410)[23m Multiple imports on one line (sys, os)
• Artinali-master\Invariant-Inf\DEMiner.py:7,0 - [3m(C0410)[23m Multiple imports on one line (shutil, errno)
• Artinali-master\Invariant-Inf\DEMiner.py:16,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:16,0 - [3m(C0103)[23m Function name "checkInputTrace" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:18,2 - [3m(C0103)[23m Constant name "cOpt" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:18,2 - [3m(W0602)[23m Using global for 'cOpt' but no assignment is done
• Artinali-master\Invariant-Inf\DEMiner.py:19,28 - [3m(E0602)[23m Undefined variable 'options'
• Artinali-master\Invariant-Inf\DEMiner.py:22,2 - [3m(W0702)[23m No exception type(s) specified
• Artinali-master\Invariant-Inf\DEMiner.py:21,4 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:21,8 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\DEMiner.py:23,10 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• Artinali-master\Invariant-Inf\DEMiner.py:24,11 - [3m(E0602)[23m Undefined variable 'options'
• Artinali-master\Invariant-Inf\DEMiner.py:25,2 - [3m(R1722)[23m Consider using sys.exit()
• Artinali-master\Invariant-Inf\DEMiner.py:21,8 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\DEMiner.py:21,4 - [3m(W0612)[23m Unused variable 'f'
• Artinali-master\Invariant-Inf\DEMiner.py:27,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:40,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:40,0 - [3m(C0103)[23m Function name "readInputTrace" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:40,0 - [3m(R0914)[23m Too many local variables (16/15)
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(C0103)[23m Constant name "InputTrace" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(C0103)[23m Constant name "classes" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(C0103)[23m Constant name "numofclass" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(C0103)[23m Constant name "Var_names" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(C0103)[23m Constant name "s" doesn't conform to UPPER_CASE naming style
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(C0103)[23m Constant name "Lines" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(C0103)[23m Constant name "lines" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(C0103)[23m Constant name "baskets" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(C0103)[23m Constant name "newbasket" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0602)[23m Using global for 'InputTrace' but no assignment is done
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0602)[23m Using global for 'C' but no assignment is done
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0602)[23m Using global for 'classes' but no assignment is done
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0602)[23m Using global for 'numofclass' but no assignment is done
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0602)[23m Using global for 'Var_names' but no assignment is done
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0602)[23m Using global for 's' but no assignment is done
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0602)[23m Using global for 'Lines' but no assignment is done
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0601)[23m Global variable 'lines' undefined at the module level
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0601)[23m Global variable 'baskets' undefined at the module level
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0601)[23m Global variable 'newbasket' undefined at the module level
• Artinali-master\Invariant-Inf\DEMiner.py:41,2 - [3m(W0601)[23m Global variable 'VN' undefined at the module level
• Artinali-master\Invariant-Inf\DEMiner.py:42,2 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:42,5 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\DEMiner.py:42,5 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\DEMiner.py:44,10 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\DEMiner.py:44,10 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\DEMiner.py:50,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:57,11 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(lines, ':::')) instead.
• Artinali-master\Invariant-Inf\DEMiner.py:58,2 - [3m(C0103)[23m Variable name "DEinvariants" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:60,2 - [3m(C0103)[23m Variable name "SNames" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:63,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:73,2 - [3m(C0103)[23m Variable name "DE" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:75,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:77,17 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(newbasket[i], '&&')) instead.
• Artinali-master\Invariant-Inf\DEMiner.py:97,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:97,6 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:98,4 - [3m(C0103)[23m Variable name "DEnumber" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:99,4 - [3m(C0103)[23m Variable name "DEnumber" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:100,4 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:100,8 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\DEMiner.py:102,28 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\Invariant-Inf\DEMiner.py:102,46 - [3m(E1136)[23m Value 'intersected_inv' is unsubscriptable
• Artinali-master\Invariant-Inf\DEMiner.py:100,8 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\DEMiner.py:104,2 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:104,6 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\DEMiner.py:107,2 - [3m(C0103)[23m Variable name "Coincidence" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:108,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:108,6 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:109,4 - [3m(C0103)[23m Variable name "DEnumber" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:110,4 - [3m(C0103)[23m Variable name "DEnumber" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:104,6 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\DEMiner.py:111,4 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:111,8 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\DEMiner.py:113,28 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\Invariant-Inf\DEMiner.py:113,46 - [3m(E1136)[23m Value 'Coincidence' is unsubscriptable
• Artinali-master\Invariant-Inf\DEMiner.py:111,8 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\DEMiner.py:58,2 - [3m(W0612)[23m Unused variable 'DEinvariants'
• Artinali-master\Invariant-Inf\DEMiner.py:62,2 - [3m(W0612)[23m Unused variable 'temp3'
• Artinali-master\Invariant-Inf\DEMiner.py:94,4 - [3m(W0612)[23m Unused variable 'union_item'
• Artinali-master\Invariant-Inf\DEMiner.py:120,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:120,0 - [3m(C0103)[23m Function name "AttachVariableNames" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:121,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:121,6 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:122,6 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:122,10 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:127,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:133,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:133,6 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:134,6 - [3m(E1137)[23m 'final' does not support item assignment
• Artinali-master\Invariant-Inf\DEMiner.py:134,48 - [3m(E1136)[23m Value 'final' is unsubscriptable
• Artinali-master\Invariant-Inf\DEMiner.py:139,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:139,0 - [3m(C0103)[23m Function name "FindFrequentitemSet" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:139,24 - [3m(C0103)[23m Argument name "A" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:139,26 - [3m(C0103)[23m Argument name "B" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:142,4 - [3m(C0103)[23m Variable name "AA" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:143,4 - [3m(C0103)[23m Variable name "BB" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:145,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:145,8 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:146,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:146,12 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:153,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:153,11 - [3m(C0103)[23m Argument name "a" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:153,13 - [3m(C0103)[23m Argument name "b" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:162,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:162,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:163,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:163,12 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:188,11 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(merged, '&&')) instead.
• Artinali-master\Invariant-Inf\DEMiner.py:189,11 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(shared, '&&')) instead.
• Artinali-master\Invariant-Inf\DEMiner.py:190,10 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(delta, '&&')) instead.
• Artinali-master\Invariant-Inf\DEMiner.py:158,4 - [3m(W0612)[23m Unused variable 'temp'
• Artinali-master\Invariant-Inf\DEMiner.py:197,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:197,14 - [3m(C0103)[23m Argument name "a" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:197,16 - [3m(C0103)[23m Argument name "b" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:200,2 - [3m(C0103)[23m Variable name "c" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:202,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:203,6 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:203,10 - [3m(C0103)[23m Variable name "p" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:209,18 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:210,22 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:206,14 - [3m(W0612)[23m Unused variable 'sign'
• Artinali-master\Invariant-Inf\DEMiner.py:228,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:228,12 - [3m(C0103)[23m Argument name "x" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:229,2 - [3m(R1705)[23m Unnecessary "elif" after "return", remove the leading "el"
  from "elif"
• Artinali-master\Invariant-Inf\DEMiner.py:231,7 - [3m(R0123)[23m Comparison to literal
• Artinali-master\Invariant-Inf\DEMiner.py:239,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:239,0 - [3m(C0103)[23m Function name "ChangeFormat" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:239,0 - [3m(R0914)[23m Too many local variables (28/15)
• Artinali-master\Invariant-Inf\DEMiner.py:239,17 - [3m(W0621)[23m Redefining name 'lines' from outer scope (line 44)
• Artinali-master\Invariant-Inf\DEMiner.py:258,4 - [3m(W0622)[23m Redefining built-in 'next'
• Artinali-master\Invariant-Inf\DEMiner.py:240,2 - [3m(C0103)[23m Constant name "var_name" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:240,2 - [3m(W0601)[23m Global variable 'var_name' undefined at the module level
• Artinali-master\Invariant-Inf\DEMiner.py:241,2 - [3m(C0103)[23m Variable name "MergedLine" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:242,2 - [3m(C0103)[23m Variable name "Eindex" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:246,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:255,4 - [3m(C0103)[23m Variable name "MergedLine" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:260,2 - [3m(C0103)[23m Variable name "MergedLine" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:271,2 - [3m(C0103)[23m Variable name "C" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:276,6 - [3m(C0103)[23m Variable name "numofDataVar" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:279,2 - [3m(C0103)[23m Variable name "C" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:286,2 - [3m(C0103)[23m Variable name "numofDataVariables" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:300,2 - [3m(C0103)[23m Variable name "CLA" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:304,6 - [3m(C0103)[23m Variable name "p" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:305,6 - [3m(C0103)[23m Variable name "CLASSES" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:313,2 - [3m(C0103)[23m Variable name "CLA" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:325,2 - [3m(C0103)[23m Variable name "DEinvariant" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:327,2 - [3m(C0103)[23m Variable name "MergedData" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:329,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:337,8 - [3m(C0103)[23m Variable name "Mergedobj" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:338,8 - [3m(C0103)[23m Variable name "Mergedobj" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:349,4 - [3m(C0103)[23m Variable name "DEinvariant" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:239,0 - [3m(R0912)[23m Too many branches (14/12)
• Artinali-master\Invariant-Inf\DEMiner.py:239,0 - [3m(R0915)[23m Too many statements (64/50)
• Artinali-master\Invariant-Inf\DEMiner.py:247,4 - [3m(W0612)[23m Unused variable 'uline'
• Artinali-master\Invariant-Inf\DEMiner.py:276,6 - [3m(W0612)[23m Unused variable 'numofDataVar'
• Artinali-master\Invariant-Inf\DEMiner.py:282,2 - [3m(W0612)[23m Unused variable 'newlines'
• Artinali-master\Invariant-Inf\DEMiner.py:303,2 - [3m(W0612)[23m Unused variable 'splitted_name'
• Artinali-master\Invariant-Inf\DEMiner.py:326,2 - [3m(W0612)[23m Unused variable 'temp2'
• Artinali-master\Invariant-Inf\DEMiner.py:357,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:357,0 - [3m(C0103)[23m Function name "SplitVariableNames" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DEMiner.py:357,23 - [3m(C0103)[23m Argument name "s" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:368,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:370,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:379,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:379,0 - [3m(C0103)[23m Function name "ExtractNames" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:379,17 - [3m(C0103)[23m Argument name "s" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:387,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:395,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:395,0 - [3m(C0103)[23m Function name "SplitAllNames" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:395,18 - [3m(C0103)[23m Argument name "Lines" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:397,4 - [3m(C0103)[23m Variable name "newLine" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:399,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\DEMiner.py:407,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:407,0 - [3m(C0103)[23m Function name "DataMerging" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:408,1 - [3m(C0103)[23m Variable name "myClass" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DEMiner.py:409,20 - [3m(E0602)[23m Undefined variable 'numofclass'
• Artinali-master\Invariant-Inf\DEMiner.py:411,23 - [3m(E0602)[23m Undefined variable 'classes'
• Artinali-master\Invariant-Inf\DEMiner.py:412,9 - [3m(E0602)[23m Undefined variable 'classes'
• Artinali-master\Invariant-Inf\DEMiner.py:414,10 - [3m(E0602)[23m Undefined variable 'classes'
• Artinali-master\Invariant-Inf\DEMiner.py:421,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DEMiner.py:421,9 - [3m(C0103)[23m Argument name "InputTrace" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DEMiner.py:421,9 - [3m(W0621)[23m Redefining name 'InputTrace' from outer scope (line 12)
• Artinali-master\Invariant-Inf\DEMiner.py:421,9 - [3m(W0613)[23m Unused argument 'InputTrace'
• Artinali-master\Invariant-Inf\DEMiner.py:7,0 - [3m(W0611)[23m Unused import shutil
• Artinali-master\Invariant-Inf\DEMiner.py:7,0 - [3m(W0611)[23m Unused import errno
• Artinali-master\Invariant-Inf\DEMiner.py:8,0 - [3m(W0611)[23m Unused import subprocess
• Artinali-master\Invariant-Inf\DurationMiner.py:2,0 - [3m(C0301)[23m Line too long (113/100)
• Artinali-master\Invariant-Inf\DurationMiner.py:3,0 - [3m(C0301)[23m Line too long (113/100)
• Artinali-master\Invariant-Inf\DurationMiner.py:4,0 - [3m(C0301)[23m Line too long (113/100)
• Artinali-master\Invariant-Inf\DurationMiner.py:15,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:16,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:17,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DurationMiner.py:18,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DurationMiner.py:19,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DurationMiner.py:20,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DurationMiner.py:21,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DurationMiner.py:22,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DurationMiner.py:23,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\DurationMiner.py:28,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:29,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DurationMiner.py:30,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:32,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:33,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:34,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:35,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:36,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:37,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:38,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:39,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DurationMiner.py:40,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DurationMiner.py:41,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\DurationMiner.py:42,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DurationMiner.py:44,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:45,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:46,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:47,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:49,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DurationMiner.py:65,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\DurationMiner.py:119,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:120,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:123,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 4
• Artinali-master\Invariant-Inf\DurationMiner.py:125,0 - [3m(C0305)[23m Trailing newlines
• Artinali-master\Invariant-Inf\DurationMiner.py:1,0 - [3m(C0114)[23m Missing module docstring
• Artinali-master\Invariant-Inf\DurationMiner.py:1,0 - [3m(C0103)[23m Module name "DurationMiner" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:5,0 - [3m(C0410)[23m Multiple imports on one line (sys, os)
• Artinali-master\Invariant-Inf\DurationMiner.py:6,0 - [3m(C0410)[23m Multiple imports on one line (shutil, errno)
• Artinali-master\Invariant-Inf\DurationMiner.py:14,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DurationMiner.py:27,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DurationMiner.py:27,0 - [3m(C0103)[23m Function name "readInputTETrace" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(C0103)[23m Constant name "InputTrace" doesn't conform to
  UPPER_CASE naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(C0103)[23m Constant name "classes" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(C0103)[23m Constant name "numofclass" doesn't conform to
  UPPER_CASE naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(C0103)[23m Constant name "basket" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(C0103)[23m Constant name "ETpaired" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(C0103)[23m Constant name "paired" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(C0103)[23m Constant name "group" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(W0602)[23m Using global for 'InputTrace' but no assignment is done
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(W0602)[23m Using global for 'C' but no assignment is done
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(W0602)[23m Using global for 'classes' but no assignment is done
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(W0602)[23m Using global for 'numofclass' but no assignment is done
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(W0601)[23m Global variable 'basket' undefined at the module level
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(W0602)[23m Using global for 'ETpaired' but no assignment is done
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(W0602)[23m Using global for 'paired' but no assignment is done
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(W0602)[23m Using global for 'FIS' but no assignment is done
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(W0601)[23m Global variable 'group' undefined at the module level
• Artinali-master\Invariant-Inf\DurationMiner.py:28,2 - [3m(W0601)[23m Global variable 'DELTA' undefined at the module level
• Artinali-master\Invariant-Inf\DurationMiner.py:30,10 - [3m(R1732)[23m Consider using 'with' for resource-allocating
  operations
• Artinali-master\Invariant-Inf\DurationMiner.py:30,10 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\DurationMiner.py:34,11 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(lines, ':::')) instead.
• Artinali-master\Invariant-Inf\DurationMiner.py:33,2 - [3m(W0612)[23m Unused variable 'numoflines'
• Artinali-master\Invariant-Inf\DurationMiner.py:51,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DurationMiner.py:51,0 - [3m(C0103)[23m Function name "GroupEvents" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:51,16 - [3m(W0621)[23m Redefining name 'basket' from outer scope (line 36)
• Artinali-master\Invariant-Inf\DurationMiner.py:52,4 - [3m(C0103)[23m Variable name "C" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DurationMiner.py:53,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with
  range and len
• Artinali-master\Invariant-Inf\DurationMiner.py:56,12 - [3m(C0103)[23m Variable name "C" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DurationMiner.py:60,16 - [3m(C0200)[23m Consider using enumerate instead of iterating with
  range and len
• Artinali-master\Invariant-Inf\DurationMiner.py:66,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DurationMiner.py:66,0 - [3m(C0103)[23m Function name "CalDuration" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:66,16 - [3m(W0621)[23m Redefining name 'group' from outer scope (line 40)
• Artinali-master\Invariant-Inf\DurationMiner.py:70,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with
  range and len
• Artinali-master\Invariant-Inf\DurationMiner.py:71,12 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DurationMiner.py:78,24 - [3m(C0103)[23m Variable name "d" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DurationMiner.py:68,4 - [3m(W0612)[23m Unused variable 'num_group_in_basket'
• Artinali-master\Invariant-Inf\DurationMiner.py:88,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DurationMiner.py:88,0 - [3m(C0103)[23m Function name "MergeDurations" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:88,19 - [3m(C0103)[23m Argument name "DELTA" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:88,19 - [3m(W0621)[23m Redefining name 'DELTA' from outer scope (line 37)
• Artinali-master\Invariant-Inf\DurationMiner.py:90,4 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DurationMiner.py:90,7 - [3m(R1732)[23m Consider using 'with' for resource-allocating
  operations
• Artinali-master\Invariant-Inf\DurationMiner.py:90,7 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\DurationMiner.py:91,4 - [3m(C0103)[23m Variable name "FIS" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:92,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DurationMiner.py:94,4 - [3m(C0103)[23m Variable name "FIS" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:95,4 - [3m(C0103)[23m Variable name "DurationInv" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:96,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with
  range and len
• Artinali-master\Invariant-Inf\DurationMiner.py:96,8 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DurationMiner.py:97,8 - [3m(C0103)[23m Variable name "MergeDur" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:98,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with
  range and len
• Artinali-master\Invariant-Inf\DurationMiner.py:101,16 - [3m(C0103)[23m Variable name "MergeDur" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:102,8 - [3m(C0103)[23m Variable name "MergeDur" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:103,8 - [3m(C0103)[23m Variable name "MergeDur" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:105,8 - [3m(C0103)[23m Variable name "TDnumber" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:107,8 - [3m(C0103)[23m Variable name "TDnumber" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:109,8 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\DurationMiner.py:109,12 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\DurationMiner.py:111,31 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\Invariant-Inf\DurationMiner.py:109,12 - [3m(R1732)[23m Consider using 'with' for resource-allocating
  operations
• Artinali-master\Invariant-Inf\DurationMiner.py:118,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\DurationMiner.py:118,9 - [3m(C0103)[23m Argument name "InputTrace" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:118,9 - [3m(W0621)[23m Redefining name 'InputTrace' from outer scope (line
  10)
• Artinali-master\Invariant-Inf\DurationMiner.py:119,2 - [3m(W0621)[23m Redefining name 'DELTA' from outer scope (line 37)
• Artinali-master\Invariant-Inf\DurationMiner.py:119,2 - [3m(C0103)[23m Variable name "DELTA" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\DurationMiner.py:118,9 - [3m(W0613)[23m Unused argument 'InputTrace'
• Artinali-master\Invariant-Inf\DurationMiner.py:6,0 - [3m(W0611)[23m Unused import shutil
• Artinali-master\Invariant-Inf\DurationMiner.py:6,0 - [3m(W0611)[23m Unused import errno
• Artinali-master\Invariant-Inf\DurationMiner.py:7,0 - [3m(W0611)[23m Unused import subprocess
• Artinali-master\Invariant-Inf\TEMiner.py:2,0 - [3m(C0301)[23m Line too long (115/100)
• Artinali-master\Invariant-Inf\TEMiner.py:3,0 - [3m(C0301)[23m Line too long (109/100)
• Artinali-master\Invariant-Inf\TEMiner.py:4,0 - [3m(C0301)[23m Line too long (109/100)
• Artinali-master\Invariant-Inf\TEMiner.py:5,0 - [3m(C0301)[23m Line too long (109/100)
• Artinali-master\Invariant-Inf\TEMiner.py:18,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:19,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:20,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:21,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:22,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:23,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:24,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:25,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:26,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:29,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:30,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:31,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:32,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:33,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:34,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:35,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:36,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:37,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:42,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:43,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:45,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:46,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:48,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:49,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:50,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:50,0 - [3m(C0325)[23m Unnecessary parens after 'return' keyword
• Artinali-master\Invariant-Inf\TEMiner.py:51,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:54,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:55,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:56,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:57,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:58,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:59,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:60,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:61,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:62,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:63,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:64,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:65,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:67,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:70,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:71,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:72,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:73,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:74,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:75,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:76,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:78,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:79,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:80,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:81,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:82,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:83,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:86,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:87,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:88,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:89,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:90,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:91,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:92,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:93,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:94,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:95,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:96,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:97,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:98,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:101,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:102,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:103,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:104,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:105,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:106,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:107,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:108,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:109,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:110,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\TEMiner.py:111,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 20
• Artinali-master\Invariant-Inf\TEMiner.py:112,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 20
• Artinali-master\Invariant-Inf\TEMiner.py:113,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 20
• Artinali-master\Invariant-Inf\TEMiner.py:114,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:115,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:116,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:119,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:121,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:122,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:123,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:124,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:125,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:127,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:128,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:131,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:132,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:133,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:134,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:136,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:137,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\TEMiner.py:138,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\TEMiner.py:139,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:140,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:141,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:142,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:143,0 - [3m(C0301)[23m Line too long (110/100)
• Artinali-master\Invariant-Inf\TEMiner.py:143,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:145,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:146,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:147,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:148,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:149,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:150,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:151,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:152,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:153,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:154,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\TEMiner.py:156,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:157,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\TEMiner.py:158,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:159,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:164,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:166,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:167,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:168,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:170,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:171,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:175,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:176,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:178,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:179,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:180,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:182,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:183,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:187,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:188,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:189,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:190,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:191,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:194,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:195,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:196,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:197,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:198,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:199,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:200,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:201,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:202,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:203,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:204,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:205,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:210,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:211,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:212,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:213,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:214,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:215,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:216,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:217,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:218,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:219,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:220,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:222,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:223,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:224,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:225,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:226,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:227,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:228,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:233,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:234,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:235,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:236,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:237,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:238,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:239,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:240,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:241,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:242,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:243,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:244,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:245,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:246,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:247,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:248,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:249,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:250,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:251,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:252,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:253,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:257,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:258,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:259,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:260,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:261,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:262,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:263,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:264,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:265,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:266,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:267,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:268,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\TEMiner.py:269,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 20
• Artinali-master\Invariant-Inf\TEMiner.py:270,0 - [3m(W0311)[23m Bad indentation. Found 14 spaces, expected 24
• Artinali-master\Invariant-Inf\TEMiner.py:271,0 - [3m(W0311)[23m Bad indentation. Found 14 spaces, expected 24
• Artinali-master\Invariant-Inf\TEMiner.py:272,0 - [3m(W0311)[23m Bad indentation. Found 14 spaces, expected 24
• Artinali-master\Invariant-Inf\TEMiner.py:273,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:274,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 16
• Artinali-master\Invariant-Inf\TEMiner.py:275,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 16
• Artinali-master\Invariant-Inf\TEMiner.py:276,0 - [3m(W0311)[23m Bad indentation. Found 10 spaces, expected 16
• Artinali-master\Invariant-Inf\TEMiner.py:277,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:278,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:279,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 16
• Artinali-master\Invariant-Inf\TEMiner.py:280,0 - [3m(W0311)[23m Bad indentation. Found 6 spaces, expected 12
• Artinali-master\Invariant-Inf\TEMiner.py:281,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:282,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:283,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:284,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:285,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:286,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:288,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:289,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:290,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:290,0 - [3m(C0325)[23m Unnecessary parens after 'return' keyword
• Artinali-master\Invariant-Inf\TEMiner.py:303,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:304,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:305,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:306,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:307,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:308,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:309,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:310,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:311,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:312,0 - [3m(C0303)[23m Trailing whitespace
• Artinali-master\Invariant-Inf\TEMiner.py:313,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:314,0 - [3m(W0311)[23m Bad indentation. Found 4 spaces, expected 8
• Artinali-master\Invariant-Inf\TEMiner.py:317,0 - [3m(W0311)[23m Bad indentation. Found 8 spaces, expected 4
• Artinali-master\Invariant-Inf\TEMiner.py:319,0 - [3m(C0305)[23m Trailing newlines
• Artinali-master\Invariant-Inf\TEMiner.py:1,0 - [3m(C0114)[23m Missing module docstring
• Artinali-master\Invariant-Inf\TEMiner.py:1,0 - [3m(C0103)[23m Module name "TEMiner" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:7,0 - [3m(C0410)[23m Multiple imports on one line (sys, os)
• Artinali-master\Invariant-Inf\TEMiner.py:8,0 - [3m(C0410)[23m Multiple imports on one line (shutil, errno)
• Artinali-master\Invariant-Inf\TEMiner.py:16,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:16,0 - [3m(C0103)[23m Function name "checkInputTETrace" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:19,2 - [3m(C0103)[23m Constant name "cOpt" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:19,2 - [3m(W0602)[23m Using global for 'cOpt' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:20,28 - [3m(E0602)[23m Undefined variable 'options'
• Artinali-master\Invariant-Inf\TEMiner.py:23,2 - [3m(W0702)[23m No exception type(s) specified
• Artinali-master\Invariant-Inf\TEMiner.py:22,4 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:22,8 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\TEMiner.py:24,10 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• Artinali-master\Invariant-Inf\TEMiner.py:25,11 - [3m(E0602)[23m Undefined variable 'options'
• Artinali-master\Invariant-Inf\TEMiner.py:26,2 - [3m(R1722)[23m Consider using sys.exit()
• Artinali-master\Invariant-Inf\TEMiner.py:22,8 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\TEMiner.py:22,4 - [3m(W0612)[23m Unused variable 'f'
• Artinali-master\Invariant-Inf\TEMiner.py:28,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:41,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:41,0 - [3m(C0103)[23m Function name "readInputTETrace" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(C0103)[23m Constant name "InputTrace" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(C0103)[23m Constant name "classes" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(C0103)[23m Constant name "numofclass" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(C0103)[23m Constant name "basket" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(C0103)[23m Constant name "ETpaired" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(C0103)[23m Constant name "paired" doesn't conform to UPPER_CASE naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(C0103)[23m Constant name "numofbasket" doesn't conform to UPPER_CASE
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(W0602)[23m Using global for 'InputTrace' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(W0602)[23m Using global for 'C' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(W0602)[23m Using global for 'classes' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(W0602)[23m Using global for 'numofclass' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(W0602)[23m Using global for 'basket' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(W0602)[23m Using global for 'ETpaired' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(W0602)[23m Using global for 'paired' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(W0602)[23m Using global for 'FIS' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(W0602)[23m Using global for 'TE' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:42,2 - [3m(W0602)[23m Using global for 'numofbasket' but no assignment is done
• Artinali-master\Invariant-Inf\TEMiner.py:43,2 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:43,5 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\TEMiner.py:43,5 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\TEMiner.py:45,10 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\TEMiner.py:45,10 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\TEMiner.py:49,11 - [3m(R1721)[23m Unnecessary use of a comprehension, use
  list(split_seq(lines, ':::')) instead.
• Artinali-master\Invariant-Inf\TEMiner.py:43,2 - [3m(W0612)[23m Unused variable 'f'
• Artinali-master\Invariant-Inf\TEMiner.py:46,2 - [3m(W0612)[23m Unused variable 'numoflines'
• Artinali-master\Invariant-Inf\TEMiner.py:53,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:53,0 - [3m(C0103)[23m Function name "calculateTimeInv" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:55,2 - [3m(C0103)[23m Variable name "FIS" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:57,2 - [3m(C0103)[23m Variable name "pairedBasket" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:58,2 - [3m(C0103)[23m Variable name "pairedTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:61,10 - [3m(C0103)[23m Variable name "ETpaired" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:63,4 - [3m(C0103)[23m Variable name "pairedBasket" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:65,4 - [3m(C0103)[23m Variable name "pairedTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:55,2 - [3m(W0612)[23m Unused variable 'FIS'
• Artinali-master\Invariant-Inf\TEMiner.py:69,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:69,0 - [3m(C0103)[23m Function name "calculateImmidiateTimeInv" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:71,2 - [3m(C0103)[23m Variable name "FIS" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:73,2 - [3m(C0103)[23m Variable name "pairedBasket" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:74,2 - [3m(C0103)[23m Variable name "pairedTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:78,10 - [3m(C0103)[23m Variable name "ETpaired" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:80,4 - [3m(C0103)[23m Variable name "pairedBasket" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:82,4 - [3m(C0103)[23m Variable name "pairedTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:71,2 - [3m(W0612)[23m Unused variable 'FIS'
• Artinali-master\Invariant-Inf\TEMiner.py:85,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:85,0 - [3m(C0103)[23m Function name "MergingTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:85,17 - [3m(C0103)[23m Argument name "pairedBasket" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:85,30 - [3m(C0103)[23m Argument name "pairedTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:85,0 - [3m(R0914)[23m Too many local variables (25/15)
• Artinali-master\Invariant-Inf\TEMiner.py:86,2 - [3m(C0103)[23m Variable name "flatPairedTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:88,2 - [3m(C0103)[23m Variable name "FIS" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:89,2 - [3m(C0103)[23m Variable name "FISunion" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:91,4 - [3m(C0103)[23m Variable name "FIS" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:92,4 - [3m(C0103)[23m Variable name "FISunion" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:93,2 - [3m(C0103)[23m Variable name "numofFIS" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:94,2 - [3m(C0103)[23m Variable name "MergedTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:95,2 - [3m(C0103)[23m Variable name "MergedTimeU" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:96,2 - [3m(C0103)[23m Variable name "TEinvariant" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:97,2 - [3m(C0103)[23m Variable name "Frequency" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:98,2 - [3m(C0103)[23m Variable name "TE" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:102,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\TEMiner.py:104,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\TEMiner.py:108,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\TEMiner.py:119,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\TEMiner.py:125,2 - [3m(C0103)[23m Variable name "FISunion" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:127,2 - [3m(C0103)[23m Variable name "FIS_support" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:127,15 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• Artinali-master\Invariant-Inf\TEMiner.py:128,2 - [3m(C0103)[23m Variable name "FIS_support" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:131,2 - [3m(C0103)[23m Variable name "FISunion" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:132,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\TEMiner.py:132,6 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:134,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\TEMiner.py:139,7 - [3m(C1803)[23m 'MergedTime != []' can be simplified to 'MergedTime' as an
  empty sequence is falsey
• Artinali-master\Invariant-Inf\TEMiner.py:140,6 - [3m(C0103)[23m Variable name "MergedTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:143,6 - [3m(C0103)[23m Variable name "TEinvariant" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:85,0 - [3m(R0912)[23m Too many branches (14/12)
• Artinali-master\Invariant-Inf\TEMiner.py:85,0 - [3m(R0915)[23m Too many statements (53/50)
• Artinali-master\Invariant-Inf\TEMiner.py:87,2 - [3m(W0612)[23m Unused variable 'totalnum'
• Artinali-master\Invariant-Inf\TEMiner.py:93,2 - [3m(W0612)[23m Unused variable 'numofFIS'
• Artinali-master\Invariant-Inf\TEMiner.py:163,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:163,0 - [3m(C0103)[23m Function name "WriteInvariantsToFile" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:163,27 - [3m(C0103)[23m Argument name "TE" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:164,2 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:164,6 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\TEMiner.py:166,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\TEMiner.py:166,6 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:167,4 - [3m(C0103)[23m Variable name "TEnumber" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:168,4 - [3m(C0103)[23m Variable name "TEnumber" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:170,27 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\Invariant-Inf\TEMiner.py:164,6 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\TEMiner.py:174,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:174,0 - [3m(C0103)[23m Function name "WriteFrequenciesToFile" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:174,28 - [3m(C0103)[23m Argument name "Frequency" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:175,2 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:175,6 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• Artinali-master\Invariant-Inf\TEMiner.py:178,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\TEMiner.py:178,6 - [3m(C0103)[23m Variable name "n" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:179,4 - [3m(C0103)[23m Variable name "Fnumber" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:180,4 - [3m(C0103)[23m Variable name "Fnumber" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:182,27 - [3m(W0108)[23m Lambda may not be necessary
• Artinali-master\Invariant-Inf\TEMiner.py:175,6 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• Artinali-master\Invariant-Inf\TEMiner.py:186,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:186,11 - [3m(C0103)[23m Argument name "l" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:187,10 - [3m(C0103)[23m Variable name "sl" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:188,7 - [3m(C0123)[23m Use isinstance() rather than type() for a typecheck.
• Artinali-master\Invariant-Inf\TEMiner.py:190,26 - [3m(R1714)[23m Consider merging these comparisons with "in" to "i not in
  ([], '')"
• Artinali-master\Invariant-Inf\TEMiner.py:193,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:193,0 - [3m(C0103)[23m Function name "immidiateEpairing" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:195,2 - [3m(C0103)[23m Variable name "Impaired" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:196,2 - [3m(C0103)[23m Variable name "ImrelativeTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:197,2 - [3m(C0103)[23m Variable name "ImETpaired" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:202,2 - [3m(C0103)[23m Variable name "ImrelativeTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:203,2 - [3m(C0103)[23m Variable name "Impaired" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:204,2 - [3m(C0103)[23m Variable name "ImETpaired" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:204,14 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• Artinali-master\Invariant-Inf\TEMiner.py:209,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:209,0 - [3m(C0103)[23m Function name "EventPairing" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:214,2 - [3m(C0103)[23m Variable name "relativeTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:215,2 - [3m(C0103)[23m Variable name "ETpaired" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:224,2 - [3m(C0103)[23m Variable name "relativeTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:227,2 - [3m(C0103)[23m Variable name "ETpaired" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:227,12 - [3m(C0209)[23m Formatting a regular string which could be a f-string
• Artinali-master\Invariant-Inf\TEMiner.py:230,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:230,0 - [3m(C0103)[23m Function name "CalculateRelTime" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:248,2 - [3m(W0622)[23m Redefining built-in 'min'
• Artinali-master\Invariant-Inf\TEMiner.py:233,2 - [3m(C0103)[23m Variable name "s" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:236,2 - [3m(C0103)[23m Variable name "s" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:238,2 - [3m(C0103)[23m Variable name "sinSec" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:240,2 - [3m(C0103)[23m Variable name "e" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:242,2 - [3m(C0103)[23m Variable name "e" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:243,2 - [3m(C0103)[23m Variable name "einSec" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:245,2 - [3m(C0103)[23m Variable name "Delta" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:250,2 - [3m(W0612)[23m Unused variable 'microsec'
• Artinali-master\Invariant-Inf\TEMiner.py:256,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:256,0 - [3m(C0103)[23m Function name "FindEventFrequency" doesn't conform to
  snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:257,2 - [3m(C0103)[23m Variable name "allFreq" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:258,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\TEMiner.py:258,6 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:260,4 - [3m(C0103)[23m Variable name "equalEvents" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:261,4 - [3m(C0103)[23m Variable name "FreqClass" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:282,4 - [3m(C0103)[23m Variable name "FreqClass" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:285,2 - [3m(C0103)[23m Variable name "allFreq" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:288,2 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and
  len
• Artinali-master\Invariant-Inf\TEMiner.py:288,6 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• Artinali-master\Invariant-Inf\TEMiner.py:292,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:292,12 - [3m(C0103)[23m Argument name "l" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:293,8 - [3m(C0103)[23m Variable name "el" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:294,26 - [3m(E0602)[23m Undefined variable 'collections'
• Artinali-master\Invariant-Inf\TEMiner.py:294,71 - [3m(E0602)[23m Undefined variable 'basestring'
• Artinali-master\Invariant-Inf\TEMiner.py:302,0 - [3m(C0116)[23m Missing function or method docstring
• Artinali-master\Invariant-Inf\TEMiner.py:302,9 - [3m(C0103)[23m Argument name "InputTrace" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:302,9 - [3m(W0621)[23m Redefining name 'InputTrace' from outer scope (line 12)
• Artinali-master\Invariant-Inf\TEMiner.py:305,2 - [3m(C0103)[23m Variable name "pairedBasket" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:305,15 - [3m(C0103)[23m Variable name "pairedTime" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:306,2 - [3m(C0103)[23m Variable name "TE" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:309,2 - [3m(C0103)[23m Variable name "allFreq" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:310,2 - [3m(C0103)[23m Variable name "pairedBasket2" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:310,16 - [3m(C0103)[23m Variable name "pairedTime2" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:313,4 - [3m(C0103)[23m Variable name "te" doesn't conform to snake_case naming
  style
• Artinali-master\Invariant-Inf\TEMiner.py:313,8 - [3m(C0103)[23m Variable name "Frequency" doesn't conform to snake_case
  naming style
• Artinali-master\Invariant-Inf\TEMiner.py:302,9 - [3m(W0613)[23m Unused argument 'InputTrace'
• Artinali-master\Invariant-Inf\TEMiner.py:306,6 - [3m(W0612)[23m Unused variable 'frequency'
• Artinali-master\Invariant-Inf\TEMiner.py:313,4 - [3m(W0612)[23m Unused variable 'te'
• Artinali-master\Invariant-Inf\TEMiner.py:8,0 - [3m(W0611)[23m Unused import shutil
• Artinali-master\Invariant-Inf\TEMiner.py:8,0 - [3m(W0611)[23m Unused import errno
• Artinali-master\Invariant-Inf\TEMiner.py:9,0 - [3m(W0611)[23m Unused import subprocess
• Artinali-master\Invariant-Inf\TEMiner.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==Duration-IDS:[104:137]
  ┃ ==DurationMiner:[51:83]
  ┃     C=[]
  ┃     for i in range (0, len(basket)):
  ┃         if basket[i] != '':
  ┃             C.append(basket[i].split()[1])
  ┃             C = list(set(C))
  ┃             numofclass=len(C)
  ┃             classes=[[] for i in range(numofclass)]
  ┃             for j in range (0, numofclass) :
  ┃                 for i in range (0, len(basket)) :
  ┃                     if C[j] in basket[i].split() :
  ┃                         classes[j].append(basket[i])
  ┃     return classes
  ┃ ############################################################################
  ┃
  ┃
  ┃ def CalDuration(group):
  ┃     #group=[['START_of E1 4.56', 'END_of E1 4.78', 'START_of E1 4.85', 'END_of E1 4.98'], []]
  ┃     num_group_in_basket=len(group)
  ┃     delta=[[] for i in range(len(group))]
  ┃     for j in range (0, len(group)):
  ┃         for m in range (0, len(group[j])):
  ┃             if group[j][m].split()[0]== "START_of":
  ┃                 delta[j]= [ ]
  ┃                 event=group[j][m].split()[1]
  ┃                 delta[j]= delta[j]+ [str(event)]
  ┃                 for k in range (m+1, len (group[j])):
  ┃                     if group[j][k].split()[0]=="END_of":
  ┃                         d=str((float(group[j][k].split()[2])-float(group[j][m].split()[2])))
  ┃                         group[j][k]= "--"
  ┃                         break
  ┃                 delta[j]=delta[j] + [str(d)]
  ┃                 group[j][m]= " -- "
  ┃         delta[j]=' '.join(delta[j])

• Artinali-master\Invariant-Inf\TEMiner.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==TE-IDS:[231:263]
  ┃ ==TEMiner:[226:256]
  ┃   ETpaired=["%s%   0f" % t for t in zip(paired, relativeTime)]
  ┃   return paired,ETpaired
  ┃ ############################################################################
  ┃ def CalculateRelTime(end, start):
  ┃     #start= '00:14:58.705781'
  ┃     #end= '01:12:58.736490'
  ┃   s=[item for sublist in start for item in sublist]
  ┃   print (s)
  ┃   temp=[''.join(s[0:2])] + [''.join(s[3:5])] +[''.join(s[6:8])] +[''.join(s[9:15])]
  ┃   s=temp
  ┃   print (s)
  ┃   sinSec=int(s[0])*60*60 + int(s[1])*60 + int(s[2]) + int(s[3])*0.000001
  ┃   print (sinSec)
  ┃   e=[item for sublist in end for item in sublist]
  ┃   temp=[''.join(e[0:2])] + [''.join(e[3:5])] +[''.join(e[6:8])] +[''.join(e[9:15])]
  ┃   e=temp
  ┃   einSec=int(e[0])*60*60 + int(e[1])*60 + int(e[2]) + int(e[3])*0.000001
  ┃   print (einSec)
  ┃   Delta= einSec-sinSec
  ┃   delta=Delta
  ┃   hour=int(delta)/3600
  ┃   min=int(delta)/60
  ┃   sec= delta- hour*3600-min*60
  ┃   microsec=delta- hour*3600-min*60-sec
  ┃   delta= str(hour) + ":" + str(min) + ":" + str(sec)
  ┃   print (Delta)
  ┃   return Delta
  ┃ ###############################################################################
  ┃
  ┃
  ┃ def FindEventFrequency(baskets):

• Artinali-master\Invariant-Inf\TEMiner.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==DEMiner:[23:40]
  ┃ ==TEMiner:[24:41]
  ┃   os.rmdir(options["dir"])
  ┃   exit(1)
  ┃ #############################################################################
  ┃ def split_seq(seq, sep):
  ┃   start = 0
  ┃   while start < len(seq):
  ┃     try:
  ┃       stop = start + seq[start:].index(sep)
  ┃       yield seq[start:stop]
  ┃       start = stop + 1
  ┃     except ValueError:
  ┃       yield seq[start:]
  ┃       break
  ┃
  ┃
  ┃ #############################################################################
  ┃
  ┃
  ┃ def readInputTETrace():

• Artinali-master\Invariant-Inf\TEMiner.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==DurationMiner:[14:27]
  ┃ ==TEMiner:[28:41]
  ┃   start = 0
  ┃   while start < len(seq):
  ┃     try:
  ┃       stop = start + seq[start:].index(sep)
  ┃       yield seq[start:stop]
  ┃       start = stop + 1
  ┃     except ValueError:
  ┃       yield seq[start:]
  ┃       break
  ┃
  ┃
  ┃ #############################################################################
  ┃
  ┃
  ┃ def readInputTETrace():

• Artinali-master\Invariant-Inf\TEMiner.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==DEMiner:[27:40]
  ┃ ==TE-IDS:[38:51]
  ┃     start = 0
  ┃     while start < len(seq):
  ┃         try:
  ┃             stop = start + seq[start:].index(sep)
  ┃             yield seq[start:stop]
  ┃             start = stop + 1
  ┃         except ValueError:
  ┃             yield seq[start:]
  ┃             break
  ┃
  ┃
  ┃ #############################################################################
  ┃
  ┃
  ┃ def readInputTrace():

• Artinali-master\Invariant-Inf\TEMiner.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==DE-IDS:[74:87]
  ┃ ==Duration-IDS:[26:39]
  ┃     start = 0
  ┃     while start < len(seq):
  ┃         try:
  ┃             stop = start + seq[start:].index(sep)
  ┃             yield seq[start:stop]
  ┃             start = stop + 1
  ┃         except ValueError:
  ┃             yield seq[start:]
  ┃             break
  ┃ ############################################################################
  ┃ def intersect(a,b):
  ┃     #a= ['Event:send()', 'd1=true', 'd2=all_data', 'd3=time_out, d3=time_in']
  ┃     #b= ['Event:send()', 'd1=true', 'd2=all_data', 'd3=time_out']

• Artinali-master\Invariant-Inf\TEMiner.py:1,0 - [3m(R0801)[23m Similar lines in 2 files

  ┃ ==DEMiner:[10:20]
  ┃ ==TEMiner:[10:21]
  ┃ script_path = os.path.realpath(os.path.dirname(__file__))
  ┃ InputTrace = os.path.basename(sys.argv[1])
  ┃ basedir= os.getcwd()
  ┃ ############################################################################
  ┃
  ┃
  ┃ def checkInputTrace():
  ┃     #Check for Input Trace's presence
  ┃   global cOpt
  ┃   srcpath = os.path.dirname(options["source"])
  ┃   try:


1.1.3.3 Details — Mypy reports no issues with this project — ❌

Mypy reported [1m448[0m issues with your project:
• Artinali-master\Invariant-Inf\TEMiner.py:16,1 - Error: Function is missing a return type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:16,1 - Note: Use "-> None" if function does not return a value
• Artinali-master\Invariant-Inf\TEMiner.py:20,29 - Error: Name "options" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\TEMiner.py:25,12 - Error: Name "options" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\TEMiner.py:28,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:41,1 - Error: Function is missing a return type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:43,6 - Error: "close" of "IOBase" does not return a value
  [func-returns-value]
• Artinali-master\Invariant-Inf\TEMiner.py:49,24 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:53,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:57,18 - Error: Need type annotation for "pairedBasket"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:58,14 - Error: Need type annotation for "pairedTime"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:61,20 - Error: Call to untyped function "EventPairing" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:63,18 - Error: Call to untyped function "purify" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:65,16 - Error: Call to untyped function "purify" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:69,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:73,18 - Error: Need type annotation for "pairedBasket"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:74,14 - Error: Need type annotation for "pairedTime"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:78,21 - Error: Call to untyped function "immidiateEpairing" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:80,18 - Error: Call to untyped function "purify" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:82,16 - Error: Call to untyped function "purify" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:85,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:94,3 - Error: Need type annotation for "MergedTime" (hint: "MergedTime:
  List[<type>] = ...")  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:95,3 - Error: Need type annotation for "MergedTimeU" (hint: "MergedTimeU:
  List[<type>] = ...")  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:96,3 - Error: Need type annotation for "TEinvariant" (hint: "TEinvariant:
  List[<type>] = ...")  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:101,3 - Error: Need type annotation for "support" (hint: "support:
  List[<type>] = ...")  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:149,14 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\Invariant-Inf\TEMiner.py:151,14 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\Invariant-Inf\TEMiner.py:163,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:168,14 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\Invariant-Inf\TEMiner.py:174,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:180,13 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\Invariant-Inf\TEMiner.py:186,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:189,14 - Error: Call to untyped function "purify" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:193,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:195,12 - Error: Need type annotation for "Impaired"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:196,18 - Error: Need type annotation for "ImrelativeTime"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:197,14 - Error: Need type annotation for "ImETpaired"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:200,5 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument
  types "int", "float"  [call-overload]
• Artinali-master\Invariant-Inf\TEMiner.py:200,5 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\TEMiner.py:200,5 - Note: def [1msetitem[0m(self, SupportsIndex, List[Any]) -> None
• Artinali-master\Invariant-Inf\TEMiner.py:200,5 - Note: def [1msetitem[0m(self, slice, Iterable[List[Any]]) -> None
• Artinali-master\Invariant-Inf\TEMiner.py:201,5 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument
  types "int", "str"  [call-overload]
• Artinali-master\Invariant-Inf\TEMiner.py:201,5 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\TEMiner.py:201,5 - Note: def [1msetitem[0m(self, SupportsIndex, List[Any]) -> None
• Artinali-master\Invariant-Inf\TEMiner.py:201,5 - Note: def [1msetitem[0m(self, slice, Iterable[List[Any]]) -> None
• Artinali-master\Invariant-Inf\TEMiner.py:204,15 - Error: List comprehension has incompatible type List[str]; expected
  List[List[Any]]  [misc]
• Artinali-master\Invariant-Inf\TEMiner.py:204,28 - Error: Incompatible types in string interpolation (expression has
  type "List[Any]", placeholder has type "Union[int, float, SupportsFloat]")  [str-format]
• Artinali-master\Invariant-Inf\TEMiner.py:209,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:213,10 - Error: Need type annotation for "paired"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:213,23 - Error: No overload variant of "range" matches argument type "float"
  [call-overload]
• Artinali-master\Invariant-Inf\TEMiner.py:213,23 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\TEMiner.py:213,23 - Note: def range(self, SupportsIndex) -> range
• Artinali-master\Invariant-Inf\TEMiner.py:213,23 - Note: def range(self, SupportsIndex, SupportsIndex, SupportsIndex =
  ...) -> range
• Artinali-master\Invariant-Inf\TEMiner.py:214,16 - Error: Need type annotation for "relativeTime"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:214,29 - Error: No overload variant of "range" matches argument type "float"
  [call-overload]
• Artinali-master\Invariant-Inf\TEMiner.py:214,29 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\TEMiner.py:214,29 - Note: def range(self, SupportsIndex) -> range
• Artinali-master\Invariant-Inf\TEMiner.py:214,29 - Note: def range(self, SupportsIndex, SupportsIndex, SupportsIndex =
  ...) -> range
• Artinali-master\Invariant-Inf\TEMiner.py:215,12 - Error: Need type annotation for "ETpaired"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:215,25 - Error: No overload variant of "range" matches argument type "float"
  [call-overload]
• Artinali-master\Invariant-Inf\TEMiner.py:215,25 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\TEMiner.py:215,25 - Note: def range(self, SupportsIndex) -> range
• Artinali-master\Invariant-Inf\TEMiner.py:215,25 - Note: def range(self, SupportsIndex, SupportsIndex, SupportsIndex =
  ...) -> range
• Artinali-master\Invariant-Inf\TEMiner.py:220,9 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument
  types "int", "float"  [call-overload]
• Artinali-master\Invariant-Inf\TEMiner.py:220,9 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\TEMiner.py:220,9 - Note: def [1msetitem[0m(self, SupportsIndex, List[Any]) -> None
• Artinali-master\Invariant-Inf\TEMiner.py:220,9 - Note: def [1msetitem[0m(self, slice, Iterable[List[Any]]) -> None
• Artinali-master\Invariant-Inf\TEMiner.py:222,9 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument
  types "int", "str"  [call-overload]
• Artinali-master\Invariant-Inf\TEMiner.py:222,9 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\TEMiner.py:222,9 - Note: def [1msetitem[0m(self, SupportsIndex, List[Any]) -> None
• Artinali-master\Invariant-Inf\TEMiner.py:222,9 - Note: def [1msetitem[0m(self, slice, Iterable[List[Any]]) -> None
• Artinali-master\Invariant-Inf\TEMiner.py:227,13 - Error: List comprehension has incompatible type List[str]; expected
  List[List[Any]]  [misc]
• Artinali-master\Invariant-Inf\TEMiner.py:227,26 - Error: Incompatible types in string interpolation (expression has
  type "List[Any]", placeholder has type "Union[int, float, SupportsFloat]")  [str-format]
• Artinali-master\Invariant-Inf\TEMiner.py:230,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:251,10 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "float")  [assignment]
• Artinali-master\Invariant-Inf\TEMiner.py:256,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:257,11 - Error: Need type annotation for "allFreq"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:261,15 - Error: Need type annotation for "FreqClass"  [var-annotated]
• Artinali-master\Invariant-Inf\TEMiner.py:292,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:294,27 - Error: Name "collections" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\TEMiner.py:294,72 - Error: Name "basestring" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\TEMiner.py:295,24 - Error: Call to untyped function "flatten" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:302,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\TEMiner.py:304,11 - Error: Call to untyped function "readInputTETrace" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:305,41 - Error: Call to untyped function "calculateImmidiateTimeInv" in
  typed context  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:306,18 - Error: Call to untyped function "MergingTime" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:307,3 - Error: Call to untyped function "WriteInvariantsToFile" in typed
  context  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:309,12 - Error: Call to untyped function "FindEventFrequency" in typed
  context  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:310,43 - Error: Call to untyped function "calculateImmidiateTimeInv" in
  typed context  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:313,20 - Error: Call to untyped function "MergingTime" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:314,5 - Error: Call to untyped function "WriteFrequenciesToFile" in typed
  context  [no-untyped-call]
• Artinali-master\Invariant-Inf\TEMiner.py:317,9 - Error: Call to untyped function "main" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DurationMiner.py:14,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DurationMiner.py:27,1 - Error: Function is missing a return type annotation
  [no-untyped-def]
• Artinali-master\Invariant-Inf\DurationMiner.py:34,24 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DurationMiner.py:36,3 - Error: Name "basket" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:37,3 - Error: Name "DELTA" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:39,5 - Error: Name "basket" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:40,5 - Error: Name "group" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:40,12 - Error: Call to untyped function "GroupEvents" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DurationMiner.py:40,24 - Error: Name "basket" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:41,5 - Error: Name "DELTA" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:41,15 - Error: Call to untyped function "CalDuration" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DurationMiner.py:41,27 - Error: Name "group" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:44,3 - Error: Name "DELTA" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:45,3 - Error: Name "DELTA" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:46,46 - Error: Name "DELTA" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:47,10 - Error: Name "DELTA" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DurationMiner.py:51,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DurationMiner.py:58,21 - Error: Need type annotation for "classes"  [var-annotated]
• Artinali-master\Invariant-Inf\DurationMiner.py:66,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DurationMiner.py:69,11 - Error: Need type annotation for "delta"  [var-annotated]
• Artinali-master\Invariant-Inf\DurationMiner.py:83,9 - Error: No overload variant of "[1msetitem[0m" of "list" matches
  argument types "int", "str"  [call-overload]
• Artinali-master\Invariant-Inf\DurationMiner.py:83,9 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\DurationMiner.py:83,9 - Note: def [1msetitem[0m(self, SupportsIndex, List[Any]) -> None
• Artinali-master\Invariant-Inf\DurationMiner.py:83,9 - Note: def [1msetitem[0m(self, slice, Iterable[List[Any]]) -> None
• Artinali-master\Invariant-Inf\DurationMiner.py:88,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DurationMiner.py:90,8 - Error: "close" of "IOBase" does not return a value
  [func-returns-value]
• Artinali-master\Invariant-Inf\DurationMiner.py:95,17 - Error: Need type annotation for "DurationInv"  [var-annotated]
• Artinali-master\Invariant-Inf\DurationMiner.py:97,9 - Error: Need type annotation for "MergeDur" (hint: "MergeDur:
  List[<type>] = ...")  [var-annotated]
• Artinali-master\Invariant-Inf\DurationMiner.py:107,18 - Error: Incompatible types in assignment (expression has type
  "str", variable has type "List[str]")  [assignment]
• Artinali-master\Invariant-Inf\DurationMiner.py:118,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DurationMiner.py:119,9 - Error: Call to untyped function "readInputTETrace" in typed
  context  [no-untyped-call]
• Artinali-master\Invariant-Inf\DurationMiner.py:120,3 - Error: Call to untyped function "MergeDurations" in typed
  context  [no-untyped-call]
• Artinali-master\Invariant-Inf\DurationMiner.py:123,9 - Error: Call to untyped function "main" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:16,1 - Error: Function is missing a return type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:16,1 - Note: Use "-> None" if function does not return a value
• Artinali-master\Invariant-Inf\DEMiner.py:19,29 - Error: Name "options" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:24,12 - Error: Name "options" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:27,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:40,1 - Error: Function is missing a return type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:42,6 - Error: "close" of "IOBase" does not return a value
  [func-returns-value]
• Artinali-master\Invariant-Inf\DEMiner.py:44,3 - Error: Name "lines" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:46,3 - Error: Name "lines" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:50,28 - Error: Name "lines" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:51,5 - Error: Name "lines" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:53,5 - Error: Name "lines" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:57,3 - Error: Name "baskets" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:57,24 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:57,34 - Error: Name "lines" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:58,17 - Error: Need type annotation for "DEinvariants"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:58,40 - Error: Name "baskets" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:59,3 - Error: Name "newbasket" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:59,36 - Error: Name "baskets" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:60,10 - Error: Need type annotation for "SNames"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:60,33 - Error: Name "baskets" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:63,27 - Error: Name "baskets" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:64,12 - Error: Name "baskets" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:65,5 - Error: Name "newbasket" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:65,29 - Error: Call to untyped function "ChangeFormat" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:73,6 - Error: Need type annotation for "DE"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:73,29 - Error: Name "baskets" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:74,3 - Error: Name "VN" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:74,29 - Error: Name "baskets" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:75,26 - Error: Name "newbasket" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:77,5 - Error: Name "newbasket" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:77,30 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:79,26 - Error: Name "newbasket" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:80,19 - Error: Call to untyped function "FindFrequentitemSet" in typed
  context  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:80,39 - Error: Name "newbasket" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:81,5 - Error: Name "VN" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:81,20 - Error: Call to untyped function "FindFrequentitemSet" in typed
  context  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:82,36 - Error: Name "VN" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:83,5 - Error: Name "VN" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:85,3 - Error: Name "VN" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:86,34 - Error: Name "VN" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:87,3 - Error: Name "VN" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:93,27 - Error: Name "newbasket" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:94,41 - Error: Call to untyped function "union" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:96,21 - Error: Call to untyped function "AttachVariableNames" in typed
  context  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:99,14 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\Invariant-Inf\DEMiner.py:107,15 - Error: Call to untyped function "AttachVariableNames" in typed
  context  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:110,14 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\Invariant-Inf\DEMiner.py:120,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:122,30 - Error: Name "VN" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:123,14 - Error: Name "VN" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:126,46 - Error: Name "VN" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:139,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:153,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:158,10 - Error: Need type annotation for "temp"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:173,28 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[Any]")  [assignment]
• Artinali-master\Invariant-Inf\DEMiner.py:175,30 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[Any]")  [assignment]
• Artinali-master\Invariant-Inf\DEMiner.py:178,50 - Error: "List[Any]" has no attribute "split"  [attr-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:180,32 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[Any]")  [assignment]
• Artinali-master\Invariant-Inf\DEMiner.py:188,24 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:189,24 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:190,23 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:197,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:201,3 - Error: Need type annotation for "merge" (hint: "merge: List[<type>]
  = ...")  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:228,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:234,12 - Error: Call to untyped function "flatten" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:236,21 - Error: Call to untyped function "flatten" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:239,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:242,3 - Error: Need type annotation for "Eindex" (hint: "Eindex:
  List[<type>] = ...")  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:243,3 - Error: Need type annotation for "temp" (hint: "temp: List[<type>] =
  ...")  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:282,12 - Error: Need type annotation for "newlines"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:286,22 - Error: Need type annotation for "numofDataVariables"
  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:287,11 - Error: Need type annotation for "classes"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:293,5 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument
  types "int", "int"  [call-overload]
• Artinali-master\Invariant-Inf\DEMiner.py:293,5 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\DEMiner.py:293,5 - Note: def [1msetitem[0m(self, SupportsIndex, List[Any]) -> None
• Artinali-master\Invariant-Inf\DEMiner.py:293,5 - Note: def [1msetitem[0m(self, slice, Iterable[List[Any]]) -> None
• Artinali-master\Invariant-Inf\DEMiner.py:300,7 - Error: Need type annotation for "CLA"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:301,14 - Error: Need type annotation for "pure_class"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:302,3 - Error: Name "var_name" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:303,17 - Error: Need type annotation for "splitted_name"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:305,15 - Error: Need type annotation for "CLASSES"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:316,22 - Error: Name "var_name" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:316,35 - Error: Call to untyped function "SplitAllNames" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:317,7 - Error: Name "var_name" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:319,37 - Error: Name "var_name" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:320,7 - Error: Name "var_name" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:322,7 - Error: Name "var_name" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:325,3 - Error: Need type annotation for "DEinvariant" (hint: "DEinvariant:
  List[<type>] = ...")  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:327,3 - Error: Need type annotation for "MergedData" (hint: "MergedData:
  List[<type>] = ...")  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:338,19 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[Any]")  [assignment]
• Artinali-master\Invariant-Inf\DEMiner.py:351,23 - Error: Name "var_name" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:357,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:360,15 - Error: Need type annotation for "name_list"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:371,9 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument
  types "int", "str"  [call-overload]
• Artinali-master\Invariant-Inf\DEMiner.py:371,9 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\DEMiner.py:371,9 - Note: def [1msetitem[0m(self, SupportsIndex, List[Any]) -> None
• Artinali-master\Invariant-Inf\DEMiner.py:371,9 - Note: def [1msetitem[0m(self, slice, Iterable[List[Any]]) -> None
• Artinali-master\Invariant-Inf\DEMiner.py:379,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:381,15 - Error: Need type annotation for "name_list"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:388,9 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument
  types "int", "str"  [call-overload]
• Artinali-master\Invariant-Inf\DEMiner.py:388,9 - Note: Possible overload variants:
• Artinali-master\Invariant-Inf\DEMiner.py:388,9 - Note: def [1msetitem[0m(self, SupportsIndex, List[Any]) -> None
• Artinali-master\Invariant-Inf\DEMiner.py:388,9 - Note: def [1msetitem[0m(self, slice, Iterable[List[Any]]) -> None
• Artinali-master\Invariant-Inf\DEMiner.py:395,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:397,13 - Error: Need type annotation for "newLine"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:398,11 - Error: Need type annotation for "names"  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:400,32 - Error: Call to untyped function "SplitVariableNames" in typed
  context  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:407,1 - Error: Function is missing a return type annotation
  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:407,1 - Note: Use "-> None" if function does not return a value
• Artinali-master\Invariant-Inf\DEMiner.py:408,2 - Error: Need type annotation for "myClass" (hint: "myClass:
  Dict[<type>, <type>] = ...")  [var-annotated]
• Artinali-master\Invariant-Inf\DEMiner.py:409,21 - Error: Name "numofclass" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:411,24 - Error: Name "classes" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:412,10 - Error: Name "classes" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:414,11 - Error: Name "classes" is not defined  [name-defined]
• Artinali-master\Invariant-Inf\DEMiner.py:421,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\Invariant-Inf\DEMiner.py:423,3 - Error: Call to untyped function "readInputTrace" in typed context
  [no-untyped-call]
• Artinali-master\Invariant-Inf\DEMiner.py:432,5 - Error: Call to untyped function "main" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\TE-IDS.py:12,1 - Error: Function is missing a return type annotation  [no-untyped-def]
• Artinali-master\IDS-src\TE-IDS.py:14,8 - Error: "close" of "IOBase" does not return a value  [func-returns-value]
• Artinali-master\IDS-src\TE-IDS.py:16,5 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\TE-IDS.py:18,5 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\TE-IDS.py:27,5 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\TE-IDS.py:28,5 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\TE-IDS.py:33,13 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\TE-IDS.py:33,21 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\TE-IDS.py:38,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\TE-IDS.py:50,1 - Error: Function is missing a return type annotation  [no-untyped-def]
• Artinali-master\IDS-src\TE-IDS.py:52,16 - Error: Call to untyped function "readInputTrace" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\TE-IDS.py:54,24 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\TE-IDS.py:66,26 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\TE-IDS.py:70,5 - Error: Need type annotation for "anomalous_pair" (hint: "anomalous_pair:
  List[<type>] = ...")  [var-annotated]
• Artinali-master\IDS-src\TE-IDS.py:76,22 - Error: Call to untyped function "EventPairing" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\TE-IDS.py:101,44 - Error: Argument 1 to "append" of "list" has incompatible type "str";
  expected "int"  [arg-type]
• Artinali-master\IDS-src\TE-IDS.py:117,37 - Error: Argument 1 to "append" of "list" has incompatible type "str";
  expected "int"  [arg-type]
• Artinali-master\IDS-src\TE-IDS.py:120,30 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\TE-IDS.py:121,30 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\TE-IDS.py:122,32 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\TE-IDS.py:126,13 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument types
  "int", "str"  [call-overload]
• Artinali-master\IDS-src\TE-IDS.py:126,13 - Note: Possible overload variants:
• Artinali-master\IDS-src\TE-IDS.py:126,13 - Note: def [1msetitem[0m(self, SupportsIndex, int) -> None
• Artinali-master\IDS-src\TE-IDS.py:126,13 - Note: def [1msetitem[0m(self, slice, Iterable[int]) -> None
• Artinali-master\IDS-src\TE-IDS.py:130,13 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument types
  "int", "str"  [call-overload]
• Artinali-master\IDS-src\TE-IDS.py:130,13 - Note: Possible overload variants:
• Artinali-master\IDS-src\TE-IDS.py:130,13 - Note: def [1msetitem[0m(self, SupportsIndex, int) -> None
• Artinali-master\IDS-src\TE-IDS.py:130,13 - Note: def [1msetitem[0m(self, slice, Iterable[int]) -> None
• Artinali-master\IDS-src\TE-IDS.py:141,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\TE-IDS.py:141,48 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\TE-IDS.py:142,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\TE-IDS.py:142,35 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\TE-IDS.py:143,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\TE-IDS.py:143,64 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\TE-IDS.py:144,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\TE-IDS.py:144,35 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\TE-IDS.py:145,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\TE-IDS.py:145,58 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\TE-IDS.py:146,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\TE-IDS.py:146,35 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\TE-IDS.py:149,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\TE-IDS.py:149,48 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\TE-IDS.py:150,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\TE-IDS.py:150,36 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\TE-IDS.py:151,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\TE-IDS.py:151,53 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\TE-IDS.py:152,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\TE-IDS.py:152,36 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\TE-IDS.py:162,18 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\IDS-src\TE-IDS.py:165,29 - Error: No overload variant of "map" matches argument types
  "Callable[[Any], str]", "int"  [call-overload]
• Artinali-master\IDS-src\TE-IDS.py:165,29 - Note: Possible overload variants:
• Artinali-master\IDS-src\TE-IDS.py:165,29 - Note: def [_S, _T1] map(self, Callable[[_T1], _S], Iterable[_T1]) ->
  map[_S]
• Artinali-master\IDS-src\TE-IDS.py:165,29 - Note: def [_S, _T1, _T2] map(self, Callable[[_T1, _T2], _S],
  Iterable[_T1], Iterable[_T2]) -> map[_S]
• Artinali-master\IDS-src\TE-IDS.py:165,29 - Note: def [_S, _T1, _T2, _T3] map(self, Callable[[_T1, _T2, _T3], _S],
  Iterable[_T1], Iterable[_T2], Iterable[_T3]) -> map[_S]
• Artinali-master\IDS-src\TE-IDS.py:165,29 - Note: def [_S, _T1, _T2, _T3, _T4] map(self, Callable[[_T1, _T2, _T3,
  _T4], _S], Iterable[_T1], Iterable[_T2], Iterable[_T3], Iterable[_T4]) -> map[_S]
• Artinali-master\IDS-src\TE-IDS.py:165,29 - Note: def [_S, _T1, _T2, _T3, _T4, _T5] map(self, Callable[[_T1, _T2, _T3,
  _T4, _T5], _S], Iterable[_T1], Iterable[_T2], Iterable[_T3], Iterable[_T4], Iterable[_T5]) -> map[_S]
• Artinali-master\IDS-src\TE-IDS.py:165,29 - Note: def [_S] map(self, Callable[..., _S], Iterable[Any], Iterable[Any],
  Iterable[Any], Iterable[Any], Iterable[Any], Iterable[Any], *iterables: Iterable[Any]) -> map[_S]
• Artinali-master\IDS-src\TE-IDS.py:169,18 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\IDS-src\TE-IDS.py:172,29 - Error: No overload variant of "map" matches argument types
  "Callable[[Any], str]", "int"  [call-overload]
• Artinali-master\IDS-src\TE-IDS.py:172,29 - Note: Possible overload variants:
• Artinali-master\IDS-src\TE-IDS.py:172,29 - Note: def [_S, _T1] map(self, Callable[[_T1], _S], Iterable[_T1]) ->
  map[_S]
• Artinali-master\IDS-src\TE-IDS.py:172,29 - Note: def [_S, _T1, _T2] map(self, Callable[[_T1, _T2], _S],
  Iterable[_T1], Iterable[_T2]) -> map[_S]
• Artinali-master\IDS-src\TE-IDS.py:172,29 - Note: def [_S, _T1, _T2, _T3] map(self, Callable[[_T1, _T2, _T3], _S],
  Iterable[_T1], Iterable[_T2], Iterable[_T3]) -> map[_S]
• Artinali-master\IDS-src\TE-IDS.py:172,29 - Note: def [_S, _T1, _T2, _T3, _T4] map(self, Callable[[_T1, _T2, _T3,
  _T4], _S], Iterable[_T1], Iterable[_T2], Iterable[_T3], Iterable[_T4]) -> map[_S]
• Artinali-master\IDS-src\TE-IDS.py:172,29 - Note: def [_S, _T1, _T2, _T3, _T4, _T5] map(self, Callable[[_T1, _T2, _T3,
  _T4, _T5], _S], Iterable[_T1], Iterable[_T2], Iterable[_T3], Iterable[_T4], Iterable[_T5]) -> map[_S]
• Artinali-master\IDS-src\TE-IDS.py:172,29 - Note: def [_S] map(self, Callable[..., _S], Iterable[Any], Iterable[Any],
  Iterable[Any], Iterable[Any], Iterable[Any], Iterable[Any], *iterables: Iterable[Any]) -> map[_S]
• Artinali-master\IDS-src\TE-IDS.py:177,18 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\IDS-src\TE-IDS.py:183,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\TE-IDS.py:193,5 - Error: Unsupported target for indexed assignment ("range")  [index]
• Artinali-master\IDS-src\TE-IDS.py:194,5 - Error: Unsupported target for indexed assignment ("range")  [index]
• Artinali-master\IDS-src\TE-IDS.py:195,14 - Error: Incompatible types in assignment (expression has type "List[str]",
  variable has type "range")  [assignment]
• Artinali-master\IDS-src\TE-IDS.py:199,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\TE-IDS.py:215,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\TE-IDS.py:237,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\TE-IDS.py:258,10 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "float")  [assignment]
• Artinali-master\IDS-src\TE-IDS.py:263,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\TE-IDS.py:264,5 - Error: Call to untyped function "AlarmAbnormality" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\TE-IDS.py:270,5 - Error: Call to untyped function "main" in typed context  [no-untyped-call]
• Artinali-master\IDS-src\Duration-IDS.py:11,1 - Error: Function is missing a return type annotation  [no-untyped-def]
• Artinali-master\IDS-src\Duration-IDS.py:13,9 - Error: "close" of "IOBase" does not return a value
  [func-returns-value]
• Artinali-master\IDS-src\Duration-IDS.py:15,5 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\Duration-IDS.py:17,5 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\Duration-IDS.py:20,5 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\Duration-IDS.py:21,5 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\Duration-IDS.py:22,12 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\Duration-IDS.py:22,21 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\Duration-IDS.py:26,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\Duration-IDS.py:38,1 - Error: Function is missing a return type annotation  [no-untyped-def]
• Artinali-master\IDS-src\Duration-IDS.py:40,21 - Error: Call to untyped function "readInputTrace" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\Duration-IDS.py:41,26 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\Duration-IDS.py:46,16 - Error: Call to untyped function "GroupEvents" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\Duration-IDS.py:47,16 - Error: Call to untyped function "CalDuration" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\Duration-IDS.py:75,40 - Error: Argument 1 to "append" of "list" has incompatible type "str";
  expected "int"  [arg-type]
• Artinali-master\IDS-src\Duration-IDS.py:77,30 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\Duration-IDS.py:82,13 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument
  types "int", "str"  [call-overload]
• Artinali-master\IDS-src\Duration-IDS.py:82,13 - Note: Possible overload variants:
• Artinali-master\IDS-src\Duration-IDS.py:82,13 - Note: def [1msetitem[0m(self, SupportsIndex, int) -> None
• Artinali-master\IDS-src\Duration-IDS.py:82,13 - Note: def [1msetitem[0m(self, slice, Iterable[int]) -> None
• Artinali-master\IDS-src\Duration-IDS.py:86,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\Duration-IDS.py:86,48 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\Duration-IDS.py:87,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\Duration-IDS.py:87,35 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\Duration-IDS.py:88,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\Duration-IDS.py:88,68 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\Duration-IDS.py:89,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\Duration-IDS.py:89,35 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\Duration-IDS.py:90,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\Duration-IDS.py:90,58 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\Duration-IDS.py:91,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\Duration-IDS.py:91,35 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\Duration-IDS.py:96,18 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\IDS-src\Duration-IDS.py:99,29 - Error: No overload variant of "map" matches argument types
  "Callable[[Any], str]", "int"  [call-overload]
• Artinali-master\IDS-src\Duration-IDS.py:99,29 - Note: Possible overload variants:
• Artinali-master\IDS-src\Duration-IDS.py:99,29 - Note: def [_S, _T1] map(self, Callable[[_T1], _S], Iterable[_T1]) ->
  map[_S]
• Artinali-master\IDS-src\Duration-IDS.py:99,29 - Note: def [_S, _T1, _T2] map(self, Callable[[_T1, _T2], _S],
  Iterable[_T1], Iterable[_T2]) -> map[_S]
• Artinali-master\IDS-src\Duration-IDS.py:99,29 - Note: def [_S, _T1, _T2, _T3] map(self, Callable[[_T1, _T2, _T3],
  _S], Iterable[_T1], Iterable[_T2], Iterable[_T3]) -> map[_S]
• Artinali-master\IDS-src\Duration-IDS.py:99,29 - Note: def [_S, _T1, _T2, _T3, _T4] map(self, Callable[[_T1, _T2, _T3,
  _T4], _S], Iterable[_T1], Iterable[_T2], Iterable[_T3], Iterable[_T4]) -> map[_S]
• Artinali-master\IDS-src\Duration-IDS.py:99,29 - Note: def [_S, _T1, _T2, _T3, _T4, _T5] map(self, Callable[[_T1, _T2,
  _T3, _T4, _T5], _S], Iterable[_T1], Iterable[_T2], Iterable[_T3], Iterable[_T4], Iterable[_T5]) -> map[_S]
• Artinali-master\IDS-src\Duration-IDS.py:99,29 - Note: def [_S] map(self, Callable[..., _S], Iterable[Any],
  Iterable[Any], Iterable[Any], Iterable[Any], Iterable[Any], Iterable[Any], *iterables: Iterable[Any]) -> map[_S]
• Artinali-master\IDS-src\Duration-IDS.py:104,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\Duration-IDS.py:111,21 - Error: Need type annotation for "classes"  [var-annotated]
• Artinali-master\IDS-src\Duration-IDS.py:119,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\Duration-IDS.py:122,11 - Error: Need type annotation for "delta"  [var-annotated]
• Artinali-master\IDS-src\Duration-IDS.py:136,9 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument
  types "int", "str"  [call-overload]
• Artinali-master\IDS-src\Duration-IDS.py:136,9 - Note: Possible overload variants:
• Artinali-master\IDS-src\Duration-IDS.py:136,9 - Note: def [1msetitem[0m(self, SupportsIndex, List[Any]) -> None
• Artinali-master\IDS-src\Duration-IDS.py:136,9 - Note: def [1msetitem[0m(self, slice, Iterable[List[Any]]) -> None
• Artinali-master\IDS-src\Duration-IDS.py:144,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\Duration-IDS.py:145,5 - Error: Call to untyped function "AlarmAbnormality" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\Duration-IDS.py:148,9 - Error: Call to untyped function "main" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\DE-IDS.py:18,1 - Error: Function is missing a return type annotation  [no-untyped-def]
• Artinali-master\IDS-src\DE-IDS.py:20,6 - Error: "close" of "IOBase" does not return a value  [func-returns-value]
• Artinali-master\IDS-src\DE-IDS.py:22,3 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:24,3 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:26,28 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:27,5 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:28,5 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:30,22 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\DE-IDS.py:30,32 - Error: Name "lines1" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:41,3 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:42,3 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:43,28 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:44,5 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:45,5 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:46,29 - Error: Name "lines2" is not defined  [name-defined]
• Artinali-master\IDS-src\DE-IDS.py:50,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\DE-IDS.py:52,5 - Error: Need type annotation for "Eindex" (hint: "Eindex: List[<type>] =
  ...")  [var-annotated]
• Artinali-master\IDS-src\DE-IDS.py:53,5 - Error: Need type annotation for "temp" (hint: "temp: List[<type>] = ...")
  [var-annotated]
• Artinali-master\IDS-src\DE-IDS.py:74,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\DE-IDS.py:85,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\DE-IDS.py:89,5 - Error: Need type annotation for "merge" (hint: "merge: List[<type>] = ...")
  [var-annotated]
• Artinali-master\IDS-src\DE-IDS.py:109,1 - Error: Function is missing a return type annotation  [no-untyped-def]
• Artinali-master\IDS-src\DE-IDS.py:111,20 - Error: Call to untyped function "readInputTrace" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\DE-IDS.py:112,14 - Error: Call to untyped function "DataEventGrouping" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\DE-IDS.py:113,16 - Error: Call to untyped function "DataEventGrouping" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\DE-IDS.py:114,18 - Error: Need type annotation for "DataInvClass"  [var-annotated]
• Artinali-master\IDS-src\DE-IDS.py:115,26 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\DE-IDS.py:122,16 - Error: Call to untyped function "DataEventGrouping" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\DE-IDS.py:124,20 - Error: Need type annotation for "traceClass"  [var-annotated]
• Artinali-master\IDS-src\DE-IDS.py:138,32 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[Any]")  [assignment]
• Artinali-master\IDS-src\DE-IDS.py:140,33 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[Any]")  [assignment]
• Artinali-master\IDS-src\DE-IDS.py:146,36 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[Any]")  [assignment]
• Artinali-master\IDS-src\DE-IDS.py:148,37 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[Any]")  [assignment]
• Artinali-master\IDS-src\DE-IDS.py:160,60 - Error: Argument 1 to "append" of "list" has incompatible type "str";
  expected "int"  [arg-type]
• Artinali-master\IDS-src\DE-IDS.py:169,56 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[Any]")  [assignment]
• Artinali-master\IDS-src\DE-IDS.py:171,57 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[Any]")  [assignment]
• Artinali-master\IDS-src\DE-IDS.py:182,80 - Error: Argument 1 to "append" of "list" has incompatible type "str";
  expected "int"  [arg-type]
• Artinali-master\IDS-src\DE-IDS.py:186,34 - Error: Call to untyped function "split_seq" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\DE-IDS.py:190,13 - Error: No overload variant of "[1msetitem[0m" of "list" matches argument types
  "int", "str"  [call-overload]
• Artinali-master\IDS-src\DE-IDS.py:190,13 - Note: Possible overload variants:
• Artinali-master\IDS-src\DE-IDS.py:190,13 - Note: def [1msetitem[0m(self, SupportsIndex, int) -> None
• Artinali-master\IDS-src\DE-IDS.py:190,13 - Note: def [1msetitem[0m(self, slice, Iterable[int]) -> None
• Artinali-master\IDS-src\DE-IDS.py:198,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\DE-IDS.py:198,52 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\DE-IDS.py:199,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\DE-IDS.py:199,39 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\DE-IDS.py:200,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\DE-IDS.py:200,59 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\DE-IDS.py:201,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\DE-IDS.py:201,39 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\DE-IDS.py:202,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\DE-IDS.py:202,42 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\DE-IDS.py:203,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\DE-IDS.py:203,48 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\DE-IDS.py:204,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\DE-IDS.py:204,39 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\DE-IDS.py:205,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\DE-IDS.py:205,31 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\DE-IDS.py:206,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\DE-IDS.py:206,72 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\DE-IDS.py:207,9 - Error: Unsupported target for indexed assignment ("int")  [index]
• Artinali-master\IDS-src\DE-IDS.py:207,40 - Error: Value of type "int" is not indexable  [index]
• Artinali-master\IDS-src\DE-IDS.py:208,9 - Error: "int" has no attribute "pop"  [attr-defined]
• Artinali-master\IDS-src\DE-IDS.py:213,18 - Error: Incompatible types in assignment (expression has type "str",
  variable has type "List[str]")  [assignment]
• Artinali-master\IDS-src\DE-IDS.py:216,29 - Error: No overload variant of "map" matches argument types
  "Callable[[Any], str]", "int"  [call-overload]
• Artinali-master\IDS-src\DE-IDS.py:216,29 - Note: Possible overload variants:
• Artinali-master\IDS-src\DE-IDS.py:216,29 - Note: def [_S, _T1] map(self, Callable[[_T1], _S], Iterable[_T1]) ->
  map[_S]
• Artinali-master\IDS-src\DE-IDS.py:216,29 - Note: def [_S, _T1, _T2] map(self, Callable[[_T1, _T2], _S],
  Iterable[_T1], Iterable[_T2]) -> map[_S]
• Artinali-master\IDS-src\DE-IDS.py:216,29 - Note: def [_S, _T1, _T2, _T3] map(self, Callable[[_T1, _T2, _T3], _S],
  Iterable[_T1], Iterable[_T2], Iterable[_T3]) -> map[_S]
• Artinali-master\IDS-src\DE-IDS.py:216,29 - Note: def [_S, _T1, _T2, _T3, _T4] map(self, Callable[[_T1, _T2, _T3,
  _T4], _S], Iterable[_T1], Iterable[_T2], Iterable[_T3], Iterable[_T4]) -> map[_S]
• Artinali-master\IDS-src\DE-IDS.py:216,29 - Note: def [_S, _T1, _T2, _T3, _T4, _T5] map(self, Callable[[_T1, _T2, _T3,
  _T4, _T5], _S], Iterable[_T1], Iterable[_T2], Iterable[_T3], Iterable[_T4], Iterable[_T5]) -> map[_S]
• Artinali-master\IDS-src\DE-IDS.py:216,29 - Note: def [_S] map(self, Callable[..., _S], Iterable[Any], Iterable[Any],
  Iterable[Any], Iterable[Any], Iterable[Any], Iterable[Any], *iterables: Iterable[Any]) -> map[_S]
• Artinali-master\IDS-src\DE-IDS.py:220,1 - Error: Function is missing a type annotation  [no-untyped-def]
• Artinali-master\IDS-src\DE-IDS.py:221,5 - Error: Call to untyped function "AlarmAbnormality" in typed context
  [no-untyped-call]
• Artinali-master\IDS-src\DE-IDS.py:228,5 - Error: Call to untyped function "main" in typed context  [no-untyped-call]

1.1.3.4 Details — Black reports no issues with this project — ❌

Black reported [1m6[0m files in your project that it would reformat:
• Artinali-master\Invariant-Inf\DurationMiner.py
• Artinali-master\IDS-src\Duration-IDS.py
• Artinali-master\IDS-src\DE-IDS.py
• Artinali-master\Invariant-Inf\TEMiner.py
• Artinali-master\IDS-src\TE-IDS.py
• Artinali-master\Invariant-Inf\DEMiner.py

Black can fix these issues automatically when you run black . in your project.

1.1.3.5 Details — isort reports no issues with this project — ❌

isort reported [1m6[0m files in your project that it would fix:
• Artinali-master\IDS-src\DE-IDS.py - Imports are incorrectly sorted and/or formatted.
• Artinali-master\IDS-src\Duration-IDS.py - Imports are incorrectly sorted and/or formatted.
• Artinali-master\IDS-src\TE-IDS.py - Imports are incorrectly sorted and/or formatted.
• Artinali-master\Invariant-Inf\DEMiner.py - Imports are incorrectly sorted and/or formatted.
• Artinali-master\Invariant-Inf\DurationMiner.py - Imports are incorrectly sorted and/or formatted.
• Artinali-master\Invariant-Inf\TEMiner.py - Imports are incorrectly sorted and/or formatted.

isort can fix these issues automatically when you run isort . in your project.

1.1.3.6 Details — isort is properly configured — ❌

isort is not properly configured. In order to be compatible with [Black](https://github.com/psf/black), which mllint
also recommends using, you should configure isort to use the black profile. Furthermore, we recommend centralising your
configuration in your pyproject.toml

Thus, ensure that your pyproject.toml contains at least the following section:

┃ [tool.isort]
┃ profile = "black"

1.1.3.7 Details — Bandit reports no issues with this project — ❌

Bandit reported [1m6[0m issues with your project:
• Artinali-master\IDS-src\DE-IDS.py:8 - [3m(B404, severity: LOW, confidence: HIGH)[23m - Consider possible security
  implications associated with the subprocess module. [More
  Info](https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_imports.html#b404-import-subprocess)
• Artinali-master\IDS-src\Duration-IDS.py:7 - [3m(B404, severity: LOW, confidence: HIGH)[23m - Consider possible security
  implications associated with the subprocess module. [More
  Info](https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_imports.html#b404-import-subprocess)
• Artinali-master\IDS-src\TE-IDS.py:8 - [3m(B404, severity: LOW, confidence: HIGH)[23m - Consider possible security
  implications associated with the subprocess module. [More
  Info](https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_imports.html#b404-import-subprocess)
• Artinali-master\Invariant-Inf\DEMiner.py:8 - [3m(B404, severity: LOW, confidence: HIGH)[23m - Consider possible security
  implications associated with the subprocess module. [More
  Info](https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_imports.html#b404-import-subprocess)
• Artinali-master\Invariant-Inf\DurationMiner.py:7 - [3m(B404, severity: LOW, confidence: HIGH)[23m - Consider possible
  security implications associated with the subprocess module. [More
  Info](https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_imports.html#b404-import-subprocess)
• Artinali-master\Invariant-Inf\TEMiner.py:9 - [3m(B404, severity: LOW, confidence: HIGH)[23m - Consider possible security
  implications associated with the subprocess module. [More
  Info](https://bandit.readthedocs.io/en/1.7.4/blacklists/blacklist_imports.html#b404-import-subprocess)

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

took: 4.4842959s
