
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RETO 1 TAREA 2</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            text-align: center;
            padding: 20px;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
            display: inline-block;
            margin-bottom: 20px;
            width: 80%;
            max-width: 900px;
        }
        h1 {
            font-size: 36px;
            color: #2C3E50;
        }
        h2, h3 {
            color: #34495E;
        }
        button {
            background-color: #3498db;
            color: white;
            padding: 15px 30px;
            font-size: 18px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            margin: 10px;
            display: inline-block;
        }
        button:hover {
            background-color: #2980b9;
        }
        .info-content {
            margin-top: 20px;
            background-color: #ecf0f1;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        ul {
            text-align: left;
            list-style-type: square;
            padding-left: 20px;
        }
        li {
            margin: 10px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        th, td {
            padding: 8px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        th {
            background-color: #3498db;
            color: white;
        }
    </style>
</head>
<body>

    <h1>RETO 1 TAREA 2</h1>

    <!-- Botones para saltar directamente a cada sección -->
    <div>
        <button onclick="location.href='#seccion1'">Listado de Empleos para Erika</button>
        <button onclick="location.href='#seccion2'">Perfil Profesional de Erika</button>
        <button onclick="location.href='#seccion3'">Plan de Acción para Erika</button>
        <button onclick="location.href='#seccion4'">Perfil de Empleo de Erika</button>
        <button onclick="location.href='#seccion5'">Datos sobre el Estado de Salud o la Discapacidad</button>
        <button onclick="location.href='#seccion6'">Prestaciones</button>
        <button onclick="location.href='#seccion7'">Historial Laboral</button>
        <button onclick="location.href='#seccion8'">Aficiones e Intereses</button>
        <button onclick="location.href='#seccion9'">Habilidades Sociolaborales</button>
        <button onclick="location.href='#seccion10'">Aspiraciones Laborales</button>
    </div>

    <div id="seccion1" class="info-content">
        <div class="container">
            <h2>1. Listado de cinco empleos que Erika podría realizar</h2>
            <ul>
                <li>Recepcionista en una oficina o centro de atención al público</li>
                <li>Auxiliar de atención al cliente o en una tienda</li>
                <li>Actriz o asistente en un grupo de teatro o actividades culturales</li>
                <li>Asistente en eventos o actividades organizadas</li>
                <li>Guía turístico o animadora de actividades turísticas</li>
            </ul>
        </div>
    </div>

    <div id="seccion2" class="info-content">
        <div class="container">
            <h2>2.Perfil Profesional de Erika</h2>
            <h3>Datos Personales</h3>
            <p><strong>Nombre:</strong> Erika</p>
            <p><strong>Edad:</strong> 23 años</p>
            <p><strong>Diagnóstico:</strong> Síndrome de Down, discapacidad intelectual 40%</p>

            <h3>Habilidades Personales</h3>
            <ul>
                <li>Trata bien a la gente y le gusta interactuar con el público</li>
                <li>Le gusta el teatro y la actuación</li>
                <li>Tiene capacidad de trabajar en un entorno comunicativo y social</li>
                <li>Tiene buenas capacidades para la recepción de información y organizarse en el entorno laboral</li>
            </ul>

            <h3>Preferencias Laborales</h3>
            <ul>
                <li>Prefiere un trabajo donde pueda interactuar con personas</li>
                <li>No le gustan las tareas manuales ya que se cansa rápido</li>
                <li>Se siente cómoda al trabajar por la mañana</li>
                <li>Le gustaría ir de forma independiente al trabajo en autobús</li>
            </ul>

            <h3>Experiencia Laboral</h3>
            <p><strong>Recepcionista</strong> en un programa de inserción administrativa, se divirtió y le gusta estar hablando con el público.</p>

            <h3>Formación</h3>
            <ul>
                <li>Educación especial hasta los 18 años</li>
                <li>Participó en programas de inserción laboral</li>
            </ul>

            <h3>Objetivos a Corto Plazo</h3>
            <ul>
                <li>Conseguir un empleo donde pueda interactuar con el público</li>
                <li>Aprender a desplazarse al trabajo de forma autónoma</li>
            </ul>
        </div>
    </div>

    <div id="seccion3" class="info-content">
        <div class="container">
            <h2>3.Plan de Acción para Erika</h2>
            <div class="section">
                <h3>Objetivos</h3>
                <ul>
                    <li>Ayudar a encontrar un trabajo a Erika que se ajuste a sus habilidades e intereses.</li>
                    <li>Apoyar su adaptación al trabajo, para que pueda ser más independiente.</li>
                </ul>
            </div>

            <div class="section">
                <h3>Acciones</h3>
                <ul>
                    <li>Acompañarla en su adaptación al trabajo.</li>
                    <li>Entrenarla con sus tareas básicas, como el uso de herramientas y organización del trabajo.</li>
                    <li>Ayudarla a moverse más independientemente y desarrollar sus habilidades sociales.</li>
                </ul>
            </div>

            <div class="section">
                <h3>Recursos</h3>
                <ul>
                    <li>Apoyo de la familia y preparador laboral.</li>
                    <li>Formación según su empleo.</li>
                    <li>Herramientas tecnológicas que le ayuden en sus tareas.</li>
                </ul>
            </div>

            <div class="section">
                <h3>Personal</h3>
                <ul>
                    <li>La guiará su preparador laboral.</li>
                    <li>Le apoyará la familia de Erika.</li>
                    <li>Compañeros y supervisores que le ayuden a integrarse.</li>
                </ul>
            </div>

            <div class="section">
                <h3>Temporalización</h3>
                <ul>
                    <li><strong>Corto plazo (1-3 meses):</strong> Adaptación inicial con un apoyo cercano.</li>
                    <li><strong>Medio plazo (3-6 meses):</strong> Más autonomía en el trabajo.</li>
                    <li><strong>Largo plazo (6-12 meses):</strong> Erika debería ser independiente en su puesto.</li>
                </ul>
            </div>

            <div class="section">
                <h3>Seguimiento</h3>
                <ul>
                    <li>Ver cómo va en su progreso con reuniones regulares.</li>
                    <li>Evaluaciones periódicas de cómo se siente en el trabajo y de sus habilidades.</li>
                    <li>Ajuste del plan según lo necesite.</li>
                </ul>
            </div>
        </div>
    </div>

    <div id="seccion4" class="info-content">
        <div class="container">
            <h2>4.Perfil de Empleo de Erika</h2>
            <div class="section">
                <h3>¿Qué empleo consideras más adecuado para Erika?</h3>
                <p>El empleo más adecuado para Erika es el de recepcionista en una oficina o centro de atención al público. Erika disfruta de trabajar con personas y ya tiene experiencia en recepción. Este puesto le permite interactuar con el público y usar sus habilidades sociales, sin ser un trabajo muy complicado. Podrá adaptarse bien con el apoyo del preparador laboral y con el tiempo. Es un trabajo estructurado que le proporciona estabilidad y oportunidad para desarrollarse poco a poco.</p>
            </div>
        </div>
    </div>

    <div id="seccion5" class="info-content">
        <div class="container">
            <ul>
                <li><strong>Estado de Salud o Discapacidad:</strong> Erika tiene una discapacidad intelectual de 40%, con dificultades cognitivas pero es capaz de trabajar con el apoyo adecuado.</li>
                <li><strong>Impacto sobre el Empleo:</strong> Erika necesitará apoyo al principio para adaptarse al entorno laboral, especialmente en tareas complejas, pero puede realizar tareas sencillas como recepcionista sin apoyo constante.</li>
                <li><strong>Información Complementaria:</strong> La familia de Erika apoya su proceso, pero ella busca ser más independiente. El preparador laboral ayudará en su adaptación al empleo.</li>
            </ul>
        </div>
    </div>

    <div id="seccion6" class="info-content">
        <div class="container">
            <ul>
                <li><strong>Prestación:</strong> [Especificar prestación]</li>
                <li><strong>Cantidad:</strong> [Especificar cantidad]</li>
                <li><strong>Frecuencia:</strong> [Especificar frecuencia]</li>
            </ul>
        </div>
    </div>

    <div id="seccion7" class="info-content">
        <div class="container">
            <ul>
                <li><strong>Fecha (Desde/Hasta):</strong> 11/01/2021</li>
                <li><strong>Empleo (Empresas):</strong> Ayudante de recepción en una entidad</li>
                <li><strong>Puesto de Trabajo y Tareas:</strong> Atención al público, recepcionista</li>
                <li><strong>Causa de Cese:</strong> Prácticas temporales</li>
                <li><strong>Nombre de Contacto:</strong> [Especificar nombre de contacto]</li>
            </ul>
        </div>
    </div>

    <div id="seccion8" class="info-content">
        <div class="container">
            <ul>
                <li><strong>Aficiones:</strong> Disfrazarse, actuar y hacer teatro</li>
                <li><strong>Intereses:</strong> Ser más independiente y trabajar con personas</li>
            </ul>
        </div>
    </div>

    <div id="seccion9" class="info-content">
        <div class="container">
            <ul>
                <li><strong>Habilidades Transversales:</strong> Buena interacción social, comunicación clara, capacidad para establecer relaciones sociales</li>
                <li><strong>Habilidades de Identificación:</strong> Capacidad para identificar tareas y seguir instrucciones, aunque necesita apoyo</li>
                <li><strong>Habilidades de Relación:</strong> Le gusta trabajar con personas, buena disposición para interactuar con el público</li>
                <li><strong>Habilidades de Afrontamiento:</strong> Necesita ayuda para adaptarse a situaciones laborales nuevas</li>
                <li><strong>Habilidades Técnicas y Profesionales:</strong> Experiencia como recepcionista, habilidades de atención al público</li>
                <li><strong>Habilidades de Búsqueda de Empleo:</strong> Necesitará ayuda para identificar ofertas de empleo y acudir a ellas</li>
                <li><strong>Habilidades en el Proceso de Selección:</strong> Necesitará acompañamiento en entrevistas y presentación de CV</li>
            </ul>
        </div>
    </div>

    <div id="seccion10" class="info-content">
        <div class="container">
            <table>
                <tr>
                    <th>Empleos a los que se Orienta</th>
                    <th>Apoyos Necesarios</th>
                </tr>
                <tr>
                    <td>Recepcionista</td>
                    <td>Apoyo a la adaptación al empleo</td>
                </tr>
                <tr>
                    <td>Atención al cliente</td>
                    <td>Entrenamiento para la autonomía en desplazamientos</td>
                </tr>
                <tr>
                    <td>Asistente en eventos</td>
                    <td>Acompañamiento en la integración al puesto</td>
                </tr>
                <tr>
                    <td>Trabajo de teatro</td>
                    <td>Apoyo en las actividades realizadas</td>
                </tr>
            </table>
        </div>
    </div>
