# demo-junit

Demostración de cómo implementar tests unitarios para un componente Calculadora usando JUnit y del uso de mocks usando Mockito

## Ejercicio

1. Crear un test dummy con la anotación @Test y usando métodos de org.junit.jupiter.api.Assertions
2. Crear tests unitarios del método division de Calculadora:
   1. Dos positivos
   2. Dos negativos
   3. División por cero
3. Agregar en Calculadora una dependencia con el componente LogaritmosApiClient para calcular logaritmos
4. Crear nuevos tests unitarios del metodoo logaritmo, haciendo mocks del nuevo componente
5. Refactorizar código repetido a un método de setup usando @BeforeEach