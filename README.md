Запуск приложения:
go run cmd/auth/main.go --config=./config/local.yaml

Команда для миграции данных:
go run ./cmd/migrator --storage-path=./storage/auth.db --migrations-path=./migrations
