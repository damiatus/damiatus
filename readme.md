# Awesome GitHub Profile Readme Templates

Este proyecto proporciona una colección de plantillas increíbles para perfiles de GitHub.

## Contenido

- **Plantillas de perfil**: Encuentra diversas plantillas para personalizar tu perfil de GitHub.
- **Cómo usar**: Instrucciones sobre cómo implementar estas plantillas en tu perfil.

## Recursos

1. **[Awesome GitHub Profile Readme Templates](https://github.com/durgeshsamariya/awesome-github-profile-readme-templates)**

## Configuración del Sidebar

Para personalizar el sidebar en tu repositorio, puedes usar la configuración de Docsify. Aquí hay un ejemplo básico de configuración:

```html
<script>
  window.$docsify = {
    search: [ '/_sidebar' ],
    name: 'Awesome Github Profile Readme Templates',
    basePath: 'https://raw.githubusercontent.com/durgeshsamariya/awesome-github-profile-readme-templates/master/',
    loadSidebar: true,
    auto2top: true,
    sidebarDisplayLevel: 1,
  }
</script>
<script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
<script src="//cdn.jsdelivr.net/npm/docsify-darklight-theme@3/dist/docsify-themeable/main.min.js"></script>
<script src="//cdn.jsdelivr.net/npm/docsify-darklight-theme@3/dist/docsify-themeable/index.min.js"></script>
<script src="//cdn.jsdelivr.net/npm/docsify-sidebar-collapse/dist/docsify-sidebar-collapse.min.js"></script>
<script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/search.min.js"></script>
