<template>
    <div class="content">
        <h3>Contact</h3>
        <Contact/>
    </div>
    <ContactVue/>
</template>
<script>
import ContactVue from '../components/ContactVue.vue'
export default {
    name: 'ContactView',
    components: {
        ContactVue
    }

}

</script>
<style scoped>
    
</style>