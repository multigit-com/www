
![obraz](https://github.com/multigit-com/www/assets/5669657/30cd48d0-b9d2-412d-bc40-c77dd0240ca6)

# [multigit.com](https://www.multigit.com/)

How to load many repositories at once on gitlab, github, ... ?


# hypermodular-gitmodules
About hypermodularity in git modules

## czym jest:

+ dependency - zależność
  + node definition
  + resource - źródło danych
+ datatype - typ danych źródła
+ network definition - struktura, definicja sieci

  

## Principles:

### 1. Flat list of depend source type over the structure 
in the same type of data, resource, source-code

explanation:
tworzenie struktury jest kosztem
aby również struktura była reużywalna warto dbać o to by tworzenie sieci połączeń opierało się na typach danych.
ilość elementów "node" można modyfikować, ale sam punkt połączeń jest definicją sieci i ona powinna pozostać stała.

example:


### 2. functions over variables
Warstwa funkcji nad warstwą zmiennych

explanation:
tworzenie sieci zależności zaczynamy danych, kolejna warstwa to warstwa wykorzystania tych danych lub zbiory jednorodnych typów danych
