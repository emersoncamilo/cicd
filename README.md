
docker run --rm -it -v "C:/SRC/LEARNING/cicd/app_go:/app" -w /app golangci-lint-go golangci-lint run controllers/ database/ models/ routes/


docker run --rm -itv "C:/SRC/LEARNING/cicd/app_go:/app" -w /app golangci/golangci-lint golangci-lint run controllers/ database/ models/ routes/


docker compose exec app go test main_test.go