# Simple Dependency Injection

## How to run and test this simple server

Run the following command in your terminal.

```bash
go run main.go
```

After running the server, you could `curl` request to `http://localhost:8080`.

```bash
$ curl "http://localhost:8080/hello?user_id=test_user"
unknown user
```

```bash
$ curl "http://localhost:8080/hello?user_id=1"
Hello, Fred
```
