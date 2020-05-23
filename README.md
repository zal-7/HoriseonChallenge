# Code Refactor Starter Code
#Horiseon

1. Add id="search-engine-optimization" to <div alt="coffee and notebook" class="search-engine-optimization">

2. Add  <section class="policy">
        <h5 class="page-title">
          Privacy Policy
        </h5>
    </section> to the end

3. Add alt to each image, as according...
<div id="search-engine-optimization" alt="coffee and notebook" class="search-engine-optimization">

<div id="online-reputation-management" alt="reputation chart laptop" class="online-reputation-management">

<div id="social-media-marketing" alt="like tweet media" class="social-media-marketing">

<img src="./assets/images/lead-generation.png" alt="inbound funnel image"/>

<img src="./assets/images/brand-awareness.png" alt="lightbulb head"/>

<img src="./assets/images/cost-management.png" alt="advertising costs" /> </img>

4. Align <h1> to <h4> accordingly

5. Organize section in image order:
.search-engine-optimization {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}
.search-engine-optimization img {
    max-height: 200px;
}

.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.online-reputation-management img {
    max-height: 200px;
}

.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.social-media-marketing img {
    max-height: 200px;
}

.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

6. Assign Hero Style Start & End:
/* Hero Style Start */
.hero {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("../images/digital-marketing-meeting.jpg");
    background-size: cover;
    background-position: center;
}
/* Hero Style End */

7. Consolidate tile to Horiseon