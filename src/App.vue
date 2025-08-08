<script>
import AdminDashboard from './components/AdminDashboard.vue';
import Leads from './components/Leads.vue';
export default {
  name: 'App',
  components: {
    AdminDashboard,
    Leads
  },
};
</script>

<template>
  <div id="app" class="bg-gray-100">
    <!-- <AdminDashboard /> -->
    <Leads />
  </div>
</template>
