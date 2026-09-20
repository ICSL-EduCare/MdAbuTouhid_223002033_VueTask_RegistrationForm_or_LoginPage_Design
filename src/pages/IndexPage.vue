<template>
  <div class="q-pa-xl bg-grey-3 flex flex-center" style="min-height: 100vh;">
    
    <div class="row q-col-gutter-lg items-start" style="max-width: 1350px; width: 100%;">
      
      <!-- ================= LEFT: MAIN COVER PAGE ================= -->
      <div class="col-12 col-lg-5">
        <q-card class="cover-card shadow-12 overflow-hidden bg-white q-pa-md">
          <div class="row no-wrap full-height relative-position overflow-hidden" style="min-height: 580px;">
            
            <!-- Left Vertical Dark Bar -->
            <div class="col-4 bg-black text-white flex flex-center q-pa-md z-top">
              <div class="vertical-title text-h3 text-weight-bolder letter-spacing-2">
                CREATIVE <br /> PORTFOLIO
              </div>
            </div>

            <!-- Main Cover Image -->
            <div class="col-8 relative-position bg-grey-2">
              <img 
                src="thd.jpg" 
                alt="Cover Image" 
                class="full-image cover-img"
              />
            </div>

          </div>

          <!-- Cover Footer Text -->
          <div class="row justify-between items-center q-pt-md text-caption text-grey-9 text-weight-bold">
            <div>
              Design By : <br />
              <span class="text-weight-regular text-grey-7">Md. Abu Touhid</span>
            </div>
            <div>2026</div>
          </div>
        </q-card>
      </div>

      <!-- ================= RIGHT: 2x3 SPREADS GRID ================= -->
      <div class="col-12 col-lg-7">
        <div class="row q-col-gutter-md">
          
          <!-- Spread 1: INDEX & ABOUT THE STUDIO -->
          <div class="col-12 col-md-6">
            <q-card class="spread-card shadow-2 bg-white q-pa-sm">
              <div class="row full-height">
                <!-- Page 1 (Index) -->
                <div class="col-6 q-pa-xs border-right flex column justify-between">
                  <div>
                    <div class="text-caption text-weight-bolder">INDEX</div>
                    <div class="index-menu q-mt-xs text-grey-8">
                      <div class="active-item">ABOUT THE STUDIO</div>
                      <div>TEAM</div>
                      <div>MISSION & VALUES</div>
                      <div>WORK</div>
                      <div>MODERN FASHION</div>
                    </div>
                  </div>
                  <!-- Vertical image at bottom right of Index page -->
                  <div class="row justify-end q-mt-xs">
                    <div style="width: 50px; height: 65px;">
                      <img src="thd.jpg" class="full-image fit-cover" />
                    </div>
                  </div>
                </div>
                <!-- Page 2 (About Studio) -->
                <div class="col-6 q-pa-xs flex column justify-between">
                  <div>
                    <div class="text-caption text-weight-bold">About The Studio</div>
                    <p class="tiny-text text-grey-7 q-mt-xs">Lorem ipsum dolor sit amet consectetur.</p>
                  </div>
                  <!-- Large Square/Portrait Image -->
                  <div style="height: 85px;" class="q-mt-xs">
                    <img src="thd.jpg" class="full-image fit-cover" />
                  </div>
                </div>
              </div>
            </q-card>
          </div>

          <!-- Spread 2: TEAM & MISSION-VALUES -->
          <div class="col-12 col-md-6">
            <q-card class="spread-card shadow-2 bg-white q-pa-sm">
              <div class="row full-height">
                <!-- Page 3 (Team) -->
                <div class="col-6 q-pa-xs border-right flex column justify-between">
                  <div>
                    <div class="text-caption text-weight-bolder">Team</div>
                    <p class="tiny-text text-grey-7">Creative Studio</p>
                  </div>
                  <!-- 3 Vertical Stacked Portrait Photos -->
                  <div class="column q-gutter-xs">
                    <div style="height: 28px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                    <div style="height: 28px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                    <div style="height: 28px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                  </div>
                </div>
                <!-- Page 4 (Mission-Values) -->
                <div class="col-6 q-pa-xs flex column justify-between">
                  <div>
                    <div class="text-caption text-weight-bold">Mission-Values</div>
                    <p class="tiny-text text-grey-7">OUR CLIENTS</p>
                  </div>
                  <!-- Single Tall Full-Length Model Photo -->
                  <div class="row justify-center">
                    <div style="width: 55px; height: 100px;">
                      <img src="thd.jpg" class="full-image fit-cover" />
                    </div>
                  </div>
                </div>
              </div>
            </q-card>
          </div>

          <!-- Spread 3: MODERN FASHION SHOW & MODERN FASHION -->
          <div class="col-12 col-md-6">
            <q-card class="spread-card shadow-2 bg-white q-pa-sm">
              <div class="row full-height">
                <!-- Page 5 (Modern Fashion Show) -->
                <div class="col-6 q-pa-xs border-right flex column justify-between">
                  <div>
                    <div class="text-caption text-weight-bold">Modern Fashion Show</div>
                  </div>
                  <!-- Big Square Hero Photo -->
                  <div style="height: 105px;">
                    <img src="thd.jpg" class="full-image fit-cover" />
                  </div>
                </div>
                <!-- Page 6 (Modern Fashion) -->
                <div class="col-6 q-pa-xs flex column justify-between">
                  <div>
                    <div class="text-caption text-weight-bold">Modern Fashion</div>
                  </div>
                  <!-- 1 Top Horizontal Photo + 2 Bottom Square Photos -->
                  <div class="column q-gutter-xs">
                    <div style="height: 45px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                    <div class="row q-gutter-x-xs no-wrap">
                      <div class="col-6" style="height: 45px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                      <div class="col-6" style="height: 45px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                    </div>
                  </div>
                </div>
              </div>
            </q-card>
          </div>

          <!-- Spread 4: NEW COLLECTION -->
          <div class="col-12 col-md-6">
            <q-card class="spread-card shadow-2 bg-white q-pa-sm">
              <div class="row full-height">
                <!-- Page 7 -->
                <div class="col-6 q-pa-xs border-right flex column justify-between">
                  <div>
                    <div class="text-caption text-weight-bolder">New Collection</div>
                  </div>
                  <!-- Tall Center Image -->
                  <div style="height: 110px;">
                    <img src="thd.jpg" class="full-image fit-cover" />
                  </div>
                </div>
                <!-- Page 8 -->
                <div class="col-6 q-pa-xs flex column justify-between">
                  <!-- 1 Top Right Square + 1 Bottom Left Square -->
                  <div class="row justify-end">
                    <div style="width: 55px; height: 55px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                  </div>
                  <div class="row justify-start">
                    <div style="width: 55px; height: 55px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                  </div>
                </div>
              </div>
            </q-card>
          </div>

          <!-- Spread 5: INTERIORS -->
          <div class="col-12 col-md-6">
            <q-card class="spread-card shadow-2 bg-white q-pa-sm">
              <div class="row full-height">
                <!-- Page 9 -->
                <div class="col-6 q-pa-xs border-right flex column justify-between">
                  <div>
                    <div class="text-caption text-weight-bolder">Interiors</div>
                  </div>
                  <!-- Top-Right Offset Image -->
                  <div style="height: 90px;" class="q-ml-md">
                    <img src="thd.jpg" class="full-image fit-cover" />
                  </div>
                </div>
                <!-- Page 10 -->
                <div class="col-6 q-pa-xs flex column justify-between">
                  <!-- Two Column Interior Photos -->
                  <div class="row q-gutter-x-xs no-wrap items-end" style="height: 120px;">
                    <div class="col-6" style="height: 100px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                    <div class="col-6" style="height: 70px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                  </div>
                </div>
              </div>
            </q-card>
          </div>

          <!-- Spread 6: BEST COLLECTION -->
          <div class="col-12 col-md-6">
            <q-card class="spread-card shadow-2 bg-white q-pa-sm">
              <div class="row full-height">
                <!-- Page 11 -->
                <div class="col-6 q-pa-xs border-right flex column justify-between">
                  <div>
                    <div class="text-caption text-weight-bolder">Best Collection</div>
                  </div>
                  <!-- 1 Tall Left Image + 1 Small Bottom Right Image -->
                  <div class="row q-gutter-x-xs items-end" style="height: 110px;">
                    <div class="col-6 full-height"><img src="thd.jpg" class="full-image fit-cover" /></div>
                    <div class="col-5" style="height: 50px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                  </div>
                </div>
                <!-- Page 12 -->
                <div class="col-6 q-pa-xs flex column justify-between">
                  <!-- Grid layout of 1 Tall + 2 Horizontal Right Images -->
                  <div class="row q-gutter-xs full-height items-center">
                    <div class="col-5" style="height: 80px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                    <div class="col-6 column q-gutter-xs">
                      <div style="height: 38px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                      <div style="height: 38px;"><img src="thd.jpg" class="full-image fit-cover" /></div>
                    </div>
                  </div>
                </div>
              </div>
            </q-card>
          </div>

        </div>
      </div>

    </div>

  </div>
</template>

<style scoped>
/* Image Helper Classes */
.full-image {
  width: 100%;
  height: 100%;
}

.fit-cover {
  object-fit: cover;
  border-radius: 1px;
}

.cover-img {
  object-fit: cover;
  object-position: center;
}

/* Vertical Typography */
.vertical-title {
  writing-mode: vertical-rl;
  transform: rotate(180deg);
  white-space: nowrap;
  letter-spacing: 3px;
  line-height: 1.1;
}

/* Card Containers */
.cover-card {
  border-radius: 2px;
}

.spread-card {
  height: 165px;
  border-radius: 2px;
  border: 1px solid #e2e2e2;
}

.border-right {
  border-right: 1px solid #ededed;
}

/* Micro Typography */
.index-menu {
  font-size: 6.5px;
  line-height: 1.3;
  font-weight: 600;
}

.active-item {
  border-bottom: 1px solid #000;
  display: inline-block;
  font-weight: 800;
}

.tiny-text {
  font-size: 7.5px;
  line-height: 1.1;
}

.letter-spacing-2 {
  letter-spacing: 2px;
}
</style>