<template>
    <div class="">
        <div class="container-fluid">
  <div class="row">
    <nav id="sidebarMenu" class="col-md-3 col-lg-2 d-md-block bg-light sidebar collapse">
      <div class="position-sticky pt-3">
        <ul class="nav flex-column">
          <li class="nav-item">
            <router-link to="/home" class="nav-link active" aria-current="page" href="#">
                <i class="bi bi-house-fill p-2"></i>
              INICIO
            </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/ventas" class="nav-link" href="#">
              <i class="bi bi-shop p-2"></i>
              VENTAS
            </router-link>
          </li>
          <li class="nav-item">
            <router-link to="proveedores" class="nav-link" href="#">
              <i class="bi bi-people p-2" ></i>PROVEEDORES
            </router-link>
          </li>
         <li class="nav-item">
            <router-link to="/categorias" class="nav-link"  > 
            
             <i class="bi bi-tags-fill p-2"></i> CATEGORIAS
            </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/reportes" class="nav-link" href="#">
              <i class="bi bi-flag p-2"></i>REPORTES
            </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/pedidos" class="nav-link" href="#">
            <i class="bi bi-calendar2-week-fill p-2"></i>  PEDIDOS
            </router-link>
          </li>
        </ul>

        <h6 class="sidebar-heading d-flex justify-content-between align-items-center px-3 mt-4 mb-1 text-muted">
          <span>otros</span>
          <a class="link-secondary" href="#" aria-label="Add a new report">
          </a>
        </h6>
        <ul class="nav flex-column mb-2">
          <li class="nav-item">
            <router-link to="/favoritos" class="nav-link" href="#">
              <i class="bi bi-bookmark-star p-2"></i>VENTAS FAVORITAS
            </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/archivo" class="nav-link" href="#">
              <i class="bi bi-folder-symlink p-2"></i>ARCHIVO
            </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/productos" class="nav-link" href="#">
              productos
            </router-link>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              Year-end sale
            </a>
          </li>
        </ul>
      </div>
    </nav>
    <main class="col-md-9 ms-sm-auto col-lg-10">
     
<router-view></router-view>

     
    </main>
  </div>
</div>
    </div>
</template>
<script>
export default {
    name: 'Links'
}
</script>