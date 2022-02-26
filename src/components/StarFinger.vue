<template>

<button type="button" class="btn btn-primary">Проголосовать</button>

<button type="button" class="btn btn-dark" @click="$emit('increaseBy', 1)">Добавить</button>

</template>
<script>
export default{
  name:'StarFinger',
}

</script>