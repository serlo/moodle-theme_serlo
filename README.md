How to develop using Docker

1. `docker compose up -d`
2. `docker compose exec moodle ln -s /serlotheme /bitnami/moodle/theme/serlo`
   (you may need to wait about a minute until the folder `/bitnami/moodle` is populated)
3. Go to Browser `http://localhost`, login with

```
user: user
password: bitnami
```

4. If it's your first login, install the theme.  
   Otherwise, go to "Site Administration > Local plugins > Manage local plugins"
5. Select the new theme at 'Site Administration > Appearence > Theme'
6. When you're done developing -> `docker compose down -v`
