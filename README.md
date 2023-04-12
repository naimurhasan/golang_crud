# A crud and Login Sample App in go

### uses
- gin
- gorm:postgres
- jwt

```
Project_Dir: .
│   .env
│   go.mod
│   go.sum
│   main.go
│
├───controllers
│       postController.go
│       userController.go
│
├───initializers
│       database.go
│       loadEnvVariables.go
│
├───migrate
│       migrate.go
│
└───models
        postModel.go
        userModel.go
```