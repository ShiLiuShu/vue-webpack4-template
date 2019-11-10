<template>
  <div class="container center-content">
    <RouterView />
    {{#if useUip}}
    <p>Using UIP hahaha</p>
    {{/if}}
  </div>
</template>

<style lang="stylus" scoped>

.container
  font-family 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif
  max-width 1200px

</style>
