<script>

export default {
  data() {
    return {
        navLinks : [
            "CHARACTERS",
            "COMISC",
            "MOVIE",
            "TV",
            "GAMES",
            "COLLECT",
            "VIDEO",
            "FANS",
            "NEWS",
            "SHOP"
        ]
    }
  }
}
</script>

<template>
<header>
    <div class="logo">
        <img src="../assets/img 7/dc-logo.png" alt="DC-logo">
    </div>
    <div class="navbar">
        <ul>
            <li v-for="(navItem,index) in navLinks" key="index">
                {{ navItem }}
            </li>

        </ul>
    </div>
</header>
</template>

<style lang="scss" scoped>

header {
    display: flex;
    padding: 20px ;
    align-items: center;
    justify-content: space-around;
}

ul {
    display: flex;

    li {
        color: #79797d;
        font-size: 20px;
        margin-right: 20px;

    }
    
}
    


</style>
