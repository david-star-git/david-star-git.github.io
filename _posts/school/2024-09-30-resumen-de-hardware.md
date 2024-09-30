---
title: Errores Comunes y Soluciones en Componentes de PC
description: Guía para diagnosticar y solucionar errores frecuentes en hardware de computadoras, incluyendo monitor, teclado, mouse, RAM, procesador, disco duro, placa madre y fuente de alimentación.
author: david
date: 2024-09-30 07:00:00 -0400
categories: [School, Hardware]
tags: [hardware]
pin: false
math: false
mermaid: false
comments: false
---

# TEMA: Errores Típicos y Posibles Soluciones (Partes Externas)

## Capacidad
- Diagnosticar con solvencia técnica proporcionando soluciones a los problemas frecuentes.

## Actividades

### Monitor

- **El Equipo No Da Video**
  1. Verifique el cable de alimentación AC (Cable A) y que el monitor esté encendido.
  2. Pruebe un cable de monitor que funcione (Cable B). Si el Cable A no enciende y el Cable B sí, reemplace el Cable A.
  3. Verifique el cable RGB conectado a la tarjeta de video. Si hay daños, reemplace o repare el cable RGB.

- **Las Imágenes Del Monitor No Tienen Todos Los Colores**
  1. Verifique los controladores de video en el Administrador de Dispositivos. 
     - **Posibles causas de un signo de exclamación:**
       - Controladores no instalados correctamente.
       - Conflicto de recursos.
       - Configuración incorrecta del adaptador de video.
  2. Si inicia en Modo a Prueba de Fallos, revise el motivo.
  3. Verifique el cable RGB, ya que un color primario dañado puede causar problemas en la visualización.

### Teclado

- **Teclado No Responde**
  1. Reinicie el equipo; Windows puede haber colgado.
  2. Pruebe la tecla DEL en modo MS-DOS.
  3. Verifique el cable del teclado con un multímetro. Si está dañado, reemplace o repare el cable.
  4. Pruebe el teclado en otro equipo. Si no responde, reemplácelo.

### Mouse

- **Problemas en Mouse Ópticos**
  1. El mouse óptico tiene un sistema complejo que utiliza un LED rojo y un sensor CMOS.
  2. Los problemas pueden incluir falsos contactos debido al óxido en los conectores.
  3. Verifique la conductividad de las resistencias de superficie con un tester.
  4. Reemplace componentes dañados como el LED rojo.

### Problemas de Temperatura

- **Prevención de Problemas de Temperatura**
  1. Mantener el PC limpio, limpiando ventiladores y disipadores.
  2. Tener un buen ventilador y disipador para el microprocesador.
  3. Comprobar periódicamente la pasta térmica del microprocesador.
  4. Testear las temperaturas con software especializado.
  5. Evitar colocar el PC en lugares con mala ventilación.



# TEMA: Errores Típicos y Posibles Soluciones (Partes Internas)

## Capacidad:
- Diagnostica con solvencia técnica proporcionando soluciones a los problemas frecuentes.

## Actividades

### Memoria RAM
Las memorias RAM son uno de los componentes más importantes en nuestra computadora, ya que, junto con la motherboard, el procesador y el disco rígido, es la que nos permite que nuestra PC funcione, y además las capacidades que posea la memoria inciden directamente en la velocidad y rendimiento que alcance el equipo.

Al igual que el resto de los componentes de hardware de la PC, los módulos de memoria RAM pueden presentar con el correr del tiempo algunos inconvenientes en su funcionamiento, provocando que el rendimiento de nuestra PC disminuya considerablemente.

Es por esto que te ayudaremos a que identifiques los problemas más comunes de la memoria RAM y que conozcas sus posibles soluciones.

- **Falla:** Manda un mensaje de error de insuficiente memoria para trabajar  
  **Solución:** Vacuna el equipo, instalar un antivirus y mantenerlo actualizado.
  
- **Falla:** El ordenador no arranca.  
  **Solución:** Verificar que está insertada correctamente la memoria. Comprobar que los bancos se han llenado de la forma adecuada y, en los casos necesarios, con módulos de la misma capacidad y mismo tipo. Si tras hacer todo esto sigue sin funcionar, la memoria será defectuosa o estará averiada.
  
- **Falla:** El sistema no reconoce toda la memoria instalada. (Durante el arranque del ordenador aparecerá un mensaje de error indicando que hay un error en la CMOS relativo al tamaño de la memoria)  
  **Solución:** Entraremos en la BIOS y saldremos guardando los cambios para que el sistema reconozca toda la memoria.

### Procesador
El microprocesador es un componente que, dada su estructura, no tiene muchas opciones de reparación. Hay una serie de factores externos que afectan su funcionamiento y que, aunque no siempre llegan a dañarlo, generan síntomas muy diversos.

- **Fallas:** El equipo se torna inestable, presenta cuelgues en aplicaciones que requieren mayores recursos, pero luego la circunstancia se repite aun frente a las tareas más simples. Reinicio repentino, pantallas azules al azar, errores de lectura de disco y disminución notable del rendimiento.  
  **Solución:** El setup de muchos motherboards posee una página donde se informa la velocidad de rotación de la turbina y la temperatura del microprocesador. Otra alternativa para verificar estos parámetros es utilizar un software como: hardware sensor monitor. Si la velocidad de rotación es inferior a las 3000 RPM y la temperatura supera los 60° C, será entonces el momento de actuar. Primero quitamos la turbina (por lo general, sostenida al disipador con cuatro tornillos); observaremos el eje de rotación en su parte inferior oculto bajo un pequeño tapón de goma. Una vez al descubierto, aplicamos una gota de aceite de máquina y giramos manualmente las paletas, de manera que éste se impregne a lo largo de todo el eje. Luego retiramos el disipador y aplicamos una pizca de grasa siliconada en la cara que hace contacto en el micro (la cual ayuda a transmitir el calor entre ambos), en caso de que ya no haya más o esté reseca. Armamos todo y efectuamos otra medición de la temperatura y de la rotación.
  
- **Falla:** El equipo no arranca y el microprocesador no se calienta.  
  **Solución:** Posiblemente la tensión de trabajo no sea la adecuada. Revisaremos con un voltímetro la fuente de alimentación. Puede ser que esté seleccionada una tensión de 3,3 voltios cuando el micro necesite unos 5 voltios. Si, por el contrario, hacemos trabajar un micro en base a 5 voltios, tampoco arrancará, pero en este caso el micro se calentará. Si mantenemos esa tensión mucho tiempo, acabará quemándose, por lo tanto, hay que apagar el equipo lo antes posible.

### Disco duro
#### Errores lógicos
Son los más comunes y pueden estar presentes tanto en discos duros como en memorias flash o USB, y son fallos de los sistemas de archivos del disco duro o problemas de software. También se deben a fallos humanos. Estos fallos pueden impedir que se acceda a algún archivo, que aparezcan carpetas donde su contenido desapareció o que el sistema operativo no detecte el disco duro porque la tabla de particiones esté dañada. Pueden producirse por:
- Virus o malware.
- Borrado de datos.
- Corrupción de datos.
- Formateos.
- Tablas de particiones corruptas o dañadas.

Si se produce un error lógico, se recomienda no utilizar ni guardar datos en el disco duro (y menos aún realizar un formateo o usar programas para intentar repararlo), ya que cada escritura dificultará la recuperación de los archivos al sobrescribir los sectores afectados. Lo mejor en estos casos es usar programas como “TestDisk” o “Photo Rec” (disponible para Linux y Windows). Estos programas son capaces de reparar tablas de particiones defectuosas o leer el contenido del dispositivo bit a bit para intentar recuperar la información.

#### Errores electrónicos
Este tipo de errores también son muy comunes. En este caso, la placa PCB del disco duro se daña y es más difícil de reparar, ya que deberíamos adquirir otro disco duro idéntico para cambiar la placa y repararlo. Aunque en la mayoría de los casos, este tipo de error hace que algún sector se dañe al rozar la cabeza lectora con los discos y quede defectuoso, con lo que deberíamos usar algún programa de recuperación de datos. Suelen ser producidos por:
- Cambios bruscos de temperatura y/o humedad.
- Bajadas o subidas de tensión (picos de tensión).

Si se produce este tipo de error, no es aconsejable intentar iniciar el disco duro quemado, ya que se dañaría aún más, y tampoco es recomendable abrir el disco duro, ya que una mota de polvo podría dañar los datos contenidos en los discos magnéticos. Lo recomendable sería apagar el ordenador y desconectar el disco duro para llevarlo a reparar.

#### Errores mecánicos
Estos errores son los más difíciles de reparar y podemos detectarlos cuando la BIOS no detecta el disco duro, el disco duro hace ruidos o produce fuertes vibraciones o incluso la superficie de los platos magnéticos está dañada. Suelen producirse por:
- Caídas o golpes.
- Sectores defectuosos.
- Fallos de fabricación.
- Fallo o rotura de las cabezas lectoras.
- El desgaste o la corrosión.
- Parada o fallo del motor que realiza el giro para leer los datos.
- HeadCrash (se produce cuando las cabezas lectoras se posan sobre los discos magnéticos, rayando la superficie, y la recuperación de los datos sería prácticamente imposible).

En este caso, lo más recomendable es no intentar arreglarlo para no dañarlo más y llevarlo a una empresa especializada en recuperación de datos, ya que cuentan con las herramientas y repuestos necesarios para realizar la reparación, aunque esto suele salir caro.

#### Errores de firmware
Este tipo de errores son más difíciles de detectar, ya que el sistema operativo y la BIOS no son capaces de detectarlo. En este caso, el disco duro no hará ruidos extraños, pero sí encenderá. Pueden reconocerse por:
- El disco duro no arranca, pero gira el motor y se mueven las cabezas lectoras.
- El sistema operativo y la BIOS no reconocen el disco duro.
- La BIOS reconoce el disco duro con 0 GB de capacidad y sin poder acceder a los datos.
- Algunos discos duros tienen bugs en sus firmwares.

Lo recomendable en estos casos es no utilizar el disco duro, ya que podría quedar inservible y sin poder recuperar la información.

### Placa madre
Todos aquellos que tenemos una PC en nuestra casa o en la oficina sabemos que está compuesta por múltiples componentes. Uno de ellos, tal vez el más importante, es la placa madre, también llamada motherboard o placa base. Todas las placas madre están compuestas por chips, capacitores (o condensadores), y otros elementos que serán mencionados en otra ocasión.

- **Falla:** Agotamiento de la pila o batería.  
  **Solución:** Cuando se agota la pila o la batería del ordenador, aparecerá un mensaje en pantalla del tipo CMOS checksum error. Esta avería es sencilla de reparar; se sustituye la pila por otra nueva y no hay más.
  
- **Falla:** El equipo sufre reinicios inesperados, pantallas azules en Windows o, incluso, falla en la copia de los archivos, pero en este caso se suma la presencia de un extraño olor que surge del CPU.  
  **Solución:** Podremos observar a simple vista los capacitores afectados, ya que habrá un líquido marrón que brota de su parte superior y una notable hinchazón en el cilindro. Una vez identificamos todos los capacitores, procedemos a reemplazarlos haciendo uso de un soldador. Esta es una reparación delicada que requiere paciencia y buenas herramientas, ya que, si no es realizada de la manera adecuada, puede dañar otros componentes.
  
- **Falla:** El ordenador se apaga o reinicia inesperadamente.  
  **Solución:** Este síntoma puede provenir de varios factores: el software, la fuente de alimentación, la memoria RAM, o incluso la placa madre. Para determinar cuál de ellos está fallando, habrá que ir probando con cada uno de los componentes hasta dar con el que causa la falla. Por ejemplo, empezaremos a descartar conectando un monitor externo para descartar que el problema no esté en la tarjeta gráfica, y así sucesivamente.
  
- **Falla:** Error en las conexiones SATA.  
  **Solución:** Se observan fallas que imposibilitan la lectura de datos, que son producidas por diversos factores: un cable SATA defectuoso, un conector SATA sucio o dañado, o un puerto SATA fallido. Para corregir este error, comenzaremos revisando que no haya problemas con el cable, lo que incluye verificar que no tenga cortes ni esté desconectado en la parte trasera de la unidad. Luego continuaremos limpiando el puerto de conexión. Una vez hecho esto, cambiaremos el cable SATA por uno nuevo y, si sigue sin funcionar, probaremos conectando la unidad en otro puerto SATA o en otro equipo para descartar que el error no sea del dispositivo.

### Fuente de alimentación
La fuente de alimentación es un componente que cumple la función de transformar la corriente alterna (CA) que se obtiene de la red eléctrica en corriente continua (CC) para ser utilizada por el resto de los componentes de la computadora. Cuando este componente no funciona correctamente, los síntomas que se producen en el equipo pueden llegar a ser variados.

- **Falla:** No arranca el PC o se apaga repentinamente.  
  **Solución:** Verificaremos el cable de alimentación, los conectores del equipo y, finalmente, la toma de corriente. Si hemos realizado estas comprobaciones y seguimos sin tener resultados, entonces sospecharemos que la fuente está dañada y que es necesaria su sustitución.

- **Falla:** El PC se apaga solo o no arranca de manera constante.  
  **Solución:** Primero debemos descartar que no haya problemas con el sistema de refrigeración (ventiladores y disipadores de calor), ya que si no se producen estos mantenimientos se puede sobrecalentar la PC, haciendo que se apague. Otro motivo por el que puede apagarse el ordenador es la fuente de alimentación. Puede ocurrir que, aunque la fuente esté funcionando, esté entregando menos potencia de la necesaria, lo que llevará al sistema a apagarse por completo.

- **Falla:** Aparece la pantalla azul.  
  **Solución:** Es un síntoma que indica que el sistema está encontrando un error en el momento de cargar el sistema operativo. Puede ser por varias causas, una de ellas podría ser la fuente de alimentación, que no esté brindando la energía suficiente. Si tras realizar un testeo con un programa especializado se concluye que la fuente está bien, el siguiente paso será verificar la memoria RAM y otros componentes.

- **Falla:** Aumentan los ruidos en el PC.  
  **Solución:** El ruido puede deberse al desgaste de los ventiladores de la fuente. Puede ocurrir que, si los ventiladores se estropean, la fuente de alimentación se calienta y esto provoca un ruido continuo que hace pensar que el problema es la fuente. Para descartar que la fuente esté defectuosa, lo mejor será comprobar su funcionamiento mediante un multímetro.

# Limpieza a Fondo de un Ordenador

## Capacidades
- Planificación de actividades de mantenimiento y actualización del hardware y software.

## Actividades

### Limpieza Interna

1. **Limpiar la caja del PC**
   - Usar un paño de microfibra y producto de limpieza.
   - Utilizar aire comprimido para eliminar la suciedad.

2. **Limpiar el disipador o radiador**
   - Disipadores de aire: limpiar bajo el grifo (desmontar antes el ventilador si es necesario).
   - Disipadores de refrigeración líquida: usar aire comprimido o aspiradora de mano.

3. **Cómo limpiar adecuadamente los ventiladores**
   - Usar aire comprimido y sostener una de las aspas.
   - Limpiar con paño de microfibra y bastoncillos en zonas difíciles.

4. **Limpieza de la tarjeta gráfica**
   - Limpiar cuidadosamente; evitar aire comprimido.
   - Usar alcohol isopropílico si es necesario.

5. **Cuidado con la fuente de alimentación y la placa base**
   - Evitar abrir la fuente de alimentación.
   - Limpiar con paño y alcohol isopropílico.

6. **Discos duros, SSD y demás dispositivos**
   - Limpiar con brocha y paño de microfibra.

7. **Cambio de la pasta térmica**
   - Recomendado cada 6 meses a un año.

### Limpieza Externa

1. **Teclado y Mouse**
   - Limpiar cuidadosamente y tomar fotos si es necesario.

2. **Impresora**
   - Mantener limpia; usar líquidos especiales para cabezales.
   - Cubrir y utilizar la impresora regularmente.

3. **Monitores**
   - No abrir para limpiar por dentro.
   - Limpiar con cepillo y paño; usar espuma limpiadora indirectamente.

