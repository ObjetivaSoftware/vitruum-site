# vitruum-site

```js
    Google Analytics - Vitruum - vitruumapp@gmail.com 
    <!-- Google tag (gtag.js) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-V7HD3Q676T"></script>
    <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());

    gtag('config', 'G-V7HD3Q676T');
    </script>
```

## Para transpilar os arquivos scss

* Verificar se pussui o `sass` instalado e no path
    * Utilize o seguinte comando: `$ node sass`. Pode ser utilizado por outras linguagens.
* Após isso execute o próximo comando no terminal.
```BASH
$ sass src/public/index.scss:src/view/css/site.min.css --watch --style=compress
```

## Para rodar o server em localhost

* Se estiver na pasta view
```bash
php -S localhost:3000 
```
* Se estiver na home do projeto
```bash
php -S localhost:3000 -t src/view
```