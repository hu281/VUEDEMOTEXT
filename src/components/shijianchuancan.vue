<template>
    <div class="shijianchuancan">
        <h3>事件传参</h3>
        <button @click="count1">add 454</button>
        <p>count is {{ countNum }}</p>

        <button @click="newCount('hello syxy')">newCount 222</button>
        <hr>
    </div>
</template>

<script>
export default {
    name: 'Shijianchuancan',
    data() {
        return {
            countNum: 0
        }
    },
    methods: {
        count1() {
            this.countNum += 454;
        },
        newCount(message) {
            this.countNum += 222;
            console.log(message);
        }
    }
}
</script>

<style scoped>
.shijianchuancan {
    color: lightcoral;
    border: 1px solid lightcoral;
    padding: 10px;
    margin: 10px 0;
}
</style>