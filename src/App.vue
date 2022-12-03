<template>
  <HeaderComponent @changePage="onChange($event)" />
  <Home v-if="Page === 'default'"  />
  <Contact  v-if="Page === 'contact'" />
  <Service  v-if="Page === 'service'"  />
  <Team  v-if="Page === 'team'"  />
  <About   v-if="Page === 'about'"/>
  <Portfolio v-if="Page === 'portfolio'" />
  <FotterComponent  />
  
</template>

<script>

import Home from "./components/Home.vue"
import HeaderComponent from "./components/Header.vue";
import FotterComponent from "./components/Fotter.vue";
import Contact from "./components/Contact.vue";
import Service from "./components/Service.vue";
import Team from "./components/Team.vue";
import About from "./components/About.vue";
import Portfolio from  "./components/Portfolio.vue"
export default {
  
  name: 'App',
  components: {
    HeaderComponent,
    FotterComponent,
    Contact,
    Service,
    Team,
    About,
    Home,
    Portfolio,
  },
  data() {
    return {
      Page: "default",
    };
  },
  methods: {
    onChange(event) {
      console.log();
      this.Page = event.page;
     
    },
  },
}

</script>


