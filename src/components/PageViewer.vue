<template>
    <div class="container">
        <h1>{{ page.pageTitle }}</h1>
        <p>{{ page.content }}</p>
        test
    </div>
</template>
<script>
export default {
    props: ['page']
}
</script> 