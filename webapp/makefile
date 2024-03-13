# init:
# 	go mod init webapp
# install-deps
# 	go get github.com/go-chi/chi/v5

run_web:
	go run ./cmd/web

run_api:
	go run ./cmd/api

run: run_api

test:
	go test ./...

test_verbose:
	go test -v ./...

test_single:
	go test -v -run Test_alpha_isPrime

test_suite:
	go test -v -run Test_alpha

test_integration:
	go test -v -tags=integration ./...

cover:
	go test -cover ./...

coverprofile:
	go test -coverprofile=coverage.out ./...

coverpreview: coverprofile
	go tool cover -html=coverage.out
