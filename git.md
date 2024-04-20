## Error Acceso Denegado a un nuevo usuario Github en el comando: GIT PUSH.

Lo único que tuve que hacer aparte de cambiar el email y el user name en el config de git, fue correr el comando

```
git config --local credential.helper ""
```

para así poner el default y borrar las credenciales del anterior usuario.