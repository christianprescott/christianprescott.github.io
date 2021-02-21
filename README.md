Feast your eyes [http://christianprescott.com/](http://christianprescott.com/)

## Compiling Assets

Install [Sass](https://sass-lang.com/install)

```sh
# Install pre-commit asset compilation check
cp pre-commit .git/hooks/pre-commit
# Development
sass --watch scss/:css/
# Deployment
sass --style compressed scss/:css/
```
