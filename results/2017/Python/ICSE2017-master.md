Linting project at  F:\Python3.8env/data/2017/ICSE2017-master
No .mllint.yml or pyproject.toml found in project folder, using default configuration
---

🏃 Running - Version Control (0.00 ms)
🏃 Running - Dependency Management (0.00 ms)
🏃 Running - Continuous Integration (CI) (0.00 ms)
✔️ Done - Dependency Management (0.51 ms)
🏃 Running - Code Quality (0.51 ms)
🏃 Running - Testing (0.51 ms)
⏳ Waiting - Version Control (0.51 ms)
🏃 Running - Version Control - Git (0.00 ms)
🏃 Running - Version Control - DVC (0.00 ms)
✔️ Done - Testing (0.51 ms)
✔️ Done - Version Control - DVC (0.00 ms)
🏃 Running - Code Quality - Pylint (0.00 ms)
🏃 Running - Code Quality - Mypy (0.00 ms)
🏃 Running - Code Quality - Black (0.00 ms)
🏃 Running - Code Quality - isort (0.00 ms)
🏃 Running - Code Quality - Bandit (0.00 ms)
⏳ Waiting - Code Quality (5 ms)
✔️ Done - Version Control - Git (41 ms)
🏃 Running - Version Control (42 ms)
✔️ Done - Version Control (42 ms)
✔️ Done - Continuous Integration (CI) (169 ms)
✔️ Done - Code Quality - Black (1.38 s)
✔️ Done - Code Quality - Bandit (1.56 s)
✔️ Done - Code Quality - isort (1.66 s)
✔️ Done - Code Quality - Mypy (1.71 s)
✔️ Done - Code Quality - Pylint (2.74 s)
🏃 Running - Code Quality (2.75 s)
✔️ Done - Code Quality (2.75 s)

✔️ All done!

---

1 ML Project Report
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────

┌──────────────────────┬─────────────────────────────────────────┐
│[1mProject[0m               │[1mDetails[0m                                  │
╞══════════════════════╪═════════════════════════════════════════╡
│Date                  │Sat, 20 Aug 2022 20:48:33 +0800          │
├──────────────────────┼─────────────────────────────────────────┤
│Path                  │F:\Python3.8env/data/2017/ICSE2017-master│
├──────────────────────┼─────────────────────────────────────────┤
│Config                │default                                  │
├──────────────────────┼─────────────────────────────────────────┤
│Default               │Yes                                      │
├──────────────────────┼─────────────────────────────────────────┤
│Number of Python files│1                                        │
├──────────────────────┼─────────────────────────────────────────┤
│Lines of Python code  │400                                      │
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
1.1.3 Code Quality (code-quality) — [1m24.2[0m%

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
│  ❌  │ 93.8%│     1│Bandit reports no issues with this project      │code-quality/bandit/no-issues                   │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│      │ [3mTotal[23m│      │                                                │                                                │
├──────┼──────┼──────┼────────────────────────────────────────────────┼────────────────────────────────────────────────┤
│  ❌  │ [1m24.2[0m%│      │Code Quality                                    │code-quality                                    │
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

Pylint reported [1m237[0m issues with your project:
• ICSE2017-master\script\getBugs.py:10,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:14,44 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:16,75 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:17,46 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:45,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:54,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• ICSE2017-master\script\getBugs.py:55,33 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:58,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• ICSE2017-master\script\getBugs.py:62,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• ICSE2017-master\script\getBugs.py:69,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:75,38 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:76,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:81,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:82,96 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:83,95 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:84,95 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:87,0 - [3m(C0325)[23m Unnecessary parens after 'return' keyword
• ICSE2017-master\script\getBugs.py:88,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:89,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:93,0 - [3m(C0325)[23m Unnecessary parens after 'return' keyword
• ICSE2017-master\script\getBugs.py:100,0 - [3m(C0301)[23m Line too long (119/100)
• ICSE2017-master\script\getBugs.py:113,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:127,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:129,22 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:130,22 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:131,24 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:138,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:145,20 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:151,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:157,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:162,0 - [3m(C0301)[23m Line too long (111/100)
• ICSE2017-master\script\getBugs.py:168,25 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:170,27 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:171,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:176,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:193,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:211,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:213,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:219,0 - [3m(C0301)[23m Line too long (141/100)
• ICSE2017-master\script\getBugs.py:222,45 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:224,0 - [3m(C0325)[23m Unnecessary parens after 'return' keyword
• ICSE2017-master\script\getBugs.py:228,49 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:230,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:238,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:243,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:246,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:247,89 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:258,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:259,45 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:262,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:263,35 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:269,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:276,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• ICSE2017-master\script\getBugs.py:279,141 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:279,0 - [3m(C0301)[23m Line too long (141/100)
• ICSE2017-master\script\getBugs.py:284,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• ICSE2017-master\script\getBugs.py:288,141 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:288,0 - [3m(C0301)[23m Line too long (141/100)
• ICSE2017-master\script\getBugs.py:290,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:293,0 - [3m(C0301)[23m Line too long (123/100)
• ICSE2017-master\script\getBugs.py:297,34 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:298,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:299,41 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:304,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:307,100 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:309,63 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:310,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:312,61 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:314,90 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:315,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:317,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:324,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:327,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:335,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:338,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:339,45 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:343,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:344,41 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:348,117 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:348,0 - [3m(C0301)[23m Line too long (117/100)
• ICSE2017-master\script\getBugs.py:349,71 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:350,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:353,63 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:354,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:355,35 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:361,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:364,0 - [3m(C0325)[23m Unnecessary parens after 'if' keyword
• ICSE2017-master\script\getBugs.py:368,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:371,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:373,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:375,49 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:377,84 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:378,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:380,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:382,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:383,106 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:383,0 - [3m(C0301)[23m Line too long (106/100)
• ICSE2017-master\script\getBugs.py:385,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:388,65 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:391,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:392,89 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:393,73 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:397,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:402,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:406,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:408,89 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:414,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:418,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:419,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:421,0 - [3m(C0301)[23m Line too long (110/100)
• ICSE2017-master\script\getBugs.py:422,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:424,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:434,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:439,0 - [3m(C0301)[23m Line too long (154/100)
• ICSE2017-master\script\getBugs.py:440,34 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:450,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:459,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:466,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:474,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:486,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:496,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:498,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:502,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:503,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:504,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:505,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:506,0 - [3m(C0303)[23m Trailing whitespace
• ICSE2017-master\script\getBugs.py:109,16 - [3m(W1401)[23m Anomalous backslash in string: '\W'. String constant might be
  missing an r prefix.
• ICSE2017-master\script\getBugs.py:110,17 - [3m(W1401)[23m Anomalous backslash in string: '\w'. String constant might be
  missing an r prefix.
• ICSE2017-master\script\getBugs.py:110,20 - [3m(W1401)[23m Anomalous backslash in string: '\/'. String constant might be
  missing an r prefix.
• ICSE2017-master\script\getBugs.py:110,22 - [3m(W1401)[23m Anomalous backslash in string: '\w'. String constant might be
  missing an r prefix.
• ICSE2017-master\script\getBugs.py:111,26 - [3m(W1401)[23m Anomalous backslash in string: '\/'. String constant might be
  missing an r prefix.
• ICSE2017-master\script\getBugs.py:111,29 - [3m(W1401)[23m Anomalous backslash in string: '\w'. String constant might be
  missing an r prefix.
• ICSE2017-master\script\getBugs.py:111,32 - [3m(W1401)[23m Anomalous backslash in string: '\/'. String constant might be
  missing an r prefix.
• ICSE2017-master\script\getBugs.py:111,34 - [3m(W1401)[23m Anomalous backslash in string: '\w'. String constant might be
  missing an r prefix.
• ICSE2017-master\script\getBugs.py:111,38 - [3m(W1401)[23m Anomalous backslash in string: '\/'. String constant might be
  missing an r prefix.
• ICSE2017-master\script\getBugs.py:111,53 - [3m(W1401)[23m Anomalous backslash in string: '\/'. String constant might be
  missing an r prefix.
• ICSE2017-master\script\getBugs.py:1,0 - [3m(C0103)[23m Module name "getBugs" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:34,0 - [3m(E0401)[23m Unable to import 'bs4'
• ICSE2017-master\script\getBugs.py:38,0 - [3m(E0401)[23m Unable to import 'pygithub3'
• ICSE2017-master\script\getBugs.py:40,0 - [3m(C0103)[23m Constant name "username" doesn't conform to UPPER_CASE naming style
• ICSE2017-master\script\getBugs.py:41,0 - [3m(C0103)[23m Constant name "password" doesn't conform to UPPER_CASE naming style
• ICSE2017-master\script\getBugs.py:44,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:44,0 - [3m(R0914)[23m Too many local variables (19/15)
• ICSE2017-master\script\getBugs.py:90,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:95,29 - [3m(C0103)[23m Argument name "projectName" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:114,4 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• ICSE2017-master\script\getBugs.py:117,12 - [3m(C0103)[23m Variable name "m" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:141,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:141,0 - [3m(C0103)[23m Function name "get_ifRelated" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:141,26 - [3m(C0103)[23m Argument name "projectName" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:141,38 - [3m(C0103)[23m Argument name "subId" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:142,4 - [3m(R1703)[23m The if statement can be replaced with 'return bool(test)'
• ICSE2017-master\script\getBugs.py:142,4 - [3m(R1705)[23m Unnecessary "else" after "return", remove the "else" and de-indent
  the code inside it
• ICSE2017-master\script\getBugs.py:147,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:161,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:170,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:177,7 - [3m(R0123)[23m Comparison to literal
• ICSE2017-master\script\getBugs.py:194,7 - [3m(R0123)[23m Comparison to literal
• ICSE2017-master\script\getBugs.py:214,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:214,17 - [3m(C0103)[23m Argument name "projectName" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:221,16 - [3m(C0103)[23m Variable name "pr" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:226,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:226,19 - [3m(C0103)[23m Argument name "projectName" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:233,8 - [3m(C0103)[23m Variable name "r" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:241,8 - [3m(C0103)[23m Variable name "c" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:247,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:247,0 - [3m(C0103)[23m Function name "get_subjectIssueInfo" doesn't conform to snake_case
  naming style
• ICSE2017-master\script\getBugs.py:247,25 - [3m(C0103)[23m Argument name "subjectUser" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:247,38 - [3m(C0103)[23m Argument name "subjectProjectName" doesn't conform to snake_case
  naming style
• ICSE2017-master\script\getBugs.py:247,0 - [3m(R0914)[23m Too many local variables (35/15)
• ICSE2017-master\script\getBugs.py:311,11 - [3m(W0703)[23m Catching too general exception Exception
• ICSE2017-master\script\getBugs.py:260,8 - [3m(C0103)[23m Variable name "sb" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:272,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• ICSE2017-master\script\getBugs.py:278,20 - [3m(C0103)[23m Variable name "cr" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:286,20 - [3m(C0103)[23m Variable name "wr" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:294,12 - [3m(C0103)[23m Variable name "cr" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:295,12 - [3m(C0103)[23m Variable name "cr" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:302,8 - [3m(C0103)[23m Variable name "pr" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:303,8 - [3m(C0103)[23m Variable name "pr" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:311,4 - [3m(C0103)[23m Variable name "e" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:313,13 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• ICSE2017-master\script\getBugs.py:313,62 - [3m(C0103)[23m Variable name "ef" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:318,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:318,0 - [3m(C0103)[23m Function name "get_refIssueInfo" doesn't conform to snake_case
  naming style
• ICSE2017-master\script\getBugs.py:318,21 - [3m(C0103)[23m Argument name "subjectProjectName" doesn't conform to snake_case
  naming style
• ICSE2017-master\script\getBugs.py:318,41 - [3m(C0103)[23m Argument name "refIssue" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:318,51 - [3m(C0103)[23m Argument name "subIssue" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:318,0 - [3m(R0914)[23m Too many local variables (32/15)
• ICSE2017-master\script\getBugs.py:321,4 - [3m(C0103)[23m Variable name "projectName" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:374,11 - [3m(W0703)[23m Catching too general exception Exception
• ICSE2017-master\script\getBugs.py:346,8 - [3m(C0103)[23m Variable name "pr" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:347,8 - [3m(C0103)[23m Variable name "pr" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:363,8 - [3m(C0200)[23m Consider using enumerate instead of iterating with range and len
• ICSE2017-master\script\getBugs.py:374,4 - [3m(C0103)[23m Variable name "e" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:376,13 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• ICSE2017-master\script\getBugs.py:376,70 - [3m(C0103)[23m Variable name "ef" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:381,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:381,12 - [3m(C0103)[23m Argument name "subjectUser" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:381,25 - [3m(C0103)[23m Argument name "subjectProjectName" doesn't conform to snake_case
  naming style
• ICSE2017-master\script\getBugs.py:381,45 - [3m(C0103)[23m Argument name "labelName" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:381,0 - [3m(R0914)[23m Too many local variables (36/15)
• ICSE2017-master\script\getBugs.py:388,4 - [3m(C0103)[23m Variable name "sr" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:388,9 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• ICSE2017-master\script\getBugs.py:394,4 - [3m(C0103)[23m Variable name "sp" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:394,9 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• ICSE2017-master\script\getBugs.py:399,11 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• ICSE2017-master\script\getBugs.py:403,4 - [3m(C0103)[23m Variable name "sb" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:403,9 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• ICSE2017-master\script\getBugs.py:411,4 - [3m(C0103)[23m Variable name "r" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:411,8 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• ICSE2017-master\script\getBugs.py:415,4 - [3m(C0103)[23m Variable name "rb" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:415,9 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• ICSE2017-master\script\getBugs.py:451,12 - [3m(C0103)[23m Variable name "ri" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:381,0 - [3m(R0915)[23m Too many statements (59/50)
• ICSE2017-master\script\getBugs.py:388,9 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• ICSE2017-master\script\getBugs.py:394,9 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• ICSE2017-master\script\getBugs.py:399,11 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• ICSE2017-master\script\getBugs.py:403,9 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• ICSE2017-master\script\getBugs.py:411,8 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• ICSE2017-master\script\getBugs.py:415,9 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• ICSE2017-master\script\getBugs.py:469,0 - [3m(C0116)[23m Missing function or method docstring
• ICSE2017-master\script\getBugs.py:469,0 - [3m(C0103)[23m Function name "getProjectIssueWithRelated" doesn't conform to
  snake_case naming style
• ICSE2017-master\script\getBugs.py:469,31 - [3m(C0103)[23m Argument name "urlFile" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:469,0 - [3m(R0914)[23m Too many local variables (18/15)
• ICSE2017-master\script\getBugs.py:470,4 - [3m(C0103)[23m Variable name "s" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:470,8 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• ICSE2017-master\script\getBugs.py:475,9 - [3m(W1514)[23m Using open without explicitly specifying an encoding
• ICSE2017-master\script\getBugs.py:475,26 - [3m(C0103)[23m Variable name "f" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:478,8 - [3m(C0103)[23m Variable name "Row" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:479,12 - [3m(C0103)[23m Variable name "r" doesn't conform to snake_case naming style
• ICSE2017-master\script\getBugs.py:484,12 - [3m(C0103)[23m Variable name "projectName" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:485,12 - [3m(C0103)[23m Variable name "labelName" doesn't conform to snake_case naming
  style
• ICSE2017-master\script\getBugs.py:470,8 - [3m(R1732)[23m Consider using 'with' for resource-allocating operations
• ICSE2017-master\script\getBugs.py:35,0 - [3m(C0411)[23m standard import "import re" should be placed before "import
  requests"
• ICSE2017-master\script\getBugs.py:36,0 - [3m(C0411)[23m standard import "import csv" should be placed before "import
  requests"
• ICSE2017-master\script\getBugs.py:37,0 - [3m(C0411)[23m standard import "from collections import namedtuple" should be
  placed before "import requests"

1.1.3.3 Details — Mypy reports no issues with this project — ❌

Mypy reported [1m42[0m issues with your project:
• ICSE2017-master\script\getBugs.py:33,1 - Error: Library stubs not installed for "requests" (or incompatible with
  Python 3.8)  [import]
• ICSE2017-master\script\getBugs.py:33,1 - Note: Hint: "python3 -m pip install types-requests"
• ICSE2017-master\script\getBugs.py:33,1 - Note: (or run "mypy --install-types" to install all missing stub packages)
• ICSE2017-master\script\getBugs.py:33,1 - Note: See [https://mypy.readthedocs.io/en/stable/running_mypy.html#missing-i
  mports](https://mypy.readthedocs.io/en/stable/running_mypy.html#missing-imports)
• ICSE2017-master\script\getBugs.py:34,1 - Error: Cannot find implementation or library stub for module named "bs4"
  [import]
• ICSE2017-master\script\getBugs.py:38,1 - Error: Cannot find implementation or library stub for module named
  "pygithub3"  [import]
• ICSE2017-master\script\getBugs.py:44,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:90,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:95,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:131,14 - Error: Incompatible types in assignment (expression has type "Set[Any]",
  variable has type "List[Any]")  [assignment]
• ICSE2017-master\script\getBugs.py:141,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:147,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:161,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:170,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:214,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:226,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:247,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:251,16 - Error: Call to untyped function "get_html" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:260,14 - Error: Call to untyped function "get_basic" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:264,49 - Error: Call to untyped function "get_comments" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:273,45 - Error: Call to untyped function "get_related" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:292,48 - Error: Call to untyped function "get_refs" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:300,38 - Error: Call to untyped function "get_close" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:303,14 - Error: Call to untyped function "get_pr" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:306,25 - Error: Call to untyped function "get_participants" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:318,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:329,16 - Error: Call to untyped function "get_html" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:340,20 - Error: Call to untyped function "get_basic" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:345,38 - Error: Call to untyped function "get_close" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:347,14 - Error: Call to untyped function "get_pr" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:352,25 - Error: Call to untyped function "get_participants" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:356,49 - Error: Call to untyped function "get_comments" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:364,17 - Error: Call to untyped function "get_ifRelated" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:381,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:439,71 - Error: Call to untyped function "get_subjectIssueInfo" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:453,35 - Error: Call to untyped function "get_refIssueInfo" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:469,1 - Error: Function is missing a type annotation  [no-untyped-def]
• ICSE2017-master\script\getBugs.py:478,15 - Error: List or tuple literal expected as the second argument to
  "namedtuple()"  [misc]
• ICSE2017-master\script\getBugs.py:481,19 - Error: "Row@478" has no attribute "url"  [attr-defined]
• ICSE2017-master\script\getBugs.py:485,25 - Error: "Row@478" has no attribute "bug_label"  [attr-defined]
• ICSE2017-master\script\getBugs.py:491,37 - Error: Call to untyped function "get_all" in typed context
  [no-untyped-call]
• ICSE2017-master\script\getBugs.py:501,1 - Error: Call to untyped function "getProjectIssueWithRelated" in typed
  context  [no-untyped-call]

1.1.3.4 Details — Black reports no issues with this project — ❌

Black reported [1m1[0m files in your project that it would reformat:
• ICSE2017-master\script\getBugs.py

Black can fix these issues automatically when you run black . in your project.

1.1.3.5 Details — isort reports no issues with this project — ❌

isort reported [1m1[0m files in your project that it would fix:
• ICSE2017-master\script\getBugs.py - Imports are incorrectly sorted and/or formatted.

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
• ICSE2017-master\script\getBugs.py:41 - [3m(B105, severity: LOW, confidence: MEDIUM)[23m - Possible hardcoded password:
  'password' [More Info](https://bandit.readthedocs.io/en/1.7.4/plugins/b105_hardcoded_password_string.html)

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

took: 2.8121172s
