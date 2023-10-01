<template>
  <div class="swipper-up">
    <header class="swipper-heading">Наши проекты</header>
    <div class="swipper-skip">
      <button class="swipper-button swipper-button-right">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="56"
          height="56"
          viewBox="0 0 56 56"
          fill="none"
        >
          <circle
            cx="28"
            cy="28"
            r="27"
            transform="matrix(-1 0 0 1 56 0)"
            stroke="url(#paint0_linear_10901_1218)"
            stroke-width="2"
          />
          <path
            d="M30.6667 22L25 27.8286L31 34"
            stroke="url(#paint1_linear_10901_1218)"
            stroke-width="2"
            stroke-linecap="round"
          />
          <defs>
            <linearGradient
              id="paint0_linear_10901_1218"
              x1="5.824"
              y1="11.424"
              x2="49.504"
              y2="45.696"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#615BD6" />
              <stop offset="1" stop-color="#528FEF" />
            </linearGradient>
            <linearGradient
              id="paint1_linear_10901_1218"
              x1="25.624"
              y1="24.448"
              x2="32.1766"
              y2="27.0186"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#615BD6" />
              <stop offset="1" stop-color="#528FEF" />
            </linearGradient>
          </defs>
        </svg>
      </button>
      <button class="swipper-button swipper-button-left">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="56"
          height="56"
          viewBox="0 0 56 56"
          fill="none"
        >
          <circle
            cx="28"
            cy="28"
            r="27"
            stroke="url(#paint0_linear_10901_1221)"
            stroke-width="2"
          />
          <path
            d="M25.3333 22L31 27.8286L25 34"
            stroke="url(#paint1_linear_10901_1221)"
            stroke-width="2"
            stroke-linecap="round"
          />
          <defs>
            <linearGradient
              id="paint0_linear_10901_1221"
              x1="5.824"
              y1="11.424"
              x2="49.504"
              y2="45.696"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#615BD6" />
              <stop offset="1" stop-color="#528FEF" />
            </linearGradient>
            <linearGradient
              id="paint1_linear_10901_1221"
              x1="30.376"
              y1="24.448"
              x2="23.8234"
              y2="27.0186"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#615BD6" />
              <stop offset="1" stop-color="#528FEF" />
            </linearGradient>
          </defs>
        </svg>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'heading-and-buttons',
};
</script>

<style scoped>
.swipper-up {
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding-bottom: 68px;
}
.swipper-heading {
  color: #333;
  font-family: Rubik;
  font-size: 52px;
  font-style: normal;
  font-weight: 500;
  line-height: 64px;
}
.swipper-skip {
  display: flex;
  gap: 1rem;
}
.swipper-button {
  max-width: 56px;
  max-height: 56px;
}
</style>
