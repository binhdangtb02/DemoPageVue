<!-- eslint-disable vue/no-unused-components -->
<template>
    <section class="service" id="service">
        <div class="service-content">
            <h1>SERVICES</h1>
            <hr />
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium quibusdam, beatae iure nostrum
                suscipit, laborum asperiores dolore doloremque nemo dolorem eius neque facere earum iusto itaque
                placeat, quae sequi! Iure!
                Sed ut, corporis maiores porro id blanditiis provident cum iusto mollitia quo rem doloremque excepturi
                tempora soluta debitis quia repellendus labore veritatis neque impedit sapiente. Voluptatem eos sed
                maxime earum.
            </p>
            <div class="service-category-container">
                <div class="service-category">
                    <CheckCircleOutlined class="service-icon" />
                    <h2 class="service-title">WEB DESIGN</h2>
                </div>
                <div class="service-category">
                <CheckCircleOutlined class="service-icon" />
                    <h2 class="service-title">WEB DESIGN</h2>
                </div>
                <div class="service-category">
                    <CheckCircleOutlined class="service-icon" />
                    <h2 class="service-title">WEB DESIGN</h2>
                </div>
                <div class="service-category">
                    <CheckCircleOutlined class="service-icon" />
                    <h2 class="service-title">WEB DESIGN</h2>
                </div>
                <div class="service-category">
                    <CheckCircleOutlined class="service-icon" />
                    <h2 class="service-title">WEB DESIGN</h2>
                </div>
                <div class="service-category">
                    <CheckCircleOutlined class="service-icon" />
                    <h2 class="service-title">WEB DESIGN</h2>
                </div>
                <div class="service-category">
                    <CheckCircleOutlined class="service-icon"/> 
                    <h2 class="service-title">WEB DESIGN</h2>
                </div>
                <div class="service-category">
                    <CheckCircleOutlined class="service-icon" />
                    <h2 class="service-title">WEB DESIGN</h2>
                </div>
            </div>
        </div>
        <div class="service-register">
            <h2>WE CREATE <span class="service-awesome">AWESOME</span> PROJECTS</h2>
            <button class="service-register-btn">GET STARTED</button>
        </div>
    </section>
    
</template>

<script>

import {UserOutlined, CheckCircleOutlined, } from '@ant-design/icons-vue';

export default {

    name: 'App',
    components: {
        
        CheckCircleOutlined,
    },
 
}

</script>