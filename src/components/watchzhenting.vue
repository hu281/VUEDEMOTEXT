<template>
    <div class="watchzhenting">
        <h3>watch监听</h3>
        <p>
            {{ message }}
        </p>
        <button @click="updata">修改数据</button>
    </div>
</template> 

<script>
export default {
    name: "watchzhenting",
    data() {
        return {
            message:'watchzhenting'
        }
    },
    methods: {
        updata() {
            this.message = '11111111111111111updata'
        }
    },
    watch: {
        message(newVal, oldVal) {
            console.log(newValue, '++++++++++++++');
            console.log(oldValue, '+--------------');
        }
    }
}
</script>

<style scoped>
.watchzhenting {
    color: red;
}
</style>