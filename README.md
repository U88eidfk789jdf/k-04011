[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com//https://U88eidfk789jdf/k-04011.git)

```
addEventListener(
  "fetch", event => {
    let url = new URL(event.request.url);
    url.host = "appname.herokuapp.com";
    let request = new Request(url, event.request);
    event.respondWith(
      fetch(request)
    )
  }
)
```
