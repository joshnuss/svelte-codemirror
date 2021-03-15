Svelte CodeMirror component
---------------------------

Provides an abstraction layer over CodeMirror that reduces the setup needed to make it work with Svelte.

## Demo

https://svelte.dev/repl/b2c657e8c49a42b6ba6aaf3dbd7d09d5

## Usage

```html
<script>
  import 'codemirror/mode/javascript/javascript'
  import CodeMirror from '@joshnuss/svelte-codemirror'
  
  let editor
</script>

<CodeMirror bind:editor options={{ lineNumbers: true, mode: "javascript", value: 'const x = 42' }}/>
```

## License

MIT
