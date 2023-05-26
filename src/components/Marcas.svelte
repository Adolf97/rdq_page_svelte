<script>
    import '$lib/styles/Marcas.css'
    import LogoDatalogic from '$lib/images/data.png'
    import LogoFesto from '$lib/images/fes.png'
</script>

<div class="marcas_container">
    <div class="marcas-info_container">
        <h2>Equipos y productos de múltiples marcas</h2>
        <span>En RDQ somos distribuidores autorizados de las marcas <b class="b-datalogic">Datalogic</b> y <b class="b-festo">Festo Electric Automation</b>, sin embargo hemos trabajado con distintas marcas del sector, como Siemens, Cognex, Balluff, Phoenix Contact, etc.</span>
        <h3>Distribuciones Autorizadas</h3>
        <div class="marca-info_container">
            <img class="img-logoData" src={LogoDatalogic} alt="Logo RDQ">
            <ul>
                <li>Equipos de Trazabilidad</li>
                <li>Equipos de sensado</li>
                <li>Sistemas de visión</li>
                <li>Equipos de marcado láser</li>
                <li>Equipos de seguridad</li>
            </ul>
            <a href="#Productos/Datalogic" class="btn-vino">Ver todos los prodcutos ></a>
        </div>
        <div class="marca-info_container">
            <img class="img-logoFesto" src={LogoFesto} alt="Logo Festo">
            <ul>
                <li>Servomotores</li>
                <li>Actuadores</li>
                <li>Válvulas y terminales de válvulas</li>
                <li>Motion Terminals</li>
            </ul>
            <a href="#Productos/Festo" class="btn-vino">Ver todos los productos ></a>
        </div>
    </div>
    <button class="btn_quote">Solicita tu cotización</button>
</div>