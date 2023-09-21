<script>
export default {
    // questo é il vs options object
    data() {
        return {
            message: 'Benvenuto nel fantastico mondo di Vite + Vue',
        }
    },
    methods: {
    }
}
</script>

<template>
    <div class="jumbo">
        <div class="title">
            <h1>{{ message }}</h1>
        </div>
        <div class="description">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum obcaecati officia voluptas velit maiores
                molestiae vel sunt facere sint mollitia laudantium magni quisquam odio fuga quasi, a eveniet perspiciatis
                dolores.
            </p>
            <button class="logo">Entra ora</button>
        </div>
    </div>
</template>

<style scoped>
.jumbo {
    background-color: rgb(83, 94, 104);
    padding: 1rem;
    border-radius: 2rem;
}

.title {
    border-bottom: 1px solid rgba(255, 255, 255, 0.5);
}

button {
    transition: all 0.7s;
}

button:hover {

    transform: scale(1.5);
}
</style>