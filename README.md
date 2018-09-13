## layakeytool

命令行工具管理layacloud节点上Public/Private Key


## 功能和使用方法

````

  Usage: layakeytool [options] [command]

  layacloud Keytool

  Options:

    -V, --version                           output the version number
    -h, --help                              output usage information

  Commands:

    create                                  create a new account and its private key
    list                                    list accounts
    delete [options] <address>              delete a account and its associated key
    key [options] <address>                 show private key info of the specified account
    sign [options] <message>                sign a message. The message could be from a file content referenced by @<path>
    verify [options] <message> <signature>  verify a signature. The message could be from a file content referenced by @<path>
````

