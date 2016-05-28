---
layout: default
---

#La Battigia#


Osteria, Ristorante, Pizzeria  
{: .desc}

Siamo aperti tutti i giorni per la colazione, il pranzo, gli aperitivi e la cena
{: .normalText .desc}

<div class="social">
<a href="https://twitter.com/share" class="twitter-share-button" data-url="http://www.labattigiasori.it" data-text="Visita" data-lang="it">Tweet</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
<iframe src="//www.facebook.com/plugins/like.php?href=https%3A%2F%2Fwww.facebook.com%2Fpages%2FLa-Battigia-Sori-GE%2F117728135020371&amp;send=false&amp;layout=button_count&amp;width=450&amp;show_faces=false&amp;action=like&amp;colorscheme=light&amp;font&amp;height=21" scrolling="no" frameborder="0" style="border:none; overflow:hidden; width:110px; height:21px;" allowTransparency="true"></iframe>
</div>

------------
{% for page in site.pages reversed %}
{% if page.title contains 'Menu' %}
{% if page.visible%}
<a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a>
{% endif %}
{% endif %}
{% endfor %}
------------
<div class="tour">
<iframe src="https://www.google.com/maps/embed?pb=!1m0!3m2!1sit!2sit!4v1419795601492!6m8!1m7!1s47q1HgAudh0AAAQIt7j12Q!2m2!1d44.37159888407967!2d9.103638629976103!3f134.95219070362683!4f0.6621123189926266!5f0.4000000000000002" width="100%" height="400" frameborder="0" style="border:0"></iframe>
</div>

