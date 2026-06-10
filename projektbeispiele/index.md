---
layout: page
title: "Projektbeispiele | GetPEC mbH"
description: "Ausgewählte Projektbeispiele aus der Arbeit von GetPEC mbH – kundenspezifische Entwicklungen in Messtechnik, Prüfstandsbau und thermodynamischer Analyse."
hero_title: "Projektbeispiele"
hero_subtitle: "Ausgewählte Beispiele aus der Projektarbeit von GetPEC – kundenspezifische Lösungen für anspruchsvolle thermische Fragestellungen."
hero_image: "/assets/images/hero-project-examples.png"
permalink: /projektbeispiele/
---

<section class="section">
  <div class="container">
    <div class="project-notice">
      <p>Die folgenden Beispiele illustrieren ausgewählte Kompetenzen und Engineering-Lösungen aus der Projektarbeit von GetPEC. Es handelt sich um <strong>kundenspezifische Entwicklungen</strong>, keine Standardprodukte. Ihre Aufgabenstellung wird individuell analysiert und umgesetzt.</p>
    </div>

    <div class="projects-grid">
      {% for project in site.data.project_examples %}
        {% include project-card.html project=project %}
      {% endfor %}
    </div>
  </div>
</section>

<section class="section section--bg">
  <div class="container">
    <h2 class="section-title">Ihr Projekt anfragen</h2>
    <p class="section-subtitle">Sie haben eine ähnliche Aufgabenstellung oder suchen nach einer individuellen Lösung? Sprechen Sie uns an – wir besprechen Ihre Anforderungen gerne unverbindlich.</p>
    <div class="text-center">
      <a href="{{ '/kontakt/' | relative_url }}" class="btn btn-primary btn-large">Anfrage stellen</a>
      <a href="{{ '/leistungen/' | relative_url }}" class="btn btn-outline" style="margin-left:1rem">Alle Leistungen</a>
    </div>
  </div>
</section>
