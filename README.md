# 📊 Template Dashboard Angular v1

Un template moderno y profesional para crear dashboards con Angular 18, TailwindCSS y Server-Side Rendering (SSR).

## ✨ Características

- **Angular 18.2** - La última versión del framework
- **TypeScript** - Tipado estático para mayor robustez
- **TailwindCSS 4.x** - Framework CSS moderno y utilitario
- **Server-Side Rendering (SSR)** - Mejor rendimiento y SEO
- **Express Server** - Servidor Node.js integrado
- **Componentes Standalone** - Arquitectura moderna de Angular
- **Tests Unitarios** - Configurado con Jasmine y Karma
- **Responsive Design** - Adaptable a todos los dispositivos

## 🚀 Inicio Rápido

### Prerrequisitos

- Node.js (versión 18 o superior)
- npm o yarn

### Instalación

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/EnriqueMendozadevGT/Template_Dashboard_v1.git
   cd Template_Dashboard_v1
   ```

2. **Instala las dependencias**
   ```bash
   npm install
   ```

3. **Ejecuta el servidor de desarrollo**
   ```bash
   npm start
   ```

4. **Abre tu navegador**
   
   Navega a `http://localhost:4200/`. La aplicación se recargará automáticamente si cambias algún archivo.

## 📋 Scripts Disponibles

| Comando | Descripción |
|---------|-------------|
| `npm start` | Inicia el servidor de desarrollo |
| `npm run build` | Construye la aplicación para producción |
| `npm run watch` | Construye en modo observación para desarrollo |
| `npm test` | Ejecuta las pruebas unitarias |
| `npm run serve:ssr:Dashboard` | Ejecuta la aplicación con SSR |

## 🏗️ Estructura del Proyecto

```
src/
├── app/
│   ├── app.component.ts          # Componente principal
│   ├── app.component.html        # Template principal
│   ├── app.component.css         # Estilos del componente principal
│   ├── app.component.spec.ts     # Tests del componente principal
│   ├── app.config.ts             # Configuración de la aplicación
│   ├── app.config.server.ts      # Configuración del servidor
│   └── app.routes.ts             # Definición de rutas
├── index.html                    # Página principal
├── main.ts                       # Punto de entrada de la aplicación
├── main.server.ts                # Punto de entrada del servidor
└── styles.css                    # Estilos globales
```

## 🎨 Personalización

### Colores y Temas

El template incluye un sistema de variables CSS modernas con gradientes y colores personalizables:

```css
--bright-blue: oklch(51.01% 0.274 263.83);
--electric-violet: oklch(53.18% 0.28 296.97);
--french-violet: oklch(47.66% 0.246 305.88);
--vivid-pink: oklch(69.02% 0.277 332.77);
--hot-red: oklch(61.42% 0.238 15.34);
--orange-red: oklch(63.32% 0.24 31.68);
```

### Agregar Nuevos Componentes

```bash
ng generate component nombre-del-componente
```

### Agregar Nuevas Rutas

Edita el archivo `src/app/app.routes.ts`:

```typescript
export const routes: Routes = [
  { path: 'dashboard', component: DashboardComponent },
  { path: 'users', component: UsersComponent },
  { path: '', redirectTo: '/dashboard', pathMatch: 'full' }
];
```

## 🧪 Testing

Ejecutar tests unitarios:
```bash
npm test
```

Para ejecutar tests en modo observación:
```bash
ng test --watch
```

## 📦 Build para Producción

```bash
npm run build
```

Los archivos de construcción se almacenarán en el directorio `dist/`.

## 🌐 Server-Side Rendering

Este template incluye SSR preconfigurado. Para ejecutar la aplicación con SSR:

```bash
npm run build
npm run serve:ssr:Dashboard
```

## 🔧 Configuración Avanzada

### TailwindCSS

El proyecto incluye TailwindCSS 4.x configurado. Puedes personalizar la configuración en:
- PostCSS está configurado para procesar TailwindCSS
- Los estilos se pueden agregar en `src/styles.css`

### TypeScript

Configuración estricta de TypeScript habilitada:
- `strict: true`
- `noImplicitReturns: true`
- `noFallthroughCasesInSwitch: true`

## 🤝 Contribución

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

## 💬 Soporte

Si tienes preguntas o necesitas ayuda:

- 🐛 [Reportar un bug](https://github.com/EnriqueMendozadevGT/Template_Dashboard_v1/issues)
- 💡 [Solicitar una feature](https://github.com/EnriqueMendozadevGT/Template_Dashboard_v1/issues)
- 📧 [Contacto directo](mailto:enriquemendoza.dev@outlook.com)

## 🙏 Reconocimientos

- **Angular Team** - Por el increíble framework
- **TailwindCSS Team** - Por el excelente framework CSS
- **Comunidad de desarrolladores** - Por el feedback y contribuciones

---

⭐ **¡Si te gusta este template, dale una estrella!** ⭐