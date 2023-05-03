
# webserv

This project is a C++ HTTP/1.1 server.





## Deployment

run ```make``` to create and execute
 
```bash
    ./webserv path/server.conf
```

If you don't specify the ```server.conf``` we set the default path to ```conf/config.conf```

For example with the default ```conf/config.conf```, you can now connect to the server with ```nc``` like the command bellow.

```bash 
    nc localhost 8001
```

The default port in ```conf/config.conf``` is set to ```8001```, you can change it.







## Authors

[@lenphatos](https://www.github.com/lenphatos)

