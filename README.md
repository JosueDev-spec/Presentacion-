<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículum Josué García</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f8fafc;
            color: #1e293b;
            padding: 20px;
        }
        .cv-container {
            max-width: 850px;
            margin: 0 auto;
            background: #ffffff;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
        }
        /* Encabezado */
        .header {
            display: flex;
            align-items: center;
            gap: 25px;
            border-bottom: 2px solid #f1f5f9;
            padding-bottom: 25px;
            margin-bottom: 25px;
        }
        .header-info h1 {
            font-size: 28px;
            color: #0f172a;
            margin-bottom: 4px;
        }
        .header-info .sub {
            font-size: 16px;
            color: #475569;
            font-weight: 600;
            margin-bottom: 2px;
        }
        .header-info .univ {
            font-size: 14px;
            color: #64748b;
            margin-bottom: 12px;
        }
        .meta-data {
            display: flex;
            gap: 20px;
            font-size: 13px;
            color: #475569;
            flex-wrap: wrap;
        }
        /* Grid de Contenido */
        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-bottom: 25px;
        }
        .section-title {
            font-size: 16px;
            font-weight: 700;
            color: #0f172a;
            margin-bottom: 15px;
            border-bottom: 1px solid #e2e8f0;
            padding-bottom: 5px;
        }
        .card {
            background: #f8fafc;
            border: 1px solid #e2e8f0;
            border-radius: 12px;
            padding: 15px;
            margin-bottom: 15px;
        }
        /* Habilidades */
        .skills-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }
        .skill-category {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 10px;
            padding: 12px;
        }
        .skill-category h4 {
            font-size: 13px;
            color: #1e3a8a;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        .skill-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 13px;
            margin-bottom: 6px;
        }
        .skill-level {
            font-size: 11px;
            color: #2563eb;
            background: #eff6ff;
            padding: 2px 8px;
            border-radius: 12px;
            font-weight: 600;
        }
        /* Listas simples */
        ul {
            list-style: none;
        }
        ul li {
            font-size: 13px;
            margin-bottom: 6px;
            position: relative;
            padding-left: 15px;
        }
        ul li::before {
            content: "•";
            color: #2563eb;
            font-weight: bold;
            position: absolute;
            left: 0;
        }
        @media print {
            body { background: none; padding: 0; }
            .cv-container { box-shadow: none; padding: 0; }
        }
    </style>
</head>
<body>

<div class="cv-container">
    <div class="header">
        <div class="header-info">
            <h1>Josué García</h1>
            <div class="sub">Estudiante de Administración de Oficinas</div>
            <div class="univ">Universidad Nacional de Costa Rica – Campus Sarapiquí</div>
            <div class="meta-data">
                <span>📍 Río Frío, Sarapiquí, Costa Rica</span>
                <span>✉️ josuegarciarortiz36@gmail.com</span>
                <span>🎂 Edad: 25 años</span>
            </div>
        </div>
    </div>

    <div class="grid-2">
        <div>
            <div class="section-title">Aplicaciones Destacadas</div>
            <div class="card">
                <div class="skill-item"><strong>Microsoft Office</strong> <span class="skill-level">Intermedio</span></div>
                <div class="skill-item" style="margin-top: 5px;"><strong>Power BI</strong> <span class="skill-level">Básico</span></div>
                <div class="skill-item" style="margin-top: 5px;"><strong>Access</strong> <span class="skill-level">Básico</span></div>
            </div>
        </div>
        <div>
            <div class="section-title">Intereses</div>
            <div class="card">
                <ul>
                    <li>Tecnología e Innovación Digital</li>
                    <li>Inteligencia Artificial</li>
                    <li>Análisis de Datos</li>
                </ul>
            </div>
        </div>
    </div>

    <div class="section-title">Habilidades Técnicas</div>
    <div class="skills-grid">
        <div class="skill-category">
            <h4>Sistemas Operativos</h4>
            <div class="skill-item"><span>Windows</span> <span class="skill-level">Intermedio-Avanzado</span></div>
            <div class="skill-item"><span>Linux</span> <span class="skill-level">Básico</span></div>
        </div>
        
        <div class="skill-category">
            <h4>Inteligencia Artificial</h4>
            <div class="skill-item"><span>ChatGPT</span> <span class="skill-level">Intermedio</span></div>
            <div class="skill-item"><span>Gemini</span> <span class="skill-level">Intermedio</span></div>
            <div class="skill-item"><span>ElevenLabs</span> <span class="skill-level">Intermedio</span></div>
            <div class="skill-item"><span>Microsoft Copilot</span> <span class="skill-level">Intermedio</span></div>
        </div>

        <div class="skill-category">
            <h4>Automatización y Desarrollo</h4>
            <div class="skill-item"><span>Power Automate</span> <span class="skill-level">Básico-Intermedio</span></div>
            <div class="skill-item"><span>Google Apps Script</span> <span class="skill-level">Básico-Intermedio</span></div>
            <div class="skill-item"><span>Power Apps</span> <span class="skill-level">Básico-Intermedio</span></div>
        </div>

        <div class="skill-category">
            <h4>Herramientas de Gestión y Diseño</h4>
            <div class="skill-item"><span>Notion / Trello</span> <span class="skill-level">Básico-Intermedio</span></div>
            <div class="skill-item"><span>Slack / GitHub</span> <span class="skill-level">Básico</span></div>
            <div class="skill-item"><span>Canva / Figma</span> <span class="skill-level">Básico</span></div>
        </div>
    </div>

    <br>

    <div class="grid-2">
        <div>
            <div class="section-title">Educación</div>
            <div class="card">
                <strong>Universidad Nacional de Costa Rica</strong><br>
                <span style="font-size: 13px; color: #475569;">Administración de Oficinas</span><br>
                <span style="font-size: 12px; color: #64748b;">2024 - Actualidad</span>
            </div>
        </div>
        <div>
            <div class="section-title">Idiomas</div>
            <div class="card">
                <div class="skill-item"><span>Español</span> <span class="skill-level" style="background:#dcfce7; color:#15803d;">Nativo</span></div>
                <div class="skill-item" style="margin-top: 8px;"><span>Inglés</span> <span class="skill-level">Intermedio</span></div>
            </div>
        </div>
    </div>
</div>

</body>
</html>
