# amr.js 源码解析（一）

---

根据[amr.js](https://github.com/jpemartins/amr.js)进行逐步源码分析,其中涉及amr文件格式分析，以及其他一些内容。

### 前置知识

[AMR文件格式分析](http://blog.csdn.net/dinggo/article/details/1966444)

[amr文件格式解析](http://blog.csdn.net/qingye2008/article/details/26101481)

[AMR格式标准文档](http://ietfreport.isoc.org/rfc/PDF/rfc3267.pdf)

### amr.js所依赖的libamr-nb.js

libamr-nb.js是使用Emscripten将[OpenCORE](https://github.com/android/platform_external_opencore)的amr_nb编解码模块转换过来的js库,读者若感兴趣，可直接阅读[源码](https://github.com/android/platform_external_opencore/tree/master/codecs_v2/audio/gsm_amr/amr_nb)

### 为何只采用amr-nb?

Android支持的音频编解码仅为AMR_NB

---

*To be continue*
