<template>
  <div>
    <!--DOCTYPE html-->
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Evidencias</title>
      </head>
      <body>
        <div class="evidencias">
          <h1>Resumen de contenidos computo 2</h1>
          <h4>1.0.0 Generalidades de la seguridad de los datos</h4>
          <p>
            hablar sobre la seguridad de los datos se refiere a las diversas
            medidas que toman las organizaciones para garantizar que sus bases
            de datos estén protegidas de amenazas internas y externas. Esta
            seguridad de los datos incluye proteger la propia base de datos, los
            datos que contiene, su sistema de administración de bases de datos y
            las diversas aplicaciones que acceden a ella. En general, hoy en día
            las organizaciones debieran proteger las bases de datos de ataques
            deliberados, como amenazas a la seguridad haciendo uso de internet
            (ataques automatizados), así como del uso indebido de datos y bases
            de datos por parte de quienes pueden acceder a ellos. En los últimos
            años, el número de accesos no autorizados de los datos en las
            empresas ha aumentado considerablemente. Además del daño inmenso que
            estas amenazas representan para la reputación y la base de clientes
            de una empresa, existe un número creciente de regulaciones y
            sanciones por violaciones de datos que cada país debe de trabajar,
            reglamentos con los cuales basarse para crear políticas internas de
            trabajo para protección de los datos, siendo esto el primer paso
            para lograr una seguridad efectiva de la base de datos, la cual es
            clave para seguir cumpliendo, protegiendo la reputación de las
            organizaciones y permitirles mantener a sus clientes.
          </p>

          <p>
            La seguridad es la protección de activos (como edificios, equipos,
            carga, inventario y, en algunos casos, personas) de las amenazas. La
            seguridad de los datos (o seguridad de la información) se ha
            descrito generalmente como "la protección de la información de una
            amplia gama de amenazas con el fin de garantizar la continuidad del
            negocio, minimizar riesgo empresarial y maximizar el rendimiento de
            las inversiones y las oportunidades de negocio”, y como “el proceso
            porque una organización protege y asegura los sistemas, medios e
            instalaciones que procesan y mantienen información vital para sus
            operaciones ".
          </p>

          <h5>Seguridad de datos.</h5>
          <p>
            Descuidar la privacidad y la protección de los datos puede traer
            consecuencias adversas que son importantes, tales como:
          </p>
          <ol>
            <li>
              Sanciones civiles y penales impuestas por los gobiernos, incluidas
              multas y sanciones.
            </li>
            <li>
              Importantes multas e indemnizaciones por daños resultantes de
              demandas privadas, incluidas las acciones colectivas (permitidas
              en algunas leyes de privacidad y seguridad de datos, esto a partir
              de la legislación en este aspecto que tengan los países).
            </li>
            <li>
              Daño a la reputación de la empresa y la pérdida de la confianza de
              los clientes, lo que resulta en la pérdida de ventas,
              participación de mercado y valor de marca y accionistas.
            </li>
          </ol>

          <h5>Seguridad de la base de datos.</h5>
          <p>
            En cuanto a la seguridad de la base de datos, se refiere al conjunto
            de estándares y tecnologías, que proveen de una gama de
            herramientas, controles y medidas diseñadas para establecer y
            preservar la confidencialidad, integridad y disponibilidad de la
            base de datos. Siendo la intención que las empresas siempre
            consideren a este elemento, como el que continuamente se verá
            comprometido en la mayoría de las filtraciones de datos y, por lo
            tanto, deberá ser protegido de la destrucción, modificación o
            divulgación intencional o accidental.
          </p>
          <h5>La seguridad de los datos, aborda y protege lo siguiente:</h5>
          <ol>
            <li>Los datos en la base de datos.</li>
            <li>El sistema de gestión de bases de datos (DBMS).</li>
            <li>Cualquier aplicación asociada a esta.</li>
          </ol>
          <h4>
            2.0.0 Amenazas, riesgos y vulnerabilidades de las bases de datos
          </h4>
          <h5>Principales Amenazas</h5>
          <ol>
            <li>Ausencia de contraseñas</li>
            <li>Privilegios excesivos</li>
            <li>Vulnerabilidades de la plataforma</li>
            <li>Inyección de sql</li>
            <li>Auditoría débil</li>
            <li>Denegación de servicio</li>
            <li>La Exposición De Los Datos De Backup</li>
            <li>Desbordamiento de búfer</li>
            <li>Bases de datos sin actualizar</li>
          </ol>

          <h5>Ausencia de contraseñas</h5>
          <p>
            Nombre de usuario/password en blanco o bien hacer uso de uno débil
            Hoy en día no es raro encontrarnos pares de datos usuario/password
            del tipo admin/12345 o similar. Esta es la primera línea de defensa
            de entrada a nuestra información y debemos optar por el uso de algo
            más complejo que sea complicado de conseguir por parte de cualquier
            atacante.
          </p>
          <h5>
            Características de bases de datos innecesariamente habilitadas
          </h5>
          <p>
            Cada instalación de base de datos viene con una seriede paquetes o
            módulos adicionales de distintas formasy tamaños que en muy pocas
            ocasiones todos ellosson utilizadas por las compañías, lo que las
            conviertenen una posible puerta de entrada para sufrir algún tipode
            ataque si en esos paquetes se descubre cualquierproblema de
            seguridad. Para reducir riesgos, es recomendable que losusuarios
            detecten esos paquetes que no se utilizan yse desactiven del
            servidor donde estén instalados. Esto no sólo reduce los riesgos de
            ataques, sino quetambién simplifica la gestión de parches ya
            queúnicamente será de máxima urgencia actualizaraquellos que hagan
            referencia a un módulo queestemos utilizando.
          </p>

          <h5>Auditoría débil</h5>
          <p>
            En los últimos años, las redes empresariales han evolucionado
            considerablemente. Todo, desde el computo móvil hasta la nube, todos
            los sistemas están haciendo que las redes actuales sean más
            complejas que nunca, incluso las mismas herramientas que son
            utilizadas para administrar la seguridad de red pueden expandir el
            ataque y crear vulnerabilidades. Las políticas débiles de auditoría
            de base de datos representan riesgos en términos de cumplimiento, la
            disuasión, detección, análisis forense y recuperación
          </p>
          <h4>3.0.0 Normas ISO para la seguridad de los datos</h4>
          <p>
            La norma ISO es establecida por la Organización Internacional de
            estándares (ISO), y se compone de estándares y guías relacionados
            con sistemas y herramientas específicas de gestión aplicables en
            cualquier tipo de organización. Realmente es una entidad conocida a
            nivel global que publica normas internacionales asociadas a la
            calidad. En particular, las conocidas normas ISO son documentos en
            los que se especifican requerimientos que pueden ser utilizados en
            distintas instituciones para garantizar que sus productos y/o
            servicios cumplan con los objetivos de calidad deseada. Los
            beneficios de las normas ISO son notables permiten a las
            organizaciones reducir errores e incrementar la productividad
            minimizando de esta forma costos.
          </p>
          <h5>Cuáles son las normas ISO para la seguridad de los datos:</h5>
          <ol>
            <li>Destrucción de la información y otros recursos.</li>
            <li>Modificación o distorsión de información.</li>
            <li>
              Robo, eliminación o pérdida de información u otros recursos.
            </li>
            <li>La revelación de información.</li>
            <li>La interrupción de los servicios.</li>
          </ol>
          <h5>Preparando a la organización:</h5>
          <p>
            Antes de pensar en la gestión de la seguridad de la información en
            una organización, hay que tener en cuenta las respuestas a las
            siguientes preguntas:
          </p>
          <ol>
            <li>
              ¿Qué hay que proteger? Los activos de la organización requieren
              protección.
            </li>
            <li>
              ¿Contra qué o quién? ¿Cuáles son las amenazas que pueden afectar a
              la organización y cómo y quién puede explotar estas amenazas?
            </li>
            <li>
              ¿Cuál es la importancia de cada recurso? Cada recurso de la
              información participa en el proceso de negocio de la organización.
            </li>
          </ol>

          <h4>Plan de seguridad de los datos basado en normas ISO27001</h4>
          <h5>Protocolos de seguridad de la información</h5>
          <p>
            Estos protocolos se diseñaron con el fin de prevenir que agentes
            externos no autorizados puedan tener acceso a estos datos y están
            compuestos por:
          </p>
          <p>
            Cifrado de datos: cuando el mensaje es enviado por el emisor lo que
            hace es ocultar la información hasta que esta llegue al receptor.
          </p>
          <p>
            Lógica: debe contar con un orden en el que primero van los datos del
            mensaje, el significado y en qué momento se va a enviar este.
          </p>
          <p>
            Autenticación: esta técnica se utiliza para saber que la información
            está siendo manipulada por un ente autorizado y no está sufriendo
            algún tipo de intervención por agentes externos.
          </p>
          <h4>
            Para que sirve el sistema de gestion de seguridad de la
            informacion(SGSI)
          </h4>
          <p>
            La información de una compañía es uno de los activos más importantes
            que se tiene, es por esto que es tan indispensable protegerla, ya
            que esta es esencial para el cumplimiento de los objetivos. Un SGSI
            es un instrumento de gran ayuda para cumplir con la legalidad y la
            protección de los datos, pues este permite que se definan los
            procedimientos y controles que se llevarán a cabo para mantener los
            datos blindados. Además, permite que se establezcan las políticas
            que se le darán a conocer a todos los miembros de la organización y
            saber a profundidad cuáles son los riesgos que pueden sufrir y de
            qué manera pueden mitigarlos.
          </p>
          <h4>4.0.0 Seguridad de las bases de datos en entornos locales</h4>
          <h5>¿Qué es un keylogger?</h5>
          <p>
            Es un software o hardware que puede interceptar y guardar las
            pulsaciones realizadas en el teclado de un equipo que haya sido
            infectado. Este software se sitúa entre el teclado y el sistema
            operativo para interceptar y registrar la información sin que el
            usuario lo note. Además, un keylogger almacena los datos de forma
            local en el ordenador infectado y, en caso de que forme parte de un
            ataque mayor, permite que el atacante tenga acceso remoto al equipo
            de la víctima y registre la información en otro equipo. Aunque el
            término keylogger se usa, normalmente, para nombrar este tipo de
            herramienta maliciosas, existen también herramientas de vigilancia
            legítimas que usan las autoridades policiales y que funcionan de la
            misma forma que los keyloggers.
          </p>
          <h5>Crear sesiones de usuarios con privilegios en un DBMS</h5>
          <p>
            Un usuario es un nombre definido en la base de datos que puede
            conectarse a ella y acceder a determinada información según los
            permisos que tenga asignados por el administrador El objetivo de la
            creación de usuarios es establecer una cuenta segura y útil, que
            tenga los privilegios adecuados y los valores por defecto
            apropiados. Existen usuarios DBA, usuarios operadores y usuarios
            finales, este último puede ser interno o externo a la institución.
            Un usuario DBA tendrá asignado todos los privilegios de la base de
            datos, es el responsable de crear y asignar los privilegios a los
            demás usuarios, es decir es el que planifica la política de
            seguridad de las bases de datos.
          </p>
          <p>
            Los roles son los conjuntos de permisos. Estos conjuntos existen a
            tres niveles distintos: servidor, base de datos y aplicación. Los
            roles permiten agrupar los derechos y gestionar más fácilmente los
            diferentes usuarios y las conexiones. Siempre es preferible asignar
            los derechos a los roles y posteriormente asignar los roles a los
            usuarios. Con una estructura como esta, la adición y la modificación
            de permisos o de usuarios son más sencillas.
          </p>
          <h4>Seguridad en la bases de datos en entornos web</h4>
          <h5>¿Qué es la seguridad de la base de datos?</h5>
          <p>
            La seguridad de la base de datos se refiere a las diversas medidas
            que toman las organizaciones para garantizar que sus bases de datos
            estén protegidas de amenazas internas y externas. La seguridad de la
            base de datos incluye proteger la propia base de datos, los datos
            que contiene, su sistema de administración de bases de datos y las
            diversas aplicaciones que acceden a ella. Las organizaciones deben
            proteger las bases de datos de ataques deliberados, como amenazas a
            la seguridad cibernética, así como del uso indebido de datos y bases
            de datos por parte de quienes pueden acceder a ellos.
          </p>

          <h5>Riesgos para una base de datos</h5>
          <ul>
            <li>
              Denegación de servicio (DoS): el búfer se desborda debido a
              problemas de DoS. Esta es una amenaza común para sus datos.
              También puede deberse a la corrupción de datos y, cuando se
              produce un ataque de este tipo, el servidor se bloquea y no puede
              acceder a los datos. Su sitio web permanecerá inactivo, lo que
              provocará la pérdida de negocios y una mala reputación.
            </li>
            <li>
              Escalada de privilegios: esta es una de las amenazas más graves
              para su base de datos porque puede causar un caos total en su
              negocio. Este problema hace que su base de datos sea propensa a la
              pérdida de datos, la adición malintencionada de datos y la
              modificación.
            </li>
          </ul>
          <h5>Como implementar seguridad en una base de datos?</h5>
          <p>
            Hay tres capas de seguridad de la base de datos: el nivel de la base
            de datos, el nivel de acceso y el nivel del perímetro. La seguridad
            a nivel de la base de datos se produce dentro de la propia base de
            datos, donde viven los datos. La seguridad de la capa de acceso se
            centra en controlar quién puede acceder a ciertos datos o sistemas
            que los contienen. La seguridad de la base de datos a nivel del
            perímetro determina quién puede y quién no puede ingresar a las
            bases de datos. Cada nivel requiere soluciones de seguridad únicas.
          </p>
          <h5>Garantizar la seguridad de la base de datos física</h5>
          <p>
            En el sentido tradicional, esto significa mantener el servidor de
            base de datos en un entorno seguro y bloqueado con controles de
            acceso para mantener fuera a las personas no autorizadas. Pero
            también significa mantener la base de datos en una máquina física
            separada, eliminada de las máquinas que ejecutan aplicaciones o
            servidores web.
          </p>
          <h5>Aplicaciones y Firewall</h5>
          <p>
            El uso de aplicaciones web y firewalls es una de las mejores
            prácticas de seguridad de bases de datos en la capa perimetral. Los
            cortafuegos evitan que los intrusos accedan a la red de TI de una
            organización a través de Internet; son un requisito previo crucial
            para las preocupaciones de seguridad cibernética. Las aplicaciones
            web que interactúan con bases de datos pueden protegerse mediante
            software de gestión de acceso a aplicaciones. Esta medida de
            seguridad de la base de datos es similar a las listas de control de
            acceso y determina quién puede acceder a las aplicaciones web y cómo
            pueden hacerlo. También hay firewalls para aplicaciones web
            individuales que brindan los mismos beneficios que los firewalls
            tradicionales.
          </p>

          <h4>Importancia de los contenidos</h4>
          <p>
            La importancia de cada contenido deriba de la importancia que cada
            tema tenga para nosotros, al menos en cada tema es necesario que le
            demos el tiempo necesario para esclarecer dudas y poder estar seguro
            cuando algo se hace de cierta manera y cual es la correcta
          </p>

          <h1 align="center">Resumen de contenidos computo 3</h1>

          <h4>Almacen de datos</h4>
          <h5>Conceptualización de almacén de datos</h5>
          <p>
            Es un tipo de sistema de gestión de datos que está diseñado para
            habilitar y respaldar las actividades de inteligencia empresarial
            BI, especialmente las analíticas. Los almacenes de datos están
            destinados únicamente a realizar consultas y análisis y, a menudo,
            contienen grandes cantidades de datos históricos. Los datos dentro
            de un almacén de datos generalmente se derivan de una amplia gama de
            fuentes, como archivos de registro de aplicaciones y aplicaciones de
            transacciones.
          </p>

          <p>
            Un almacén de datos centraliza y consolida grandes cantidades de
            datos de múltiples fuentes. Sus capacidades analíticas permiten a
            las organizaciones obtener valiosos conocimientos comerciales a
            partir de sus datos para mejorar la toma de decisiones. Con el
            tiempo, crea un registro histórico que puede ser invaluable para los
            científicos de datos y los analistas comerciales. Debido a estas
            capacidades, un almacén de datos puede considerarse la "única fuente
            de información" de una organización.
          </p>
          <h5>¿Cómo funciona Data Warehouse?</h5>
          <ol>
            <li>
              Funciona como un depósito central donde la información llega de
              una o más fuentes de datos. Los datos fluyen hacia un almacén de
              datos desde el sistema transaccional y otras bases de datos
              relacionales los datos de estas pueden ser:
            </li>
            <li>Estructurado</li>
            <li>Semiestructurada</li>
            <li>Datos no estructurados</li>
          </ol>

          <h5>¿Cómo funciona Data Warehouse?</h5>
          <p>
            Los datos se procesan, transforman e ingieren para que los usuarios
            puedan acceder a los datos procesados en el almacén de datos a
            través de herramientas de inteligencia empresarial, clientes SQL y
            hojas de cálculo. Un almacén de datos fusiona información procedente
            de diferentes fuentes en una base de datos completa.
          </p>
          <p>
            Al fusionar toda esta información en un solo lugar, una organización
            puede analizar a sus clientes de manera más integral. Esto ayuda a
            garantizar que se ha tenido en cuenta toda la información
            disponible. El almacenamiento de datos hace posible la minería de
            datos. La minería de datos busca patrones en los datos que puedan
            generar mayores ventas y ganancias.
          </p>

          <h3>Procesos ETL</h3>
          <p>
            ETL es un proceso que extrae los datos de diferentes sistemas de
            origen, luego los transforma como aplicar cálculos, concatenaciones,
            etc. y finalmente carga los datos en el sistema de almacenamiento de
            datos. La forma completa de ETL es Extraer, Transformar y Cargar
            Extract-Transform-Load.
          </p>
          <p>
            No es tan simple pensar que la creación de un almacén de datos es
            simplemente extraer datos de múltiples fuentes y cargarlos en la
            base de datos de un almacén de datos. Esto está lejos de la verdad y
            requiere un proceso ETL complejo. El proceso ETL requiere
            aportaciones activas de varias partes interesadas, incluidos
            desarrolladores, analistas, probadores, altos ejecutivos y es un
            desafío técnico.
          </p>
          <p>
            ETL es una actividad recurrente diaria, semanal, mensual de un
            sistema de almacenamiento de datos y debe ser ágil, automatizada y
            bien documentada.
          </p>
          <h5>Por que son necesarias en una empresa?</h5>
          <ol>
            <li>
              Permitir la verificación de las reglas de transformación,
              agregación y cálculo de datos.
            </li>
            <li>
              El proceso ETL permite la comparación de datos de muestra entre el
              sistema de origen y el de destino.
            </li>
            <li>
              El proceso ETL puede realizar transformaciones complejas y
              requiere un área adicional para almacenar los datos.
            </li>
            <li>
              ETL ayuda a migrar datos a un almacén de datos. Convierta a varios
              formatos y tipos para adherirse a un sistema consistente.
            </li>
            <li>
              ETL es un proceso predefinido para acceder y manipular datos de
              origen en la base de datos de destino.
            </li>
            <li>
              ETL en el almacén de datos ofrece un contexto histórico profundo
              para el negocio.
            </li>
          </ol>

          <h3>Cubos OLAP</h3>

          <p>
            El procesamiento analítico en línea OLAP es una categoría de
            software que permite a los usuarios analizar información de
            múltiples sistemas de bases de datos al mismo tiempo. Es una
            tecnología que permite a los analistas extraer y ver datos
            comerciales desde diferentes puntos de vista. Los analistas con
            frecuencia necesitan agrupar, agregar y unir datos.
          </p>
          <p>
            Estas operaciones en bases de datos relacionales requieren muchos
            recursos. Con OLAP, los datos se pueden calcular y agregar
            previamente, lo que agiliza el análisis. Las bases de datos OLAP se
            dividen en uno o más cubos. Los cubos están diseñados de tal manera
            que la creación y visualización de informes resulten fáciles. OLAP
            significa procesamiento analítico en línea.
          </p>
          <h5>Los cubos OLAP constan de:</h5>
          <p>
            El Cubo OLAP consta de hechos numéricos llamados medidas que se
            clasifican por dimensiones. El Cubo OLAP también se llama hipercubo
            .
          </p>
          <p>
            Por lo general, las operaciones y el análisis de datos se realizan
            utilizando una hoja de cálculo simple, donde los valores de los
            datos se organizan en formato de fila y columna. Esto es ideal para
            datos bidimensionales. Sin embargo, OLAP contiene datos
            multidimensionales, con datos que generalmente se obtienen de una
            fuente diferente y no relacionada. Usar una hoja de cálculo no es
            una opción óptima. El cubo puede almacenar y analizar datos
            multidimensionales de manera lógica y ordenada.
          </p>

          <h5>Los cubos OLAP funcionan de la siguiente manera:</h5>
          <p>
            Un almacén de datos extraería información de múltiples fuentes y
            formatos de datos, como archivos de texto, hojas de Excel, archivos
            multimedia, etc. Los datos extraídos se limpian y transforman. Los
            datos se cargan en un servidor OLAP o cubo OLAP donde la información
            se calcula previamente para su posterior análisis.
          </p>
          <h3>Introduccion a la mineria de datos</h3>
          <p>
            En el mundo empresarial, los minoristas y el comercio electrónico
            han generado grandes bases de datos sobre transacciones comerciales.
            También se han generado una gran cantidad de datos científicos en
            varios campos. La World Wide Web proporciona un ejemplo con miles de
            millones de páginas web que consisten en información textual y
            multimedia que son utilizadas por millones de personas. El análisis
            de grandes cantidades de datos que se pueden comprender y utilizar
            de manera eficiente sigue siendo un problema desafiante. La minería
            de datos aborda este problema proporcionando técnicas y software
            para automatizar el análisis y la exploración de conjuntos de datos
            grandes y complejos. La investigación sobre minería de datos se
            lleva a cabo en una amplia variedad de campos, que incluyen
            estadísticas, informática, aprendizaje automático, gestión de bases
            de datos y visualización de datos, por nombrar algunos.
          </p>

          <h5>Mineria de los datos</h5>
          <p>
            La minería de datos , también conocida popularmente como
            descubrimiento de conocimientos en bases de datos KDD, se refiere a
            la extracción no trivial de información implícita, previamente
            desconocida y potencialmente útil de datos en bases de datos. Si
            bien la minería de datos y el descubrimiento de conocimientos en
            bases de datos o KDD se tratan con frecuencia como sinónimos, la
            minería de datos es en realidad parte del proceso de descubrimiento
            de conocimientos.
          </p>
          <p>
            La minería de datos se refiere a un conjunto de métodos aplicables a
            bases de datos grandes y complejas para eliminar la aleatoriedad y
            descubrir el patrón oculto. Los métodos de minería de datos casi
            siempre son computacionalmente intensivos. La minería de datos se
            trata de herramientas, metodologías y teorías para revelar patrones
            en los datos, que es un paso fundamental en el descubrimiento del
            conocimiento.
          </p>
          <p>
            Utilizamos técnicas de minería de datos para un largo proceso de
            investigación y desarrollo de productos. Como esta evolución se
            inició cuando los datos comerciales se almacenaron por primera vez
            en las computadoras. Además, permite a los usuarios navegar por sus
            datos en tiempo real. La minería de datos en la comunidad
            empresarial está respaldada por tres tecnologías que ahora están
            maduras:
          </p>
          <ol>
            <li>Recopilación masiva de datos</li>
            <li>Potentes ordenadores multiprocesador</li>
            <li>Algoritmos de minería de datos</li>
          </ol>
          <h5>Herramientas para minar datos</h5>
          <p>
            La minería de datos se refiere al proceso de "excavar" es decir,
            analizar con computadoras grandes volúmenes de datos para
            identificar anomalías, patrones y correlaciones interesantes. Este
            tipo de análisis tiene sus raíces en técnicas estadísticas como el
            teorema de Bayes que inicialmente se calcularon a mano. Sin embargo,
            la minería de datos actual es cada vez más sofisticada y refleja una
            combinación de prácticas de estadística, ciencia de datos , teoría
            de bases de datos, inteligencia artificial y aprendizaje automático
            .
          </p>
          <p>
            Con las herramientas de minería de datos , las organizaciones de
            cualquier tamaño pueden extraer información valiosa de sus conjuntos
            de datos, incluida información sobre consumidores, costos y
            tendencias futuras. Este proceso puede emplearse para a responder
            preguntas comerciales que tradicionalmente tomaban demasiado tiempo
            para abordar y b tomar decisiones basadas en el conocimiento basadas
            en los mejores datos disponibles.
          </p>

          <h5>La mineria de datos en las empresas y su marketing</h5>
          <p>
            Las herramientas de minería de datos pueden a obtener más
            información sobre las preferencias del consumidor, recopilar datos
            demográficos, de género, ubicación y otros datos de perfil, y
            aprovechar toda esa información para optimizar los esfuerzos de
            marketing y ventas. Las correlaciones en el comportamiento de
            compra, por ejemplo, se pueden utilizar para crear personas
            compradoras más sofisticadas que, a su vez, pueden ayudarlo a crear
            mensajes más específicos.
          </p>
          
        </div>
      </body>
    </html>
  </div>
</template>