---
layout: default
title: 
  en: About
  el: Ποιοι είμαστε 
description:
  en: Thessaloniki-based Oktagono is dealing with real estate services, finding, selling and renting real estate, business spaces and land.
  el: Η εταιρεία Oktagono με έδρα τη Θεσσαλονίκη δραστηριοποιείται στις μεσιτικές υπηρεσίες, εύρεσης, πώλησης και ενοικίασης ακινήτων, επαγγελματικών χώρων και γης. 
---
<section class="page-sumbit">
  <div class="vertical shadow">
     <div class="container card">
        <div class="">
        <h1>{% t global.title %}</h1>
        <h2>{{ site.subtitle }}</h2>
        <p>{{page.description[site.lang]}}</p>  
        {% translate_file about.md %}
        </div>
    </div>
  </div>
</section>
