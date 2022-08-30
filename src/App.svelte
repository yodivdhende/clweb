<script>
  import { ViewContent } from './lib/ViewContent.store';

</script>

<textarea name="comandline" id="commandLine" bind:value={$ViewContent}></textarea>

<style>
  text {
    width: 100%;
    height: 100%;
    padding:0;
    margin:0;
    border: 0;
    color: white;
    font-family: 'Courier New', Courier, monospace;
    background-color: black;
  }
</style>
