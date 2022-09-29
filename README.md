# Git y un mundo por explorar

### git pull --rebase vs git pull

- Cuando trabajamos en una rama ajena a main y traemos los cambios usando un git pull sin la etiqueta rebase, esperamos que en el histórico se vean los commits realizados en la rama hija.
- Cuando trabajamos en una rama ajena a main y traemos los cambios usando un git pull con la etiqueta rebase, esperamos que en el histórico se vean los commits realizados en el mismo nivel que en la rama principal.

Para revisar si se cumple o no lo descrito anteriormente, debemos realizar un git log después de hacer el merge de los dos casos sobre la rama principal.
