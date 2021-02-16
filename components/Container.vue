<template>
  <div>
    <h2> {{titre}}</h2>
    <div>{{contenu}}</div><!-- 
    <div class="item">
      <p>Add item</p>
     <section class="item">
    <div id="checkbox" @click="isChecked = !isChecked">
      <div v-if="!isChecked" class="circle-svg svg-wrapper"> 
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle></svg>
      </div>
      <div v-if="isChecked" class="check-circle-svg svg-wrapper">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path><polyline points="22 4 12 14.01 9 11.01"></polyline></svg>
      </div>   
    </div>
    <div id="item">
      <p>{{ todo }}</p>
    </div>
    <div class="trash-svg svg-wrapper" @click="removeItem(todo)">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="3 6 5 6 21 6"></polyline><path d="M19 6v14a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V6m3 0V4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2"></path><line x1="10" y1="11" x2="10" y2="17"></line><line x1="14" y1="11" x2="14" y2="17"></line></svg>
    </div>
  </section>`,
    <div id="list-items-wrapper">
      <list-input :todos="todos"></list-input>
      <list-stats :todos="todos"></list-stats>
      <list-item
        v-for="todo in todos"
        :key="todo"
        :todo="todo"
        :todos="todos"
      >
      </list-item> -->
  </div>
</template>

<script>
export default {
  name: 'container',
  props: ["titre", "contenu"]
}
</script>

<style scoped>

</style>