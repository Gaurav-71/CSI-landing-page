<template>
  <div class="home">
    <v-app class="custom-background">
      <v-app-bar app class="custom-gradient">
        <div class="d-flex align-center justify-center custom-center">
          <v-img
            alt="CSI Logo"
            src="../assets/csi.png"
            transition="scale-transition"
            contain
            width="45"
            class="shrink"
          />
          <v-divider vertical class="mx-4" dark />
          <v-img
            alt="RIT logo"
            src="../assets/ramaiah-white.png"
            transition="scale-transition"
            contain
            width="140"
            class="shrink"
          />
        </div>
        <v-spacer class="d-none d-sm-flex"></v-spacer>
        <v-btn target="_blank" class="d-none d-sm-flex white--text" color="#E34E4B">
          <span class="mr-2">Register Now</span>
          <v-icon>mdi-open-in-new</v-icon>
        </v-btn>
      </v-app-bar>
      <v-container>
        <v-layout row wrap class="mx-1 mt-3">
          <v-flex xs12 md6 class="my-3">
            <h1 class="display-3 font-weight-black custom-color-primary">CODE FOR THOUGHT</h1>
            <h3
              class="font-weight-medium my-5 custom-color-secondary"
            >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Distinctio adipisci eveniet voluptatem fugiat, repellendus qui itaque pariatur sunt animi neque placeat. Veritatis nobis hic similique dolorem accusamus, voluptate cupiditate fuga?</h3>
            <p class="font-weight-regular mb-6" style="color: #374957;">
              Department of MCA, CSE & ISE
              <br />In collaboration with RIT-CSI student chapter & CSI Region V
            </p>
            <v-divider class="my-4" />
            <v-layout row wrap justify-center class="mx-1">
              <v-flex xs12 sm6 class="my-3">
                <div class="custom-flex">
                  <img alt="CSI Logo" src="../assets/calendar.svg" transition="scale-transition" />
                  <div>
                    <p class="ma-0 ml-2 font-weight-bold">Date</p>
                    <p class="ma-0 ml-2 font-weight-regular custom-color-secondary">18th July 2020</p>
                  </div>
                </div>
              </v-flex>
              <v-flex xs12 sm6 class="my-3">
                <div class="custom-flex">
                  <img alt="CSI Logo" src="../assets/alarm.svg" transition="scale-transition" />
                  <div>
                    <p class="ma-0 ml-3 mt-1 font-weight-bold">Time</p>
                    <p class="ma-0 ml-3 font-weight-regular custom-color-secondary">11am to 11pm</p>
                  </div>
                </div>
              </v-flex>
            </v-layout>
            <v-divider class="my-4" />
            <v-layout column justify-center align-center class="mt-5">
              <v-btn target="_blank" class="white--text" rounded large color="#E34E4B">
                <span class="mr-2">Register Now</span>
                <v-icon>mdi-open-in-new</v-icon>
              </v-btn>
              <p class="my-4">
                <b>Note</b> : Registration fee of Rs. 100 for non-CSI members, free for CSI members
              </p>
            </v-layout>
          </v-flex>
          <v-flex xs12 md6 class="my-3 d-none d-sm-flex">
            <v-layout column align-center>
              <img src="../assets/desk.svg" alt="illustration" class="illustration" />
              <div class="my-3">
                <div class="time-container">
                  <span class="display-4 font-weight-bold custom-color-primary mx-3">{</span>
                  <span class="time">
                    <div class="display-1 font-weight-light">{{days}}</div>
                    <h2 class="font-weight-normal ma-0">Days</h2>
                  </span>
                  <span class="font-weight-normal mx-4 display-2 custom-color-primary">:</span>
                  <span class="time">
                    <div class="display-1 font-weight-light">{{hours}}</div>
                    <h2 class="font-weight-normal ma-0">Hours</h2>
                  </span>
                  <span class="font-weight-normal mx-4 display-2 custom-color-primary">:</span>
                  <span class="time">
                    <div class="display-1 font-weight-light">{{minutes}}</div>
                    <h2 class="font-weight-normal ma-0">Mins</h2>
                  </span>
                  <span class="font-weight-normal mx-4 display-2 custom-color-primary">:</span>
                  <span class="time">
                    <div class="display-1 font-weight-light">{{seconds}}</div>
                    <h2 class="font-weight-normal ma-0">Secs</h2>
                  </span>
                  <span class="display-4 font-weight-bold custom-color-primary mx-3">}</span>
                </div>
              </div>
            </v-layout>
          </v-flex>
        </v-layout>
        <v-divider class="mb-3"></v-divider>
        <v-layout row wrap class="mx-1" justify-center align-center>
          <v-flex xs12 md12 class="my-3">
            <div class="trophy">
              <img src="../assets/trophy.svg" alt="trophy" />
              <h1 class="ml-1">Exciting cash prizes for top winners !</h1>
            </div>
          </v-flex>
          <v-flex xs12 md4 class="my-3">
            <div class="custom-flex-prizes">
              <img src="../assets/medal.svg" alt="first-prize" />
              <div>
                <div>
                  <p class="ma-0 ml-2 font-weight-bold">1st Prize</p>
                  <p class="ma-0 ml-2 font-weight-regular custom-color-secondary">Rs. 3000 /-</p>
                </div>
              </div>
            </div>
          </v-flex>
          <v-flex xs12 md4 class="my-3">
            <div class="custom-flex-prizes">
              <img src="../assets/second.svg" alt="first-prize" />
              <div>
                <div>
                  <p class="ma-0 font-weight-bold">2nd Prize</p>
                  <p class="ma-0 font-weight-regular custom-color-secondary">Rs. 1500 /-</p>
                </div>
              </div>
            </div>
          </v-flex>
          <v-flex xs12 md4 class="my-3">
            <div class="custom-flex-prizes">
              <img src="../assets/patent.svg" alt="second-prize" />
              <div>
                <div>
                  <p class="ma-0 font-weight-bold">Best performers</p>
                  <p class="ma-0 font-weight-regular custom-color-secondary">E-certificates</p>
                </div>
              </div>
            </div>
          </v-flex>
        </v-layout>
        <v-divider class="my-3"></v-divider>
        <v-layout row wrap class="mx-1" justify-center align-center>
          <v-flex xs12 md12 class="my-3">
            <div class="trophy">
              <img src="../assets/questions.svg" alt="information" />
              <h1 class="font-weight-light">
                <b class="font-weight-bold">Any Queries ?</b> Contact Us
              </h1>
            </div>
          </v-flex>
          <v-flex xs12 sm6 md3 class="my-1">
            <v-card class="ma-5 custom-card-secondary" max-width="300" hover>
              <v-card-text>
                <h2 class="font-weight-normal custom-color-primary">Dr. S Ajitha</h2>
                <p class="ma-0 mt-2">Dept. of MCA</p>
                <div class="text--primary">CSI Student Branch Coordinator</div>
              </v-card-text>
              <v-divider class="mt-1" />
              <div class="custom-flex custom-card-primary">
                <img
                  src="../assets/phone.svg"
                  alt="call-us"
                  style="width: 23px;height: 23px;margin: 0.5rem 1rem;"
                />
                <div class="white--text">7760002530</div>
              </div>
            </v-card>
          </v-flex>
          <v-flex xs12 sm6 md3 class="my-1">
            <v-card class="ma-5 custom-card-secondary" max-width="300" hover>
              <v-card-text>
                <h2 class="font-weight-normal custom-color-primary">Dr. Monica R Mundada</h2>
                <p class="ma-0 mt-2">Dept. of CSE</p>
                <div class="text--primary">Faculty Coordinator</div>
              </v-card-text>
              <v-divider class="mt-1" />
              <div class="custom-flex custom-card-primary">
                <img
                  src="../assets/phone.svg"
                  alt="call-us"
                  style="width: 23px;height: 23px;margin: 0.5rem 1rem;"
                />
                <div class="white--text">9980315974</div>
              </div>
            </v-card>
          </v-flex>
          <v-flex xs12 sm6 md3 class="my-1">
            <v-card class="ma-5 custom-card-secondary" max-width="300" hover>
              <v-card-text>
                <h2 class="font-weight-normal custom-color-primary">Dr. Megha Arkeri</h2>
                <p class="ma-0 mt-2">Dept. of ISE</p>
                <div class="text--primary">Faculty Coordinator</div>
              </v-card-text>
              <v-divider class="mt-1" />
              <div class="custom-flex custom-card-primary">
                <img
                  src="../assets/phone.svg"
                  alt="call-us"
                  style="width: 23px;height: 23px;margin: 0.5rem 1rem;"
                />
                <div class="white--text">9008977922</div>
              </div>
            </v-card>
          </v-flex>
          <v-flex xs12 sm6 md3 class="my-1">
            <v-card class="ma-5 custom-card-secondary" max-width="300" hover>
              <v-card-text>
                <h2 class="font-weight-normal custom-color-primary">Ananya Pramod</h2>
                <p class="ma-0 mt-2">Student of CSE</p>
                <div class="text--primary">Student Coordinator</div>
              </v-card-text>
              <v-divider class="mt-1" />
              <div class="custom-flex custom-card-primary">
                <img
                  src="../assets/phone.svg"
                  alt="call-us"
                  style="width: 23px;height: 23px;margin: 0.5rem 1rem;"
                />
                <div class="white--text">7760002530</div>
              </div>
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
      <p
        class="custom-gradient mb-0 pa-2"
        style="text-align:center;color:gray"
      >Ramaiah Institute of Technology, Autonomous institute, Affilliated to VTU, Approved by AICTE - New Delhi & Govt. of Karnataka, MSR Nagar, MSRIT Post, Bangalore - 560054, Karnataka</p>
    </v-app>
  </div>
</template>

<script>
export default {
  data() {
    return {
      days: 0,
      hours: 0,
      minutes: 0,
      seconds: 0
    };
  },
  methods: {
    result() {
      let end = new Date("2020-07-18");
      let start = new Date();
      let remTime = end.getTime() - start.getTime();
      let mm = Math.floor(remTime / (1000 * 60));
      let hh = Math.floor(mm / 60);
      let dd = Math.floor(hh / 24);
      let ss = Math.floor(remTime / 1000);
      hh %= 24;
      mm %= 60;
      ss %= 60;
      hh = hh < 0 ? "0" : hh < 10 ? "0" + hh : hh;
      mm = mm < 0 ? "0" : mm < 10 ? "0" + mm : mm;
      ss = ss < 0 ? "0" : ss < 10 ? "0" + ss : ss;
      this.days = dd;
      this.hours = hh;
      this.minutes = mm;
      this.seconds = ss;
      if (start >= end) {
        this.days = 0;
        this.hours = 0;
        this.minutes = 0;
        this.seconds = 0;
      }
      setTimeout(this.result, 1000);
    }
  },
  mounted() {
    this.result();
  }
};
</script>


<style lang="scss" scoped>
.custom-center{
  @media (max-width: 414px){
    display: block;
    margin: 0 auto;
  }
}
.trophy {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  img {
    width: 80px;
    height: 80px;
  }
}
.time-container {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.time {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.custom-color-primary {
  color: #e34e4b;
}
.custom-card-primary {
  background: #e34e4b;
}
.custom-color-secondary {
  color: #374957;
}
.custom-card-secondary {
  text-align: center;
  background: #f9f5f3;
}
.custom-flex,
.custom-flex-prizes {
  display: flex;
  height: auto;
  align-items: center;
  justify-content: center;
  img {
    width: 70px;
    height: 70px;
  }
}
.custom-flex-prizes {
  flex-direction: column;
  div {
    margin-top: 0.3rem;
    text-align: center;
  }
}
.illustration {
  width: 515px;
  height: 350px;
  @media (max-width: 1024px) {
    width: 420px;
    height: 350px;
  }
  @media (max-width: 414px) {
    width: 215px;
    height: 250px;
  }
}
.custom-gradient {
  background-image: linear-gradient(
      448deg,
      rgba(213, 213, 213, 0.01) 0%,
      rgba(213, 213, 213, 0.01) 14.286%,
      rgba(140, 140, 140, 0.01) 14.286%,
      rgba(140, 140, 140, 0.01) 28.572%,
      rgba(52, 52, 52, 0.01) 28.572%,
      rgba(52, 52, 52, 0.01) 42.858%,
      rgba(38, 38, 38, 0.01) 42.858%,
      rgba(38, 38, 38, 0.01) 57.144%,
      rgba(159, 159, 159, 0.01) 57.144%,
      rgba(159, 159, 159, 0.01) 71.42999999999999%,
      rgba(71, 71, 71, 0.01) 71.43%,
      rgba(71, 71, 71, 0.01) 85.71600000000001%,
      rgba(88, 88, 88, 0.01) 85.716%,
      rgba(88, 88, 88, 0.01) 100.002%
    ),
    linear-gradient(
      517deg,
      rgba(25, 25, 25, 0.01) 0%,
      rgba(25, 25, 25, 0.01) 12.5%,
      rgba(150, 150, 150, 0.01) 12.5%,
      rgba(150, 150, 150, 0.01) 25%,
      rgba(84, 84, 84, 0.01) 25%,
      rgba(84, 84, 84, 0.01) 37.5%,
      rgba(85, 85, 85, 0.01) 37.5%,
      rgba(85, 85, 85, 0.01) 50%,
      rgba(188, 188, 188, 0.01) 50%,
      rgba(188, 188, 188, 0.01) 62.5%,
      rgba(80, 80, 80, 0.01) 62.5%,
      rgba(80, 80, 80, 0.01) 75%,
      rgba(73, 73, 73, 0.01) 75%,
      rgba(73, 73, 73, 0.01) 87.5%,
      rgba(219, 219, 219, 0.01) 87.5%,
      rgba(219, 219, 219, 0.01) 100%
    ),
    linear-gradient(
      380deg,
      rgba(233, 233, 233, 0.01) 0%,
      rgba(233, 233, 233, 0.01) 25%,
      rgba(114, 114, 114, 0.01) 25%,
      rgba(114, 114, 114, 0.01) 50%,
      rgba(164, 164, 164, 0.01) 50%,
      rgba(164, 164, 164, 0.01) 75%,
      rgba(228, 228, 228, 0.01) 75%,
      rgba(228, 228, 228, 0.01) 100%
    ),
    linear-gradient(
      383deg,
      rgba(139, 139, 139, 0.02) 0%,
      rgba(139, 139, 139, 0.02) 16.667%,
      rgba(44, 44, 44, 0.02) 16.667%,
      rgba(44, 44, 44, 0.02) 33.334%,
      rgba(166, 166, 166, 0.02) 33.334%,
      rgba(166, 166, 166, 0.02) 50.001000000000005%,
      rgba(2, 2, 2, 0.02) 50.001%,
      rgba(2, 2, 2, 0.02) 66.668%,
      rgba(23, 23, 23, 0.02) 66.668%,
      rgba(23, 23, 23, 0.02) 83.33500000000001%,
      rgba(21, 21, 21, 0.02) 83.335%,
      rgba(21, 21, 21, 0.02) 100.002%
    ),
    linear-gradient(
      508deg,
      rgba(3, 3, 3, 0.03) 0%,
      rgba(3, 3, 3, 0.03) 12.5%,
      rgba(116, 116, 116, 0.03) 12.5%,
      rgba(116, 116, 116, 0.03) 25%,
      rgba(214, 214, 214, 0.03) 25%,
      rgba(214, 214, 214, 0.03) 37.5%,
      rgba(217, 217, 217, 0.03) 37.5%,
      rgba(217, 217, 217, 0.03) 50%,
      rgba(68, 68, 68, 0.03) 50%,
      rgba(68, 68, 68, 0.03) 62.5%,
      rgba(118, 118, 118, 0.03) 62.5%,
      rgba(118, 118, 118, 0.03) 75%,
      rgba(200, 200, 200, 0.03) 75%,
      rgba(200, 200, 200, 0.03) 87.5%,
      rgba(198, 198, 198, 0.03) 87.5%,
      rgba(198, 198, 198, 0.03) 100%
    ),
    linear-gradient(
      270deg,
      rgba(195, 195, 195, 0.03) 0%,
      rgba(195, 195, 195, 0.03) 16.667%,
      rgba(177, 177, 177, 0.03) 16.667%,
      rgba(177, 177, 177, 0.03) 33.334%,
      rgba(170, 170, 170, 0.03) 33.334%,
      rgba(170, 170, 170, 0.03) 50.001000000000005%,
      rgba(158, 158, 158, 0.03) 50.001%,
      rgba(158, 158, 158, 0.03) 66.668%,
      rgba(121, 121, 121, 0.03) 66.668%,
      rgba(121, 121, 121, 0.03) 83.33500000000001%,
      rgba(146, 146, 146, 0.03) 83.335%,
      rgba(146, 146, 146, 0.03) 100.002%
    ),
    linear-gradient(
      497deg,
      rgba(103, 103, 103, 0.03) 0%,
      rgba(103, 103, 103, 0.03) 25%,
      rgba(112, 112, 112, 0.03) 25%,
      rgba(112, 112, 112, 0.03) 50%,
      rgba(4, 4, 4, 0.03) 50%,
      rgba(4, 4, 4, 0.03) 75%,
      rgba(227, 227, 227, 0.03) 75%,
      rgba(227, 227, 227, 0.03) 100%
    ),
    linear-gradient(277deg, hsl(98, 0%, 0%), hsl(98, 0%, 0%));
  //  background-image: linear-gradient(148deg, rgba(15, 15, 15,0.04) 0%, rgba(15, 15, 15,0.04) 35%,rgba(113, 113, 113,0.04) 35%, rgba(113, 113, 113,0.04) 42%,rgba(210, 210, 210,0.04) 42%, rgba(210, 210, 210,0.04) 100%),linear-gradient(70deg, rgba(15, 15, 15,0.04) 0%, rgba(15, 15, 15,0.04) 25%,rgba(113, 113, 113,0.04) 25%, rgba(113, 113, 113,0.04) 30%,rgba(210, 210, 210,0.04) 30%, rgba(210, 210, 210,0.04) 100%),linear-gradient(65deg, rgba(15, 15, 15,0.04) 0%, rgba(15, 15, 15,0.04) 13%,rgba(113, 113, 113,0.04) 13%, rgba(113, 113, 113,0.04) 27%,rgba(210, 210, 210,0.04) 27%, rgba(210, 210, 210,0.04) 100%),linear-gradient(90deg, rgb(0,0,0),rgb(0,0,0));
}
.custom-background {
  background-image: linear-gradient(
      158deg,
      rgba(84, 84, 84, 0.03) 0%,
      rgba(84, 84, 84, 0.03) 20%,
      rgba(219, 219, 219, 0.03) 20%,
      rgba(219, 219, 219, 0.03) 40%,
      rgba(54, 54, 54, 0.03) 40%,
      rgba(54, 54, 54, 0.03) 60%,
      rgba(99, 99, 99, 0.03) 60%,
      rgba(99, 99, 99, 0.03) 80%,
      rgba(92, 92, 92, 0.03) 80%,
      rgba(92, 92, 92, 0.03) 100%
    ),
    linear-gradient(
      45deg,
      rgba(221, 221, 221, 0.02) 0%,
      rgba(221, 221, 221, 0.02) 14.286%,
      rgba(8, 8, 8, 0.02) 14.286%,
      rgba(8, 8, 8, 0.02) 28.572%,
      rgba(52, 52, 52, 0.02) 28.572%,
      rgba(52, 52, 52, 0.02) 42.858%,
      rgba(234, 234, 234, 0.02) 42.858%,
      rgba(234, 234, 234, 0.02) 57.144%,
      rgba(81, 81, 81, 0.02) 57.144%,
      rgba(81, 81, 81, 0.02) 71.42999999999999%,
      rgba(239, 239, 239, 0.02) 71.43%,
      rgba(239, 239, 239, 0.02) 85.71600000000001%,
      rgba(187, 187, 187, 0.02) 85.716%,
      rgba(187, 187, 187, 0.02) 100.002%
    ),
    linear-gradient(
      109deg,
      rgba(33, 33, 33, 0.03) 0%,
      rgba(33, 33, 33, 0.03) 12.5%,
      rgba(147, 147, 147, 0.03) 12.5%,
      rgba(147, 147, 147, 0.03) 25%,
      rgba(131, 131, 131, 0.03) 25%,
      rgba(131, 131, 131, 0.03) 37.5%,
      rgba(151, 151, 151, 0.03) 37.5%,
      rgba(151, 151, 151, 0.03) 50%,
      rgba(211, 211, 211, 0.03) 50%,
      rgba(211, 211, 211, 0.03) 62.5%,
      rgba(39, 39, 39, 0.03) 62.5%,
      rgba(39, 39, 39, 0.03) 75%,
      rgba(55, 55, 55, 0.03) 75%,
      rgba(55, 55, 55, 0.03) 87.5%,
      rgba(82, 82, 82, 0.03) 87.5%,
      rgba(82, 82, 82, 0.03) 100%
    ),
    linear-gradient(
      348deg,
      rgba(42, 42, 42, 0.02) 0%,
      rgba(42, 42, 42, 0.02) 20%,
      rgba(8, 8, 8, 0.02) 20%,
      rgba(8, 8, 8, 0.02) 40%,
      rgba(242, 242, 242, 0.02) 40%,
      rgba(242, 242, 242, 0.02) 60%,
      rgba(42, 42, 42, 0.02) 60%,
      rgba(42, 42, 42, 0.02) 80%,
      rgba(80, 80, 80, 0.02) 80%,
      rgba(80, 80, 80, 0.02) 100%
    ),
    linear-gradient(
      120deg,
      rgba(106, 106, 106, 0.03) 0%,
      rgba(106, 106, 106, 0.03) 14.286%,
      rgba(67, 67, 67, 0.03) 14.286%,
      rgba(67, 67, 67, 0.03) 28.572%,
      rgba(134, 134, 134, 0.03) 28.572%,
      rgba(134, 134, 134, 0.03) 42.858%,
      rgba(19, 19, 19, 0.03) 42.858%,
      rgba(19, 19, 19, 0.03) 57.144%,
      rgba(101, 101, 101, 0.03) 57.144%,
      rgba(101, 101, 101, 0.03) 71.42999999999999%,
      rgba(205, 205, 205, 0.03) 71.43%,
      rgba(205, 205, 205, 0.03) 85.71600000000001%,
      rgba(53, 53, 53, 0.03) 85.716%,
      rgba(53, 53, 53, 0.03) 100.002%
    ),
    linear-gradient(
      45deg,
      rgba(214, 214, 214, 0.03) 0%,
      rgba(214, 214, 214, 0.03) 16.667%,
      rgba(255, 255, 255, 0.03) 16.667%,
      rgba(255, 255, 255, 0.03) 33.334%,
      rgba(250, 250, 250, 0.03) 33.334%,
      rgba(250, 250, 250, 0.03) 50.001000000000005%,
      rgba(231, 231, 231, 0.03) 50.001%,
      rgba(231, 231, 231, 0.03) 66.668%,
      rgba(241, 241, 241, 0.03) 66.668%,
      rgba(241, 241, 241, 0.03) 83.33500000000001%,
      rgba(31, 31, 31, 0.03) 83.335%,
      rgba(31, 31, 31, 0.03) 100.002%
    ),
    linear-gradient(
      59deg,
      rgba(224, 224, 224, 0.03) 0%,
      rgba(224, 224, 224, 0.03) 12.5%,
      rgba(97, 97, 97, 0.03) 12.5%,
      rgba(97, 97, 97, 0.03) 25%,
      rgba(143, 143, 143, 0.03) 25%,
      rgba(143, 143, 143, 0.03) 37.5%,
      rgba(110, 110, 110, 0.03) 37.5%,
      rgba(110, 110, 110, 0.03) 50%,
      rgba(34, 34, 34, 0.03) 50%,
      rgba(34, 34, 34, 0.03) 62.5%,
      rgba(155, 155, 155, 0.03) 62.5%,
      rgba(155, 155, 155, 0.03) 75%,
      rgba(249, 249, 249, 0.03) 75%,
      rgba(249, 249, 249, 0.03) 87.5%,
      rgba(179, 179, 179, 0.03) 87.5%,
      rgba(179, 179, 179, 0.03) 100%
    ),
    linear-gradient(
      241deg,
      rgba(58, 58, 58, 0.02) 0%,
      rgba(58, 58, 58, 0.02) 25%,
      rgba(124, 124, 124, 0.02) 25%,
      rgba(124, 124, 124, 0.02) 50%,
      rgba(254, 254, 254, 0.02) 50%,
      rgba(254, 254, 254, 0.02) 75%,
      rgba(52, 52, 52, 0.02) 75%,
      rgba(52, 52, 52, 0.02) 100%
    ),
    linear-gradient(90deg, #ffffff, #ffffff);
}
.transparent {
  background: none !important;
  opacity: 1;
}
</style>


