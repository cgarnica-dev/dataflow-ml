# Guía de contribución y evidencia inicial

## Creación en GitHub

1. Iniciar sesión en GitHub con la cuenta que será propietaria.
2. Abrir https://github.com/new y usar el nombre `dataflow-ml`.
3. Descripción: Pipeline de datos para entrenamiento de modelos ML - Proyecto Integrador.
4. Seleccionar público si el equipo desea acceso directo del docente. Si se usa privado, invitar también al usuario del docente.
5. Crear el repositorio e incorporar README.md con título, descripción y autores. El contenido de esta entrega se publicó mediante GitHub.
6. En Settings > Collaborators, añadir las cuentas confirmadas de los compañeros y esperar la aceptación.

## Repositorio oficial

https://github.com/cgarnica-dev/dataflow-ml

El repositorio fue creado públicamente en GitHub y el README se publicó mediante el editor web. Esto no sustituye el commit y push desde el entorno local de cada integrante. Para contribuir, clonar el repositorio oficial siguiendo las instrucciones siguientes.

## Commit y push local de cada integrante

Cada persona ejecuta desde su propio equipo, con Git instalado y su cuenta autenticada:

```powershell
git clone https://github.com/cgarnica-dev/dataflow-ml.git
cd dataflow-ml
git config user.name "NOMBRE COMPLETO"
git config user.email "CORREO ASOCIADO A SU CUENTA"
git pull --ff-only origin main
```

Crear un archivo NUEVO en `evidencias/aportes/` según el integrante:

- Jose: `jose-villavicencio.md`, con acuerdos Scrum y seguimiento.
- Cesar: `cesar-garnica.md`, con prioridades y criterios del producto.
- Sebastian: `sebastian-haro.md`, con estructura técnica y flujo de datos.

Guardar nombre, rol y descripción del aporte real. Después ejecutar, sustituyendo ARCHIVO y MENSAJE:

```powershell
git add evidencias/aportes/ARCHIVO.md
git commit -m "MENSAJE"
git push origin main
git log -1 --format="%h | %an | %s"
git status -sb
```

Hacer los aportes iniciales de forma secuencial: cada persona clona o actualiza después del push anterior. Si el push se rechaza, ejecutar `git pull --rebase origin main`, resolver conflictos si aparecen y repetir `git push origin main`. Nunca usar `--force` en esta validación.

## Evidencia requerida

1. Captura del terminal local que muestre el commit y un push exitoso hacia el repositorio oficial, sin tokens ni contraseñas.
2. Captura de GitHub > Commits que muestre autor, mensaje y hash de cada aporte.
3. Añadir fecha, hash y enlace al commit real en `evidencias/registro.md` y en el informe.

El autor mostrado en GitHub no demuestra por sí solo quién ejecutó el push ni que existió conexión desde el equipo local. Un commit creado solo desde la web tampoco valida el requisito del entorno local.

## Fuentes oficiales

- https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories
- https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository
- https://docs.github.com/en/get-started/using-git/about-git
