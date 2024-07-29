<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">The Dataset Tool</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item d-flex align-items-center">
            <h6 class="m-0 me-2 text-secondary">Benefits you?</h6>
            <a
              href="//paypal.me/mhmdhana"
              target="_blank"
              class="btn btn-primary btn-sm"
            >
              <i class="fab fa-paypal me-1"></i> PayPal me
            </a>
          </li>
        </ul>
        <div class="d-flex align-items-center">
          <form class="d-flex me-2" role="search">
            <select class="form-select form-select-sm" aria-label="AI Model">
              <option selected>Select AI model</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
            <input
              class="form-control form-control-sm ms-2"
              type="password"
              placeholder="Your OpenAI API key"
              aria-label="API Key"
            />
          </form>
          <div class="dropdown flex-shrink-0 mx-2">
            <a
              href="#"
              class="d-block link-body-emphasis text-decoration-none dropdown-toggle"
              data-bs-toggle="dropdown"
              data-bs-auto-close="outside"
              aria-expanded="false"
            >
              <span>
                <i class="far fa-user"></i>
              </span>
            </a>
            <div
              class="dropdown-menu text-small shadow dropdown-menu-end user-info-dropdown"
            >
              <div class="row m-2">
                <div class="col-6">
                  <input
                    class="form-control form-control-sm mb-2"
                    type="text"
                    placeholder="First name"
                    aria-label="First name"
                  />
                </div>
                <div class="col-6">
                  <input
                    class="form-control form-control-sm mb-2"
                    type="text"
                    placeholder="Last name"
                    aria-label="Last name"
                  />
                </div>
                <div class="col-12">
                  <input
                    type="email"
                    class="form-control form-control-sm mb-2"
                    id="email"
                    placeholder="Email"
                  />
                </div>
                <div class="col-12">
                  <input
                    type="text"
                    class="form-control form-control-sm mb-2"
                    id="phone"
                    placeholder="Phone"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "nav-bar",
}
</script>

<style scoped>
.user-info-dropdown {
  width: 320px;
}
</style>
