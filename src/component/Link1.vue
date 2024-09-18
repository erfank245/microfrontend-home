  <template>
    <div class="paddnav"></div>
    <div class="center-items">
      <img 
        class="logo"
        src="https://graphicallyapp.ir/MainLogo.png"
        alt="graphically app"
      />
      <div class="text">
        تست میکرو فرانت اند گرافیکالی
      </div>
    </div>
  </template>
  <script>
  export default {
   
  };
  </script>
  <style scoped>
    .paddnav {
      width: 100%;
      height: 80px;
    }
    .center-items {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      align-items: center;
      margin: auto;
      width: 50%;
    }
    .logo {
      width: 100%;
      max-width: 400px;
      margin: auto;
    }
    .text {
      font-weight: 600;
    }
  </style>