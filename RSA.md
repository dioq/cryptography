# RSA 非对称加密

RSA 公钥加密 私钥解密,反过来数学理论上可行,但实际上会降低加密的安全等级

openssl 生成公钥和私钥
openssl genrsa -out private_key.pem 1024
openssl rsa -in private_key.pem -pubout -out public_key.pem
