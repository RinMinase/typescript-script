<h1 align="center"> typescript-script </h1>
<p align="center">
📜🛠 Script tag support for TypeScript.<br>
Based from basarat/typescript-script with Minified Versions
</p>

## Usage
Add the following lines at the **bottom** of your page: 
```html
<script src="https://cdn.jsdelivr.net/gh/rinminase/typescript-script/ts-services.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/rinminase/typescript-script/ts-transpiler.min.js"></script>
```

And then you can use script tags that load `.ts` files or even have inline `typescript` syntax:
```html
<script type="text/typescript" src="script.ts"></script>
<script type="text/typescript">
    setTimeout(()=>console.log('hello'));
</script>
```

`<script type="text/typescript">` tags should be located **above** the transpiler and services.

## Demo
https://next.plnkr.co/edit/3TCDINcd6LAGcHMm
