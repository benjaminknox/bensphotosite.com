<div class="wrapper">
  Ben's Photo Site
  <image class="me" src="/me.png" />
  <div class="photo">
    Good Morning Cincinnati
    <image class="snapshot" src="/good-morning-cincinnati.jpg" />
  </div>
  <div class="photo">
    Good Night Kentucky
    <image class="snapshot" src="/good-night-kentucky.jpg" />
  </div>
</div>

<style lang="scss">
  :global(html, body) {
    width: 100%;
    height: 100%;
    margin: 0;
    padding: 0;
  }

  :global(body) {
    background: url('/background-pattern.jpg');
    font-family: "Just Another Hand", sans-serif;
  }

  .wrapper {
    padding-top: 40px;
    padding-bottom: 40px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: #050302;
    font-size: 96px;
    font-style: normal;
    font-weight: 300;
    line-height: normal;
    letter-spacing: 4.8px;
    gap: 40px;
    min-width: 100%;
    min-height: 100%;

    .photo {
      align-items: center;
      font-size: 50px;
      display: flex;
      flex-direction: column;

      .snapshot {
        width: 600px;
        border: 10px solid #000;
      }
    }
  }
</style>
