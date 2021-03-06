# Cannabis-Law-Society
Cannabis Law Society

<!DOCTYPE html>

<html>
<head>

<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>

<title>A Flexible Grid</title>

<meta name="DC.creator" content="Ethan Marcotte - http://unstoppablerobotninja.com/" />
<meta name="DC.language" content="en" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<style type="text/css" media="screen, projection">
.section:after,
ul.nav:after {
	content: ".";
	display: block;
	height: 0;
	clear: both;
	visibility: hidden;
}

/* http://meyerweb.com/eric/tools/css/reset/ */
/* v1.0 | 20080212 */
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,font,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td { margin:0;padding:0;border:0;outline:0;font-size:100%;vertical-align:baseline;background:transparent; }
body { line-height:1; }
ol,ul { list-style:none; }
blockquote,q { quotes:none; }
blockquote:before,blockquote:after,q:before,q:after { content:'';content:none; }
ins { text-decoration:none; }
del { text-decoration:line-through; }
table { border-collapse:collapse;border-spacing:0; }

body {
	background: #E4E4E4 url("site/bg.png");
	color: #292929;
	color: rgba(0, 0, 0, 0.82);
	font: normal 100% Cambria, Georgia, serif;
	-moz-text-shadow: 0 1px 0 rgba(255, 255, 255, 0.8);
	-webkit-text-shadow: 0 1px 0 rgba(255, 255, 255, 0.8);
	text-shadow: 0 1px 0 rgba(255, 255, 255, 0.8);
	-webkit-text-size-adjust: none;
}
a {
	color: #890101;
	text-decoration: none;
	-moz-transition: 0.2s color linear;
	-webkit-transition: 0.2s color linear;
	transition: 0.2s color linear;
}
a:hover {
	color: #DF3030;
}
#page {
	background: url("site/rag.png") repeat-x;
	padding: 2em 0;
}
.inner {
	margin: 0 auto;
	width: 93.75%;		/* 960px / 1024px */
}
img {
	max-width: 100%;
}
.amp {
	font-family: Baskerville, Garamond, Palatino, "Palatino Linotype", "Hoefler Text", "Times New Roman", serif;
	font-style: italic;
	font-weight: normal;
}
.mast {
	float: left;
	width: 31.875%;	/* 306px / 960px */
}
h1 {
	background: url("site/logo-bg.png") no-repeat 50% 0;
}
h1 a {
	padding-top: 117px;
	height: 162px;
	display: block;
	text-align: center;
}
.intro,
.main,
.footer {
	float: right;
	width: 65.9375%;	/* 633px / 960px */
}
.intro {
	margin-top: 117px;
}
.intro div {
	line-height: 1.4;
}
ul.nav {
	border-top: 1px solid #888583;
	margin: 2em auto 0;
	width: 64.379%;
}
ul.nav a {
	background: url("site/ornament.png") no-repeat 0 100%;
	font: bold 14px/1.2 "Book Antiqua", "Palatino Linotype", Georgia, serif;
	display: block;
	text-align: center;
	letter-spacing: 0.1em;
	padding: 1em 0.5em 3em;
	margin-bottom: -1em;
	text-transform: uppercase;
}
ul.nav a:hover {
	background-position: 50% 100%;
}
li.first a {
	border-top: 1px solid #FFF9EF;
	padding-top: 1.25em;
}
ul.nav i {
	font: normal 10px Baskerville, Garamond, Palatino, "Palatino Linotype", "Hoefler Text", "Times New Roman", serif;
	display: block;
	letter-spacing: 0.05em;
}
.intro h2 {
	font: normal 2em "Hoefler Text", "Baskerville old face", Garamond, "Times New Roman", serif;
	text-align: center;
	margin-bottom: 0.25em;
}
.main h2 {
	background: url("site/ornament.png") no-repeat 0 50%;
	font-size: 1.4em;
	text-transform: lowercase;
	text-align: center;
	margin: 0.75em 0 1em;
}
.main h2 b {
	background: url("site/bg.png");
	font-weight: normal;
	padding: 0 1em;
}
.figure {
	float: left;
	font-size: 10px;
	line-height: 1.1;
	margin: 0 3.317535545023696682% 1.5em 0;			/* 21px / 633px */
	text-align: center;
	width: 31.121642969984202211%;				/* 197px / 633px */
	text-transform: uppercase;
	letter-spacing: 0.05em;
}
.figure b {
	display: block;
	font-size: 14px;
	font-family: "Book Antiqua", "Palatino Linotype", Georgia, serif;
	letter-spacing: 0.1em;
}
.figure img {
	-webkit-border-radius: 4px;
	-moz-border-radius: 4px;
	border-radius: 4px;
	-webkit-box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
	-moz-box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);;
	box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);;
	display: block;
	margin: 0 auto 1em;
}
li#f-mycroft,
li#f-winter {
	margin-right: 0;
}
.footer {
	background: url("site/ornament.png") 50% 0 repeat-x;
	font-size: 12px;
	text-align: center;
	padding: 40px 0 20px;
}
.footer p {
	margin-bottom: 0.5em;
}
@media (max-width: 600px) {
	/* 633px grid (88x6 col, 21x5 gut; 88+21+88+21+88+21+88+21+88+21+88) */
	.inner {
		position: relative;
	}
	.mast,
	.intro,
	.main,
	.footer {
		float: none;
		width: auto;
	}
	h1 {
		background: none;
	}
	h1 a {
		padding-top: 70px;
		height: 87px;
	}
	ul.nav {
		background: url("site/ornament.png") no-repeat 0 -20px;
		border-top: none;
		margin: 0 auto;
		position: absolute;
		top: 0;
		width: 100%;
	}
	ul.nav li {
		float: left;
		margin-right: 3.317535545023696682%;	/* 21px / 633px */
		width: 31.121642969984202211%;		/* 197px / 633px */
	}
	ul.nav a,
	ul.nav i {
		font: 10px Helvetica, Arial, sans-serif;
		letter-spacing: 0;
	}
	ul.nav a:hover,
	ul.nav a:focus {
		background-position: 0 100%;
	}
	li.first a {
		border-top: none;
		padding-top: 1em;
	}
	ul.nav li.last {
		margin-right: 0;
	}
	.intro {
		margin-top: 0;
	}
	.intro h2 {
		font-size: 1.4em;
	}
}
@media (max-width: 400px) {
	.figure,
	li#f-mycroft {
		margin-right: 3.317535545023696682%;	/* 21px / 633px */
		width: 48.341232227488151658%;	/* 306px / 633px */
	}
	li#f-watson,
	li#f-moriarty {
		margin-right: 0;
	}
}
@media (min-width: 1300px) {
	.mast {
		float: none;
		width: auto;
	}
	h1 {
		float: left;
		width: 31.875%;	/* 306px / 960px */
	}
	ul.nav {
		float: right;
		margin: 40px 0 1em;
		text-align: center;
		width: 65.9375%;	/* 633px / 960px */
	}
	ul.nav {
		border-top: none;
	}
	ul.nav li.first a {
		border-top: none;
		padding-top: 1em;
	}
	ul.nav li {
		float: left;
		margin-right: 3.317535545023696682%;			/* 21px / 633px */
		width: 31.121642969984202211%;				/* 197px / 633px */
	}
	ul.nav li.last {
		margin-right: 0;
	}
	.intro {
		margin-top: 1em;
	}
	.figure,
	li#f-mycroft {
		margin-right: 3.317535545023696682%;			/* 21px / 633px */
		width: 13.902053712480252764%;				/* 88px / 633px */
	}
	.footer {
		clear: both;
		float: none;
		margin-left: 56.770833333333333333%;			/* 327px / 960px */
		width: 20.520833333333333333%;				/* 197px / 960px */
	}
}
</style>

</head>

<body>

<div id="page">
	<div class="inner">
		<div class="mast">
			<h1 id="logo"><a href="#"><img src="site/logo.png" alt="Cannabis Law Society" /></a></h1>

			<ul class="nav">
				<li class="first"><a href="#"><i>Cannabis & Hemp</i> Issues</a></li>
				<li><a href="#"><i>Legal</i> Commentary</a></li>
				<li class="last"><a href="#"><i>About</i> Our Society</a></li>
			</ul><!-- /end .nav -->
		</div><!-- /end .mast -->

		<div class="section intro">
			<div>
				<h2>&#8220;Age quod &nbsp;<em>agis</em>.&#8221;</h2>

				<p>Lorem ipsum dolor sit amet, id sint aliquid oporteat mel. Cu sit tantas atomorum. Cu maiorum conceptam has, te vim eripuit nusquam. Ea splendide elaboraret nam, et elit habeo idque ius, per ut vitae minimum deterruisset. Clita putent audire an mei, mea no inani noster, ex est autem nusquam theophrastus.

Noster audiam legendos ei his, at mei eius verterem indoctum. Ei eam facilis placerat quaerendum, cu deserunt volutpat scribentur ius. Ex maiorum menandri necessitatibus vix, ea sit rebum nonumes democritum. Cu qui omittam adversarium comprehensam.

Latine tractatos maiestatis ex pri, et zril lobortis his. Eirmod accusamus vituperata vim cu, his te possim fabulas copiosae, oblique meliore per ut. Wisi vitae persecuti ex quo. Paulo suscipiantur eu eum. Vim agam dicam cu, quis etiam intellegam at eos, facete facilisis per an. Vivendo luptatum consectetuer an vel.

Volutpat mediocritatem vix id. Qui ut animal reformidans, iudico incorrupte scripserit pro et, sea purto voluptatum conclusionemque eu. Sed alia summo iuvaret te, utinam habemus democritum ei est. Eum in laoreet petentium. Vim choro similique ea, vel ei natum bonorum, vide atqui at eum.

Simul fabulas insolens vim in, an aeque sanctus ocurreret mei. Nibh movet sea cu, eos ea lorem democritum consectetuer, mel an postea accommodare. Ea nam malis ubique voluptua, qualisque necessitatibus mei et. Est ea detraxit complectitur, habeo dolor an eum, id abhorreant disputationi mea. Ne mel putent putant, quem appareat postulant at vis. Id erat torquatos eum, alia omnesque hendrerit id eam.</p>
			</div>
		</div><!-- /end .section.intro -->

		<div class="section main">
			<h2><b>Victors <abbr class="amp" title="And">&amp;</abbr> Villains</b></h2>
			<ol>
				<li id="f-holmes" class="figure">
					<a href="#">
						<img src="site/f-holmes.jpg" alt="" />
						<span class="figcaption">Sherlock <b>Holmes</b></span>
					</a>
				</li><!-- /end .figure -->
				<li id="f-watson" class="figure">
					<a href="#">
						<img src="site/f-watson.jpg" alt="" />
						<span class="figcaption"><abbr title="Professor">Dr</abbr> John Hemish <b>Watson</b></span>
					</a>
				</li><!-- /end .figure -->
				<li id="f-mycroft" class="figure">
					<a href="#">
						<img src="site/f-mycroft.jpg" alt="" />
						<span class="figcaption">Mycroft <b>Holmes</b></span>
					</a>
				</li><!-- /end .figure -->
				<li id="f-moriarty" class="figure">
					<a href="#">
						<img src="site/f-moriarty.jpg" alt="" />
						<span class="figcaption"><abbr title="Professor">Prof</abbr> James <b>Moriarty</b></span>
					</a>
				</li><!-- /end .figure -->
				<li id="f-adler" class="figure">
					<a href="#">
						<img src="site/f-adler.jpg" alt="" />
						<span class="figcaption">Irene <b>Adler</b></span>
					</a>
				</li><!-- /end .figure -->
				<li id="f-winter" class="figure">
					<a href="#">
						<img src="site/f-winter.jpg" alt="" />
						<span class="figcaption">James <b>Winter</b></span>
					</a>
				</li><!-- /end .figure -->
			</ol>
		</div><!-- /end .section.main -->

		<div class="footer">
			<p>Illustrations by <a href="http://en.wikipedia.org/wiki/Sidney_Paget">Sidney Paget</a>, words by <a href="http://en.wikipedia.org/wiki/Arthur_Conan_Doyle">Sir Arthur Conan Doyle</a>.</p>
			<p>What remains is by <a href="http://unstoppablerobotninja.com/">Ethan Marcotte</a>.</p>
		</div><!-- /end .footer -->
	</div><!-- /end .inner -->
</div><!-- /end #page -->

<!--[if lte IE 7]><script type="text/javascript" src="site/imgSizer.js"></script>
<script type="text/javascript">
window.onload = function() {
	imgSizer.collate();
}
</script><![endif]-->
<!--[if lte IE 6]><script type="text/javascript" src="share/ddpng.js"></script>
<script type="text/javascript">
DD_belatedPNG.fix('body, #page, h1, h1 img, ul.nav, ul.nav a, .main h2, .main h2 b, .footer');
</script><![endif]-->

</body>
</html>

