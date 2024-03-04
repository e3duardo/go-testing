run:
	go run .

test:
	go test .

test_verbose:
	go test -v .

cover:
	go test -cover .

coverprofile:
	go test -coverprofile=coverage.out

coverpreview: coverprofile
	go tool cover -html=coverage.out
