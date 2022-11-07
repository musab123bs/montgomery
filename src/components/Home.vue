<template>
  <div>
    <TopHeader />
    <OurMission/>
    <CompanyStats/>
    <NewsMedia/>
    <OurMap/>
    <OurFooter/>
  </div>
</template>

<script>
import TopHeader from "./Header.vue";
import OurMission from './OurMission.vue';
import CompanyStats from './CompanyStatus.vue';
import NewsMedia from './News.vue';
import OurMap from './Map.vue';
import OurFooter from './Footer.vue';


export default {
  name: 'MainHome',
  components: {
    TopHeader,
    OurMission,
    CompanyStats,
    NewsMedia,
    OurMap,
    OurFooter
  },
};
</script>