---
layout: default
---
[comment]:# (Welcome to Beehive HelpDesk!)
[comment]: # (This is a comment.)
<style>
    .buttons { margin-top: 20px; }
    .buttons a {
        display: inline-block;
        padding: 10px 20px;
        margin: 5px;
        background-color: #007BFF;
        color: white;
        text-decoration: none;
        border-radius: 5px;
    }
    .buttons a:hover { background-color: #0056b3; }
</style>

<!-- Buttons -->
  <div class="buttons">
      {% for btn in site.buttons %}
          <a href="{{ btn.url }}" target="_blank">{{ btn.text }}</a>
      {% endfor %}
</div>


[Link to another page](./another-page.html).


