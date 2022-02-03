project 1 起動
```
cd project1 && docker-compose -p hoge up

```

project 2 起動
```
cd project2 && docker-compose -p hoge up

```


project1 のサーバに入って project2 の 4567ポートにアクセスする

```
docker exec -it app_project1 bash
curl 'app_project2:4567'
```