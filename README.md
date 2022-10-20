# Trabajo Practico Integrador N°1.
## Alumno Nicolas Leali.

Dataset:
**Disney Character Success**

[link](https://www.kaggle.com/datasets/thedevastator/disney-character-success-a-comprehensive-analysi?select=disney-characters.csv)

Introduccion.
=============


Estructura del dataset.
=======================

El dataset poseé 4 archivos .csv. Cada uno 
Tres de estos archivos funcionan como vistas y dos poseen datos numericos o fact tables.

## Vistas.
- disney-characters
- disney-voice-actors
- disney-directors

## Fact
- disney_movies_total_gross
- disney_total_revenue_1911-2016

TABLA DETALLES
===============

## disney-characteres

- movie_title: The title of the movie. (String)
- release_date: The release date of the movie. (Date)
- hero: The main character of the movie. (String)
- villian: The villain of the movie. (String)
- song: A song associated with the movie. (String)

## disney-director

- name: The name of the mvie (String)
- director: The name of the director (String)

## disney-voice_actor

- character: The name of the character. (String)
- voice-actor: The name of the voice actor. (String)
- movie: The name of the movie. (String)

## disney_movies_total_gross

- movie_title: The title of the movie. (String)
- release_date: The release date of the movie. (Date)
- genre: The genre of the movie. (String)
- MPAA_rating: The MPAA rating of the movie. (String)
- total_gross: The total gross of the movie. (Integer)
- inflationadjustedgross: The inflation-adjusted gross of the movie. (Integer)

## disney_total_revenue_1911-2016

- Year: The year the movie was released. (Numeric)
- Studio Entertainment[NI 1]: The studio entertainment segment of the Walt Disney Company. (String)
- Disney Consumer Products[NI 2]: The consumer products segment of the Walt Disney Company. (String)
- Disney Interactive[NI 3][Rev 1]: The interactive segment of the Walt Disney Company. (String)
- Walt Disney Parks and Resorts: The parks and resorts segment of the Walt Disney Company. (String)
- Disney Media Networks: The media networks segment of the Walt Disney Company. (String)
- Total: The total box office gross for the movie. (Numeric)
