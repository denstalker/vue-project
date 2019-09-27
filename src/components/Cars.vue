<template>
  <div>
    <h3>Название : {{carName}}</h3>
    <p>Год выпуска : {{carYear}}</p>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
        carName: 'Ford',
        carYear: 2008
    };
  }
};
</script>