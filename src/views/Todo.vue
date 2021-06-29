<template>
  <div class="home">
   
    <!-- <v-list v-if="tasks.length" class="pt-0" flat> -->
    <list-tasks v-if="$store.state.tasks.length" />
    <!-- <div v-else class="no-tasks">
      <v-icon size="100" color="green darken-2"> mdi-check</v-icon>
      <div class="text-h5 primary--text">No tasks</div>
    </div> -->
    <no-tasks v-else />
    <button-done-sorting 
    v-if="$store.state.sorting"
    />
  </div>
</template>

<script>
import ListTasks from "../components/Todo/ListTasks.vue";
import NoTasks from "../components/Todo/NoTasks.vue";
import ButtonDoneSorting from "../components/Todo/ButtonDialogSorting.vue";
export default {
  name: "Home",

  components: {
    "list-tasks": ListTasks,
    "no-tasks": NoTasks,
    "button-done-sorting": ButtonDoneSorting,
  },
};
</script>

