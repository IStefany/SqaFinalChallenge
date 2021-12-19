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

![Imagen3](https://user-images.githubusercontent.com/95836335/146692142-dda59cc1-526c-475b-8e70-9c25d531c111.png)

### Steps Definition

En la clase `SqaFinalChallengeStepDefinitions` se relacionan los snippets correspondientes a los escenarios planteados:

![Imagen7](https://user-images.githubusercontent.com/95836335/146692637-cb21d3dc-6cf4-4f7d-b007-c61934ef81c0.png)

### SqaFinalChallengeSteps

En esta clase se declaran los pasos a emplear en los Steps Definitions.

![Imagen12](https://user-images.githubusercontent.com/95836335/146693506-199ca9a5-f4e9-4847-9d57-c53117077fe7.png)

### SqaFinalChallengeHomePageObject

En esta clase se mapean los xpath la barra de búsqueda y el botón de búsqueda de la página principal.

![Imagen9](https://user-images.githubusercontent.com/95836335/146692993-89c6e82f-73eb-43c7-ae56-4649ededf25d.png)

### SqaFinalChallengeProductsPageObject

En esta clase, hacemos uso del método *replace()*, el cual, se utiliza para reemplazar un carácter especifico en una cadena, en este caso especifico, fue usado para reemplazar el nombre del producto en el xpath general.

Con el método *clickOnProduct* le estamos indicando al programa que de click al producto encontrado.

![Imagen11](https://user-images.githubusercontent.com/95836335/146693359-b16e8c4e-0e70-4d39-a2f1-248b4ad4362b.png)

### SqaFinalChallengeProductInfoPageObject

En esta clase se relaciona el xpath para obtener el texto o nombre del producto buscado. 

![Imagen10](https://user-images.githubusercontent.com/95836335/146693176-c8a56d75-3f39-40c9-84ba-23574c33bb05.png)

### Runners

Se configuraron dos runners para ejecutar cada uno de los features; Background y Scenario Template.

![Imagen8](https://user-images.githubusercontent.com/95836335/146692790-6b627253-aef3-442a-b12e-8fd769ac7ab7.png)

## Resultado de las pruebas

### Resultado del Background

Al ejecutar el runner del background `BackgroundRunner `se obtiene como resultado un resultado exitoso, ya que encontró el producto buscado en la pagina web; y un resultado fallido, ya que no encuentra el producto buscado.

![Imagen5](https://user-images.githubusercontent.com/95836335/146692190-6885180c-127b-4b50-875b-5a672c27876c.png)

### Resultado del Scenario Template

Cuanto se ejecuta el runner `SqaFinalChallengeRunner` se obtiene el siguiente resultado en la prueba. Se puede observar que buscó exitosamente los cinco productos relacionados en los **examples**.

![Imagen6](https://user-images.githubusercontent.com/95836335/146692479-4850a02d-669b-40bf-b4ae-0afa7313b9bc.png)

