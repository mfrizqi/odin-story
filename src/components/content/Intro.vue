<template>
    <div>
        <div class="outer">
            <!-- <h2>This is Introduction</h2> -->
            <div class="content">
                <div class="left-content">
                    <h1 class="odin">{{odin.name}}</h1>
                    <!-- <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Molestiae, repellat quibusdam corporis sed minus est accusamus, ab nisi, amet sit reiciendis aut inventore? Dolores corporis cupiditate praesentium maxime totam fuga.</p> -->
                    <p>{{odin.caption}}</p>
                </div>
                <div class="right-content">
                    <!-- dffef -->
                    <div class="odin_picture"></div>
                </div>
            </div>
            <h2 class="scrollmsg"> Be ready to be amazed by the One-eyed! </h2>
        </div>  
    </div>
</template>

<script>

export default {
    name : 'Intro',
    data(){
        return{
            odin: {
                    'name' : 'Odin',
                    'caption' : 'Hear story about the all might of allfather. Sometimes called Allfather who have a central role who in myths about the creation and destruction of the world'
            },
        }
    }
}
</script>

<style scoped>
    .outer{
        /* margin-top: 4vh; */
        /* background-color: slategray; */
        height: 80vh;    
    }

    .content{
        /* background-color: pink; */
        margin: auto;
        height: 100%;
        width: 80%;
        display: flex;
    }

    .left-content{
        word-wrap: break-word;
        /* background-color: indigo; */
        width: 50%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        word-wrap: break-word;
    }

    .left-content h1{
        margin: 0;
        padding: 0;
        font-size: 5vw;
        font-family: 'Rowdies';
        font-weight: 400;
    }

    .left-content p{
        /* background-color: green; */
        margin: 0;
        padding: 0;
        font-size: 1.05vw;
        font-weight: 400;
        width: auto;
    }

    .right-content{
        /* background-color: orange; */
        display: flex;
        justify-content: center;
        align-items: center;
        width: 50%;
    }

    .odin{
        letter-spacing: 5px;
    }

    .odin_picture{
        height: 80%;
        width: 80%;
        /* background-color: orchid; */
        background-image: url('../../assets/odin_50.jpg');
        background-size: cover;
        background-repeat: no-repeat;
    }

    .scrollmsg{
        margin: 0;
        padding: 0;
        text-align: center;
        font-family: 'Rowdies';
        font-weight: 300;
    }

</style>