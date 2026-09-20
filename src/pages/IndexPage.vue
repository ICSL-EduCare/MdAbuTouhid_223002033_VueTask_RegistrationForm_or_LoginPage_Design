<template>
  <div class="q-pa-md flex flex-center bg-grey-3" style="min-height: 100vh;">
    
    <div style="max-width: 1100px; width: 100%;">
      <q-card class="my-card overflow-hidden shadow-10" style="border-radius: 12px;">
        
        <div class="row">
          
          <!-- Left Column -->
          <div class="col-12 col-md-7 bg-white q-pa-lg relative-position" style="min-height: 550px;">
            
            <!-- Exact Nested Row Structure from your Template -->
            <div class="row items-center">
              
              <!-- Logo Container (col-2) -->
              <div class="col-2 flex flex-center">
                <div class="logo-icon bg-coral text-white flex flex-center">
                  <q-icon name="bubble_chart" size="22px" />
                </div>
              </div>
              
              <!-- Menu Buttons Container (col-10) -->
              <div class="col-10">
                <div class="q-gutter-sm">
                  <q-btn label="SERVICES" color="grey-8" dense flat class="nav-btn" />
                  <q-btn label="OFFICES" color="deep-orange-5" dense flat class="nav-btn active-nav" />
                  <q-btn label="TEAM" color="grey-8" dense flat class="nav-btn" />
                  <q-btn label="PHILOSOPHY" color="grey-8" dense flat class="nav-btn" />
                  <q-btn label="SPACES" color="grey-8" dense flat class="nav-btn" />
                </div>
              </div>

            </div>

            <!-- Main Content Area (Person & Bio) -->
            <div class="row items-center justify-center relative-position q-mt-xl" style="height: 380px;">
              
              <!-- Background Red Circle -->
              <div class="coral-circle-bg"></div>
              
              <!-- Person Image -->
              <div class="person-wrapper z-top">
                <img 
                  src="touhid.png" 
                  alt="Lorraine Wolf" 
                  class="grayscale-img"
                />
              </div>

              <!-- Left Side Text Info -->
              <div class="bio-info z-top">
                <div class="text-caption text-grey-6 text-weight-bold letter-spacing-1">OUR TEAM</div>
                <div class="line-divider bg-grey-4 q-mb-sm"></div>
                <div class="text-subtitle2 text-grey-7">Lorraine Wolf</div>
                <div class="text-h5 text-weight-bold text-grey-9 leading-tight">
                  Technology <br /> lawyer
                </div>
                <div class="text-coral text-weight-bold cursor-pointer q-mt-sm hover-underline">
                  Explore
                </div>
              </div>

            </div>

          </div>

          <!-- Right Column (Hero Banner) -->
          <div class="col-12 col-md-5 bg-coral text-white q-pa-xl column justify-between" style="min-height: 550px;">
            
            <!-- Top Right Login Button -->
            <div class="row justify-end">
              <q-btn 
                outline 
                rounded 
                label="LOGIN" 
                class="q-px-lg text-weight-bold text-caption tracking-wider"
                style="border-color: rgba(255,255,255,0.8); color: white;" 
              />
            </div>

            <!-- Hero Banner Text -->
            <div class="q-my-auto q-py-lg">
              <h1 class="text-h3 text-weight-bolder q-mb-md leading-normal serif-font">
                Your legal advisers <br /> for the problems <br /> of this century
              </h1>
              <p class="text-subtitle2 text-white-8 text-weight-light q-mb-xl" style="opacity: 0.9;">
                We offer solutions adapted to <br /> today's needs
              </p>
              
              <q-btn 
                unelevated 
                color="white" 
                text-color="deep-orange-5" 
                label="VIEW MORE" 
                class="q-px-xl q-py-xs text-weight-bold custom-pill-btn"
              />
            </div>

            <div></div>

          </div>

        </div>

      </q-card>
    </div>

  </div>
</template>

<style scoped>
/* Color Palette */
.bg-coral {
  background-color: #ff5e53 !important;
}
.text-coral {
  color: #ff5e53 !important;
}

/* Nav Button Customization */
.nav-btn {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1px;
}
.active-nav {
  border-bottom: 2px solid #ff5e53;
  border-radius: 0;
}

/* Logo Styling */
.logo-icon {
  width: 36px;
  height: 36px;
  border-radius: 50%;
}

/* Image & Shape Graphics */
.coral-circle-bg {
  position: absolute;
  width: 250px;
  height: 250px;
  background-color: #ff5e53;
  border-radius: 50%;
  z-index: 1;
}

.person-wrapper {
  position: relative;
  width: 230px;
  height: 310px;
  overflow: hidden;
}

.grayscale-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  filter: grayscale(100%) contrast(1.1);
}

/* Text Overlay & Details */
.bio-info {
  position: absolute;
  left: 10px;
  bottom: 20px;
}

.line-divider {
  width: 40px;
  height: 2px;
}

.serif-font {
  font-family: 'Georgia', 'Times New Roman', serif;
}

.leading-normal {
  line-height: 1.15;
}

.leading-tight {
  line-height: 1.1;
}

.letter-spacing-1 {
  letter-spacing: 1px;
}

.hover-underline:hover {
  text-decoration: underline;
}

/* Pill Button Shape */
.custom-pill-btn {
  border-radius: 20px 0px 20px 20px;
  font-size: 11px;
  letter-spacing: 1px;
}
</style>