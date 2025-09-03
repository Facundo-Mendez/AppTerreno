## 📄 CONTRIBUTING.md
```markdown
# 🤝 Guía de Contribución

Gracias por contribuir a este proyecto 🚀.  
Para mantener un flujo de trabajo ordenado seguimos estas reglas:

---

## 🌳 Flujo de Ramas
- `main`: código estable en producción.
- `develop`: integración de features.
- `feature/<nombre>`: cada tarea/issue tiene su rama.
- `bugfix/<nombre>`: corrección de errores.
- `release/vX.Y.Z`: rama para preparar versiones.
- `hotfix/<nombre>`: para parches urgentes en producción.

---

## 📝 Convenciones de Commit
Formato:
<tipo>: Descripcion breve

Ejemplos:
- `feat: agregar pantalla de login`
- `fix: corregir error en polyline de mapa`

Tipos disponibles:
- `feat` → nueva funcionalidad
- `fix` → corrección de errores
- `docs` → documentación
- `style` → cambios de formato (sin lógica)
- `refactor` → reestructuración de código
- `test` → pruebas
- `chore` → tareas menores (configs, scripts, etc.)

---

## 🔀 Pull Requests
1. Crear rama desde `develop`.
2. Hacer commits pequeños y claros.
3. Subir cambios y abrir PR hacia `develop`.
4. Esperar revisión de al menos 1 compañero.
5. No hacer merge directo a `main`.

---

## ✅ Checklist antes de subir PR
- [ ] Código probado en local.
- [ ] Sin errores de consola.
- [ ] Variables sensibles no subidas al repo.
- [ ] Documentación actualizada si aplica.
