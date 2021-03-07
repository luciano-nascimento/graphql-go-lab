# Objective
create a graphql server using go lang

# How to run ?
go run server.go   
also could be tested running localhost:8080 after run serve.go

# Commands/Configs used during dev
go mod init github.com/luciano-nascimento/graphql-go-lab   
go get github.com/99designs/gqlgen   
after create model(schema): go run github.com/99designs/gqlgen init   
when update gqlgen.yml run: gqlgen generate