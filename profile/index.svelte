<script>
  let isLoggedIn = true;
</script>


{#if isLoggedIn} 
  <p>Welcome, user!</p>
{:else}
  <p>Please log in.</p>
{/if}
