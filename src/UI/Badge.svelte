<script>
  import { slide } from 'svelte/transition'
</script>

<style>
  span {
    display: inline-block;
    margin: 0 0.25rem;
    padding: 0 .5rem;
    background-color: #cf0056;
    color: #fff;
    font-family: 'Lato', sans-serif;
    font-size: 0.8rem;
    border: 1px solid #cf0056;
    border-radius: 3px;
  }
</style>

<span transition:slide><slot></slot></span>