<template>
  <div>
    <div class="text-white text-center d-flex flex-column align-items-center" style="height: 360px; background-image: url(https://cdn.shopify.com/s/files/1/0600/8573/1543/files/alexandr-podvalny-n_Jb_d8O43Q-unsplash.jpg?v=1633446432); background-size: cover; background-position-y: center; ">
      <div class="col-12 col-xxl-6 col-xl-6">
        <div class="fs-1 py-4 fw-bold">Frequently Asked Questions</div>
        <input class="mt-4 py-2 px-4 rounded-3 fs-5" style="width: 90%;" type="text" placeholder="What can we help you with?">
      </div>
    </div>
    <div class="px-4" style="background-color: #f8f0e4">
      <div class="container text-center p-4 row" style="margin: auto">
        <span class="fs-3 fw-bold">Featured FAQs</span>
        <div class="accordion col-6 text-start" id="accordionPanelsStayOpenExample">
          <div class="accordion-item my-3" style="border: none !important;">
            <div class="">
              <h2 class="accordion-header" id="featured-1">
                <div class="accordion-button text-white collapsed" style="background-color: #f8f0e4" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-featured-1" aria-expanded="false" aria-controls="panelsStayOpen-featured-1">
                  <span class="text-dark">Accordion Item #1</span>
                </div>
              </h2>
              <div id="panelsStayOpen-featured-1" class="accordion-collapse collapse" aria-labelledby="featured-1">
                <div class="accordion-body" style="background-color: #f8f0e4">
                  <strong>This is the first item's accordion body.</strong>.
                </div>
              </div>
            </div>
          </div>
          <div class="accordion-item my-3" style="border: none !important;">
            <h2 class="accordion-header" id="featured2">
              <div class="accordion-button text-white collapsed" style="background-color: #f8f0e4" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseTwo" aria-expanded="false" aria-controls="panelsStayOpen-collapseTwo">
                <span class="text-dark">Accordion Item #2</span>
              </div>
            </h2>
            <div id="panelsStayOpen-collapseTwo" class="accordion-collapse collapse" aria-labelledby="featured2">
              <div class="accordion-body" style="background-color: #f8f0e4">
                <strong>This is the second item's accordion body.</strong> 
              </div>
            </div>
          </div>
        </div>
        <div class="accordion col-6 text-start" id="accordionPanelsStayOpenExample">
          <div class="accordion-item my-3" style="border: none !important;">
            <div class="">
              <h2 class="accordion-header" id="featured3">
              <div class="accordion-button text-white collapsed" style="background-color: #f8f0e4" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapse3" aria-expanded="false" aria-controls="panelsStayOpen-collapse3">
                <span class="text-dark">Accordion Item #3</span>
              </div>
            </h2>
            <div id="panelsStayOpen-collapse3" class="accordion-collapse collapse" aria-labelledby="featured3">
              <div class="accordion-body" style="background-color: #f8f0e4">
                <strong>This is the first item's accordion body.</strong>
              </div>
            </div>
            </div>
          </div>
          <div class="accordion-item my-3" style="border: none !important;">
            <h2 class="accordion-header" id="featured4">
              <div class="accordion-button text-white collapsed" style="background-color: #f8f0e4" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapse4" aria-expanded="false" aria-controls="panelsStayOpen-collapse4">
                <span class="text-dark">Accordion Item #4</span>
              </div>
            </h2>
            <div id="panelsStayOpen-collapse4" class="accordion-collapse collapse" aria-labelledby="featured4">
              <div class="accordion-body " style="background-color: #f8f0e4">
                <strong>This is the second item's accordion body.</strong>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="d-flex justify-content-center my-4">
      <a href="#account" class="me-3">
        <button class="btn btn-primary">Account</button>
      </a>
      <a href="#gift-card" class="me-3">
        <button class="btn btn-primary">Gift card</button>
      </a>
    </div>
    <div class="container p-0 my-4" style="margin:auto">
      <div class="d-flex flex-column">
        <span id="account" class="fs-4">Account:</span>
        <div class="accordion" id="accordionPanelsStayOpenExample">
          <div class="accordion-item border my-3">
            <h2 class="accordion-header" id="account-1">
              <button class="accordion-button text-white collapsed" style="background-color: #0368a2" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-account-1" aria-expanded="false" aria-controls="panelsStayOpen-account-1">
                Accordion Item #1
              </button>
            </h2>
            <div id="panelsStayOpen-account-1" class="accordion-collapse collapse" aria-labelledby="account-1">
              <div class="accordion-body">
                <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
              </div>
            </div>
          </div>
          <!-- <div class="accordion-item border my-3">
            <h2 class="accordion-header" id="account-2">
              <button class="accordion-button text-white collapsed" style="background-color: #0368a2" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-account2" aria-expanded="false" aria-controls="panelsStayOpen-account2">
                Accordion Item #2
              </button>
            </h2>
            <div id="panelsStayOpen-account2" class="accordion-collapse collapse" aria-labelledby="account-2">
              <div class="accordion-body">
                <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
              </div>
            </div>
          </div>
          <div class="accordion-item border my-3">
            <h2 class="accordion-header" id="account-3">
              <button class="accordion-button text-white collapsed" style="background-color: #0368a2" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-account3" aria-expanded="false" aria-controls="panelsStayOpen-account3">
                Accordion Item #3
              </button>
            </h2>
            <div id="panelsStayOpen-account3" class="accordion-collapse collapse" aria-labelledby="account-3">
              <div class="accordion-body">
                <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
              </div>
            </div>
          </div> -->
        </div>
      </div>
      <div class="d-flex flex-column" id="gift-card">
        <span class="fs-4">Gift card:</span>
        <div class="accordion" id="accordionPanelsStayOpenExample">
          <div class="accordion-item border my-3">
            <h2 class="accordion-header" id="gift-card-1">
              <button class="accordion-button text-white collapsed" style="background-color: #0368a2" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-gift-card-1" aria-expanded="false" aria-controls="panelsStayOpen-gift-card-1">
                Accordion Item #1
              </button>
            </h2>
            <div id="panelsStayOpen-gift-card-1" class="accordion-collapse collapse" aria-labelledby="gift-card-1">
              <div class="accordion-body">
                <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
              </div>
            </div>
          </div>
          <!-- <div class="accordion-item border my-3">
            <h2 class="accordion-header" id="gift-card-2">
              <button class="accordion-button text-white collapsed" style="background-color: #0368a2" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-gift-card-2" aria-expanded="false" aria-controls="panelsStayOpen-gift-card-2">
                Accordion Item #2
              </button>
            </h2>
            <div id="panelsStayOpen-gift-card-2" class="accordion-collapse collapse" aria-labelledby="gift-card-2">
              <div class="accordion-body">
                <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
              </div>
            </div>
          </div>
          <div class="accordion-item border my-3">
            <h2 class="accordion-header" id="gift-card-3">
              <button class="accordion-button text-white collapsed" style="background-color: #0368a2" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-gift-card-3" aria-expanded="false" aria-controls="panelsStayOpen-gift-card-3">
                Accordion Item #3
              </button>
            </h2>
            <div id="panelsStayOpen-gift-card-3" class="accordion-collapse collapse" aria-labelledby="gift-card-3">
              <div class="accordion-body">
                <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
              </div>
            </div>
          </div> -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
/* .accordion-button{
  background-color: #0368a2;
}
.accordion-button:hover{
  background-color: #03517d !important
} */
</style>