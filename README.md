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

## more command
```bash
goreman -f procfile run restart first
goreman -f procfile run stop first
goreman 0f procfile run status
```