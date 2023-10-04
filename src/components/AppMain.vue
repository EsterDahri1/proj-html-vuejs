<script>
export default {
    name: 'AppMain',
}
</script>

<template>
    <div id="jumbotron">
        <div class="container d-flex align-items-center justify-content-center">
            <div class="todayPick">
                <button class="btn text-uppercase text-white">Today's picks</button>
                <h1 class="pt-3">
                    <a href="#" class="text-decoration-none">
                        Food Corner: Top Japanese Restaurants for Sushi
                    </a>
                </h1>
                <p class="text-center pt-3">
                    March 25, 2019
                </p>
            </div>
        </div>
    </div>
    <section id="journal">

    </section>
    <section id="popRecipes">

    </section>
    <section id="collection">

    </section>
    <section id="blog">

    </section>
    <section id="subscription">

    </section>
    <div id="banner">

    </div>
</template>

<style lang="scss">
@use '../assets/scss/partials/variables' as *;

#jumbotron {
    height: 615px;
    background-image: url(https://avada.website/food/wp-content/uploads/sites/118/2019/02/slide1-bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: 10%;

    .container {
        padding-top: 150px;

        .todayPick {
            background-color: white;
            height: 223px;
            width: 50%;
            border-radius: 12px;
            color: #67615a;
            display: flex;
            flex-direction: column;
            font-size: 17px;
            justify-content: center;
            letter-spacing: 0.2px;
            line-height: 30.6px;
            margin: auto;
            padding: 20px 0px 12px;
            position: relative;

            .btn {
                background-color: $food_warning;
                border-radius: 5px;
                position: absolute;
                bottom: 90%;
                left: 40%;
                font-size: 14px;
                font-weight: 400;
                padding: 10px 20px;
            }

            h1 {
                font-family: 'Vidaloka';
                font-size: 45px;
                letter-spacing: -0.675px;
                text-align: center;

                a {
                    color: $food_dark;
                }

                a:hover {
                    color: $food_warning;
                }
            }


        }
    }
}
</style>