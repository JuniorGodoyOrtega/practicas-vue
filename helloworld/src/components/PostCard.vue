<template>
    <div class="post-card">
        <h1>Hola Mundo</h1>
        <p>Este es un componente, Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum perspiciatis temporibus hic quam necessitatibus impedit dicta odio corrupti, nostrum eaque earum in voluptatibus perferendis rerum aspernatur explicabo delectus incidunt fugit.</p>
        <PostButton />
    </div>
</template>

<script setup>
    import PostButton from './PostButton.vue';
</script>

<style scoped>
    .post-card {
        background-color: #f1f1f1;
        border-radius: 10px;
        padding: 20px;
        margin: 10px 0;
    }
    h1 {
        color: green;
    }
</style>