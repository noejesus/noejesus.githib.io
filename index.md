<!DOCTYPE html>

<html lang="en">
  <style>
    .tooltip {
      position: relative;
      display: inline-block;
      border-bottom: 1px dotted black;
    }
    
    .tooltip .tooltiptext {
      visibility: hidden;
      width: 120px;
      background-color: black;
      color: #fff;
      text-align: center;
      border-radius: 6px;
      padding: 5px 0;
      position: absolute;
      z-index: 1;
      bottom: 150%;
      left: 50%;
      margin-left: -60px;
    }
    
    .tooltip .tooltiptext::after {
      content: "";
      position: absolute;
      top: 100%;
      left: 50%;
      margin-left: -5px;
      border-width: 5px;
      border-style: solid;
      border-color: black transparent transparent transparent;
    }
    
    .tooltip:hover .tooltiptext {
      visibility: visible;
    }
    </style>
  <head>
    <meta charset="utf-8" />
    <title>Homepage - Styles Conference</title>
    <link rel="icon" type="image/gif/png" href="ProfilePicture.png">
  </head>

  <body style="text-align: center">
    <header>
      <nav>
        <a href="index.html">Home</a>
        <a href="speakers.html">Speakers</a>
        <a href="schedule.html">Schedule</a>
        <a href="venue.html">Venue</a>
        <a href="register.html">Register</a>
      </nav>
      <h1>
        <a href="index.html"> Styles Conference </a>
      </h1>
      <h3>August 24 &ndash; 26th &mdash; Chicago, IL</h3>
    </header>

    <main>
      <section>
        <h2>Dedicated to the Craft of Building Websites</h2>
        <p>
          Every year the brightest web designers and front-end developers
          descend on Chicago to discuss the latest technologies. Join us this
          August!
        </p>
        <a href="register.html">Register Now</a>
      </section>

      <section>
        <h2>What to Expect from the Conference</h2>
        <p>
          This will be an <strong>emersive experience</strong> to hone in on
          your web dev skills and pick up industry insights and trends from
          leading pracitioners. So bring your laptops and be ready to take your
          web development to the next level.
        </p>

        <div><a href="schedule.html"> Click Here </a> for a full itinerary</div>

        <p> Soon you'll be <div class="tooltip"> writing HTML
          <span class="tooltiptext">see itinerary</span>
          </div>
          with the best of them!

        </p>

        
      </section>
    </main>

    <footer>
      <nav>
        <a href="index.html">Home</a>
        <a href="speakers.html">Speakers</a>
        <a href="schedule.html">Schedule</a>
        <a href="venue.html">Venue</a>
        <a href="register.html">Register</a>
      </nav>
      <small>&copy; Styles Conference 2020</small>
    </footer>
  </body>
</html>
