<template>
  <div class="content">
      <div class="chapter">
          <h1>History</h1>
          <p v-for="s in stories" :key="s.story">{{s.story}}</p>
          <!-- <hr /> -->
      </div>
  </div>
</template>

<script>
export default {
  name : 'History',
  data(){
    return{
      stories : [
        {'story' : 'Odin spanned the history of the Norse mythic world from its creation to its destruction. Before the world existed, he and his two younger brothers, Vili and Ve, killed the frost giant Ymir (pronounced EE-mir). They used Ymir`s bones, blood, and flesh to form the universe. Odin arranged the heavens for the gods, the middle world for humans and dwarfs, and the underworld for the dead. He then created the first man and woman from an ash tree and an elm tree. Among the deities said to have been Odin`s children were Balder (pronounced BAWL-der) and Thor. Odin—the favorite deity of princes, nobles, and warriors—came to be seen as the supreme Norse god, the one to whom the other deities turned for help and advice. He ruled them from his palace Valhalla (pronounced val-HAL-uh) in the heavenly realm called Asgard (pronounced AHS-gahrd). As the god of war, Odin watched over warriors who fell in battle. Valkyries , female deities who served Odin, carried the bravest of the warriors straight to Valhalla. There Odin feasted them and prepared them for Ragnarok (pronounced RAHG-nuh-rok), the final battle in which the gods were doomed to perish.'},
        {'story' : 'Odin was credited with great wisdom, including knowledge of magic and the ability to see the future. He paid a high price for this gift, however, giving one of his eyes in exchange for a drink from the well of Mimir (pronounced MEE-mir). The waters of this well, which seeped from among the roots of the enormous tree known as Yggdrasill (pronounced IG-druh-sil) that supported the world, contained great wisdom. Another myth says that Odin stabbed himself with his magical spear, called Gungnir (pronounced GOONG-nir), and hung from Yggdrasill for nine days and nights in a living death. This self-sacrifice gave him knowledge of the runes, the Norse symbols used for writing and fortune-telling. Yet, although Odin was wise, he could also be sly and treacherous. It was not unusual, for example, for him to break his word or to turn people against each other to start conflicts.'},
        {'story' : 'Odin had the power to change his appearance, and this shape-shifting played a part in the myth that explains Odin`s connection with poetry. The wisest being who ever lived was Kvasir (pronounced VAHS-eer), whom the gods had formed from their own saliva. Dwarves killed Kvasir and mixed his blood with honey to form a potion that granted wisdom and the gift of poetry. A giant hid the potion in the middle of a mountain and set his daughter to guard it. Odin changed himself into a snake and slithered through a tiny hole in the mountain. Taking the form of a handsome giant, he charmed the daughter into letting him drink the potion. Once Odin had swallowed it, he changed into an eagle and flew to Asgard, where he vomited the potion into three sacred vats. A few drops of the potion fell to the earth during his flight and became the inspiration for human poets.'},
      ]
    }
  }
}
</script>

<style scoped>

.content{
  margin-top: 20vh;
  display: flex;
  justify-content: center;
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

.chapter{
width: 80%;
}

</style>