<template>
<section>
<HeaderVue/>
  <div style="display:flex;background:white;width:100%;">
<SideBarVue/>
<BodyVue/>
  </div>
</section>

</template>

<script>
import BodyVue from './Body.vue';
import HeaderVue from './Header.vue';
import SideBarVue from './SideBar.vue';
export default {

  name: "ViewLayout",
  components: {
    HeaderVue,
    BodyVue,
    SideBarVue
    
    
  },
};
</script>
<style></style>
