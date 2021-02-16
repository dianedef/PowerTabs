<template>
  <div class="p-6 max-w-sm mx-auto bg-white rounded-xl shadow-md flex items-center space-x-4">
    <a href="https://nuxtjs.org/" target="_blank" class="button--green"
      >Documentation <IconLink
    /></a>
    <NLink to="/about" class="button--grey">About</NLink>
  </div>
</template>

<script>
export default {
  name: 'Link',
}
</script>