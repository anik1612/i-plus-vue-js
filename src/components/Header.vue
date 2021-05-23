<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid mx-5">
      <a class="navbar-brand" href="#">
        <img height="45" src="../assets/images/user-icon.png" alt="" />
      </a>
      <nav class="navbar navbar-light bg-dark">
        <div class="container-fluid">
          <form class="d-flex">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Type here to search"
              aria-label="Search"
            />
          </form>
        </div>
      </nav>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">
              <img
                src="../assets/images/bento-menu-icon.png"
                height="45"
                alt="bento-menu-icon"
              />
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <img src="../assets/images/translation.png" height="45" alt="" />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Header",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>