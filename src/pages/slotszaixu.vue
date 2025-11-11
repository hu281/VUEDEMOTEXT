<template>
    <h3>插槽3再续</h3>
    <slot name="headerer" :msg="childMsg"></slot>
    <slot name="mainin" :job="jobMsg"></slot>
</template>

<script>
export default {
    name: 'slotszaixu',
    data() {
        return {
            childMsg: 'hello child',
            jobMsg: 'hello job'
        }
    }
}
</script>