# gulp-timestamp-append

`npm i -D gulp-timestamp-append`

具体使用参考 https://github.com/bustardcelly/gulp-rev-append

用法一样，只是把 md5 换成了时间戳
因为 gulp-rev-append 只能通过 html 引用的相对路径读取本地的文件，然后通过 md5 加密生成一个 hash 字符串，但是对于一些完整路径的引用会有问题，所以换成这个生成时间戳，也只是一个暂时的办法
