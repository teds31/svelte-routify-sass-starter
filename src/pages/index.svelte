<script>
  import RoutifyIntro from "./example/_components/RoutifyIntro.svelte";
  import Lazy from "svelte-lazy";
</script>

<style lang="scss" type="text/scss">
  .container {
    background-color: aqua;
    h1 {
      font-size: 60px;
    }
  }
</style>

<RoutifyIntro />
<div class="container">
  <h1>this is a test</h1>

</div>
<Lazy height={300} offset={150}>
  <img
    src="https://www.lifewithdogs.tv/wp-content/uploads/2016/06/6.26.16-Bad-Pun-Husky1.jpg"
    alt="" />
</Lazy>
