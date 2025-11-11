<template>
    <div class="zichuanfu">
        <h3>child</h3>
        <button @click="clickmsg"></button>
    </div>
</template>
<script>
import { ms } from 'element-plus/es/locales.mjs';

export default {
    name: 'zichuanfu',
    data() {
        return {
            msg: '这是子组件'
        }
    },

    methods: {
        clickmsg() {
            this.$emit('someEvent', this.msg);
        }
    }
}
</script>
<style scoped>

</style>
