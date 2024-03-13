<template>
  <section id="section-about" class="section-about">
    <div class="grid">
	<div class="grid__item grid__item--head">
		<h1>The Cascade Cafe...</h1>

		<address>
			<span>
				<svg viewBox="0 0 384 512" width="15" title="map-marker-alt">
					<path d="M172.268 501.67C26.97 291.031 0 269.413 0 192 0 85.961 85.961 0 192 0s192 85.961 192 192c0 77.413-26.97 99.031-172.268 309.67-9.535 13.774-29.93 13.773-39.464 0zM192 272c44.183 0 80-35.817 80-80s-35.817-80-80-80-80 35.817-80 80 35.817 80 80 80z" />
				</svg>
				<p>123 Main Street • Smalltown, PA</p>
			</span>
			<span>
				<svg viewBox="0 0 512 512" width="15" title="phone-alt">
					<path d="M497.39 361.8l-112-48a24 24 0 0 0-28 6.9l-49.6 60.6A370.66 370.66 0 0 1 130.6 204.11l60.6-49.6a23.94 23.94 0 0 0 6.9-28l-48-112A24.16 24.16 0 0 0 122.6.61l-104 24A24 24 0 0 0 0 48c0 256.5 207.9 464 464 464a24 24 0 0 0 23.4-18.6l24-104a24.29 24.29 0 0 0-14.01-27.6z" />
				</svg>
				<a href="4125550100">412-555-0100</a>
			</span>
		</address>
	</div>
	<div class="grid__item grid__item--info">
		<table class="hours">
			<thead>
				<tr>
					<th colspan="2">Hours</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>Mon. - Thurs.</td>
					<td>6 a.m. - 9 p.m.</td>
				</tr>
				<tr>
					<td>Fri. - Sat.</td>
					<td>6 a.m. - 11 p.m.</td>
				</tr>
				<tr>
					<td>Sunday</td>
					<td>8 a.m. - 2 p.m.</td>
				</tr>
			</tbody>
		</table>
		<div class="img-wrap">
			<img src="https://assets.codepen.io/t-1/nathan-dumlao-6VhPY27jdps-unsplash.jpg" alt="three hands toasting with coffee drinks">
		</div>
	</div>
	<div class="grid__item grid__item--coffee">
		<h2>Coffee</h2>
		<p class="prices"><span>Small: $2</span> <span>Large: $4</span></p>
		<dl>
			<dt>House Blend</dt>
			<dd class="description">
				<p>Smoky, strong, and assertive, just like us.</p>
			</dd>
			<dt>Organic French Roast</dt>
			<dd class="description">
				<p>Smooth and mellow with hints of molasses.</p>
			</dd>
			<dt>Organic Decaf</dt>
			<dd class="description">
				<p>Full bodied and rich, we promise you won't miss the caffiene.</p>
			</dd>
		</dl>
	</div>
	<div class="grid__item grid__item--espresso">
		<h2>Espresso Drinks</h2>
		<p class="prices"><span>Small: $3</span> <span>Large: $5</span></p>
		<dl>
			<dt>Machiatto </dt>
			<dd class="description">
				<p>Espressso and steamed milk, served in a demitasse cup. <span class="note">(Size Small Only)</span></p>
			</dd>
			<dt>Latte</dt>
			<dd class="description">
				<p>Espresso with steamed milk, and sometimes a little art on top. </p>
			</dd>
			<dt>Mocha</dt>
			<dd class="description">
				<p>Espresso with steamed chocolate milk and whipped cream. Also available with white chocolate milk.</p>
			</dd>
			<dt>Americano</dt>
			<dd class="description">
				<p>1 shot espresso, two shots hot water.</p>
			</dd>
		</dl>
	</div>
	<div class="grid__item grid__item--tea">
		<h2>Tea</h2>
		<p>Served to brave people in our notorious antique tea cups.</p>
		<p class="prices"><span>Per Cup: $2</span> <span class="note">$200 if you break the cup</span></p>
		<dl>
			<dt>Earl Grey </dt>
			<dd class="description">
				<p>Black tea fragranced with bergamot.</p>
			</dd>
			<dt>Ginger Hibiscus</dt>
			<dd class="description">
				<p>Floral, tart, and spicy. Caffeine free.</p>
			</dd>
			<dt>Cascade Green</dt>
			<dd class="description">
				<p>A blend of green teas hand selected by our master teamaker.</p>
			</dd>
			<dt>Chamomile</dt>
			<dd class="description">
				<p>Soothing and slightly sweet. Try it with honey! Caffeine free.</p>
			</dd>
		</dl>
	</div>
	<div class="grid__item grid__item--bakery">
		<h2>From the Bakery</h2>
		<p class="prices"><span>Cookies: $2</span> <span>Muffins &amp; Pastries: $3</span></p>
		<dl>
			<dt>Mallory's Famous Snickerdoodles </dt>
			<dd class="description">
				<p>Creamy cinnamony goodness made from scratch with our founder Mallory's prizewinning recipe.</p>
			</dd>
			<dt>Oatmeal Cookie</dt>
			<dd class="description">
				<p>Packed with rolled oats, raisins, and cranberries, these monster cookies are (almost) good for ya!</p>
			</dd>
			<dt>Mixed Berry Muffins</dt>
			<dd class="description">
				<p>Filled with the best berries of the season and topped with a crumb crust. </p>
			</dd>
			<dt>Croissant</dt>
			<dd class="description">
				<p>Our oversized croissants are buttery, flaky, and usually all sold out by 7 a.m.</p>
			</dd>
		</dl>
	</div>
</div>

  </section>
</template>

<script>
export default {
  name: "SectionAbout",
  data() {
    return {
    };
  },
  computed: {
  },
  mounted() {
  },
  methods: {
  },
};
</script>
<style>
@import url('../src/assets/styles.css');
</style>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Big+Shoulders+Display:wght@700&family=Dosis:wght@400;500&family=Dancing+Script&display=swap&display=swap");

body {
	font-family: "Dosis", sans-serif;
	background: #999;
	color: #242424;
	background-image: url(https://images.unsplash.com/photo-1576092762791-dd9e2220abd1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1050&q=80);
	background-size: cover;
	padding: 40px;
}

img {
	max-width: 100%;
}

* {
	box-sizing: border-box;
}

.grid {
	max-width: 800px;
	padding: 10px;
	margin: 0 auto;
	box-shadow: 0px 2px 20px rgba(black, 0.2);
	border-radius: 3px;
	background: white;
	background-image: url(https://images.unsplash.com/photo-1615800098799-0ccb261b1f92?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=654&q=80);
	background-size: cover;
	display: grid;
	width: 100%;
	grid-template-columns: 220px auto auto;
	grid-template-rows: 80px auto auto;
	transform: rotate(-1.5deg);
}

.grid__item {
	padding: 10px 10px;
}

.grid__item--head {
	grid-column-start: 1;
	grid-column-end: span 3;
	grid-row-start: 1;
	padding: 10px;
	display: flex;
	justify-content: space-between;
	border-bottom: 1px dashed #555;
}

.grid__item--head h1 {
	margin: 0;
}

.grid__item--info {
	grid-row-start: 2;
	grid-row-end: span 2;
	border-right: 1px dashed #555;
}

.img-wrap {
	margin: 5px;
	width: calc(100% - 10px);
	border: 5px solid #999900;
	background: rgba(#999900, 0.5);
	border-radius: 100%;
	box-shadow: 0px 0px 4px rgba(black, 0.1);
	overflow: hidden;
	padding-top: calc(100% - 10px);
	position: relative;
}

.img-wrap img {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	object-fit: cover;
	object-position: center center;
}

h1,
h2,
h3,
h4,
h5,
h6 {
	font-family: "Dancing Script", sans-serif;
	font-weight: 400;
	margin: 0 0 10px;
}

h1 {
	font-size: 50px;
	line-height: 1;
}

h2 {
	font-size: 30px;
}

address {
	font-style: normal;
	display: flex;
	flex-direction: column;
	align-items: flex-end;
	font-size: 14px;
}

address svg {
	fill: #999900;
}

address p {
	margin: 0;
}

address span {
	display: flex;
	align-items: center;
}

address span + span {
	margin-top: 5px;
}

address svg {
	margin-right: 10px;
}

address a {
	color: #242424;
	text-decoration: none;
}

.hours {
	width: 100%;
	text-align: left;
	margin: 0 0 20px;
}

.hours thead {
	font-family: "Big Shoulders Display", sans-serif;
	font-size: 18px;
}

.hours td:nth-of-type(2) {
	text-align: right;
	text-transform: uppercase;
	font-weight: 500;
}

dt {
	font-family: "Big Shoulders Display", sans-serif;
	font-weight: 700;
	font-size: 18px;
	text-transform: uppercase;
	margin: 0 0 4px;
}

dd {
	margin: 0 0 20px;
	padding: 0;
}

dd p {
	margin: 0;
}

.prices .note {
	display: block;
	background: #999900;
	color: white;
	padding: 5px;
	border-radius: 2px;
	margin-top: 5px;
}

</style>