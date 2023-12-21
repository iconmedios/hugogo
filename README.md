# hugogo
https://gohugo.io/getting-started/quick-start/

## 1. Crear sitio:

hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml

## 2. Definir tema: 
theme = 'Paradojo'

## 3. Servir

hugo server --help

## 4. Construir (Build)
hugo

## 5. Crear nuevo tema

https://gohugo.io/commands/hugo_new_theme/
hugo new theme
hugo server --noHTTPCache