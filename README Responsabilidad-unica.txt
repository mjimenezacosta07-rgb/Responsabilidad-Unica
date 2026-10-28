Principio de Responsabilidad Unica
que dice el principio
una clase debe tener una sola responsabilidad, ósea un solo motivo para cambiar
un ejempolo es un rewstaurante cocinero cocina y el mesero atiende las mesas cada uno hace un solo trabajo, su el cociunero también atendeira las mesas haría un caos 

como se implementa rl código 

el programa trabaja con un libro y lo guarda. En vez de hacer todo en una sola clase
se separa en dos clases y cada una tiene un solo trabajo

-la clase libro solo se encarga de los datos del libro (titulo y autor)
-la clase guardar solo se encarga de guardar el libro

asi si mañana se quiere guardar el libro de otra forma (por ejemplo en un archivo)
solo se cambia la clase guardar y la clase Libro queda igual y si se le agrega un dato
nuevo al libro (por ejemplo el año) solo se camba libro


si el metodo GuardarLibro estuviera dentro de Libro la clase tendria dos motivos para
cambiar y ya no cumpliria el principio