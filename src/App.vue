<template>
  <v-app>
    <Sbar/>
    <Appbar/>
    <Navbar/>
    <v-main>
      
    </v-main>
    <Footer/>
    <Vbotton/>
  </v-app>
</template>

<script>

import Footer from './components/Footer';
import Navbar from './components/Navbar';
import Vbotton from './components/Vbotton';
import Sbar from './components/Sbar';
import Appbar from './components/Appbar';

export default {
  name: 'App',

  components: {
    Footer,
    Appbar,
    Navbar,
    Vbotton,
    Sbar,
    
  },

  data: () => ({
    //
  }),
};
</script>
