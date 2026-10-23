# cf-worker-resvg
svg2png renderer for cf worker

## usage
add following to each file.

`package.json`
```json
{
  "dependencies":{
    "cf-worker-resvg":"git+https://github.com/mcbeeringi/cf-worker-resvg.git"
  }
}
```

`wrangler.jsonc`
```jsonc
{
	"main":"./index.mjs",
	"assets":{
		"binding":"ASSETS"
	}
}
```

`index.mjs`
```js
export{default}from'cf-worker-resvg';
```
