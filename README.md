INURLBR-API-DecrypterMD5
========================

![alt text](https://pbs.twimg.com/media/BszUUqyCMAE8Xh5.png "INURLBR-API-DecrypterMD5")
[**FACEBOOK**](https://fb.com/InurlBrasil) / [**TWITTER**](https://twitter.com/googleinurl)

>Utilizando serviço decrypter do site md5.gromweb.com é possível descriptografar senhas em massa, seja de um arquivo em texto ou pesquisa single.

[+] Pesquisa por arquivo
------
```
php md5.php --file filemd5.txt
```

[+] Pesquisa single
------
```
php md5.php --md5 21232f297a57a5a743894a0e4a801fc3
```
[+] Proxy camuflagem envio de request.
------
```
    - Exemplo: --proxy {proxy:porta}
    - Uso:     --proxy localhost:8118
               --proxy socks5://googleinurl@localhost:9050
               --proxy http://admin:12334@172.16.0.90:8080
``` 
[+] Pesquisas em massa.
>
Deve-se usar o proxy tor, pois ao indentifcar um "x" numero de requisições em 
seus servidores o md5.gromweb.com efetua o devido bloquio, com isso o script
identifica e já renova seu ip na rede tor.

Esse comando só é executado caso tenha preenchido a opção -proxy {proxy}.
Para que tal função tenha funcionamento deve-se instalar o aplivativo tor.
A cada bloquio dos servidores o script renova seu ip na rede TOR será renovado.
Ajuda:                                                                                    
 * - https://www.torproject.org/docs/debian.html.en
 * - http://www.privoxy.org/
