<template>
    <div class="main">
        About me
    </div>
</template>

<script>

export default {
    name: 'About me',
    props: {
        msg: String
    }
}
</script>
<style scoped>
    div{
        flex: left;
        width: max-content;
        border: 1px solid black;
    }
    .main{
        margin-left: 45%;
    }
</style>