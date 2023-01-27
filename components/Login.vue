<template>

<div>
        <div class="nk-block-head">
        <div class="nk-block-head-content">
            <h5 class="nk-block-title">Welcome to ST X Modular</h5>
            <div class="nk-block-des">
                <p>Before you get started, you must login or register if you dont't have an account</p>
            </div>
        </div>
    </div>

     <h5 class="nk-block-title mb-2">Login</h5>

    <form action="#" class="is-alter" autocomplete="off">
        <div class="form-group">
            <div class="form-label-group">
                <label class="form-label">Email</label>
            </div>
            <div class="form-control-wrap">
                <input autocomplete="off" type="text" class="form-control form-control-lg" required placeholder="Enter your email address">
            </div>
        </div>
        <div class="form-group">
            <div class="form-label-group">
                <label class="form-label" for="password">Password</label>
                
            </div>
            <div class="form-control-wrap">
                <a tabindex="-1" href="#" class="form-icon form-icon-right passcode-switch lg" data-target="password">
                    <em class="passcode-icon icon-show icon ni ni-eye"></em>
                    <em class="passcode-icon icon-hide icon ni ni-eye-off"></em>
                </a>
                <input type="password" class="form-control form-control-lg" required placeholder="Enter your password">

                <div style="text-align: right;">
                    <a class="link link-primary link-sm mt-3" tabindex="-1" href="#"><NuxtLink to="/auth/forgot-pass">Forgot Password?</NuxtLink></a>
                </div>
            </div>
        </div>
        <div class="form-group">
            <button class="btn btn-lg btn-primary btn-block">Sign In</button>
        </div>
    </form>
</div>

</template>

<script>
export default {
  name: 'Login'
}
</script>
