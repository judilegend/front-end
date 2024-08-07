<script setup lang="ts">
import AddTaskTemplate from "~/components/AddTaskTemplate.vue";
import ContainerDashboard from "~/components/ContainerDashboard.vue";
</script>

<template>
  <div>
    <ContainerDashboard>
      <main>
        <AddTaskTemplate />
      </main>
    </ContainerDashboard>
  </div>
</template>
