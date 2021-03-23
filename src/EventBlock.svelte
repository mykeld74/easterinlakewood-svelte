<script>
  export let eventImg =
    "https://res.cloudinary.com/mykeld74/image/upload/c_scale,w_450,dpr_auto,f_auto,q_auto/easterinlakewood/crown_logo";
  export let eventImgDesc = "Easter Sunday Logo";
  export let backgroundColor = `radial-gradient(
      circle,
      rgba(20, 57, 62, 1) 0%,
      rgba(8, 5, 40, 1) 100%
    )`;
</script>

<div class="eventContainer" style="background: {backgroundColor}">
  <div class="eventLogo">
    <img src={eventImg} alt={eventImgDesc} />
  </div>
  <h1 class="invite">Your Invited</h1>
  <div class="yourInvited">
    <slot name="title" />
    <slot name="desc" />
    <slot name="dateTime" />
  </div>
</div>

<style>
  .eventContainer {
    box-sizing: border-box;
    min-height: 100vh;
    width: 100vw;
    color: #fff;
    padding: 15px;
  }

  .eventLogo {
    width: clamp(300px, 60vw, 450px);
    margin: 3vh auto 5vh;
  }
  .yourInvited {
    width: 94%;
    max-width: 1280px;
    margin: auto;
    border: 2px solid #fff;
    padding: 1.5vh 2vw;
    position: relative;
    margin-bottom: 30px;
  }
  .invite {
    width: 100%;
    text-align: center;
  }
</style>
