[![](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/lukyqwe/V2test1.git)

```js
addEventListener(
    "fetch",event => {
        let url=new URL(event.request.url);lukyqwe/V2test1
        url.hostname="appname.herokuapp.com";
        let request=new Request(url,event.request);
        event. respondWith(
            fetch(request)
        )
    }
)
```