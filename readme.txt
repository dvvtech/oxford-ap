1. в сss c 28
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&subset=cyrillic&display=swap");

2. в css

/*лого друг под другом*/

3. c531
применяем отзыв
.fm-sec2 {
  font-family: "Montserrat", cursive !important;
}

<span class="fm-sec2">
                    АСО Кафедра АП
                </span>    


todo:

1. При открытии меню в мобильной версии не раскрываются подменю. Нужно сделать див с меню чтобы он был поверх всего и за ним не было видно логотипа

Изменил z index в mobile-nav__wrapper чтоб лого было под меню мобильного

Изменил высоту хедера
@media (max-width: 575px) {
  .page_title_banner {
    background: url(../media/banners/page-title-bg.png);
    height: 420px;
  }
}