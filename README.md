# ArquiteturaJavaSpringJpaMySql

Para testar é necessário ter Docker instalado na máquina e executar o seguinte comando:

docker run --name mysql -e MYSQL_ALLOW_EMPTY_PASSWORD=yes -v {localVolume}:/var/lib/mysql -p 3306:3306 -d mysql
