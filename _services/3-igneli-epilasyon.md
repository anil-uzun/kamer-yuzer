---
layout: featured

title_tr: İğneli Epilasyon

permalink: hizmetler/igneli-epilasyon

number: 3

categories: [service]
icon: /assets/img/icons/algolia-brands.svg
image: /assets/img/services/03.jpg
---

<div class="row">
    <div class="col-md-12">
        <div class="service-details mb-40">
            <h3>{% translate service_3.header_1 %}</h3>
            <div class="contact-person">
                {% if site.lang == "tr" %}
                <b><a href="/sayfalar/iletisim">
                {% endif %}
                {% if site.lang == "en" %}
                <b><a href="/en/pages/contact">
                {% endif %}
                <span><i class="fas fa-phone"></i>{% translate service_3.btn_1 %}</span></a></b><p></p>
            </div>
            {% translate service_3.text_1 %}
            <h3>{% translate service_3.header_2 %}</h3>
            <div class="contact-person">
                {% if site.lang == "tr" %}
                <b><a href="/sayfalar/iletisim"><span><i class="fas fa-phone"></i>{% translate service_3.btn_1 %}</span></a></b><p></p>
                {% endif %}
                {% if site.lang == "en" %}
                <b><a href="/en/pages/contact"><span><i class="fas fa-phone"></i>{% translate service_3.btn_1 %}</span></a></b><p></p>
                {% endif %}
            </div>
            {% translate service_3.text_2 %}
            <p></p>
        </div>
    </div>
</div>