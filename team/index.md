---
layout: page
title: "Team | GetPEC mbH"
description: "Das Team von GetPEC mbH – Dr. Axel Sielaff, Dr. Martin Freystein, Dr. Felix Brinckmann und Prof. Dr. Peter Stephan – verbindet wissenschaftliche Exzellenz mit industrieller Erfahrung."
hero_title: "Das Team"
hero_subtitle: "GetPEC mbH vereint wissenschaftliche Exzellenz mit industrieller Erfahrung – für praxisnahe Lösungen auf wissenschaftlichem Fundament."
hero_image: "/assets/images/hero-team.png"
permalink: /team/
breadcrumbs: true
---

<section class="section">
  <div class="container">

    <p class="lead">
      Unser Team verbindet tiefsitzende wissenschaftliche Expertise in der Thermodynamik und Wärmeübertragung mit jahrelanger Erfahrung in industriellen Projekten. Diese Kombination ermöglicht es uns, sowohl für die Forschungswelt als auch für die Industrie den richtigen Ansprechpartner zu sein.
    </p>

    <div class="team-grid" style="margin-top:2.5rem">
      {% for member in site.data.team %}
      <article class="team-card" id="{{ member.name | downcase | replace: ' ', '-' | replace: '.', '' }}">
        <div class="team-card-image">
          <img src="{{ '/assets/images/' | append: member.image | relative_url }}"
               alt="{{ member.name }}"
               loading="lazy"
               width="480" height="360">
        </div>
        <div class="team-card-body">
          <h2 class="team-card-name">{{ member.name }}</h2>
          <p class="team-card-role">{{ member.role }}</p>
          <p class="team-card-role-detail">{{ member.role_detail }}</p>
          <p class="team-card-description">{{ member.description }}</p>
        </div>
      </article>
      {% endfor %}
    </div>

    <div class="info-box" style="margin-top:3rem">
      <p>GetPEC arbeitet je nach Projektanforderung mit einem Netzwerk von Spezialisten zusammen. Durch die enge Anbindung an die TU Darmstadt haben wir Zugang zu aktuellem Forschungswissen und können bei Bedarf zusätzliche Expertise einbinden.</p>
    </div>

    <div style="margin-top:2rem">
      <a href="{{ '/kontakt/' | relative_url }}" class="btn btn-primary">Kontakt aufnehmen</a>
      <a href="{{ '/kurse/grundlagen-waermeuebertragung/' | relative_url }}" class="btn btn-outline" style="margin-left:1rem">Zum Seminar</a>
    </div>

  </div>
</section>
