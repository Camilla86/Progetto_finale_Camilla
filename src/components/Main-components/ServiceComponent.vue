<template>
    <div>
        <section id="advantages-list">
        <div class="container">
            <div class="row">
                <div class="col-md-3">
                    <div class="process-wrapp">
                        <span class="pro-step blue"><i aria-hidden="true" class="fas fa-folder-open"></i></span>
                        <h4 class="service-heading">World leader in consulting and finance</h4>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="process-wrapp">
                        <span class="pro-step midnight"><i aria-hidden="true" class="fas fa-code"></i></span>
                        <h4 class="service-heading">A focused team with a specialized skill</h4>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="process-wrapp">
                        <span class="pro-step purple"><i aria-hidden="true" class="fas fa-cog"></i></span>
                        <h4 class="service-heading">Trusted and professional advisors for you</h4>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="process-wrapp">
                        <span class="pro-step pink"><i aria-hidden="true" class="fas fa-edit"></i></span>
                        <h4 class="service-heading">Experience to give you a better results</h4>
                    </div>
                </div>
            </div>
        </div>
    </section>
    </div>
    </template>
    
    <script>
    export default {
        name:'ServiceComponent',
    }
    </script>
    
    <style scoped>
    #advantages-list {
    padding: 80px 180px;
}


.process-wrapp {
    text-align: center;
    cursor: pointer;
}

.process-wrapp > .service-heading{
    font-size: 17px;
    line-height: 1.5;
    font-weight: 400;
    margin-top: 20px;
}

.process-wrapp > .pro-step {
    position: relative;
    z-index: 1;
}

.process-wrapp > .pro-step {
    display: inline-block;
    height: 90px;
    width: 90px;
    line-height: 90px;
    font-size: 28px;
    font-weight: 600;
    color: #fff;
    text-align: center;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    -webkit-transition: all .3s ease;
    -o-transition: all .3s ease;
    transition: all .3s ease;
}

.process-wrapp:hover > .pro-step::before {
    content: "";
    background: transparent;
    top: 1px;
    left: 1px;
    bottom: 1px;
    right: 1px;
    position: absolute;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    border: 4px solid #fff;
    -webkit-transition: all .3s ease-in-out;
    -moz-transition: all .3s ease-in-out;
    -ms-transition: all .3s ease-in-out;
    -o-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out;
}


.process-wrapp > .pro-step.blue{
    background: #03a9f5;
}

.process-wrapp:hover .pro-step.blue{
    -webkit-animation: itg_pulse_blue 1s infinite;
    -o-animation: itg_pulse_blue 1s infinite;
    animation: itg_pulse_blue 1s infinite;
    -webkit-box-shadow:0 0 0 0 rgb(0, 188, 212);
    box-shadow:0 0 0 0 rgb(0, 188, 212);
}

.process-wrapp > .pro-step.midnight{
    background: #41526b;
}

.process-wrapp:hover .pro-step.midnight{
    -webkit-animation: itg_pulse_midnight 1s infinite;
    -o-animation: itg_pulse_midnight 1s infinite;
    animation: itg_pulse_midnight 1s infinite;
    -webkit-box-shadow:0 0 0 0 rgb(65, 82, 107);
    box-shadow:0 0 0 0 rgb(65, 82, 107);
}

.process-wrapp > .pro-step.purple{
    background: #9556f5;
}
.process-wrapp:hover .pro-step.purple{
    -webkit-animation: itg_pulse_purple 1s infinite;
    -o-animation: itg_pulse_purple 1s infinite;
    animation: itg_pulse_purple 1s infinite;
    -webkit-box-shadow:0 0 0 0 rgb(149, 86, 245);
    box-shadow:0 0 0 0 rgb(149, 86, 245);
}

.process-wrapp > .pro-step.pink{
    background: #f021b6;
}

.process-wrapp:hover .pro-step.pink{
    -webkit-animation: itg_pulse_pink 1s infinite;
    -o-animation: itg_pulse_pink 1s infinite;
    animation: itg_pulse_pink 1s infinite;
    -webkit-box-shadow:0 0 0 0 rgb(240, 33, 182);
    box-shadow:0 0 0 0 rgb(240, 33, 182);
}
    </style>