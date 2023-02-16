<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Laboratorio de sistemas y aplicaciones web email contacto@isclab.com.mx</template>


  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>  ¿Qué hacemos en isclab?</template>

    Desarrollamos aplicaciones con fines de práctica, investigación y responsabilidad social.
    Buscamos el desarrollo de nuestros estudiantes a través de la creación de proyectos que sean útiles a la sociedad.<br>

    <a href="https://on.cypress.io/component" target="_blank">¿Tienes un proyecto en mente?</a>.
    Compártelo con nosotros y buscaremos la manera de ayudarte.

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>¿pueden crear un sitio web gratuito para mi proyecto?</template>
    La respuesta corta es sí.<br>
    Claro que necesitamos saber en qué consiste el sitio que necesitas y tu historia para valorar el apoyo gratuito en la creación y publicación de tu sitio.<br>
    <a href="https://on.cypress.io/component" target="_blank">Averigua las condiciones de un sitio web gratuito </a>.
    para nosotros será un placer apoyarte.



  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>¿Qué clase de proyectos realizamos?</template>
    Nuestro laboratorio está pensado para <b>programadores</b> por lo que los productos que creamos se categorizan como software.
    El software puede encajar en alguna de estas posibilidades:
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>
</template>
