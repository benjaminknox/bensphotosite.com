<div class="wrapper">
  Ben's Photo Site
  <image class="me" src="/me.png" />
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
    gap: 27.5px;
    min-width: 100%;
    min-height: 100%;
  }
</style>
