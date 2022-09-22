# URL Shortener

URL shortener that is written in Golang and uses [Hexagonal](https://en.wikipedia.org/wiki/Hexagonal_architecture_(software)) architecture.

It uses REDIS or MONGO as repository and supports json and msgpack.

## Endpoints

Gets shortened URL and automatically redirects
`GET /{code}`

Post request creates new URL and persists it at one of the supported repository
`POST /` with json or msgpack `{"url": "http://some-url-to-be-shortened"}`

## Credits

[Tensor Programming Youtube Channel](https://www.youtube.com/c/TensorProgramming)
