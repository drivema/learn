
set GOPATH=C:\Users\7169977\go        	home
echo %GOPATH%
cd C:\Users\7169977\go\src\hello		workspace

go install					//build hello.exe in C:\Users\7169977\go\bin
go clean -i					//delete hello.exe in C:\Users\7169977\go\bin

go build					//build hello.exe
go run hello.go				//run hello.go

