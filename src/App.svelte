<script>
  let saldo = 1526;

  let history = [
    "pantere i høst = xx",
    "1mda-kafé = kr +1596",
    "roser og sjokolade til kontakt-lærerne våre, (valentinsdagen) = kr -170",
    "Erik panta = kr +100",
  ];
</script>

<div class="saldo">
  <h1>Saldo: kr {saldo}</h1>
</div>

<div class="historikk">
  <h2>Historikk:</h2>
  <ul>
    {#each history as item}
      <li>{item}</li>
    {/each}
  </ul>
</div>
