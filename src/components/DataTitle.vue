<template>
    <div class="text-center">
        Selected: <h2 class="text-2xl text-indigo-800 font-bold"> {{text}} </h2>
    </div>
</template>

<script>
export default {
    name: 'DataTitle',
    props: ['text', 'dataDate'],
}
</script>
