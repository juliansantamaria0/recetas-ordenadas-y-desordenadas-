# Autor
Julian Andres Santamaria Bustamante 

# 🍪 Receta Combinando Listas Ordenadas y Desordenadas
## 🎯 Objetivo
Aprender a estructurar un documento HTML usando listas **ordenadas** para secuencias de pasos y listas **desordenadas** para elementos sin orden jerárquico.

## 📋 Instrucciones

### 1. Documento base
```html
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <title>Receta de Galletas</title>
</head>
<body>
  <h1>Receta de Galletas de Avena</h1>
</body>
</html>
```

### 2. Ingredientes con `<ul>` (orden NO importa)
```html
<h2>Ingredientes</h2>
<ul>
  <li>2 tazas de avena</li>
  <li>1 taza de harina</li>
  <li>1/2 taza de azúcar</li>
  <li>2 huevos</li>
  <li>1/2 taza de mantequilla</li>
  <li>1 cucharadita de esencia de vainilla</li>
</ul>
```

### 3. Pasos con `<ol>` (orden SÍ importa)
```html
<h2>Preparación</h2>
<ol>
  <li>Mezclar los ingredientes secos (avena, harina y azúcar).</li>
  <li>Agregar los huevos, la mantequilla derretida y la esencia de vainilla.</li>
  <li>Formar pequeñas bolitas de masa y colocarlas en una bandeja para hornear.</li>
  <li>Hornear a 180°C durante 15 minutos.</li>
  <li>Dejar enfriar y servir.</li>
</ol>
```

## 🔍 Cuándo usar cada tipo

| Lista | Cuándo usar | Ejemplo |
|-------|-------------|---------|
| `<ul>` | Orden NO importa | Ingredientes, características |
| `<ol>` | Orden SÍ importa | Pasos, instrucciones |

## ✅ Checklist
- [ ] Documento HTML creado
- [ ] Lista desordenada para ingredientes
- [ ] Lista ordenada para preparación
- [ ] Validación en navegador