# blog
blog.bo40.net

# Develpment
## Install Hugo
```bash
brew install hugo
```

## Download Theme
```bash
mkdir -p themes/hugo-geekblog/
curl -L https://github.com/thegeeklab/hugo-geekblog/releases/latest/download/hugo-geekblog.tar.gz | tar -xz -C themes/hugo-geekblog/ --strip-components=1
```

## Run Hugo
```bash
hugo server -D
```
then open http://localhost:1313/

## Build
```bash
hugo
```
then the static files are generated in `public` directory.