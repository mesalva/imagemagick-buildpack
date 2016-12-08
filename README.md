imagemagick-buildpack
=================================

Este [buildpack](http://devcenter.heroku.com/articles/buildpacks) adiciona bináros da suite [ImageMagick](https://www.imagemagick.org/script/index.php) em projetos do heroku. No Me Salva! o utilizamos nas aplicações de [QA](https://dashboard.heroku.com/apps/mesalva-backend-api-qa/) e [Prod](https://dashboard.heroku.com/apps/mesalva-api).

Versão do ImageMagick: 7.0.3-9.

Para adicionar um buildpack específico a um novo projeto, basta executar o seguinte comando:

```
heroku buildpacks:add --index 1 https://github.com/mesalva/imagemagick-buildpack
```
