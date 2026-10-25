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
        background-color: #4da3ff;
        color: white;
        text-decoration: none;
        border-radius: 5px;
    }
    .buttons a:hover { background-color: #0056b3; }

    /* Left-align main content */
    .container {
      text-align: left; /* ensures inline content is left-aligned */
      padding-left: 10px;   /* adjust to your preference */
      padding-right: 10px;
}

</style>

<!-- Buttons -->
  <div class="buttons">
      {% for btn in site.buttons %}
          <a href="{{ btn.url }}" target="_blank">{{ btn.text }}</a>
      {% endfor %}
</div>


[comment]:([Link to another page](./another-page.html))


