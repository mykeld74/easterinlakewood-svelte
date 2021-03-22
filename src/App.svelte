<script>
  import DirectionBlock from "./DirectionBlock.svelte";

  import EventBlock from "./EventBlock.svelte";
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.gstatic.com" />
  <link
    href="https://fonts.googleapis.com/css2?family=Mukta:wght@200;300;400;500;600;700;800&display=swap"
    rel="stylesheet"
  />
  <title>Easter In Lakewood | Westwoods Community Church</title>
</svelte:head>

<main>
  <div class="logo">
    <a
      href="https://westwoodscc.org"
      target="_blank"
      rel="noopener noreferrer"
      class="wwLink"
    >
      <img
        src="assets/wwcc-logo.png"
        alt="Westwoods Community Church Logo"
      /></a
    >
  </div>
  <EventBlock>
    <h2 slot="title">Because Jesus Lives</h2>
    <div slot="desc">
      <p>
        Jesus lives because He is not an idea, He is a person. Jesus lives
        because the grave could not and did not hold Him. Jesus lives because
        Love wins!
      </p>
      <p>
        Join us this Easter and let’s discover the hope, joy and purpose in
        living for Him.
      </p>
    </div>
    <div slot="dateTime" class="eventDetails">
      <div class="times">
        <h3>
          <a
            href="https://westwoodscc.org"
            target="_blank"
            rel="noopener noreferrer"
            class="wwLink"
          >
            Westwoods Community Church</a
          >
        </h3>
        <h4>Sunday 4/4</h4>
        <h4>6:30 Sunrise Service & 9am Easter Service</h4>
        <p>
          7700 W Woodard Drive<br />
          Lakewood, CO
        </p>
      </div>
      <div class="topics">
        <h3>Series dates and topics:</h3>
        <h4>4.11 Because Jesus Lives, I LIVE</h4>
        <h4>4.18 Because Jesus Lives, I Have Hope</h4>
        <h4>4.25 Because Jesus Lives, I Have Joy</h4>
        <h4>5.2 Because Jesus Lives, I Have Purpose</h4>
      </div>
    </div>
  </EventBlock>
  <EventBlock
    eventImg="assets/good-friday.png"
    backgroundColor={`radial-gradient(circle, rgba(87,87,87,1) 0%, rgba(35,35,35,1) 100%)`}
  >
    <h2 slot="title">A journey with Jesus and those closest to Him</h2>
    <div slot="desc">
      <p>
        A deep look into the elements, ideas and objects from Jesus' journey to
        the cross. These elements help us understand that we are not troubled
        guests in this world, that we are not forgotten, and that Jesus
        expressed the good news of this season best when he said, "In this world
        you will experience trials, but take heart, I have overcome the world."
        Join us for a time rooted in prayer for what the season holds.
      </p>
    </div>
    <div slot="dateTime" class="dtonly">
      <div class="times">
        <h3>
          <a
            href="https://westwoodscc.org"
            target="_blank"
            rel="noopener noreferrer"
            class="wwLink"
          >
            Westwoods Community Church</a
          >
        </h3>

        <h4>Friday 4/2</h4>
        <h4>3pm - 8pm</h4>
        <p>
          7700 W Woodard Drive<br />
          Lakewood, CO
        </p>
      </div>
    </div>
  </EventBlock>
  <EventBlock
    eventImg="assets/egg-hunt.png"
    backgroundColor={`radial-gradient(circle, rgba(158,217,115,1) 0%, rgba(108,177,127,1) 100%)`}
  >
    <h2 slot="title">
      Hop on over for fun and we will find some eggs - every last one!
    </h2>
    <div slot="desc">
      <p>
        Join your neighbors Saturday, 4/20 from 10am to noon for our annual
        COMMUNITY EGG HUNT!
      </p>
      <p>PRIZES, GAMES, FOOD, and FUN for the whole family!</p>
      <p>Everyone is welcome!</p>
    </div>
    <div slot="dateTime" class="dtonly">
      <div class="times">
        <h3>
          <a
            href="https://westwoodscc.org"
            target="_blank"
            rel="noopener noreferrer"
            class="wwLink"
          >
            Westwoods Community Church</a
          >
        </h3>

        <h4>Saturday 4/3</h4>
        <h4>10am - Noon</h4>
        <p>
          7700 W Woodard Drive<br />
          Lakewood, CO
        </p>
      </div>
    </div>
  </EventBlock>
  <DirectionBlock
    backgroundColor={`radial-gradient(circle, rgba(118,202,254,1) 0%, rgba(1,30,64,1) 100%)`}
    eventImg="assets/wwcc-logo.png"
  >
    <div slot="desc" class="wwDetails">
      <div>
        <h3>
          <a
            href="https://westwoodscc.org"
            target="_blank"
            rel="noopener noreferrer"
            class="wwLink"
          >
            Westwoods Community Church</a
          >
        </h3>
        <h4>Sunday 4/4</h4>
        <h4>6:30am Sunrise Service & 9am Easter Service</h4>
        <p>
          7700 W Woodard Drive<br />
          Lakewood, CO
        </p>
      </div>
      <div class="mapContainer">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3070.8329214253686!2d-105.08480848435234!3d39.675972808278864!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x876b81ad73d8223d%3A0xef2d6fab8083844!2sWestwoods%20Community%20Church!5e0!3m2!1sen!2sus!4v1569100714699!5m2!1sen!2sus"
          frameBorder="0"
          allowFullScreen=""
          title="Westwoods Map"
          style="width: 100%; height: 25vh;"
        />
      </div>
    </div>
    <div class="pdfLinks" slot="links">
      <a
        href="assets/easter-flyer.pdf"
        target="_blank"
        rel="noopener noreferrer"
        class="pdfLink"
        ><div class="linkImage">
          <img src="assets/easter-sunday.png" alt="Easter Sunday Logo" />
        </div>
        Easter Flyer</a
      >
      <a
        href="assets/good-friday-flyer.pdf"
        target="_blank"
        rel="noopener noreferrer"
        class="pdfLink"
        ><div class="linkImage">
          <img src="assets/good-friday.png" alt="Good Friday Logo" />
        </div>
        Good Friday Flyer</a
      >
      <a
        href="assets/egg-hunt-flyer.pdf"
        target="_blank"
        rel="noopener noreferrer"
        class="pdfLink"
        ><div class="linkImage">
          <img src="assets/egg-hunt.png" alt="Egg Hunt Logo" />
        </div>
        Egg Hunt Flyer</a
      >
    </div>
  </DirectionBlock>
</main>

<style>
  :global(img) {
    max-width: 100%;
    max-height: 100%;
  }
  :global(h1) {
    font-size: clamp(28px, 5vw, 48px);
  }
  :global(h2) {
    font-size: clamp(26px, 4vw, 36px);
    margin: 0;
  }
  :global(h3) {
    font-size: clamp(24px, 3vw, 30px);
    line-height: 1.2;
    margin: 10px 0;
  }
  :global(h4) {
    font-size: clamp(20px, 2.5vw, 26px);
    line-height: 1.2;
    margin: 0;
    font-weight: 500;
  }
  :global(p) {
    font-size: clamp(20px, 2.5vw, 26px);
    line-height: 1.2;
    margin: 0.5em 0;
  }
  main {
    padding: 0;
    margin: 0;
  }
  .logo {
    width: clamp(100px, 20vw, 250px);
    position: absolute;
    top: 2vh;
    left: 2vw;
  }
  .eventDetails,
  .wwDetails,
  .pdfLinks {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    justify-content: space-around;
    justify-items: center;
    max-width: 100%;
  }
  .pdfLinks {
    margin-top: 3vh;
    padding-top: 3vh;
    border-top: 1px solid #fff;
  }
  .dtonly {
    margin-left: 5vw;
  }
  .mapContainer {
    width: 100%;
  }
  .wwLink,
  .pdfLink {
    color: #fff;
    transition: all 0.3s ease-in-out;
  }
  .pdfLink {
    font-size: clamp(24px, 3vw, 30px);
  }
  .linkImage {
    height: 50px;
    display: grid;
    align-items: center;
    justify-content: center;
    margin-top: 20px;
  }
</style>
