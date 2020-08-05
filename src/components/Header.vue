<template>
    <div>
        <span>Odin</span>
        <ul>
            <li>History</li>
            <li>Companion</li>
            <li>Weapon</li>
        </ul>
    </div>
</template>

<script>
export default {
    name : 'Header'
}
</script>

<style scoped>

    div{
        margin: 4vh 0 0 0;
    }

    span{
        font-family: 'Rowdies';
    }

    span{
        font-size: 1.8vw;
    }
    
    ul{
        list-style-type: none;
        display: inline;
    }

    li{
        font-size: 1.2vw;
        display: inline;
        margin-left: 2vw;
    }
</style>