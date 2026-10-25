# Apuntes Oficiales: Curso de GitHub - Edutin Academy

**Estado del curso:** ✅ Completado
**Certificado a obtener:** Gestión de Proyectos de Software con Git y GitHub (90 horas certificables)
**Modalidad:** 100% Virtual
**Perfil del instructor:** Harvard University - Ciencias de la Computación

## 🎯 Objetivos del Curso
Al finalizar, seré capaz de:
1.  **Comprender los fundamentos** de Git y GitHub.
2.  **Aplicar técnicas avanzadas** para la creación de commits precisos, gestión de ramas y la resolución de conflictos.

## 📚 Programa del Curso
*   **Unidad 1:** Control de Versiones con Git y GitHub (2 clases)
*   **Unidad 2:** Gestión avanzada de Git y colaboración en GitHub (4 clases)

---

## 🧠 Unidad 1: Control de Versiones con Git y GitHub
- [x] Introducción al curso
- [x] Fundamentos de Git y GitHub

### Super Resumen
*   **Git (Local):** Es el programa que instalamos en la computadora. Rastrea cambios y guarda el historial. Es nuestra "cámara de fotos".
*   **GitHub (Nube):** Plataforma en internet para alojar repositorios, colaborar y mostrar nuestro código. Es nuestro "álbum de fotos".
*   **Flujo de trabajo básico:** `git add .` (preparar) -> `git commit -m "mensaje"` (guardar) -> `git push` (subir a la nube).
*   **Comandos de Supervivencia:** `git clone [url]` (descargar), `git checkout -- [archivo]` (deshacer cambios), `git pull` (actualizar antes de subir).

---

## 🚀 Unidad 2: Gestión avanzada y colaboración
- [x] Introducción a la unidad
- [x] Trabajando con commits y branches
- [x] Características avanzadas de GitHub
- [x] Conclusión del curso

### Conceptos Clave Aprendidos
*   **`git status`:** Es el comando de diagnóstico. Muestra qué archivos han cambiado y en qué estado están.
*   **`git diff`:** Muestra exactamente qué líneas de código se han añadido o eliminado desde el último commit.
*   **Ramas (Branches):** Permiten crear una copia paralela del proyecto para trabajar en nuevas funciones sin dañar la rama principal (`main`).
*   **Pull Request (PR):** Solicitud para unir los cambios de nuestra rama a `main`. Permite que el equipo revise el código antes de aprobarlo.
*   **Conflictos de Merge:** Ocurre cuando dos personas modifican la misma línea de un archivo. Se resuelven eligiendo qué código mantener (VS Code ofrece botones visuales para esto).

---

## 🛠️ Actividad Integradora: Proyecto-Web-Ejemplo
Realicé con éxito el proyecto práctico del curso aplicando todo el flujo de trabajo profesional:

1.  **Creación:** Creé un repositorio público en GitHub con un README inicial.
2.  **Desarrollo:** Cloné el repositorio localmente y añadí archivos `index.html` y `style.css`.
3.  **Ramas:** Creé la rama `feature-mejora-estilo` para aplicar cambios visuales sin afectar `main`.
4.  **Pull Request:** Subí la rama y fusioné los cambios a la principal a través de un PR en GitHub.
5.  **Resolución de Conflictos:** Simulé un conflicto modificando el mismo archivo en dos ramas distintas, lo resolví visualmente en VS Code y finalicé el merge con éxito.
6.  **Documentación:** Actualicé el `README.md` explicando cómo clonar el proyecto y detallando la función de cada rama.

---

## 🚑 Bitácora de Errores y Soluciones
*(Registro de problemas encontrados durante el aprendizaje y cómo los solucioné)*

*   **Error: `'git' no se reconoce como un comando...`**
    *   *Causa:* Git no estaba instalado o no estaba en el PATH de Windows.
    *   *Solución:* Instalar Git desde la web oficial y asegurarse de seleccionar la opción *"Git from the command line and also from 3rd-party software"*.
*   **Error: `touch hello.html` (Comando no encontrado)**
    *   *Causa:* El comando `touch` es de Linux/Mac. En Windows PowerShell no funciona.
    *   *Solución:* Usar el comando `ni hello.html` (New-Item) en PowerShell o crear el archivo directamente desde el explorador de VS Code.
*   **Error: `Author identity unknown`**
    *   *Causa:* Git no sabe quién está haciendo el commit la primera vez.
    *   *Solución:* Configurar el usuario y correo con `git config --global user.name` y `git config --global user.email`.

---

## 🎯 Próximos Pasos
*   Utilizar **GitHub Pages** para publicar el proyecto web y crear mi portafolio online.
*   Empezar a documentar mis nuevos proyectos en la carpeta `01_Proyectos`.
*   Mantener este "Segundo Cerebro" actualizado con cada nueva tecnología que aprenda.

---
*Documento generado como parte de mi formación en Edutin Academy.*
*Curso: [Curso de GitHub](https://edutin.com/curso-de-github)*