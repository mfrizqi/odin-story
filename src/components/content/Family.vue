<template>
    <div class="content">
        <div class="family">
            <h1>Family</h1>
            <p>Odin is the son of Borr and the jötunn Bestla. He is married to the goddess Frigg, by whom he is the father of the twin gods Baldr and Höðr. With the giantesses Gríðr and Rindr, Odin has two other sons named Víðarr and Váli. His eldest son is Thor, god of thunder, born to him by Jörð, the personification of the Earth.</p>
            <div class="family-photos">
                <FamilyCard/>
                <FamilyCard/>
                <FamilyCard/>
                <FamilyCard/>
                <FamilyCard/>
                <FamilyCard/>
                <FamilyCard/>
            </div>
        </div>
    </div>
</template>

<script>
import FamilyCard from './FamilyCard.vue'

export default {
    name: 'Family',
    components:{
        FamilyCard
    }
}
</script>

<style scoped>
.content{
  margin-top: 10vh;
  display: flex;
  justify-content: center;
  margin-bottom: 10vh;
}

p{
  /* font-family: serif; */
  font-size: 1.2vw;
  line-height: 1.5;
  margin-bottom: 3vh;
}

h1{
  font-size: 3vw;
  font-family: 'Rowdies';
  font-weight: 300;
}

.family{
width: 80%;
}

.family-photos{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}
</style>