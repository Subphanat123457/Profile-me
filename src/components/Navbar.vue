<template>
  <div class="bg">
    <div class="row">
      <div class="col-sm-4 padding-l nav-link text-color-w">
        <div class="fs-3">
          MyName
        </div>
      </div>
      <div class="col-sm-8">
        <ul class="nav nav-underline justify-content-end">
          <li class="nav-item">
            <a class="nav-link text-color-w" aria-current="page" href="#scrollspyHeading0">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-color-w" aria-current="page" href="#scrollspyHeading1">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-color-w" href="#scrollspyHeading2">Certificate</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-color-w" href="#scrollspyHeading3">Contract</a>
          </li>
        </ul>
      </div>
  </div>
</div>
  

</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Navbar',
  components: {
  }
}
</script>

<style scoped>
    .text-color-w{
        color: aliceblue;
    }
    .padding-l{
        padding-left: 0px;
    }
    
    
</style>
