<template>
    <div class="info-container">
        <div class="info-container__main">
            <img src="https://vendoo.ge/media/wysiwyg/back.png" alt="asd" >

        <div class="info-container__desc">
            <h5>იპოვეთ თქვენთვის სასურველი პროდუქტი მარტივად</h5>
            <p>შეარჩიეთ საუკეთესო</p>
            <button class="choose-banner" >
                <a href="http://weshort.co/other?image=audio" target="_blank">
                    შეარჩიე
                </a>
                
                </button>
        </div>
        <div class="info-container__list">
            <div class="info-container__list-item" :key="index" v-for="(x,index) in items">
                <a  :href="x.href" target="_blank">
                    <img :src="x.image" alt="a">
                </a>
            </div>

        </div>

        </div>

    </div>
</template>

<script>
export default {

    name: 'infoContainer',
    props: {
        msg: String,
        
    },
    data (){
    return {
      items : [
        {href:'http://weshort.co/other?image=audio',image:'https://vendoo.ge/media/wysiwyg/dinamiki-purple.png'},
        {href:'http://weshort.co/other?image=crosleygrey',image:'https://vendoo.ge/media/wysiwyg/22.png'},
        {href:'http://weshort.co/other?image=audio',image:'https://vendoo.ge/media/wysiwyg/3.png'},
        {href:'http://weshort.co/other?image=audio',image:'https://vendoo.ge/media/wysiwyg/4_1.png'}
      ]
    }
    
  }
}

</script>