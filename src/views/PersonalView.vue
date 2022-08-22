<!-- <script setup>
import Personal from '@/components/Personal.vue'
</script> -->

<template>
    <div class="personal">
        <div class="project-experience">
            <h4>PROJECT EXPERIENCE</h4>
            <hr>

            <div class="b-project-experience">
                <div class="bootstrap">
                <h5>Bootstrap</h5>
                <h6>Replicate Epic Game Website</h6>
                <h6>Food Delivery Landing Page Website</h6>
            </div>

            <div class="php">
                <h5>PHP</h5>
                <h6>Borrowing School Item Website</h6>
            </div>

            <div class="laravel">
                <h5>Laravel</h5>
                <h6>Teacher Agenda Website</h6>
                <h6>School Infrastructure Website</h6>
            </div>
            </div>
        </div>

        <div class="education">
            <h4>EDUCATION</h4>
            <hr>
            <h5>SMK Taruna Bhakti</h5>
            <h6>Computer Engineering</h6>
            <p>2021 - Now</p>
        </div>

        <div class="language">
            <h4>LANGUAGE</h4>
            <hr>
            <h6>Indonesia</h6>
            <h6>English</h6>
        </div>
    </div>
</template>

<style>
    .personal hr {
        margin: 20px 100px;
    }

    .personal h4 {
        color: #0062bd;
        margin-left: 100px;
    }

    .personal h5 {
        margin-left: 100px;
    }

    .personal h6 {
        margin-left: 100px;
    }

    .personal p {
        margin-left: 100px;
    }

    .b-project-experience {
        display: flex;
        flex-wrap: wrap;
        justify-content: left;
    }

    .bootstrap {
        margin-bottom: 30px;
    }

    .php {
        margin-bottom: 30px;
    }

    .laravel {
        margin-bottom: 50px;
    }

    .education {
        margin-bottom: 50px;
    }

    .language {
        margin-bottom: 50px;
    }
</style>