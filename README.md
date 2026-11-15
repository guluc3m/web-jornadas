# GUL Jornadas Webpage

Web para la difusión de las XXXV Jornadas Técnicas del GUL.

## Formato charlas

Las charlas se encuentran en `static/js/charlas.js` en formato JSON, que luego son leidas y mostradas en la página.

```json
dias: [
    {
        id: X,
        charlas: [
            {
                titulo: "Charla 1",
                ponente: "Nombre 1",
                social_network: { // Opcional
                    username: "xX_pepito_Xx",
                    url: "https://epicgames.com/u/xX_pepito_Xx"
                },
                horario: "XX:00 - XX:00",
                aula: "XX.XX.XX"
                descripcion: "Lorem ipsum dolor sit amet"
            }, ...
        ]
    }, ...
]
```
