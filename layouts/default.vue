<template>
  <div class="container">
    <CThemeProvider>
      <CColorModeProvider>
        <CBox font-family="body" as="main">
          <CReset />
          <Nuxt />
        </CBox>
      </CColorModeProvider>
    </CThemeProvider>
  </div>
</template>
<script>
import {
  CThemeProvider,
  CColorModeProvider,
  CReset,
  CBox,
  CButton,
} from "@chakra-ui/vue";

export default {
  name: "DefaultLayout",
  components: {
    CThemeProvider,
    CColorModeProvider,
    CReset,
    CBox,
    CReset,
    CButton,
  },
};
</script>
