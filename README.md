# Experimento-Red-Skull-Lite
Prototipo jugable de un sandbox de piratería en el Caribe, generado al 100 % por IA (Claude) como experimento y maqueta para mi proyecto real, Red Skull. Para Linux y Windows.

# Red Skull Lite

Prototipo jugable de un sandbox de piratería en el Caribe del siglo XVIII, que corre como ejecutable de escritorio sin conexión.

> **Este juego ha sido generado al 100 % por una IA (Claude, de Anthropic).** Es un experimento, no un producto final.

## Qué es y por qué existe

Estoy desarrollando **Red Skull**, un sandbox 3D de piratería en el Caribe, en Unity. Este repositorio **no es ese juego**.

Es un experimento paralelo: darle a una IA la descripción de mi idea y dejarla construir una versión "lite" y jugable, para:

- **poner a prueba hasta dónde llega una IA** construyendo un juego completo a partir de una idea concreta;
- **usarla como maqueta**: probar rápido mecánicas, ritmo y sensaciones antes de llevarlas (o descartarlas) en el proyecto real;
- **buscar inspiración**: ver cómo otro "diseñador" interpreta la misma idea y quedarme con lo que merezca la pena.

El código, la geografía, el equilibrio y las mecánicas de este repositorio los escribió la IA siguiendo mis indicaciones, iteración a iteración. El diseño real de Red Skull es independiente y sigue su propio camino.

## Qué incluye el prototipo

- Mapa del Caribe a partir de geografía real, con zonas de dificultad y clima regional aleatorio, y zoom hasta el plano de las ciudades.
- Navegación a vela, combate naval, comercio entre puertos y facciones (España, Inglaterra, piratas).
- Fama, infamia y reputación que cambian cómo reaccionan puertos y guardias.
- Creación de personaje, desembarco y exploración a pie de pueblos con habitantes que hacen sus tareas, con hombres y mujeres diferenciados.
- Personajes con esqueleto y animación procedural: combos de espada, esquiva (Z), guardia y bloqueo, ropa con física y armas en la mano.
- Combate cuerpo a cuerpo (ataque ligero y pesado, bloqueo, parada, stamina, niveles).
- Edificios con interior (taberna, iglesia, herrería, astillero, ayuntamiento, lonja) y habitantes con los que hablar.
- Conquista de pueblos con tripulación, guarniciones, banderas, ingresos, fortificaciones y contraataques.
- **Base propia** que crece con tu oro (almacén, taberna, herrería, iglesia y **sastrería**), con sus habitantes, con los que se puede hablar.
- **Sastrería y armario**: libro de muestras con atuendos, sombreros, peinados, barbas y tintes para personalizar al capitán, y un armario en la base para cambiar entre la ropa que ya posees.
- Puertos con muelles detallados (tablones, barandas, bolardos, cajas, barriles, farolas y grúa).
- Guardado automático.

## Descargas

En la sección **[Releases](../../releases)** hay dos paquetes que funcionan **sin conexión**:

| Sistema | Archivo | Cómo ejecutarlo |
|---|---|---|
| Linux | `Red Skull Lite-4.0.0.AppImage` | `chmod +x` y doble clic. Si no abre: `./"Red Skull Lite-4.0.0.AppImage" --appimage-extract-and-run --no-sandbox` (puede requerir `libfuse2`). |
| Windows | `Red Skull Lite-4.0.0-win.zip` | Descomprimir y abrir `Red Skull Lite.exe`. No está firmado: SmartScreen puede avisar. |

Pulsa **F11** para pantalla completa.

## Limitaciones

Es un prototipo: sin audio elaborado, gráficos simples, equilibrio sin pulir y posibles errores. Las tipografías de la versión de escritorio usan una serif del sistema para no depender de internet.

## Créditos y licencias

- Generado por Claude (Anthropic) a partir de la idea y la dirección de su autor.
- [Three.js](https://threejs.org/) r128 (MIT) y [Electron](https://www.electronjs.org/) (MIT).

---

## English summary

**Red Skull Lite** is a browser/desktop prototype of a Caribbean piracy sandbox, **built 100% by an AI (Claude)** as an experiment: testing what an AI can do from a personal game idea, and using it as a quick mock-up and source of inspiration for my real project, *Red Skull* (Unity, in development). This repository is not that game. Offline builds for Linux and Windows (v4.0.0) are available in Releases.
