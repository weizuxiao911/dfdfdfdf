## dsadsd
```python linenos
const http = require('http')

const hostname = '127.0.0.1'
const port = 3000

const server = http.createServer((req, res) => {
  res.statusCode = 200
  res.setHeader('Content-Type', 'text/plain')
  res.end('Hello World\n')
})

server.listen(port, hostname, () => {
  console.log(`Server running at http://${hostname}:${port}/`)
})
```
```
如何创建一个目录
```{{copy }}
```
mkdir textLiu
```{{exec :verify1}}
```
ls textLi
```{{validate}}

```
ls textLiu
```{{validate :verify1}}

```
ls textLi
```{{validate ::next}}
#s dsddsd
dadsd