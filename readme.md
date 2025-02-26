<h1>README</h1>

<h2>English</h2>

<p>This repository contains the materials to support the article <strong>"Service-aware password risk meter – Helping users to choose suitable passwords in services"</strong>, submitted for consideration in ARES 2025.</p>

<p>Some elements have been removed to ensure anonymity.</p>

<p>These materials include:</p>

<ol>
    <li>A <strong>website</strong> that implements a password risk meter, helping users evaluate the security of their passwords based on the context of the service.</li>
    <li>The <strong>\( R_d \) matrix</strong>, provided in the file <strong>Rd_matrix.xlsx</strong>, which is used to compute password risk levels.</li>
    <li><strong>Survey results</strong> stored in the <strong>surveys</strong> folder:
        <ul>
            <li><strong>Expert validation</strong> results in <strong>expert_validation_english.xlsx</strong> and <strong>expert_validation_spanish.xlsx</strong>.</li>
            <li><strong>User validation</strong> results in <strong>user_validation.xlsx</strong>.</li>
        </ul>
    </li>
</ol>

<h3>How to Run the Website Locally</h3>
<p>To run the website, navigate to the <strong>risk-meter</strong> folder and start the server:</p>

<h4>Using Python 3:</h4>
<pre><code>cd risk-meter
python -m http.server</code></pre>
<p>The website will be available at <a href="http://localhost:8000">http://localhost:8000</a>.</p>

<h4>Using Python 2:</h4>
<pre><code>cd risk-meter
python -m SimpleHTTPServer</code></pre>

<h3>Repository Structure</h3>

<h4>Root Directory</h4>
<ul>
    <li><strong>.gitattributes</strong> - Git configuration file.</li>
    <li><strong>.gitignore</strong> - Specifies files ignored by Git.</li>
</ul>

<h4>Risk Meter (Website)</h4>
<ul>
    <li><strong>risk-meter/</strong> - Contains the implementation of the password risk meter:
        <ul>
            <li><strong>index.html</strong> - Main HTML file.</li>
            <li><strong>app.js</strong> - Main JavaScript logic.</li>
            <li><strong>style.css</strong> - Stylesheet.</li>
            <li><strong>LICENSE</strong> - License file.</li>
            <li><strong>readme.md</strong> - Markdown version of this README.</li>
            <li><strong>assets/images/</strong> - Contains images and icons.</li>
            <li><strong>data/</strong> - Stores JSON data:
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
    </li>
</ul>

<h4>Survey Data</h4>
<ul>
    <li><strong>surveys/</strong> - Contains survey results:
        <ul>
            <li><strong>Rd_matrix.xlsx</strong> - The \( R_d \) matrix used in risk calculations.</li>
            <li><strong>expert validation/</strong> - Results from expert validation:
                <ul>
                    <li><strong>expert_validation_english.xlsx</strong> - Expert validation in English.</li>
                    <li><strong>expert_validation_spanish.xlsx</strong> - Expert validation in Spanish.</li>
                </ul>
            </li>
            <li><strong>user validation/</strong> - Results from user validation:
                <ul>
                    <li><strong>user_validation.xlsx</strong> - User validation results.</li>
                </ul>
            </li>
        </ul>
    </li>
</ul>

<hr>

<h2>Español</h2>

<p>Este repositorio contiene los materiales de apoyo para el artículo <strong>"Service-aware password risk meter – Helping users to choose suitable passwords in services"</strong>, enviado para consideración en ARES 2025.</p>

<p>Algunos elementos han sido eliminados para garantizar el anonimato.</p>

<p>Estos materiales incluyen:</p>

<ol>
    <li>Un <strong>sitio web</strong> que implementa un medidor de riesgo de contraseñas, ayudando a los usuarios a evaluar la seguridad de sus contraseñas según el contexto del servicio.</li>
    <li>La <strong>matriz \( R_d \)</strong>, proporcionada en el archivo <strong>Rd_matrix.xlsx</strong>, utilizada para calcular los niveles de riesgo de las contraseñas.</li>
    <li><strong>Resultados de encuestas</strong> almacenados en la carpeta <strong>surveys</strong>:
        <ul>
            <li><strong>Validación de expertos</strong> en <strong>expert_validation_english.xlsx</strong> y <strong>expert_validation_spanish.xlsx</strong>.</li>
            <li><strong>Validación de usuarios</strong> en <strong>user_validation.xlsx</strong>.</li>
        </ul>
    </li>
</ol>

<h3>Cómo Ejecutar el Sitio Web Localmente</h3>
<p>Para ejecutar el sitio web, navega a la carpeta <strong>risk-meter</strong> y ejecuta el servidor:</p>

<h4>Usando Python 3:</h4>
<pre><code>cd risk-meter
python -m http.server</code></pre>
<p>El sitio estará disponible en <a href="http://localhost:8000">http://localhost:8000</a>.</p>

<h4>Usando Python 2:</h4>
<pre><code>cd risk-meter
python -m SimpleHTTPServer</code></pre>