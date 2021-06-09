# Host API documenation with Redoc for Serover Inventory

## Run following commands
npx redoc-cli bundle openapi.yaml

## Move html to index.html
mv redoc-static.html index.html

## Add following line to index.html

1. Line 7 add
<link rel="icon" type="image/png" href="/favicon.ico"/>

2. Line with <body> add
<img class="mb-4" src="logo.png" alt="" width="216" height="72">