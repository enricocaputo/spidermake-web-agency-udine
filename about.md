---
layout: page
title: About
excerpt: 'Categoria: web designer, Nome: Enrico Caputo, Descrizione: Enrico Caputo è web designer a Udine, lavora presso Spidermake Web Agency Udine e freelance a Trieste'
permalink: /about-enrico-caputo-web-designer-e-spidermake-web-agency-udine/
sitemap:
  priority: 0.51
---
<blockquote>Insieme dal 2010</blockquote>

<h2>Web agency Udine</h2>
<h3>e agenzia di comunicazione</h3>

Spidermake ™ da otto anni con successo nel mercato on-line e off-line come digital e web agency. Agenzia di comunicazione per la creazione di loghi e la promozione online. Realizza siti internet per le piccole e medie aziende a Udine e in tutto il Friuli-Venezia Giulia. Formula proposte altamente personalizzate e offre supporto costante nel tempo.


## Web designer
### SEO specialist

Enrico Caputo collabora con Spidermake Web Agency a Udine. Freelance a Trieste, in tutta Italia e all'estero. Dall'anno 2010 è web designer. Si occupa di promozione online e posizionamento di siti web su motori di ricerca. Esperto, con certificazioni Google AdWords e Google AdSense, in pubblicità dei segmenti desktop e mobile.



<br/>
<div class="post-list">

  <h2 class="page-heading">Posts</h2>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
</div>
