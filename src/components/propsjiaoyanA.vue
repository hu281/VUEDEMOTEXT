<template>
    <div class="propsjiaoyanA">
        <hr>
        <h3>props校验</h3>
        <PropsjiaoyanB></PropsjiaoyanB>
    </div>
</template>


<script>
import PropsjiaoyanB from '../pages/propsjiaoyanB.vue';
export default {
    name: 'PropsjiaoyanA',
    data() {
        return {
            title: 'propsjiaoyanA',
            age: 1800,
            names: ["张三", "李四", "王五"],
        }
    },
    components: {
        PropsjiaoyanB
    }
}
</script>

<style scoped>
.propsjiaoyanA {
    color: palegoldenrod;
}
</style>