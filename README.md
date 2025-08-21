Gestión de Activos y Hojas de Vida TIC
Una aplicación web completa para la gestión centralizada del inventario tecnológico (equipos, software, periféricos), el seguimiento de hojas de vida de usuarios y el registro de mantenimientos en un entorno multiempresa.

✨ Características Principales
🏢 Gestión Multiempresa: Crea, gestiona e invita a usuarios a múltiples empresas desde una sola cuenta.

💻 Inventario Completo: Registra y clasifica equipos, software y periféricos con detalles de compra, garantía y costos.

👤 Hojas de Vida de Usuarios: Asigna activos a los usuarios, registra fechas de ingreso, cargos y gestiona sus perfiles.

🛠️ Registro de Mantenimiento: Lleva un historial detallado de todos los mantenimientos realizados a los equipos, incluyendo descripciones y evidencias.

📊 Dashboard y Reportes: Visualiza métricas clave de tu inventario, como el estado de los equipos, licencias por vencer y costos totales.

🔄 Importación/Exportación CSV: Carga masivamente datos de usuarios y activos o exporta tus inventarios a formato CSV.

📄 Exportación a PDF: Genera hojas de vida completas de los usuarios en formato PDF con un solo clic.

🔐 Autenticación Segura: Sistema de inicio de sesión y registro de usuarios utilizando Supabase Auth.

🚀 Tecnologías Utilizadas
Frontend: HTML5, Tailwind CSS, JavaScript (Vanilla JS)

Backend y Base de Datos: Supabase (Base de datos Postgres, Autenticación, Storage)

Librerías Adicionales:

Chart.js para gráficos y reportes.

jsPDF y jsPDF-AutoTable para la exportación de PDFs.

🔧 Instalación y Puesta en Marcha
Para ejecutar este proyecto, necesitas configurarlo con tu propia instancia de Supabase.

Clona el repositorio:

git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git

Crea tu proyecto en Supabase:

Ve a Supabase.io y crea un nuevo proyecto.

Ve a la sección SQL Editor en el dashboard de tu proyecto.

Abre el archivo schema.sql de este repositorio, copia todo su contenido, pégalo en el editor de Supabase y haz clic en "RUN". Esto creará todas las tablas, funciones y políticas de seguridad necesarias.

Ve a la sección Storage y crea los buckets necesarios con acceso público: activos, facturas, evidencias.

Configura las claves de Supabase en el código:

Abre el archivo index.html.

Busca la sección // --- CONFIGURACIÓN DE SUPABASE --- en el script.

Reemplaza los valores de SUPABASE_URL y SUPABASE_KEY con las claves de tu proyecto. Las encontrarás en Project Settings > API.

const SUPABASE_URL = 'URL_DE_TU_PROYECTO_SUPABASE';
const SUPABASE_KEY = 'TU_CLAVE_PUBLICA_ANON';

¡Listo! Abre el archivo index.html en tu navegador para empezar a usar la aplicación.

❤️ Apoya este Proyecto
Si esta aplicación te ha sido de utilidad, te ha ahorrado tiempo o te ha ayudado a aprender, ¡considera apoyarme con un café! Tu apoyo me motiva a seguir manteniendo y mejorando este proyecto.

<a href='https://ko-fi.com/miltondemo' target='_blank'>
<img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' />
</a>

📜 Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
