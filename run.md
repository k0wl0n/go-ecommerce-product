export DB_URL=postgres://ecommerce:ecommerce@localhost:5432/products_db?sslmode=disable
goose -dir ./sql/schema/ postgres $DB_URL up 