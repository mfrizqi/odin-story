<template>
  <div class="content">
    <div class="weapon">
        <h1>Weapon</h1>
        <div class="weapon-image"></div>
        <div class="quote-contain">
            <div class="quote">
                <h2 class="quote-message">"By Gungnir, the hallowed weapon of the All-Father, I declare that these seven heroes shall have full rights of passage through the Nine Worlds, including Valhalla."</h2>
                <h2 class="quote-name">Odin</h2>
            </div>
        </div>
        <p><strong>Gungnir</strong> (Old Norse Gungnir, “Swaying;” pronounced “GUNG-neer”) is the name of the mighty spear that belongs to the god Odin. In the recorded Norse myths, <strong>Gungnir</strong> is the weapon most consistently and powerfully associated with <strong>Odin</strong>. Both poetry and visual art demonstrate that this connection is deep and long-standing. It goes back at least as far as the ninth century, when the poet Bragi Boddason referred to Odin as <strong>Gungnis váfaðr</strong> (“Gungnir’s shaker”). Pre-Christian <strong>Scandinavian</strong> visual art often depicts Odin bearing a spear; in fact, the spear is one of his most typical iconographic attributes. Such depictions are found from <strong>Viking Age</strong> runestones all the way back to Bronze Age rock carvings of a spear god, who very well may be Odin (though due to the very early date and lack of other distinguishing features, it’s impossible to say for certain).</p>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Weapon'
}
</script>

<style scoped>

div{
    margin: 0;
    padding: 0;
}

.content{
  margin-top: 10vh;
  margin-bottom: 10vh;
  display: flex;
  justify-content: center;
}

p{
  font-size: 1.2vw;
  line-height: 1.5;
  margin-bottom: 3vh;
}

.quote-contain{
    display: flex;
    justify-content: center;
}

.quote{
    width: 70%;
    margin-top: 5vh;
}

h1,h2 {
  font-family: 'Rowdies';
  font-weight: 300;
}

h2{
    font-size: 1.5vw;
}

h1 {
    font-size: 3vw;
}

.weapon{
    width: 80%;
    /* margin-top: 5vh; */
}

.weapon-image{
    margin: auto;
    margin-top: 10vh;
    width: 70%;
    height: 40vh;
    /* background-color: crimson; */
    background-image: url('https://blog.vkngjewelry.com/wp-content/uploads/2019/10/Gungnir_-The-Spear-of-Odin-1280x720.png');
    background-size: contain;
    background-repeat: no-repeat;
}
</style>