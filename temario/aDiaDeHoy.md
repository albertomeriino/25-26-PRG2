# A día de hoy deberíamos saber

> *Entiéndase "deberíamos saber" como una combinación de "nos debería sonar", "no nos debería sorprender", "deberíamos conocer", "deberíamos saber manejar", en función del tema abordado. En cualquier caso, lo mínimo es "no nos debería sorprender" y deberíamos poder tener una mínima conversación o lectura sobre estos temas.*

## 12 may

- Herencia:
  - Herencia por extensión: especialización por adición (atributos, métodos, constructores con `super`) y por redefinición (`@Override`)
  - Miembros protegidos (`protected`): visibilidad y compromisos entre get/set protegidos y atributos protegidos
  - Clases abstractas: no instanciables, métodos abstractos, reglas de herencia entre clases abstractas y concretas
  - Polimorfismo: definición, enlace estático vs dinámico, comportamiento y limitación, polimorfismo vs sobrecarga

## 10 abr

- Diseño descendente con "Flipping on the Beach" (FotB):
  - main limpio como punto de partida
  - "Flipadas" sucesivas: de responsabilidades a colaboradores
  - Visión estática (clases y relaciones) vs visión dinámica (objetos y colaboración)
  - Delegación de tareas y encapsulación efectiva

## 16 mar

- Vista privada de objetos:
  - El estado interno no es observable desde fuera: es lo que garantiza la encapsulación
  - Desencadenamiento de instanciaciones y mensajes internos en tiempo de ejecución
  - Dos objetos con representaciones internas distintas pero comportamiento público idéntico son indistinguibles

## 10 mar

- Vista privada de clases:
  - Definición de atributos: datos constantes, variables de tipos primitivos, referencias a objetos
  - Inicialización de atributos mediante constructores, valores por defecto
  - Definición de métodos: cuerpo, acceso a atributos, parámetros y declaraciones locales
  - Referencia `this`: resolución de colisión de identificadores, reutilización de constructores y métodos
  - Métodos privados: reutilización interna dentro de la clase

## 3 mar

- Vistas: introducción al concepto de ámbitos público y privado
- Vista pública de objetos: repaso y consolidación de creación de objetos, referencias y paso de mensajes

## 3 feb

- Consideraciones básicas de diseño de vistas públicas

## 27 feb

- Clases de soporte: clase Console y fundamentos de la clase String
- Vista pública de objetos:
  - Creación de objetos, referencia a un objeto, vectores de objetos, referencia a un vector de referencias a objetos
  - Paso de mensajes

## 24 feb

- Vista pública de clases:
  - Nombre de la clase
  - Cabecera de métodos de la clase, sobrecarga de métodos
  - Constructores

## 20 feb

- Sistemas complejos y por qué necesitamos software
- Los 4 pilares: abstracción, encapsulación, modularización, jerarquización
- Evolución histórica de los lenguajes hasta POO: POO = TAD + herencia + polimorfismo
- Conceptos básicos: clase, objeto, mensaje, método, atributo, estado / Vista pública (interfaz) & vista privada (implementación)

## 10 y 13 feb

- Qué hacer ante un código heredado
- Cómo ir tendiendo hacia una modularización en programación estructurada
- Criterios para nombrar y describir commits
- Solución de problemas con ramas

## 6 feb

- Criterios de refactorización que conduzcan a un main() limpio como objetivo.
- Como dejar una historia adecuadamente contada en los commits del repo.
- Ejemplo hecho en clase: un [refactor...](https://github.com/ibuprofenofernandez/25-26-PRG2/commits/reto-001)
  - [Código limpio!](https://github.com/ibuprofenofernandez/25-26-PRG2/commit/30aa0d0792f47e7924420b4f8abe5b754d406c42)

## 3 feb

- Repaso de PRG1 e iGPySw
