<p align="center">A Docker PHP development environment that facilitates running PHP Apps on Docker</p>

---

<p align="center">
	<a href="http://laradock.io">
        http://laradock.io
	</a>
</p>

## Using

### start
    docker-compose up -d nginx mariadb phpmyadmin redis workspace php-fpm beanstalkd beanstalkd-console maildev phpredisadmin

### stop

    docker-compose down


### workspace

    docker-compose exec workspace bash



## Web Servers

### Beanstalk console

http://localhost:2080/

### phpredisadmin

http://localhost:9987/

laradock/laradock

### phpmyadmin

http://localhost:8080/

mariadb/root/root


## License

[MIT License](https://github.com/laradock/laradock/blob/master/LICENSE)
