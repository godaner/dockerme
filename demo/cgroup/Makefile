build:
	-rm cgroup.amd
	CGO_ENABLE=0 GOOS=linux GOARCH=amd64 go build -o cgroup.amd
	-upx -9 cgroup.amd
