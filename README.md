# PcLigApp: PcLiga en el móvil (Android, no oficial)

PcLiga, el manager de fútbol online, adaptado al teléfono. Es la misma
PcLiga de siempre, con tu cuenta y tus datos, pero cada pantalla se acomoda
al móvil: sin pellizcar, ampliar y deslizar para encontrar un dato.

> **App no oficial.** Hecha por un manager para los managers. No tiene
> relación con los responsables de PcLiga.

## Qué cambia respecto de la web

### Menús

La barra de accesos de PcLiga (alineación, plantilla, tácticas,
calendario…) queda fija arriba y se desliza de costado. El menú izquierdo
de la web pasa al botón ☰, con todas las secciones del juego; la columna
derecha, al botón ⋮, con lo que se puede hacer en la página que estás
viendo: en la ficha de otro equipo, por ejemplo, mandarle un comunicado,
ofrecerle un contrato o una transferencia, añadirlo a tu cartera o ver su
táctica.

<p align="center">
  <img width="180" height="390" alt="Portada" title="Portada, antes de iniciar sesión" src="https://github.com/user-attachments/assets/a7f4094a-cb97-48a1-a6f8-00f93917bafe">
  <img width="180" height="390" alt="Menú principal" title="Menú ☰: todas las secciones del juego" src="capturas/menu_izquierdo.jpeg">
  <img width="180" height="390" alt="Menú de la página" title="Menú ⋮ en la ficha de otro equipo: sus datos y las acciones sobre él" src="capturas/menu_derecho.jpeg">
</p>

### Alineación, tácticas y clasificación

Las tablas se acomodan al ancho de la pantalla: si no entran, bajan la
letra, acortan los nombres o esconden columnas, lo justo. El ojo de cada
jugador abre su resumen, con las stats con decimales, las medias y, en la
alineación, la EF. La clasificación, cuando no entra, se queda con los
puntos y los criterios de desempate. Y en tácticas, el campo entra entero
en la pantalla. Muchas tablas recuperan la vista completa con solo girar
el teléfono.

<p align="center">
  <img width="180" height="390" alt="Alineación" title="Alineación, con el resumen de un jugador" src="https://github.com/user-attachments/assets/9ad9f893-bb7c-4982-8afe-c6305a8ecf79">
  <img width="180" height="390" alt="Tácticas" title="Tácticas" src="https://github.com/user-attachments/assets/cb35b6cc-96c5-44d0-aa8d-a3b0280aedec">
  <img width="180" height="390" alt="Clasificación" title="Clasificación de la liga" src="https://github.com/user-attachments/assets/f840b1ed-bcc6-4d02-b7c4-e6616ce64def">
</p>

### Mercado

En el buscador, las demarcaciones son botones grandes y los filtros van en
secciones que se despliegan. En las subastas, el botón de pujar siempre
entra en la pantalla, y en un teléfono lento la lista aparece por tandas
en vez de hacerte esperar.

<p align="center">
  <img width="180" height="390" alt="Buscador de jugadores" title="Buscador de jugadores: demarcaciones en botones y filtros en secciones" src="capturas/buscar_jugadores.jpeg">
  <img width="180" height="390" alt="Subastas" title="Subastas, con el botón de pujar a la vista" src="https://github.com/user-attachments/assets/708e4d04-d848-49fb-aacc-744b90a2bee5">
</p>

### Ficha del jugador

Las stats en barras, con los colores de PcLiga, o en un gráfico de diez
porciones; y el histórico de cada temporada, en un gráfico que se ve entero
en el móvil.

<p align="center">
  <img width="180" height="390" alt="Ficha del jugador" title="Ficha del jugador, con las stats en gráfico" src="https://github.com/user-attachments/assets/f0ea39bb-a1f0-4ad6-adaa-f89438e3c0d3">
  <img width="180" height="390" alt="Ficha del jugador en tema oscuro" title="La misma ficha, en tema oscuro y con menús azules" src="https://github.com/user-attachments/assets/e3c17474-c87f-4e67-af0d-dfb12dbf5644">
</p>

### Partidos

En el calendario y los resultados, los goles van separados de los equipos,
con el acceso al visor, a la simulación al minuto y al carrusel de cada
partido.

<p align="center">
  <img width="180" height="390" alt="Visor de partidos" title="Visor de partidos" src="https://github.com/user-attachments/assets/8329e21a-6929-4156-b3da-1ef50f980c71">
</p>

### Tema, colores y zoom

Tema claro, oscuro o el del teléfono; cinco colores para los menús; y zoom
propio, del 80 % al 130 %, que se recuerda.

### Cargas y errores

Mientras carga una página nueva, queda la anterior con un indicador. Si se
corta internet, aparece un aviso con "Reintentar"; si PcLiga rechaza algo
sin decir por qué, vuelves a la portada con un aviso.

### Para empezar

Un tutorial recorre el juego la primera vez, y la cuenta nueva se puede
crear desde la app.

## Descargar

En **[Releases](../../releases/latest)** está siempre la última versión.
Descarga el archivo `.apk` de la sección *Assets*.

## Instalar

1. Abre el `.apk` descargado en el teléfono.
2. Si Android avisa de que no permite instalar apps de origen desconocido,
   toca **Ajustes** y permite instalar desde esa app (el navegador o el
   gestor de archivos). Después vuelve atrás y toca **Instalar**.
3. Entra con tu usuario y contraseña de PcLiga.

Las versiones nuevas se instalan **encima** de la anterior, sin
desinstalar y sin perder nada.

> Si tienes una beta anterior a la 1.0 (0.5 o anterior), desinstálala
> primero: estaba firmada con otra clave y Android no deja instalar encima.

## Actualizar sola, con Obtainium

[Obtainium](https://github.com/ImranR98/Obtainium) avisa cuando hay una
versión nueva y la instala:

1. Instala Obtainium desde su página.
2. Toca **Añadir app** y pega la dirección de este repositorio.
3. Toca **Añadir**. Desde ahí, Obtainium busca las versiones nuevas.

## Comprobar que el APK es el original

Cada versión trae en sus notas la **huella SHA-256 del archivo**. Todas las
versiones desde la 1.0 están firmadas con el mismo certificado:

```
SHA-256: 26:79:37:A0:D9:BE:E6:94:44:B3:56:13:16:93:30:19:E2:FA:52:9A:B0:17:13:4A:5E:78:E0:DE:22:BE:70:2B
```

Si un APK no coincide, no lo instales.

## Privacidad

- La app **no recoge datos**, no lleva publicidad ni rastreadores y solo
  pide permiso de internet.
- **No guarda tu contraseña.** Si quieres, la recuerda el gestor de
  contraseñas del teléfono (Google, Samsung Pass…).
- Solo se conecta con PcLiga, más tres servidores de Google de los que la
  propia web de PcLiga carga piezas (jQuery y las tipografías) y el captcha
  "No soy un robot". Cualquier otro enlace (foro, wiki, redes) se abre en
  tu navegador.

## Lo que no está en la app

La compra de créditos, los ingresos extra, la cuenta premium con tarjeta o
PayPal y las notificaciones se hacen desde un navegador. Al entrar en esas
páginas, la app explica cómo.

## Dudas y fallos

En el foro o en el Discord de PcLiga.
