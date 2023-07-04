<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique placeat
      corporis veniam, odit dicta maxime totam praesentium esse possimus minima
      sequi consequuntur asperiores, ea facilis harum quis neque at eaque!
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;

definePageMeta({ layout: "products" });
</script>

<style lang="scss" scoped></style>
