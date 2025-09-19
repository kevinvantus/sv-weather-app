<article class="hourly-forecast-card">
  <img
    src="/assets/images/icon-drizzle.webp"
    alt=""
    width="40"
    height="40"
    class="weather-icon"
  />

  <time datetime="3 PM" class="text-5 md">3 PM</time>

  <span class="temp text-7">20&deg;</span>
</article>

<style>
  .hourly-forecast-card {
    padding: var(--size-125) var(--size-200);
    background-color: var(--neutral-700);
    border: 1px solid var(--neutral-600);
    border-radius: var(--radius-8);
    display: flex;
    align-items: center;
    gap: var(--size-100);
    height: 60px;
  }

  .weather-icon,
  .temp {
    flex: 0;
  }

  time {
    flex: auto;
  }
</style>
