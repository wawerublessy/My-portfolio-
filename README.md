# My-portfolio-
p {
    font-size: 20px;
    color: #fff;
    text-shadow: 0 0 8px #fff, 0 0 16px #00f, 0 0 2px #fff;
}
/* Add gap between social icons */
.social-links {
    gap: 44px !important;
}
/* Social icon glow effect */
.social-icon svg {
    filter: drop-shadow(0 0 8px #00f);
    animation: rgb-glow-icon 3s linear infinite;
    transition: filter 0.2s;
}

@keyframes rgb-glow-icon {
    0% {
        filter: drop-shadow(0 0 8px #00f);
    }
    25% {
        filter: drop-shadow(0 0 8px #0f0);
    }
    50% {
        filter: drop-shadow(0 0 8px #f00);
    }
    75% {
        filter: drop-shadow(0 0 8px #fff);
    }
    100% {
        filter: drop-shadow(0 0 8px #00f);
    }
}
/* Fixed and cleaned up navigation and logo styles */
body {
    background: url(public.img/fotis-fotopoulos-SyvsTmuuZyM-unsplash.jpg);
    color: white;
    background-size: cover;
    margin: 0;
    padding: 0;
}

.main {
    width: 100%;
    background: url();
    background-position: center;
    background-size: cover;
    height: 100vh;
    position: relative;
    font-family: sans-serif;
}

.navbar {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 40px 0 40px;
    box-sizing: border-box;
}

.logo {
    height: 70px;
    width: auto;
    max-width: 180px;
    max-height: 70px;
    object-fit: contain;
    border-radius: 50%;
    box-shadow: 0 0 30px 10px #00f;
    animation: rgb-glow 3s linear infinite;
}

@keyframes rgb-glow {
    0% {
        box-shadow: 0 0 30px 10px #00f;
    }
    25% {
        box-shadow: 0 0 30px 10px #0f0;
    }
    50% {
        box-shadow: 0 0 30px 10px #f00;
    }
    75% {
        box-shadow: 0 0 30px 10px #fff;
    }
    100% {
        box-shadow: 0 0 30px 10px #00f;
    }
}

ul {
    list-style: none;
    display: flex;
    gap: 8px;
    margin: 0;
    padding: 0;
    align-items: center;
    justify-content: flex-end;
}

ul li {
    display: flex;
    align-items: center;
}

ul li a {
    color: white;
    text-decoration: none;
    font-size: 15px;
    padding: 0px 13px;
    transition: color 0.2s;
}

ul li a:hover {
    color: orangered;
}

span {
    color: orangered;
}

a {
    text-decoration: underline;
}

h1{
    color: #fff;
    text-shadow: 0 0 8px #fff, 0 0 16px #00f, 0 0 2px #fff;
}

.copyright {
    display: block;
    text-align: center;
    color: #fff;
    font-size: 14px;
    margin-top: 32px;
    margin-bottom: 16px;
    opacity: 0.7;
}
