# CubeCart Manual Testing Project

Manual testing project for the CubeCart e-commerce demo store (https://javabykiran.in/other/CC/), covering the
Registration, Login, Admin Login, Inventory and Add Product modules. This is the manual-testing companion to the
Selenium + TestNG automation project for the same application.

## Folder Structure

Just two simple folders - Word documents in one, Excel sheets in the other.

| Folder | Contents |
|---|---|
| `Documents/` | Project_Overview, Requirement_Understanding, Application_Flow, STLC, Boundary_Value_Analysis, Equivalence_Partitioning, Error_Guessing, Test_Metrics, Test_Closure_Report, Interview_Questions_and_Answers (10 `.docx` files) |
| `Excel_Sheets/` | Requirement_Traceability_Matrix, Test_Scenarios, Test_Cases, Smoke_Suite, Sanity_Suite, Regression_Suite, End_to_End_Test_Cases, Bug_Report, Test_Execution_Report (9 `.xlsx` files) |

## How to Use This Project

1. Start with `Documents/Project_Overview.docx` to understand what was tested and why.
2. `Excel_Sheets/Requirement_Traceability_Matrix.xlsx` shows how every requirement traces down to a specific test case.
3. `Excel_Sheets/Test_Cases.xlsx` is the main working sheet - every other Excel file (suites, execution
   report, RTM) references the Test Case IDs from this sheet.
4. `Excel_Sheets/Bug_Report.xlsx` lists the 5 real defects found; each is also flagged directly in the Test Case sheet
   with a `Fail` status and a comment pointing to the Bug ID.

## Key Numbers

- 43 requirements, 100% covered in the RTM
- 99 test scenarios, 146 test cases
- 141 Passed / 5 Failed (96.6% pass rate)
- 5 genuine application defects logged (3 High severity, 1 Medium, 1 Low)

## Related Project

The Selenium + TestNG automation project for this same application automates the stable, repeatable regression
scenarios identified here (see `CubeCartAutomationFramework/` for that project).
