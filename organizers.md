---
layout: default
---

# Organizers

<p>
{% for person in site.workshop.organizers %}
<a href="mailto:{{ person.email }}">
<div class="item">
    <img class="headshot" src="{{ person.pic }}"/>
    <span class="name">{{ person.name }}<br>{{ person.surname }}</span>
    <span class="affiliation">{{ person.affiliation }}</span>
</div>
</a>
{% endfor %}
</p>

# Program Committee

{% for person in site.workshop.pc %}
* {{ person.name }} ({{person.affiliation }})
{% endfor %}
* ...more coming

<!--<ul>
  <li>Pietro Buzzega (Covision Lab)</li>
  <li>Matthias De Lange (KU Leuven)</li>
  <li>Arthur Douillard (Sorbonne University)</li>
  <li>Sebastian Farquhar (University of Oxford)</li>
  <li>Bartosz Krawczyk (Virginia Commonwealth University)</li>
  <li>Marc Masana (Graz University of Technology)</li>
  <li>Seyed Iman Mirzadeh (Washington State University)</li>
  <li>Gido Van De Ven (Baylor College of Medicine)</li>
  <li>Joost van de Weijer (Universitat Autònoma de Barcelona)</li>
  <li>Johannes von Oswald (ETH Zurich)</li>
  <li>James Smith (Georgia Institute of Technology)</li>
  <li>Mehrdad Farajtabar (Google Deepmind)</li>
  <li>Timothée Lesort (MILA, University of Montreal)</li>
</ul>-->

# Contact

Click on your favorite organizer to contact us for any additional information!
