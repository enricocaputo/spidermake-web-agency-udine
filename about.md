---
layout: page
title: About
excerpt: 'Categoria: web designer, Nome: Enrico Caputo, Descrizione: Enrico Caputo è web designer a Udine, lavora presso Spidermake Web Agency Udine e freelance a Trieste'
permalink: /about-enrico-caputo-web-designer-e-spidermake-web-agency-udine/
sitemap:
  priority: 0.3
---
<blockquote>Insieme dal 2010</blockquote>

<h2>Web agency Udine <br/>e agenzia di comunicazione</h2>

Spidermake ™ da otto anni con successo nel mercato on-line e off-line come digital e web agency e agenzia di comunicazione Udine nella creazione di loghi e promozione online.


## Enrico Caputo è web designer, esperto in SEO

Lavora presso Spidermake Web Agency Udine e freelance a Trieste. Dall'anno 2010 si occupa di realizzare siti web. Realizza siti internet per le piccole e medie aziende a Udine, a Trieste e in tutto il Friuli-Venezia Giulia. Formula proposte altamente personalizzate e offre supporto costante nel tempo.



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
