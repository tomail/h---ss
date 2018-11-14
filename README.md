配置环境变量
Config Vars
ADD需要配置 METHOD(加密方法)，PASSWORD(密码，推荐使用`aes-256-cfb`)，SERVER_ADDRESS(`0.0.0.0`) 三个环境变量，PORT：443支持以下加密方法:
* rc4
* rc4-md5
* table
* bf-cfb
* des-cfb
* rc2-cfb
* idea-cfb
* seed-cfb
* cast5-cfb
* aes-128-cfb
* aes-192-cfb
* aes-256-cfb
* camellia-256-cfb
* camellia-192-cfb
* camellia-128-cfb
