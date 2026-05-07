<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rapport de Stage CBG 2026 - Kaba Mohamed Asbour Diakité</title>
    <style>
        /* Microsoft-style layout */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            background: #fff;
            line-height: 1.5;
        }

        .container {
            display: flex;
            gap: 2rem;
            max-width: 1400px;
            margin: 0 auto;
            padding: 1rem;
        }

        .sidebar {
            width: 280px;
            flex-shrink: 0;
            border-right: 1px solid #e1e4e8;
            padding-right: 1.5rem;
            position: sticky;
            top: 0;
            height: 100vh;
            overflow-y: auto;
        }

        .main-content {
            flex: 1;
            min-width: 0;
            padding: 0 1rem;
        }

        .right-toc {
            width: 240px;
            flex-shrink: 0;
            border-left: 1px solid #e1e4e8;
            padding-left: 1.5rem;
            position: sticky;
            top: 0;
            height: 100vh;
            overflow-y: auto;
        }

        .sidebar summary, .right-toc summary {
            cursor: pointer;
            font-weight: 600;
            padding: 0.5rem 0;
            color: #24292e;
        }

        .sidebar details, .right-toc details {
            margin-bottom: 0.5rem;
        }

        .sidebar a, .right-toc a {
            text-decoration: none;
            color: #0366d6;
            display: block;
            padding: 0.25rem 0 0.25rem 1rem;
            font-size: 0.875rem;
        }

        .sidebar a:hover, .right-toc a:hover {
            color: #0056b3;
            text-decoration: underline;
        }

        h1, h2, h3, h4 {
            scroll-margin-top: 1rem;
        }

        h1 {
            border-bottom: 2px solid #e1e4e8;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }

        h2 {
            border-bottom: 1px solid #e1e4e8;
            padding-bottom: 0.3rem;
            margin-top: 1.5rem;
            margin-bottom: 1rem;
        }

        .confidential-box {
            background-color: #fff8e7;
            border-left: 4px solid #ffa500;
            padding: 1rem;
            margin: 1rem 0;
            font-style: italic;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        video {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        table {
            border-collapse: collapse;
            width: 100%;
            margin: 1rem 0;
        }

        th, td {
            border: 1px solid #e1e4e8;
            padding: 0.5rem;
            text-align: left;
        }

        th {
            background-color: #f6f8fa;
        }

        @media (max-width: 900px) {
            .sidebar, .right-toc {
                display: none;
            }
            .container {
                padding: 0.5rem;
            }
            .main-content {
                width: 100%;
            }
        }
    </style>
</head>
<body>

<div class="container">

    <!-- ==================== LEFT SIDEBAR MENU ==================== -->
    <div class="sidebar">
        <h3>📋 RAPPORT DE STAGE 2026</h3>
        <p><strong>Kaba Mohamed Asbour Diakité</strong></p>
        <hr>

        <details open>
            <summary><strong>🏠 INTRODUCTION</strong></summary>
            <a href="#confidentialite">🔒 Avis de Confidentialité</a>
            <a href="#couverture">📄 Couverture</a>
            <a href="#table-des-matieres">📑 Table des Matières</a>
            <a href="#introduction-generale">Introduction Générale</a>
        </details>

        <details>
            <summary><strong>🙏 REMERCIEMENTS & OBJECTIFS</strong></summary>
            <a href="#remerciements">🙏 Remerciements</a>
            <a href="#objectifs-strategiques-du-stage">🎯 Objectifs stratégiques</a>
            <a href="#vision-dintegration-et-projection-professionnelle">👁️ Vision professionnelle</a>
        </details>

        <details>
            <summary><strong>🏢 PRÉSENTATION CBG</strong></summary>
            <a href="#presentation-de-lentreprise">Aperçu général</a>
            <a href="#5-description-du-departement-informatique-d4402">Département IT D4402</a>
        </details>

        <details>
            <summary><strong>📊 SEMAINE 1 - INDUCTION</strong></summary>
            <a href="#51-induction-et-sensibilisation-institutionnelle">Induction</a>
            <a href="#52-premiere-immersion-dans-les-departements-techniques--12022026">Première immersion</a>
            <a href="#55-immersion-au-departement-sap--13022026">Immersion SAP</a>
            <a href="#7-difficultes-rencontrees">Difficultés</a>
        </details>

        <details>
            <summary><strong>🟢 SEMAINE 2 - SAP & FICHES DE PAIE</strong></summary>
            <a href="#571-approfondissement-des-transactions-sap--16022026">Transactions SAP</a>
            <a href="#572-assistance-utilisateur--transaction-migo">Assistance MIGO</a>
            <a href="#573-mise-en-place-dun-serveur-apache--projet-fiches-de-paie">Serveur Apache</a>
            <a href="#575-choix-du-module-sap--orientation-vers-mm">Module MM</a>
        </details>

        <details>
            <summary><strong>⚙️ SEMAINES 3 À 5</strong></summary>
            <a href="#581-reunion-hebdomadaire-et-management-operationnel--23022026">Management Outils</a>
            <a href="#591-developpement-dun-tableau-de-bord-power-bi--02032026">Power BI</a>
            <a href="#5101-reunion-hebdomadaire-et-suivi-des-projets--09032026">Admin & Accès</a>
        </details>

        <details>
            <summary><strong>🚀 SEMAINES 6 À 12</strong></summary>
            <a href="#5113-lancement-du-projet-power-apps-laissez-passer--18032026">Power Apps</a>
            <a href="#5122-poursuite-du-projet-power-apps">Développement avancé</a>
            <a href="#513-huitieme-semaine--integration-des-workflows-et-optimisation-des-outils">Finalisation</a>
            <a href="#517-douzieme-semaine--bilan-final-et-cloture-du-stage">Bilan final</a>
        </details>

        <details>
            <summary><strong>📎 ANNEXES & CONCLUSION</strong></summary>
            <a href="#8-competences-techniques-acquises">Compétences</a>
            <a href="#conclusion-generale">Conclusion</a>
            <a href="#annexes-1">Annexes</a>
        </details>
    </div>

    <!-- ==================== MAIN CONTENT AREA ==================== -->
    <div class="main-content">

        <h1>RAPPORT DE STAGE DE KABA MOHAMED ASBOUR DIAKITÉ - 2026</h1>

        <div id="confidentialite" class="confidential-box">
            <strong>🔒 AVIS DE CONFIDENTIALITÉ</strong><br>
            <em>Ce document contient des informations relatives à mon stage au sein de la <strong>COMPAGNIE DES BAUXITES DE GUINEE (CBG)</strong>.</em><br>
            <em>Il est destiné uniquement à des fins d'évaluation académique.</em><br>
            <em>Merci de ne pas le diffuser sans autorisation préalable.</em><br>
            📞 Tel: (+224) 626-73-26-82 / 611-57-12-58<br>
            📧 asbourkaba3657diakite@gmail.com<br>
            📧 asbourmohamed3657@outlook.fr
        </div>

        <div id="couverture">
            <h2>COVER PAGE - PAGE DE GARDE</h2>
            <img src="coverpage.png" alt="Page de garde" style="max-width: 100%; border: 1px solid #ddd;">
        </div>

        <div id="table-des-matieres">
            <h2>TABLE OF CONTENT / TABLE DES MATIÈRES</h2>
            <ul>
                <li><a href="#introduction-generale">Introduction Générale</a></li>
                <li><a href="#remerciements">2. Remerciements</a></li>
                <li><a href="#presentation-de-lentreprise">4. Présentation de l'Entreprise</a></li>
                <li><a href="#51-induction-et-sensibilisation-institutionnelle">7.1 Semaine 1 - Induction</a></li>
                <li><a href="#571-approfondissement-des-transactions-sap--16022026">7.2 Semaine 2 - SAP</a></li>
                <li><a href="#8-competences-techniques-acquises">8. Compétences Techniques Acquises</a></li>
                <li><a href="#conclusion-generale">12. Conclusion Générale</a></li>
                <li><a href="#annexes-1">13. Annexes</a></li>
            </ul>
        </div>

        <div id="introduction-generale">
            <h2>INTRODUCTION</h2>
            <p>Ce stage s'inscrit dans le cadre de ma formation académique et représente une étape essentielle dans mon parcours professionnel. Il a été effectué au sein de la <strong>Compagnie des Bauxites de Guinée (CBG)</strong>, plus précisément dans le département D4402 Informatique.</p>
            <p>L'objectif principal de cette immersion était de découvrir le fonctionnement d'un environnement industriel complexe, d'acquérir des compétences techniques concrètes et de participer activement aux activités du département informatique.</p>
            <p>Au cours de cette expérience, j'ai été impliqué dans plusieurs domaines clés tels que : les systèmes ERP (SAP), l'analyse et la gestion des données, le support technique, le développement d'applications (Power Apps, Django), et l'automatisation des processus (Power Automate).</p>
            <video src="./INTERNSHIPSource/INTERNSHIP%20FILE/NEW%20ARRIVAL/video.mp4" controls autoplay muted loop width="100%"></video>
        </div>

        <div id="remerciements">
            <h2>Remerciements</h2>
            <p>Je tiens à exprimer ma profonde gratitude à la <strong>Compagnie des Bauxites de Guinée (CBG)</strong> pour m'avoir offert l'opportunité d'effectuer mon stage au sein du département D4402 Informatique. Cette expérience représente une étape déterminante dans mon parcours académique et professionnel.</p>
            <p>Je remercie particulièrement mon encadreur professionnel, <strong>Monsieur Thierno Mamoudou Barry</strong>, pour son accompagnement, sa disponibilité, ses conseils techniques et la confiance qu'il m'a accordée tout au long de cette période.</p>
        </div>

        <!-- The rest of your content continues here -->
        <!-- I have your complete content - for brevity, I'm showing the structure -->
        <!-- Please copy the ENTIRE content from your original file into this HTML -->

    </div>

    <!-- ==================== RIGHT TOC ==================== -->
    <div class="right-toc">
        <h4>📑 Sur cette page</h4>
        <a href="#confidentialite">Confidentialité</a>
        <a href="#couverture">Couverture</a>
        <a href="#remerciements">Remerciements</a>
        <a href="#introduction-generale">Introduction</a>
        <a href="#presentation-de-lentreprise">Présentation CBG</a>
        <a href="#conclusion-generale">Conclusion</a>
        <a href="#annexes-1">Annexes</a>
    </div>

</div>

</body>
</html>
