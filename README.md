## Spring Cloud Gateway组件
可以记录通过gateway转发的请求到日志文件，辅助调试和分析。

配置项 | 含义
------------ | -------------
gateway.log.enable | true或false，是否启用组件.默认true
logging.path | 日志文件夹路径
logging.pattern.file | 日志格式

我当初设计这个功能纯粹是前后端调试时方便撇清后端责任，生产环境慎用。
 