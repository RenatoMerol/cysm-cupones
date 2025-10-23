# CYSM - Base de Datos de Cupones

Herramienta de referencia interactiva para el equipo de Customer Service. Búsqueda rápida y fácil de todos los cupones activos con información clara sobre dónde encontrarlos y quién puede usarlos.

---

## 📋 Contenido

- **index.html** - Aplicación web completa (interactiva)
- **cupones.csv** - Base de datos de cupones (respaldo)
- **README.md** - Este archivo (instrucciones)

---

## 🚀 Cómo usar

### Opción 1: Abrir directamente en el navegador (Más fácil)

1. Descarga los archivos de GitHub
2. Abre `index.html` en tu navegador (doble click)
3. ¡Listo! Busca cupones al instante

### Opción 2: Usar en Figma Make

1. Copia el código de `index.html`
2. Pégalo en tu componente HTML/embed de Figma Make
3. Configura el tamaño del iframe según necesites

---

## 🎯 Funcionalidades

✅ **20 categorías de cupones** - Organized por tipo y uso  
✅ **Búsqueda global** - Busca por código, valor, tipo de descuento  
✅ **Información clara** - "Dónde lo encontrará" y "Quién puede usarlo"  
✅ **Tarjetas compactas** - 5 columnas en desktop, responsive  
✅ **Tabs intuitivos** - Navega por categoría fácilmente  

---

## 📂 Categorías disponibles

1. **POSTALES** - 2U (Impresos y postales)
2. **SMS** - 4U (Mensajes de texto)
3. **RESEÑAS** - REVIEW (Clientes que dejan reseñas)
4. **SERVICIO** - CS (Exclusivo Customer Service)
5. **WEBSITE** - CYSM (Genéricos multi-canal)
6. **NICE** - Campaña específica (en transición)
7. **VIP** - Exclusivo clientes VIP
8. **SHAPE** - Línea específica de shapewear
9. **FLASH** - Promociones de corto tiempo
10. **FACEBOOK** - FB (Facebook Ads)
11. **BIENVENIDA** - WELCOME (Primer contacto)
12. **CUMPLEAÑOS** - BIRTHDAY (Automático)
13. **PRIMER CONTACTO** - GET (Landing pages)
14. **EVERGREEN** - Promociones activas siempre
15. **ERROR/CARRITO** - OOPS10, CART (Contextos específicos)
16. **PRODUCTO** - Categorías específicas (Jeans, Denim, etc.)
17. **TEMPORAL** - Estacionales y especiales (Navidad, Halloween)
18. **BLOG** - BLOG10 (Contenido)
19. **FOREVER** - FOREVER10 (VIP permanente)
20. **INFLUENCERS** - Afiliados personales

---

## 🔍 Cómo buscar cupones

### Por código
```
Escribe: 2U20
Resultado: Encuentra el cupón 2U20 en la categoría POSTALES
```

### Por descuento
```
Escribe: 20%
Resultado: Muestra todos los cupones con 20% de descuento
```

### Por tipo
```
Escribe: percentage
Resultado: Muestra todos los cupones con descuento porcentual
```

---

## 📊 Información por cupón

Cada cupón muestra:

- **Código** - Nombre del cupón (ej: WELCOME10)
- **Descuento** - Valor (20%, $50, etc.)
- **Tipo** - Porcentaje o cantidad fija
- **Dónde lo encontrará** - Canal o contexto
- **Quién puede usarlo** - Segmento de cliente

---

## 🔄 Actualizar cupones

### Cuando se agreguen nuevos cupones:

1. Descarga el CSV actualizado de Shopify
2. Reemplaza `cupones.csv` en el repositorio
3. Contacta para regenerar `index.html`
4. Push a GitHub

### Proceso técnico (para desarrollador):

El `index.html` lee automáticamente del JSON embebido. Para actualizar:

1. Reemplaza el CSV original
2. Ejecuta el script Python para regenerar
3. Sube el nuevo `index.html`

---

## 🎨 Diseño

- **Color principal** - Rojo/Borgoña (#c41e3a) - Match con botones CYSM
- **Responsive** - Funciona en desktop, tablet, móvil
- **5 columnas** - Desktop | 4 columnas - Tablet grande | 3 columnas - Tablet | 2 columnas - Tablet pequeña | 1 columna - Móvil

---

## 📝 Notas importantes

⚠️ **Todos los cupones son ACTIVOS** - Si necesitas desactivar uno, coordina con el equipo  
⚠️ **VIP cupones** - El sistema de Shopify restringe automáticamente para clientes no-VIP  
⚠️ **CS cupones** - Uso exclusivo del equipo por teléfono, no se promocionan  
⚠️ **En transición** - NICE y algunos otros están siendo desactivados gradualmente  

---

## 🐛 Reporte de errores

Si encuentras:
- Cupón duplicado
- Información incorrecta
- Problema de búsqueda
- Cupón faltante

**Contacta al equipo técnico con el código del cupón y los detalles**

---

## 📞 Soporte

- **Preguntas sobre cupones** → Supervisor de Customer Service
- **Actualizaciones de cupones** → Equipo de Marketing
- **Problemas técnicos** → Equipo de Desarrollo

---

## 📅 Última actualización

Octubre 23, 2025

- 274 cupones activos
- 20 categorías
- 5 columnas responsive

---

**¡Gracias por usar CYSM - Base de Cupones!**
