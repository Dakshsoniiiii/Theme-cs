# Theme-css
/*
Name: 			theme.css
Written by: 	Okler Themes - (http://www.okler.net)
Theme Version:	1.1.0
*/
html {
	direction: ltr;
	-webkit-box-shadow: none !important;
	box-shadow: none !important;
	font-size: 100%;
	margin: 0 !important;
	width:100%;
}
.nav > li > a:hover{
	background:transparent !important;
	/* color:707070 !important; */
}
@media (max-width:991px){
    #showlogin{
    	display:flex;
    	}
 
 
    }
 
	@media (min-width:991px){
    #showlogin{
    	display:none !important;
    	}
 
 
    }
a:hover{
	color:#FFF !important;
}
.Disclaimerr:hover{
	color:#707070 !important;
	text-decoration:underline !important;
}
 
.btn:hover{
	background: #FFF !important;
}
 
@media (min-width: 900px){
 
#navhead {
max-width: 1600px !important;
margin:10 0px;
}
}
#openaccountbtn:hover{
	/* background:#000 !important; */
	color:#707070 !important;
}
#openaccountbtn1:hover{
	/* background:#000 !important; */
	color:#707070 !important;
}
#loginbtn	:hover{
	/* background:#000 !important; */
	color:#707070 !important;
}
body {
	background:url(../img/background/background7.png) !important; 
	/*background-repeat:no-repeat !important;*/
	background-size:contain !important;
	/* background:#fff; */
	color: #fff !important;
	font-family: "Open Sans", sans-serif;
	font-size: 13px;
	line-height: 22px;
	margin: 0;
	padding: 0;
	overflow-x: hidden;
	overflow-y: scroll;
	text-align: left;
	image-rendering: -webkit-optimize-contrast !important;
}
 
.body {
	/* background:#fff; */
	background:url(../img/background/background7.png) !important; 
	/*background-repeat:no-repeat !important;
	background-size:100% 100% !important ;*/
	image-rendering: -webkit-optimize-contrast !important;
}
 
@media screen and (max-width:991px){
	.hideimg{
		display:none;
	}
}
 
 
body a {
	outline: none !important;
}
 
strong {
	line-height: 1;
}
 
h1, h2, h3, h4, h5, h6 {
	font-family: "Montserrat", sans-serif;
}
 
li {
	line-height: 24px;
}
 
/* Responsive */
@media (max-width: 991px) {
	html.safari {
		position: relative;
		overflow-x: hidden;
	}
}
 
@media (max-width: 479px) {
	body {
		font-size: 13px;
	}
}
 
 
/* Header */
#header {
	height:auto !important;
	position: relative;
	z-index: 1030;
	-webkit-transition: ease min-height 300ms;
	transition: ease min-height 300ms;
}
 
#header .header-body {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	background:url(../img/background/background7.png) !important; 
	image-rendering: -webkit-optimize-contrast !important;
	-webkit-transition: min-height 0.3s ease;
	transition: min-height 0.3s ease;
	width: 100%;
	z-index: 1001;
}
 
#header .header-container {
	position: relative;
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-ms-flex-flow: row wrap;
	flex-flow: row wrap;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	min-height: 104px;
	-webkit-transition: ease height 300ms;
	transition: ease height 300ms;
}
 
@media (max-width: 991px) {
	#header .header-container:not(.container) .header-nav-main {
		padding: 0 0.75rem;
	}
}
 
#header .header-container:after {
	content: '';
	display: block;
	position: absolute;
	bottom: 0;
	left: 50%;
	width: 100vw;
	border-bottom: 1px solid rgba(204, 204, 204, 0.2);
	-webkit-transform: translate3d(-50%, 0, 0);
	transform: translate3d(-50%, 0, 0);
	pointer-events: none;
	z-index: 0;
}
 
#header .header-container.header-column-equal-width .header-column {
	-webkit-box-flex: 1;
	-ms-flex: 1;
	flex: 1;
}
 
#header.header-border-bottom .header-container:after {
	content: '' !important;
}
 
#header.header-border-bottom-dark .header-container:after {
	border-color: rgba(37, 42, 44, 0.1);
}
 
#header .container {
	position: relative;
}
 
@media (max-width: 767px) {
	#header .container {
		width: 100%;
	}
}
 
#header .header-row {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	position: relative;
	-webkit-box-flex: 1;
	-ms-flex-positive: 1;
	flex-grow: 1;
	-ms-flex-preferred-size: 100%;
	flex-basis: 100%;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	-ms-flex-item-align: stretch;
	align-self: stretch;
	max-height: 100%;	
}
 
#header .header-column {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-item-align: stretch;
	align-self: stretch;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	-webkit-box-flex: 1;
	-ms-flex-positive: 1;
	flex-grow: 1;
}
 
#header .header-column .header-row {
	-webkit-box-pack: inherit;
	-ms-flex-pack: inherit;
	justify-content: inherit;
}
 
#header.header-no-min-height .header-body {
	min-height: 0 !important;
}
 
#header .header-top
{
    background: #d5d5d5;
	position: relative;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	border-bottom: 1px solid #EDEDEE;
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-flex: 1;
	-ms-flex-positive: 1;
	flex-grow: 1;
	font-size: 10.56px;
	font-size: 0.66rem;
	/* min-height: 41px; */
	max-height: 41px;
	z-index: 4;
	-webkit-transition: ease height 300ms, ease max-height 300ms, ease min-height 300ms;
	transition: ease height 300ms, ease max-height 300ms, ease min-height 300ms;
}
 
#header .header-top::after {
	clear: both;
	content: "";
	display: block;
}
 
#header .header-top .header-top-container {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-item-align: stretch;
	align-self: stretch;
	background-color:#3B3122;
}
 
#header .header-top p {
	margin: 0;
	padding: 0;
	line-height: 37px;
	float: left;
}
 
#header .header-top p .fa, #header .header-top p .fas, #header .header-top p .far, #header .header-top p .fal, #header .header-top p .fab, #header .header-top p .icons {
	position: relative;
	top: 1px;
}
 
#header .header-top .list-inline:not(.social-icons) > li {
	margin-right: 27.2px;
	margin-right: 1.7rem;
}
 
#header .header-top .list-inline:not(.social-icons) > li:last-child {
	margin-right: 0;
}
 
#header .header-top .header-social-icons li + li {
	margin-left: 0.4em;
}
 
#header .header-top .btn {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-item-align: stretch;
	align-self: stretch;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
}
 
#header .header-top.header-top-dark, #header .header-top.header-top-colored {
	background: #2E3237;
	border-bottom: 0;
}
 
#header .header-top.header-top-dark li, #header .header-top.header-top-dark span, #header .header-top.header-top-dark p, #header .header-top.header-top-dark a, #header .header-top.header-top-dark i, #header .header-top.header-top-colored li, #header .header-top.header-top-colored span, #header .header-top.header-top-colored p, #header .header-top.header-top-colored a, #header .header-top.header-top-colored i {
	color: #FFF;
}
 
#header .header-top.header-top-dark .dropdown-menu, #header .header-top.header-top-colored .dropdown-menu {
	margin: 0;
}
 
#header .header-top.header-top-dark .dropdown-menu li,
#header .header-top.header-top-dark .dropdown-menu li a, #header .header-top.header-top-colored .dropdown-menu li,
#header .header-top.header-top-colored .dropdown-menu li a {
	color: #9D9D9D;
}
 
#header .header-top.header-top-dark .dropdown-menu li:hover, #header .header-top.header-top-dark .dropdown-menu li:focus, #header .header-top.header-top-dark .dropdown-menu li:active,
#header .header-top.header-top-dark .dropdown-menu li a:hover,
#header .header-top.header-top-dark .dropdown-menu li a:focus,
#header .header-top.header-top-dark .dropdown-menu li a:active, #header .header-top.header-top-colored .dropdown-menu li:hover, #header .header-top.header-top-colored .dropdown-menu li:focus, #header .header-top.header-top-colored .dropdown-menu li:active,
#header .header-top.header-top-colored .dropdown-menu li a:hover,
#header .header-top.header-top-colored .dropdown-menu li a:focus,
#header .header-top.header-top-colored .dropdown-menu li a:active {
	color: #FFF;
}
 
#header .header-top.header-top-dark .nav i, #header .header-top.header-top-colored .nav i {
	color: #9D9D9D;
}
 
#header .header-top.header-top-dark .nav > li > a.dropdown-menu-toggle i, #header .header-top.header-top-colored .nav > li > a.dropdown-menu-toggle i {
	color: #FFF;
}
 
#header .header-logo {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	-ms-flex-item-align: stretch;
	align-self: stretch;
	position: relative;
	float: left;
}
 
#header .header-logo img {
	-webkit-transition: all 0.3s ease;
	transition: all 0.3s ease;
	position: relative;
	top: 0;
	/*margin-top: 16px;
	margin-top: 1rem;
	margin-bottom: 16px;
	margin-bottom: 1rem;*/
}
 
#header .header-logo img.logo-1 {
	opacity: 0;
}
 
#header .header-logo img.logo-1.active {
	opacity: 1;
}
 
#header .header-logo img.logo-2 {
	position: absolute;
	top: 50%;
	left: 0;
	margin: 0;
	opacity: 0;
	-webkit-transform: translate3d(-30%, -50%, 0);
	transform: translate3d(-30%, -50%, 0);
}
 
#header .header-logo img.logo-2.active {
	opacity: 1;
	-webkit-transform: translate3d(0, -50%, 0);
	transform: translate3d(0, -50%, 0);
}
 
#header .header-social-icons,
#header .header-search,
#header .header-button {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	-ms-flex-item-align: stretch;
	align-self: stretch;
}
 
#header .header-button a {
	font-size: 12px;
	font-size: 0.75rem;
	font-weight: 700;
}
 
#header .header-search form input {
	border-radius: 2px 0px 0px 2px;
	font-size: 12.8px;
	font-size: 0.8rem;
	border: 0;
}
 
#header .header-search form button {
	background: #FFF;
	height: 100%;
	border-radius: 0px 2px 2px 0px;
	-webkit-box-shadow: none;
	box-shadow: none;
}
 
#header .header-search form button i {
	color: #CCC;
}
 
#header .header-search.header-search-dark form input {
	background: #2E3237;
	color: #CCC;
}
 
#header .header-search.header-search-dark form button {
	background: #2E3237;
}
 
#header .header-search.header-search-dark form button i {
	color: #CCC;
}
 
#header .header-top-search form input {
	border-color: #ededee;
	border-radius: 35px;
	font-size: 11.2px;
	font-size: 0.7rem;
	padding: 7px 12px;
	line-height: 1;
	width: 150px;
}
 
#header .header-top-search form button {
	position: absolute;
	top: 0;
	right: 0;
	border: 0;
	background-color: transparent;
	height: 100%;
	z-index: 3;
}
 
#header .header-top-search form button i {
	color: #CCC;
}
 
#header .header-btn-collapse-nav {
	display: none;
	background: transparent;
	color: #1c1f21ZZ;
	outline: 0;
	border: none;
	width: 30px;
	height: 30px;
	padding: 0;
	margin: 16px 0;
}
 
#header .header-btn-collapse-nav .hamburguer span {
	position: absolute;
	top: 50%;
	left: 0;
	width: 100%;
	height: 2px;
	background: #F5F5F5;
	-webkit-transition: ease width 300ms;
	transition: ease width 300ms;
	-webkit-transform: translateY(-50%);
	transform: translateY(-50%);
}
 
#header .header-btn-collapse-nav .hamburguer span:nth-child(1) {
	top: 30%;
}
 
#header .header-btn-collapse-nav .hamburguer span:nth-child(2) {
	-webkit-transition-delay: 100ms;
	transition-delay: 100ms;
}
 
#header .header-btn-collapse-nav .hamburguer span:nth-child(3) {
	top: 70%;
	-webkit-transition-delay: 200ms;
	transition-delay: 200ms;
}
 
#header .header-btn-collapse-nav .close {
	opacity: 0;
	-webkit-transition: ease all 300ms;
	transition: ease all 300ms;
}
 
#header .header-btn-collapse-nav .close span {
	position: absolute;
	top: 50%;
	left: 50%;
	width: 20px !important;
	height: 1px;
	background: #F5F5F5;
	-webkit-transition: ease all 300ms;
	transition: ease all 300ms;
	-webkit-transform-origin: 50% 0;
	transform-origin: 50% 0;
}
 
#header .header-btn-collapse-nav .close span:nth-child(1) {
	-webkit-transform: translateX(-50%) rotate(45deg);
	transform: translateX(-50%) rotate(45deg);
}
 
#header .header-btn-collapse-nav .close span:nth-child(2) {
	-webkit-transform: translateX(-50%) rotate(-45deg);
	transform: translateX(-50%) rotate(-45deg);
}
 
#header .header-btn-collapse-nav.active .hamburguer {
	opacity: 0;
}
 
#header .header-btn-collapse-nav.active .hamburguer span {
	width: 0;
}
 
#header .header-btn-collapse-nav.active .close {
	opacity: 1;
	-webkit-transition: ease all 300ms;
	transition: ease all 300ms;
}
 
#header .header-btn-collapse-nav.active .close span {
	width: 80%;
	-webkit-transition: ease all 300ms;
	transition: ease all 300ms;
}
 
#header .header-btn-collapse-nav.active .close span:nth-child(2) {
	-webkit-transition-delay: 300ms;
	transition-delay: 300ms;
}
 
#header .header-btn-collapse-nav.header-btn-collapse-nav-light .hamburguer span,
#header .header-btn-collapse-nav.header-btn-collapse-nav-light .close span {
	background: #FFF;
}
 
#header.header-effect-shrink .header-container {
	min-height: 100px;
}
 
#header.header-container-no-min-height .header-container {
	min-height: 0;
}
 
#header.header-no-border-bottom .header-body {
	border-bottom: 0;
}
 
@-webkit-keyframes headerReveal {
	from {
		top: -150px;
	}
 
	to {
		top: 0;
	}
}
 
@keyframes headerReveal {
	from {
		top: -150px;
	}
 
	to {
		top: 0;
	}
}
 
html.sticky-header-active #header.header-effect-reveal .header-body {
	-webkit-animation: headerReveal 300ms;
	animation: headerReveal 300ms;
}
 
html.sticky-header-active #header.header-no-border-bottom .header-body {
	border-bottom: 1px solid rgba(204, 204, 204, 0.2);
}
 
html.sticky-header-active #header.header-effect-shrink .header-body .header-top {
	max-height: 0;
}
 
html #header.header-transparent {
	min-height: 0 !important;
	width: 100%;
	position: absolute;
}
 
html #header.header-transparent .header-body {
	position: relative;
	top: 0;
	background: transparent;
}
 
html #header.header-transparent .header-body:before {
	content: "";
	position: absolute;
	width: 100%;
	height: 100%;
	left: 0;
	right: 0;
	top: 0;
	bottom: 0;
	background: #FFF;
	opacity: 0;
	-webkit-transition: opacity 0.3s ease;
	transition: opacity 0.3s ease;
	-webkit-transform: translate3d(0, 0, 0);
	-webkit-backface-visibility: hidden;
	-webkit-perspective: 1000px;
	perspective: 1000px;
}
 
html #header.header-transparent .header-container {
	min-height: 92px;
}
 
html #header.header-transparent .header-container:after {
	content: none;
}
 
html #header.header-transparent .header-nav-main {
	padding: 0 16px;
	padding: 0 1rem;
	-webkit-transition: ease padding 300ms;
	transition: ease padding 300ms;
}
 
html #header.header-transparent .header-nav-main:before {
	width: 100%;
	-webkit-transition: ease width 300ms;
	transition: ease width 300ms;
}
 
html #header.header-transparent-dark .header-body:before {
	background: #1c1f21;
}
 
html.sticky-header-enabled #header.header-transparent .header-body {
	position: fixed;
}
 
html:not(.sticky-header-active) #header.header-transparent .header-body {
	border-bottom: 0;
}
 
@media (min-width: 992px) {
	html:not(.sticky-header-active) #header.header-transparent .header-nav-main nav > ul > li > a:not(.active) {
		color: #FFF;
	}
 
	html:not(.sticky-header-active) #header.header-transparent .header-nav-main.header-nav-main-dark nav > ul > li > a:not(.active) {
		color: #1c1f21;
	}
}
 
html.sticky-header-active #header.header-transparent .header-container:after {
	content: '';
}
 
html.sticky-header-active #header.header-transparent .header-body:before {
	opacity: 1;
}
 
html.sticky-header-active #header.header-transparent .header-nav-main:before {
	width: 100vw;
}
 
@media (max-width: 991px) {
	html.sticky-header-active #header.header-transparent .header-container:after {
		content: '';
	}
 
	html.sticky-header-active #header.header-transparent .header-nav-main {
		padding: 0;
	}
 
	html.sticky-header-active.mobile-menu-opened #header.header-transparent .header-container:after {
		content: none;
	}
}
 
html #header.header-semi-transparent, html #header.header-semi-transparent-light {
	position: absolute;
	min-height: 0 !important;
	width: 100%;
}
 
html #header.header-semi-transparent .header-container:after, html #header.header-semi-transparent-light .header-container:after {
	content: none;
}
 
html #header.header-semi-transparent .header-body, html #header.header-semi-transparent-light .header-body {
	background: #000 !important;
}
 
html #header.header-semi-transparent .header-body:before, html #header.header-semi-transparent-light .header-body:before {
	content: "";
	position: absolute;
	width: 100%;
	height: 100%;
	left: 0;
	right: 0;
	top: 0;
	bottom: 0;
	background: #252A2C;
	border-bottom: 0;
	opacity: 0.1;
	-webkit-transition: opacity 0.3s ease;
	transition: opacity 0.3s ease;
}
 
html #header.header-semi-transparent .header-nav-main, html #header.header-semi-transparent-light .header-nav-main {
	padding: 0 16px;
	padding: 0 1rem;
	-webkit-transition: ease padding 300ms;
	transition: ease padding 300ms;
}
 
html #header.header-semi-transparent .header-nav-main:before, html #header.header-semi-transparent-light .header-nav-main:before {
	width: 100%;
	-webkit-transition: ease width 300ms;
	transition: ease width 300ms;
}
 
html #header.header-semi-transparent-light .header-body:before {
	background: #FFF;
}
 
html:not(.sticky-header-active) #header.header-semi-transparent .header-body, html:not(.sticky-header-active) #header.header-semi-transparent-light .header-body {
	border-bottom: 0;
}
 
@media (min-width: 992px) {
	html:not(.sticky-header-active) #header.header-semi-transparent .header-nav-main nav > ul > li:not(.active) > a, html:not(.sticky-header-active) #header.header-semi-transparent-light .header-nav-main nav > ul > li:not(.active) > a {
		color: #FFF;
	}
}
 
@media (min-width: 992px) {
	html.sticky-header-active #header.header-semi-transparent .header-nav-main nav > ul > li:not(.active) > a {
		color: #FFF;
	}
}
 
html.sticky-header-active #header.header-semi-transparent .header-body {
	border-color: rgba(46, 50, 55, 0.2);
}
 
html.sticky-header-active #header.header-transparent .header-container:after, html.sticky-header-active #header.header-semi-transparent-light .header-container:after {
	content: '';
	z-index: 0;
}
 
html.sticky-header-active #header.header-semi-transparent .header-body:before, html.sticky-header-active #header.header-semi-transparent-light .header-body:before {
	opacity: 1;
}
 
@media (max-width: 991px) {
	html #header.header-transparent .header-container:not(.container) .header-nav-main, html #header.header-semi-transparent .header-container:not(.container) .header-nav-main, html #header.header-semi-transparent-light .header-container:not(.container) .header-nav-main {
		margin: 0 1rem;
	}
 
	html.sticky-header-active #header.header-semi-transparent .header-nav-main, html.sticky-header-active #header.header-semi-transparent-light .header-nav-main {
		padding: 0;
	}
 
	html.sticky-header-active #header.header-semi-transparent .header-nav-main:before, html.sticky-header-active #header.header-semi-transparent-light .header-nav-main:before {
		width: 100vw;
	}
}
 
@media (max-width: 767px) {
	#header .header-top li {
		font-size: 1.1em;
	}
}
 
html #header.header-container-bottom-border .header-container:after {
	content: none;
}
 
html #header.header-container-bottom-border .header-body:after {
	content: '';
	display: block;
	position: absolute;
	left: 50%;
	bottom: 0;
	width: 100%;
	border-bottom: 1px solid rgba(255, 255, 255, 0.2);
	-webkit-transform: translateX(-50%);
	transform: translateX(-50%);
}
 
@media (min-width: 576px) {
	html #header.header-container-bottom-border .header-body:after {
		max-width: 510px;
	}
}
 
@media (min-width: 768px) {
	html #header.header-container-bottom-border .header-body:after {
		max-width: 690px;
	}
}
 
@media (min-width: 992px) {
	html #header.header-container-bottom-border .header-body:after {
		max-width: 930px;
	}
}
 
@media (min-width: 1200px) {
	html #header.header-container-bottom-border .header-body:after {
		max-width: 1110px;
	}
}
 
html.sticky-header-active #header.header-container-bottom-border .header-container .header-container:after {
	content: '';
}
 
html.sticky-header-active #header.header-container-bottom-border .header-body:after {
	content: none;
}
 
html #header.header-with-borders .header-body:after, html #header.header-with-borders-dark .header-body:after {
	content: '';
	display: block;
	position: absolute;
	left: 50%;
	bottom: 0;
	width: 100%;
	border-bottom: 0;
	-webkit-transform: translateX(-50%);
	transform: translateX(-50%);
}
 
html #header.header-with-borders .header-logo,
html #header.header-with-borders .header-social-icons,
html #header.header-with-borders .header-search,
html #header.header-with-borders .header-button, html #header.header-with-borders-dark .header-logo,
html #header.header-with-borders-dark .header-social-icons,
html #header.header-with-borders-dark .header-search,
html #header.header-with-borders-dark .header-button {
	border-right: 1px solid rgba(204, 204, 204, 0.2);
	border-left: 1px solid rgba(204, 204, 204, 0.2);
}
 
html #header.header-transparent .header-body:after, html #header.header-semi-transparent .header-body:after, html #header.header-semi-transparent-light .header-body:after {
	border-bottom: 1px solid rgba(204, 204, 204, 0.2);
}
 
html #header.header-with-borders-dark .header-body:after {
	border-color: rgba(46, 50, 55, 0.8);
}
 
html #header.header-with-borders-dark .header-logo,
html #header.header-with-borders-dark .header-social-icons,
html #header.header-with-borders-dark .header-search,
html #header.header-with-borders-dark .header-button {
	border-color: rgba(46, 50, 55, 0.8);
}
 
html.sticky-header-active #header:not(.header-with-borders-sticky).header-with-borders .header-body:after,
html.sticky-header-active #header:not(.header-with-borders-sticky).header-with-borders .header-logo,
html.sticky-header-active #header:not(.header-with-borders-sticky).header-with-borders .header-social-icons,
html.sticky-header-active #header:not(.header-with-borders-sticky).header-with-borders .header-search,
html.sticky-header-active #header:not(.header-with-borders-sticky).header-with-borders .header-button, html.sticky-header-active #header:not(.header-with-borders-sticky).header-with-borders-dark .header-body:after,
html.sticky-header-active #header:not(.header-with-borders-sticky).header-with-borders-dark .header-logo,
html.sticky-header-active #header:not(.header-with-borders-sticky).header-with-borders-dark .header-social-icons,
html.sticky-header-active #header:not(.header-with-borders-sticky).header-with-borders-dark .header-search,
html.sticky-header-active #header:not(.header-with-borders-sticky).header-with-borders-dark .header-button {
	border-color: transparent;
}
 
html #header.header-floating {
	position: absolute;
	min-height: 0 !important;
	width: 100%;
}
 
@media (min-width: 992px) {
	html #header.header-floating {
		top: 45px;
	}
}
 
html #header.header-floating .header-container:after {
	content: none;
}
 
html #header.header-floating .header-body {
	margin: 0 auto;
	border-radius: 3px;
}
 
@media (min-width: 992px) {
	html #header.header-floating .header-body {
		max-width: 960px;
	}
 
	html #header.header-floating .header-body .header-container {
		padding-right: 30px;
		padding-left: 30px;
	}
}
 
@media (min-width: 1200px) {
	html #header.header-floating .header-body {
		max-width: 1140px;
	}
}
 
html.sticky-header-active #header.header-floating .header-container:after {
	content: '';
}
 
html.sticky-header-active #header.header-floating .header-body {
	max-width: none;
	margin: none;
}
 
html.sticky-header-active #header.header-floating .header-body .header-container {
	padding-right: 15px;
	padding-left: 15px;
}
 
html #header.header-dark .header-body {
	background: #202326;
	border-color: rgba(46, 50, 55, 0.2);
}
 
html #header.header-dark.header-transparent .header-body, html #header.header-dark.header-semi-transparent .header-body, html #header.header-dark.header-semi-transparent-light .header-body {
	background: transparent;
}
 
html #header.header-dark .header-nav-main:before {
	background-color: #202326;
}
 
html #header.header-dark .header-nav-main nav > ul > li {
	border-color: #2E3237;
}
 
html #header.header-dark .header-nav-main nav > ul > li > a {
	color: #FFF;
}
 
html #header.header-dark .header-nav-main nav > ul > li.dropdown .dropdown-menu {
	background-color: #202326;
}
 
html #header.header-dark .header-nav-main nav > ul > li.dropdown .dropdown-menu li {
	border-color: #2E3237;
}
 
html #header.header-dark .header-nav-main nav > ul > li.dropdown .dropdown-menu li a {
	color: #777;
}
 
html #header.header-dark .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-title {
	color: #707070;
}
 
html #header.header-dark .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li.active > a, html #header.header-dark .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li:hover > a, html #header.header-dark .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li:focus > a {
	color: #FFF;
}
 
html #header.header-dark .header-search form input {
	background: #2E3237;
	color: #CCC;
}
 
html #header.header-dark .header-search form button {
	background: #2E3237;
}
 
html #header.header-dark .header-search form button i {
	color: #CCC;
}
 
html.sticky-header-active #header .header-btn-collapse-nav.on-sticky-dark .hamburguer span,
html.sticky-header-active #header .header-btn-collapse-nav.on-sticky-dark .close span {
	background: #1c1f21;
}
 
html.sticky-header-active #header .header-btn-collapse-nav.on-sticky-light .hamburguer span,
html.sticky-header-active #header .header-btn-collapse-nav.on-sticky-light .close span {
	background: #FFF;
}
 
html:not(.sticky-header-active) #header.header-transparent-sticky-deactive .header-body:before {
	background: transparent !important;
}
 
/* Navigations */
/* Header Nav Main */
@media (min-width: 992px) {
	#header .header-nav {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-align: center;
		-ms-flex-align: center;
		align-items: center;
		-webkit-box-flex: 1;
		-ms-flex-positive: 1;
		flex-grow: 1;
		-webkit-box-pack: end;
		-ms-flex-pack: end;
		justify-content: flex-end;
		-ms-flex-item-align: stretch;
		align-self: stretch;
	}
 
	#header .header-nav.header-nav-border-top:before {
		content: '';
		display: block;
		position: absolute;
		top: 0;
		left: 50%;
		width: 100vw;
		border-top: 1px solid #EDEDEE;
		-webkit-transform: translateX(-50%);
		transform: translateX(-50%);
	}
 
	#header .header-action {
		border-left: 1px solid #e1e1e1;
		margin-left: 1.1rem;
		padding-left: 1.1rem;
		font-size: 0.85rem;
	}
 
	#header .header-nav-main {
		display: -webkit-box !important;
		display: -ms-flexbox !important;
		display: flex !important;
		height: auto !important;
		-webkit-box-ordinal-group: 0;
		-ms-flex-order: -1;
		order: -1;
		-ms-flex-item-align: stretch;
		align-self: stretch;
	}
 
	#header .header-nav-main nav.collapse {
		display: -webkit-box !important;
		display: -ms-flexbox !important;
		display: flex !important;
		width: 100%;
	}
 
	#header .header-nav-main nav > ul {
		width: 100%;
	}
 
	#header .header-nav-main nav > ul > li {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		height: 100%;
	}
 
	#header .header-nav-main nav > ul > li + li {
		margin-left: 2px;
	}
 
	#header .header-nav-main nav > ul > li a {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		line-height: 1.42857143;
		font-family: "Montserrat", sans-serif;
		-webkit-box-align: center;
		-ms-flex-align: center;
		align-items: center;
	}
 
	#header .header-nav-main nav > ul > li a .menu-arrow {
		position: absolute;
		min-width: 30px;
		height: 100%;
		right: 15px;
		top: 0;
	}
 
	#header .header-nav-main nav > ul > li a .menu-arrow:after {
		content: " ";
		position: absolute;
		top: 50%;
		left: 50%;
		border-color: #CCC;
		border-top: 1px solid;
		border-right: 1px solid;
		width: 6px;
		height: 6px;
		-webkit-transform: translate(-50%, -50%) rotate(45deg);
		transform: translate(-50%, -50%) rotate(45deg);
	}
 
	#header .header-nav-main nav > ul > li a.dropdown-item {
		background-color: transparent;
	}
 
	#header .header-nav-main nav > ul > li > a {
		border-radius: 4px;
		font-style: normal;
		font-weight: 500;
		line-height: 1.2;
		padding: 10px 10px;
		color: #FFF !important;
	}
 
#header .header-nav-main nav > ul > li.active> a {
    color: #FFF !important;
    padding-bottom: 15px;
    background:#000!important;
    border-radius: 2px;
	font-style: normal;
	font-weight: 700;
	line-height: 1.2;
	padding: 2px 5px;
}
	#header .header-nav-main nav > ul > li > a .menu-arrow {
		display: none;
	}
 
	#header .header-nav-main nav > ul > li.open > a, #header .header-nav-main nav > ul > li:hover > a, #header .header-nav-main nav > ul > li.active > a {
		color: #CCC;
		background: transparent;
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu {
		background: #252A2C;
		top: -10000px;
		display: block;
		opacity: 0;
		left: auto;
		border-radius: 4px;
		border: 0;
		-webkit-box-shadow: 0 0 45px rgba(0, 0, 0, 0.08);
		box-shadow: 0 0 45px rgba(0, 0, 0, 0.08);
		margin: -3px 0 0 0;
		min-width: 260px;
		padding: 20px 10px 20px 30px;
		text-align: left;
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li {
		border-bottom: 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li a:not(.btn) {
		color: #e8e4e4;
		font-size: 1em;
		font-weight: 400;
		padding: 8px 0;
		position: relative;
		text-transform: none;
		-webkit-transition: ease transform 300ms, ease color 300ms;
		transition: ease transform 300ms, ease color 300ms;
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu {
		position: relative;
		z-index: 1;
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-menu {
		background: #2a2f31;
		left: 100%;
		display: block;
		margin-top: -5px;
		margin-left: -1px;
		border-radius: 4px;
		opacity: 0;
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-menu.dropdown-reverse {
		left: auto;
		right: 100%;
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:hover, #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:focus {
		z-index: 2;
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:hover > .dropdown-menu, #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:focus > .dropdown-menu {
		top: -15px;
		opacity: 1;
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:hover.dropdown-reverse > a.dropdown-toggle .menu-arrow, #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:focus.dropdown-reverse > a.dropdown-toggle .menu-arrow {
		-webkit-transform: rotate(180deg);
		transform: rotate(180deg);
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu.dropdown-reverse > .dropdown-menu {
		left: auto;
		right: calc(100% + 20px);
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu.dropdown-reverse > .dropdown-menu:after {
		content: '';
		position: absolute;
		top: 0;
		right: -20px;
		height: 100%;
		width: 20px;
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li:hover > a, #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li:focus > a {
		color: #FFF;
		-webkit-transform: translate3d(10px, 0, 0);
		transform: translate3d(10px, 0, 0);
	}
 
	#header .header-nav-main nav > ul > li.dropdown .dropdown-menu li:last-child {
		border-bottom: 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown.open > .dropdown-menu, #header .header-nav-main nav > ul > li.dropdown:hover > .dropdown-menu {
		top: 100%;
		left: 0;
		display: block;
		opacity: 1;
		margin-top: 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega {
		position: static;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu {
		background: #252A2C;
		border-radius: 6px;
		left: 50% !important;
		right: auto !important;
		padding: 0;
		width: 100% !important;
		max-width: 95vw;
		-webkit-transform: translate3d(-50%, 0, 0);
		transform: translate3d(-50%, 0, 0);
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content {
		padding: 40px 20px;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content > .row > div {
		padding: 15px 5px 10px 30px;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content > .row > div:first-child:not(.dropdown-mega-sub-content-block),
  #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content > .row > div + div {
		border-right: 1px solid #303537;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content > .row > div:last-child {
		border-right: 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-title {
		color: #FFF;
		display: block;
		font-size: 1em;
		font-weight: 600;
		margin-top: 1.2rem;
		padding-bottom: 5px;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-title:first-child {
		margin-top: 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav {
		list-style: none;
		padding: 0;
		margin: 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav li a {
		display: block;
		padding: 8px;
		line-height: 1.42857143;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav li:hover > a, #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav li:focus > a {
		color: #FFF;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav li:last-child a {
		border-bottom: 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block {
		position: absolute;
		left: 0;
		top: 0;
		padding: 55px 30px !important;
		height: 100%;
		border-radius: 4px 0 0 4px;
		overflow: hidden;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block.dropdown-mega-sub-content-block-right {
		right: 0;
		left: auto;
		border-radius: 0 4px 4px 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block.overlay:before {
		z-index: 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block h4 {
		font-size: 1.6em;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block p {
		color: #777;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block .content-block-image {
		position: absolute;
		bottom: 0;
		right: 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block .content-block-button {
		display: inline-block;
		border-bottom: none;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block > span,
  #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block > h4,
  #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block > p,
  #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block > a {
		opacity: 0;
		-webkit-transform: translateY(-15%);
		transform: translateY(-15%);
		-webkit-transition: ease transform 300ms, ease opacity 300ms;
		transition: ease transform 300ms, ease opacity 300ms;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block > img.content-block-image {
		opacity: 0;
		-webkit-transform: translateX(15%);
		transform: translateX(15%);
		-webkit-transition: ease transform 300ms, ease opacity 300ms;
		transition: ease transform 300ms, ease opacity 300ms;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block > span {
		-webkit-transition-delay: 100ms;
		transition-delay: 100ms;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block > h4 {
		-webkit-transition-delay: 200ms;
		transition-delay: 200ms;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block > p {
		-webkit-transition-delay: 300ms;
		transition-delay: 300ms;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block > img.content-block-image {
		-webkit-transition-delay: 400ms;
		transition-delay: 400ms;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block > a {
		-webkit-transition-delay: 500ms;
		transition-delay: 500ms;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega:hover .dropdown-mega-sub-content-block > span,
  #header .header-nav-main nav > ul > li.dropdown-mega:hover .dropdown-mega-sub-content-block > h4,
  #header .header-nav-main nav > ul > li.dropdown-mega:hover .dropdown-mega-sub-content-block > p,
  #header .header-nav-main nav > ul > li.dropdown-mega:hover .dropdown-mega-sub-content-block > a {
		opacity: 1;
		-webkit-transform: translateY(0);
		transform: translateY(0);
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega:hover .dropdown-mega-sub-content-block > img.content-block-image {
		opacity: 1;
		-webkit-transform: translateX(0);
		transform: translateX(0);
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-style-2 > .dropdown-menu {
		border-radius: 4px;
		width: 100vw !important;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-style-2 .dropdown-mega-sub-content-block {
		position: relative;
		height: auto;
		padding: 30px 50px !important;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-style-2 .dropdown-mega-sub-content-block:before {
		content: '';
		position: absolute;
		top: 0;
		right: 0;
		bottom: 0;
		left: 15px;
		background: #282D2F;
		z-index: -1;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-style-2 .dropdown-mega-sub-nav .dropdown-submenu .dropdown-menu {
		border-radius: 0;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin {
		position: relative;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin > .dropdown-menu {
		left: auto !important;
	}
 
	#header .header-nav-main.header-nav-main-light nav > ul > li > a {
		color: #FFF;
	}
 
	#header .header-nav-main.header-nav-main-light nav > ul > li > a:hover {
		background: transparent;
	}
 
	#header .header-nav-main.header-nav-main-dark nav > ul > li > a {
		color: #1c1f21;
	}
 
	#header .header-nav-main.header-nav-main-dark nav > ul > li > a:hover {
		background: transparent;
	}
 
	#header .header-nav-main.header-nav-main-uppercase nav > ul > li > a {
		text-transform: uppercase;
		font-weight: 600;
/* font-size:11px; */
		padding-left: 1.9em;
		padding-right: 1.9em;
	}
}
 
@media (min-width: 992px) and (max-width: 1199px) {
	#header .header-nav-main.header-nav-main-uppercase nav > ul > li > a {
/* font-size:11px; */
	}
}
 
@media (min-width: 992px) {
	#header .header-nav.header-nav-top-line .header-nav-main nav > ul > li > a {
		position: relative;
	}
 
	#header .header-nav.header-nav-top-line .header-nav-main nav > ul > li > a.active:before {
		content: '';
		display: block;
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		/* border-top: 3px solid #CCC; */
	}
 
	#header .header-nav.header-nav-top-line .header-nav-main nav > ul > li:hover > a:before, #header .header-nav.header-nav-top-line .header-nav-main nav > ul > li:focus > a:before {
		content: '';
		display: block;
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		/* border-top: 3px solid #CCC; */
	}
 
	#header .header-nav.header-nav-stripe .header-nav-main nav > ul > li {
		margin-left: 0;
	}
 
	#header .header-nav.header-nav-stripe .header-nav-main nav > ul > li > .dropdown-menu {
		-webkit-box-shadow: 0 21px 55px -20px rgba(0, 0, 0, 0.08);
		box-shadow: 0 21px 55px -20px rgba(0, 0, 0, 0.08);
		border-radius: 0 0 4px 4px;
	}
 
	#header .header-nav.header-nav-stripe .header-nav-main nav > ul > li > .dropdown-menu:before {
		content: '';
		position: absolute;
		top: -1px;
		left: 0;
		width: 100%;
		border-top: 1px solid rgba(204, 204, 204, 0.3);
	}
 
	#header .header-nav.header-nav-stripe .header-nav-main nav > ul > li > a {
		border-radius: 0;
		-webkit-transition: none;
		transition: none;
	}
 
	#header .header-nav.header-nav-stripe .header-nav-main nav > ul > li > a.active {
		background: #CCC;
		color: #FFF;
	}
 
	#header .header-nav.header-nav-stripe .header-nav-main nav > ul > li:hover > a, #header .header-nav.header-nav-stripe .header-nav-main nav > ul > li:focus > a {
		background: #CCC;
		color: #FFF;
	}
 
	#header .header-nav.header-nav-stripe .header-nav-main nav > ul > li.dropdown-full-color > a {
		color: #777 !important;
	}
 
	#header .header-nav.header-nav-stripe .header-nav-main nav > ul > li.dropdown-full-color > a.active {
		color: #FFF !important;
	}
 
	#header .header-nav.header-nav-stripe .header-nav-main nav > ul > li.dropdown-full-color:hover > a, #header .header-nav.header-nav-stripe .header-nav-main nav > ul > li.dropdown-full-color:focus > a {
		color: #FFF !important;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul > li.dropdown .dropdown-menu {
		background-color: #FFF;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul > li.dropdown .dropdown-menu li:hover > a, #header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul > li.dropdown .dropdown-menu li:focus > a {
		color: #CCC;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu .dropdown-menu {
		background-color: #FFF;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content > .row > div {
		border-color: #F1F3F7;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-title {
		color: #1c1f21;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-style-2 .dropdown-mega-sub-content-block:before {
		background-color: #CCC;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-style-2 .dropdown-mega-sub-content-block .content-block-button {
		color: #FFF !important;
	}
 
	#header .header-nav.header-nav-sub-title .header-nav-main nav > ul > li > a, #header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li > a {
		position: relative;
		-webkit-box-orient: vertical;
		-webkit-box-direction: normal;
		-ms-flex-direction: column;
		flex-direction: column;
		-webkit-box-align: start;
		-ms-flex-align: start;
		align-items: flex-start;
		-webkit-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
		padding-right: 0;
		padding-left: 0;
		margin-left: 0.7rem;
		margin-right: 0.7rem;
	}
 
	#header .header-nav.header-nav-sub-title .header-nav-main nav > ul > li > a > span, #header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li > a > span {
		font-size: 0.8em;
		text-transform: none;
		font-weight: normal;
		margin-top: 0.3rem;
	}
 
	#header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li > a {
		-webkit-transition: ease padding-bottom 300ms;
		transition: ease padding-bottom 300ms;
	}
 
	#header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li > a.active {
		padding-bottom: 35px;
	}
 
	#header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li > a.active > span {
		top: 60%;
		left: 0;
		opacity: 1;
	}
 
	#header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li > a > span {
		position: absolute;
		top: 50%;
		left: 0;
		margin-top: 0;
		opacity: 0;
		-webkit-transform: translate3d(0, -50%, 0);
		transform: translate3d(0, -50%, 0);
		-webkit-transition: ease opacity 200ms, ease top 300ms;
		transition: ease opacity 200ms, ease top 300ms;
	}
 
	#header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li:hover > a, #header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li:focus > a {
		padding-bottom: 35px;
	}
 
	#header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li:hover > a > span, #header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li:focus > a > span {
		top: 60%;
		left: 0;
		opacity: 1;
	}
 
	#header .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li > a {
		position: relative;
	}
 
	#header .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li > a:before {
		content: '';
		display: block;
		position: absolute;
		top: 56%;
		left: 0.55rem;
		right: 100%;
		border-top: 7px solid rgba(204, 204, 204, 0.5);
		-webkit-transform: translate3d(0, -50%, 0);
		transform: translate3d(0, -50%, 0);
		-webkit-transition: ease right 300ms;
		transition: ease right 300ms;
	}
 
	#header .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li > a.active {
		color: #777;
	}
 
	#header .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li > a.active:before {
		right: 0.55rem;
	}
 
	#header .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li:hover > a, #header .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li:focus > a {
		color: #777;
	}
 
	#header .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li:hover > a:before, #header .header-nav.header-nav-line-under-text .header-nav-main nav > ul > li:focus > a:before {
		right: 0.55rem;
	}
 
	#header .header-nav.header-nav-square .header-nav-main nav > ul > li > a {
		border-radius: 0;
	}
 
	#header .header-nav.header-nav-square .header-nav-main nav > ul > li.dropdown .dropdown-menu {
		border-radius: 0;
	}
 
	#header .header-nav.header-nav-square .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-menu {
		border-radius: 0;
	}
 
	#header .header-nav.header-nav-square .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu {
		border-radius: 0;
	}
}
 
@media (min-width: 992px) and (max-width: 1199px) {
	#header .header-nav-main nav > ul > li > a {
		/*  */
		padding:10px;
	}
}
 
@media (min-width: 992px) {
	#header .header-nav-main-effect-1 nav > ul > li.dropdown:not(.dropdown-mega-signin) .dropdown-menu li,
  #header .header-nav-main-effect-1 nav > ul > li.dropdown:not(.dropdown-mega-signin) .dropdown-mega-sub-nav li {
		-webkit-transition: -webkit-transform .2s ease-out;
		transition: -webkit-transform .2s ease-out;
		transition: transform .2s ease-out;
		transition: transform .2s ease-out, -webkit-transform .2s ease-out;
		-webkit-transform: translate3d(0, -5px, 0);
		transform: translate3d(0, -5px, 0);
	}
 
	#header .header-nav-main-effect-1 nav > ul > li.dropdown:not(.dropdown-mega-signin):hover > .dropdown-menu li,
  #header .header-nav-main-effect-1 nav > ul > li.dropdown:not(.dropdown-mega-signin):hover .dropdown-mega-sub-nav li {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
	}
 
	#header .header-nav-main-effect-1 nav > ul > li.dropdown .dropdown-menu {
		-webkit-transition: -webkit-transform .2s ease-out;
		transition: -webkit-transform .2s ease-out;
		transition: transform .2s ease-out;
		transition: transform .2s ease-out, -webkit-transform .2s ease-out;
		-webkit-transform: translate3d(0, -5px, 0);
		transform: translate3d(0, -5px, 0);
	}
 
	#header .header-nav-main-effect-1 nav > ul > li.dropdown.open > .dropdown-menu, #header .header-nav-main-effect-1 nav > ul > li.dropdown:hover > .dropdown-menu {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
	}
 
	#header .header-nav-main-effect-1 nav > ul > li.dropdown.dropdown-mega > .dropdown-menu {
		-webkit-transform: translate3d(-50%, -5px, 0);
		transform: translate3d(-50%, -5px, 0);
	}
 
	#header .header-nav-main-effect-1 nav > ul > li.dropdown.dropdown-mega > .dropdown-menu > li {
		-webkit-transform: translate3d(0, 0, 0) !important;
		transform: translate3d(0, 0, 0) !important;
	}
 
	#header .header-nav-main-effect-1 nav > ul > li.dropdown.dropdown-mega.open > .dropdown-menu, #header .header-nav-main-effect-1 nav > ul > li.dropdown.dropdown-mega:hover > .dropdown-menu {
		-webkit-transform: translate3d(-50%, 0, 0);
		transform: translate3d(-50%, 0, 0);
	}
 
	#header .header-nav-main-effect-1 nav > ul > li.dropdown.dropdown-mega.dropdown-mega-signin > .dropdown-menu {
		-webkit-transform: translate3d(0, -5px, 0);
		transform: translate3d(0, -5px, 0);
	}
 
	#header .header-nav-main-effect-1 nav > ul > li.dropdown.dropdown-mega.dropdown-mega-signin.open > .dropdown-menu, #header .header-nav-main-effect-1 nav > ul > li.dropdown.dropdown-mega.dropdown-mega-signin:hover > .dropdown-menu {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
	}
}
 
@media (min-width: 992px) {
	#header .header-nav-main-effect-2 nav > ul > li.dropdown .dropdown-menu {
		-webkit-transition: opacity .2s ease-out, -webkit-transform .2s ease-out;
		transition: opacity .2s ease-out, -webkit-transform .2s ease-out;
		transition: transform .2s ease-out, opacity .2s ease-out;
		transition: transform .2s ease-out, opacity .2s ease-out, -webkit-transform .2s ease-out;
		-webkit-transform: translate3d(0, 5px, 0);
		transform: translate3d(0, 5px, 0);
		opacity: 0;
	}
 
	#header .header-nav-main-effect-2 nav > ul > li.dropdown.open > .dropdown-menu, #header .header-nav-main-effect-2 nav > ul > li.dropdown:hover > .dropdown-menu {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
		opacity: 1;
	}
 
	#header .header-nav-main-effect-2 nav > ul > li.dropdown.dropdown-mega > .dropdown-menu {
		-webkit-transform: translate3d(-50%, 5px, 0);
		transform: translate3d(-50%, 5px, 0);
	}
 
	#header .header-nav-main-effect-2 nav > ul > li.dropdown.dropdown-mega.open > .dropdown-menu, #header .header-nav-main-effect-2 nav > ul > li.dropdown.dropdown-mega:hover > .dropdown-menu {
		-webkit-transform: translate3d(-50%, 0, 0);
		transform: translate3d(-50%, 0, 0);
	}
 
	#header .header-nav-main-effect-2 nav > ul > li.dropdown.dropdown-mega.dropdown-mega-signin > .dropdown-menu {
		-webkit-transform: translate3d(0, 5px, 0);
		transform: translate3d(0, 5px, 0);
	}
 
	#header .header-nav-main-effect-2 nav > ul > li.dropdown.dropdown-mega.dropdown-mega-signin.open > .dropdown-menu, #header .header-nav-main-effect-2 nav > ul > li.dropdown.dropdown-mega.dropdown-mega-signin:hover > .dropdown-menu {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
	}
}
 
@media (min-width: 992px) {
	#header .header-nav-main-effect-3 nav > ul > li.dropdown .dropdown-menu {
		-webkit-transition: -webkit-transform .2s ease-out;
		transition: -webkit-transform .2s ease-out;
		transition: transform .2s ease-out;
		transition: transform .2s ease-out, -webkit-transform .2s ease-out;
		-webkit-transform: translate3d(0, 10px, 0);
		transform: translate3d(0, 10px, 0);
	}
 
	#header .header-nav-main-effect-3 nav > ul > li.dropdown.open > .dropdown-menu, #header .header-nav-main-effect-3 nav > ul > li.dropdown:hover > .dropdown-menu {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
	}
 
	#header .header-nav-main-effect-3 nav > ul > li.dropdown.dropdown-mega > .dropdown-menu {
		-webkit-transform: translate3d(-50%, 10px, 0);
		transform: translate3d(-50%, 10px, 0);
	}
 
	#header .header-nav-main-effect-3 nav > ul > li.dropdown.dropdown-mega.open > .dropdown-menu, #header .header-nav-main-effect-3 nav > ul > li.dropdown.dropdown-mega:hover > .dropdown-menu {
		-webkit-transform: translate3d(-50%, 0, 0);
		transform: translate3d(-50%, 0, 0);
	}
}
 
@media (min-width: 992px) {
	#header .header-nav-main-effect-4 nav > ul > li.dropdown .dropdown-menu {
		-webkit-transition: opacity .2s ease-out, -webkit-transform .2s ease-out;
		transition: opacity .2s ease-out, -webkit-transform .2s ease-out;
		transition: transform .2s ease-out, opacity .2s ease-out;
		transition: transform .2s ease-out, opacity .2s ease-out, -webkit-transform .2s ease-out;
		-webkit-transform: translate3d(-20px, 0, 0);
		transform: translate3d(-20px, 0, 0);
		opacity: 0;
	}
 
	#header .header-nav-main-effect-4 nav > ul > li.dropdown .dropdown-menu.dropdown-reverse {
		-webkit-transition: opacity .2s ease-out, -webkit-transform .2s ease-out;
		transition: opacity .2s ease-out, -webkit-transform .2s ease-out;
		transition: transform .2s ease-out, opacity .2s ease-out;
		transition: transform .2s ease-out, opacity .2s ease-out, -webkit-transform .2s ease-out;
		-webkit-transform: translate3d(20px, 0, 0);
		transform: translate3d(20px, 0, 0);
		left: auto;
		right: 100%;
		opacity: 0;
	}
 
	#header .header-nav-main-effect-4 nav > ul > li.dropdown.open > .dropdown-menu, #header .header-nav-main-effect-4 nav > ul > li.dropdown:hover > .dropdown-menu {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
		opacity: 1;
	}
 
	#header .header-nav-main-effect-4 nav > ul > li.dropdown.dropdown-mega > .dropdown-menu {
		-webkit-transform: translate3d(-55%, 0, 0);
		transform: translate3d(-55%, 0, 0);
	}
 
	#header .header-nav-main-effect-4 nav > ul > li.dropdown.dropdown-mega > .dropdown-menu.dropdown-reverse {
		-webkit-transform: translate3d(45%, 0, 0);
		transform: translate3d(45%, 0, 0);
	}
 
	#header .header-nav-main-effect-4 nav > ul > li.dropdown.dropdown-mega.open > .dropdown-menu, #header .header-nav-main-effect-4 nav > ul > li.dropdown.dropdown-mega:hover > .dropdown-menu {
		-webkit-transform: translate3d(-50%, 0, 0);
		transform: translate3d(-50%, 0, 0);
	}
}
 
@media (min-width: 992px) {
	#header .header-nav-main-sub-effect-1 nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-menu {
		-webkit-transition: opacity .2s ease-out, -webkit-transform .2s ease-out;
		transition: opacity .2s ease-out, -webkit-transform .2s ease-out;
		transition: transform .2s ease-out, opacity .2s ease-out;
		transition: transform .2s ease-out, opacity .2s ease-out, -webkit-transform .2s ease-out;
		-webkit-transform: translate3d(-20px, 0, 0);
		transform: translate3d(-20px, 0, 0);
		opacity: 0;
	}
 
	#header .header-nav-main-sub-effect-1 nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:hover > .dropdown-menu {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
		opacity: 1;
	}
 
	#header .header-nav-main-sub-effect-1 nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu.dropdown-reverse > .dropdown-menu {
		-webkit-transform: translate3d(20px, 0, 0);
		transform: translate3d(20px, 0, 0);
	}
 
	#header .header-nav-main-sub-effect-1 nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu.dropdown-reverse:hover > .dropdown-menu {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
	}
}
/* Header Nav Main Mobile */
@media (max-width: 991px) {
	#header .header-nav {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-align: center;
		-ms-flex-align: center;
		align-items: center;
	}
 
	#header .header-nav-main {
		position: absolute;
		top: 99%;
		right: 0;
		left: 0;
		background: transparent;
		margin-top: 0px;
		z-index: 1;
	}
 
	#header .header-nav-main:before {
		content: '';
		display: block;
		position: absolute;
		top: 0;
		left: 50%;
		width: 100vw;
		height: 100%;
		background: #000;
		z-index: -1;
		-webkit-transform: translateX(-50%);
		transform: translateX(-50%);
	}
 
	#header .header-nav-main nav {
		max-height: 60vh;
		overflow: hidden;
		overflow-y: auto;
		margin: 1.3rem 0;
		-webkit-transition: ease all 300ms;
		transition: ease all 300ms;
	}
 
	#header .header-nav-main nav.collapsing {
		overflow-y: hidden;
	}
 
	#header .header-nav-main nav.closed {
		margin: 0;
	}
 
	#header .header-nav-main nav::-webkit-scrollbar {
		width: 5px;
	}
 
	#header .header-nav-main nav::-webkit-scrollbar-thumb {
		border-radius: 0px;
		background: rgba(204, 204, 204, 0.5);
	}
 
	#header .header-nav-main nav > ul li {
		border-bottom: 1px solid #888888;
		clear: both;
		display: block;
		float: none;
		margin: 0;
		padding: 0;
		position: relative;
		width: 100%;
	}
 
	#header .header-nav-main nav > ul li a:not(.btn) {
		position: relative;
		display: block;
		color: #FFF;
		font-style: normal;
		line-height: 1.3;
		padding: 10px 0;
		border-radius: 4px;
		font-family: "Montserrat", sans-serif;
		font-size:14px;
	}
 
	#header .header-nav-main nav > ul li a:not(.btn):hover, #header .header-nav-main nav > ul li a:not(.btn):focus, #header .header-nav-main nav > ul li a:not(.btn).active {
		color: #FFF;
	}
 
	#header .header-nav-main nav > ul li a:not(.btn) .menu-arrow {
		position: absolute;
		min-width: 30px;
		height: 100%;
		right: 5px;
		top: 0;
		-webkit-transform-origin: center;
		transform-origin: center;
		-webkit-transition: ease transform 800ms;
		transition: ease transform 800ms;
	}
 
	#header .header-nav-main nav > ul li a:not(.btn) .menu-arrow:after {
		content: " ";
		position: absolute;
		top: 50%;
		left: 50%;
		border-color: #CCC;
		border-top: 1px solid;
		border-right: 1px solid;
		width: 7px;
		height: 7px;
		-webkit-transform: translate(-50%, -50%) rotate(135deg);
		transform: translate(-50%, -50%) rotate(135deg);
	}
 
	#header .header-nav-main nav > ul li a:not(.btn).dropdown-item {
		background-color: transparent;
	}
 
	#header .header-nav-main nav > ul li.dropdown .dropdown-menu {
		background: transparent;
		padding: 0 0 20px;
		margin: 0;
		font-size: 13px;
		-webkit-box-shadow: none;
		box-shadow: none;
		border-radius: 0;
		border: 0;
		clear: both;
		display: none;
		float: none;
		position: static;
	}
 
	#header .header-nav-main nav > ul li.dropdown .dropdown-menu li.dropdown-submenu.opened > .dropdown-toggle .menu-arrow {
		-webkit-transform: rotateX(180deg) translate3d(0, -3px, 0);
		transform: rotateX(180deg) translate3d(0, -3px, 0);
	}
 
	#header .header-nav-main nav > ul li.dropdown .dropdown-menu li.dropdown-submenu.opened > .dropdown-menu {
		margin-left: 20px;
	}
 
	#header .header-nav-main nav > ul li.dropdown.opened > .dropdown-toggle .menu-arrow {
		-webkit-transform: rotateX(180deg) translate3d(0, -3px, 0);
		transform: rotateX(180deg) translate3d(0, -3px, 0);
	}
 
	#header .header-nav-main nav > ul li.dropdown.opened > .dropdown-menu {
		padding-left: 20px;
	}
 
	#header .header-nav-main nav > ul li.dropdown-mega .dropdown-mega-content {
		padding-left: 0;
	}
 
	#header .header-nav-main nav > ul li.dropdown-mega .dropdown-mega-sub-title {
		margin-top: 10px;
		display: block;
		color: #FFF;
	}
 
	#header .header-nav-main nav > ul li.dropdown-mega .dropdown-mega-sub-nav {
		margin: 0;
		padding: 0;
		list-style: none;
	}
 
	#header .header-nav-main nav > ul li.dropdown-mega .dropdown-mega-sub-nav > li > a {
		display: block;
		text-decoration: none;
	}
 
	#header .header-nav-main nav > ul li.dropdown-full-color:first-child {
		margin-top: 0;
	}
 
	#header .header-nav-main nav > ul li.dropdown-full-color > a {
		padding: 10px 15px;
	}
 
	#header .header-nav-main nav > ul li.dropdown-full-color > .dropdown-menu li {
		border: none;
	}
 
	#header .header-nav-main nav > ul li.dropdown-full-color.opened > .dropdown-menu {
		padding-left: 15px;
	}
 
	#header .header-nav-main nav > ul li:last-child {
		border-bottom: 0;
	}
 
	#header .header-nav-main nav > ul > li > a {
		font-size: 14px;
		font-weight: 400;
		margin-top: 1px;
		margin-bottom: 1px;
	}
 
	#header .header-btn-collapse-nav {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		position: relative;
		z-index: 1;
	}
 
	#header .header-nav.header-nav-sub-title .header-nav-main nav > ul > li > a, #header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li > a {
		text-align: left;
	}
 
	#header .header-nav.header-nav-sub-title .header-nav-main nav > ul > li > a > span, #header .header-nav.header-nav-sub-title-animated .header-nav-main nav > ul > li > a > span {
		font-size: 0.6em;
		display: block;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main:before {
		background-color: #FFF;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul li {
		border-color: #F1F3F7;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul li a:hover, #header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul li a:focus, #header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul li a.active {
		color: #CCC;
	}
 
	#header .header-nav.header-nav-light-dropdown .header-nav-main nav > ul li.dropdown-mega .dropdown-mega-sub-title {
		color: #1c1f21;
		font-weight: bold;
	}
 
	html.safari #header .header-nav-main nav a {
		-webkit-transform: translate3d(0px, 0px, 1px) !important;
		transform: translate3d(0px, 0px, 1px) !important;
	}
}
/* Side Header */
/* Side Header */
html.side-header:not(.side-header-from-out) #header {
	min-height: 0 !important;
}
 
@media (min-width: 992px) {
	html.side-header .main .container, html.side-header #footer .container {
		padding: 0 35px;
		width: 100% !important;
		max-width: 1210px;
	}
 
	html.side-header body > .body {
		margin: 0 0 0 280px;
		width: auto;
		overflow-x: hidden;
		overflow-y: visible;
	}
 
	html.side-header body > .body .forcefullwidth_wrapper_tp_banner .rev_slider_wrapper {
		width: 100% !important;
		left: auto !important;
	}
 
	html.side-header .nano > .nano-content {
		right: -12px !important;
		margin-right: 0 !important;
	}
 
	html.side-header .nano > .nano-pane {
		width: 7px;
		background: rgba(28, 31, 33, 0.05);
	}
 
	html.side-header .nano > .nano-pane > .nano-slider {
		background: rgba(28, 31, 33, 0.2);
	}
 
	html.side-header #header {
		background: #FFF;
		position: fixed;
		-webkit-box-shadow: 0 0 18px rgba(28, 31, 33, 0.07);
		box-shadow: 0 0 18px rgba(28, 31, 33, 0.07);
		top: 0;
		left: 0;
		width: 280px;
		height: 100%;
		padding-top: 3rem;
	}
 
	html.side-header #header .header-body {
		border-bottom: 0;
	}
 
	html.side-header #header .header-container {
		display: block;
		margin: 0;
	}
 
	html.side-header #header .header-container:after {
		content: none;
	}
 
	html.side-header #header .header-row {
		-webkit-box-orient: vertical;
		-webkit-box-direction: normal;
		-ms-flex-direction: column;
		flex-direction: column;
	}
 
	html.side-header #header .header-nav {
		margin: 2.7rem 0;
		height: 33vh;
	}
 
	html.side-header #header .header-logo img {
		margin: 0;
	}
 
	html.side-header #header .header-nav-main nav > ul > li {
		-ms-flex-preferred-size: 100%;
		flex-basis: 100%;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		height: auto;
	}
 
	html.side-header #header .header-nav-main nav > ul > li a {
		position: relative;
		padding: 0.7rem;
		-ms-flex-preferred-size: 100%;
		flex-basis: 100%;
	}
 
	html.side-header #header .header-nav-main nav > ul > li a.dropdown-toggle .menu-arrow {
		display: block;
		right: 0;
		-webkit-transform-origin: center;
		transform-origin: center;
		-webkit-transition: ease transform 800ms;
		transition: ease transform 800ms;
	}
 
	html.side-header #header .header-nav-main nav > ul > li a.dropdown-toggle .menu-arrow:after {
		top: 45%;
		-webkit-transform: translate(-50%, -50%) rotate(135deg);
		transform: translate(-50%, -50%) rotate(135deg);
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu, html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu {
		display: none;
		position: relative;
		top: 0;
		padding: 0 0 0 0.7rem;
		margin: 0;
		opacity: 1;
		-webkit-box-shadow: none;
		box-shadow: none;
		background-color: transparent;
		min-width: 0;
		width: 100% !important;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu, html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu {
		position: static;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:hover > .dropdown-menu, html.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:focus > .dropdown-menu, html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu:hover > .dropdown-menu, html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu:focus > .dropdown-menu {
		top: 0;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow, html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow {
		right: 12px;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-menu, html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu > .dropdown-menu {
		display: none;
		left: 0;
		padding-left: 1rem;
		margin: 0;
		opacity: 1;
		width: 100%;
		background: transparent;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu.opened > .dropdown-toggle .menu-arrow, html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu.opened > .dropdown-toggle .menu-arrow {
		-webkit-transform: rotateX(180deg) translate3d(0, -3px, 0);
		transform: rotateX(180deg) translate3d(0, -3px, 0);
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li:hover > a, html.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li:focus > a, html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li:hover > a, html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li:focus > a {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown.opened > .dropdown-toggle .menu-arrow, html.side-header #header .header-nav-main nav > ul > li.dropdown-mega.opened > .dropdown-toggle .menu-arrow {
		-webkit-transform: rotateX(180deg) translate3d(0, -3px, 0);
		transform: rotateX(180deg) translate3d(0, -3px, 0);
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu {
		padding: 0 0 0 0.2rem;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow {
		right: 13px;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown-mega [class*="col"] {
		-ms-flex-preferred-size: 100%;
		flex-basis: 100%;
		max-width: 100%;
		margin-left: 0;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content {
		padding: 0 0 0 0.5rem;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content > .row > div {
		padding: 0 0 0 15px;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block {
		display: none !important;
	}
 
	html.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-title {
		color: #1c1f21;
		margin: 0.4rem 0 0;
	}
 
	html.side-header.side-header-right body > .body {
		margin: 0 280px 0 0;
	}
 
	html.side-header.side-header-right #header {
		left: auto;
		right: 0;
	}
}
 
html.side-header.side-header-semi-transparent body > .body {
	margin: 0;
}
 
html.side-header.side-header-semi-transparent .nano > .nano-pane {
	background: rgba(255, 255, 255, 0.05);
}
 
html.side-header.side-header-semi-transparent .nano > .nano-pane > .nano-slider {
	background: rgba(255, 255, 255, 0.2);
}
 
html.side-header.side-header-semi-transparent #header {
	background: transparent;
}
 
html.side-header.side-header-semi-transparent #header .header-container:after {
	content: none;
}
 
html.side-header.side-header-semi-transparent #header .header-body {
	background: transparent;
	border-bottom: 0;
}
 
html.side-header.side-header-semi-transparent #header .header-body:before {
	content: "";
	position: absolute;
	width: 100%;
	height: 100%;
	left: 0;
	right: 0;
	top: 0;
	bottom: 0;
	background: #1c1f21;
	border-bottom: 0;
	opacity: 0.2;
	-webkit-transition: opacity 0.3s ease;
	transition: opacity 0.3s ease;
}
 
html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li:not(.active) > a {
	color: #FFF;
}
 
html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li.dropdown .dropdown-menu > li {
	border-bottom-color: rgba(255, 255, 255, 0.2);
}
 
html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li.dropdown .dropdown-menu > li > a {
	color: #d0d0d0;
}
 
html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li.dropdown .dropdown-menu > li:hover > a, html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li.dropdown .dropdown-menu > li:focus > a {
	color: #FFF;
}
 
html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-title {
	color: #FFF;
}
 
html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav li {
	border-bottom-color: rgba(255, 255, 255, 0.2);
}
 
html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav li a {
	color: #d0d0d0;
}
 
html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav li:hover > a, html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav li:focus > a {
	color: #FFF;
}
 
@media (max-width: 991px) {
	html.side-header.side-header-semi-transparent #header {
		position: absolute;
		width: 100%;
	}
 
	html.side-header.side-header-semi-transparent #header .header-nav-main {
		background: transparent;
	}
 
	html.side-header.side-header-semi-transparent #header .header-nav-main:before {
		background: #1c1f21;
		opacity: 0.2;
	}
 
	html.side-header.side-header-semi-transparent #header .header-nav-main nav > ul > li {
		border-bottom-color: rgba(255, 255, 255, 0.2);
	}
}
 
html.side-header.side-header-semi-transparent-light #header .header-body:before {
	background: #FFF;
}
 
@media (max-width: 991px) {
	html.side-header.side-header-semi-transparent-light #header .header-nav-main:before {
		background: #FFF;
	}
}
 
@media (max-width: 991px) {
	html.side-header #header .nano {
		position: static;
		overflow: visible;
	}
 
	html.side-header #header .nano .nano-content {
		top: 99%;
		bottom: auto;
		right: 0 !important;
		overflow: visible;
	}
}
/*
Side Header From Out
*/
@media (min-width: 992px) {
	html.side-header.side-header-from-out .main .container, html.side-header.side-header-from-out #footer .container {
		max-width: 1140px;
	}
 
	html.side-header.side-header-from-out body > .body {
		margin: 0;
	}
 
	html.side-header.side-header-from-out #header {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-align: center;
		-ms-flex-align: center;
		align-items: center;
		right: 0;
		left: auto;
		width: 490px;
		-webkit-transform: translate3d(100%, 0, 0);
		transform: translate3d(100%, 0, 0);
		-webkit-transition: ease transform 300ms;
		transition: ease transform 300ms;
	}
 
	html.side-header.side-header-from-out #header.side-header-show {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
	}
 
	html.side-header.side-header-from-out #header .header-column {
		-webkit-box-orient: vertical;
		-webkit-box-direction: normal;
		-ms-flex-direction: column;
		flex-direction: column;
	}
 
	html.side-header.side-header-from-out #header .header-nav {
		height: 37vh;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li a {
		-webkit-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
		font-size: 0.85rem;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li a > i {
		position: relative;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li a .menu-arrow {
		min-width: 45px;
		margin-right: -1.9rem;
		right: 13px;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown .dropdown-menu {
		padding: 0;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-menu {
		padding-left: 0;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega [class*="col"] {
		margin-top: 0.8rem;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega [class*="col"]:last-child {
		margin-bottom: 0.8rem;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu {
		padding: 0;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content {
		margin-top: -0.8rem;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-title {
		margin: 0;
		text-align: center;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav li a {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav + .dropdown-mega-sub-title {
		margin-top: 0.8rem;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content {
		padding: 0;
	}
 
	html.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content > .row > div {
		padding: 0;
	}
}
 
@media (max-width: 991px) {
	html.side-header.side-header-from-out #header .header-nav-main nav > ul li:hover > a, html.side-header.side-header-from-out #header .header-nav-main nav > ul li:focus > a {
		color: #FFF;
	}
}
/*
Side Header Overlay Full Screen
*/
html.side-header-overlay-full-screen body > .body {
	margin: 0;
	width: auto;
	overflow-x: hidden;
	overflow-y: visible;
}
 
html.side-header-overlay-full-screen body > .body .forcefullwidth_wrapper_tp_banner .rev_slider_wrapper {
	width: 100% !important;
	left: auto !important;
}
 
html.side-header-overlay-full-screen #header {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	background-color: rgba(27, 30, 33, 0.99);
	position: fixed;
	-webkit-box-shadow: 0 0 18px rgba(28, 31, 33, 0.07);
	box-shadow: 0 0 18px rgba(28, 31, 33, 0.07);
	top: 0;
	left: 0;
	width: 100vw;
	height: 100vh;
	padding-top: 48px;
	padding-top: 3rem;
	opacity: 0;
	visibility: hidden;
	-webkit-transition: ease opacity 300ms, ease visibility 300ms;
	transition: ease opacity 300ms, ease visibility 300ms;
}
 
html.side-header-overlay-full-screen #header.side-header-show {
	opacity: 1;
	visibility: visible;
	-webkit-transition: ease opacity 300ms, ease visibility 300ms;
	transition: ease opacity 300ms, ease visibility 300ms;
}
 
html.side-header-overlay-full-screen #header .header-container:after {
	content: none;
}
 
html.side-header-overlay-full-screen #header .header-body {
	background-color: transparent;
	border-bottom: 0;
}
 
html.side-header-overlay-full-screen #header .header-row {
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
}
 
html.side-header-overlay-full-screen #header .header-column {
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
}
 
html.side-header-overlay-full-screen #header .header-nav {
	width: 290px;
	height: 37vh;
	margin: 32px auto;
	margin: 2rem auto;
	border-top: 1px solid #292929;
	border-bottom: 1px solid #292929;
}
 
html.side-header-overlay-full-screen #header .header-nav > .nano-pane {
	top: 20px;
	bottom: 20px;
}
 
html.side-header-overlay-full-screen #header .header-nav > .nano-pane > .nano-slider {
	background: #CCC;
}
 
html.side-header-overlay-full-screen #header .header-logo img {
	margin: 0;
}
 
html.side-header-overlay-full-screen #header .header-nav-main {
	-ms-flex-item-align: auto;
	align-self: auto;
	max-height: 100%;
	padding-right: 0;
	margin-top: 25.6px;
	margin-top: 1.6rem;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav {
	width: 100%;
	max-height: none;
	overflow: visible;
	overflow-y: visible;
	border-bottom: 0;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul {
	padding-bottom: 25.6px;
	padding-bottom: 1.6rem;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-preferred-size: 100%;
	flex-basis: 100%;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	height: auto;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li a {
	position: relative;
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	padding: 11.2px;
	padding: 0.7rem;
	-ms-flex-preferred-size: 100%;
	flex-basis: 100%;
	font-size: 13.6px !important;
	font-size: 0.85rem !important;
	color: #FFF;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li a > i {
	position: relative;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li a .menu-arrow {
	position: relative;
	min-width: 45px;
	margin-right: -33.6px;
	margin-right: -2.1rem;
	right: 10px;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li a.dropdown-toggle .menu-arrow {
	display: block;
	-webkit-transform-origin: center;
	transform-origin: center;
	-webkit-transition: ease transform 800ms;
	transition: ease transform 800ms;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li a.dropdown-toggle .menu-arrow:after {
	top: 45%;
	-webkit-transform: translate(-50%, -50%) rotate(135deg);
	transform: translate(-50%, -50%) rotate(135deg);
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown .dropdown-menu, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu {
	display: none;
	position: relative;
	top: 0;
	padding: 0;
	margin: 0;
	opacity: 1;
	-webkit-box-shadow: none;
	box-shadow: none;
	background-color: transparent;
	min-width: 0;
	width: 100% !important;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li {
	border-bottom: 0;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu {
	position: static;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-menu, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu > .dropdown-menu {
	display: none;
	left: 0;
	padding-left: 0;
	margin: 0;
	opacity: 1;
	width: 100%;
	background: transparent;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:hover .dropdown-menu, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu:focus .dropdown-menu, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu:hover .dropdown-menu, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu:focus .dropdown-menu {
	top: 0;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu.opened > .dropdown-toggle .menu-arrow, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu.opened > .dropdown-toggle .menu-arrow {
	-webkit-transform: rotateX(180deg) translate3d(0, -3px, 0);
	transform: rotateX(180deg) translate3d(0, -3px, 0);
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li:hover > a, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li:focus > a, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li:hover > a, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li:focus > a {
	color: #FFF;
	-webkit-transform: translate3d(0, 0, 0);
	transform: translate3d(0, 0, 0);
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li > a, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li > a {
	color: #9d9d9d;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown.opened > .dropdown-toggle .menu-arrow, html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega.opened > .dropdown-toggle .menu-arrow {
	-webkit-transform: rotateX(180deg) translate3d(0, -3px, 0);
	transform: rotateX(180deg) translate3d(0, -3px, 0);
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega [class*="col"] {
	-ms-flex-preferred-size: 100%;
	flex-basis: 100%;
	max-width: 100%;
	margin-top: 12.8px;
	margin-top: 0.8rem;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega [class*="col"]:last-child {
	margin-bottom: 12.8px;
	margin-bottom: 0.8rem;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu {
	padding: 0;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content {
	margin-top: -12.8px;
	margin-top: -0.8rem;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-title {
	margin: 0;
	text-align: center;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav li a {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-nav + .dropdown-mega-sub-title {
	margin-top: 12.8px;
	margin-top: 0.8rem;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content {
	padding: 0;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-content > .row > div {
	padding: 0;
	margin-left: 0;
}
 
html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block {
	display: none !important;
}
 
@media (max-width: 991px) {
	html.side-header-overlay-full-screen #header .header-nav-main {
		position: static;
		background-color: transparent;
		padding: 0;
		margin-top: 0;
	}
 
	html.side-header-overlay-full-screen #header .header-nav-main:before {
		content: none;
	}
 
	html.side-header-overlay-full-screen #header .header-nav-main nav > ul > li {
		border-bottom: 0;
	}
}
 
/* Side Header Toggles */
.side-header-btn-toggle {
	display: -webkit-inline-box;
	display: -ms-inline-flexbox;
	display: inline-flex;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	color: #FFF;
	font-weight: 600;
}
 
html.sticky-wrapper-active .side-header-btn-toggle {
	color: #1c1f21;
}
 
.side-header-btn-close {
	position: absolute;
	top: 20.8px;
	top: 1.3rem;
	right: 19.2px;
	right: 1.2rem;
	font-size: 24px;
	font-size: 1.5rem;
}
 
@media (max-width: 991px) {
	html.side-header-from-out .side-header-btn-close {
		display: none;
	}
}
/* Double Carousel */
@media (min-width: 992px) {
	html.side-header:not(.side-header-from-out) .double-carousel .nav {
		margin-left: -140px;
	}
 
	html.side-header:not(.side-header-from-out) .double-carousel .wrapper-left {
		width: calc(35vw - 140px);
		margin-right: -140px;
	}
 
	html.side-header:not(.side-header-from-out) .double-carousel .wrapper-right {
		margin-left: -140px;
		width: calc(35vw - 140px);
	}
}
 
@media (max-width: 1600px) {
	html.side-header:not(.side-header-from-out) .double-carousel .nav .title-left,
  html.side-header:not(.side-header-from-out) .double-carousel .nav .title-right {
		display: none;
	}
}
 
@media (max-width: 1199px) and (min-width: 768px) {
	html.side-header:not(.side-header-from-out) .double-carousel .nav {
		top: 50%;
	}
 
	html.side-header:not(.side-header-from-out) .double-carousel .owl-carousel .owl-dots {
		top: 58%;
	}
}
 
/* IE */
@media (min-width: 992px) {
	html.ie.side-header .nano > .nano-content {
		right: 3px !important;
		margin-right: -20px !important;
		padding-right: 5px;
	}
}
 
/* Microsoft Edge */
@media (min-width: 992px) {
	html.edge.side-header .nano > .nano-content,
  html.gecko.side-header .nano > .nano-content {
		right: -16px !important;
	}
 
	html.edge.side-header #header .header-nav-main nav > ul > li a.dropdown-toggle .menu-arrow,
  html.gecko.side-header #header .header-nav-main nav > ul > li a.dropdown-toggle .menu-arrow {
		right: 6px;
	}
 
	html.edge.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow, html.edge.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow,
  html.gecko.side-header #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow,
  html.gecko.side-header #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow {
		right: 6px;
	}
 
	html.edge.side-header #header .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow,
  html.gecko.side-header #header .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow {
		right: 21px;
	}
 
	html.edge.side-header.side-header-from-out #header .header-nav-main nav > ul > li a.dropdown-toggle .menu-arrow,
  html.gecko.side-header.side-header-from-out #header .header-nav-main nav > ul > li a.dropdown-toggle .menu-arrow {
		right: 12px;
	}
 
	html.edge.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow, html.edge.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow,
  html.gecko.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow,
  html.gecko.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow {
		right: 12px;
	}
 
	html.edge.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow,
  html.gecko.side-header.side-header-from-out #header .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu li.dropdown-submenu > .dropdown-toggle .menu-arrow {
		right: 12px;
	}
}
 
/* Signin */
/* Header Signin / Signup / Logged */
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin.open > .dropdown-menu, #header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin:hover > .dropdown-menu {
	pointer-events: auto;
}
 
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin > a {
	position: relative;
}
 
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin > a:before {
	content: '';
	display: block;
	position: absolute;
	top: 50%;
	left: 0;
	height: 20px;
	border-left: 1px solid #CCC;
	-webkit-transform: translate3d(0, -50%, 0);
	transform: translate3d(0, -50%, 0);
}
 
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin > .dropdown-menu {
	max-width: 350px;
	width: 100vw !important;
	top: 100%;
	right: 0 !important;
	left: auto;
	pointer-events: none;
	background: #FFF;
}
 
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin > .dropdown-menu:before {
	content: '';
	display: block;
	position: absolute;
	top: -10px;
	right: 30px;
	width: 0;
	height: 0;
	border-left: 10px solid transparent;
	border-right: 10px solid transparent;
	border-bottom: 10px solid #FFF;
}
 
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin > .dropdown-menu li:hover > a {
	color: #CCC;
	-webkit-transform: translate3d(0, 0, 0);
	transform: translate3d(0, 0, 0);
}
 
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin .dropdown-mega-content > .row > div {
	padding: 5px 25px;
	border: none !important;
}
 
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin .forgot-pw:hover {
	text-decoration: underline;
}
 
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin.signin .signup-form,
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin.signin .recover-form {
	display: none;
}
 
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin.signup .signin-form,
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin.signup .recover-form {
	display: none;
}
 
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin.recover .signin-form,
#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin.recover .signup-form {
	display: none;
}
 
@media (max-width: 991px) {
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin > a {
		font-weight: bold;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin > a:before {
		content: none;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin > .dropdown-menu {
		display: block;
		max-width: 100%;
		padding: 0.6rem;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin > .dropdown-menu:before {
		content: none;
	}
 
	#header .header-nav-main nav > ul > li.dropdown-mega.dropdown-mega-signin.logged li {
		border-bottom: 0;
	}
}
/* Shop */
/* Shop */
html.shop #header .header-nav-main {
	-webkit-box-ordinal-group: 3;
	-ms-flex-order: 2;
	order: 2;
}
 
.mini-cart {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	position: relative;
}
 
.mini-cart .mini-cart-icon {
	position: relative;
	margin-left: 12.8px;
	margin-left: 0.8rem;
	top: -4px;
}
 
.mini-cart .mini-cart-icon > span {
	position: absolute;
	bottom: -5px;
	right: -5px;
	padding: 3.2px 4.8px;
	padding: 0.2rem 0.3rem;
}
 
.mini-cart .mini-cart-content {
	position: absolute;
	width: 300px;
	top: 100%;
	right: -32px;
	padding-top: 25.6px;
	padding-top: 1.6rem;
	opacity: 0;
	visibility: hidden;
	z-index: 1;
	-webkit-transform: translate3d(0, 20px, 0);
	transform: translate3d(0, 20px, 0);
	-webkit-transition: ease opacity 300ms, ease visibility 300ms, ease transform 300ms;
	transition: ease opacity 300ms, ease visibility 300ms, ease transform 300ms;
}
 
.mini-cart .mini-cart-content .inner-wrapper {
	position: relative;
	padding: 25.6px;
	padding: 1.6rem;
	-webkit-box-shadow: 0px 0px 30px -8px rgba(0, 0, 0, 0.5);
	box-shadow: 0px 0px 30px -8px rgba(0, 0, 0, 0.5);
}
 
.mini-cart .mini-cart-content .inner-wrapper:before {
	content: '';
	display: block;
	position: absolute;
	top: -10px;
	right: 30px;
	width: 0;
	height: 0;
	border-left: 10px solid transparent;
	border-right: 10px solid transparent;
	border-bottom: 10px solid #FFF;
}
 
.mini-cart .mini-cart-content .mini-cart-product {
	margin-bottom: 16px;
	margin-bottom: 1rem;
}
 
.mini-cart .mini-cart-content .mini-cart-product .product-image {
	position: relative;
}
 
.mini-cart .mini-cart-content .mini-cart-product .product-image > a {
	position: absolute;
	top: -11px;
	right: -12px;
	padding: 0;
	width: 22.4px;
	width: 1.4rem;
	height: 22.4px;
	height: 1.4rem;
	border: 1px solid #e9ecef;
	-webkit-box-shadow: 0px 0px 30px -8px rgba(0, 0, 0, 0.5);
	box-shadow: 0px 0px 30px -8px rgba(0, 0, 0, 0.5);
}
 
.mini-cart .mini-cart-content .mini-cart-total {
	padding: 11.2px 0;
	padding: 0.7rem 0;
	border-top: 1px solid #e9ecef;
	margin-bottom: 16px;
	margin-bottom: 1rem;
}
 
.mini-cart .mini-cart-content .mini-cart-actions .btn {
	display: block;
	width: 100%;
	text-align: center;
}
 
.mini-cart:hover .mini-cart-content {
	opacity: 1;
	visibility: visible;
	-webkit-transform: translate3d(0, 0, 0);
	transform: translate3d(0, 0, 0);
}
 
/* Header Search Expand */
#header .header-search-expanded {
	position: absolute;
	top: 50%;
	left: 0;
	width: 100%;
	height: 55px;
	opacity: 0;
	visibility: hidden;
	-webkit-transform: translate3d(0, -30%, 0);
	transform: translate3d(0, -30%, 0);
	-webkit-transition: ease opacity 300ms, ease visibility 300ms, ease transform 300ms;
	transition: ease opacity 300ms, ease visibility 300ms, ease transform 300ms;
}
 
#header .header-search-expanded > form {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-align: stretch;
	-ms-flex-align: stretch;
	align-items: stretch;
	height: 100%;
}
 
#header .header-search-expanded > form input {
	-webkit-box-shadow: none;
	box-shadow: none;
	border-color: transparent;
}
 
#header .header-search-expanded > form input::-webkit-input-placeholder {
	color: #b9b9b9;
}
 
#header .header-search-expanded > form input::-moz-placeholder {
	color: #b9b9b9;
}
 
#header .header-search-expanded > form input:-ms-input-placeholder {
	color: #b9b9b9;
}
 
#header .header-search-expanded > form button {
	position: absolute;
	top: 0;
	right: 0;
	z-index: 3;
	height: 100%;
	padding: 0;
	width: 50px;
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
	background: transparent;
	font-size: 22.4px;
	font-size: 1.4rem;
	-webkit-box-shadow: none;
	box-shadow: none;
}
 
#header .header-nav,
#header .header-logo {
	-webkit-transition: ease opacity 300ms, ease visibility 300ms, ease transform 300ms;
	transition: ease opacity 300ms, ease visibility 300ms, ease transform 300ms;
	padding-left: 100px;
}
 
html.sticky-header-active #header .header-search-expanded {
	height: 45px;
}
 
html.sticky-header-active #header .header-search-expanded > form button {
	padding-top: 6.4px;
	padding-top: 0.4rem;
}
 
html.header-search-expanded-active #header .header-search-expanded {
	opacity: 1;
	visibility: visible;
	-webkit-transform: translate3d(0, -50%, 0);
	transform: translate3d(0, -50%, 0);
	-webkit-transition: ease opacity 300ms 0ms, ease visibility 300ms 0ms, ease transform 300ms 0ms;
	transition: ease opacity 300ms 0ms, ease visibility 300ms 0ms, ease transform 300ms 0ms;
}
 
html.header-search-expanded-active #header .header-nav,
html.header-search-expanded-active #header .header-logo {
	opacity: 0;
	visibility: hidden;
	-webkit-transform: translate3d(0, -20px, 0);
	transform: translate3d(0, -20px, 0);
}
 
/* Mobile Menu Opened */
html.mobile-menu-opened #header .header-container:after {
	content: none;
}
 
html.mobile-menu-opened #header.header-container-bottom-border .header-body:after {
	content: none;
}
 
/* Page Header */
.page-header {
	background-color: #f1f3f7;
	margin: 0 0 50px 0;
	min-height: 50px;
	padding: 55px 0;
	position: relative;
	text-align: center;
}
 
.page-header .breadcrumb {
	background: none;
	margin: 0 0 8px 2px;
	padding: 0;
	position: relative;
	z-index: 1;
	-webkit-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}
 
.page-header .breadcrumb > li {
	display: inline-block;
	font-size: 0.85em;
	text-shadow: none;
}
 
.page-header .breadcrumb > li + li:before {
	color: inherit;
	opacity: 0.5;
	font-family: 'Font Awesome 5 Free';
	content: "\f105";
	padding: 0 7px 0 5px;
	font-weight: 900;
}
 
.page-header .breadcrumb.breadcrumb-valign-mid {
	position: absolute;
	top: 36%;
	right: 20px;
}
 
.page-header h1 {
	display: inline-block;
	line-height: 32px;
	margin: 0;
	padding: 5px 0;
	font-weight: 600;
	position: relative;
	font-size: 25.6px;
	font-size: 1.6rem;
}
 
.page-header .lead {
	padding: 0;
	margin: 0;
	font-size: 1.3em;
	line-height: 1.6;
}
 
.page-header.page-header-color a:hover {
	text-decoration: underline;
}
 
.page-header.page-header-text-light h1, .page-header.page-header-text-light a:not(.btn), .page-header.page-header-text-light span, .page-header.page-header-text-light p {
	color: #FFF;
}
 
.page-header.page-header-text-light li,
.page-header.page-header-text-light li > a {
	color: #a2a2a2;
}
 
.page-header.page-header-text-light.page-header-crumbs-light-2 li,
.page-header.page-header-text-light.page-header-crumbs-light-2 li > a {
	color: #d8d8d8;
}
 
.page-header.parallax > .container {
	position: relative;
	z-index: 3;
}
 
.page-header.page-header-dark {
	background-color: #2E3237;
}
 
/* Parallax */
/* Sections */
.section {
	position: relative;
	padding: 73.846px 0;
	padding: 4.6153846154rem 0;
  /* Section Content Pull Top */
  /* Section Content Pull Top 2 */
  /* Section Content Pull Top 3 */
  /* Section Content Pull Top 4 */
  /* Section Content Pull Top 5 */
  /* Section Over Slider */
  /* Section With Text Overlay */
  /* Responsive */
}
 
.section.section-height-1 {
	padding: 12.307px 0;
	padding: 0.7692307692rem 0;
}
 
.section.section-height-2 {
	padding: 36.923px 0;
	padding: 2.3076923077rem 0;
}
 
.section.section-height-3 {
	padding: 73.846px 0;
	padding: 4.6153846154rem 0;
}
 
.section.section-height-4 {
	padding: 110.769px 0;
	padding: 6.9230769231rem 0;
}
 
.section.section-height-5 {
	padding: 147.692px 0;
	padding: 9.2307692308rem 0;
}
 
.section > .container {
	position: relative;
	z-index: 3;
}
 
.section.section-background {
	background-position: 0 50%;
	background-repeat: repeat;
	z-index: 1;
}
 
.section.section-skew {
	position: relative;
	overflow: hidden;
}
 
.section.section-skew .section-skew-layer {
	position: absolute;
	z-index: 2;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	width: 100%;
	height: 100%;
	-webkit-transform: skew(-15deg, 0deg);
	transform: skew(-15deg, 0deg);
}
 
.section.section-skew .section-skew-layer.skew-layer-from-right, .section.section-skew .section-skew-layer[data-skew-layer-from="right"] {
	left: 105%;
}
 
.section.section-skew > .container {
	position: relative;
	z-index: 3;
}
 
@media (max-width: 991px) {
	.section.section-skew .section-skew-layer.section-skew-layer-mobile-right {
		left: 90% !important;
	}
}
 
.section.section-content-pull-top > .container:not(.no-pull-top) {
	margin-top: -112px;
	margin-top: -7rem;
}
 
.section.section-content-pull-top.pull-top-level-2 > .container:not(.no-pull-top) {
	margin-top: -144px;
	margin-top: -9rem;
}
 
.section.section-content-pull-top.pull-top-level-3 > .container:not(.no-pull-top) {
	margin-top: -176px;
	margin-top: -11rem;
}
 
.section.section-content-pull-top.pull-top-level-4 > .container:not(.no-pull-top) {
	margin-top: -240px;
	margin-top: -15rem;
}
 
.section.section-content-pull-top.pull-top-level-5 > .container:not(.no-pull-top) {
	margin-top: -288px;
	margin-top: -18rem;
}
 
.section.section-content-pull-top-2 {
	padding-bottom: 0;
}
 
.section.section-content-pull-top-2 > .container:not(.no-pull-top) {
	margin-top: -112px;
	margin-top: -7rem;
	background: #FFF;
	border-radius: 7px;
	-webkit-box-shadow: 0px -1px 15px -3px rgba(153, 153, 153, 0.1);
	box-shadow: 0px -1px 15px -3px rgba(153, 153, 153, 0.1);
	padding: 60px 40px;
	z-index: 0;
}
 
@media (min-width: 768px) {
	.section.section-content-pull-top-2 > .container:not(.no-pull-top) {
		max-width: 720px;
	}
}
 
@media (min-width: 992px) {
	.section.section-content-pull-top-2 > .container:not(.no-pull-top) {
		max-width: 1015px;
	}
}
 
@media (min-width: 1200px) {
	.section.section-content-pull-top-2 > .container:not(.no-pull-top) {
		max-width: 1190px;
	}
}
 
.section.section-content-pull-top-2.pull-top-level-2 > .container:not(.no-pull-top) {
	margin-top: -144px;
	margin-top: -9rem;
}
 
.section.section-content-pull-top-2.pull-top-level-3 > .container:not(.no-pull-top) {
	margin-top: -176px;
	margin-top: -11rem;
}
 
.section.section-content-pull-top-3 {
	padding: 36.8px 0;
	padding: 2.3rem 0;
}
 
.section.section-content-pull-top-3 > .container:not(.no-pull-top) {
	margin-top: -112px;
	margin-top: -7rem;
	background: #FFF;
	padding: 40px 40px;
}
 
@media (min-width: 768px) {
	.section.section-content-pull-top-3 > .container:not(.no-pull-top) {
		max-width: 720px;
	}
}
 
@media (min-width: 992px) {
	.section.section-content-pull-top-3 > .container:not(.no-pull-top) {
		max-width: 1015px;
	}
}
 
@media (min-width: 1200px) {
	.section.section-content-pull-top-3 > .container:not(.no-pull-top) {
		max-width: 1190px;
	}
}
 
.section.section-content-pull-top-4 {
	padding: 36.8px 0;
	padding: 2.3rem 0;
}
 
@media (max-width: 575px) {
	.section.section-content-pull-top-4 {
		padding-top: 0;
	}
}
 
.section.section-content-pull-top-4:before {
	content: '';
	position: absolute;
	top: 0;
	left: 50%;
	-webkit-transform: translate3d(-50%, 0, 0);
	transform: translate3d(-50%, 0, 0);
	width: 100%;
	height: 170px;
	background: -webkit-gradient(linear, left bottom, left top, from(#f1f3f7), to(rgba(46, 50, 55, 0.2)));
	background: linear-gradient(to top, #f1f3f7, rgba(46, 50, 55, 0.2));
}
 
@media (min-width: 576px) {
	.section.section-content-pull-top-4:before {
		max-width: 540px;
	}
}
 
@media (min-width: 768px) {
	.section.section-content-pull-top-4:before {
		max-width: 720px;
	}
}
 
@media (min-width: 992px) {
	.section.section-content-pull-top-4:before {
		max-width: 960px;
	}
}
 
@media (min-width: 1200px) {
	.section.section-content-pull-top-4:before {
		max-width: 1440px;
	}
}
 
.section.section-content-pull-top-4 > .container:not(.no-pull-top) {
	margin-top: -240px;
	margin-top: -15rem;
}
 
.section.section-content-pull-top-4 > .container:not(.no-pull-top) > .row {
	padding: 0 30px;
}
 
.section.section-content-pull-top-4 > .container:not(.no-pull-top) > .row:first-child {
	position: relative;
	padding: 30px 30px 0;
}
 
.section.section-content-pull-top-4 > .container:not(.no-pull-top) > .row:first-child:before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	left: 0;
	height: 203px;
	border-radius: 7px 7px 0 0;
	background: #2E3237;
	z-index: -1;
}
 
@media (max-width: 575px) {
	.section.section-content-pull-top-4 > .container:not(.no-pull-top) > .row:first-child:before {
		height: 100%;
		border-radius: 0;
	}
}
 
.section.section-content-pull-top-5 > .container,
.section.section-content-pull-top-5 > .container-fluid {
	margin-top: -48px;
	margin-top: -3rem;
}
 
.section.section-over-slider {
	margin-top: -106px;
	padding: 0;
}
 
.section.section-over-slider.section-over-slider-style-1 > .container {
	position: relative;
	border-top: 1px solid rgba(255, 255, 255, 0.2);
	padding: 24px 0;
	padding: 1.5rem 0;
}
 
.section.section-text-overlay {
	position: relative;
	overflow: hidden;
}
 
.section.section-text-overlay .text-background {
	position: absolute;
	left: 50%;
	bottom: 0;
	width: 100%;
	text-align: center;
	font-size: 13vw;
	line-height: 3.3vw;
	opacity: 0.06;
	z-index: 2;
	-webkit-transform: translateX(-50%);
	transform: translateX(-50%);
}
 
.section.section-text-overlay .text-background.appear-animation {
	opacity: 0;
}
 
.section.section-text-overlay .text-background.text-background-style-2 {
	width: 120%;
	opacity: 0.03;
}
 
.section.section-text-overlay .text-background.text-background-color-1 {
	color: #72b9ff;
}
 
@media (max-width: 991px) {
	.section.section-content-pull-top:not(.pull-top-always) > .container, .section.section-content-pull-top-2:not(.pull-top-always) > .container, .section.section-content-pull-top-3:not(.pull-top-always) > .container {
		margin-top: 0 !important;
		padding: 0 15px;
	}
}
 
@media (max-width: 767px) {
	.section.section-over-slider {
		margin-top: 0;
	}
 
	.section.section-over-slider.section-over-slider-style-1 {
		background: #2E3237;
	}
 
	.section.section-over-slider.section-over-slider-style-1 > .container {
		border-top: 0;
		padding: 1.5rem 15px;
	}
}
 
@media (max-width: 575px) {
	.section.section-content-pull-top-4:not(.pull-top-always) > .container {
		margin-top: 0 !important;
	}
}
 
/* Sidebar */
.sidebar .sidebar-search input {
	padding: 11.2px 35.2px 11.2px 11.2px;
	padding: 0.7rem 2.2rem 0.7rem 0.7rem;
}
 
.sidebar .sidebar-search button {
	position: absolute;
	top: 0;
	right: 0;
	border: 0;
	background-color: transparent;
	height: 100%;
	z-index: 3 !important;
}
 
.sidebar .sidebar-search button i {
	color: #CCC;
}
 
.sidebar .sort-source > div > a,
.sidebar .sort-source > li > a {
	font-family: "Open Sans", sans-serif;
}
 
/* Sliders */
.slider-container {
	background: #1c1f21;
	width: 100%;
	height: 490px;
	overflow: hidden;
	direction: ltr;
}
 
.slider-container.slider-container-full-height {
	height: 100vh;
}
 
.slider-container.slider-container-height-490 {
	height: 490px;
}
 
.slider-container.slider-container-height-550 {
	height: 550px;
}
 
.slider-container.slider-container-height-600 {
	height: 600px;
}
 
.slider-container.slider-container-height-720 {
	height: 720px;
}
 
.slider-container.slider-container-height-800 {
	height: 800px;
}
 
.slider-container.slider-container-height-870 {
	height: 870px;
}
 
/* Slider With Overlay */
.rev_slider li.slide-overlay {
  /* Slider With Overlay Opacity Level */
}
 
.rev_slider li.slide-overlay .slotholder:after {
	width: 100%;
	height: 100%;
	content: '';
	position: absolute;
	left: 0;
	top: 0;
	pointer-events: none;
	opacity: 0.9;
	background: #1c1f21;
	z-index: 2;
}
 
.rev_slider li.slide-overlay.slide-overlay-light .slotholder:after {
	background: #FFF;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-0 .slotholder:after {
	opacity: 0.0;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-1 .slotholder:after {
	opacity: 0.1;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-2 .slotholder:after {
	opacity: 0.2;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-3 .slotholder:after {
	opacity: 0.3;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-4 .slotholder:after {
	opacity: 0.4;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-5 .slotholder:after {
	opacity: 0.5;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-6 .slotholder:after {
	opacity: 0.6;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-7 .slotholder:after {
	opacity: 0.7;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-8 .slotholder:after {
	opacity: 0.8;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-9 .slotholder:after {
	opacity: 0.9;
}
 
.rev_slider li.slide-overlay.slide-overlay-level-10 .slotholder:after {
	opacity: 0.10;
}
 
/* Slider Navigation */
.tp-bullets.bullets-style-1 .tp-bullet {
	width: 7px;
	height: 7px;
	border-radius: 100%;
}
 
/* Slider Arrows */
.tparrows {
  /* Arrows Dark */
}
 
.tparrows.slider-arrows-style-1 {
	background: transparent !important;
}
 
.tparrows.slider-arrows-style-1:hover:before {
	opacity: 0.8;
}
 
.tparrows.slider-arrows-style-2 {
	background: transparent !important;
}
 
.tparrows.slider-arrows-style-2.tp-leftarrow:before, .tparrows.slider-arrows-style-2.tp-rightarrow:before {
	content: '';
	position: absolute;
	top: 50%;
	left: 70%;
	width: 30px;
	height: 30px;
	border-top: 1px solid #FFF;
	border-left: 1px solid #FFF;
	opacity: 0.4;
	-webkit-transform: translate3d(-50%, -50%, 0) rotate(-45deg);
	transform: translate3d(-50%, -50%, 0) rotate(-45deg);
	-webkit-transition: ease opacity 300ms;
	transition: ease opacity 300ms;
}
 
.tparrows.slider-arrows-style-2.tp-leftarrow:after, .tparrows.slider-arrows-style-2.tp-rightarrow:after {
	content: '';
	display: block;
	position: absolute;
	left: 9px;
	top: 50%;
	width: 60px;
	border-top: 1px solid #FFF;
	opacity: 0.4;
	-webkit-transform: translate3d(0, -50%, 0);
	transform: translate3d(0, -50%, 0);
	-webkit-transition: ease width 300ms, ease opacity 300ms;
	transition: ease width 300ms, ease opacity 300ms;
}
 
.tparrows.slider-arrows-style-2.tp-leftarrow:hover:before, .tparrows.slider-arrows-style-2.tp-rightarrow:hover:before {
	opacity: 0.8;
}
 
.tparrows.slider-arrows-style-2.tp-leftarrow:hover:after, .tparrows.slider-arrows-style-2.tp-rightarrow:hover:after {
	width: 90px;
	opacity: 0.8;
}
 
.tparrows.slider-arrows-style-2.tp-rightarrow {
	-webkit-transform: rotate(180deg);
	transform: rotate(180deg);
}
 
.tparrows.slider-arrows-dark:before {
	color: #1c1f21;
}
 
/* Slider Contact Form */
.slider-contact-form-wrapper {
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-align: end;
	-ms-flex-align: end;
	align-items: flex-end;
	-webkit-box-pack: end;
	-ms-flex-pack: end;
	justify-content: flex-end;
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 50%;
	z-index: 99999;
	-webkit-transform: translate3d(-50%, 0, 0);
	transform: translate3d(-50%, 0, 0);
}
 
.slider-contact-form-wrapper .slider-contact-form {
	background: rgba(28, 31, 33, 0.3);
	padding: 80px 80px 256px;
	padding: 5rem 5rem 16rem;
	min-width: 416px;
}
 
.slider-contact-form-wrapper .slider-contact-form > p {
	color: #969696;
}
 
.slider-contact-form-wrapper .slider-contact-form form label {
	color: #CCC;
}
 
@media (max-width: 575px) {
	.slider-contact-form-wrapper {
		-webkit-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
	}
 
	.slider-contact-form-wrapper .slider-contact-form {
		min-width: 256px;
		padding: 3rem;
	}
}
 
@media (max-width: 320px) {
	.slider-contact-form-wrapper .slider-contact-form {
		padding: 1rem;
	}
}
/* Slider Scroll Button */
.slider-scroll-button {
	position: relative;
	width: 57px;
	height: 57px;
	background: #CCC;
	border-radius: 100%;
}
 
.slider-scroll-button:before {
	content: '';
	position: absolute;
	top: 50%;
	left: 49%;
	width: 23px;
	height: 34px;
	border: 1px solid #FFF;
	border-radius: 15px;
	-webkit-transform: translate3d(-50%, -50%, 0);
	transform: translate3d(-50%, -50%, 0);
}
 
.slider-scroll-button:after {
	content: '';
	width: 6px;
	height: 10px;
	border-radius: 10px;
	border: 1px solid #FFF;
	position: absolute;
	top: 19px;
	left: 49%;
	-webkit-transform: translate3d(-50%, 0, 0);
	transform: translate3d(-50%, 0, 0);
	-webkit-animation-name: sliderScrollButton;
	animation-name: sliderScrollButton;
	-webkit-animation-duration: 2s;
	animation-duration: 2s;
	-webkit-animation-iteration-count: infinite;
	animation-iteration-count: infinite;
}
 
/* Custom Layer Styles */
.layer-bg-color-1 {
	background-color: #2b3b4b;
}
 
.layer-border-1 {
	border: 5px solid #55616E;
}
 
.layer-border-width-1 {
	border-width: 5px !important;
}
 
.layer-border-width-2 {
	border-width: 2px !important;
}
 
/* Slider IE Fix */
html.ie .forcefullwidth_wrapper_tp_banner {
	overflow: hidden;
}
 
/* Embed Border */
.rev_slider embed,
.rev_slider iframe,
.rev_slider object,
.rev_slider video {
	border: 0 !important;
}
 
/* Responsive Letter Spacing for Text Layers */
@media (min-width: 576px) {
	.layer-letter-spacing-10 {
		letter-spacing: 10px !important;
	}
}
/* Boxed */
html.boxed .slider-container {
	width: 100% !important;
	left: auto !important;
}
 
/* #Footer */
#footer {
	background: #1C1F21;
	margin-top: 50px;
}
 
#footer h1, #footer h2, #footer h3, #footer h4, #footer h5 {
	color: #FFF;
}
 
#footer h2 {
	font-weight: 500;
}
 
#footer li {
	color: #9e9d9d;
}
 
#footer a.highlight-underlined-light {
	color: #FFF;
	text-decoration: underline;
	font-weight: 100;
}
 
#footer a.highlight-underlined-dark {
	color: #1c1f21;
	text-decoration: underline;
	font-weight: 100;
}
 
#footer.footer-hover-links-light a:not(.btn) {
	-webkit-transition: ease all 300ms;
	transition: ease all 300ms;
}
 
#footer.footer-hover-links-light a:not(.btn):hover {
	color: #FFF;
	border-color: #FFF;
}
 
#footer.footer-text-light h1, #footer.footer-text-light h2, #footer.footer-text-light h3, #footer.footer-text-light h4, #footer.footer-text-light h5, #footer.footer-text-light h6, #footer.footer-text-light p, #footer.footer-text-light a, #footer.footer-text-light span, #footer.footer-text-light li, #footer.footer-text-light strong {
	color: #FFF;
}
 
#footer.footer-colors a:hover:not(.link-underline-light) {
	text-decoration: underline;
}
 
#footer > .container > .row {
	padding-top: 64px;
	padding-top: 4rem;
}
 
#footer .logo img {
	/*max-width: 122px;*/
	/*max-width: 180px;*/
}
 
#footer .footer-top-featured-boxes .featured-box h4 {
	line-height: 1.2;
	font-weight: 500;
	font-size: 1.1em;
	padding-top: 4px;
}
 
#footer .footer-top-featured-boxes .featured-box:nth-child(1) img {
	height: 50px;
}
 
#footer .footer-top-featured-boxes .featured-box:nth-child(2) img {
	height: 45px;
	left: 37px;
}
 
#footer .footer-top-featured-boxes .featured-box:nth-child(3) img {
	height: 44px;
	top: 40px;
	left: 27px;
}
 
#footer.footer-reveal {
	position: fixed;
	bottom: 0;
	left: 0;
	width: 100%;
	z-index: -10;
}
 
#footer .footer-copyright {
	background: #000;
	/* margin-top: 5em; */
	padding: 2em 0;
}
 
#footer .footer-copyright.footer-copyright-border-top {
	border-top: 1px solid #E2E4E8;
}
 
#footer .footer-copyright.footer-copyright-border-top-2 {
	border-top: 1px solid #252525;
}
 
#footer .footer-copyright.footer-copyright-container-border-top {
	position: relative;
}
 
#footer .footer-copyright.footer-copyright-container-border-top:before {
	content: '';
	display: block;
	position: absolute;
	top: 0;
	left: 50%;
	width: 100vw;
	max-width: 1140px;
	border-bottom: 1px solid #E2E4E8;
	-webkit-transform: translate3d(-50%, 0, 0);
	transform: translate3d(-50%, 0, 0);
}
 
#footer .footer-copyright.footer-copyright-landing-bg-color {
	background-color: #202528;
}
 
#footer .footer-copyright p {
	font-size: 0.9em;
}
 
#footer .section-skew .footer-copyright {
	position: relative;
	background: transparent;
	z-index: 2;
}
 
/* Dark Layout */
html.dark {
  /* Helpers */
  /* Header */
  /* Steps */
  /* Sort */
  /* Double Carousel */
  /* Section */
  /* Learn More */
  /* Content Grid */
}
 
html.dark .body {
	background-color: #1c1f21;
}
 
html.dark .border {
	border-color: #2E3237 !important;
}
 
html.dark #header .header-top {
	border-bottom-color: #2E3237;
}
 
html.dark #header .header-body {
	background: #1c1f21;
}
 
html.dark #header .header-container:after {
	border-bottom-color: rgba(46, 50, 55, 0.2);
}
 
@media (min-width: 992px) {
	html.dark #header .header-nav-main-dark nav > ul > li > a {
		color: #777;
	}
}
 
html.dark #header .header-btn-collapse-nav .hamburguer span {
	background: #FFF;
}
 
html.dark #header .header-btn-collapse-nav .close span {
	background: #FFF;
}
 
html.dark .word-rotator.type .word-rotator-words.waiting::after {
	-webkit-animation: 1s word-rotator-pulse-light step-end infinite;
	animation: 1s word-rotator-pulse-light step-end infinite;
}
 
html.dark .steps .item:not(.active) {
	background: #1c1f21 !important;
}
 
html.dark .steps .item .item-title {
	color: #FFF;
}
 
html.dark .steps .item .item-title:after {
	background: #1c1f21;
}
 
html.dark .steps .item.active {
	border-color: #FFF;
}
 
html.dark .steps .item.active:before {
	border: 6px solid #1c1f21;
}
 
html.dark .steps .item.active:after {
	background: #1c1f21;
}
 
html.dark .steps .item.active .item-title {
	color: #1c1f21;
}
 
html.dark .steps .dots .dots-color-dark {
	background: #FFF;
}
 
html.dark .sort-destination-loader:after {
	background: #202326;
}
 
html.dark .double-carousel .owl-carousel .owl-item .card {
	background: #292d31;
}
 
html.dark .double-carousel .owl-carousel .owl-item .card p, html.dark .double-carousel .owl-carousel .owl-item .card strong {
	color: #FFF;
}
 
html.dark section.section {
  /* Section Content Pull Top 2 */
}
 
html.dark section.section:not([class*="bg-light"]) h2, html.dark section.section:not([class*="bg-light"]) h3, html.dark section.section:not([class*="bg-light"]) h4, html.dark section.section:not([class*="bg-light"]) h5, html.dark section.section:not([class*="bg-light"]) h6 {
	color: #FFF;
}
 
html.dark section.section.section-content-pull-top-2 > .container:not(.no-pull-top) {
	background: #202326;
	-webkit-box-shadow: 0px -1px 15px -3px rgba(9, 10, 11, 0.1);
	box-shadow: 0px -1px 15px -3px rgba(9, 10, 11, 0.1);
}
 
html.dark .learn-more {
	color: #FFF;
}
 
html.dark .learn-more:hover {
	color: #CCC;
}
 
html.dark .content-grid .content-grid-item:before {
	border-left: 1px solid #2E3237;
}
 
html.dark .content-grid .content-grid-item:after {
	border-bottom: 1px solid #2E3237;
}
 
html.dark .content-grid.content-grid-dashed .content-grid-item:before {
	border-left: 1px dashed #2E3237;
}
 
html.dark .content-grid.content-grid-dashed .content-grid-item:after {
	border-bottom: 1px dashed #2E3237;
}
 
/* Boxed Layout */
html.boxed body {
	background-color: #E7E9ED;
	background-position: 0 0;
	background-repeat: repeat;
}
 
html.boxed .body {
	position: relative;
	background-color: #FFF;
	margin: 25px auto;
	max-width: 1200px;
	height: auto;
	z-index: 0;
}
 
html.boxed #header .header-body {
	max-width: 1200px;
}
 
html.boxed #header .header-container:after {
	max-width: 1200px;
}
 
html.boxed #header .header-nav-main nav > ul > li.dropdown-mega > .dropdown-menu {
	max-width: 1200px;
	border-radius: 0 !important;
}
 
html.boxed #header .header-nav-main nav > ul > li.dropdown-mega .dropdown-mega-sub-content-block {
	border-radius: 0 !important;
}
 
html.boxed #header .header-nav-main nav > ul > li .dropdown-menu {
	border-radius: 0 !important;
}
 
html.boxed .main {
	overflow: hidden;
}
 
html.boxed section.section.section-text-overlay .text-background {
	font-size: 9vw;
	line-height: 1.3vw;
}
 
@media (min-width: 1200px) {
	html.boxed .double-carousel {
		-ms-flex-preferred-size: 100vw;
		flex-basis: 100vw;
		max-width: none;
		left: 50%;
		-webkit-transform: translate3d(-50%, 0, 0);
		transform: translate3d(-50%, 0, 0);
	}
}
 
/* Responsive */
@media (min-width: 1140px) {
	html.boxed.sticky-header-active #header .header-body {
		width: 100%;
		max-width: 1200px;
	}
}
 
@media (max-width: 991px) {
	html.boxed .body {
		margin: 0 auto;
	}
}
 
html.gap-outside .body {
	margin-top: 25.6px;
	margin-top: 1.6rem;
	margin-bottom: 25.6px;
	margin-bottom: 1.6rem;
}
 
html.gap-outside .main,
html.gap-outside #footer {
	margin-right: 25.6px;
	margin-right: 1.6rem;
	margin-left: 25.6px;
	margin-left: 1.6rem;
}
 
html.gap-outside .slider-container {
	width: 100% !important;
	left: auto !important;
}
 
html.gap-outside #header {
	margin-top: -25.6px;
	margin-top: -1.6rem;
}
 
html.gap-outside #header .header-body {
	left: 0;
	padding-right: 25.6px;
	padding-right: 1.6rem;
	padding-left: 25.6px;
	padding-left: 1.6rem;
}
 
html.gap-outside #header .header-container:after {
	content: none;
}
 
@media (max-width: 991px) {
	html.gap-outside #header .header-nav-main:before {
		width: calc(100vw - 3.2rem);
	}
}
 
.text-color-light {
	color: #FFF !important;
}
 
.text-color-light-2 {
	color: #e2e2e2 !important;
}
 
.text-color-light-3 {
	color: #a2a2a2 !important;
}
 
.text-color-dark {
	color: #1c1f21 !important;
}
 
.text-color-default {
	color: #707070 !important;
}
 
.link-color-dark {
	color: #1c1f21;
}
 
.link-color-light {
	color: #FFF;
}
 
.link-color-light:hover {
	color: #f1f3f7 !important;
}
 
.link-color-light-2 {
	color: #f1f3f7;
}
 
.link-color-light-2:hover, .link-color-light-2:focus, .link-color-light-2:active, .link-color-light-2.active {
	color: #FFF !important;
}
 
.link-color-light-3 {
	color: #a2a2a2;
}
 
.link-color-light-3:hover, .link-color-light-3:focus, .link-color-light-3:active, .link-color-light-3.active {
	color: #FFF !important;
}
 
.bg-light {
	background-color: #FFF !important;
}
 
.bg-light-1 {
	background-color: #fcfdfd !important;
}
 
.bg-light-2 {
	background-color: #fbfbfd !important;
}
 
.bg-light-3 {
	background-color: #f7f9fb !important;
}
 
.bg-light-4 {
	background-color: #f4f6f9 !important;
}
 
.bg-light-5 {
	background-color: #f1f3f7 !important;
}
 
.bg-dark {
	background-color: #1c1f21 !important;
}
 
.bg-dark-1 {
	background-color: #090a0b !important;
}
 
.bg-dark-1 .sort-destination-loader:after {
	background-color: #090a0b !important;
}
 
.bg-dark-2 {
	background-color: #1b1e21 !important;
}
 
.bg-dark-2 .sort-destination-loader:after {
	background-color: #1b1e21 !important;
}
 
.bg-dark-3 {
	background-color: #202326 !important;
}
 
.bg-dark-3 .sort-destination-loader:after {
	background-color: #202326 !important;
}
 
.bg-dark-4 {
	background-color: #292d31 !important;
}
 
.bg-dark-4 .sort-destination-loader:after {
	background-color: #292d31 !important;
}
 
.bg-dark-5 {
	background-color: #2E3237 !important;
}
 
.bg-dark-5 .sort-destination-loader:after {
	background-color: #2E3237 !important;
}
 
.bg-transparent {
	background-color: trasnparent !important;
}
 
.border-light {
	border-color: #FFF !important;
}
 
.border-light-1 {
	border-color: #fcfdfd !important;
}
 
.border-light-2 {
	border-color: #fbfbfd !important;
}
 
.border-light-3 {
	border-color: #f7f9fb !important;
}
 
.border-light-4 {
	border-color: #f4f6f9 !important;
}
 
.border-light-5 {
	border-color: #f1f3f7 !important;
}
 
.border-dark {
	border-color: #1c1f21 !important;
}
 
.border-dark-1 {
	border-color: #090a0b !important;
}
 
.border-dark-2 {
	border-color: #1b1e21 !important;
}
 
.border-dark-3 {
	border-color: #202326 !important;
}
 
.border-dark-4 {
	border-color: #292d31 !important;
}
 
.border-dark-5 {
	border-color: #2E3237 !important;
}
 
.border-grey {
	border-color: #A8AEB0 !important;
}
 
.text-0 {
	font-size: 11.2px !important;
	font-size: .70rem !important;
}
 
.text-1 {
	font-size: 12.8px !important;
	font-size: .80rem !important;
}
 
.text-2 {
	font-size: 14.4px !important;
	font-size: .90rem !important;
}
 
.text-3 {
	font-size: 16px !important;
	font-size: 1rem !important;
}
 
.text-4 {
	font-size: 17.6px !important;
	font-size: 1.1rem !important;
}
 
.text-5 {
	font-size: 24px !important;
	font-size: 1.50rem !important;
}
 
.text-6 {
	font-size: 28.8px !important;
	font-size: 1.80rem !important;
}
 
.text-7 {
	font-size: 32px !important;
	font-size: 2rem !important;
}
 
.text-8 {
	font-size: 36.8px !important;
	font-size: 2.30rem !important;
}
 
.text-9 {
	font-size: 40px !important;
	font-size: 2.50rem !important;
}
 
.text-10 {
	font-size: 44px !important;
	font-size: 2.75rem !important;
}
 
.text-11 {
	font-size: 48px !important;
	font-size: 3rem !important;
}
 
.text-12 {
	font-size: 52px !important;
	font-size: 3.25rem !important;
}
 
.text-13 {
	font-size: 56px !important;
	font-size: 3.50rem !important;
}
 
.text-14 {
	font-size: 60px !important;
	font-size: 3.75rem !important;
}
 
.text-15 {
	font-size: 64px !important;
	font-size: 4rem !important;
}
 
.text-16 {
	font-size: 72px !important;
	font-size: 4.5rem !important;
}
 
.text-17 {
	font-size: 80px !important;
	font-size: 5rem !important;
}
 
.text-18 {
	font-size: 84.8px !important;
	font-size: 5.3rem !important;
}
 
.text-19 {
	font-size: 92.8px !important;
	font-size: 5.8rem !important;
}
 
.text-20 {
	font-size: 104px !important;
	font-size: 6.5rem !important;
}
 
@media (max-width: 1199px) {
	.text-15.resp-text-15 {
		font-size: 3.5rem !important;
	}
}
 
@media (max-width: 991px) {
	.text-5.resp-text-5 {
		font-size: 1.3rem !important;
	}
 
	.text-15.resp-text-15 {
		font-size: 3rem !important;
	}
}
 
@media (max-width: 767px) {
	.text-5.resp-text-5 {
		font-size: 1.2rem !important;
	}
 
	.text-15.resp-text-15 {
		font-size: 2.5rem !important;
	}
}
 
@media (max-width: 575px) {
	.text-5.resp-text-5 {
		font-size: 1.1rem !important;
	}
 
	.text-15.resp-text-15 {
		font-size: 2.3rem !important;
	}
}
 
.line-height-07 {
	line-height: 0.7 !important;
}
 
.line-height-1 {
	line-height: 1 !important;
}
 
.line-height-2 {
	line-height: 1.2 !important;
}
 
.line-height-3 {
	line-height: 1.4 !important;
}
 
.line-height-4 {
	line-height: 1.6 !important;
}
 
.line-height-5 {
	line-height: 1.8 !important;
}
 
@media (max-width: 575px) {
	.mobile-text-1 {
		font-size: 5vw !important;
	}
 
	.mobile-text-2 {
		font-size: 7vw !important;
	}
 
	.mobile-text-3 {
		font-size: 12vw !important;
	}
 
	.mobile-text-4 {
		font-size: 15vw !important;
	}
 
	.mobile-text-5 {
		font-size: 18vw !important;
	}
}
 
.letter-spacing-n1 {
	letter-spacing: -1px;
}
 
.letter-spacing-n6 {
	letter-spacing: -6px;
}
 
.letter-spacing-0 {
	letter-spacing: 0;
}
 
.letter-spacing-5 {
	letter-spacing: 5px;
}
 
.letter-spacing-10 {
	letter-spacing: 10px;
}
 
.width-auto {
	width: auto;
}
 
.pointer-events-none {
	pointer-events: none !important;
}
 
.font-weight-thin {
	font-weight: 100 !important;
}
 
.font-weight-light {
	font-weight: 300 !important;
}
 
.font-weight-normal {
	font-weight: 400 !important;
}
 
.font-weight-semibold {
	font-weight: 600 !important;
}
 
.font-weight-bold {
	font-weight: 700 !important;
}
 
.font-weight-extra-bold {
	font-weight: 800 !important;
}
 
.mt-negative-1 {
	margin-top: -16px;
	margin-top: -1rem;
}
 
.mt-negative-2 {
	margin-top: -24px;
	margin-top: -1.5rem;
}
 
.mt-negative-3 {
	margin-top: -48px;
	margin-top: -3rem;
}
 
.mt-negative-4 {
	margin-top: -72px;
	margin-top: -4.5rem;
}
 
.border-radius-0 {
	border-radius: 0 !important;
}
 
.font-style-italic {
	font-style: italic !important;
}
 
.font-primary {
	font-family: "Montserrat", sans-serif !important;
}
 
.font-secondary {
	font-family: "Open Sans", sans-serif !important;
}
 
.font-tertiary {
	font-family: "Georgia", sans-serif !important;
}
 
.font-quaternary {
	font-family: "Permanent Marker", cursive !important;
}
 
.text-uppercase {
	text-transform: uppercase !important;
}
 
.text-lowercase {
	text-transform: lowercase !important;
}
 
.text-capitalize {
	text-transform: capitalize !important;
}
 
.text-underline {
	text-decoration: underline !important;
}
 
.text-line-trough {
	text-decoration: line-through !important;
}
 
.flex-0-0-auto {
	-webkit-box-flex: 0 !important;
	-ms-flex: 0 0 auto !important;
	flex: 0 0 auto !important;
}
 
.scale-1 {
	-webkit-transform: scale(1.2);
	transform: scale(1.2);
}
 
.scale-2 {
	-webkit-transform: scale(2);
	transform: scale(2);
}
 
.scale-3 {
	-webkit-transform: scale(3);
	transform: scale(3);
}
 
.abs-pos-bottom-right {
	position: absolute;
	bottom: 0;
	right: 0;
}
 
.transform-center-x {
	left: 50%;
	-webkit-transform: translate3d(-50%, 0, 0);
	transform: translate3d(-50%, 0, 0);
}
 
.transform-center-y {
	top: 50%;
	-webkit-transform: translate3d(0, -50%, 0);
	transform: translate3d(0, -50%, 0);
}
 
.transform-center-xy {
	top: 50%;
	left: 50%;
	-webkit-transform: translate3d(-50%, -50%, 0);
	transform: translate3d(-50%, -50%, 0);
}
 
.overflow-hidden {
	overflow: hidden !important;
}
 
.overflow-visible {
	overflow: visible !important;
}
 
.overflow-scroll {
	overflow: scroll !important;
}
 
.va-middle {
	vertical-align: middle;
}
 
.ws-nowrap {
	white-space: nowrap;
}
 
.ws-normal {
	white-space: normal;
}
 
.z-index-0 {
	z-index: 0 !important;
}
 
.z-index-1 {
	z-index: 1 !important;
}
 
.z-index-2 {
	z-index: 2 !important;
}
 
.z-index-3 {
	z-index: 3 !important;
}
 
.z-index-10 {
	z-index: 10 !important;
}
 
.box-shadow-none {
	-webkit-box-shadow: none !important;
	box-shadow: none !important;
}
 
.height-1 {
	height: 18.25vw !important;
}
 
@media (max-width: 991px) {
	.height-1 {
		height: 23vw !important;
	}
}
 
@media (max-width: 767px) {
	.height-1 {
		height: 100vw !important;
	}
}
 
@media (min-width: 576px) and (max-width: 991px) {
	.height-1 {
		min-height: 300px;
	}
}
 
.height-1x2 {
	height: 36.50vw !important;
}
 
@media (max-width: 991px) {
	.height-1x2 {
		height: 46vw !important;
	}
}
 
@media (max-width: 767px) {
	.height-1x2 {
		height: 100vw !important;
	}
}
 
@media (min-width: 576px) and (max-width: 991px) {
	.height-1x2 {
		min-height: 600px;
	}
}
 
.height-2 {
	height: 16.25vw !important;
}
 
@media (max-width: 991px) {
	.height-2 {
		height: 26vw !important;
	}
}
 
@media (max-width: 767px) {
	.height-2 {
		height: 100vw !important;
	}
}
 
.height-2x2 {
	height: 32.50vw !important;
}
 
.height-3 {
	height: 23.25vw !important;
}
 
@media (max-width: 991px) {
	.height-3 {
		height: 33vw !important;
	}
}
 
@media (max-width: 767px) {
	.height-3 {
		height: 100vw !important;
	}
}
 
.height-3x3 {
	height: 46.50vw !important;
}
 
.height-500 {
	height: 500px;
}
 
.height-100vh {
	height: 100vh;
}
 
.min-height-200 {
	min-height: 200px;
}
 
.min-height-236 {
	min-height: 236px;
}
 
.min-height-285 {
	min-height: 285px;
}
 
.min-height-300 {
	min-height: 300px;
}
 
.min-height-370 {
	min-height: 370px;
}
 
.min-height-450 {
	min-height: 450px;
}
 
.min-height-550 {
	min-height: 550px;
}
 
.min-height-680 {
	min-height: 680px;
}
 
.min-height-750 {
	min-height: 750px;
}
 
.min-height-800 {
	min-height: 800px;
}
 
.min-height-900 {
	min-height: 900px;
}
 
.min-height-32vw {
	min-height: 32vw;
}
 
.min-height-100vh {
	min-height: 100vh;
}
 
.min-height-calc-1 {
	min-height: calc(100vh - 118px);
}
 
.max-width-150 {
	max-width: 150px;
}
 
.max-width-200 {
	max-width: 200px;
}
 
.max-width-250 {
	max-width: 250px;
}
 
.max-width-320 {
	max-width: 320px;
}
 
.max-width-400 {
	max-width: 400px;
}
 
.no-vertical-scroll {
	overflow-y: hidden;
}
 
.no-horizontal-scroll {
	overflow-x: hidden;
}
 
.col-1-5, .col-sm-1-5, .col-md-1-5, .col-lg-1-5, .col-xl-1-5, .col-2-5, .col-sm-2-5, .col-md-2-5, .col-lg-2-5, .col-xl-2-5, .col-3-5, .col-sm-3-5, .col-md-3-5, .col-lg-3-5, .col-xl-3-5, .col-4-5, .col-sm-4-5, .col-md-4-5, .col-lg-4-5, .col-xl-4-5 {
	position: relative;
	min-height: 1px;
	width: 100%;
	padding-right: 15px;
	padding-left: 15px;
}
 
.col-1-5 {
	-webkit-box-flex: 0;
	-ms-flex: 0 0 20%;
	flex: 0 0 20%;
	max-width: 20%;
}
 
.col-2-5 {
	-webkit-box-flex: 0;
	-ms-flex: 0 0 40%;
	flex: 0 0 40%;
	max-width: 40%;
}
 
.col-3-5 {
	-webkit-box-flex: 0;
	-ms-flex: 0 0 60%;
	flex: 0 0 60%;
	max-width: 60%;
}
 
.col-4-5 {
	-webkit-box-flex: 0;
	-ms-flex: 0 0 80%;
	flex: 0 0 80%;
	max-width: 80%;
}
 
@media (min-width: 576px) {
	.col-sm-1-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 20%;
		flex: 0 0 20%;
		max-width: 20%;
	}
 
	.col-sm-2-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 40%;
		flex: 0 0 40%;
		max-width: 40%;
	}
 
	.col-sm-3-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 60%;
		flex: 0 0 60%;
		max-width: 60%;
	}
 
	.col-sm-4-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 80%;
		flex: 0 0 80%;
		max-width: 80%;
	}
}
 
@media (min-width: 768px) {
	.col-md-1-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 20%;
		flex: 0 0 20%;
		max-width: 20%;
	}
 
	.col-md-2-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 40%;
		flex: 0 0 40%;
		max-width: 40%;
	}
 
	.col-md-3-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 60%;
		flex: 0 0 60%;
		max-width: 60%;
	}
 
	.col-md-4-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 80%;
		flex: 0 0 80%;
		max-width: 80%;
	}
}
 
@media (min-width: 992px) {
	.col-lg-1-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 20%;
		flex: 0 0 20%;
		max-width: 20%;
	}
 
	.col-lg-2-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 40%;
		flex: 0 0 40%;
		max-width: 40%;
	}
 
	.col-lg-3-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 60%;
		flex: 0 0 60%;
		max-width: 60%;
	}
 
	.col-lg-4-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 80%;
		flex: 0 0 80%;
		max-width: 80%;
	}
}
 
@media (min-width: 1200px) {
	.col-xl-1-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 20%;
		flex: 0 0 20%;
		max-width: 20%;
	}
 
	.col-xl-2-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 40%;
		flex: 0 0 40%;
		max-width: 40%;
	}
 
	.col-xl-3-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 60%;
		flex: 0 0 60%;
		max-width: 60%;
	}
 
	.col-xl-4-5 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 80%;
		flex: 0 0 80%;
		max-width: 80%;
	}
}
 
