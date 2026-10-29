# Azahares Apartamento Turístico

Web local en HTML, CSS y JavaScript vanilla. Abrir index.html con Live Server. No requiere compilación.

## Fotografías actuales

Se han inspeccionado visualmente las siete fotografías de imgs/ y conservado todos los originales.

| Archivo | Resolución | Contenido observado | Uso |
| --- | --- | --- | --- |
| 703764221.jpg | 1024 × 576 | Salón-comedor | Portada principal sin recorte |
| 500220243.jpg | 433 × 768 | Mesa, copas y tarjeta de Azahares | Detalle de portada |
| 640925943.jpg | 576 × 768 | Dormitorio | Secuencia interior |
| 578390994.jpg | 577 × 768 | Patio con plantas y mesa | Secuencia interior |
| 525854904.jpg | 576 × 768 | Perspectiva del interior | Secuencia interior |
| 484673882.jpg | 1024 × 683 | Casas y montañas | Sección del entorno, sin atribuir vistas al apartamento |
| 505947629.jpg | 433 × 768 | Curso de agua entre rocas | Excluida: ubicación no confirmada |

Cinco fotografías verticales y dos horizontales; calidad suficiente para web, resolución moderada. Se limita la ampliación y se conservan los encuadres completos del salón, dormitorio, patio e interior. El detalle decorativo adapta su recorte por pantalla. Las seis fotografías publicadas pesan aproximadamente 399 KiB en total; cada JPEG original pesa menos de 100 KB. No se han recomprimido ni generado versiones mayores que el original. Carga diferida fuera de portada, dimensiones explícitas, texto alternativo y rutas locales desde imgs/. No hay duplicados ni fotografías externas utilizadas para representar el apartamento.

La galería es una secuencia editorial estática y responsive, sin carrusel ni controles de ampliación. No se infieren capacidad, número total de dormitorios, servicios, equipamiento incluido ni disponibilidad a partir de las fotografías. La botella del detalle decorativo no se presenta como obsequio incluido.

## Identidad y fuentes

Se conserva el diseño editorial, la paleta blanco cálido/oliva/terracota, Bodoni Moda y Albert Sans locales, navegación, enlaces externos, animaciones y estructura del footer. Se actualizan los textos que describían únicamente el destino y sus créditos fotográficos.

Fuentes verificadas durante la creación: ficha coincidente de Azahares en Booking, Cádiz Turismo y Ventana del Visitante de la Junta de Andalucía. Los enlaces permanecen en la web. No se atribuye el canal de Booking como sitio propio del propietario. No se añaden datos de reserva ni contacto.

Las imágenes antiguas de assets/ quedan sin uso en la web. Su procedencia y licencias se conservan aquí:
- el-bosque.jpg y majaceite.jpg: El Pantera, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:ElBosqueDesdeCarretera.jpg y https://commons.wikimedia.org/wiki/File:Majaceite.jpg ; https://creativecommons.org/licenses/by-sa/4.0/
- calles.jpg: Ismael Olea, CC BY 4.0. https://commons.wikimedia.org/wiki/File:El_Bosque_20210609_01.jpg ; https://creativecommons.org/licenses/by/4.0/

## Verificación de la actualización

Chrome local automatizado a 375, 768, 1440 y 1920 px: seis imágenes cargadas desde imgs/, sin errores JavaScript ni respuestas HTTP fallidas, sin scroll horizontal, fuentes cargadas, anclas internas válidas, etiqueta única noindex/nofollow. Comprobada apertura de los créditos en móvil y prefers-reduced-motion. Capturas de 375 y 1440 px revisadas visualmente. Script y capturas en .qa/, ignorado por Git.

No se ha probado en Safari/iPhone real. No se ha realizado auditoría formal de accesibilidad o rendimiento. Los enlaces externos existentes se conservan y no se ha repetido la investigación del negocio.

Todos los cambios se limitan a azahares-apartamento-turistico/. Sin commits, pushes ni despliegues.