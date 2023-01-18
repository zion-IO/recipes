
building blocks and recipes;

## instrutions

# RETO 1 (Pull Request)

### 1. install nodejs (si no lo tienen instalado)
### 2. install git (si no lo tienen instalado)
### 3. Entrar a la Terminal en su computadora y escribir el siguiente comando para clonar el repositorio

```bash
git clone https://github.com/zion-IO/recipes.git
```

### 4. Entrar a la carpeta recipes y abrir el proyecto en su editor de codigo favorito

```bash

```bash
cd recipes
```
### 5. No se espanten ... no van a codear, solo van a copiar y pegar.

### 6. Crear una rama con el nombre de su receta Ej, feature/pastel-de-zanahoria

```bash
git checkout -b feature/nombre-de-la-receta
```

### 7. crear un archivo .md (markdown) con el nombre de su receta dentro de la carpeta recipes

### 8. copiar y pegar una receta en su archivo .md con el siguiente formato

# Nombre de la receta
## Ingredientes
* 1 taza de harina
* 1 taza de azucar
* 1 taza de leche
* 1 taza de aceite
* 1 cucharadita de polvo de hornear
* 1 cucharadita de sal
* 1 cucharadita de vainilla

## Preparacion

1. Mezclar todos los ingredientes
2. Hornear a 180 grados por 30 minutos

### 9. Guardar el archivo .md
### 10. Abrir la terminal y ejecutar el siguiente comando

```bash
git add .
git commit -m "feature(receta): descripcion de la el trabajo realizado"
Ej. feature(receta): agregue la receta de pastel de zanahoria
```

### 11. Subir los cambios a github

```bash
git push origin feature/nombre-de-la-receta
```

### 12. Crear un pull request en github

### 13. Esperar a que alguien revise su receta y la apruebe

### 14. Felicidades, ya tienes una receta en el libro de cocina de Zion

# RETO 2 (Code Review)

### 1. Entrar a Github y buscar el pull request de su compañeros (por lo menos 2 PRs)
### 2. Hacer un code review de su compañeros
### 3. Comentar en el PR de su compañeros
### 4. Esperar a que su compañero apruebe su code review

# RETO 3 (Merge)

### 1. Si el PR ya esta aprobado por su compañero, proceder a hacer el merge de sus respectivas ramas

### 2. descargar develop actualizado con los cambios de su compañeros

### 3. Modificar por lo menos 2 recetas que no publicaron ustedes
### 4. Crear un pull request de su rama nueva a develop

### 5. Esperar a que alguien revise su receta y la apruebe (Code Review como en retos anteriores).

# RETO 4 (CONFLICTOS)

### 1. Crear una rama nueva para hacer un fix sobre la receta de los Chilaquiles

### 2. Modificar la receta de los Chilaquiles y agregarle un ingrediente nuevo.

### 3. Crear un pull request de su rama nueva del fix de los chilaquiles a develop

### Buscar que haya conflictos con el PR de su compañero

### 4. Resolver los conflictos y hacer el merge de su PR

### 5. Felicidades, ya tienes una receta muy completa (CHILAQUILES) en el libro de cocina de Zion-IO

# TASKS

1. Identificar las posibles soluciones para resolver los conflictos
2. Documentar el proceso de como resolver los conflictos en el README.md
