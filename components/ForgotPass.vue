<template>

<div>
        <div class="nk-block-head">
            <div class="nk-block-head-content">
                <h5 class="nk-block-title">Forgot Password</h5>
                <div class="nk-block-des">
                    <p>Don't remember your password's account? We will send reset link through your email</p>
                </div>
            </div>
        </div><!-- .nk-block-head -->

        <form action="#" class="is-alter" autocomplete="off">
            <div class="form-group">
                <div class="form-label-group">
                    <label class="form-label">Email</label>
                </div>
                <div class="form-control-wrap">
                    <input autocomplete="off" type="text" class="form-control form-control-lg" required placeholder="Enter your email address">
                </div>
            </div><!-- .form-group -->
            <div class="form-group">
                <button class="btn btn-lg btn-primary btn-block">Send reset password link</button>
            </div>
        </form>
</div>

</template>

<script>
export default {
  name: 'Forgot Password'
}
</script>
