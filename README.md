Thought for 10s### QUIPUX - Frontend

Sistema de gestión escolar desarrollado con Angular para la administración de estudiantes, grupos, materias, evaluaciones e informes académicos.

## Características

- Gestión completa de estudiantes
- Administración de grupos y grados
- Control de materias académicas
- Registro y seguimiento de evaluaciones
- Generación de informes académicos
- Interfaz responsive y moderna


## Tecnologías

- Angular
- TypeScript
- RxJS
- Angular Router


## Instalación

```shellscript
# Clonar repositorio
git clone https://github.com/tu-usuario/quipux-frontend.git
cd quipux-frontend

# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
ng serve
```

La aplicación estará disponible en `http://localhost:4200`

## Estructura del Proyecto

```plaintext
src/app/
├── _models/          # Modelos de datos (estudiante, grupo, materia, etc.)
├── _services/        # Servicios para consumo de API
└── components/       # Componentes de la aplicación
```

## Scripts

```shellscript
npm start           # Servidor de desarrollo
npm run build       # Build de producción
npm test            # Ejecutar tests
npm run lint        # Análisis de código
```

## Configuración

Configurar las variables de entorno en `src/environments/environment.ts`:

```typescript
export const environment = {
  production: false,
  apiUrl: 'http://localhost:3000/api'
};
´´´

---

**QUIPUX** - Sistema de Gestión Escolar
