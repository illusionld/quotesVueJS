<template>
  <div class="col-sm-12 col-md-4 col-md-offset-2">
    <div class="panel panel-default">
      <div class="panel-body quote">
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style>
  .panel-body {
    font-size: 24px;
    font-family: 'Arizonia', cursive;
    color: #6e6e6e;
    text-align: center;
  }
  .quote {
    cursor: pointer;
  }
  .quote:hover {
    background-color: lightcoral;
  }
</style>
