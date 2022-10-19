<template>
    <img v-if="names=== 'perfume'" src="..\images\image-product-desktop.jpg" :width="widths" alt="Perfume">
</template>
<script>
export default{
    props: ['names','widths']
}
</script>