<script>
    export default{
        name: "AppCards",
    };
</script>

<template>
    <section>
        <div class="container">
        --> content goes here <--
        </div>
    </section>
</template>

<style scoped lang="scss">
    @use "../style/partials/variables" as *;

    section{
        min-height: 200px;
        background-color: $secondary_dark;
        color: white;
        font-size: 2rem;
        .container{
            padding: 20px;
        }
    }
</style>