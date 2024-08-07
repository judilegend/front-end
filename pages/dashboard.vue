<script setup lang="ts">
import Sidebar from "~/components/Sidebar.vue";
import Navbar from "~/components/Navbar.vue";
import AddTaskTemplate from "~/components/AddTaskTemplate.vue";
</script>
<template>
  <main
    class="w-full grid grid-cols-[300px,1fr] grid-rows-[70px,1fr] h-screen overflow-x-hidden relative"
  >
    <div className="row-span-2  ">
      <Sidebar />
    </div>
    <div className="col-span-1 ">
      <Navbar />
    </div>
    <div className="col-start-2 row-start-2 px-8 z-100">
      <section className="flex w-full justify-between relative">
        <slot></slot>
        <!-- <AddTaskTemplate /> -->
      </section>
    </div>
  </main>
</template>
