<template>
    <p>Message from Hello: {{ msg }}</p>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
    name: "Hello",
    props: {
        msg: {
            type: String,
            required: true
        }
    }
})
</script>

