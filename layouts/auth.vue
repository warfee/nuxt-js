<template>
	<div class="nk-app-root">
	    <div class="nk-main ">
	        <div class="nk-wrap nk-wrap-nosidebar">
	            <!-- content @s -->
	            <div class="nk-content ">
	                <div class="nk-split nk-split-page nk-split-lg">
	                    <div class="nk-split-content nk-block-area nk-block-area-column nk-auth-container bg-white">
	                        <div class="absolute-top-right d-lg-none p-3 p-sm-5">
	                            <a href="#" class="toggle btn-white btn btn-icon btn-light" data-target="athPromo"><em class="icon ni ni-info"></em></a>
	                        </div>
	                        <div class="nk-block nk-block-middle nk-auth-body">
	                            <div class="brand-logo pb-5">
	                                <a href="html/index.html" class="logo-link">
	                                    <img class="logo-light logo-img logo-img-lg" src="~/assets/images/stxm-logo.png" srcset="~assets/images/stxm-logo.png 2x" alt="logo">
	                                    <img class="logo-dark logo-img logo-img-lg" src="~/assets/images/stxm-logo.png" srcset="~/assets/images/stxm-logo.png 2x" alt="logo-dark">
	                                </a>
	                            </div>


	                                <Nuxt />


	                            <div class="text-center mt-5">
	                            	<div class="mb-3">
	                            		<NuxtLink to="/">Back To Home</NuxtLink>
	                            	</div>
	                            	

	                                <span class="fw-500">&copy; ST TECH. Product Of Sankyu Tech Sdn Bhd</span>
	                            </div>
	                        </div><!-- .nk-block -->
	                    </div><!-- .nk-split-content -->
	                    <div class="nk-split-content nk-split-stretch bg-lighter d-flex toggle-break-lg toggle-slide toggle-slide-right" data-toggle-body="true" data-content="athPromo" data-toggle-screen="lg" data-toggle-overlay="true">

	                        <img class="background" src="~/assets/images/login-background.jpeg" srcset="~assets/images/login-background.jpeg 2x" alt="">

	                    </div><!-- .nk-split-content -->
	                </div><!-- .nk-split -->
	            </div>
	            <!-- wrap @e -->
	        </div>
	        <!-- content @e -->
	    </div>
	</div>
</template>