<template>
  <div class="content">
      <div class="companies">
            <h1>Companion</h1>
            <p>Known as the All-Father, Odin is often accompanied by two ravens, Huginn and Muninn, along with the wolves Geri and Freki; the god rides into battle atop an eight-legged steed, Sleipnir</p>
            <CompaniesCard v-bind:companies="company"/>
      </div>
  </div>
</template>

<script>
import CompaniesCard from './CompaniesCard'

export default {
    name:'Companies',
    components:{
        CompaniesCard,
    },
    data(){
        return{
            company :[
                {  
                    'name' : 'Huginn & Muninn',
                    'describe' : 'Huginn and Muninn are two ravens are a pair of ravens that fly all over the world, Midgard, and bring information to the god Odin.Their names translate as thought and memory, respectively.',
                    'image' : "odin_50.jpg",
                    'imagelink' : 'https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/3dc0e05c-1099-4bc4-b97f-e36b03a1637a/d5vxhyq-15e3919a-80fe-420d-9406-8be777049fbc.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvM2RjMGUwNWMtMTA5OS00YmM0LWI5N2YtZTM2YjAzYTE2MzdhXC9kNXZ4aHlxLTE1ZTM5MTlhLTgwZmUtNDIwZC05NDA2LThiZTc3NzA0OWZiYy5wbmcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ.c0MJuIu6kVds_fql69yrQNPKYdDmt-ncC3RDj8rbHns'
                },
                {
                    'name' : 'Freki & Geri',
                    'describe' : 'Freki & Geri are two wolves who are said to accompany the god Odin. The two are most often seen at Odin`s side when he is in Valhalla, feasting with the warriors who dwell in its numerous halls. They are said to devour those who would present false information to or otherwise lie to Odin.',
                    'image' : "odin_100.jpg",
                    'imagelink' : 'https://vignette.wikia.nocookie.net/mightythor/images/b/bf/Geri_and_Freki_%28Earth-616%29.jpg/revision/latest?cb=20170109001521'
                },
                {
                    'name' : 'Sleipnir',
                    'describe' : 'In Norse mythology, Sleipnir is the eight-legged horse who serves as Odin`s trusted steed. He is the son of Svaðilfari and the god/jötunn Loki, the latter of whom is actually his mother, having given birth to Sleipnir in the form of a mare. Sleipnir is described as the best and fastest of all horses.',
                    'image' : "odin_100.jpg",
                    'imagelink' : 'https://vignette.wikia.nocookie.net/olympians/images/1/18/Sleipnir.JPG/revision/latest?cb=20171225192902'
                }
            ]
        }
    }
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

.companies{
    width: 80%;
}

.card{
    display: flex;
    justify-content: space-between;
}

</style>