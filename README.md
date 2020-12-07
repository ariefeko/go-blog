## Go Blog
This repo is using Go module, can be used with Mysql or PostgreSQL

### Scope:
- Signup (Register)
- Edit his account
- Shutdown (Delete his account)
- Create a blog post
- Edit blog post created by him
- View all blog posts
- View a particular blog post
- View other blog posts published by other users
- Delete blog post created by him

### Dependencies
- github.com/badoux/checkmail
- github.com/jinzhu/gorm
- golang.org/x/crypto/bcrypt
- github.com/dgrijalva/jwt-go
- github.com/gorilla/mux
- github.com/jinzhu/gorm/dialects/mysql" //If using mysql
- github.com/jinzhu/gorm/dialects/postgres //If using postgres
- github.com/joho/godotenv
- gopkg.in/go-playground/assert.v1

Source tutorial: https://levelup.gitconnected.com/crud-restful-api-with-go-gorm-jwt-postgres-mysql-and-testing-460a85ab7121