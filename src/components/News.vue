<template>
    <div>
      <Navbar />
      <router-view />
    </div>
    <div class="container my-5">
  <div class="position-relative p-5 text-center text-muted bg-body border border-dashed rounded-5">
    <button type="button" class="position-absolute top-0 end-0 p-3 m-3 btn-close bg-secondary bg-opacity-10 rounded-pill" aria-label="Close"></button>
    <svg class="bi mt-5 mb-3" width="48" height="48"><use xlink:href="#check2-circle"></use></svg>
    <h2 class="text-body-emphasis">Tech’s Role in Beating the Restaurant Hiring Crunch</h2>
    <p class="col-lg-6 mx-auto mb-4">
      The hiring shortage and the fallout from "The Great Resignation" that saw 47 million U.S. workers quit their jobs in 2021 is still in full swing    </p>
    <button class="btn btn-primary px-5 mb-5" type="button">
      Next
    </button>
  </div>
</div>
</template>


<script>

import Navbar from "./Navbar.vue";

export default {
  name: "Features",
  components: {
    Navbar,
  },
};

  </script>