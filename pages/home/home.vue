<template>
    <div id="wrapper">
        <!-- Content Wrapper -->
        <app-sidebar></app-sidebar>
        <div id="content-wrapper" class="d-flex flex-column">

            <!-- Main Content -->
            <div id="content">
                <app-header></app-header>
                <app-header v-if="isAuth"></app-header>
            </div>
        </div>
    </div>
</template>

<script>
import Sidebar from '@/components/layouts/Sidebar.vue'
import Header from '@/components/layouts/Header.vue'
export default {
    name: 'ArdhianiNuxt',
    components: {
        'app-sidebar': Sidebar,
        'app-header': Header
    }
}
</script>