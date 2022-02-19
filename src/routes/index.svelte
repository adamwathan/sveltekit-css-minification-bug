<div class="a">Grayscale doesn't work</div>
<div class="b">Grayscale does work</div>

<style>
  .a {
    padding: 25px;
    background: fuchsia;
    --blur: ;
    --grayscale: grayscale(1);
    filter: var(--blur) var(--grayscale);
  }
  .b {
    padding: 25px;
    background: fuchsia;
    --blur: /**/ /**/ ;
    --grayscale: grayscale(1);
    filter: var(--blur) var(--grayscale);
  }
</style>
