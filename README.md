# bookshelf
My little bookshelf 📚

```
docker run --rm -v "$(pwd):/data" -u $(id -u):$(id -g) pandoc/core --standalone --template template/template.html template/books.md -o index.html
`
