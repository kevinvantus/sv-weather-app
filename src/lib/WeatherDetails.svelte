<article class="weather-details">
  <dl>
    <dt class="label text-6">Feels like</dt>
    <dd class="value text-3">18&deg;</dd>
  </dl>
</article>

<style>
  .weather-details {
    padding: var(--size-250);
    border: 1px solid var(--neutral-600);
    border-radius: var(--radius-12);
    background-color: var(--neutral-800);
    height: 118px;
  }

  .weather-details dl {
    display: flex;
    flex-direction: column;
    gap: var(--size-300);
  }

  .label {
    color: var(--neutral-200);
  }
</style>
