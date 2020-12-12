<template>
    <ul>
        <li v-for="(message, i) in messages" :key="i">
            {{ message }}
        </li>
    </ul>
</template>

<script>
export default {
  name: 'list',
  props: ['messages']
}
</script>