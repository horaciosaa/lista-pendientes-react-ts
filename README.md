# Lista de Pendientes (React + TypeScript)

Una pequeña aplicación de lista de tareas (To‑Do) construida con React y TypeScript. Permite crear, editar, marcar como completadas y eliminar tareas. Ideal como proyecto de aprendizaje o base para expandir funcionalidades.

## Características
- Añadir tareas
- Editar tareas
- Marcar tareas como completadas / pendientes
- Eliminar tareas
- Persistencia local (localStorage) — (si está implementada)
- Interfaz responsiva básica

## Requisitos
- Node.js (recomendado >= 16.x)
- npm, yarn o pnpm
- Git (para clonar el repositorio)

Comprueba la versión recomendada en `package.json` o en la documentación del proyecto.

## Instalación (local)
1. Clona el repositorio:
```bash
git clone https://github.com/horaciosaa/lista-pendientes-react-ts.git
cd lista-pendientes-react-ts
```

2. Instala dependencias (elige uno):
```bash
# con npm
npm install

# o con yarn
yarn

# o con pnpm
pnpm install
```

3. Revisa los scripts disponibles (opcional):
```bash
npm run
# o
yarn run
# o
pnpm run
```

> Nota: los comandos exactos para iniciar pueden variar según la plantilla usada (Create React App, Vite, etc.). Si ves `dev`, `start` o similar, usa ese script.

## Ejecutar en desarrollo
Inicia la aplicación en modo desarrollo:
```bash
# npm
npm start
# o
npm run dev

# yarn
yarn start
# o
yarn dev

# pnpm
pnpm start
# o
pnpm dev
```
Luego abre `http://localhost:3000` o la URL que indique la terminal.

## Compilar para producción
Genera la versión optimizada para producción:
```bash
# npm
npm run build

# yarn
yarn build

# pnpm
pnpm build
```

Para servir localmente la carpeta `build` (ejemplo con `serve`):
```bash
npx serve -s build
```

## Comprobación de TypeScript y linters
- Para comprobar tipos con TypeScript (sin generar archivos):
```bash
npx tsc --noEmit
```
- Si hay scripts de linting:
```bash
npm run lint
# o
yarn lint
# o
pnpm lint
```

## Tests
Si el proyecto incluye tests, puedes ejecutarlos con:
```bash
npm test
# o
yarn test
# o
pnpm test
```
Si no hay tests aún, considera agregar algunos con Jest/React Testing Library.

## Variables de entorno
Si el proyecto requiere variables de entorno, crea un archivo `.env` en la raíz y añade las variables necesarias. Revisa la documentación o `package.json`/código para conocer las claves esperadas.

## Resolución de problemas comunes
- Errores de dependencias: borra `node_modules` y reinstala:
  ```bash
  rm -rf node_modules package-lock.json yarn.lock pnpm-lock.yaml
  npm install
  ```
- Problemas de versión de Node: usa `nvm` para cambiar la versión:
  ```bash
  nvm install 18
  nvm use 18
  ```
- Si la aplicación no arranca, revisa la consola para mensajes de error y comprueba que no falten variables de entorno.

## Contribuir
1. Abre un issue para discutir cambios grandes.
2. Crea una rama (branch) para tu característica o corrección:
   ```bash
   git checkout -b feat/mi-cambio
   ```
3. Haz commits claros y abre un Pull Request.

## Licencia
(Indica la licencia del proyecto aquí, por ejemplo MIT.)  
Ajusta según corresponda.

## Contacto
- Autor: horaciosaa  
- Repositorio: https://github.com/horaciosaa/lista-pendientes-react-ts

¡Gracias por usar o contribuir a este proyecto!
