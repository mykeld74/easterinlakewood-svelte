<script>
  export let eventImg = "assets/wwcc-logo.png";
  export let eventImgDesc = "Westwoods Community Church Logo";
  export let backgroundColor = `radial-gradient(
      circle,
      rgba(20, 57, 62, 1) 0%,
      rgba(8, 5, 40, 1) 100%
    )`;
</script>

<div class="eventContainer" style="background: {backgroundColor}">
  <div class="eventLogo">
    <a
      href="https://westwoodscc.org"
      target="_blank"
      rel="noopener noreferrer"
      class="wwLink"><img src={eventImg} alt={eventImgDesc} /></a
    >
  </div>

  <div class="yourInvited">
    <slot name="title" />
    <slot name="desc" />
    <slot name="links" />
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
    padding: 1.5vh 2vw;
    position: relative;
  }
</style>
