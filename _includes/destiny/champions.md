{% case include.champ_type %}
{% when "barrier" | lowercase %}{% assign champ_type = "Barrier" %}
{% when "unstop" | lowercase %}{% assign champ_type = "Unstoppable" %}
{% when "overload" | lowercase %}{% assign champ_type = "Overload" %}
{% endcase %}{% unless champ_type == nil %}<img src="../assets/images/destiny/champion_icons/{{champ_type}}_Champion_icon.png" alt="{{champ_type}} Champion" {{include.style}}>{% endunless %}{% unless include.name == nil %} {{champ_type}} {{include.enemy}}{% endunless %}