# HydroSentinel
Proyecto para el curso de Seminario de Ingeniería Eléctrica e Innovación (EL3105-2).
Este proyecto está basado en el StarterKit NB-IoT de Entel.

## Módulos/Sensores utilizados:
- RAK19001 WisBlock Dual IO Base Board
- RAK5860 WisBlock NB-IoT Interface Module + Antena LTE + Antena GPD
- RAK11200 WisBlock WiFi Module, ESP32 + 2 jumpers + 3 pares pinout
- Batería de Litio LiPo 2500mAh 3.7V
- RAK5801 WisBlock 4-20mA Interface Module.
- Sensor de flujo YF-S201

## Explicación del proyecto
El módulo RAK5801 y el sensor YF-S201 reciben información sobre la corriente que está recibiendo la motobomba y el flujo de agua que está pasando respectivamente, posterior a recibir la información, envía ésta a través de un mensaje por NB que es recibida por un Dashboard para así organizar los datos almacenados para que sea más intuitivo y cómodo para el usuario saber qué está pasando por su motobomba.

OBS: El sensor de flujo no se encuentra operativo actualmente ya que su forma de recolectar e interpretar los datos ocaciona que se sature la CPU provocando que se apague o reinicie todo el sistema. (Aún así, funciona por separado, es decir, sin utilizar la comunicación.)

## Videos demostrativos
- https://drive.google.com/file/d/180c-wNcW0nTIcBb5RHB_3fi3kyxiMKGl/view?resourcekey (Flujo)
- https://drive.google.com/file/d/17y4Zd_wieQllReBEq0bHoLr1ByMvM6-8/view?resourcekey (Corriente y Dashboard)

## Contacto
- Maximiliano Flores C. (m.flores.c@ug.uchile.cl)
- Sebastián Herrera T. (sebastian.herrera.t@ug.uchile.cl)
- Cristian Hernández H. (c.hernandez.h@ug.uchile.cl)
