c和s最后通信通过对称机密，只不过一开始c把密钥通过s的公钥发送给s
如何保证s公钥的正确性，s用ca的私钥生成数字签名，发送给c，c用ca的公钥解密数字签名，确认公钥的正确性