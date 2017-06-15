# Banner outside {#banner-outside}

Módulo con texto fuera de la imagen. En este caso podemos tener solo un link o dos.

En caso de tener dos enlaces la imagen principal enlazará al primer botón \(href\) y el segundo botón a href2.

![](/assets/banner_outside.jpg)

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
| textAlign | Alineación del copy |
| src\_1024 | imagen en resoluciones mayores de 768px |
| src\_768 | imagen en resoluciones menores o igual a 768px |
| src | imagen por defecto |

### Código {#c%C3%B3digo}

---

```
{
    "template": "banner_outside",
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
        "src_1024": "img/image_1024.jpg",
        "src_768":"img/image_768.jpg",
        "src":"img/image_1024.jpg"
      }
}
```

### Medidas imágenes {#medidas-im%C3%A1genes}

---

* Large: no disponible
* Medium: no disponible
* Small: 1086xheight
* Extra small: 768xheight

### Ejemplo {#ejemplo}

---

```
{
    "template": "banner_outside",
    "content":[
        {
            "href": "1317539",
            "href2": "",
            "target": "",
            "target2": "",
            "title": "TRAVEL ESSENTIALS",
            "cta": "<strong>COMPRA AHORA</strong>",
            "cta2": "",
            "src_1024": "img/image_1024.jpg",
            "src_768":"img/image_768.jpg",
            "src":"img/image_1024.jpg"
        }
    ]
}
```



