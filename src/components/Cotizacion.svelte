<script>
    import '$lib/styles/Cotizacion.css'
</script>

<div class="cotizacion_container">
    <h1>Solicita tu cotización</h1>
    <form action="">
        <div>
            <label for="">Nombre:</label>
            <input name="name" class="cotizacion_form_box" type="text" placeholder="Nombre completo" required>
        </div>
        <div>
            <label for="">Empresa:</label>
            <input name="company" class="cotizacion_form_box" type="text" placeholder="Nombre de tu empresa" required>
        </div>
        <div>
            <label for="">Email:</label>
            <input name="email" class="cotizacion_form_box" type="email" placeholder="Email de contacto" required>
        </div>
        <div>
            <label for="">Teléfono:</label>
            <input name="tel" class="cotizacion_form_box" type="tel" placeholder="Teléfono de contacto" required>
        </div>
        <div>
            <label for="">Marca solicitada:</label>
            <select class="cotizacion_form_box" name="brand" id="" required>
                <option value="datalogic">Datalogic</option>
                <option value="festo">Festo</option>
                <option value="others">Otra</option>
            </select>
        </div>
        <div>
            <label for="">Mensaje:</label>
            <textarea name="message" class="cotizacion_form_box" rows="4" placeholder="Escribe aquí el modelo, número de parte o una descripción del producto que estás buscando..." required></textarea>
        </div>
        <input type="submit" class="btn-form-submit" value="Enviar">
    </form>
</div>