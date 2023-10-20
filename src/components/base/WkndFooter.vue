<template>
  <footer className="footer">
    <img :src="logo" className="logo" alt="WKND Logo" />
    <WkndNavMenu />
    <small>Copyright &copy; 2023 Adobe. All rights reserved</small>
  </footer>
</template>

<script>
import WkndNavMenu from './WkndNavMenu.vue';
import logoUrl from '../../assets/wknd-logo-dk.svg?url'


export default {
  name: 'WkndFooter',
  components: {
    WkndNavMenu
  },
  data() {
    return {
      logo: logoUrl
    }
  }
}
</script>
