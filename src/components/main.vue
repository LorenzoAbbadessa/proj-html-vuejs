<script>






</script>
<template>
    <main>
        <div class="container">
            <div>
                <p>Start Investing in Yourself</p>
                <p>With over 1200 courses in 18 subjects, you're guaranteed to find something that's right for you.</p>
                <button>JOIN FOR FREE</button>
            </div>
            <div class="animation">
                <img src="../../public\assets\img\base.png" alt="#" id="base">
                <img src="../../public\assets\img\book1.png" alt="#" id="book1">
                <img src="../../public\assets\img\book2.png" alt="#" id="book2">
                <img src="../../public\assets\img\bubblespeech.png" alt="#" id="bubblespeech">
                <img src="../../public\assets\img\moon.png" alt="#" id="moon">
            </div>
        </div>
        <div class="cards">
            <div class="card">
                <p>Worldwide Trends</p>
                <p>Our services and collections adhere to cutting-edge solutions in the design world.</p>



            </div>
            <div class="card">
                <p>Worldwide Trends</p>
                <p>Our services and collections adhere to cutting-edge solutions in the design world.</p>



            </div>
            <div class="card">
                <p>Worldwide Trends</p>
                <p>Our services and collections adhere to cutting-edge solutions in the design world.</p>



            </div>
        </div>



        <div class="images">
            <div class="img_one">
                <div class="pic_full">
                    <img src="../../public/assets/img/cat_1-1540x750.jpg" class="one">
                    <div class="text">
                        <p>Software Development</p>
                        <p>4 Courses</p>
                    </div>
                </div>
                <div class="pic">
                    <img src="../../public/assets/img/cat_4-740x310.jpg" class="one">
                    <div class="text">
                        <p>Exercise</p>
                        <p>7 Courses</p>
                    </div>
                </div>
                <div class="pic">
                    <img src="../../public/assets/img/cat_5-740x310.jpg" class="one">
                    <div class="text">
                        <p>Music</p>
                        <p>4 Courses</p>
                    </div>
                </div>

            </div>
            <div class="img_two">
                <div class="pic_full">
                    <img src="../../public/assets/img/cat_2-740x310.jpg" class="one">
                    <div class="text">
                        <p>Art</p>
                        <p>8 Courses</p>
                    </div>

                </div>
                <div class="pic_full">
                    <img src="../../public/assets/img/cat_3-740x310.jpg" class="one">
                    <div class="text">
                        <p>Material Design</p>
                        <p>4 Courses</p>
                    </div>
                </div>
                <div class="pic_full">
                    <img src="../../public/assets/img/cat_6-740x310.jpg" class="one">
                    <div class="text">
                        <p>Photography</p>
                        <p>4 Courses</p>
                    </div>
                </div>
            </div>
        </div>


    </main>
</template>
<style scoped>
* {
    box-sizing: border-box;
    margin: 0;
}

main {

    width: 70%;
    margin: auto;
}

.container {
    margin: auto;
    height: 600px;
    width: 100%;
}

.cards {
    display: flex;
    justify-content: space-between;

}

.card {
    background-color: #f2f6fb;
    padding: 20px 20px;
    margin: 0 1rem;

}

.images {
    width: 100%;
    display: flex;
}

.img_one {
    width: 66%;
    display: flex;
    flex-wrap: wrap;
}

.img_two {
    width: 34%;
    display: flex;
    flex-wrap: wrap;
}

.pic_full {
    width: 100%;
    padding: 1rem;
}

.pic {
    width: 50%;
    padding: 1rem;
}

.one {
    width: 100%;
}

.text {
    display: flex;
    justify-content: space-between;
}

.animation {
    position: relative;

}

#base {
    position: absolute;
    left: 600px;
}

#book1 {
    position: absolute;
    left: 970px;
    top: 100px;
}

#book2 {
    position: absolute;
    left: 825px;
    top: 275px;
}

#bubblespeech {
    position: absolute;
    left: 1100px;
    top: 60px;

}

#moon {
    position: absolute;
    left: 705px;
    top: 110px;
}
</style>