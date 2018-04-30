KodeCMS
========================
### Symfony4 CMS from developers for developers

KodeCMS is Symfony 4 based CMS/CMF designed to be easily 
maintainable by a developer and understandable by user

Requirements
-----
* PHP ^7.1
* Redis
* MySQL / MariaDB / SQLite
* [Symfony application requirements][1]

Installation
-----
```bash
composer create-project kode-cms/kode-cms:dev-master
```

Usage
-----
There's no need to configure anything to run the application. Just execute this
command to run the built-in web server and access the application in your
browser at <http://localhost:8000>:

```bash
$ cd kode-cms/
$ php bin/console server:run
```

Alternatively, you can [configure a fully-featured web server][2] like Nginx
or Apache to run the application.  
`* No need to additionally require symfony/apache-pack as it
is already a dependency of this application.`

[1]: https://symfony.com/doc/current/reference/requirements.html
[2]: https://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html