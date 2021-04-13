<template>
    <div :class="[btnClass,cname]">
        <slot/>
    </div>
</template>

<script>
export default {
    // 调用自定义类名
    props: {
        cname: {
            type: String,
            default: ''
        }
    },
    data() {
        return {
            btnClass: 'btn'    // 基础样式
        }
    }
}
</script>

<style lang="scss">
@import "../../css/element.scss";
.btn {
    @include btn; 
}
</style>
