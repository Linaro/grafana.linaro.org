# deploy to a remote server

Update hosts file and then:

```
ansible ansible/site.yml
```

Bear in mind that SSL is setup in grafana conf, you'll have
to provide keys manually in /etc/grafana/letsencrypt

Also, grafana database config credentials need to be
updated in /etc/grafana/grafana.ini
