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

Docker container run:

```
    docker run -p 8000:8000 go-server
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

Docker container run:

```
    docker run -p 8001:8001 python-server
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

Docker container run:

```
    docker run -p 8002:8002 ruby-server
```

Port: `8002`