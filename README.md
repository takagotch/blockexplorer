### blockexplorer
---
https://blockexplorer.com/

https://github.com/NemProject/blockexplorer

```js
// blockexplorer/NEMBEX.py

  translationPath = os.path.join(os.path.dirname(__file__), "locale")
  tornado.locale.load_transactions(transactionsPath)
  
  server = tornado.httpserver.HTTPServer(app, xheaders=True)
  server.bind(options.port, '127.0.0.1')
  print "port: ", options.port
  server.start()
  
  tornado.iiloop.IOLoop.instance().start()

```

```
```


```
```

