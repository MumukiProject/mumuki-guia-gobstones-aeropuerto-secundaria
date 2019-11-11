<gs-attire attire-url="https://raw.githubusercontent.com/MumukiProject/mumuki-guia-gobstones-aeropuerto-secundaria/master/assets/attires/config_1573506340002.json"></gs-attire>



Para que un avión esté en el aire hay que tomar ciertas medidas de seguridad. Por eso es muy importante la torre de control de los aeropuertos, donde profesionales se fijan que todo esté en condiciones para el despegue :airplane_departure:. Su principal herramienta es el radar. ¡Prendámoslo!

<gs-board>
     GBB/1.0
     size 2 2
     head 0 0
</gs-board>

> Dado el tablero anterior, definí el procedimiento `PrenderRadar` para que prenda cada cuadrante del tablero y termine en el casillero de abajo a la derecha. Para eso, creá el procedimiento `PrenderCuadrante` para que, si está apagado (no hay bolita de color verde), lo prenda (ponga una bolita verde).