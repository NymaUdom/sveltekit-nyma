
<script lang="ts">
    import { onDestroy, onMount } from 'svelte'

    onMount(() => console.log('Mounted posts page'))
    onDestroy(() => console.log('Unmounted posts page'))

</script>
<nav>
    <a href="/">Home</a>
    <a href="/posts">Posts</a>
  </nav>
  
  <h1>Posts page</h1>

  <p>
    You can
    <a href="/posts/create">+create</a>
    or edit your posts here.
  </p>