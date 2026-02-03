Запуск приложения:
go run cmd/auth/main.go --config=./config/local.yaml

Команда для миграции данных:
go run ./cmd/migrator --storage-path=./storage/auth.db --migrations-path=./migrations

Миграция для тестовых данных:
go run ./cmd/migrator/main.go --storage-path=./storage/auth.db --migrations-path=./tests/migrations --migrations-table=migrations_test