# ESEP Grade Calculator

This library is a simple utility to calculate your grades. You can add grades as one of 3 types and use the calculator functions to compute your grade based on weight.

Files:
```
grade_calculator.go: Defines the GradeCalculator and Grade structs along with functions to add grades, calculate averages, and return the final letter grade.
grade_calculator_test.go: Contains unit tests that verify grade calculation logic by comparing expected vs. actual results.
go.mod: Specifies the module path and Go version required for the project.
```

Installation Notes:
```
Fork Repository and Clone locally. 
To run this project, note the necessary installation of Golang:
Golang 1.24+

```
Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
