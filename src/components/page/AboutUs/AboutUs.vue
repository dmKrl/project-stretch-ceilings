<template>
  <div class="about">
    <div class="about-us">
      <h2 class="about-heading">О компании</h2>
      <main-text style="max-width: 559px"
        >Ceilng+ основана в 2018 году. Компания занимается установкой натяжных
        потолков. Нам платят деньги за то, что мы всегда выполняем свои
        обязательства в срок и заботимся о наших клиентах. Если после установки
        потолков что-то случится, мы бесплатно меняем потолок на новый в течение
        24 часов. Кроме установки, мы помогаем нашим клиентам с подбором
        материала и консультируем их после завершения работ в любое время. Нам
        важен профессионализм исполнителей, поэтому принимаем на работу только
        сертифицированных мастеров.</main-text
      >
      <div class="about-certificate">
        <h2 class="about-heading">Сертификаты</h2>
        <div class="about-items">
          <div class="about-certificate-item">
            <img
              src="../../../static/images/certificate1.png"
              alt="certificate"
              class="about-img"
            />
          </div>
          <div class="about-certificate-item">
            <img
              src="../../../static/images/certificate1.png"
              alt="certificate"
              class="about-img"
            />
          </div>
          <div class="about-certificate-item">
            <img
              src="../../../static/images/certificate1.png"
              alt="certificate"
              class="about-img"
            />
          </div>
        </div>
      </div>
    </div>
    <div class="about-info">
      <div class="about-info-item">
        <price-ceiling>2400</price-ceiling>
        <main-text>выполненных заказов</main-text>
      </div>
      <div class="about-info-item">
        <price-ceiling>3</price-ceiling>
        <main-text>года на рынке</main-text>
      </div>
      <div class="about-info-item">
        <price-ceiling>26</price-ceiling>
        <main-text>сертифицированный мастеров</main-text>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.about {
  display: flex;
  margin: 100px auto;
  gap: 140px;
  max-width: 1440px;
}
.about-us {
  display: flex;
  flex-direction: column;
  gap: 48px;
}
.about-heading {
  color: var(--, #333);
  font-family: Rubik;
  font-size: 3.25rem;
  font-style: normal;
  font-weight: 500;
  line-height: 4rem;
}
.about-certificate {
  display: flex;
  flex-direction: column;
  gap: 48px;
}
.about-info {
  display: flex;
  flex-direction: column;
  gap: 31px;
  margin-top: 112px;
}
.about-items {
  display: flex;
  gap: 40px;
}
</style>
