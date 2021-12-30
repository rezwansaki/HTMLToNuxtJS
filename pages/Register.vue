<template>
  <div>
    <scction class="register-area">
      <div class="container register-container">
        <div class="row">
          <div class="col-xl-6">
            <div class="register-info-area">
              <div class="registration-info-title">Information</div>
              <div class="registration-info-desc">
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Eveniet corporis eius mollitia praesentium error? Quis nostrum
                  facilis quod veritatis minus rem, enim dolore modi distinctio
                  qui mollitia explicabo natus, id minima asperiores repellendus
                  architecto adipisci? Quod, repellat natus odio voluptas iusto
                  officia corrupti! Molestiae itaque ex, corrupti porro ipsam
                  numquam.
                </p>
                <p>
                  <span><i class="fas fa-info-circle"></i></span>Lorem ipsum
                  dolor, sit amet consectetur adipisicing elit. Deleniti
                  doloremque laudantium voluptate!
                </p>
                <p>
                  <span><i class="fas fa-info-circle"></i></span>Lorem ipsum
                  dolor sit amet consectetur adipisicing elit. Fuga veritatis
                  harum explicabo eligendi dicta! Explicabo placeat quam quasi
                  soluta molestias, aliquam repellendus neque rerum quia.
                </p>
                <p>
                  <span><i class="fas fa-info-circle"></i></span>Lorem ipsum
                  dolor sit amet consectetur adipisicing elit. Laborum delectus
                  ipsam beatae ut aliquid possimus atque. Commodi unde a
                  asperiores modi veniam impedit suscipit nihil, perferendis
                  debitis dolorem, eius facilis ab odio?
                </p>
                <p>
                  <span><i class="fas fa-info-circle"></i></span>Lorem, ipsum
                  dolor sit amet consectetur adipisicing elit.
                </p>
              </div>
            </div>
          </div>
          <div class="col-xl-6">
            <div class="registration-form-area">
              <div class="registration-form-title">Register</div>
              <div class="registration-form">
                <!-- registration start form -->
                <form action="" method="">
                  <div class="mb-3">
                    <label class="form-label">Name</label>
                    <input
                      type="text"
                      class="form-control"
                      id="name"
                      name="name"
                    />
                  </div>
                  <div class="mb-3">
                    <label class="form-label">Birth Date</label>
                    <input
                      type="text"
                      class="form-control"
                      id="birthdate"
                      name="birthdate"
                      placeholder="dd/mm/yyyy"
                    />
                  </div>
                  <div class="mb-3">
                    <label class="form-label">Address</label>
                    <input
                      type="text"
                      class="form-control"
                      id="address"
                      name="address"
                    />
                  </div>
                  <div class="mb-3">
                    <label class="form-label">Phone Number</label>
                    <input
                      type="text"
                      class="form-control"
                      id="phonenumber"
                      name="phonenumber"
                    />
                  </div>
                  <div class="mb-3">
                    <label class="form-label">Gender</label>
                    <select
                      class="form-select"
                      aria-label="Default select example"
                      id="gender"
                      name="gender"
                    >
                      <option value="1">Male</option>
                      <option value="2">Female</option>
                      <option value="3">Others</option>
                    </select>
                  </div>
                  <div class="mb-3">
                    <label class="form-label">Email</label>
                    <input
                      type="email"
                      class="form-control"
                      id="email"
                      name="email"
                    />
                  </div>
                  <div class="mb-3">
                    <label class="form-label">Password</label>
                    <input
                      type="password"
                      class="form-control"
                      id="password"
                      name="password"
                    />
                  </div>
                  <div class="d-grid gap-2">
                    <button type="button" class="btn btn-primary">
                      Submit
                    </button>
                  </div>
                </form>
                <!-- registration end here form -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </scction>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
