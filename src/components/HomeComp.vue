<template>
<div>
  <header class="header">
    <nav>
      <ul>
        <li>
          <button @click="openModal()" class="login-btn">Log in</button>
        </li>
      </ul>
    </nav>
    <div class="header-content">
      <h4>Try up to one month free</h4>
      <img class="logo" src="@/assets/logo.png" alt="">
      <div class="header-text-1">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eum, repellat.
      </div>
      <div class="header-text-2">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus corrupti provident tempore.
      </div>
      <button class="btn btn-cta">
        Start your free trial
      </button>
      <div class="legal-text">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Explicabo, minima!
      </div>
    </div>
  </header>
  <section class="sub-header">
    <img src="@/assets/logos.png" alt="">
    <div>
      <h4>Bundle with any Hulu plan &amp; save</h4>
      <h3>Get Hulu, Disney+, etc.</h3>
      <a href="#" class="sub-link">Details</a>
    </div>
    <div>
      <a href="#" class="btn btn-outline">Get Bundle</a>
      <a href="#" class="sub-link">Terms apply</a>
    </div>
  </section>

  <section class="categories">
    <h4>Included in all plans</h4>
    <div class="text-xl">All the TV you love</div>
    <div class="sub-text">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eum repellendus perferendis iusto magnam numquam quam iste. Blanditiis, maiores!
    </div>

    <div class="covers">
      <div class="cover-1">
        <div class="cover-grad"></div>
        <div class="cover-text">
          <div class="sub-title">Past &amp; current seasons</div>
          <h3>TV Shows</h3>
        </div>
      </div>
        <div class="cover-2">
        <div class="cover-grad"></div>
        <div class="cover-text">
          <div class="sub-title">New &amp; classics</div>
          <h3>Movies</h3>
        </div>
      </div>
        <div class="cover-3">
        <div class="cover-grad"></div>
        <div class="cover-text">
          <div class="sub-title">Groundbreaking</div>
          <h3>Hulu originals</h3>
        </div>
      </div>
        <div class="cover-4">
        <div class="cover-grad"></div>
        <div class="cover-text">
          <div class="sub-title">Add-On</div>
          <h3>Premiums</h3>
        </div>
      </div>
    </div>
  </section>

  <section class="live">
    <div class="live-border">
      <h4>Hulu + Live TV</h4>
      <div class="text-xl">Live TV Makes It Better</div>
      <div class="sub-text">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quo animi obcaecati iusto facere dolore optio porro necessitatibus libero commodi
      </div>
      <div class="legal-text">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde nihil esse provident nisi eveniet?
      </div>
      <a href="#">View Channels in Your Area</a>
    </div>
  </section>

  <section class="live-sports">
    <div class="live-sports-content">
      <div class="text-xl">Live Sports</div>
      <div class="sub-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem culpa magnam, similique aliquam maxime voluptates perferendis unde consequuntur quo sit!
      <div class="live-sports-logos">
        <div>
          <img src="@/assets/live-sports-logo-1.png" alt="">
        </div>
        <div>
          <img src="@/assets/live-sports-logo-2.png" alt="">
        </div>
        <div>
          <img src="@/assets/live-sports-logo-3.svg" alt="">
        </div>
        <div>
          <img src="@/assets/live-sports-logo-4.png" alt="">
        </div>
      </div>
      <div class="legal-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias cum tempora vel doloremque! Autem, aliquam.
      </div>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="footer-container">
      <div class="footer-lists">
         <ul>
            <li class="list-head">BROWSE</li>
            <li><a href="#">Streaming Library</a></li>
            <li><a href="#">Live TV</a></li>
            <li><a href="#">Live News</a></li>
            <li><a href="#">Live Sports</a></li>
          </ul>
          <ul>
            <li><a href="#">TV Shows</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">Originals</a></li>
            <li><a href="#">Networks</a></li>
            <li><a href="#">Kids</a></li>
            <li><a href="#">FX on Hulu</a></li>
          </ul>
          <ul>
            <li><a href="#">Hulu, Disney+, and ESPN+</a></li>
            <li><a href="#">Disney Bundle</a></li>
            <li><a href="#">HBO Max</a></li>
            <li><a href="#">Cinimax</a></li>
            <li><a href="#">Showtime</a></li>
            <li><a href="#">STARZ</a></li>
          </ul>
          <ul>
            <li class="list-head">HELP</li>
            <li><a href="#">Account &amp; Billing</a></li>
            <li><a href="#">Plans &amp; Pricing</a></li>
            <li><a href="#">Supported Devices</a></li>
            <li><a href="#">Accesibility</a></li>
          </ul>
          <ul>
            <li class="list-head">ABOUT US</li>
            <li><a href="#">Press</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
      </div>
      <div class="divider"></div>
      <div class="social-icons">
          <a href="#"><img src="@/assets/facebook.svg" alt="" /></a>
          <a href="#"><img src="@/assets/twitter.svg" alt="" /></a>
          <a href="#"><img src="@/assets/youtube.svg" alt="" /></a>
          <a href="#"><img src="@/assets/instagram.svg" alt="" /></a>
      </div>
    </div>
  </footer>

  <div class="modal">
    <div class="modal-box">
      <div class="modal-body">
        <h3>Log In</h3>
        <form action="#">
          <div class="form-control">
             <label for="email">Email</label>
            <input type="email" id="email">
          </div>
          <div class="form-control">
            <label for="password">Password</label>
            <input type="password" id="password">
          </div>
          <p><a href="#">Forgot you email or password?</a></p>
          <button class="btn btn-dark">Login</button>
        </form>
      </div>
      <div class="modal-footer">
        <p>Lorem ipsum, dolor sit amet <a href="#">consectetur adipisicing</a> elit. Itaque, totam.</p>
      </div>
      <img @click="closeModal()" class="close" src="@/assets/close.svg" alt="">
    </div>
  </div>
</div>
</template>

<script>
  export default {
    data: () => ({
    }),
    methods: {
      openModal(){
        const modal = document.querySelector('.modal')
        modal.style.display = 'block' //modifies the display ruleset of class modal
      },
      closeModal(){
        const modal = document.querySelector('.modal')
        modal.style.display = 'none' //modifies the display ruleset of class modal
      },
      outsideClick(e){ //closes the modal when user clicks outside the element
        const modal = document.querySelector('.modal')
        if (e.target == modal) {
          this.closeModal()
        }
      }
    },
    mounted(){
      window.addEventListener('click', this.outsideClick) //allows modal to close when user clicks outside the element
    }
  }
</script>
