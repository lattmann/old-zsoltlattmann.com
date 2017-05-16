## Online Tools
[Password](password/) generator and checker

Blank pages: [black](blank/#black), [white](blank/#white), and [blue with hex value](blank/#567890)

## Notes

{% for page in site.pages %}
{% if page.note == true %}
- [{{ page.title }}]({{ page.url }}) -- {{ page.desc }}
{% endif %}
{% endfor %}


## About
[CV](https://drive.google.com/file/d/0B-9qRayMlQDCYW1Ud0lFUW16X3M/view?usp=sharing)
