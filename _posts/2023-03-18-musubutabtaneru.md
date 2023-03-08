---
title: "東京大学きらら同好会合同誌 結ぶ、束ねる。"
layout: post
description: "東京大学きらら同好会合同誌「結ぶ、束ねる。」の紹介ページです。"
kokuchi: 2023年3月18日（土曜日）ぼっち・ざ・おんりー！にて、東京大学きらら同好会の合同誌「結ぶ、束ねる。」を頒布します。
post-image: "/assets/images/musubutabaneru/main.png"
---

2023年3月18日（土曜日）[ぼっち・ざ・おんりー！](https://bocchitheonly.bufsiz.jp) にて、東京大学きらら同好会の合同誌「結ぶ、束ねる。」を頒布します。

<br>
<div class="columns is-centered is-multiline">
    <div class="column is-one-fifth-desktop is-one-third-tablet">
        <a href="/assets/images/musubutabaneru/cover.png" data-lightbox="cover" data-lightbox-webp="/assets/images/musubutabaneru/cover.webp">
            <picture>
                <source type="image/webp" srcset="/assets/images/musubutabaneru/cover.webp">
                <img src="/assets/images/musubutabaneru/cover.png" alt="結ぶ、束ねる。" style="width: 75%; max-width: 250px">
            </picture>
        </a>
    </div>
    <div class="column is-half">
        {% include book-info-table.html
           title="結ぶ、束ねる。"
           circle="東京大学きらら同好会"
           circle_href="/"
           specification="[TODO]"
           release_date="2023年3月18日"
           booth="2023年3月「ぼっち・ざ・おんりー！」"
           price="1000円（会場）　[TODO]（委託・税込）"
           store="メロンブックス"
           store_href="https://www.melonbooks.co.jp/detail/detail.php?product_id=[TODO]"
           isdn="278-4-535539-02-7"
           isdn_href="https://isdn.jp/2784535539027" %}
    </div>
</div>

<div class="columns is-centered is-multiline">
    {% include button.html
       href="#articles"
       class="is-dark is-rounded has-text-weight-normal"
       icon_name="fa-angle-double-down"
       text="Articles" %}
    {% include button.html
       href="#photographs-and-manga"
       class="is-dark is-rounded has-text-weight-normal"
       icon_name="fa-angle-double-down"
       text="Photographs and Manga" %}
    {% include button.html
       href="#illustrations"
       class="is-dark is-rounded has-text-weight-normal"
       icon_name="fa-angle-double-down"
       text="Illustrations" %}
    {% include button.html
       href="https://www.melonbooks.co.jp/detail/detail.php?product_id=[TODO]"
       blank=true
       class="is-melon is-rounded has-text-weight-normal"
       icon_name="fa-external-link-alt"
       text="メロンブックス" %}
    {% include button.html
       href="https://bocchitheonly.bufsiz.jp/circle_list.html"
       blank=true
       class="is-light is-rounded has-text-weight-normal"
       icon_name="fa-book-open"
       text="ぼっち・ざ・おんりー！ サークルリスト" %}
</div>

## Articles

{% include detail-article.html articles=site.data.musubutabaneru.articles %}

## Photographs and Manga

{% include detail-article.html articles=site.data.musubutabaneru.photos_manga %}

## Illustrations

{% include detail-illust.html illusts=site.data.musubutabaneru.illusts %}