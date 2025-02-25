<h1>README</h1>

<h2>English</h2>

<p>This repository contains the materials to support the article <strong>"Service-aware password risk meter – Helping users to choose suitable passwords in services"</strong>, submitted for consideration in ARES 2025.</p>

<p>These materials include:</p>

<ol>
    <li>A <strong>website</strong> that implements a password risk meter, helping users evaluate the security of their passwords based on the context of the service.</li>
    <li>The <strong>\( R_d \) matrix</strong>, provided in the file <strong>Rd_matrix.xlsx</strong>, which is used to compute password risk levels.</li>
</ol>

<h3>How to Run the Website Locally</h3>
<p>The website can be hosted locally using Python's built-in HTTP server:</p>

<h4>Using Python 3:</h4>
<pre><code>python -m http.server</code></pre>
<p>The website will be available at <a href="http://localhost:8000">http://localhost:8000</a>.</p>

<h4>Using Python 2:</h4>
<pre><code>python -m SimpleHTTPServer</code></pre>

<h3>Repository Structure</h3>
<ul>
    <li><strong>index.html</strong> - Main HTML file.</li>
    <li><strong>app.js</strong> - Main JavaScript logic.</li>
    <li><strong>style.css</strong> - Stylesheet.</li>
    <li><strong>Rd_matrix.xlsx</strong> - Contains the \( R_d \) matrix used in risk calculations.</li>
    <li><strong>.gitignore</strong> - Specifies files to be ignored by Git.</li>
    <li><strong>LICENSE.md</strong> - License file.</li>
    <li><strong>readme.md</strong> - Markdown version of this README.</li>
</ul>

<h4>Folders:</h4>
<ul>
    <li><strong>assets/</strong> - Contains images and icons.</li>
    <li><strong>data/</strong> - Stores JSON data, including:
        <ul>
            <li><strong>services.json</strong> - Service-related data.</li>
            <li><strong>translations/</strong> - Language translations:
                <ul>
                    <li><strong>en.json</strong> - English translations.</li>
                    <li><strong>es.json</strong> - Spanish translations.</li>
                </ul>
            </li>
        </ul>
    </li>
    <li><strong>js/</strong> - JavaScript scripts:
        <ul>
            <li><strong>passwordStrengthChecker.js</strong> - Evaluates password strength.</li>
            <li><strong>popup.js</strong> - Manages popups.</li>
            <li><strong>riskCalculation.js</strong> - Computes risk using \( R_d \).</li>
            <li><strong>search.js</strong> - Implements search functionality.</li>
            <li><strong>zxcvbn.js</strong> - External library for password analysis.</li>
        </ul>
    </li>
</ul>

<hr>

<h2>Español</h2>

<p>Este repositorio contiene los materiales de apoyo para el artículo <strong>"Service-aware password risk meter – Helping users to choose suitable passwords in services"</strong>, enviado para consideración en ARES 2025.</p>

<p>Estos materiales incluyen:</p>

<ol>
    <li>Un <strong>sitio web</strong> que implementa un medidor de riesgo de contraseñas, ayudando a los usuarios a evaluar la seguridad de sus contraseñas según el contexto del servicio.</li>
    <li>La <strong>matriz \( R_d \)</strong>, proporcionada en el archivo <strong>Rd_matrix.xlsx</strong>, utilizada para calcular los niveles de riesgo de las contraseñas.</li>
</ol>

<h3>Cómo Ejecutar el Sitio Web Localmente</h3>
<p>El sitio web puede alojarse localmente utilizando el servidor HTTP integrado en Python:</p>

<h4>Usando Python 3:</h4>
<pre><code>python -m http.server</code></pre>
<p>El sitio estará disponible en <a href="http://localhost:8000">http://localhost:8000</a>.</p>

<h4>Usando Python 2:</h4>
<pre><code>python -m SimpleHTTPServer</code></pre>

<h3>Estructura del Repositorio</h3>
<ul>
    <li><strong>index.html</strong> - Archivo HTML principal.</li>
    <li><strong>app.js</strong> - Lógica principal en JavaScript.</li>
    <li><strong>style.css</strong> - Hoja de estilos.</li>
    <li><strong>Rd_matrix.xlsx</strong> - Contiene la matriz \( R_d \) utilizada en los cálculos de riesgo.</li>
    <li><strong>.gitignore</strong> - Especifica archivos ignorados por Git.</li>
    <li><strong>LICENSE.md</strong> - Archivo de licencia.</li>
    <li><strong>readme.md</strong> - Versión en Markdown de este README.</li>
</ul>

<h4>Carpetas:</h4>
<ul>
    <li><strong>assets/</strong> - Contiene imágenes e íconos.</li>
    <li><strong>data/</strong> - Almacena datos en JSON, incluyendo:
        <ul>
            <li><strong>services.json</strong> - Datos relacionados con los servicios.</li>
            <li><strong>translations/</strong> - Traducciones de idioma:
                <ul>
                    <li><strong>en.json</strong> - Traducciones en inglés.</li>
                    <li><strong>es.json</strong> - Traducciones en español.</li>
                </ul>
            </li>
        </ul>
    </li>
    <li><strong>js/</strong> - Scripts JavaScript:
        <ul>
            <li><strong>passwordStrengthChecker.js</strong> - Evalúa la fortaleza de la contraseña.</li>
            <li><strong>popup.js</strong> - Gestiona popups.</li>
            <li><strong>riskCalculation.js</strong> - Calcula el riesgo usando \( R_d \).</li>
            <li><strong>search.js</strong> - Implementa la búsqueda.</li>
            <li><strong>zxcvbn.js</strong> - Biblioteca externa para análisis de contraseñas.</li>
        </ul>
    </li>
</ul>