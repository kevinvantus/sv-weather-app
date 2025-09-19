<script>
  import HourlyForecastCard from "./HourlyForecastCard.svelte";
</script>

<section class="hourly-forecast">
  <header>
    <h2 class="text-5">Hourly forecast</h2>
  </header>

  <HourlyForecastCard />
  <HourlyForecastCard />
  <HourlyForecastCard />
  <HourlyForecastCard />
  <HourlyForecastCard />
  <HourlyForecastCard />
  <HourlyForecastCard />
  <HourlyForecastCard />

  <div class="divider"></div>
</section>

<style>
  .hourly-forecast {
    display: grid;
    gap: var(--size-200);
    padding: var(--size-250) var(--size-200);
    background-color: var(--neutral-800);
    border-radius: var(--radius-20);
    position: relative;
  }

  header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 37px;
  }

  .divider {
    position: absolute;
    width: var(--size-50);
    height: 262px;
    background-color: hsla(242, 22%, 24%, 1);
    border: 1px solid hsla(242, 23%, 30%, 1);
    border-radius: var(--radius-12);
    right: 0;
    bottom: 160px;
  }
</style>
