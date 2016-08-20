Simplest Express Demo
=====================

```
npm install
```

Run:

```
node index.js
```

Visit:

```
http http://localhost:3000/set-cookies
```

you will see `Set-Cookie` in the response body:

```
Set-Cookie: token=mike%3A123456; Path=/
```

Then use your browser(which sends the cookie from browser to server automatically) to visit:

```
http http://localhost:3000/set-cookies
http http://localhost:3000/cookies
```

you will see the cookie in the browser.