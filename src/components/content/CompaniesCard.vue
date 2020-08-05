<template>
    <div class="card">
        <div v-for="company in companies" :key="company.name">   
            <div class="profile"
            :style="{ 
                        backgroundImage: 'url('+ company.imagelink +')',
                    }">
            </div>
            
            <!-- 
             <div class="profile"
                :style="{ 
                            backgroundImage: `url(${odin50})`,
                        }">
            </div>

            <div class="profile"
                :style="{ 
                            backgroundImage: `url('@/assets/odin_50.jpg')`,
                        }">
            </div> -->
            <h1>{{company.name}}</h1>
            <p>{{company.describe}}</p>
        </div>
    </div>
</template>

<script>

import odin50 from '@/assets/odin_50.jpg';

export default {
    name: 'CompaniesCard',
    props: ['companies'],
    data(){
        return{
            odin50
        }
    }
}
</script>

<style scoped>
    .profile{
        height: 40vh;
        width: 30vh;
        background-color: crimson;
        /* background-image: url('../../assets/vidar.jpg'); */
        background-repeat: no-repeat;
        background-size: cover;
        /* margin-right: 2vh;
        margin-bottom: 4vh; */
    }

    div{
        height: auto;
        width: auto;
    }

    h1{
        /* margin: 0;
        padding: 0; */
        font-family: 'rowdies';
        font-weight: 300;
    }

    p{
        margin: 0;
        padding: 0;
        width: 30vh;
    }

    .card{
        display: flex;
        justify-content: space-between;
     }

</style>
