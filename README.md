# Rest-API-Go-lang-

## Comands to run this Go Rest API

i) Must have Go installed in system.
ii) In terminal : go mod init 
If shows error : go: modules disabled ....
In terminal : export GO111MODULE="on"
iii) go mod init example/yourfoldernameinsidewhichyouhavemain.go
iv) go get github.com/gin-gonic/gin
v) go run main.go 
vi) new terminal, for get request :  curl localhost:8080/books
vii) for post query : curl localhost:8080/books --include --header "Content-Type: application/json" -d @body.json --request "POST"
viii) for patch query (checkout/takeaway book)  : curl localhost:8080/checkout?id=2 --request "PATCH"
ix) for patch query (return a book) : curl localhost:8080/return?id=2 --request "PATCH"
