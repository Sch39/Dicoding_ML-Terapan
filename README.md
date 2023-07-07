# Project Dicoding - Sukron Chafidhi

## Reviewer - Dicoding
<a href="https://www.dicoding.com">
            <img src="https://dicoding-web-img.sgp1.cdn.digitaloceanspaces.com/original/commons/new-ui-logo.png" alt="Dicoding Indonesia" width="50" >
        </a> 
<br><br>

## Project Predictive Analytics
<img src='https://res.cloudinary.com/da0hsihog/image/upload/v1688719861/Portofolio/7140739_3515462_wqxkir.jpg' height='200px'>

<a href="https://www.freepik.com/free-vector/site-stats-concept-illustration_7140739.htm#query=predictive%20analytics&position=17&from_view=keyword&track=ais">Image by storyset</a> on Freepik <br>
<!-- [Choose!](https://github.com/Sch39/Dicoding_ML-Terapan/blob/master/Predictive%20Analytics/README.md) -->
<a class='link' href='https://github.com/Sch39/Dicoding_ML-Terapan/blob/master/Predictive%20Analytics/README.md'>Choose!</a>
<br><br>

## Project System Recommender
<img src='https://res.cloudinary.com/da0hsihog/image/upload/v1688719862/Portofolio/20827916_xkiifg.jpg' width="200px">

<a href="https://www.freepik.com/free-vector/team-analysts-working-brand-reputation-social-media_20827916.htm#query=recommender%20system&position=3&from_view=search&track=ais">Image by pch.vector</a> on Freepik <br>
<!-- [Choose!](https://github.com/Sch39/Dicoding_ML-Terapan/blob/master/Recommender%20System/README.md) -->
<a class='link' href='https://github.com/Sch39/Dicoding_ML-Terapan/blob/master/Recommender%20System/README.md'>Choose!</a>

<br>

## Author - Sukron Chafidhi
<a href="https://profile.sch39.dev">
            <img src="https://profile.sch39.dev/icons/icon.png" alt="Sch39" width="50" >
        </a> 




<style>
@import "https://unpkg.com/open-props";

* {
  box-sizing: border-box;
}

body {
  background: var(--gradient-1);
  display: grid;
  place-items: center;
  height: 80vh;
}

.link {
  font-family: var(--font-sans);
  font-weight: var(--font-weight-6);
  font-size: var(--font-size-3);
  color: var(--gray-8);
  background: var(--gray-0);
  border: 0;
  padding: var(--size-1) var(--size-2);
  transform: translateY(calc(var(--y, 0) * 1%)) scale(var(--scale));
  transition: transform 0.1s;
  position: relative;
  margin-top:50px;
  margin-bottom:50px;
}

.link:hover {
  --y: -10;
  --scale: 1.1;
  --border-scale: 1;
}

.link:active {
  --y: 5%;
  --scale: 0.9;
  --border-scale: 0.9, 0.8;
}

.link:before {
  content: "";
  position: absolute;
  inset: calc(var(--size-3) * -1);
  border: var(--size-2) solid var(--gray-0);
  transform: scale(var(--border-scale, 0));
  transition: transform 0.125s;
  
  --angle-one: 105deg;
  --angle-two: 290deg;
  --spread-one: 30deg;
  --spread-two: 40deg;
  --start-one: calc(var(--angle-one) - (var(--spread-one) * 0.5));
  --start-two: calc(var(--angle-two) - (var(--spread-two) * 0.5));
  --end-one: calc(var(--angle-one) + (var(--spread-one) * 0.5));
  --end-two: calc(var(--angle-two) + (var(--spread-two) * 0.5));
  
  mask: conic-gradient(
    transparent 0 var(--start-one),
    white var(--start-one) var(--end-one),
    transparent var(--end-one) var(--start-two),
    white var(--start-two) var(--end-two),
    transparent var(--end-two)
  );
  
  z-index: -1;
}
</style>