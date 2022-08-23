<template>
    <div class="footer">
        <h5>Rendi Purwito Armin</h5>
        <p>rendipurwito@gmail.com | +6281297096073 | Jl. Tunas Karsa No.56</p>
        <hr>
        <div class="f-icon">
            <button type="button" class="btn btn-light">
                <i class="fa-brands fa-facebook-f"></i>
            </button>

            <button type="button" class="btn btn-light">
                <i class="fa-brands fa-instagram"></i>
            </button>

            <button type="button" class="btn btn-light">
                <i class="fa-brands fa-twitter"></i>
            </button>

            <button type="button" class="btn btn-light">
                <i class="fa-brands fa-linkedin-in"></i>
            </button>

            <button type="button" class="btn btn-light">
                <i class="fa-brands fa-github"></i>
            </button>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Footer",
    };
</script>

<style>
    .footer {
        background-color: #0062bd;
        text-align: center;
        color: white;
        padding-top: 15px;
        padding-bottom: 15px;
        line-height: 10px;
    }

    .footer hr {
        margin: 15px 100px;
    }

    .f-icon {
        display: flex;
        justify-content: center;
        gap: 15px;
        font-size: 20px;
    }

    .f-icon button{
        border-radius: 50%;
        width: 40px;
    }
</style>