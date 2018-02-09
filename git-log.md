### git log

Muestra todo el historial de los commits del proyecto

`git log --pretty=format:"%h - %an, %ar : %s"`
Muestra el historial con el formato que indicamos.

` git log --after="2018-02-07" --before="2018-02-08 00:09:35"`
Muestra un rango de fecha

`git log --online`
Este comando nos muestra el historial en una sola linea del commit.