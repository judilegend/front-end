<script setup lang="ts">
import AddTaskTemplate from "~/components/TaskFormTemplate.vue";
import ListUser from "~/components/ListUser.vue";
import ContainerDashboard from "~/components/ContainerDashboard.vue";
</script>

<template>
  <div>
    <ContainerDashboard>
      <main class="w-full flex justify-between">
        <section class="mt-20 flex gap-5 flex-wrap justify-around">
          <ListUser />
          <ListUser />
          <ListUser />
          <ListUser />
          <ListUser />
          <ListUser />
        </section>
        <section>
          <AddTaskTemplate />
        </section>
      </main>
    </ContainerDashboard>
  </div>
</template>
