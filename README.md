# Coba-addilu

El circuito digital ADDILU funciona como un acumulador en la arquitectura de computadoras. Es un sistema secuencial diseñado para mantener un total actualizado. En lugar de hacer una suma simple y descartar los números, toma un valor de entrada nuevo, lo suma al valor previamente guardado en su memoria y sobreescribe el total con ese resultado final.

Esta lógica se aplica en múltiples aparatos cotidianos. Los medidores inteligentes de electricidad o agua la utilizan para sumar el consumo continuo mensual. También se encuentra en el procesamiento de audio y video para aplicar filtros digitales, en los cuentakilómetros de los vehículos para registrar la distancia recorrida y en los registros internos de las computadoras al procesar grandes volúmenes de datos.

En la práctica, este sistema de 16 bits utiliza un sumador aritmético y un Flip-Flop tipo D  como memoria. La clave del circuito es su retroalimentación: el resultado del sumador se guarda en el Flip-Flop, y ese valor almacenado vuelve a ingresar al sumador como base para la siguiente cuenta. Todo el ciclo se coordina con una señal de reloj que marca el momento exacto para actualizar los datos, y arranca con un valor constante en cero  para evitar arrastrar errores de cálculos previos.
