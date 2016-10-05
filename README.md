# node.js-session

```
app.use(express.session([options]));



options         参数的具体取值:

name           :字符串,用于指定用来保存session的cookie名称,默认为coomect.sid.

store          :属性值为一个用来保存session数据的第三方存储对象.

fingerprint    :属性值为一个自定义指纹生成函数.

cookie         :属性值为一个用来指定保存session数据的cookie设置的对象,默认值为{path:”/”,httpOnly:true,maxAge:14400000}.

path            是cookie保存路径.httpOnly是否只针对http保存cookie,

maxAge          用于指定cookie的过期时间,单位为毫秒.

secret          字符串.用来对session数据进行加密的字符串.这个属性值为必须指定的属性.

在使用了session中间件后,代表客户端请求的http.IncomingMessage对象就具有了一个session属性.该属性保存了所有session数据.

```
