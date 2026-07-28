# El Show de Peluquín — Brief de Proyecto Web

## 1. Resumen del proyecto

- **Tipo de proyecto:** Landing page.
- El desarrollador trabajará sobre una **plantilla base de HTML ya existente**.
- Ya se entregó por separado un **prompt inicial** para adaptar dicha plantilla al negocio. Este README es un complemento a ese prompt: define la información del negocio, el branding y los requisitos visuales que el sitio debe cumplir.
- **Este README NO define la estructura de secciones de la página.** La estructura a seguir es la de la plantilla base ya entregada.

---

## 2. Información del negocio

Información extraída del material gráfico disponible en la carpeta `imagenes/` (logo y flyer promocional). Esta es toda la información con la que se cuenta del negocio.

- **Nombre del negocio:** El Show de Peluquín
- **Rubro:** Show infantil / animación de eventos — payaso cantarín "Peluquín" y su equipo.
- **Representante artístico:** Dicson Franco
- **Contacto / WhatsApp:** 563 850 6473
- **Dirección física:** No aplica — es un servicio que se traslada a la sede del evento (no hay local fijo).
- **Horario:** No aplica horario de atención fijo; el contacto y las reservas se gestionan vía WhatsApp.

### Servicios / repertorio del show

- Show cómico-mágico-musical con el payaso "Peluquín"
- Peluquín en concierto
- Títere cómico "Pequín"
- Papá Noel y su Navimensaje (temporada navideña)
- Impro reality infantil "Canto a la Navidad"
- Polijuegos infanto-familiares
- Tour especial de temporada: "Navilandia" (espectáculo navideño)
- Animación general para eventos: grupo tropical, maestro de ceremonia, animadores, activación comercial, entre otros

### Datos adicionales relevantes

- Duración del show: aproximadamente 2 horas de duración.
- Debido a la alta demanda por fechas, se recomienda reservar el show con anticipación.

---

## 3. Branding e identidad visual

Definido a partir del análisis del logo (`imagenes/logo.jpeg`).

### Paleta de colores

| Color | HEX | Uso sugerido |
|---|---|---|
| Púrpura/violeta profundo | `#4B1D6E` | Fondo, secciones ancla, contraste principal |
| Púrpura medio | `#6A2C91` | Degradados, fondos secundarios |
| Dorado/amarillo | `#FFC72C` | Acentos, CTA, detalles tipo "luces de marquesina" |
| Rojo | `#E63946` | Acentos, botones, elementos de énfasis |
| Azul | `#2E9DF7` | Acentos secundarios |
| Verde | `#39B54A` | Acentos secundarios |
| Rosa/magenta | `#EC4899` | Acentos secundarios |
| Negro | `#0A0A0A` | Fondo profundo, texto sobre claros |

### Tipografía sugerida

- **Encabezados / logotipo textual:** una fuente display redondeada y de trazo grueso que evoque el estilo circense-festivo del logo (ej. Fredoka, Baloo 2, Bungee o Luckiest Guy de Google Fonts).
- **Cuerpo de texto:** una fuente sans-serif limpia y de alta legibilidad para mantener el balance con el estilo premium exigido (ej. Poppins, Nunito o Quicksand).

### Identidad visual

El logo transmite una estética de marquesina/circo: fondo púrpura con luces tipo bombillas, estrellas multicolor y tipografía en degradado arcoíris sobre el nombre "Peluquín". Esta identidad debe traducirse al sitio de forma controlada: usar la paleta de acentos con moderación, dejando que el estilo premium/minimalista (ver punto 4) sea el que domine la composición general.

---

## 4. Estilo visual obligatorio

El sitio debe manejar:

- Estilo **premium, enterprise y corporativo de marca**.
- Nivel **big tech**: elegante y a la vez minimalista.

---

## 5. Efectos y animaciones requeridos

El sitio debe incluir:

- Efectos visuales y **animaciones de scroll**.
- **Pantalla de carga (preloader)** con spinner + logo del negocio.
- **Animación en el título del hero**: efecto máquina de escribir, cambio de color en las letras u otro efecto tipográfico similar.

---

## 6. Instrucciones sobre assets

- El logo se encuentra en `imagenes/logo.jpeg` pero **viene con fondo**. El desarrollador debe **removerle el fondo** (dejarlo transparente, exportado en PNG) antes de usarlo en el sitio (header, preloader, favicon, etc.).
- El flyer (`imagenes/WhatsApp Image 2026-07-27 at 8.20.56 PM.jpeg`) incluye **fotografías de personas reales, incluyendo menores de edad**. Antes de publicar cualquiera de esas fotos en el sitio web, verificar que se cuenta con autorización para su uso público. Si no se cuenta con dicha autorización, no usar esas fotografías específicas.

---

## 7. Nota para el desarrollador

El desarrollador puede **iterar sobre el proyecto usando Claude**, dándole instrucciones las veces que sea necesario, hasta lograr el resultado deseado.

---

## 8. Checklist

- [ ] Usar la plantilla base + el prompt inicial ya entregado para adaptar el sitio al negocio
- [ ] Remover el fondo del logo (`imagenes/logo.jpeg`) antes de usarlo
- [ ] Verificar autorización de uso de las fotos de personas/menores del flyer; si no se cuenta con permiso, no usarlas
- [ ] Aplicar la paleta de colores de marca (HEX) definida en este documento
- [ ] Aplicar la tipografía sugerida (encabezados y cuerpo de texto)
- [ ] Aplicar el estilo visual premium / enterprise / corporativo / minimalista en todo el sitio
- [ ] Implementar preloader con spinner + logo del negocio
- [ ] Implementar animaciones/efectos de scroll
- [ ] Implementar animación en el título del hero (máquina de escribir, cambio de color u otro efecto tipográfico)
- [ ] Cargar la información del negocio (servicios, contacto, WhatsApp) indicada en este README
- [ ] Iterar con Claude Code las veces que sea necesario hasta lograr el resultado deseado
