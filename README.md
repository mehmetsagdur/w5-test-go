# Week 5 Assignment

In this assignment, we expect to you write functions to pass the tests with the cases need to pass.

Every tests have several cases, you should organize the cases as `table driven design testing` and `all cases must pass!`

Test file is under `assignment` folder, make your implementation in the same folder.

## Test Run
```
go test ./...
go test -v ./...
```

### Test Coverage
```
go test -coverprofile=cover.txt ./...
go tool cover -html=cover.txt -o cover.html
```
Open `cover.html` file to see coverage report.
