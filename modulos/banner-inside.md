# Banner inside {#banner-inside}

Módulo cuyo texto queda por encima de la imagen. En este caso podemos tener solo un link o dos.

En caso de tener dos enlaces lo único que será clicable del módulo serán los botones. Cuando solo tenemos un enlace todo el módulo será clicable.

![](/assets/banner_inside.jpg)

### Opciones del módulo {#opciones-del-m%C3%B3dulo}

---

| Campo | Explicación |
| :--- | :--- |
| href | Enlace de la categoría o página |
| href2 | Enlace de la categoría o página del segundo enlace |
| target | Link externo o interno |
| target2 | Link externo o interno del segundo enlace |
| previous\_title | texto antes del titular \(ej: categoría\) |
| title | titular del módulo |
| subtitle | Subtitular |
| excerpt | texto |
| cta | texto del botón |
| cta2 | texto del segundo botón |
| textColor | color del copy,[ver apartado colores](../../../colores.md) |
| position-x | Alineación del copy en horizontal |
| position-y | Alineación del copy en vertical |
| src\_1280 | imagen en resoluciones mayores de 1024px |
| src\_1024 | imagen en resoluciones de entre 768px y 1024px |
| src\_768 | imagen en resoluciones menores o igual a 768px |
| src | imagen por defecto |

### Código {#c%C3%B3digo}

---

```
{
    "template": "banner_inside",
    "content":{
        "href":"url",
        "href2":"url del segundo link",
        "target":"_self | _blank",
        "target2":"_self | _blank",
        "previous_title": "Previo",
        "title": "título",
        "subtitle": "subtitular",
        "excerpt": "texto",
        "cta": "copy call to action",
        "cta2": "copy del segundo call to action",
        "textColor":"white | black | brand",
        "position-x":"left | center | right",
        "position-y":"top | center | bottom",
        "src_1280": "img/image_1280.jpg",
        "src_1024": "img/image_1024.jpg",
        "src_768":"img/image_768.jpg",
        "src":"img/image_1024.jpg"
      }
}

```



### Medidas imágenes {#medidas-im%C3%A1genes}

---

* Large: no disponible
* Medium: 1326xheight
* Small: 970xheight
* Extra small: 768xheight

### Ejemplo {#ejemplo}

```
{
    "template": "banner_inside",
    "content":[
        {
            "href": "1317539",
            "href2": "",
            "target": "",
            "target2": "",
            "title": "TRAVEL ESSENTIALS",
            "cta": "<strong>COMPRA AHORA</strong>",
            "cta2": "",
            "position-x":"left",
            "position-y":"bottom",
            "src_1280": "img/image_1280.jpg",
            "src_1024": "img/image_1024.jpg",
            "src_768":"img/image_768.jpg",
            "src":"img/image_1024.jpg"
        }
    ]
}

```



