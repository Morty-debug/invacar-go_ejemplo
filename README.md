
### crear el proyecto desde cero
```batch
mkdir invocar_libreria-go
cd invocar_libreria-go
notepad main.go
go mod init github.com/Morty-debug/librerias
go mod tidy
```

### obtener libreria actualizada
```batch
del /f go.mod
del /f go.sum
go mod init github.com/Morty-debug/librerias
go mod tidy
go run main.go
```
