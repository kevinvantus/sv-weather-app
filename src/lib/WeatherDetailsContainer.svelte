<script>
  import WeatherDetails from "./WeatherDetails.svelte";
</script>

<div class="weather-details-ctr">
  <WeatherDetails />
  <WeatherDetails />
  <WeatherDetails />
  <WeatherDetails />
</div>

<style>
  .weather-details-ctr {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: var(--size-200);
    margin-bottom: var(--size-400);
  }

  @media screen and (min-width: 768px) {
    .weather-details-ctr {
      grid-template-columns: repeat(4, 1fr);
      gap: var(--size-250);
    }
  }

  @media screen and (min-width: 1260px) {
    .weather-details-ctr {
      margin-bottom: var(--size-600);
    }
  }
</style>
