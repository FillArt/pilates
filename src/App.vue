<template>
  <div id="app">
    <section class="q-header">
      <div class="q-inner">
        <div class="q-header__bg"></div>
        <div class="q-header__wrapper">
          <div class="q-header__container">
            <div class="q-header__logo">
              <img src="./assets/img/logo.png" />
            </div>
            <div class="q-header__menu" @click="openMenu()"></div>
          </div>
          <div class="q-header__container">
            <div class="q-header__number">
              <p>+7 918 365 07 07</p>
            </div>
          </div>
        </div>
        <div class="q-header__content">
          <div class="q-header__text">
            <div class="q-header__title">
              <p>
                Студия <br />
                пилатеса
              </p>
            </div>
            <div class="q-header__subtitle">
              <p>Твое здоровое тело через 10 занятий</p>
            </div>
            <a class="q-header__button" href="#timetables"
              >Cмотреть расписание</a
            >
          </div>
          <div class="q-header__img">
            <div class="q-header__decor"></div>
            <img src="@/assets/img/girl.png" />
          </div>
        </div>
      </div>
    </section>
    <section id="about" class="q-about">
      <div class="q-inner">
        <div class="q-about__container">
          <div class="q-about__block">
            <div class="q-about__wrapper">
              <span class="q-about__title">О пилатесе</span>
              <p class="q-about__text">
                Пилатес соединяет элементы растяжки с элементами силовой
                тренировки
              </p>
              <p class="q-about__text">
                Комплекс упражнений укрепляет мышцы пресса и спины, улучшает
                гибкость мышц и связок, подвижность суставов и избавляет от
                дискомфорта в позвоночнике
              </p>
              <div class="q-about__link"><a href="#">Подробнее</a></div>
            </div>
          </div>
          <div class="q-about__block">
            <div class="q-about__pack">
              <div class="q-about__decor--1"></div>
              <div class="q-about__decor--2"></div>
              <div class="q-about__decor--3"></div>
              <div class="q-about__decor--4"></div>
              <div class="q-about__decor--5"></div>
              <div class="q-about__decor--6"></div>
              <div class="q-about__decor--7"></div>
              <div class="q-about__decor--8"></div>
              <div class="q-about__decor--9"></div>
              <div class="q-about__decor--10"></div>
              <div class="q-about__decor--11"></div>
            </div>
            <div class="q-about__photo">
              <img
                class="q-about__img--first"
                src="./assets/img/about-first.png"
              /><img
                class="q-about__img--second"
                src="./assets/img/about-second.png"
              />
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="q-menu">
      <div class="q-inner">
        <img
          class="q-menu__close"
          src="./assets/img/close.png"
          @click="closeMenu()"
        />
        <nav id="menu">
          <ul class="q-menu__list">
            <li style="position: relative">
              <div class="active"></div>
              <a href="#about">О пилатесе</a>
            </li>
            <li>
              <a @click="closeMenu()" href="#timetables"
                >Расписание и стоимость</a
              >
            </li>
            <li>
              <a @click="closeMenu()" href="#occupation"
                >Как проходят занятия</a
              >
            </li>
            <li><a @click="closeMenu()" href="#reviews">Отзывы</a></li>
            <li><a @click="closeMenu()" href="#contacts">Контакты</a></li>
          </ul>
        </nav>
      </div>
    </section>

    <section id="occupation" class="q-plan">
      <div class="q-inner">
        <span class="q-plan__title">Как проходят занятия</span>
        <div class="q-plan__container">
          <div class="q-plan__block">
            <div class="q-plan__block--work">
              <span class="q-plan__block--title">Дыхательные техники</span>
              <div class="q-plan__block--text">
                Специальные дыхательные упражнения помогут сконцентрировать
                внимание и сфокусировать сознание на мышцах тела
              </div>
            </div>
          </div>
          <div class="q-plan__block">
            <div class="q-plan__block--wrapper">
              <div class="q-plan__block--circle">
                <div class="q-plan__pack">
                  <div class="q-plan__decor--1"></div>
                  <div class="q-plan__decor--2"></div>
                  <div class="q-plan__decor--3"></div>
                  <div class="q-plan__decor--4"></div>
                  <div class="q-plan__decor--5"></div>
                  <div class="q-plan__decor--6"></div>
                  <div class="q-plan__decor--7"></div>
                  <div class="q-plan__decor--8"></div>
                  <div class="q-plan__decor--9"></div>
                  <div class="q-plan__decor--10"></div>
                  <div class="q-plan__decor--11"></div>
                </div>
              </div>
              <img class="q-plan__block--img" src="./assets/img/1-plan.png" />
            </div>
          </div>
        </div>
        <div class="q-plan__container">
          <div class="q-plan__block">
            <div class="q-plan__block--work">
              <span class="q-plan__block--title">Разминка</span>
              <div class="q-plan__block--text">
                Перед началом занятия разогревам тело: проработываем мышцы
                спины, шеи, выполняем упражнения на баланс под спокойную музыку.
              </div>
            </div>
          </div>
          <div class="q-plan__block">
            <div class="q-plan__block--wrapper">
              <div class="q-plan__block--bagel"></div>
              <img
                class="q-plan__block--img test"
                src="./assets/img/2-plan.png"
              />
            </div>
          </div>
        </div>
        <div class="q-plan__container">
          <div class="q-plan__block">
            <div class="q-plan__block--work">
              <span class="q-plan__block--title">Основной блок</span>
              <div class="q-plan__block--text">
                Упражнения выполняются лёжа на коврике без оборудования или с
                малым оборудованием, в медленном темпе
              </div>
            </div>
          </div>
          <div class="q-plan__block">
            <div class="q-plan__block--wrapper">
              <div class="q-plan__block--circle">
                <div class="q-plan__pack">
                  <div class="q-plan__decor--1"></div>
                  <div class="q-plan__decor--2"></div>
                  <div class="q-plan__decor--3"></div>
                  <div class="q-plan__decor--4"></div>
                  <div class="q-plan__decor--5"></div>
                  <div class="q-plan__decor--6"></div>
                  <div class="q-plan__decor--7"></div>
                  <div class="q-plan__decor--8"></div>
                  <div class="q-plan__decor--9"></div>
                  <div class="q-plan__decor--10"></div>
                  <div class="q-plan__decor--11"></div>
                </div>
              </div>
              <img class="q-plan__block--img" src="./assets/img/3-plan.png" />
            </div>
          </div>
        </div>
        <div class="q-plan__container">
          <div class="q-plan__block">
            <div class="q-plan__block--work">
              <span class="q-plan__block--title">Стрейчинг</span>
              <div class="q-plan__block--text">
                В конце занятия выполняем специальные упражнения для развития
                гибкости, снятия усталости, стресса и мышечного
              </div>
            </div>
          </div>
          <div class="q-plan__block">
            <div class="q-plan__block--wrapper">
              <div class="q-plan__block--bagel"></div>
              <img class="q-plan__block--img" src="./assets/img/4-plan.png" />
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="reviews" class="q-review">
      <div class="q-inner">
        <span class="q-review__title"> Отзывы</span>
        <div class="q-review__slider">
          <slick ref="slick" :options="slickOptions">
            <div class="q-review__container">
              <div class="q-review__pack">
                <div class="q-review__decor--1"></div>
                <div class="q-review__decor--2"></div>
                <div class="q-review__decor--3"></div>
                <div class="q-review__decor--4"></div>
                <div class="q-review__decor--5"></div>
                <div class="q-review__decor--6"></div>
                <div class="q-review__decor--7"></div>
                <div class="q-review__decor--8"></div>
                <div class="q-review__decor--9"></div>
                <div class="q-review__decor--10"></div>
                <div class="q-review__decor--11"></div>
              </div>
              <div class="q-review__container--img">
                <img src="./assets/img/feedback.png" />
              </div>
              <div class="q-review__container--box">
                <span class="q-review__container--name">Вероника Кулешова</span>
                <ul class="q-review__container--list">
                  <li><span>25 лет</span></li>
                  <li>
                    <a href="#">
                      <img class="q-review__icon" src="./assets/img/vk-logo.svg"
                    /></a>
                  </li>
                  <li>
                    <a href="#">
                      <img
                        class="q-review__icon"
                        src="./assets/img/instagram.svg"
                      />
                    </a>
                  </li>
                </ul>
                <div class="q-review__container--text">
                  <p>
                    Хожу на пилатес уже пять месяцев. <br />
                    После десяти занятий уже увидела результат: тело
                    подтянулось, улучшилась осанка, появился пресс. <br />
                    И самое главное, пропал сильный изгиб
                  </p>
                </div>
              </div>
            </div>
            <div class="q-review__container">
              <div class="q-review__pack">
                <div class="q-review__decor--1"></div>
                <div class="q-review__decor--2"></div>
                <div class="q-review__decor--3"></div>
                <div class="q-review__decor--4"></div>
                <div class="q-review__decor--5"></div>
                <div class="q-review__decor--6"></div>
                <div class="q-review__decor--7"></div>
                <div class="q-review__decor--8"></div>
                <div class="q-review__decor--9"></div>
                <div class="q-review__decor--10"></div>
                <div class="q-review__decor--11"></div>
              </div>
              <div class="q-review__container--img">
                <img src="./assets/img/feedback.png" />
              </div>
              <div class="q-review__container--box">
                <span class="q-review__container--name">Вероника Кулешова</span>
                <ul class="q-review__container--list">
                  <li><span>25 лет</span></li>
                  <li>
                    <a href="#">
                      <img class="q-review__icon" src="./assets/img/vk-logo.svg"
                    /></a>
                  </li>
                  <li>
                    <a href="#">
                      <img
                        class="q-review__icon"
                        src="./assets/img/instagram.svg"
                      />
                    </a>
                  </li>
                </ul>
                <div class="q-review__container--text">
                  <p>
                    Хожу на пилатес уже пять месяцев. <br />
                    После десяти занятий уже увидела результат: тело
                    подтянулось, улучшилась осанка, появился пресс. <br />
                    И самое главное, пропал сильный изгиб
                  </p>
                </div>
              </div>
            </div>
            <div class="q-review__container">
              <div class="q-review__pack">
                <div class="q-review__decor--1"></div>
                <div class="q-review__decor--2"></div>
                <div class="q-review__decor--3"></div>
                <div class="q-review__decor--4"></div>
                <div class="q-review__decor--5"></div>
                <div class="q-review__decor--6"></div>
                <div class="q-review__decor--7"></div>
                <div class="q-review__decor--8"></div>
                <div class="q-review__decor--9"></div>
                <div class="q-review__decor--10"></div>
                <div class="q-review__decor--11"></div>
              </div>
              <div class="q-review__container--img">
                <img src="./assets/img/feedback.png" />
              </div>
              <div class="q-review__container--box">
                <span class="q-review__container--name">Вероника Кулешова</span>
                <ul class="q-review__container--list">
                  <li><span>25 лет</span></li>
                  <li>
                    <a href="#">
                      <img class="q-review__icon" src="./assets/img/vk-logo.svg"
                    /></a>
                  </li>
                  <li>
                    <a href="#">
                      <img
                        class="q-review__icon"
                        src="./assets/img/instagram.svg"
                      />
                    </a>
                  </li>
                </ul>
                <div class="q-review__container--text">
                  <p>
                    Хожу на пилатес уже пять месяцев. <br />
                    После десяти занятий уже увидела результат: тело
                    подтянулось, улучшилась осанка, появился пресс. <br />
                    И самое главное, пропал сильный изгиб
                  </p>
                </div>
              </div>
            </div>
          </slick>
        </div>
      </div>
    </section>
    <section id="contacts" class="q-map">
      <div class="q-inner">
        <span class="q-map__title">Контакты</span>
      </div>
      <div class="q-map__container">
        <div class="q-inner">
          <div class="q-map__contact">
            <ul class="q-map__contact--list">
              <li>
                <strong>Адрес</strong>
                <span>г. Кропоткин ул. Дугинец 10а</span>
              </li>
              <li>
                <strong>Телефон</strong>
                <span>+7 918 365 06 07</span>
              </li>
              <li>
                <strong>E-mail</strong>
                <span style="text-decoration: underline"
                  >pilatesplus@gmail.com</span
                >
              </li>
            </ul>
          </div>
        </div>
        <iframe
          src="https://snazzymaps.com/embed/183854"
          width="100%"
          style="border:none;padding: 0 1px"
        ></iframe>
      </div>
    </section>
    <section class="q-footer">
      <div class="q-inner">
        <div class="q-footer__container">
          <div class="q-footer__item">
            <div class="q-footer__wrapper">
              <span>Pilates Plus, 2017 &copy;</span>
            </div>
          </div>
          <div class="q-footer__item">
            <img style="opacity: 1" src="./assets/img/logo.png" />
          </div>
          <div class="q-footer__item">
            <div class="q-footer__wrapper">
              <a href="#"><img src="./assets/img/vk-footer.svg"/></a>
              <a href="#"><img src="./assets/img/facebook-footer.svg"/></a>
              <a href="#"><img src="./assets/img/instagram-footer.svg"/></a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Slick from "vue-slick";
export default {
  name: "app",
  components: { Slick },
  data() {
    return {
      menu: false,
      map,
      slickOptions: {
        dots: true,
        infinite: true,
        autoplay: true,
        speed: 500,
        fade: false,
        cssEase: "linear"
      }
    };
  },
  methods: {
    openMenu() {
      this.menu = true;
      document.querySelector(".q-menu").classList.toggle("open");
      document.getElementById("app").style.overflow = "hidden";
      document.getElementById("app").style.position = "fixed";
    },
    closeMenu() {
      this.menu = false;
      document.querySelector(".q-menu").classList.remove("open");
      document.getElementById("app").style.overflow = "visible";
      document.getElementById("app").style.position = "static";
    },
    openMenuPrice() {
      document.querySelector(".q-price__modal").classList.toggle("open");
    },
    closeMenuPrice() {
      document.querySelector(".q-price__modal").classList.remove("open");
    },
    initMap() {
      this.map = new google.maps.Map(document.getElementById("map"), {
        center: { lat: -34.397, lng: 150.644 },
        zoom: 8
      });
    },
    next() {
      this.$refs.slick.next();
    },

    prev() {
      this.$refs.slick.prev();
    }
  }
};
</script>

<style lang="less">
@import "./../node_modules/slick-carousel/slick/slick.css";
@import "./styles/normalize.css";
@import "./styles/mixin.less";

.clear() {
  content: "";
  display: table;
  clear: both;
}
.btn-hover() {
  &:hover {
    background: #87008a;
  }
}
html,
body {
  height: 100%;
}
body {
  background: @white-bg;
  font: 16px "Roboto", sans-serif;
  font-weight: 300;
  color: @main-text-color;
}
.q-inner {
  width: 100%;
  max-width: 1150px;
  padding: 0 20px;
  margin: 0 auto;
}
.open {
  display: block !important;
}
/* Q-header начало*/
.q-header {
  position: relative;
  padding-left: 20px;
  padding-right: 20px;
  padding-bottom: 90px;
  overflow-x: hidden;
  overflow-y: hidden;
  margin-bottom: 135px;
  &__bg {
    position: relative;
    &:after {
      content: "";
      display: block;
      position: absolute;
      top: -450px;
      left: -900px;
      z-index: -99;
      background-color: @green-bg;
      border-radius: 50%;
      width: 1550px;
      height: 1220px;
    }
  }
  &__wrapper {
    display: flex;
  }
  &__container {
    display: flex;
    padding-top: 30px;
    justify-content: space-between;
    width: 50%;
    &:first-child {
      padding-bottom: 142px;
    }
  }
  &__menu {
    padding-top: 15px;
    position: relative;
    width: 23px;
    height: 16px;
    border-bottom: 2px solid white;
    cursor: pointer;
    z-index: 10;
    &:after {
      content: "";
      position: absolute;
      top: 9px;
      display: block;
      width: 23px;
      height: 2px;
      background-color: white;
    }
    &:before {
      content: "";
      position: absolute;
      display: block;
      width: 17px;
      top: 3px;
      height: 2px;
      background-color: white;
    }
  }
  &__number {
    width: 100%;
    text-align: right;
    font-size: 14px;
    font-weight: 900;
    padding-top: 10px;
    letter-spacing: 1px;
    float: left;
  }
  &__content {
    display: flex;
    border: 0px solid red;
  }
  &__text {
    width: 50%;
    color: @white-text-color;
  }
  &__title {
    text-transform: uppercase;
    font-size: 58px;
    font-weight: 300;
    letter-spacing: 3px;
    padding-bottom: 41px;
  }
  &__subtitle {
    font-size: 18px;
    font-weight: 300;
    padding-bottom: 51px;
  }
  &__button {
    display: inline-block;
    position: relative;
    padding: 20px 45px;
    border: 2px solid @border-color-white;
    border-radius: 30px;
    max-width: 400px;
    color: @white-text-color;
    text-decoration: none;
    &:before {
      content: "";
      position: absolute;
      display: block;
      background-image: url("./assets/img/arrow.png");
      width: 72px;
      height: 12px;
      //left: 220px;
      //top: 23px;
      top: 40%;
      left: 90%;
    }
    &:hover {
      background-color: @white-bg;
      color: @green-text-color;
    }
  }
  &__img {
    position: relative;
    width: 50%;
    &:after {
      content: "";
      position: absolute;
      border-radius: 50%;
      z-index: -1;
      top: -100px;
      right: 16px;
      display: block;
      width: 60px;
      height: 60px;
      background-color: @second-bg;
    }
    &:before {
      content: "";
      position: absolute;
      display: block;
      border-radius: 50%;
      border: 10px solid @second-bg;
      //right: -150px;
      right: -25%;
      top: -200px;
      width: 56px;
      height: 56px;
    }
    & img {
      position: absolute;
      max-width: 200%;
      top: -205px;
      left: -250px;
    }
  }
  &__decor {
    position: relative;
    border-radius: 50%;
    top: -20px;
    left: 120px;
    width: 455px;
    height: 455px;
    background-color: @second-bg;
  }
}
@media screen and (max-width: 992px) {
  .q-header {
    padding-bottom: 150px;
    &__bg {
      &:after {
        left: -1000px;
        top: -480px;
      }
    }
    padding-bottom: 210px;
    &__decor {
      display: none;
    }
    &__img {
      z-index: -9;
      & img {
        top: -140px;
      }
    }
    &__title {
      font-size: 48px;
    }
    &__subtitle {
      font-size: 16px;
    }
    &__img img {
      top: -100px;
      width: 170%;
    }
  }
}
@media screen and (max-width: 760px) {
  .q-header {
    padding-bottom: 250px;
    &__bg {
      &:after {
        left: -800px;
        top: -750px;
      }
    }
    &__container {
      &:first-child {
        padding-bottom: 45px;
        width: 100%;
      }
      &:nth-child(2) {
        display: none;
      }
    }
    &__content {
      display: block;
      position: relative;
      margin: 0 auto;
    }
    &__subtitle {
      display: none;
    }
    &__title {
      font-size: 30px;
      padding-bottom: 30px;
    }
    &__button {
      font-size: 11px;
      padding: 12px;
      &:hover {
        font-weight: 300;
      }
      &:before {
        display: none;
      }
    }
    &__img {
      transform: scale(-1, 1);
      margin-top: 70px;
      margin-left: 50px;
      &:after {
        content: "";
        position: absolute;
        border-radius: 50%;
        z-index: -1;
        top: -160px;
        right: 286px;
        display: block;
        width: 50px;
        height: 50px;
        background-color: @second-bg;
      }
      &:before {
        content: "";
        position: absolute;
        display: block;
        border-radius: 50%;
        border: 6px solid @second-bg;
        //right: -150px;
        left: -60%;
        top: -230px;
        width: 15px;
        height: 15px;
      }
      & img {
        position: absolute;
        top: -200px;
        left: -300px;
        min-width: 500px;
        &:before {
          display: none;
        }
      }
    }
  }
}
/* Q-header конец */

/* Q-about начало */
.q-about {
  //border: 1px solid green;
  padding-bottom: 350px;
  &__container {
    display: flex;
    margin-left: 15px;
  }
  &__block {
    position: relative;
    width: 50%;
  }
  &__wrapper {
    padding-right: 180px;
  }
  &__title {
    position: relative;
    display: block;
    line-height: 30px;
    margin-bottom: 60px;
    font-size: 45px;
    font-weight: 500;
    color: #212121;
    padding-left: 58px;
    &:before {
      content: "";
      display: block;
      position: absolute;
      top: 50%;
      left: 0;
      width: 37px;
      height: 2px;
      background-color: #212121;
    }
  }
  &__text {
    font-size: 17px;
    color: #212121;
    line-height: 25px;
    padding-bottom: 41px;
  }
  &__link a {
    font-size: 14px;
    position: relative;
    display: block;
    max-width: 150px;
    font-weight: 500;
    text-transform: uppercase;
    text-decoration: none;
    letter-spacing: 1px;
    color: #2a4f37;
    padding-right: 20px;
    box-sizing: border-box;
    &:after {
      content: "";
      display: block;
      position: absolute;
      top: 10%;
      left: 70%;
      width: 8px;
      height: 13px;
      background-image: url("./assets/img/arr.png");
    }
  }
  &__img {
    &--first {
      position: absolute;
      width: 100%;
      //top: -30px;
      bottom: -200px;
    }
    &--second {
      position: absolute;
      left: -200px;
      bottom: -250px;
    }
  }
  &__pack {
    position: relative;
    left: -110px;
    top: 170px;
    width: 134px;
    height: 134px;
  }
  &__decor {
    &--1 {
      position: absolute;
      left: 40px;
      width: 15px;
      height: 15px;
      border-radius: 50%;
      background-color: @second-bg;
    }
    &--2 {
      position: absolute;
      left: 68px;
      top: 2px;
      width: 13px;
      height: 13px;
      border-radius: 50%;
      background-color: @green-bg;
    }
    &--3 {
      position: absolute;
      width: 15px;
      height: 15px;
      border-radius: 50%;
      top: 40px;
      left: 10px;
      background-color: @green-bg;
    }
    &--4 {
      position: absolute;
      width: 13px;
      height: 13px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 40px;
      left: 40px;
    }
    &--5 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 35px;
      left: 65px;
    }
    &--6 {
      position: absolute;
      width: 18px;
      height: 18px;
      border-radius: 50%;
      box-sizing: border-box;
      border: 6px solid @second-bg;
      top: 37px;
      left: 100px;
    }
    &--7 {
      position: absolute;
      width: 15px;
      height: 15px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 75px;
      left: 40px;
    }
    &--8 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 72px;
      left: 66px;
    }
    &--9 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 72px;
      left: 100px;
    }
    &--10 {
      position: absolute;
      width: 13px;
      height: 13px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 112px;
      left: 41px;
    }
    &--11 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      box-sizing: border-box;
      border: 5px solid @second-bg;
      top: 108px;
      left: 66px;
    }
  }
}
@media screen and (max-width: 992px) {
  .q-about {
    &__title {
      font-size: 25px;
      margin-bottom: 40px;
    }
    &__pack {
      display: none;
    }
    &__title {
      margin-bottom: 40px;
    }
    &__wrapper {
      padding-right: 60px;
    }
    &__text {
      font-size: 16px;
      padding-bottom: 28px;
    }
    &__img {
      &--first {
        width: 85%;
        bottom: -125px;
        min-height: 300px;
        min-width: 300px;
      }
      &--second {
        width: 35%;
        left: -85px;
        bottom: -145px;
        min-height: 171px;
        min-width: 171px;
      }
    }
  }
}
@media screen and (max-width: 760px) {
  .q-about {
    padding-bottom: 200px;
    &__wrapper {
      padding-right: 6px;
    }
    &__container {
      flex-direction: column;
    }
    &__block {
      width: 100%;
    }
    &__photo {
      position: relative;
      text-align: right;
    }
    &__title {
      font-size: 18px;
      margin-bottom: 20px;
    }
    &__img {
      &--first {
        position: relative;
        bottom: -5px;
        min-width: 200px;
        min-height: 200px;
        max-width: 450px;
        max-height: 450px;
      }
      &--second {
        width: 40%;
        min-height: 150px;
        min-width: 150px;
        left: -11px;
        bottom: -45px;
      }
    }
    &__text {
      font-size: 14px;
      padding-bottom: 18px;
      line-height: 20px;
    }
  }
}
/* Q-about конец */

/* Q-price начало */
.q-price {
  padding-bottom: 150px;
  &__wrapper {
    position: relative;
    max-width: 1150px;
    width: 100%;
  }
  &__modal {
    display: none;
    position: absolute;
    top: -10px;
    //box-sizing: border-box;
    z-index: 999;
    box-sizing: border-box;
    background-color: white;
    padding: 150px 145px 100px 145px;
    width: 100%;
    box-shadow: 0px 9px 32px rgba(27, 27, 27, 0.2);
    &--close {
      cursor: pointer;
      position: absolute;
      top: 50px;
      right: 70px;
    }
    input[type="checkbox"] {
      display: none;
    }
    input[type="checkbox"]:checked + label::before {
      width: 20px;
      height: 20px;
      background-size: 65px;
      background-color: @green-bg;
    }
    &--label {
      font-size: 18px;
      &::before {
        position: relative;
        top: 3px;
        content: "";
        display: inline-block;
        width: 20px;
        height: 20px;
        border: thin solid #dde1e3;
        margin-right: 25px;
      }
    }
    &--button {
      margin-top: -15px;
      display: inline-block;
      border: none;
      padding: 18px 70px;
      border-radius: 27px;
      background-color: #91a959;
      font-size: 18px;
      color: white;
      cursor: pointer;
      &:hover {
        color: antiquewhite;
      }
    }
    &--title {
      display: block;
      text-align: center;
      font-size: 48px;
      margin-bottom: 35px;
      font-weight: bold;
    }
    &--subtitle {
      display: block;
      font-size: 18px;
      color: rgb(17, 17, 17);
      margin-bottom: 60px;
      text-align: center;
    }
    &--container {
      display: flex;
      justify-content: space-between;
      margin-bottom: 100px;
    }
    &--text {
      font-family: "Roboto", sans-serif;
      border: none;
      margin-right: 10px;
      padding: 15px 0;
      border-bottom: 2px solid #a3a3a3;
      font-size: 16px;
      color: rgb(17, 17, 17);
    }
  }
  &__button {
    cursor: pointer;
    display: inline-block;
    margin-top: 20px;
    position: relative;
    padding: 15px 45px;
    border: 2px solid @border-color-white;
    border-radius: 30px;
    font-size: 18px;
    max-width: 400px;
    color: @white-text-color;
    text-decoration: none;
    &:before {
      content: "";
      position: absolute;
      display: block;
      background-image: url("./assets/img/arrow.png");
      width: 72px;
      height: 12px;
      //left: 220px;
      //top: 23px;
      top: 40%;
      left: 90%;
    }
    &:hover {
      background-color: @white-bg;
      //font-weight: 900;
      color: @green-text-color;
    }
  }
  &__title {
    position: relative;
    display: block;
    line-height: 30px;
    margin-bottom: 60px;
    font-size: 45px;
    font-weight: 500;
    color: #212121;
    padding-left: 58px;
    &:before {
      content: "";
      display: block;
      position: absolute;
      top: 50%;
      left: 0;
      width: 37px;
      height: 2px;
      background-color: #212121;
    }
  }
  &__container {
    display: flex;
    justify-content: space-between;
    min-height: 100px;
  }
  &__block {
    width: 33.33%;
    position: relative;
    padding-top: 190px;
    margin-right: 20px;
    max-width: 375px;
    padding-bottom: 95px;
    padding-left: 71px;
    padding-right: 67px;
    background-color: #c8d4ac;
    border-radius: 5px;
    &--subtitle {
      display: block;
      font-size: 14px;
      color: white;
      text-transform: uppercase;
    }
    &--title {
      display: block;
      font-size: 28px;
      font-weight: 500;
      padding-bottom: 30px;
      text-transform: uppercase;
      letter-spacing: 2px;
      color: white;
    }
    &--decor {
      font-size: 210px;
      font-weight: 900;
      color: white;
      opacity: 0.1;
      top: 60px;
      position: absolute;
      right: 50px;
    }
    &--learn {
      display: block;
      padding-bottom: 40px;
      font-size: 24px;
      color: white;
      font-weight: 500;
    }
    &--wrapper {
      color: white;
      padding-bottom: 13px;
      font-size: 18px;
      &:last-child {
        padding-bottom: 45px;
      }
    }
    &--day {
      display: inline-block;
      padding-right: 20px;
    }
    &:nth-child(2) {
      background-color: #b2c38a;
    }
    &:last-child {
      margin-right: 0;
      background-color: #9cb269;
    }
  }
}
@media screen and (max-width: 1098px) {
  .q-price {
    &__modal {
      padding: 125px 35px 100px 35px;
      & .q-inner {
        padding: 0;
      }
      &--title {
        font-size: 30px;
        margin-bottom: 28px;
      }
      &--subtitle {
        margin-bottom: 30px;
      }
      &--container {
        margin-bottom: 60px;
      }
      &--close {
        width: 5%;
        top: 40px;
        right: 40px;
      }
      &--label {
        font-size: 14px;
      }
      &--button {
        font-size: 14px;
        padding: 10px 33px;
        margin-top: 0;
      }
      &--text {
        margin-right: 20px;
      }
    }
  }
}
@media screen and (max-width: 992px) {
  .q-price {
    margin-left: 10px;
    margin-right: 10px;
    &__title {
      font-size: 25px;
    }
    &__button {
      padding: 10px 25px;
      &:before {
        content: none;
      }
    }
    &__block {
      padding-top: 105px;
      padding-left: 20px;
      padding-bottom: 41px;
      &--decor {
        font-size: 115px;
        top: 25px;
      }
      &--wrapper {
        font-size: 16px;
      }
      &--subtitle {
        font-size: 12px;
      }
      &--title {
        font-size: 18px;
        padding-bottom: 20px;
      }
      &--learn {
        font-size: 16px;
        padding-bottom: 24px;
      }
    }
  }
}
@media screen and (max-width: 768px) {
  .q-price {
    padding-bottom: 150px;
    &__modal {
      padding: 50px 17px;
      &--label::before {
        margin-right: 25px;
        width: 27px;
      }
      &--title {
        font-size: 24px;
      }
      &--container {
        flex-direction: column;
        margin-bottom: 20px;
      }
      &--mobile {
        margin-bottom: 30px;
      }
      &--button {
        margin: 0 auto;
        max-width: 151px;
      }
      &--text {
        margin-bottom: 20px;
        margin-right: 0;
      }
      &--subtitle {
        font-size: 14px;
      }
      &--close {
        width: 25px;
        top: 15px;
        right: 15px;
      }
      &--label {
        display: inline-flex;
      }
    }
    &__title {
      font-size: 18px;
      margin-bottom: 20px;
    }
    &__container {
      flex-wrap: wrap;
      justify-content: space-between;
    }
    &__block {
      width: 48%;
      margin-bottom: 30px;
      margin-right: 0;
    }
  }
}
@media screen and (max-width: 500px) {
  .q-price {
    &__block {
      padding-top: 85px;
      padding-left: 52px;
      width: 100%;
      max-width: none;
    }
  }
}
/* Q-price конец */

/* Q-plan начало */
.q-plan {
  margin-bottom: 100px;
  & .q-inner {
    padding: 0 10px;
  }
  &__title {
    position: relative;
    display: block;
    line-height: 30px;
    margin-bottom: 60px;
    font-size: 45px;
    font-weight: 500;
    color: #212121;
    padding-left: 58px;
    &:before {
      content: "";
      display: block;
      position: absolute;
      top: 50%;
      left: 0;
      width: 37px;
      height: 2px;
      background-color: #212121;
    }
  }
  &__container {
    display: flex;
    margin-bottom: 50px;
    &:nth-child(odd) {
      flex-direction: row-reverse;
    }
  }
  &__block {
    width: 50%;
    margin-bottom: 50px;
    &--work {
      position: relative;
      top: 30%;
      padding-left: 15px;
      padding-right: 15px;
    }
    &--circle {
      position: absolute;
      width: 372px;
      height: 372px;
      background-color: #91a959;
      border-radius: 50%;
      opacity: 0.5;
      //left: 20%;
      bottom: 50px;
      z-index: -5;
    }
    &--bagel {
      position: absolute;
      width: 462px;
      height: 462px;
      border: 44px solid #91a959;
      box-sizing: border-box;
      z-index: -5;
      opacity: 0.5;
      border-radius: 50%;
    }
    &--wrapper {
      position: relative;
      //text-align: center;
    }
    &--title {
      display: block;
      font-size: 28px;
      padding-bottom: 30px;
      color: #242424;
    }
    &--text {
      max-width: 400px;
      font-size: 16px;
      line-height: 22px;
    }
  }
  &__pack {
    position: relative;
    left: 260px;
    z-index: 1;
    top: -100px;
    width: 134px;
    height: 134px;
  }
  &__decor {
    &--1 {
      position: absolute;
      left: 40px;
      width: 15px;
      height: 15px;
      border-radius: 50%;
      background-color: @second-bg;
    }
    &--2 {
      position: absolute;
      left: 68px;
      top: 2px;
      width: 13px;
      height: 13px;
      border-radius: 50%;
      background-color: @green-bg;
    }
    &--3 {
      position: absolute;
      width: 15px;
      height: 15px;
      border-radius: 50%;
      top: 40px;
      left: 10px;
      background-color: @green-bg;
    }
    &--4 {
      position: absolute;
      width: 13px;
      height: 13px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 40px;
      left: 40px;
    }
    &--5 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 35px;
      left: 65px;
    }
    &--6 {
      position: absolute;
      width: 18px;
      height: 18px;
      border-radius: 50%;
      box-sizing: border-box;
      border: 6px solid @second-bg;
      top: 37px;
      left: 100px;
    }
    &--7 {
      position: absolute;
      width: 15px;
      height: 15px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 75px;
      left: 40px;
    }
    &--8 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 72px;
      left: 66px;
    }
    &--9 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 72px;
      left: 100px;
    }
    &--10 {
      position: absolute;
      width: 13px;
      height: 13px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 112px;
      left: 41px;
    }
    &--11 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      box-sizing: border-box;
      border: 5px solid @second-bg;
      top: 108px;
      left: 66px;
    }
  }
}
.test {
  margin-top: -100px;
}
@media screen and (max-width: 992px) {
  .q-plan {
    &__title {
      font-size: 25px;
    }
    &__pack {
      display: none;
    }
    &__block {
      &--circle {
        width: 300px;
        height: 300px;
        bottom: 25px;
      }
      &--bagel {
        width: 300px;
        height: 300px;
      }
      &--img {
        max-width: 90%;
      }
      &--title {
        font-size: 16px;
        padding-bottom: 25px;
      }
      &--text {
        max-width: 315px;
      }
    }
  }
}
@media screen and (max-width: 768px) {
  .q-plan {
    &__title {
      font-size: 18px;
    }
    &__container {
      flex-direction: column-reverse;
      &:nth-child(odd) {
        flex-direction: column-reverse;
      }
    }
    &__block {
      width: 100%;
      text-align: center;
      &--text {
        margin: 0 auto;
        max-width: 100%;
      }
      &--circle {
        display: none;
      }
      &--bagel {
        display: none;
      }
    }
  }
  .test {
    margin-top: 0;
    max-width: 50%;
  }
}
@media screen and (max-width: 500px) {
  .q-plan {
    &__block {
      &--title {
        font-size: 14px;
        padding-bottom: 20px;
      }
      &--text {
        font-size: 14px;
      }
    }
  }
}
/* Q-plan конец */

/* Q-review начало*/
.q-review {
  margin-bottom: 160px;
  &__slider {
    position: relative;
    max-width: 963px;
    box-shadow: 0 9px 32px rgba(33, 33, 33, 0.07);
    margin: 0 auto;
  }
  &__pack {
    position: absolute;
    opacity: 0.7;
    right: 10%;
    top: 40px;
    z-index: 1;
    width: 134px;
    height: 134px;
  }
  &__decor {
    position: relative;
    left: 560px;
    z-index: 1;
    top: -100px;
    width: 134px;
    height: 134px;
    &--1 {
      position: absolute;
      left: 40px;
      width: 15px;
      height: 15px;
      border-radius: 50%;
      background-color: @second-bg;
    }
    &--2 {
      position: absolute;
      left: 68px;
      top: 2px;
      width: 13px;
      height: 13px;
      border-radius: 50%;
      background-color: @green-bg;
    }
    &--3 {
      position: absolute;
      width: 15px;
      height: 15px;
      border-radius: 50%;
      top: 40px;
      left: 10px;
      background-color: @green-bg;
    }
    &--4 {
      position: absolute;
      width: 13px;
      height: 13px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 40px;
      left: 40px;
    }
    &--5 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 35px;
      left: 65px;
    }
    &--6 {
      position: absolute;
      width: 18px;
      height: 18px;
      border-radius: 50%;
      box-sizing: border-box;
      border: 6px solid @second-bg;
      top: 37px;
      left: 100px;
    }
    &--7 {
      position: absolute;
      width: 15px;
      height: 15px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 75px;
      left: 40px;
    }
    &--8 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 72px;
      left: 66px;
    }
    &--9 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 72px;
      left: 100px;
    }
    &--10 {
      position: absolute;
      width: 13px;
      height: 13px;
      border-radius: 50%;
      background-color: @green-bg;
      top: 112px;
      left: 41px;
    }
    &--11 {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      box-sizing: border-box;
      border: 5px solid @second-bg;
      top: 108px;
      left: 66px;
    }
  }
  &__title {
    position: relative;
    display: block;
    line-height: 30px;
    margin-bottom: 60px;
    font-size: 45px;
    font-weight: 500;
    color: #212121;
    padding-left: 58px;

    &:before {
      content: "";
      display: block;
      position: absolute;
      top: 50%;
      left: 0;
      width: 37px;
      height: 2px;
      background-color: #212121;
    }
  }
  &__container {
    display: flex !important;
    position: relative;
    padding: 72px 92px;
    max-width: 100%;
    &--img {
      width: 25%;
      min-width: 180px;
      text-align: center;
    }
    &--box {
      width: 85%;
      padding-left: 50px;
    }
    &--name {
      display: block;
      font-size: 28px;
      padding-bottom: 15px;
    }
    &--list {
      display: flex;
      flex-direction: row;
      padding-bottom: 15px;
      width: 100%;
      & li {
        display: block;
        padding-right: 10px;
        font-size: 18px;
      }
    }
    &--text {
      max-width: 380px;
      font-size: 16px;
      line-height: 24px;
      font-weight: 300;
    }
  }
  &__icon {
    display: inline-block;
    width: 25px;
    opacity: 0.5;
    height: 20px;
    &:hover {
      opacity: 1;
    }
  }
}
@media screen and (max-width: 992px) {
  .q-review {
    &__title {
      font-size: 25px;
    }
    &__pack {
      display: none;
    }
    &__slider {
      max-width: 650px;
    }
    &__container {
      margin: 0 auto;
      padding: 20px 32px;
      &--name {
        font-size: 18px;
      }
      &--text {
        max-width: 493px;
      }
      &--img {
        margin: 0 auto;
        max-width: 100px;
      }
    }
  }
}
@media screen and (max-width: 768px) {
  .q-review {
    &__container {
      padding: 35px 32px;
      flex-direction: column;
      text-align: center;
      &--img {
        width: 100%;
        margin-bottom: 20px;
      }
      &--box {
        width: 100%;
        padding-left: 0;
      }
      &--list {
        justify-content: center;
      }
      &--text {
        margin: 0 auto;
        & br {
          display: none;
        }
      }
    }
  }
}
/* Q-review начало*/

/* Q-map начало */
.q-map {
  &__title {
    position: relative;
    display: block;
    line-height: 30px;
    margin-bottom: 60px;
    font-size: 45px;
    font-weight: 500;
    color: #212121;
    padding-left: 58px;
    &:before {
      content: "";
      display: block;
      position: absolute;
      top: 50%;
      left: 0;
      width: 37px;
      height: 2px;
      background-color: #212121;
    }
  }
  &__contact {
    position: absolute;
    max-width: 305px;
    background-color: #91a959;
    box-shadow: 0 6px 15px rgba(33, 33, 33, 0.2);
    box-sizing: border-box;
    padding: 60px 70px;
    &--list {
      font-size: 16px;
      color: white;
      display: flex;
      flex-direction: column;
      li {
        margin-bottom: 25px;
      }
      strong {
        display: block;
        font-weight: bold;
        line-height: 30px;
        padding-bottom: 10px;
      }
      span {
        display: block;
        line-height: 21px;
      }
    }
  }
}
iframe {
  height: 500px;
}
@media screen and (max-width: 992px) {
  .q-map {
    &__title {
      font-size: 25px;
    }
    &__contact {
      padding: 30px 45px;
    }
  }
}
@media screen and (max-width: 768px) {
  iframe {
    height: 270px;
  }
  .q-map {
    &__title {
      margin-bottom: 0;
    }
    &__contact {
      position: static;
      background-color: transparent;
      box-shadow: none;
      width: 100%;
      &--list {
        color: black;
        & li {
          margin-bottom: 15px;
        }
      }
    }
  }
}
/* Q-map конец */

/* Q-footer начало */
.q-footer {
  padding: 30px 0;
  color: white;
  font-size: 14px;
  letter-spacing: 1px;
  background-color: @green-bg;
  &__container {
    display: flex;
    justify-content: space-between;
  }
  &__wrapper {
    margin-top: 20px;
  }
  &__item {
    span {
      display: block;
    }
    img {
      display: inline-block;
      margin-right: 22px;
      opacity: 0.5;
      cursor: pointer;
      &:hover {
        opacity: 1;
      }
    }
  }
}
@media screen and (max-width: 768px) {
  .q-footer {
    &__container {
      flex-direction: column;
      justify-content: center;
      text-align: center;
    }
    &__wrapper {
      margin-top: 0;
    }
    &__item {
      order: 1;
      margin-bottom: 5px;
      & span {
        margin-top: 17px;
      }
      &:first-child {
        order: 2;
      }
      &:nth-child(2) {
        order: 1;
      }
    }
  }
}
/* Q-footer конец */

/* Q-menu начало*/
.q-menu {
  display: none;
  z-index: 99;
  top: 0;
  left: 0;
  overflow: hidden;
  position: fixed;
  background-color: @green-bg;
  width: 100%;
  height: 100vh;
  &__close {
    display: block;
    cursor: pointer;
    margin-top: 50px;
    margin-bottom: 50px;
    margin-left: auto;
  }
  &__list {
    margin-left: 25%;
    & li a {
      display: inline-block;
      text-decoration: none;
      color: white;
      font-size: 48px;
      line-height: 40px;
      padding: 25px 0;
      font-weight: bold;
      &:hover {
        opacity: 0.5;
      }
    }
  }
}
.active {
  display: block;
  position: absolute;
  top: 40%;
  left: -35px;
  width: 16px;
  height: 16px;
  border-radius: 50%;
  background-color: white;
}
@media screen and (max-width: 992px) {
  .q-menu {
    &__list {
      & li a {
        font-size: 36px;
      }
    }
  }
}
@media screen and (max-width: 768px) {
  .q-menu {
    &__close {
      width: 35px;
    }
    &__list {
      margin-left: 20%;
      & li a {
        font-size: 18px;
        line-height: 20px;
        padding: 15px 0;
      }
    }
  }
  .active {
    width: 9px;
    height: 9px;
  }
}
/* Q-menu конец */

/* Slider */
.slick-prev,
.slick-next {
  position: absolute;
  background-image: url("./assets/img/arrow.svg");
  font-size: 0;
  background-color: transparent;
  background-repeat: no-repeat;
  cursor: pointer;
  border: none;
  top: 50%;
  width: 20px;
  height: 36px;
  &:hover {
    opacity: 0.7;
  }
}
.slick-prev {
  left: -50px;
  transform: rotate(180deg);
}
.slick-next {
  right: -50px;
}
.slick-dots {
  display: flex;

  justify-content: space-around;
  position: relative;
  bottom: -50px;
  width: 90px;
  margin: 0 auto;
  margin-bottom: 10px;
}
.slick-dots li button {
  border-radius: 50%;
  display: flex;
  justify-content: space-between;
  box-sizing: border-box;
  background-color: rgba(145, 169, 89, 0.5);
  cursor: pointer;
  width: 10px;
  height: 10px;
  border: none;
  color: transparent;
  outline: none;
}
.slick-dots li.slick-active button {
  margin-top: -3px;
  width: 15px;
  height: 15px;
  background-color: rgba(145, 169, 89, 1);
}
@media screen and (max-width: 768px) {
  .slick-prev,
  .slick-next,
  .slick-arrow {
    display: none;
  }
  .slick-next.slick-arrow {
    display: none !important;
  }
  .slick-prev.slick-arrow {
    display: none !important;
  }
}
</style>
