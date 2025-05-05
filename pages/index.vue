<template>

    <div class="hero">

        <div class="text">
            <h1>Vaš oglas</h1>
            <h1>u pravo vrijeme.</h1>
            <h2 class="subtext">Na ulici ili online - pomažemo Vam biti viđeni i zapamćeni</h2>
        </div>
        <Button>Saznaj više!</Button>

    </div>
    <div class="w-card">
        <div class="why-us-content">
            <h2 class="sec-title">ZAŠTO ODABRATI SCOPE?</h2>
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
            <h2 class="sec-title">NAŠE USLUGE</h2>
            <h3 class="main-title">Web. Marketing. Billboards.<br>Jedan tok.</h3>
            <div class="cards">
                <Card number="01" title="Izrada web stranica"
                    description="Brze, funkcionalne i dizajnerski čiste web stranice koje prodaju." />
                <Card number="02" title="Digitalni marketing"
                    description="Kampanje koje pogađaju pravu publiku. Bez suvišnih klikova." />
                <Card number="03" title="Optimizacija za tražilice"
                    description="Budi pronađen kad te trebaju. I kad ne znaju da te trebaju." />
                <Card number="04" title="Oglašavanje billboardom"
                    description="Tvoja priča na ulicama. Veliko platno, prava publika, pravi trenutak." />
            </div>

        </div>

    </div>

    <div class="cta">
        <div class="cta-title">
            <h1 class="main-title">Sve povezano. Sve u pokretu.<br>Sve za tvoj rast.</h1>
        </div>
        <Button>Javi nam se!</Button>


    </div>
    <div class="process">
        <h2 class="sec-title">PROCES RADA</h2>
        <h3 class="main-title">Od ideje do rezultata.</h3>
        <div class="timeline">
            <div class="timeline-line"></div>
            <div class="timeline-item left">
                <div class="content">
                    <h3>Uvodni razgovor</h3>
                    <p>Sve počinje s vama. Upoznajemo vašu priču, ciljeve i publiku kroz kratki brief ili sastanak.</p>
                </div>
                <div class="circle">1</div>
            </div>

            <div class="timeline-item right">
                <div class="circle">2</div>
                <div class="content">
                    <h3>Analiza tržišta i potreba</h3>
                    <p>Zaranjamo u podatke i istraživanje tržišta kako bismo razumjeli vaše okruženje, konkurenciju i
                        prilike.</p>
                </div>
            </div>

            <div class="timeline-item left">
                <div class="content">
                    <h3>Razrada strategije i koncepta</h3>
                    <p>Na temelju analize gradimo jasnu i prilagođenu strategiju koja vodi prema vašim ciljevima – bez
                        šablona.</p>
                </div>
                <div class="circle">3</div>
            </div>

            <div class="timeline-item right">
                <div class="circle">4</div>
                <div class="content">
                    <h3>Izvedba i realizacija</h3>
                    <p>Ideje prenosimo u akciju. Pokrećemo kampanje, izrađujemo sadržaje i aktiviramo oglašavanje –
                        online
                        ili offline.</p>
                </div>
            </div>

            <div class="timeline-item left">
                <div class="content">
                    <h3>Praćenje i izvještavanje</h3>
                    <p>Pratimo performanse u stvarnom vremenu, optimiziramo kad treba i redovno vam šaljemo jasne i
                        razumljive izvještaje.</p>
                </div>
                <div class="circle">5</div>
            </div>

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
    height: 100vh;
}

.text {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-size: 2.8rem;
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

.w-card {
    display: flex;

    border-radius: 40px;
    background-color: #e8e9e3;
    width: 100%;
    height: 90vh;
    color: #202020;
    flex-direction: column;
    align-items: left;
    padding: 100px;

}


.sec-title {
    margin-bottom: 40px;
    font-size: 1rem;
    font-family: 'Roboto', sans-serif;
    color: #B22222;
}

.main-title {

    margin-bottom: 40px;
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
    margin-top: 80px;
    padding: 0 20px;
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

/*WHY US*/


.services {
    padding: 100px;
    display: flex;
    width: 100%;
    height: 100vh;
    flex-direction: column;
    align-items: left;
}

.cards {
    display: flex;
    gap: 5px;
    justify-content: center;
}

.cta {
    height: 50vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.process{
    padding: 100px;
}


.timeline {
    position: relative;
    padding: 100px 0;
    max-width: 1000px;
    margin: 0 auto;
}

.timeline-line {
    position: absolute;
    top: calc(18% - 20px);
    bottom: calc(18% - 20px);
    left: 50%;
    width: 2px;
    background-color: #e8e9e3;
    transform: translateX(-50%);
    z-index: 0;
}

.timeline::before {
    content: "";
    position: absolute;
    top: 0;
    bottom: 0;
    left: 50%;
    width: 2px;
    transform: translateX(-50%);
}

.timeline-item {
    position: relative;
    width: 50%;
    padding: 40px;
    box-sizing: border-box;
}

.timeline-item.left {
    left: 0;
    text-align: right;
}

.timeline-item.right {
    left: 50%;
    text-align: left;
}

.timeline-item .content {
    background-color: transparent;
    color: #e8e9e3;
    padding: 20px;
    border-radius: 8px;
    position: relative;
    z-index: 2;
}

.timeline-item h3 {
    font-size: 1.5rem;
    font-weight: 600;
}

.timeline-item p {
    margin-top: 10px;
    font-size: 1.1rem;
    color: #cccccc;
}

.circle {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 40px;
    height: 40px;
    border-radius: 50%;
    border: 2px solid #e8e9e3;
    background-color: #202020;
    color: #e8e9e3;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: bold;
    line-height: 1;

}

.timeline-item.left .circle {
    right: -20px;
}

.timeline-item.right .circle {
    left: -20px;
}


</style>