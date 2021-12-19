# SqaFinalChallenge

### Contenido del Proyecto

Este proyecto contiene las siguientes carpetas con sus respectivas clases y features:

![Imagen1](https://user-images.githubusercontent.com/95836335/146691112-ff38c264-e6a0-4e03-b97d-6b6f1fd9ac39.png)

## Features

La siguiente carpeta contiene dos features; el primero contiene el Scenario Background y el segundo contiene el Scenario Template.

![Imagen2](https://user-images.githubusercontent.com/95836335/146691271-0f0b4ed5-9fa6-4bdd-9aee-025317efb0e8.png)

### sqaFinalChallenge.feature

En este **feature** se configuró un Scenario Template con algunos **Examples** que permite buscar cinco productos en una pagina web. 

![Imagen4](https://user-images.githubusercontent.com/95836335/146691579-866fe535-1473-4fb0-ba08-428e72de6925.png)

### backgroundFailedAndPassedStages.feature

En este **feature** se configuró un Scenario Background, en el cual se ejecutan dos escenarios; uno exitoso y otro fallido. 

![Imagen3](https://user-images.githubusercontent.com/95836335/146691486-87970106-1221-4664-8971-7f1ce42aa021.png)

## Resultado de las pruebas

### Resultado del Background

Al ejecutar el runner del background `BackgroundRunner `se obtiene como resultado un resultado exitoso, ya que encontró el producto buscado en la pagina web; y un resultado fallido, ya que no encuentra el producto buscado.

![Imagen5](https://user-images.githubusercontent.com/95836335/146692190-6885180c-127b-4b50-875b-5a672c27876c.png)

### Resultado del Scenario Template

Cuanto se ejecuta el runner `SqaFinalChallengeRunner` se obtiene el siguiente resultado en la prueba. Se puede observar que buscó exitosamente los cinco productos relacionados en los **examples**.

![Imagen6](https://user-images.githubusercontent.com/95836335/146692479-4850a02d-669b-40bf-b4ae-0afa7313b9bc.png)

