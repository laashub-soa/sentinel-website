# 日志

默认的日志目录为 `~/logs/csp` 目录（与 Java 版本保持一致）。日志目录可在初始化日志时进行指定。

## 秒级监控日志

请参考 [metric 日志文档](https://github.com/sentinel-group/sentinel-golang/wiki/实时监控#秒级监控日志)。

## record 日志

其它的日志位于 `${user_home}/logs/csp/sentinel-record.log.xxx`。该日志包含规则的推送、接收、处理等记录，排查问题的时候会非常有帮助。