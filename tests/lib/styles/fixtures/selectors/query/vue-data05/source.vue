<script>
export default {
    data: {
        classData: { bar: false },
        classData2: { foo: true }
    }
}
</script>
<template>
    <ul>
        <li id="a" :class="classData" />
        <li id="b" :class="classData2" />
    </ul>
</template>
<style scoped>
.bar {
}
</style>
