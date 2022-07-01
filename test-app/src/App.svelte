<script>
  import { fly } from 'svelte/transition'
  import Keypad from './lib/Keypad.svelte'
</script>



<div>
  <Keypad/>
  <div class="left">
    
  </div>
  <div class="right">
    
  </div>
  <Keypad/>
</div>


<style>
  .left {
    position: absolute;
    background-color: rgb(86, 82, 82);
    width: 50%;
    height: 100%;
    left: 0;
    top: 0;
  }

  .right {
    position: absolute;
    background-color: rgb(86, 82, 82);
    width: 50%;
    height: 100%;
    left: 50%;
    top: 0;
  }
</style>
