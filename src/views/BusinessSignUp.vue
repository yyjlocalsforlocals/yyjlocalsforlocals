<template>
    <section class="section section-shaped section-lg my-0">
        <div class="shape shape-style-1 bg-gradient-default">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div>
        <div class="container pt-lg-md">
            <div class="row justify-content-center">
                <div class="col-lg-5">
                    <card type="secondary" shadow
                          header-classes="bg-white pb-5"
                          body-classes="px-lg-5 py-lg-5"
                          class="border-0">
                        <template>
                            <div class="text-center text-muted mb-4">
                                <small>Or sign up with credentials</small>
                            </div>
                            <form role="form">
                                <base-input alternative
                                            required
                                            class="mb-3"
                                            placeholder="Business Name"
                                            addon-left-icon="ni ni-hat-3">
                                </base-input>
                                <base-input alternative
                                            required
                                            class="mb-3"
                                            placeholder="Contact Name"
                                            addon-left-icon="ni ni-hat-3">
                                </base-input>
                                <base-input alternative
                                            required
                                            class="mb-3"
                                            placeholder="Email"
                                            addon-left-icon="ni ni-email-83">
                                </base-input>
                                <base-input alternative
                                            type="password"
                                            placeholder="Password"
                                            addon-left-icon="ni ni-lock-circle-open">
                                </base-input>
                                
                                <div class="mb-3">
                                    <small class="text-uppercase font-weight-bold">Business Type</small>
                                </div>
                                    <base-radio name="radio0" class="mb-3" v-model="radio.radio1">
                                        Restaurant
                                    </base-radio>
                                    <base-radio name="radio1" class="mb-3" v-model="radio.radio1">
                                        Retail Store
                                    </base-radio>
                                    <base-radio name="radio2" class="mb-3" v-model="radio.radio1">
                                        Hotel
                                    </base-radio>
                                    <textarea class="form-control form-control-alternative" rows="3" placeholder="Write a large text here ..."></textarea>
                                <div class="text-center">
                                    <base-button type="primary" class="my-4">Create account</base-button>
                                </div>
                            </form>
                        </template>
                    </card>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    data(){
        return {
         radio: {
           radio1: "radio1"
        }}}
};
</script>
<style>
</style>
