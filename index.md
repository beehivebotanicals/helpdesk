---
layout: default
---
# Welcome to Beehive HelpDesk!

[comment]: # (This is a comment.)

<!-- Buttons -->
  <div class="buttons">
      {% for btn in site.buttons %}
          <a href="{{ btn.url }}" target="_blank">{{ btn.text }}</a>
      {% endfor %}
</div>

[Link to another page](./another-page.html).


