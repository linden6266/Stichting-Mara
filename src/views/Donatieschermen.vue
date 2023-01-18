<template>
    <div>
        <div class="wrapper">
        <div data-animation="default" data-collapse="medium" data-duration="400" data-easing="ease" data-easing2="ease" role="banner" class="navbar w-nav">
          <div class="container w-container">
    <Navbar/>
          </div>
        </div>
        <div class="donaties--section wf-section">
          <div class="container _w-90 w-container">
            <div class="w-form">
              <form id="email-form-2" name="email-form-2" data-name="Email Form 2" method="get">
                <div class="donaties-grid">
  <Amount/>
    <Data/>
    <Payment/>
                </div>
              </form>
              <div class="w-form-done">
                <div>Thank you! Your submission has been received!</div>
              </div>
              <div class="w-form-fail">
                <div>Oops! Something went wrong while submitting the form.</div>
              </div>
            </div>
          </div>
        </div>
    <Footer/>
      </div>
    
    
    </div>
    
    
    </template>
    
    <script>  
import Navbar from '@/components/Navbar.vue';
import Amount from '@/components/Amount.vue';
import Data from '@/components/Data.vue';
import Payment from '@/components/Payment.vue';
import Footer from '@/components/Footer.vue';
    
    
    export default {
        components: {

    Navbar,
    Amount,
    Data,
    Payment,
    Footer
},
        props: [
            "input_var",
        ],
        data: () => {
            return {
                // example1: "hoi"
            }
        },
        methods: {
            // clickMethod( input_var ) {
    
            // return output
            // }
        },
        computed: {},
        watch: {
            input_var: {
                handler() {
                    // console.log( "is changed")
                }
            },
            deep: true
        }
    
    
    }
    </script>