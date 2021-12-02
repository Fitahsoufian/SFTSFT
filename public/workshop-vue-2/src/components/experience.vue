<template>
    <div class="container-fluid">
        <div class="row" data-aos="flip-up">
            <div class="col centertext about">EXPERIENCE</div>
        </div>
        <div class="row" data-aos="flip-up">
            <div class="col centertext aboutdesc">PROFESSIONAL AND ACADEMIC</div>
        </div>
        <div class="row d-flex justify-content-center" data-aos="flip-up">
            <div class="col-md-3 border2 centertext"></div>
        </div>
        <div class="row">
            <div class="col-lg-6 edu">
                <span>EDUCATION</span>
                <p class="err">From september 2017  </p>
                <p>Bachelor in Economics Science</p>
                <p class="min">Lycée Allal EL Fassi</p>
                 <p class="err">2017-2020</p>
                <p>Economics University</p>
                <p class="min">3 Years of studies in university of economics .</p>
                <p class="err">2020-2022</p>
                <p>Web Developer</p>
                <p class="min">YouCode by Simplon.co</p>
               
            </div>
            <div class="col-lg-6 exp">
                PROFESSIONAL
                <p class="err">2021</p>
                <p>Traineeship in a web agency </p>
                <p class="min"> Internship that allows me to learn a lot of skills in developping a web site</p>
                
            </div>
        </div>
    </div>
</template>

<style scoped>
    *{
        color:#fff;
    }
    .container-fluid{
        min-height: 100vh;
        background: black;
        padding-bottom: 45px;
    }
    .border2{
        border-bottom:1px solid #fff;
        margin-bottom: 40px;
    }
    .about{
        font-size: 40px;
        font-weight: 600;
        margin-top: 45px;
    }
    .centertext{
        text-align:center;
    }
    .aboutdesc{
        font-size:14px;
        margin-bottom: 15px;
    }
    .edu{
        border-right:1px solid #fff;
        text-align: right;
    }
    .exp{
        border-left:1px solid #fff;
        text-align: left;
    }
    .edu, .exp{
        font-weight: 700;
    }
    .min{
        font-weight: 400;
        font-size: 14px;
    }
    .err{
        color:#d3dcdf;
        margin-top: 20px;
        margin-bottom:3px;
            font-size: 14px;
    }
    p{
        margin:0;
    }
    span{
        font-size: 17px;
    }
    @media only screen and (max-width: 992px) {
        .exp,.edu{
            text-align: center;
        }
    }
</style>