<template>
    <div class="about">
        {{ msg }}
    </div>
</template>

<script>
export default {
    name: 'about',
    data: () => {
        return {
            msg: 'About Page!'
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1, h2 {
    font-weight: normal;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    display: inline-block;
    margin: 0 10px;
}

a {
    color: #35495E;
}
</style>