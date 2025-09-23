<article class="weather-info">
  <div class="location-info">
    <div class="location text-4">Berlin, Germany</div>
    <time datetime="Tuesday, Aug 5, 2025" class="text-6">
      Tuesday, Aug 5, 2025
    </time>
  </div>

  <div class="temp-ctr">
    <img
      src="/assets/images/icon-sunny.webp"
      alt=""
      width="120"
      height="120"
      class="weather-icon"
    />
    <span class="temp text-1">68&deg;</span>
  </div>
</article>

<style>
  .weather-info {
    padding: 41px var(--size-300);
    border-radius: var(--radius-20);
    display: flex;
    flex-direction: column;
    gap: var(--size-200);
    position: relative;
    overflow: hidden;
    background:
      linear-gradient(94deg, #4658d9 -8.59%, #2b1b9c 98.38%),
      url(/assets/images/bg-today-small.svg) no-repeat center/cover;
    background-blend-mode: saturation;
  }

  /* .weather-info::before {
    content: "";
    position: absolute;
    inset: 0;
    background: url(/public/assets/images/bg-today-small.svg) no-repeat
      center/cover;
    opacity: 16%;
    pointer-events: none;
  } */

  .location-info {
    text-align: center;
  }

  .location {
    margin-bottom: var(--size-150);
  }

  time {
    opacity: 0.8;
  }

  .temp-ctr {
    display: flex;
    align-items: center;
    gap: var(--size-250);
  }

  .weather-icon {
    flex: 0;
  }

  .temp {
    flex: 1;
  }

  @media screen and (min-width: 768px) {
    .weather-info {
      flex-direction: row;
      align-items: center;
      height: 286px;
      /* background:
        linear-gradient(94deg, #4658d9 -8.59%, #2b1b9c 98.38%),
        url(/assets/images/bg-today-large.svg) no-repeat center/cover; */
      background-image: url(/assets/images/bg-today-large.svg);
    }

    .temp-ctr {
      margin-inline-start: auto;
    }
  }
</style>
