# Sistema de seguridad con Arduino
Este sistema utiliza un teclado matricial de 4x4 para ingresar la contraseña, un display LCD de 20x4, un pequeño buzzer por el cual
emitirá una alerta sonora y unos leds que indicaran el estado del sistema. 

### Empezando
Este proyecto se basa en los sensores que hemos usado anteriormente, si no tienes mucha experiencia en el manejo de dichos sensores puedes consultar nuestros repositorios.

- Teclado matricial https://github.com/proyectoTEOS/Teclado-matricial-4x4-con-Arduino
- LCD 20x4 https://github.com/proyectoTEOS/Display-LCD-16x2-con-Arduino
- Buzzer https://github.com/proyectoTEOS/Buzzer-con-Arduino

### Requisitos
- Tener el IDE de [Arduino](https://www.arduino.cc/en/Main/Software) (o el de tu preferencia) con la versión más actual.
- Contar con las librerías [Keypad](http://playground.arduino.cc/Code/Keypad), [Password](http://playground.arduino.cc/Code/Password), [LiquidCrystal_I2C](https://github.com/fdebrabander/Arduino-LiquidCrystal-I2C-library) y [Wire] (se incluye con el IDE).
- Tener el material para hacer el proyecto (claro).

### Materiales
Enlistaremos los materiales que se necesitan para realizar el proyecto, pero puedes conseguir componentes similares.
- 1 Arduino UNO R3
- 1 Teclado matricial
- 1 Led de color rojo y otro azul (o del color que prefieras)
- 2 Resistencias de 330ohms
- 1 Resistencia de 1K ohm
- 1 Transistor NPN BC548
- 1 Protoboard
- 1 Pantalla LCD de 20x4
- 1 Módulo (adaptador) I2C
- 1 Buzzer de 5v
- 1 Sensor PIR

### Código
**[Aqui](https://github.com/proyectoTEOS/Sistema-de-seguridad-con-Arduino/blob/master/Sistema-de-seguridad-con-Arduino.ino)** podrás obtener el link del código, esta comentado de tal forma que puedas entender cada función.

### Diagrama
El siguiente esquemático muestra cómo se debe conectar todos los componentes con la placa.
![](/resources/diagrama-sistema-de-seguridad.jpg).

Si requieres más información de este y otros proyectos, puedes ir a nuestra página web y dar clic en la parte de proyectos en donde encontraras los códigos, diagramas, hojas de datos, librerías, recursos y una documentación más extensa.