# MetaDev

Le docker-compose.yml comporte les services fonctionnels en lien avec LDAP

Pour tester le fonctionnement du LDAP :

```bash
ldapsearch -H ldap://localhost -x -D "cn=admin,dc=example,dc=org" -W -b "dc=example,dc=org" "(uid=melguermat)" userPassword
```
