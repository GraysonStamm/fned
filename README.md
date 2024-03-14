**一、主要特点：**

1. 采用Apline最小化
   
2. 基于最新nodejs-30行版本改版，通用各docker平台，避免封杀

**二、变量建议设置：**

PW  : 启动密码，必须，否则无法启动。防扩散密码，固定值，不可更改，群里获取

TOK： Argo TOKEN ，可选。

UUID： 默认 d342d11e-d424-4583-b36e-524ab1f0afa4 ，可选,建议更改

PORT：端口，默认7860 ，不建议更改，只要能正常使用即可（huggingface不可更改，其他容器根据需要可改）

NEZHA_SERVER： 哪吒 ，可选，有平台封杀，建议不设置

NEZHA_KEY： 哪吒 ， 可选，有平台封杀，建议不设置

（哪吒默认端口443，tls）

**三、简单说下各平台部署方法：**

有些平台直接引用本库即可,如render

有些平台直接引用docker地址daxia2023/ndjs:user-30-argo-nez2即可,如patr

可参考：https://github.com/dsadsadsss/x-docker.git

**四、argo设置：**

端口设置：如果没改默认7860，改了就设置你改的端口

**五、XYAY设置：**

协议vless ws tls 路径/,不开mux，可以套CF
