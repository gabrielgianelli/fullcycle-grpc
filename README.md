# FULL CYCLE

## Comunicação entre sistemas

### gRPC

Código das aulas de gRPC do módulo de Comunicação entre sistemas do curso Full Cycle

#### Geração dos proto buffers

> protoc --go_out=. --go-grpc_out=. proto/course_category.proto

#### Execução do projeto

> go run cmd/grpcServer/main.go

#### Execução do Evans gRPC Client

> evans -r repl

#### Procedures que podem ser chamadas

> call CreateCategory
> call CreateCategoryStream
> call CreateCategoryStreamBidirectional
> call ListCategories