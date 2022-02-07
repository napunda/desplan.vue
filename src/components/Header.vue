<template>
<header>
        <nav class="navegacao">
            <a class="logo" href="">
                <img class="logo_png" src="../assets/header/logo.png" alt="logo">
            </a>
            <ul class="nav-lista">
                
                
                <li><a href=""><img src="../assets/header/facebook-f-brands.svg" alt="fb-logo" class="icon"></a></li>
                <li><a href=""><img src="../assets/header/instagram-brands.svg" alt="insta-logo" class="icon"></a></li>                
                <li><div class="spacer"></div></li>
                <li><a href="index.html">Sobre</a></li>
                <li><a href="index.html">Serviço</a></li>
                <li><a href="index.html">Galeria</a></li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Righteous&display=swap');
.navegacao {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1rem 5rem 1rem 5rem;
    background:#fff;

}
.nav-lista {
    list-style: none;
    display: flex;
    align-items: center;
    
}
.nav-lista a {
    text-decoration: none;
    font-family: Montserrat;
    font-style: normal;
    font-weight: bold;
    font-size: 16px;
    line-height: 20px;
    color: #3D3735;
    transition: 0.3s;
}

a:hover {
    opacity: 0.8;
}
.spacer {
    width: 1px;
    height: 24px;
    background-color: #3D3735;
}
.nav-lista li {
    padding-left: 2.5rem;
}
.icon {
    height: 25px;
    color: #3D3735;
}

</style>