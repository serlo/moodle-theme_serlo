How to develop using Docker

1. `docker compose up -d`
2. `docker compose cp . moodle:/bitnami/moodle/theme/serlo`
3. Go to Browser `http://localhost`, login with

```
user: user
password: bitnami
```

4. If it's your first login, install the theme.  
   Otherwise, go to "Site Administration > Local plugins > Manage local plugins"
5. Select the new theme at 'Site Administration > Appearence > Theme'
