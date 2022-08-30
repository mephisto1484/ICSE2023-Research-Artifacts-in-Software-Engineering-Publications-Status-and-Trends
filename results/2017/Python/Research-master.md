Linting project at  F:\Python3.8env/data/2017/Research-master
No .mllint.yml or pyproject.toml found in project folder, using default configuration
---

🏃 Running - Version Control (0.00 ms)
🏃 Running - Dependency Management (0.00 ms)
🏃 Running - Continuous Integration (CI) (0.00 ms)
✔️ Done - Dependency Management (0.00 ms)
🏃 Running - Code Quality (0.50 ms)
🏃 Running - Testing (0.52 ms)
⏳ Waiting - Version Control (0.52 ms)
🏃 Running - Version Control - Git (0.52 ms)
🏃 Running - Version Control - DVC (0.52 ms)
✔️ Done - Testing (0.52 ms)
✔️ Done - Version Control - DVC (0.52 ms)
🏃 Running - Code Quality - Pylint (0.00 ms)
🏃 Running - Code Quality - Mypy (0.00 ms)
🏃 Running - Code Quality - Black (0.00 ms)
🏃 Running - Code Quality - isort (0.00 ms)
🏃 Running - Code Quality - Bandit (0.00 ms)
⏳ Waiting - Code Quality (8 ms)
✔️ Done - Version Control - Git (60 ms)
🏃 Running - Version Control (60 ms)
✔️ Done - Version Control (60 ms)
✔️ Done - Continuous Integration (CI) (255 ms)
✔️ Done - Code Quality - Mypy (1.00 s)
✔️ Done - Code Quality - Bandit (2.01 s)
✔️ Done - Code Quality - Black (2.07 s)
✔️ Done - Code Quality - isort (2.81 s)
✔️ Done - Code Quality - Pylint (3.20 s)
🏃 Running - Code Quality (3.21 s)
✔️ Done - Code Quality (3.21 s)

✔️ All done!

---

1 ML Project Report
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────

┌──────────────────────┬─────────────────────────────────────────┐
│[1mProject[0m               │[1mDetails[0m                                  │
╞══════════════════════╪═════════════════════════════════════════╡
│Date                  │Sat, 20 Aug 2022 15:48:43 +0800          │
├──────────────────────┼─────────────────────────────────────────┤
│Path                  │F:\Python3.8env/data/2017/Research-master│
├──────────────────────┼─────────────────────────────────────────┤
│Config                │default                                  │
├──────────────────────┼─────────────────────────────────────────┤
│Default               │Yes                                      │
├──────────────────────┼─────────────────────────────────────────┤
│Number of Python files│4                                        │
├──────────────────────┼─────────────────────────────────────────┤
│Lines of Python code  │268                                      │
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

Pylint reported [1m134[0m issues with your project:
• Research-master\CrossLanguageEmpirical\soquery.py:6,31 - [3m(C0303)[23m Trailing whitespace
• Research-master\CrossLanguageEmpirical\soquery.py:18,0 - [3m(C0301)[23m Line too long (108/100)
• Research-master\CrossLanguageEmpirical\soquery.py:20,68 - [3m(C0303)[23m Trailing whitespace
• Research-master\CrossLanguageEmpirical\soquery.py:21,76 - [3m(C0303)[23m Trailing whitespace
• Research-master\CrossLanguageEmpirical\soquery.py:22,77 - [3m(C0303)[23m Trailing whitespace
• Research-master\CrossLanguageEmpirical\soquery.py:94,0 - [3m(C0301)[23m Line too long (148/100)
• Research-master\CrossLanguageEmpirical\soquery.py:147,78 - [3m(C0303)[23m Trailing whitespace
• Research-master\CrossLanguageEmpirical\soquery.py:168,43 - [3m(C0303)[23m Trailing whitespace
• Research-master\CrossLanguageEmpirical\soquery.py:173,34 - [3m(C0303)[23m Trailing whitespace
• Research-master\CrossLanguageEmpirical\soquery.py:174,0 - [3m(C0303)[23m Trailing whitespace
• Research-master\CrossLanguageEmpirical\soquery.py:175,0 - [3m(C0303)[23m Trailing whitespace
• Research-master\CrossLanguageEmpirical\soquery.py:168,9 - [3m(W0511)[23m TODO don't hardcode the root path
• Research-master\CrossLanguageEmpirical\soquery.py:194,5 - [3m(W0511)[23m TODO have a way to pass in a list of previous to
  target languages instead
• Research-master\CrossLanguageEmpirical\soquery.py:12,0 - [3m(E0401)[23m Unable to import 'google.cloud'
• Research-master\CrossLanguageEmpirical\soquery.py:13,0 - [3m(E0401)[23m Unable to import 'pandas'
• Research-master\CrossLanguageEmpirical\soquery.py:39,0 - [3m(C0116)[23m Missing function or method docstring
• Research-master\CrossLanguageEmpirical\soquery.py:40,4 - [3m(R1705)[23m Unnecessary "elif" after "return", remove the
  leading "el" from "elif"
• Research-master\CrossLanguageEmpirical\soquery.py:49,0 - [3m(C0116)[23m Missing function or method docstring
• Research-master\CrossLanguageEmpirical\soquery.py:50,4 - [3m(R1705)[23m Unnecessary "elif" after "return", remove the
  leading "el" from "elif"
• Research-master\CrossLanguageEmpirical\soquery.py:60,0 - [3m(C0116)[23m Missing function or method docstring
• Research-master\CrossLanguageEmpirical\soquery.py:61,4 - [3m(R1705)[23m Unnecessary "elif" after "return", remove the
  leading "el" from "elif"
• Research-master\CrossLanguageEmpirical\soquery.py:75,24 - [3m(C0103)[23m Argument name "a" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:75,27 - [3m(C0103)[23m Argument name "b" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:108,4 - [3m(C0103)[23m Variable name "df" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:91,4 - [3m(W0612)[23m Unused variable 'lang_no_space'
• Research-master\CrossLanguageEmpirical\soquery.py:116,19 - [3m(C0103)[23m Argument name "a" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:129,11 - [3m(C0103)[23m Variable name "l" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:161,8 - [3m(C0103)[23m Variable name "l" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:166,8 - [3m(C0103)[23m Variable name "df" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:200,8 - [3m(C0103)[23m Variable name "p" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:200,11 - [3m(C0103)[23m Variable name "t" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:201,8 - [3m(C0103)[23m Variable name "p" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:202,8 - [3m(C0103)[23m Variable name "t" doesn't conform to snake_case
  naming style
• Research-master\CrossLanguageEmpirical\soquery.py:207,4 - [3m(W0105)[23m String statement has no effect
• Research-master\CrossLanguageEmpirical\soquery.py:13,0 - [3m(W0611)[23m Unused pandas imported as pd
• Research-master\SimpleGenderComputer\getGender.py:13,7 - [3m(E0001)[23m Missing parentheses in call to 'print'. Did you mean
  print("Started")? (<unknown>, line 13)
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:33,0 - [3m(C0303)[23m Trailing whitespace
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:43,68 - [3m(C0303)[23m Trailing whitespace
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:53,91 - [3m(C0303)[23m Trailing whitespace
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:54,91 - [3m(C0303)[23m Trailing whitespace
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:55,94 - [3m(C0303)[23m Trailing whitespace
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:56,91 - [3m(C0303)[23m Trailing whitespace
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:60,0 - [3m(C0301)[23m Line too long (108/100)
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:61,0 - [3m(C0303)[23m Trailing whitespace
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:1,0 - [3m(C0114)[23m Missing module docstring
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:1,0 - [3m(C0103)[23m Module name "simpleGenderComputer" doesn't
  conform to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:3,0 - [3m(E0401)[23m Unable to import 'unidecode'
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:6,0 - [3m(W0105)[23m String statement has no effect
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:7,0 - [3m(C0116)[23m Missing function or method docstring
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:7,0 - [3m(C0103)[23m Function name "loadData" doesn't conform
  to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:7,22 - [3m(C0103)[23m Argument name "dataPath" doesn't conform
  to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:7,32 - [3m(C0103)[23m Argument name "hasHeader" doesn't conform
  to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:8,4 - [3m(C0103)[23m Function name "loadGenderList" doesn't
  conform to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:8,40 - [3m(C0103)[23m Argument name "dataPath" doesn't conform
  to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:8,50 - [3m(C0103)[23m Argument name "hasHeader" doesn't conform
  to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:9,8 - [3m(C0103)[23m Variable name "fd" doesn't conform to
  snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:9,41 - [3m(C0209)[23m Formatting a regular string which could
  be a f-string
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:14,8 - [3m(W0105)[23m String statement has no effect
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:21,12 - [3m(W0702)[23m No exception type(s) specified
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:18,16 - [3m(W0105)[23m String statement has no effect
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:22,16 - [3m(W0105)[23m String statement has no effect
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:24,19 - [3m(E1101)[23m Instance of 'dict' has no 'has_key'
  member
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:25,20 - [3m(W0105)[23m String statement has no effect
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:28,15 - [3m(E1101)[23m Instance of 'dict' has no 'has_key'
  member
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:34,8 - [3m(W0105)[23m String statement has no effect
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:35,8 - [3m(C0206)[23m Consider iterating with .items()
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:35,20 - [3m(C0201)[23m Consider iterating the dictionary
  directly instead of calling .keys()
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:37,19 - [3m(E1101)[23m Instance of 'dict' has no 'has_key'
  member
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:9,13 - [3m(R1732)[23m Consider using 'with' for
  resource-allocating operations
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:47,0 - [3m(C0115)[23m Missing class docstring
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:51,8 - [3m(C0103)[23m Attribute name "nameLists" doesn't
  conform to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:53,8 - [3m(C0103)[23m Attribute name "listOfCountries" doesn't
  conform to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:49,23 - [3m(C0103)[23m Argument name "dataPath" doesn't conform
  to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:62,4 - [3m(C0116)[23m Missing function or method docstring
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:62,4 - [3m(C0103)[23m Method name "simpleLookup" doesn't
  conform to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:63,8 - [3m(C0103)[23m Variable name "mCount" doesn't conform to
  snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:64,8 - [3m(C0103)[23m Variable name "fCount" doesn't conform to
  snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:65,8 - [3m(C0103)[23m Variable name "Total" doesn't conform to
  snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:69,16 - [3m(C0103)[23m Variable name "mCount" doesn't conform
  to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:72,16 - [3m(C0103)[23m Variable name "fCount" doesn't conform
  to snake_case naming style
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:65,8 - [3m(W0612)[23m Unused variable 'Total'
• Research-master\SimpleGenderComputer\simpleGenderComputer.py:47,0 - [3m(R0903)[23m Too few public methods (1/2)
• Research-master\SimpleGenderComputer\unicodeMagic.py:24,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:27,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:28,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:30,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:31,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:33,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:34,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:38,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:43,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:44,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:45,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:47,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:48,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:49,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:51,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:52,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:56,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:61,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:63,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:64,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:65,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:66,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:68,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:69,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:71,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:72,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:74,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:76,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:78,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:80,0 - [3m(W0311)[23m Bad indentation. Found 1 spaces, expected 4
• Research-master\SimpleGenderComputer\unicodeMagic.py:81,0 - [3m(W0311)[23m Bad indentation. Found 2 spaces, expected 8
• Research-master\SimpleGenderComputer\unicodeMagic.py:82,0 - [3m(W0311)[23m Bad indentation. Found 3 spaces, expected 12
• Research-master\SimpleGenderComputer\unicodeMagic.py:83,0 - [3m(C0303)[23m Trailing whitespace
• Research-master\SimpleGenderComputer\unicodeMagic.py:84,0 - [3m(C0303)[23m Trailing whitespace
• Research-master\SimpleGenderComputer\unicodeMagic.py:1,0 - [3m(C0103)[23m Module name "unicodeMagic" doesn't conform to
  snake_case naming style
• Research-master\SimpleGenderComputer\unicodeMagic.py:19,0 - [3m(W0105)[23m String statement has no effect
• Research-master\SimpleGenderComputer\unicodeMagic.py:21,0 - [3m(C0410)[23m Multiple imports on one line (csv, codecs,
  cStringIO)
• Research-master\SimpleGenderComputer\unicodeMagic.py:21,0 - [3m(C0413)[23m Import "import csv, codecs, cStringIO" should be
  placed at the top of the module
• Research-master\SimpleGenderComputer\unicodeMagic.py:21,0 - [3m(C0413)[23m Import "import csv, codecs, cStringIO" should be
  placed at the top of the module
• Research-master\SimpleGenderComputer\unicodeMagic.py:21,0 - [3m(E0401)[23m Unable to import 'cStringIO'
• Research-master\SimpleGenderComputer\unicodeMagic.py:21,0 - [3m(C0413)[23m Import "import csv, codecs, cStringIO" should be
  placed at the top of the module
• Research-master\SimpleGenderComputer\unicodeMagic.py:27,20 - [3m(C0103)[23m Argument name "f" doesn't conform to snake_case
  naming style
• Research-master\SimpleGenderComputer\unicodeMagic.py:30,1 - [3m(E0301)[23m [1miter[0m returns non-iterator
• Research-master\SimpleGenderComputer\unicodeMagic.py:33,1 - [3m(C0116)[23m Missing function or method docstring
• Research-master\SimpleGenderComputer\unicodeMagic.py:43,20 - [3m(C0103)[23m Argument name "f" doesn't conform to snake_case
  naming style
• Research-master\SimpleGenderComputer\unicodeMagic.py:47,1 - [3m(C0116)[23m Missing function or method docstring
• Research-master\SimpleGenderComputer\unicodeMagic.py:49,10 - [3m(E0602)[23m Undefined variable 'unicode'
• Research-master\SimpleGenderComputer\unicodeMagic.py:51,1 - [3m(E0301)[23m [1miter[0m returns non-iterator
• Research-master\SimpleGenderComputer\unicodeMagic.py:61,20 - [3m(C0103)[23m Argument name "f" doesn't conform to snake_case
  naming style
• Research-master\SimpleGenderComputer\unicodeMagic.py:68,1 - [3m(C0116)[23m Missing function or method docstring
• Research-master\SimpleGenderComputer\unicodeMagic.py:80,1 - [3m(C0116)[23m Missing function or method docstring
• Research-master\SimpleGenderComputer\unicodeMagic.py:21,0 - [3m(C0412)[23m Imports from package csv are not grouped

1.1.3.3 Details — Mypy reports no issues with this project — ✅

Congratulations, Mypy is happy with your project!

1.1.3.4 Details — Black reports no issues with this project — ❌

Black reported [1m3[0m files in your project that it would reformat:
• Research-master\SimpleGenderComputer\unicodeMagic.py
• Research-master\SimpleGenderComputer\simpleGenderComputer.py
• Research-master\CrossLanguageEmpirical\soquery.py

Black can fix these issues automatically when you run black . in your project.

1.1.3.5 Details — isort reports no issues with this project — ❌

isort reported [1m4[0m files in your project that it would fix:
• Research-master\CrossLanguageEmpirical\soquery.py - Imports are incorrectly sorted and/or formatted.
• Research-master\SimpleGenderComputer\getGender.py - Imports are incorrectly sorted and/or formatted.
• Research-master\SimpleGenderComputer\simpleGenderComputer.py - Imports are incorrectly sorted and/or formatted.
• Research-master\SimpleGenderComputer\unicodeMagic.py - Imports are incorrectly sorted and/or formatted.

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
    into string, output:

┃ errors:
┃ - filename: F:\Python3.8env/data/2017/Research-master\Research-master\SimpleGenderComputer\getGender.py
┃   reason: syntax error while parsing AST from file
┃ generated_at: '2022-08-20T07:48:42Z'
┃ metrics:
┃   F:\Python3.8env/data/2017/Research-master\Research-master\CrossLanguageEmpirical\soquery.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 1
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 1
┃     SEVERITY.UNDEFINED: 0
┃     loc: 166
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Research-master\Research-master\SimpleGenderComputer\getGender.py:
┃     loc: 30
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Research-master\Research-master\SimpleGenderComputer\simpleGenderComputer.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 69
┃     nosec: 0
┃     skipped_tests: 0
┃   F:\Python3.8env/data/2017/Research-master\Research-master\SimpleGenderComputer\unicodeMagic.py:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 0
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 0
┃     SEVERITY.UNDEFINED: 0
┃     loc: 58
┃     nosec: 0
┃     skipped_tests: 0
┃   _totals:
┃     CONFIDENCE.HIGH: 0
┃     CONFIDENCE.LOW: 1
┃     CONFIDENCE.MEDIUM: 0
┃     CONFIDENCE.UNDEFINED: 0
┃     SEVERITY.HIGH: 0
┃     SEVERITY.LOW: 0
┃     SEVERITY.MEDIUM: 1
┃     SEVERITY.UNDEFINED: 0
┃     loc: 323
┃     nosec: 0
┃     skipped_tests: 0
┃ results:
┃ - code: 92     query = \\n93         f'''\n94         SELECT CONCAT('http://stackoverflow.com/q/',
┃     Cast(P.Id as string)) as URL, P.Title, P.ViewCount, P.Score, P.AcceptedAnswerId,
┃     P.Tags, P.Body\n95         FROM sotorrent-org.2018_12_09.Posts P\n96         WHERE
┃     P.PostTypeId = 1 AND (\n97         (P.Tags LIKE '{atag}' AND P.Tags LIKE '{btag}')\n98         OR\n99
┃ (P.Tags
┃     LIKE '{atag}' AND (P.Title LIKE '{btext}' OR P.Body LIKE '{btext}'))\n100         )\n
┃   col_offset: 8
┃   filename: F:\Python3.8env/data/2017/Research-master\Research-master\CrossLanguageEmpirical\soquery.py
┃   issue_confidence: LOW
┃   issue_cwe:
┃     id: 89
┃     link: https://cwe.mitre.org/data/definitions/89.html
┃   issue_severity: MEDIUM
┃   issue_text: Possible SQL injection vector through string-based query construction.
┃   line_number: 93
┃   line_range:
┃   - 93
┃   - 94
┃   - 95
┃   - 96
┃   - 97
┃   - 98
┃   - 99
┃   more_info: https://bandit.readthedocs.io/en/1.7.4/plugins/b608_hardcoded_sql_expressions.html
┃   test_id: B608
┃   test_name: hardcoded_sql_expressions


---
❌ rules unsuccessful:	19
Your project is still lacking in quality and could do with some improvements.
Use mllint describe with each rule's slug to learn more about what you can do to get the rules to pass and improve the quality of your ML project.

took: 3.3001917s
