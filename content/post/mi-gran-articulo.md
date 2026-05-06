+++
title = "Mi gran artículo"
date = "2024-01-01"
type = "post"
categories = ["Configuration"]  # <--- ESTO activa los cuadros
pinned = true
+++
Para ver las categorías en la parte superior derecha de tu pantalla, tal como se muestra en la imagen del autor (donde aparecen "Authoring", "Configuration", "Latex"), el proceso es automático, pero requiere que tus publicaciones cumplan con tres requisitos específicos en sus archivos .md.Aquí tienes la guía definitiva para activarlas ahora mismo:1. El detonante: El Front MatterHugo no mostrará esos cuadros si no hay contenido asociado a ellos. Debes entrar a tus archivos en content/post/ y añadir la línea de categorías.Asegúrate de que tus archivos se vean así:toml+++
title = "Mi gran artículo"
date = "2024-01-01"
type = "post"
categories = ["Authoring", "Configuration"]  # <--- ESTO activa los cuadros
+++
Usa el código con precaución.Importante: Debes escribirlo exactamente así: categories = ["Nombre"], con comillas y corchetes.