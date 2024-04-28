<template>
 <div>
  <NavbarComponent />
  <JumbotronComponent />
  <AboutComponent />
  <ServiceComponent />
  <CountersComponent />
  <TeamComponent />
  <CentralComponent />
  <PortfolioComponent />
  <ClientsComponent />
  <BlogComponent />
  <SponsorComponent />
  <LocationComponent />
  <ContactComponent />
  <FooterComponent />
 </div>
</template>

<script>
import NavbarComponent from './components/Header-components/NavbarComponent.vue';
import JumbotronComponent from './components/Header-components/JumbotronComponent.vue';
import AboutComponent from './components/Main-components/AboutComponent.vue';
import ServiceComponent from './components/Main-components/ServiceComponent.vue';
import CountersComponent from './components/Main-components/CountersComponent.vue';
import TeamComponent from './components/Main-components/TeamComponent.vue';
import CentralComponent from './components/Main-components/CentralComponent.vue';
import PortfolioComponent from './components/Main-components/PortfolioComponent.vue';
import ClientsComponent from './components/Main-components/ClientsComponent.vue';
import BlogComponent from './components/Main-components/BlogComponent.vue';
import SponsorComponent from './components/Main-components/SponsorComponent.vue';
import LocationComponent from './components/Main-components/LocationComponent.vue';
import ContactComponent from './components/Footer-components/ContactComponent.vue';
import FooterComponent from './components/Footer-components/FooterComponent.vue';


export default {
  name: 'App',
  components: {
    NavbarComponent,
    JumbotronComponent,
    AboutComponent,
    ServiceComponent,
    CountersComponent,
    TeamComponent,
    CentralComponent,
    PortfolioComponent,
    ClientsComponent,
    BlogComponent,
    SponsorComponent,
    LocationComponent,
    ContactComponent,
    FooterComponent
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: 'Roboto', sans-serif;
  color:blue;
  width: 100%;
}


</style>
