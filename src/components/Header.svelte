<script>
    import '$lib/styles/Header.css'
    import LogoRdq from '$lib/images/lrdq.png'

    var clicked = false;
    const handleClick = () => {
        clicked = !clicked;
    }
</script>

<header id="header" class="header_container">
    <div class="logo_container">
        <a href="/">
            <img src={LogoRdq} alt="Logo RDQ">
        </a>
    </div>
    <div class="bars-icon_container">
        <button on:click={handleClick} class="btn-menu">
            <svg id="menuBars" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-list icon-bars" viewBox="0 0 16 16">
                <path fill-rule="evenodd" d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z"/>
            </svg>
        </button>
    </div>
    <div class={clicked ? 'menu_container-active' : 'menu_container'}>
        <ul class="menu_list">
            <li class="menu_item"><a class="menu_link" href="/">Home</a></li>
            <li class="menu_item">Nuestras marcas</li>
                <ul class="menu_list">
                    <li class="menu_item item_marca"><a class="menu_link" href="#festo">Festo Electric Automation</a></li>
                    <li class="menu_item item_marca"><a class="menu_link" href="#datalogic">Datalogic</a></li>
                </ul>
            <li class="menu_item"><a class="menu_link" href="#servicios">Servicios</a></li>
            <li class="menu_item"><a class="menu_link" href="#contacto">Contacto</a></li>
            <li class="menu_item btn_quote"><a class="menu_link" href="/Cotizacion">Solicita tu cotización</a></li>
        </ul>
    </div>
</header>