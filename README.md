Archivo JSON:

{"cartelera": [
    {
        "idioma": "inglés",
        "titulo": "Inception",
        "director": "Christopher Nolan",
        "duracion": 148,
        "reparto":{
            "actores":[
                {
                    "protagonista": true,
                    "nombre": "Leonardo DiCaprio",
                    "personaje":  "Dom Cobb"
                },
                {
                    "protagonista": false,
                    "nombre": "Joseph Gordon-Levitt",
                    "personaje": "Arthur"
                }
            ]

        },
        "premios":[
            "Oscar a mejores efectos visuales",
            "Oscar al mejor sonido"
        ],
        "fotos":[
            {
                "tipo": "cartel",
                "nombre": "inception_poster.jpg"
            },
            {
                "tipo": "escena",
                "nombre": "inception_scene1.jpg"
            }
        ]
    },
    {
        "idioma": "italiano",
        "titulo": "La dolce vita",
        "director": "Federico Fellini",
        "duracion": 174,
        "reparto":{
            "actores":[
                {
                    "protagonista": true,
                    "nombre": "Marcello Mastroianni",
                    "personaje": "Marcello Rubini" 
                },
                {
                    "protagonista": false,
                    "nombre": "Anita Ekberg",
                    "personaje": "Silvia"
                }
            ]
        },
        "premios": [
            "Palma de oro del Festival de Cannes"
        ],
        "fotos":[
            {
                "tipo": "cartel",
                "nombre": "ladolcevita_poster.jpg"
            },
            {
                "tipo": "escena",
                "nombre": "ladolcevita_scene1.jpg"
            }
        ] 
    }
]
}

Archivo XML:

<?xml version = "1.0" encoding = "UTF-8"?>

<series>
    <serie>
        <title> Breaking Bad </title>
        <seasons> 5 </seasons>
        <is_completed> true </is_completed>
        <genres>
            <genre> Crimen </genre>
            <genre> Drama </genre>
            <genre> Thriller </genre>
        </genres>
        <main_cast>
            <actor>
                <name> Bryan Cranstron </name>
                <role> Walter White </role>
            </actor>
            <actor>
                <name> Aaron Paul </name>
                <role> Jesse Pinkman </role>
            </actor>
        </main_cast>
        <ratings>
            <imdb> 9.5 </imdb>
            <rotten_tomatoes> 96 </rotten_tomatoes>
        </ratings>
    </serie>
    <serie>
        <title> Stranger Things </title>
        <seasons> 4 </seasons>
        <is_completed> false </is_completed>
        <genres>
            <genre> Science Fiction </genre>
            <genre> Drama </genre>
            <genre> Horror </genre>
        </genres>
        <main_cast>
            <actor>
                <name> Millie Bobby Brown </name>
                <role> Eleven </role>
            </actor>
            <actor>
                <name> Finn Wolfhard </name>
                <role> Mike Wheeler </role>
            </actor>
        </main_cast>
        <ratings>
            <imdb> 8.7 </imdb>
            <rotten_tomatoes> 93 </rotten_tomatoes>
        </ratings>
    </serie>
</series>
