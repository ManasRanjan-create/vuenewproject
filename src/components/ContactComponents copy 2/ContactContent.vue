<template>
  <div>
    <div class="container-fluid">
      <div class="map">
        <iframe
          data-v-34b157ca=""
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2490.4252103120607!2d-0.08434148436935351!3d51.37686267961394!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x487600cff36bb14b%3A0x432f300759858f54!2sCanning%20Rd%2C%20Croydon%20CR0%206QB%2C%20UK!5e0!3m2!1sen!2sin!4v1635156277135!5m2!1sen!2sin"
          class="d-block h-100px w-100"
          loading="lazy"
          style="border: 0px none"
        ></iframe>
      </div>
    </div>
    <div class="row row-cols-1 py-5 row-cols-md-3 g-3">
      <div class="card me-3"   style="width: calc(33.33% - 16px);">
        <div class="mx-auto" style="width: 200px">
          <h3>Mail to us</h3>
        </div >
        <div class="mx-auto" style="width: 200px">
          <a href="#" class="btn btn-basic">
            <h6>info@earlsdon.org</h6>
          </a>
        </div>
      </div>
      <div class="card me-3" style="width: calc(33.33% - 16px);">
        <div class="mx-auto" style="width: 200px">
          <h3>Call for Help</h3>
        </div>
        <div class="mx-auto" style="width: 200px">
          <a href="#" class="btn btn-basic">
            <h6>0203 026 7913</h6>
          </a>
        </div>
      </div>
      <div class="card" style="width: calc(33.33% - 16px);">
        <div class="mx-auto" style="width: 200px">
          <h3>Our Address</h3>
        </div>
        <div class="mx-auto" style="width: 200px">
          <a href="#" class="btn btn-basic">
            <h6>
              0203Earlsdon Limited, 9 Geoffery Jones Court, 345-347 Harlesden
              Road, NW10 3RW
            </h6>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "ContactContent",
};
</script>
