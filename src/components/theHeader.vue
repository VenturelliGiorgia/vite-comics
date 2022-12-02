<script>
export default {
    data() {
        return {
            vociMenu: [" CHARACTERS", "COMICS", "MOVIES", "TV", "GAMES", "COLLECTIBILIES", "VIDEOS", "FANS", "NEWS", "SHOP"],
        }
    },
    methods: {
    }
}
</script>
<template>
    <header>
        <div class="container">
            <nav class="mt-3">
                <div class="d-flex justify-content-between align-items-center">
                    <div>
                        <img src="/dc-logo.png" alt="">
                    </div>
                    <div>
                        <ul class="d-flex">
                            <li v-for="menu in vociMenu"> {{ menu }} </li>
                            <div class="active"></div>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>
    </header>
</template>


<style scoped>
li {
    padding: 0 .35rem;
    list-style: none;
}

.active {
    width: 85px;
    border-bottom: 5px solid blue;
    position: absolute;
    top: 130px;
    left: 634px;

}
</style>