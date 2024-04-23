<script>
  import AppHeader from './components/AppHeader.vue'
  import AppJumbotron from './components/AppJumbotron.vue'
  import HomeMakeMark from './components/HomeMakeMark.vue'
  import HomeGame from './components/HomeGame.vue'
  import HomeFacts from './components/HomeFacts.vue'

  export default{
    name: "App",
    components:{
      AppHeader,
      AppJumbotron,
      HomeMakeMark,
      HomeGame,
      HomeFacts,
    },
    data(){
      return {
        header:[
          {
            title: "Home",
            active: true,
            hasSubMenu: false,
            subMenu: []
          },
          {
            title: "Games",
            active: false,
            hasSubMenu: true,
            subMenu: []
          },
          {
            title: "Shop",
            active: false,
            hasSubMenu: true,
            subMenu: []
          },
          {
            title: "Pages",
            active: false,
            hasSubMenu: true,
            subMenu: []
          },
          {
            title: "Blog",
            active: false,
            hasSubMenu: true,
            subMenu: []
          },
          {
            title: "Contact",
            active: false,
            hasSubMenu: false,
            subMenu: []
          }
        ],
        footer: {
          quicklinks: [
            "Games", "Latest Tournament", "shop", "Blog", "Contact" 
          ],
          help:[
            "Faqs", "Terms & Conditions", "Privacy"
          ],
          followUs:[
            "Facebook", "Twitter", "Instagram", "Youtube", "Github"
          ],
          contactUs: [
            "4 Mayfield, Buckden, PE19 5SZ", "(302) 555-0107"
          ]
        }
      }
    }
  }
</script>


<template>
  <header>
    <AppHeader></AppHeader>
    <AppJumbotron></AppJumbotron>
  </header>
  <main>
    <HomeMakeMark></HomeMakeMark>
    <HomeGame></HomeGame>
    <HomeFacts></HomeFacts>
  </main>
</template>

<style lang="scss">
    @use './style/variables/_variables.scss' as variable;

    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Orbitron", sans-serif;
    }

    .my-btn{
      border: 0;
      padding: 12px 24px;
    }

    .primary-color{
      color: variable.$primary-color;
    }

    .secondary-color{
      color: variable.$secondary-color;
    }

    .brand-gray{
      color: variable.$brand-gray;
    }

    .secondary-font{
      font-family: "Barlow", sans-serif;
    }

    .my-btn-primary{
      background-color: variable.$primary-color;
      border-radius: 30px;
      font-weight: 600;
      font-size: variable.$font-size-medium;
      font-family: "Barlow", sans-serif;
      outline: 1px solid variable.$primary-color;
      outline-offset: 5px;
      transition: 0.2s ease;
    }

    .my-btn-primary:hover{
      outline: 1px solid variable.$secondary-color;
      background-color: variable.$secondary-color;
    }

    .my-play-btn{
      border-radius: 100%;
      height: 60px;
      width: 60px;
      color: variable.$primary-color;
      outline: 1px solid variable.$primary-color;
      outline-offset: 10px;
      font-size: 20px;
    }

    // HEADER

    header{
      background-image: url("./src/assets/img/index-banner-bg.png");
      color: white;
      font-size: variable.$font-size-medium;
      height: 900px;
      overflow: hidden;
    }

    // HEADER
</style>
