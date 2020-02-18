# Docker Tutorial

## go server

Build command:

```go
    go build hello.go
```

Run command:

```
    ./hello
```

Dockerfile build:

```
    docker build -t go-server .
```

Port: `8000`

## python server

Run command:

```python
    python3 httpserver.py
```

or 

```python
    python httpserver.py
```

Dockerfile build:

```
    docker build -t python-server .
```

Port: `8001`

## ruby server

Run command:

```ruby
    ruby http.rb
```

Dockerfile build:

```
    docker build -t ruby-server .
```

Port: `8002`