# first-html
it is my first html code
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="bootstrap.css">
</head>

<body>
  <button class="btn btn-primary" type="button" disabled>
    <span class="spinner-border spinner-border-sm" role="status" aria-hidden="true"></span>
    <span class="visually-hidden">Loading...</span>
  </button>
  <button class="btn btn-primary" type="button" disabled>
    <span class="spinner-border spinner-border-sm" role="status" aria-hidden="true"></span>
    Loading...
  </button>
  <div class="accordion" id="accordionPanelsStayOpenExample">
    <div class="accordion-item">
      <h2 class="accordion-header" id="panelsStayOpen-headingOne">
        <button class="accordion-button" type="button" data-bs-toggle="collapse"
          data-bs-target="#panelsStayOpen-collapseOne" aria-expanded="true" aria-controls="panelsStayOpen-collapseOne">
          Hello everybody
        </button>
      </h2>
      <div id="panelsStayOpen-collapseOne" class="accordion-collapse collapse show"
        aria-labelledby="panelsStayOpen-headingOne">
        <div class="accordion-body">
          Siz bu yerda o'zingizga kerakli malumoti topishingiz mumkin <strong>"USB kabellar narxi qancha"</strong>
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header" id="panelsStayOpen-headingTwo">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
          data-bs-target="#panelsStayOpen-collapseTwo" aria-expanded="false" aria-controls="panelsStayOpen-collapseTwo">
          No1
        </button>
      </h2>
      <div id="panelsStayOpen-collapseTwo" class="accordion-collapse collapse"
        aria-labelledby="panelsStayOpen-headingTwo">
        <div class="accordion-body">
          <strong>Lorem ipsum dolor sit amet.</strong> Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi
          accusamus iste praesentium. Laboriosam eligendi, magnam odit vero explicabo alias repudiandae. Hic eveniet
          voluptatem corrupti ab rerum cum reprehenderit explicabo, labore velit sequi quaerat perspiciatis placeat amet
          dignissimos consequuntur possimus nisi obcaecati, cupiditate veritatis? Temporibus totam consequatur maxime,
          quis alias earum, recusandae explicabo repudiandae minus eum harum fugit nulla accusantium quasi soluta ex
          nesciunt minima ipsa dicta veniam nobis fuga deserunt error repellendus! Labore nobis debitis voluptatibus
          earum. Ut omnis ipsam iure illo corporis eaque nihil alias veritatis minus?
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header" id="panelsStayOpen-headingThree">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
          data-bs-target="#panelsStayOpen-collapseThree" aria-expanded="false"
          aria-controls="panelsStayOpen-collapseThree">
          Accordion Item #3
        </button>
      </h2>
      <div id="panelsStayOpen-collapseThree" class="accordion-collapse collapse"
        aria-labelledby="panelsStayOpen-headingThree">
        <div class="accordion-body">
          <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin
          adds the appropriate classes that we use to style each element. These classes control the overall appearance,
          as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or
          overriding our default variables. It's also worth noting that just about any HTML can go within the
          <code>.accordion-body</code>, though the transition does limit overflow.
        </div>
      </div>
    </div>
  </div>
</body>

</html>
