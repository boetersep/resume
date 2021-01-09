### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex resume.tex
```

Use %cd%:/data on Windows 

### License

Format is MIT but all the data is owned by Sourabh Bajaj.
