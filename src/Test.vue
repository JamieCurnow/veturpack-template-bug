<template lang="html">
  <div class="">
    <SomeComponent>
      <template #header>
        <div class="">Hello</div>
      </template>
      <template #footer>
  <div class="">Hello</div>
</template>
    </SomeComponent>
  </div>
</template>

<script>
export default {
  props: ['foo', 'bar']
}
</script>