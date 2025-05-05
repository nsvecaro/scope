<template>

    <div class="hero">

        <div class="text">
            <h1>Vaš oglas</h1>
            <h1>u pravo vrijeme.</h1>
            <h2 class="subtext">Na ulici ili online - pomažemo Vam biti viđeni i zapamćeni</h2>
        </div>
        <Button>Saznaj više!</Button>

    </div>
    <div class="why-us">
        <div class="why-us-content">
            <h1 class="sec-title">ZAŠTO ODABRATI SCOPE?</h1>
            <h3 class="main-title">Jednostavan početak,<br>briljantni rezultati</h3>
            <h2 class="paragraph">Scope je digitalna marketing agencija koja se specijalizira za<br>web razvoj,
                SEO, društvene mreže i ostale digitalne strategije,<br>pomažući trvrtkama da
                unaprijede svoj online poslovni uspjeh.</h2>

            <div class="why-us-benefits">
                <div class="benefit">
                    <h3>Brza i jednostavna suradnja</h3>
                    <p>Jednostavan početak, bez nepotrebne papirologije i gubljenja vremena. Fokusiramo se na ono što je
                        važno - online ili offline.</p>
                </div>
                <div class="line"></div>
                <div class="benefit">
                    <h3>Stručnost u digitalnom i DOOH oglašavanju</h3>
                    <p>Bez obzira ciljate li publiku online ili na ulici, naš tim zna kako vašu poruku postaviti pred
                        prave ljude.</p>
                </div>
                <div class="line"></div>
                <div class="benefit">
                    <h3>Pristup vođen podacima</h3>
                    <p>Svaku kampanju gradimo na analizi i realnim podacima, ne na nagađanju. Znamo što funkcionira - i
                        zašto.</p>
                </div>
            </div>
        </div>
    </div>


    <div class="services">
        <div class="services-content">
            <h1 class="sec-title">NAŠE USLUGE</h1>
            <h3 class="main-title">Web. Marketing. Billboards.<br>Jedan tok.</h3>
            
        </div>

    </div>

</template>

<style scoped>
/* HERO*/
.hero {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    color: #e8e9e3;
    height: 80vh;
}

.text {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    font-size: xx-large;

    padding: 50px;
}

.subtext {
    font-size: medium;
    color: #e8e9e3;
    font-weight: 400;
    margin-top: 10px;
}

/* HERO*/
/*WHY US*/

.why-us {
    display: flex;

    border-radius: 40px;
    background-color: #e8e9e3;
    width: 100%;
    height: 100vh;
    color: #202020;
    flex-direction: column;
    align-items: left;

}

.why-us-content {
    padding: 100px;

}

.sec-title {


    margin-bottom: 50px;
    font-size: medium;
    font-family: 'Roboto', sans-serif;
    color: #B22222;
}

.main-title {

    margin-bottom: 100px;
    font-size: 4rem;
    font-weight: 600;

}

.paragraph {
    color: #202020aa;
    font-size: 1.5rem;
    font-weight: 450;
}

.why-us-benefits {
    display: flex;
    justify-content: space-between;
    gap: 40px;
    margin-top: 100px;
    padding: 0 40px;
    flex-wrap: wrap;
}

.benefit {
    flex: 1;
    min-width: 250px;
    max-width: 300px;
}

.benefit h3 {
    font-size: 1.5rem;
    font-weight: 600;
    min-height: 50px;
}

.benefit p {
    margin-top: 30px;
    color: #444;
    font-size: 1.2rem;
    line-height: 1.5;
}

.line {
    height: auto;
    width: 2px;
    background-color: #20202039;
}


.services {
    padding: 100px;
    display: flex;
    width: 100%;
    height: 100vh;
    flex-direction: column;
    align-items: left;
}


</style>