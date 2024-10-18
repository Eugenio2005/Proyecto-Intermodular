# Proyecto-Intermodular

## ProyectoDI_Grupo4D

Relaciones en la BBDD:

    Construir un esquema lógico relacional en la BBDD que permita:

        Registrar Usuarios

            Usuarios normales

            Monitores

            Administradores de la App

        Registrar actividades

        Poder relacionar Monitores con Actividades (Asignar Monitor a Actividades)

        Poder relacionar usuarios Actividades (Apuntarte a Clases)

        Poder valorar Actividades
Características de las tablas:

    Atributos de los usuarios (normales, monitores, administradores):

        Nombre 

            Obligatorio

            String

        Apellidos

            Obligatorio

            String

        Teléfono

            Opcional

            Solo numérico

        DNI

            Obligatorio

            String

        Dirección

            Opcional

            String

        CCC

            Obligatorio

            String

        Email

            Obligatorio

            Único

            String

        Password

            Obligatorio

            Que cumpla las siguientes características:

                >8 caracteres

                Que tenga Mayúsculas y Minúsculas

                Que tenga un carácter especial de este tipo: % & $ / *

                Que tenga un número

    Atributos de las actividades:

        Nombre

            Obligatorio

            Único

    Valoraciones de las actividades:

        Numérico del 1 al 5
