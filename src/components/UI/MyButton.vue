<template>
  <button class='btn'>
    <slot></slot>
  </button>
</template>

<script>
export default {
  name: 'MyButton'
}
</script>

<style>
.btn {
  background-color: #6932a8;
  color: white;
  border: none;
  border-radius: 5px;
  padding: 10px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  margin-top: 10px;
}

.btn:hover {
  background-color: #0057b3;
}
</style>