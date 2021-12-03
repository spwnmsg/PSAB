<template>
    <p> {{ user }}: {{ message }} </p>
</template>

<script>
export default {
    data() {
        return { user: "tags", message: "Hey o/" };
    },
}
</script>