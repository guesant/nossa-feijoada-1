<template>
  <div>
    <div class="p-2">
      <button @click="$emit('set', i)" class="text-left">Usar template</button>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    i: Object 
  }
}
</script>
