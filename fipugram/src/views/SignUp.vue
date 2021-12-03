<template>
  <div class="about">
    <h1>Sign Up Page</h1>
    <div class="container">
      <div class="row">
        <div class="col-sm"></div>
        <div class="col-sm">
          <form>
            <div class="form-group">
              <label for="namesurname">Full Name</label>
              <input
                type="text"
                class="form-control"
                id="namesurname"
                placeholder="Enter first and last name..."
              />
            </div>
            <div class="form-group">
              <label for="username">Username</label>
              <input
                type="text"
                class="form-control"
                id="username"
                placeholder="Username..."
              />
            </div>
            <div class="form-group">
              <label for="exampleInputEmail1">Email address</label>
              <input
                type="email"
                class="form-control"
                id="exampleInputEmail1"
                aria-describedby="emailHelp"
                placeholder="Enter email..."
              />
            </div>
            <div class="form-group">
              <label for="exampleInputPassword1">Password</label>
              <input
                type="password"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Password..."
              />
            </div>
            <div class="form-group">
              <label for="ConfirmPassword">Confirm Password</label>
              <input
                type="password"
                class="form-control"
                id="ConfirmPassword"
                placeholder="Confirm Password..."
              />
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
          </form>
        </div>
        <div class="col-sm"></div>
      </div>
    </div>
  </div>
</template>