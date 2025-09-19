<article class="weather-card">
  <p class="label text-6">Tue</p>

  <img
    src="/assets/images/icon-partly-cloudy.webp"
    alt=""
    width="60"
    height="60"
    class="weather-icon"
  />

  <div class="temp-range text-7">
    <span class="min">68&deg;</span>
    <span class="max">57&deg;</span>
  </div>
</article>

<style>
  .weather-card {
    height: 165px;
    padding: var(--size-200) var(--size-125);
    background-color: var(--neutral-800);
    border: 1px solid var(--neutral-600);
    border-radius: var(--radius-12);
    display: flex;
    flex-direction: column;
    gap: var(--size-200);
  }

  .label {
    text-align: center;
  }

  .weather-icon {
    margin: auto;
  }

  .temp-range {
    display: flex;
    justify-content: space-between;
  }

  .max {
    color: var(--neutral-200);
  }
</style>
