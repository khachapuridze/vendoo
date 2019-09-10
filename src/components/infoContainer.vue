<template>
    <div class="info-container">
        <div class="info-container__main">
            <img src="https://vendoo.ge/media/wysiwyg/back.png" alt="asd" >

        <div class="info-container__desc">
            <h5>იპოვეთ თქვენთვის სასურველი პროდუქტი მარტივად</h5>
            <p>შეარჩიეთ საუკეთესო</p>
            <button class="choose-banner" href="">შეარჩიე</button>
        </div>
        <div class="info-container__list">
            <div class="info-container__list-item">
                <img src="https://vendoo.ge/media/wysiwyg/dinamiki-purple.png" alt="a">
            </div>
            <div class="info-container__list-item">
                <img src="https://vendoo.ge/media/wysiwyg/22.png" alt="b">
            </div>
            <div class="info-container__list-item">
                <img src="https://vendoo.ge/media/wysiwyg/22.png" alt="c">
            </div>
            <div class="info-container__list-item">
                <img src="https://vendoo.ge/media/wysiwyg/4_1.png" alt="d">
            </div>

        </div>

        </div>

    </div>
</template>

<script>
export default {

    name: 'infoContainer',
    props: {
        msg: String
    }
}

</script>