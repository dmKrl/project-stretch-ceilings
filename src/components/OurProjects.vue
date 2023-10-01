<template>
  <div class="projects">
    <heading-and-buttons />
  </div>
  <div>

  </div>
</template>

<script>
export default {
  data() {
    return {
      item: [
        {
          img: '',
          nameCeiling: '',
          price: '',
          collectionCanvas: '',
        },
      ],
    };
  },
};
</script>

<style scoped>
.projects {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 100px 140px;
}
</style>
