<template>
    <div>
        <h3>brand : {{ brand }}</h3>
        <h3>price : {{ price }}</h3>
        <h3>color : {{ color }}</h3>
    </div>
</template>

<script>
    export default {
        name : 'Car',
        data() {
            return {
                brand : '宝马520',
                price : 10,
                color : '黑色'
            }
        }
    }
</script>

