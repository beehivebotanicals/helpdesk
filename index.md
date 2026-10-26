---
layout: default
---
[comment]: # (Beehive Coding Zone!)
[comment]: # (This is a comment.)
<style>
    .buttons { margin-top: 20px; }
    .buttons a {
        display: inline-block;
        padding: 10px 20px;
        margin: 5px;
        background-color: #4da3ff;
        color: white;
        text-decoration: none;
        border-radius: 5px;
    }
    .buttons a:hover { background-color: #0056b3; }
</style>

<!-- Buttons -->
  <div class="buttons">
      {% for btn in site.buttons %}
          <a href="{{site.url}}/{{site.baseurl}}{{ btn.url }}" target="_blank">{{ btn.text }}</a>
      {% endfor %}
</div>


[comment]:([Link to another page](./another-page.html))


