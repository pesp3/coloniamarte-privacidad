# Política de privacidad — Colonia Marte / Mars Colony

Este repositorio existe **solo** para servir una página: la política de privacidad del juego
Android *Colonia Marte* (*Mars Colony* en inglés, paquete `com.pabloespinoza.coloniamarte`),
en la dirección pública que exige Google Play.

<https://pesp3.github.io/coloniamarte-privacidad/>

Aquí no hay código del juego. El repositorio del juego es privado, y GitHub Pages sobre
repositorio privado requiere plan de pago: de ahí que la página viva aparte.

## Si hay que cambiar el texto

**La copia buena no es esta.** El original está en el repositorio del juego, en
`Docs/privacy/index.html`. Edítalo allí y copia el resultado aquí; al revés se pierde.

**Actualizado el 10 ago 2026.** Dos cambios, y ninguno de los dos avisó:

- **La partida ya no se queda en el teléfono.** El texto anterior prometía que se guardaba
  «únicamente en el almacenamiento local» y que «no sale del aparato». Dejó de ser cierto al
  integrar el guardado en nube: hay una copia en el espacio de partidas guardadas de Play
  Games Services, en la cuenta de Google del jugador. La página lo explica, e insiste en que
  esa copia va a su cuenta y no a un servidor del desarrollador.
- **Las compras son reales.** Play Billing de verdad, con validación del comprobante en el
  propio teléfono. El texto anterior decía «simuladas … no se procesa ningún pago real».

Antes (3 ago) ya se había quitado el «no recoge ningún dato», al entrar Firebase Crashlytics
y Analytics: diagnósticos de fallos, métricas de uso e identificador de publicidad.

**Lo que sigue pendiente: los ANUNCIOS.** La página dice que son simulados, y es verdad — el
SDK no está ni instalado. **El día que entre una red publicitaria real, esta página tiene que
actualizarse otra vez antes de publicar esa versión**, detallando el proveedor y para qué usa
el identificador de publicidad, que ya se recoge pero hoy solo para analítica. Ahí cambia
además el formulario de Seguridad de los datos de Play Console: ese identificador pasa de
«recogido» a «compartido», que no es lo mismo. La fecha de «última actualización» se mueve
con el texto.
