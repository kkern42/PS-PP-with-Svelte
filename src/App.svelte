<script>
  import PSPPLogo from './assets/pingpong.svg'
  import Counter from './lib/Counter.svelte'
  import Header from './lib/header.svelte'
</script>

<!-- add in player profiles when db is activated  -->

<main>
  <Header/>
  <div class="app">
    <div>

      <a href="https://brackethq.com/b/k4n6/" target="_blank"> 
        <img src={PSPPLogo} class="logo" alt="PS PP Logo" />
      </a>
    </div>
    <h1>PS PING PONG Tournament</h1>
  
    <!-- <div class="card">
      <Counter />
    </div> -->
  
    <p>
      Check out <a href="https://teams.microsoft.com/l/team/19%3aCsAUOEEmMq-4OoZugqYP4h2HWJ051bI48z3DbSB7Ha81%40thread.tacv2/conversations?groupId=3e8b7471-35de-45b0-9a0b-b40cf83d6d83&tenantId=d52c9ea1-7c21-47b1-82a3-33a74b1f74b8" target="_blank">PS PP NYC</a>, the official Teams channel for NYC PING PONG!
    </p>
  
    <p class="read-the-docs">
      Reach out to Ashely Kim, JD Pablo or Kevin Kern to learn more
    </p>
  
    <!-- style="width: 150%;" -->
    <div class="bracket">
      <h2 class="title">Tier 1 Bracket - Fall 2022</h2>
      <iframe title="Tier 1 PS PP Tournament" src="https://brackethq.com/b/k4n6/embed/" width="100%" height="550" frameborder="0"></iframe>
    </div>
  
    <hr/>
  
    <div class="bracket">
      <h2 class="title">Tier 2 Bracket - Fall 2022</h2>
      <iframe title="Tier 2 PS PP Tournament" src="https://brackethq.com/b/x6n6/embed/" width="100%" height="700" frameborder="0"></iframe>
    </div>
  </div>
  
</main>

<style>
  .logo {
    height: 9em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
