build:
	-rm cgroups.amd
	CGO_ENABLE=0 GOOS=linux GOARCH=amd64 go build -o cgroups.amd
	-upx -9 cgroups.amd
