<template>
    <div>
        <section class="section">
            <div class="container-fliud">
                <img alt="Guilherme Staffen" class="rounded-circle" id="imgCircle" src="../assets/guilherme.jpeg">
                <h1>Guilherme Staffen</h1>
                <p>Software Quality Assurance Analyst at <a href="https://www.testingcompany.com.br/" target="_blank">Testing Company</a></p>
            </div>
            <div class="container-fliud">
                <p>Scroll to more</p>
            </div>
        </section>

        <!-- portfolio section -->
        <section class="protfolio">
            <h1>Employment History</h1>
            <p></p>
            <div class="container">
                <div class="row">

                    <div class="col-md-4">
                            <div class="card">
                                <div class="card-head">
                                    <img alt="Vue logo" class="rounded-circle img-custome" src="../assets/logoTC.png">
                                    <h3>QA Analyst</h3>
                                    <h4>Testing Company</h4>
                                </div>
                                <hr>
                                <div class="card-body">
                                    <p><strong>Jul/2020</strong> - <strong>Present</strong></p>
                                    <p>
                                        I am responsible for analyzing, planning and developing automated tests for different applications from different companies.
                                    </p>
                                   
                                </div>
                            </div>
                            <br>
                    </div>

                    <div class="col-md-4">
                            <div class="card">
                                <div class="card-head">
                                    <img alt="Vue logo" class="rounded-circle img-custome" src="../assets/logoAlo.png">
                                    <h3>Technical Support</h3>
                                    <h4>Alô Automação</h4>
                                </div>
                                <hr>
                                <div class="card-body">
                                    <p><strong>Feb/2018</strong> - <strong>Jul/2020</strong></p>
                                    <p>
                                       In this position I was responsible for providing technical support, remote or in person, for the SfheraERP, SfheraPDV and Ristore systems.
                                    </p>
                                    
                                </div>
                            </div>
                        <br>
                    </div>  

                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-head">
                                <img alt="NBCarnes logo" class="rounded-circle img-custome" src="../assets/logoNB.png">
                                <h3>Web Developer</h3>
                                <h4>NB Carnes</h4>
                            </div>
                            <hr>
                            <div class="card-body">
                                <p><strong>Nov/2019</strong> - <strong>Jan/2020</strong></p>
                                <p>
                                    Web development of a system for automation and control of orders, deliveries, payments, receipts and commissions.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
    </div>
</template>


<style lang="css" scoped>
    .section{
        padding-top: 10%;
        padding-bottom: 20%;
        background-color: #314149;
    }

    .protfolio{
        background-color: #1b262c;
        padding-top: 8%;
        padding-bottom: 15%;
        /* padding:15% */
    }

    .protfolio h1{
        color: #D8E3E7;
    }

    .protfolio .card{
        background-color: #314149;
        color: #D8E3E7;
    }

    .img-custome{
        width: 140px;
        height: 140px;
        margin-top: 15px;
    }

    #imgCircle{
        max-width: 300px;
        max-height: 300px;
    }
</style>