<template>
  <div class="content">
    <TransitionGroup name="slide-fade" tag="div">
      <div v-if="status == 'builders'" class="builders">
        <h2 class="content__title lll">
          Каталог проектов домов для строительных организаций
        </h2>
        <p class="lll content__first-p">
          Перед вами
          <a href="https://xn--80aaotgcmngqg.xn--p1ai/">
            <span color-type="color" style="color: #0849fc">
              <u>каталог</u></span
            ></a
          ><span color-type="color" style="color: #0849fc">&nbsp;</span>проектов
          для строительных организаций.&nbsp; <br />Проекты на сайт загружают
          частные архитекторы и другие строительные компании, а это значит, что
          проекты<br />
          уже были когда-то построены и имеют отработанные строительные решения.
          Вы можете разместить наш<br />
          каталог на своём сайте, а благодаря фильтру с множеством параметров,
          ваш клиент сможет легко найти именно<br />
          тот проект, который устроит его на 100%&nbsp;<br />
          Вы можете задать цвет кнопок каталога, чтобы он идеально вписывался в
          оформление вашего сайта. Схема<br />
          работает и в мобильной и в desktop-версии каталога.<br />
          Вы сможете создать комплектации строительства домов, например такие
          как "коробка", "под отделку", "под <br />ключ", установить свои цены
          за квадратный метр всего один раз, и они отобразятся под каждым
          проектом.<br />
          Если вам нужна будет помощь с настройкой, просто напишите нам.
        </p>
        <div class="builders__list lll">
          <h2 class="content__list-title">Что дальше?</h2>
          <ul class="content__list">
            <li>
              Вы регистрируете личный кабинет на нашей платформе, и размещаете у
              себя на сайте HTML-код нашего встраиваемого каталога
              проектов.&nbsp;
            </li>
            <li>
              По внутреннему фильтру выбираете проекты которые хотели бы видеть
              в каталоге на своём сайте, и настраиваете комплектации для
              установки стоимости строительства этих проектов.
            </li>
            <li>
              Посетители вашего сайта могут выбрать проект и сделать заявку на
              точный расчёт стоимости строительства. Эта заявка приходит на ваш
              e-mail с контактными данными клиента и ссылкой на проект.
            </li>
            <li>
              Вы связываетесь с клиентом, и в случае заключения договора,
              выкупаете выбранный проект у нас (либо перенаправляете вашего
              клиента к нам для покупки), а дальше строите ему дом по этому
              проекту.
            </li>
            <li>
              Кроме того, Вы получите заявки на строительство от посетителей
              нашего портала.
            </li>
            <li>Сможете добавлять проекты вашей компании.<br /></li>
          </ul>
        </div>
      </div>
      <div v-else-if="status == 'architects'" class="architects">
        <h2 class="content__title lll">Каталог-портфолио для архитекторов</h2>
        <p class="content__second-p lll">
          Перед вами
          <a href="https://xn--80aaotgcmngqg.xn--p1ai/"
            ><span color-type="color" style="color: #0849fc"
              ><u>каталог-портфолио</u></span
            ></a
          ><span color-type="color" style="color: #0849fc">&nbsp;</span>для
          архитекторов. Зарегистрировав личный кабинет на нашей платформе,
          <span color-type="color" style="color: #000000"
            >Вы сможете размещать свои проекты абсолютно бесплатно. После
            загрузки первого проекта вам станет доступна ссылка на
            индивидуальный каталог. Кроме того, ваши проекты попадут в общий
            каталог основного сайта-маркетплейса, откуда также будут поступать
            заявки.&nbsp;</span
          ><br /><span color-type="color" style="color: #000000"
            >Наши партнёры-строители смогут размещать Ваши проекты в своих
            каталогах. Таким образом, вы получаете дополнительные каналы
            повторных продаж ваших готовых проектов.</span
          ><br /><span color-type="color" style="color: #000000"
            >Используя обширные настройки карточки проекта, и фильтры каталога,
            Вы сможете быстро находить среди десятков своих проектов именно тот,
            который необходим вашему заказчику.</span
          ><br /><br />
        </p>
        <div class="architects__list lll">
          <span class="content__list-title">Подытожим.</span>
          <ul class="content__list">
            <li>
              Прежде всего Вы сразу получаете мощный канал для показа ваших
              работ потенциальным застройщикам.
            </li>
            <li>
              <span
                style="
                  background-color: transparent;
                  color: inherit;
                  font-size: 1.25rem;
                "
                >Сможете легко презентовать Ваше портфолио своим
                заказчикам.</span
              ><span
                style="
                  background-color: transparent;
                  color: inherit;
                  font-size: 1.25rem;
                "
                ><br
              /></span>
            </li>
            <li>
              <span
                style="
                  background-color: transparent;
                  color: inherit;
                  font-size: 1.25rem;
                "
                >Вам больше не нужно прилагать усилия к тому, чтобы Вас нашли и
                увидели в Интернете, ведь благодаря сайтам наших
                партнёров-строителей, Ваши проекты увидят тысячи людей.</span
              ><br />
            </li>
            <li>
              <span
                style="
                  background-color: transparent;
                  color: inherit;
                  font-size: 1.25rem;
                "
                >Мы предлагаем поток заказчиков со всей страны, заинтересованных
                в легком, быстром и удобном поиске нужного проекта</span
              ><br />
            </li>
            <li>
              При хорошем качестве проектов, Вашими услугами могут
              заинтересоваться строительные компании, что обеспечит Вас
              постоянными заказами.
            </li>
            <li>
              Вы — специалист своего дела и умеете создавать высококачественные
              проекты. Мы знаем, как ярко и результативно представить Ваш проект
              в сети. Давайте объединим усилия! Вы создаёте проекты, а мы
              занимаемся их продвижением в интернете.<br />
            </li>
          </ul>
        </div>
      </div>
    </TransitionGroup>
  </div>
  <div class="content__btn-div">
    <button class="content__btn">
      <a href="https://xn--80aaotgcmngqg.xn--p1ai/admin/login">
        Создать личный кабинет
      </a>
    </button>
  </div>
</template>

<script setup>
const props = defineProps({
  status: {
    type: String,
    required: true,
  },
});
</script>

<style lang="scss" scoped>
.slide-fade-enter-active {
  transition: all 0.3s ease-out;
}

.slide-fade-leave-active {
  transition: all 0.3s cubic-bezier(1, 0.5, 0.8, 1);
}

.slide-fade-enter-from,
.slide-fade-leave-to {
  transform: translateX(10px);
  opacity: 0;
}
.content {
  &__title {
    font-size: 1.875rem;
    line-height: 1.2;
    font-weight: 700;
    text-align: left;
    margin-bottom: 15px;
  }
  &__first,
  &__second {
    &-p {
      line-height: 1.5;
    }
    &-a {
      color: #0849fc;
    }
  }
  &__list {
    margin: 0;
    padding-left: 1.75em;
    margin-bottom: 30px;
    & li {
      font-size: 1.25rem;
      line-height: 1.5;
      font-weight: 400;
      text-align: left;
    }
    &-title {
      font-size: 1.375rem;
      line-height: 1.37;
      font-weight: 700;
      text-align: left;
      padding: 5px 0;
    }
  }
  &__btn {
    padding: 12px 22px;
    width: 293px;
    height: 54px;
    min-width: 15px;
    max-width: 1150px;
    background: var(--red);
    border: none;
    border-radius: 5px;
    text-align: center;
    &-div {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 40px 0;
    }
    & a {
      text-decoration: none;
      font-weight: 900;
      font-size: 20px;
      line-height: 147%;
      text-align: center;
      color: #fff;
    }
  }
}
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.2s ease;
}
.fade-enter,
.fade-leave-to {
  opacity: 0;
}
p {
  font-family: "Tenor";
  font-weight: 400;
  font-size: 20px;
  line-height: 137%;
  color: #060607;
}
</style>
