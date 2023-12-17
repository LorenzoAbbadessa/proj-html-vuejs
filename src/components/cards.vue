<script>
export default {
    name: "AppCourses",
    data() {
        return {
            art_courses: [{
                title: "Real Things Art Painting by Jason Ni",
                category: "Art",
                price: "$45.99"
            },
            {
                title: "Minimalism, How to make things simpler",
                category: "Art",
                price: "$39.99"
            }
            ],
            material_design_courses: [{
                title: "Graphic Design Basics Masterclass",
                category: "Communication",
                price: "$45.99"

            },
            {
                title: "Correct and Beautiful Design Interaction",
                category: "360 photos",
                price: "$89.99"
            }
            ]

        }
    }
}
</script>




<template>
    <div class="card" v-for="art in art_courses">
        <h1>{{ art.title }}</h1>
        <h1>{{ art.category }}</h1>
        <h1>{{ art.price }}</h1>



    </div>
</template>




<style></style>



