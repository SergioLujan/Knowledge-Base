# 🧠 Base de Conocimiento Personal

Repositorio para guardar y organizar páginas web, artículos, herramientas o recursos que aportan valor, con el fin de tener un registro centralizado, buscable y con historial en el tiempo.

## 📄 Estructura del repositorio

```
knowledge-base/
├── README.md        → Este archivo (explicación del proyecto)
└── recursos.md       → Tabla principal con todos los recursos guardados
```

## 📝 ¿Qué información se guarda por cada recurso?

| Campo               | Descripción                                                             |
|---------------------|--------------------------------------------------------------------------|
| Fecha de registro   | Fecha en la que se agregó el recurso (formato AAAA-MM-DD)                |
| Título              | Nombre corto del recurso o de la página                                  |
| Link                | URL de la página                                                          |
| Descripción         | Breve resumen de qué trata y por qué aporta valor                        |
| Categoría / Etiquetas | Palabras clave para poder filtrar o buscar por tema                    |
| Notas               | Observaciones adicionales (opcional): por qué lo guardaste, para qué te sirve, ideas futuras, etc. |

## 🔄 Cómo se usa

1. Encuentras una página o recurso que te aporta valor.
2. Me compartes el link (y opcionalmente contexto de por qué te interesa).
3. Yo reviso el contenido, redacto la descripción y categoría, y agrego la fila correspondiente en `recursos.md`.
4. Cuando quieras, actualizas el repositorio en GitHub con los cambios (ver sección de sincronización más abajo).

## 🚀 Cómo subir este repositorio a GitHub (primera vez)

1. Crea un repositorio nuevo en GitHub (por ejemplo `knowledge-base`), sin inicializarlo con README (para evitar conflictos).
2. En tu computadora, dentro de la carpeta donde tengas estos archivos, ejecuta:

```bash
git init
git add .
git commit -m "Primer registro de la base de conocimiento"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/knowledge-base.git
git push -u origin main
```

## 🔁 Cómo actualizar el repositorio cada vez que agreguemos un recurso nuevo

Después de que actualicemos `recursos.md`:

```bash
git add recursos.md
git commit -m "Agrega nuevo recurso: <título del recurso>"
git push
```

## 💡 Ideas futuras (opcional)

- Dividir `recursos.md` en archivos por categoría si la lista crece mucho.
- Agregar un script que convierta un CSV en la tabla markdown automáticamente.
- Usar GitHub Actions para validar que no haya links rotos.
