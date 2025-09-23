<script lang="ts">
  import Header from "./lib/Header.svelte";
  import Title from "./lib/Title.svelte";
  import Search from "./lib/SearchContainer.svelte";
  import WeatherInfoContainer from "./lib/WeatherInfoContainer.svelte";
  import DailyForecast from "./lib/DailyForecast.svelte";
  import HourlyForecast from "./lib/HourlyForecast.svelte";
</script>

<Header />

<Title />

<main id="main-content">
  <Search />

  <div class="content-ctr">
    <div class="left-content">
      <WeatherInfoContainer />
      <DailyForecast />
    </div>

    <div class="right-content">
      <HourlyForecast />
    </div>
  </div>
</main>
