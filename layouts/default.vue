<template>
  <div class="container">
    <c-theme-provider>
      <c-color-mode-provider>
        <c-box as="section">
          <c-reset />
          <nuxt />
        </c-box>
      </c-color-mode-provider>
    </c-theme-provider>
  </div>
</template>

<script>
import { CThemeProvider, CColorModeProvider, CReset, CBox } from '@chakra-ui/vue'

export default {
  name: 'DefaultLayout',
  components: {
    CThemeProvider,
    CColorModeProvider,
    CReset,
    CBox
  }
}
</script>
