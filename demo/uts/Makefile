build:
	-rm uts.amd
	CGO_ENABLE=0 GOOS=linux GOARCH=amd64 go build -o uts.amd
	-upx -9 uts.amd
