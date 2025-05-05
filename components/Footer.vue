<template>
    <slot />

    <div class="footer">
        <div class="contact">
            <h3>Kontaktirajte nas!</h3>
            <p>info@scopereklame.com</p>
        </div>
        <div class="nav-bar">
            <div class="logo">
                <img src="/public/icons/scope_black_logo.svg" alt="Scope Logo Black" />
            </div>

            <ul class="nav-bar-links">
                <li>Usluge</li>
                <!-- <li>Billboards</li>-->
                <li>Blog</li>
                <li>O nama</li>
            </ul>

            <div class="back">
                Povratak na početak ↑
            </div>

        </div>

        <div class="rights">
            <p>© 2023 Scope. Sva prava pridržana.</p>
        </div>

    </div>


</template>

<style scoped>
.footer {
    background-color: #e8e9e3;
    border-radius: 40px 40px 0px 0px;
    color: #202020;
    height: 45vh;
}
.contact p{
    margin-top: 10px;
    font-size: 1.8rem;
    color: #202020c0;
}

.contact {
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 2.8rem;
    padding: 100px 0px;
    margin: 20px 100px;

}

.nav-bar {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 20px 100px;
    padding-bottom: 10px;
    border-bottom: 2px solid #202020;

}

.nav-bar-links {
    display: flex;
    gap: 30px;
    list-style: none;
    justify-content: center;
    padding: 0;
    margin: 0;
  }

.logo{
    justify-self: start;
}

.logo img{
    height: 25px;
}

.rights{
    display: flex;
    margin: 20px 100px;

}
</style>