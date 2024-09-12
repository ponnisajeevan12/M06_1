m06_1 - GO APP

# Linux

$env:GOOS = "linux"
$env:GOARCH = "amd64"
go build -o helloserver-linux main.go

# Windows

$env:GOOS = "windows"
go build -o helloserver-windows.exe main.go


# MAC

$env:GOOS = "darwin"
$env:GOARCH = "arm64"
go build -o helloserver-mac main.go
