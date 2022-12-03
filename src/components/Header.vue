<!-- eslint-disable vue/multi-word-component-names -->
<template>
    <header class="header">
        <div class="logo">
            <a class="logo-link"
                href="https://themeforest.net/item/crucio-responsive-one-page-wordpress-theme/19973422?_ga=2.108674818.1277701530.1669863416-2104601713.1669863416">
                envato<span>market</span>
            </a>
            <button class="btn">buy now</button>
        </div>
        <nav class="navbar">
            <div class="nav-header">
                <img src="http://crucio.riccardoborchi.it/wp-content/uploads/2017/05/logo-1.png" alt="CRUCIO"
                    class="logo-image">
                <button class="nav-toggle">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
            <div class="links-container">
                <ul class="links">
                    <li> <p class="link" :class="{'active' : Page === 'default'}" href=""  @click="changeTab('default')">home</p></li>
                    <li> <p class="link" :class="{'active' : Page == 'about'}" href="" @click="changeTab('about')">about</p></li>
    
                    <li> <p class="link" :class="{'active' : Page == 'service'}" href="" @click="changeTab('service')">Services</p></li>
                    <li> <p class="link" :class="{'active' : Page == 'team'}" href="" @click="changeTab('team')">Team</p></li>
                    <li> <p class="link" :class="{'active': Page == 'portfolio'}" href="" @click="changeTab('portfolio')">PORTFOLIO</p></li>
                    <li> <p class="link" :class="{ 'active': Page == 'contact'}" href="" @click="changeTab('contact')">CONTACT</p></li>
                </ul>
            </div>
        </nav>
    </header>
</template>

<script>
export default {
    data(){
        return {
            Page : 'default',
        }
    },
    methods: {
        changeTab( page) {
            
            this.Page = page;
     
            this.$emit("changePage",{page})
        },
    },
}
</script>