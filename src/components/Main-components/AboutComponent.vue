<template>
    <div>
        <section id="about-us">
        <div class="container mt-5">
            <div class="row">
                <div class="col">
                    <p class="we-are-megaone">We are megaone company</p>
                    <h3>We are making ideas</h3>
                    <h3>better for everyone</h3>
                    <p class="about-us-text">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum.</p>
                    <a href="#" class="btn px-4 mt-4 border-2">Learn More</a>
                </div>
                <div class="col">
                    <img src="@/assets/vector-art-2.png" alt="company foto">
                </div>
            </div>
        </div>
    </section>
    </div>
    </template>
    
    <script>
    export default {
        name: 'AboutComponent',
    }
    </script>
    
    <style scoped>
    #about-us {
    padding: 80px 180px;
}

#about-us h3 {
    font-family: 'Montserrat', sans-serif;
    color: black;
    font-size: 40px;
    position: relative;
}

#about-us p {
    font-family: 'Roboto', sans-serif;

    color: rgb(63, 61, 61);
    line-height: 30px;
}

.we-are-megaone {
    font-weight: 20px;
    font-size: 20px;
}

.about-us-text {
    font-weight:lighter;
}

#about-us a {
    font-family: 'Roboto', sans-serif;
    background-color: #f547d8;
    color: white;
    border-radius: 30px;
}

#about-us a:hover {
    color: white;
}

#about-us img {
    width: 100%;
}
    </style>
    