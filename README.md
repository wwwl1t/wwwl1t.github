<style>
    iframe {
        position: relative;
        width: 100%; /* Ocupa todo el ancho de la pantalla */
        height: 100vh; /* Ocupa toda la altura del navegador */
        opacity: 0.8; /* Transparencia ligera */
        z-index: 2;
        border: none; /* Elimina bordes del iframe */
    }
    div {
        position: absolute;
        top: 50%; /* Centra el botón verticalmente */
        left: 50%; /* Centra el botón horizontalmente */
        transform: translate(-50%, -50%); /* Ajuste para centrar completamente */
        z-index: 1; /* Permite que el iframe reciba clics */
    }
    button {
        font-size: 20px; /* Tamaño del texto del botón */
        font-family: Arial, sans-serif; /* Fuente clara */
        padding: 15px 30px; /* Espaciado interno del botón */
        color: white; /* Texto blanco para contraste */
        background-color: #007bff; /* Fondo azul llamativo */
        border: 2px solid #0056b3; /* Borde azul oscuro */
        border-radius: 10px; /* Bordes redondeados */
        cursor: pointer; /* Cambia el cursor a "mano" al pasar por el botón */
        box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2); /* Sombra para resaltar el botón */
    }
    button:hover {
        background-color: #0056b3; /* Oscurece el fondo al pasar el cursor */
        border-color: #003d7a; /* Cambia el color del borde al pasar el cursor */
    }
</style>
<div>
    <button>Haz clic aquí</button>
</div>
<iframe src="https://www.loveholidays.com/customer/account/"></iframe>
