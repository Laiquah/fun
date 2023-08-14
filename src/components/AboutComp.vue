<template>
    <div>
      <h3>Who are ClayExpressions?</h3>
      <div>
          <p>A pottery company dedicated to turning simple clay into exceptional art. We craft exquisite pottery pieces that combine aesthetics with functionality. Our foundation in craftsmanship and creativity sets us apart. Skilled artisans meticulously handcraft each piece, infusing expertise and imagination into every detail. Time-honored techniques like wheel throwing and glazing create a fusion of tradition and innovation. Our collection ranges from elegant vases inspired by nature to artistic tableware, each showcasing clay's versatility. We connect people with personal, meaningful art that sparks emotions and elevates experiences. Our pottery isn't just objects; they're enriching expressions of art. Discover the tactile beauty and creative spirit in each piece as we celebrate the timeless artistry of clay.</p>
      </div>
      <h3>Team</h3>
      <section id="team">
        <div class="row">
            <div class="col-3">
                <div class="book">
                    <p>Hello</p>
                    <div class="cover">
                        <p>Hover Me</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="book">
                    <p>Hello</p>
                    <div class="cover">
                        <p>Hover Me</p>
                    </div>
                </div>
            </div>
        <div class="col-3">
            <div class="book">
                <p>Hello</p>
                <div class="cover">
                    <p>Hover Me</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="book">
                <p>Hello</p>
                <div class="cover">
                    <p>Hover Me</p>
                </div>
            </div>
        </div>
        </div>
        <div class="row">
            <div class="col-3">
                <div class="book">
                    <p>Hello</p>
                    <div class="cover">
                        <p>Hover Me</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="book">
                    <p>Hello</p>
                    <div class="cover">
                        <p>Hover Me</p>
                    </div>
                </div>
            </div>
        <div class="col-3">
            <div class="book">
                <p>Hello</p>
                <div class="cover">
                    <p>Hover Me</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="book">
                <p>Hello</p>
                <div class="cover">
                    <p>Hover Me</p>
                </div>
            </div>
        </div>
        </div>
        <div class="row">
            <div class="col-3">
                <div class="book">
                    <p>Hello</p>
                    <div class="cover">
                        <p>Hover Me</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="book">
                    <p>Hello</p>
                    <div class="cover">
                        <p>Hover Me</p>
                    </div>
                </div>
            </div>
        <div class="col-3">
            <div class="book">
                <p>Hello</p>
                <div class="cover">
                    <p>Hover Me</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="book">
                <p>Hello</p>
                <div class="cover">
                    <p>Hover Me</p>
                </div>
            </div>
        </div>
        </div>
        <div class="row">
            <div class="col-3">
                <div class="book">
                    <p>Hello</p>
                    <div class="cover">
                        <p>Hover Me</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="book">
                    <p>Hello</p>
                    <div class="cover">
                        <p>Hover Me</p>
                    </div>
                </div>
            </div>
        <div class="col-3">
            <div class="book">
                <p>Hello</p>
                <div class="cover">
                    <p>Hover Me</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="book">
                <p>Hello</p>
                <div class="cover">
                    <p>Hover Me</p>
                </div>
            </div>
        </div>
        </div>
      </section>
      <h3>Services & Partnerships</h3>
      <section id="services">
        <p>We offer a variety of services, including doorstep delivery. Additionally, we operate an art shop where we teach people how to create their desired designs. Moreover, we have a studio where you can personally craft your own items. Our studio is called ClayCraft Haven.</p>
      </section>
      <section id="partnerships">

      </section>
      <h3>ClayCraft Haven</h3>
      <section id="studio">
        <p>Where clay and imagination unite, crafting timeless artistry that enriches your space. Our studio blends ancient pottery techniques with modern innovation, welcoming artisans and beginners alike to a community fueled by clay's passion. We shape elegant pottery, from nature-inspired vases to functional tableware, embodying both form and function. Our art shop, guided by skilled mentors, offers materials and inspiration, while workshops refine skills. Step into our studio, where clay comes alive through expert guidance, transforming raw material into personalized art. Discover a sanctuary for those who express through clay, uniting individuality and artistry.</p>
        <p></p>
      </section>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
h3{
    text-decoration: underline;
}

.row{
    --bs-gutter-x: 0rem;
}

.book {
    position: relative;
    margin-bottom: 2rem;
    margin-left: 3rem;
    border-radius: 10px;
    width: 220px;
    height: 300px;
    background-color: whitesmoke;
    -webkit-box-shadow: 1px 1px 12px #000;
    box-shadow: 1px 1px 12px #000;
    -webkit-transform: preserve-3d;
    -ms-transform: preserve-3d;
    transform: preserve-3d;
    -webkit-perspective: 2000px;
    perspective: 2000px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    color: #000;
  }
  
  .cover {
    top: 0;
    position: absolute;
    background-color: lightgray;
    width: 100%;
    height: 100%;
    border-radius: 10px;
    cursor: pointer;
    -webkit-transition: all 0.5s;
    transition: all 0.5s;
    -webkit-transform-origin: 0;
    -ms-transform-origin: 0;
    transform-origin: 0;
    -webkit-box-shadow: 1px 1px 12px #000;
    box-shadow: 1px 1px 12px #000;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
  
  .book:hover .cover {
    -webkit-transition: all 0.5s;
    transition: all 0.5s;
    -webkit-transform: rotatey(-80deg);
    -ms-transform: rotatey(-80deg);
    transform: rotatey(-80deg);
  }
  
  p {
    font-size: 20px;
    font-weight: bolder;
  }
</style>