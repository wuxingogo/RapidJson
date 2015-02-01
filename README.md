# RapidJson
Rapid Using Json in Cocos2D-X 3.x


这个类是我的再一次封装,只是为了能更快速更深层的理解的使用Json数据在Cocos2D-X3.x里

其实集成的RapidJson是很快速的,主要是使用的时候,api写法有些不好，所以我再次封装了一下

其中里面有三个类来帮助使用

JsonParser  主要是对文件的读取,把文件读取到了内存中

JsonObject  每一个Json数据都是一个JsonObject,可以是int,float,char,或者array

JsonArray   继承自JsonObject,不过每一个元素都是int,float,char====

读取一个Json文件,要获得RootJson

RootJson是一个JsonObject

然后由这个RootJson再进行查询嵌套的数据进行查找....
