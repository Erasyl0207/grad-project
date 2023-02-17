<template>
    <div class="container">
        <div class="taste">
            <h2 class="fz100-400">Taste the authentic Saudi cuisine</h2>
            <p class="fz23-400">Among the best Saudi chefs in the world,  <br> serving you something beyond flavor. </p>
            <button class="button">Our Menu</button>
        </div>
        <div class="culture">
            <img src="@/assets/image/second1.png" alt="">
            <div class="culture-right">
                <h3 class="fz70-400">A distinctive dining destination inspired by the culture.</h3>
                <p class="fz23-400">Experience Al Balad old town of Jeddah vibes.</p>
                <button class="button">Our Venue</button>
                <div class="images">
                    <img src="@/assets/image/second2.png" alt="">
                    <img src="@/assets/image/second3.png" alt="">
                    <img src="@/assets/image/second4.png" alt="">
                </div>
            </div>
        </div>
        <div class="review">
            <img src="@/assets/image/Quote.svg" alt="">
        </div>
        <div class="menu">
            <h2 class="fz70-400">A unique menu that reflects the <br> true essence of the Saudi cuisine</h2>
            <button class="button">Our Menu</button>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .taste {
        background-image: url('@/assets/image/main.png');
        background-repeat: no-repeat;
        background-position: right;
        background-position-y:  100%;
        margin-bottom: 100px;
        h2 {
            width: 70%;
        }
        p {
            margin: 40px 0;
        }
    }
    .culture {
        display: flex;
        justify-content: space-between;
        padding: 100px 0;
        &-right {
            margin-left: 50px;
            p {
                padding: 30px 0;
            }
            .images {
                margin-top: 50px;
                display: flex;
                justify-content: space-between;
                img {
                    transition: 0.6s;
                    &:hover {
                        transform: scale(1.2);
                        transition: 0.6s;
                    }
                }
            }
        }
    }
    .review {
        padding: 100px 0;
        img {
            width: 100%;
        }
    }
    .menu {
        padding: 100px 0;
        background-image: url('@/assets/image/unique-menu.png');
        h2 {
            text-align: center;
            padding-bottom: 40px;
        }
        button {
            display: flex;
            justify-content: center;
            margin: 0 auto;
        }
    }
</style>