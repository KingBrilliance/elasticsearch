# elasticsearch
the research on the source code of elaticsearch
对ES的读写源码的粗浅分析
EntryTask:
分析es从客户端请求发起到结果返回的整个调用链路（读与写），并对关键函数进行分析说明，最终输出报告（报告需要有详细的请求流转路径，关键函数标注解释），从而为后续的排查一些复杂问题提供支持。