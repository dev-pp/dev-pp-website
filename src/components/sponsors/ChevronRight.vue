<template>
  <svg
    height="48"
    id="angle-right"
    viewBox="0 0 48 48"
    width="48"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path class="vi-primary" d="M17,9L32,24,17,39l-3-3L26,24,14,12Z" />
    <path
      class="vi-accent"
      d="M19.5,17.5l3-3L17,9l-3,3Zm0,13L14,36l3,3,5.5-5.5Z"
    />
  </svg>
</template>

<script>
export default {};
</script>

<style>
.vi-primary {
  fill: #ff6e6e;
}

.vi-primary,
.vi-accent {
  stroke: #fff;
  stroke-linecap: round;
  stroke-width: 0;
  fill-rule: evenodd;
}

.vi-accent {
  fill: #0c0058;
}
</style>