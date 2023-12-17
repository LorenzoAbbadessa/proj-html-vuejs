<script>
let valueD = document.querySelectorAll(".num");
let interval = 5000;

valueD.forEach((valueD) => {
    let startV = 0;
    let endV = parseInt(valueD.getAttribute("data-val"));
    let duration = Math.floor(interval / endV);
    let counter = setInterval(function () {
        startV += 1;
        valueD.textContent = startV;
        if (startV == endV) {
            clearInterval(counter);
        }
    }, duration)
})
</script>
<template>
    <section>
        <div class="container">
            <span class="num" data-val="20">000
            </span>
        </div>
    </section>
</template>
<style scoped>
.num {
    font-size: 2rem;
    padding-left: 3rem;
    padding-right: 3rem;
}

.container {
    display: flex;
    justify-content: center;
}
</style>