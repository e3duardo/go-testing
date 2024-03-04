run:
	go run .

test:
	go test .

test_verbose:
	go test -v .

test_single:
	go test -v -run Test_alpha_isPrime

test_suite:
	go test -v -run Test_alpha

cover:
	go test -cover .

coverprofile:
	go test -coverprofile=coverage.out

coverpreview: coverprofile
	go tool cover -html=coverage.out
