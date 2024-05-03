<template>
  <div class="grid">
    <svg
      v-for="n in 16"
      width="200"
      height="200"
      viewBox="0 0 2776 2196"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <g id="Group 24">
        <rect
          id="Rectangle 213"
          y="0.28125"
          width="2776"
          height="2194.73"
          fill="#D9D9D9"
        />
        <path
          id="Star 1"
          d="M1340.44 524.99L1459.45 920.686H1844.56L1533 1165.24L1652 1560.94L1340.44 1316.38L1028.88 1560.94L1147.88 1165.24L836.319 920.686H1221.43L1340.44 524.99Z"
          fill="#FF0000"
        />
      </g>
    </svg>
  </div>
</template>

<style scoped>
.grid {
  position: absolute;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr 1fr;
  background-image: url("/kakakakak.svg");
}
</style>
