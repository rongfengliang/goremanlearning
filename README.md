# goreman demo project

## goreman install
```bash
go get github.com/mattn/goreman

```
## run
```bash
cd first
go build -o server
cd second
go build -o server
goreman -f procfile start
```
## 