<template>
  <div class="sticky-top">
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                  <NuxtLink to="/">
                        <img src="favicon.ico" class="logo-img">
                  </NuxtLink>
                  
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                        data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                        aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                  </button>
                  <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                              <li class="nav-item">
                                    
                                    <NuxtLink to="/" class="nav-link">Home</NuxtLink>
                              </li>
                              <li class="nav-item">
                                    <NuxtLink to="/about" class="nav-link">About</NuxtLink>
                              </li>
                              <li class="nav-item">
                                    <NuxtLink to="/services" class="nav-link">Service</NuxtLink>
                              </li>
                              <li class="nav-item">
                                    <NuxtLink to="/contact" class="nav-link">Contact</NuxtLink>
                              </li>
                              <li class="nav-item dropdown">
                                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                                          data-bs-toggle="dropdown" aria-expanded="false">
                                          language
                                    </a>
                                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                                          <li><a class="dropdown-item" href="#">Enlish</a></li>
                                          <li><a class="dropdown-item" href="#">Thai</a></li>
                  
                                          <li><a class="dropdown-item" href="#">French</a></li>
                                    </ul>
                              </li>
                              <button class="btn btn-outline-primary" type="submit">login</button>
                        </ul>
                        
                  </div>
            </div>
      </nav>
  </div>
</template>


<script>
export default {
      name: 'AppHeader'
}
</script>

<style>
.logo-img {
      width: 50px;
}
</style>
