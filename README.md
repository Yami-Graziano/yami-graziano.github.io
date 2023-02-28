<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        * {
          box-sizing: border-box;
        }
        
        .col-1 {width: 20%;}
        .col-2 {width: 5%;}
        .col-3 {width: 75%;}


        .header {
          border: 1px;
          padding: 15px;
        }

        .col-1 {
          float: left;
          padding: 15px;
          border: 1px;
        } 

        .col-3 {
          float: right;
          padding: 15px;
          border: 1px;
        }
        
        </style>
    <title>Marina Velazco CV - Proyecto de Yamila Graziano</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <div class="header">
    <h1>MARINA VELAZCO</h1>

     <p id="demo">Visualizarás los datos</p>

     <button type="button" id="Age">Edad</button>
     <button type="button" id="Mail">Mail</button>
     <button type="button" id="Address">Dirección</button>
     <button type="button" id="Cel">Celular</button>

    <script src="boton.js"></script>

    <!-- Botones de alerta en HTML para no perder la info  
     <button type="button" onclick="alert('25 años')">Edad</button>
     <button type="button" onclick="alert('m.velazco@mail.com')">Mail</button>
     <button type="button" onclick="alert('Thames 1077 - CABA')">Dirección</button>
     <button type="button" onclick="alert('1158569293')">Celular</button>
     -->
    </div>


     <div class="col-1">
     <img src="foto carnet.jpg" width="200" height="200">

     <h3>Estudios</h3>
     <dl>Hotelería, cursado en la Universidad de Morón</dl>

     <h3>Cursos</h3>
      <dl>Asistente Administrativo - Contable</dl>
      <dl>Liquidación de Sueldos</dl>

     <h3>Idiomas</h3>
      <dl>Inglés</dl>
      <dl>Italiano</dl>
      <dl>Portugués</dl>
      <dl>Francés</dl>
     </div>

    <div class="col-3">
     <h2>Experiencia Laboral</h2>
     <p>Central de reservas en Howard Johnson - Desde Enero 2020 hasta Actualidad</p>
     <p>Recepcionista en Sheraton Pilar - Desde Abril 2017 hasta Diciembre 2019</p>
     <p>Camarera en Hyatt - Desde Enero 2016 hasta Marzo 2017</p>
     
     <h2>Conocimientos de computación y sistemas</h2>
     <p>Paquete Microsoft Office</p>
     <p>Sistemas hoteleros: BackPack, Arion, WinPax</p>

     <h4>Hobbie</h4>
     <p>Tejer a crochet</p>

     <iframe width="450" height="300" src="https://www.youtube.com/embed/paI88rXqx84"></iframe>
    </div>

</body>
</html>
