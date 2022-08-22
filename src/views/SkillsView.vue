<template>
  <div class="skill">
    <h3>Skills</h3>
    <hr>
    <div class="skill-list">
      <div class="html">
        <h6>HTML</h6>
        <div class="progress">
          <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="60"
            aria-valuemin="0" aria-valuemax="100" style="width: 60%">60%</div>
        </div>
      </div>

      <div class="css">
        <h6>CSS</h6>
        <div class="progress">
          <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="60"
            aria-valuemin="0" aria-valuemax="100" style="width: 60%">60%</div>
        </div>
      </div>

      <div class="bootstrap">
        <h6>BootStrap</h6>
        <div class="progress">
          <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="50"
            aria-valuemin="0" aria-valuemax="100" style="width: 50%">50%</div>
        </div>
      </div>

      <div class="javascript">
        <h6>JavaScript</h6>
        <div class="progress">
          <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="25"
            aria-valuemin="0" aria-valuemax="100" style="width: 25%">25%</div>
        </div>
      </div>

      <div class="sql">
        <h6>SQL</h6>
        <div class="progress">
          <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="50"
            aria-valuemin="0" aria-valuemax="100" style="width: 50%">50%</div>
        </div>
      </div>

      <div class="php">
        <h6>PHP</h6>
        <div class="progress">
          <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="25"
            aria-valuemin="0" aria-valuemax="100" style="width: 25%">25%</div>
        </div>
      </div>

      <div class="laravel">
        <h6>Laravel</h6>
        <div class="progress">
          <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="25"
            aria-valuemin="0" aria-valuemax="100" style="width: 25%">25%</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  @media (min-width: 1024px) {
    .skill {
      min-height: 100vh;
      margin-top: 2rem;
    }

    .skill h3 {
      margin-left: 100px;
    }

    .skill ul {
      margin-top: 1rem;
    }

    .skill hr {
      margin: 20px 100px;
    }

    .skill-list h6 {
      margin-left: 100px;
    }

    .html {
      margin-bottom: 40px;
    }

    .css {
      margin-bottom: 40px;
    }

    .bootstrap {
      margin-bottom: 40px;
    }

    .javascript {
      margin-bottom: 40px;
    }

    .sql {
      margin-bottom: 40px;
    }

    .php {
      margin-bottom: 40px;
    }

    .laravel {
      margin-bottom: 40px;
    }

    .progress {
      margin: 0 100px;
    }
  }
</style>