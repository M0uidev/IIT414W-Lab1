# Lab 1 · Runbook

1. Extract the complete package into your course repository; preserve labs/lab_01 and data/samples/lab01_v1.
2. Use your Week 2 Python environment. If needed: `python -m pip install -r requirements_lab01_v1.txt` from the package root.
3. Open labs/lab_01/Lab01_EDA_Baselines_Student_v1.ipynb with that environment's Python kernel. Default MODE is snapshot; no network is used by the notebook.
4. Work through train, then calibration. Complete the written evidence and freeze record before enabling RUN_TEST.
5. Restart and Run All after completing the notebook. Save its outputs. Confirm that you can reproduce the frozen evaluation without modifying decisions.
6. Record your actual Python/package versions, operating system, any changes to this procedure, the submitted commit and the date/result of your check below. Keep the source CSVs unchanged.

Actual environment and execution evidence: Actual environment and execution evidence:

- Date checked: 2026-09-23.
- Operating system: Windows 11 (10.0.26200-SP0).
- Python: 3.12.10.
- pandas: 2.3.1.
- numpy: 1.26.4.
- matplotlib: 3.10.3.
- Environment: local `.venv` created in the repository and selected as the Jupyter kernel.
- Dependencies installed from `requirements_lab01_v1.txt`.
- Notebook mode: `MODE="snapshot"`; no network access was used.
- Train (2019–2021) and calibration (2022) were executed before opening the test data.
- Pre-test decisions were frozen in commit `3149f79` (`Freeze Lab 1 decisions before test`) before enabling `RUN_TEST=True`.
- Final test (2023–2024): 919 rows, 0 missing qualifying records.
- Majority baseline: accuracy = 0.499456, balanced accuracy = 0.500000.
- Qualifying-top-ten baseline: accuracy = 0.796518, balanced accuracy = 0.796517, TN = 365, FP = 94, FN = 93, TP = 367.
- No methodological decisions were changed after inspecting the test results.
- Procedure change: the lab was executed on Windows/Python 3.12.10 instead of the environment originally used to produce the existing notebook outputs. The supplied requirements installed and the notebook executed successfully.
- Final submitted commit: repository HEAD at submission; the exact commit identifier is recorded in the Canvas submission after the final push.

Submission uses GitHub + Canvas as stated in the brief. Include support code and the six CSVs plus lab01_manifest_v1.json. No API credentials are needed. If your environment is blocked, record the exact error and contact the teaching team; do not label synthetic practice as real data.
