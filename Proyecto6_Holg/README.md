# Proyecto 6: Controlador de equipos vía Ethernet

## Descripción general
Tarjeta diseñada para el control de motores y valvulas junto a la adquisición de celdas de carga y sensores NAMUR.
Utiliza un microcontrolador STM32F407VGTx que se encargará de gestionar la comunicación entre el equipo y el PC.
El diseño se realizó en 2 capas por pedido del cliente.


## Aporte
- Diseño de la tarjeta PCB en Kicad a dos capas respetando las normas IPC.
- Diseño de circuitos para la adquisición de la señal NAMUR y celda de carga.
- Simulación en 3D de la tarjeta PCB.
- Coodinación para la fabricación del producto final en JLCPCB.
- Test des los periféricos.

## Herramientas de software utilizadas

- **Diseño electrónico:** Kicad .
- **Simulaciones:** TinaTI.
- **Programación:** STM32CubeIDE.
- **Diseño CAD:** Inventor.

## Dificultades

- Diseño complejo en dos capas debido a las necesidades del cliente.
- Escaza documentación para la adquisición de la señal del sensor NAMUR y celdas de carga.
- Coordinación con el cliente para la realización de la tarjeta.

## Fotos
Layout Top
![layout top](https://github.com/FarwayDot/Portfolio/blob/main/Proyecto6_Holg/HolgCtrl_Top.png?raw=true)
-
Layout Top
![layout bottom](https://github.com/FarwayDot/Portfolio/blob/main/Proyecto6_Holg/HolgCtrl_Bottom.png?raw=true)
-
Tarjeta Kicad
![tarjeta kicad](https://github.com/FarwayDot/Portfolio/blob/main/Proyecto6_Holg/HolgCtrl_PCB2.png?raw=true)
-
Tarjeta en Físico
![tarjetas fisica](https://github.com/FarwayDot/Portfolio/blob/main/Proyecto6_Holg/HolgCtrl_Fisico.jpeg?raw=true)
-