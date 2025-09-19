<script>
  import WeatherCard from "./WeatherCard.svelte";
</script>

<section class="daily-forecast-ctr">
  <h2 class="text-5">Daily forecast</h2>

  <div class="weather-cards-ctr">
    <WeatherCard />
    <WeatherCard />
    <WeatherCard />
    <WeatherCard />
    <WeatherCard />
    <WeatherCard />
    <WeatherCard />
  </div>
</section>

<style>
  .daily-forecast-ctr {
  }

  h2 {
    margin-bottom: var(--size-250);
  }

  .weather-cards-ctr {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: var(--size-200);
  }
</style>
