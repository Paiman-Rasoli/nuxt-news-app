<template>
  <!-- Footer -->
  <mdb-footer color="blue-grey" class="page-footer font-small lighten-5 pt-0">
    <div style="backgroundColor: '#21d192'">
      <mdb-container class="text-left">
        <mdb-row class="py-4 d-flex align-items-center">
          <mdb-col md="6" lg="5" class="text-center text-md-left mb-4 mb-md-0">
            <h6 class="mb-0 white-text">
              Get connected with us on social networks!
            </h6>
          </mdb-col>
          <mdb-col md="6" lg="7" class="text-center text-md-right">
            <a class="fb-ic ml-0"
              ><i class="fab fa-facebook white-text mr-lg-4"> </i
            ></a>
            <a class="tw-ic"
              ><i class="fab fa-twitter white-text mr-lg-4"> </i
            ></a>
            <a class="gplus-ic"
              ><i class="fab fa-google-plus white-text mr-lg-4"> </i
            ></a>
            <a class="li-ic"
              ><i class="fab fa-linkedin-in white-text mr-lg-4"> </i
            ></a>
            <a class="ins-ic"
              ><i class="fab fa-instagram white-text mr-lg-4"> </i
            ></a>
          </mdb-col>
        </mdb-row>
      </mdb-container>
    </div>
    <mdb-container class="mt-5 mb-4 text-center text-md-left">
      <mdb-row class="mt-3">
        <mdb-col md="3" lg="4" xl="3" class="mb-4 dark-grey-text">
          <h6 class="text-uppercase font-weight-bold">
            <strong>Company name</strong>
          </h6>
          <hr
            class="deep-purple accent-2 mb-4 mt-0 d-inline-block mx-auto"
            style="width: 60px"
          />
          <p>
            Here you can use rows and columns here to organize your footer
            content. Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          </p>
        </mdb-col>
        <mdb-col md="2" lg="2" xl="2" class="mb-4 dark-grey-text">
          <h6 class="text-uppercase font-weight-bold">
            <strong>Products</strong>
          </h6>
          <hr
            class="deep-purple accent-2 mb-4 mt-0 d-inline-block mx-auto"
            style="width: 60px"
          />
          <p><a href="#!" class="dark-grey-text">MDBootstrap</a></p>
          <p><a href="#!" class="dark-grey-text">MDWordPress</a></p>
          <p><a href="#!" class="dark-grey-text">BrandFlow</a></p>
          <p><a href="#!" class="dark-grey-text">Bootstrap Angular</a></p>
        </mdb-col>
        <mdb-col md="3" lg="2" xl="2" class="mb-4 dark-grey-text">
          <h6 class="text-uppercase font-weight-bold">
            <strong>Useful links</strong>
          </h6>
          <hr
            class="deep-purple accent-2 mb-4 mt-0 d-inline-block mx-auto"
            style="width: 60px"
          />
          <p><a href="#!" class="dark-grey-text">Your Account</a></p>
          <p><a href="#!" class="dark-grey-text">Become an Affiliate</a></p>
          <p><a href="#!" class="dark-grey-text">Shipping Rates</a></p>
          <p><a href="#!" class="dark-grey-text">Help</a></p>
        </mdb-col>
        <mdb-col md="4" lg="3" xl="3" class="mb-4 dark-grey-text">
          <h6 class="text-uppercase font-weight-bold">
            <strong>Contact</strong>
          </h6>
          <hr
            class="deep-purple accent-2 mb-4 mt-0 d-inline-block mx-auto"
            style="width: 60px"
          />
          <p><i class="fas fa-home mr-3"></i> New York, NY 10012, US</p>
          <p><i class="fas fa-envelope mr-3"></i> info@example.com</p>
          <p><i class="fas fa-phone mr-3"></i> + 01 234 567 88</p>
          <p><i class="fas fa-print mr-3"></i> + 01 234 567 89</p>
        </mdb-col>
      </mdb-row>
    </mdb-container>
    <div class="footer-copyright text-center py-3">
      <mdb-container fluid>
        &copy; 2020 Copyright:
        <nuxt-link to="/">
          TutiaTech.com
        </nuxt-link>
      </mdb-container>
    </div>
  </mdb-footer>
  <!-- Footer -->
</template>
<script>
import { mdbFooter, mdbContainer, mdbRow, mdbCol } from "mdbvue";
export default {
  name: "FooterPage",
  components: {
    mdbFooter,
    mdbContainer,
    mdbRow,
    mdbCol
  }
};
</script>
