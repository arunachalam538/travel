# travel
my first repository on github

html, body{
	font-size: 100%;
	background: #fff;
	font-family: 'Open Sans', sans-serif;
}
body a,.grid_1,plan_1,plan_1.one,plan_1.two,i.icon1, i.icon2, i.icon3, i.icon4, i.icon5, i.icon6 {
	transition:0.5s all;
	-webkit-transition:0.5s all;
	-moz-transition:0.5s all;
	-o-transition:0.5s all;
	-ms-transition:0.5s all;
}
a:hover{
 text-decoration:none;
}
input[type="button"],input[type="submit"],li.parallelogram{
	transition:0.5s all;
	-webkit-transition:0.5s all;
	-moz-transition:0.5s all;
	-o-transition:0.5s all;
	-ms-transition:0.5s all;
}
h1,h2,h3,h4,h5,h6{
	margin:0;
	font-family: 'Roboto Condensed', sans-serif;
}	
p{
	margin:0;
}
ul{
	margin:0;
	padding:0;
}
label{
	margin:0;
}
/*-- top-header --*/
.logo a {
    color: #3F84B1;
    letter-spacing: 1px;
    font-size: 2em;
    font-weight: 400;
    display: block;
    text-decoration: none;
    font-family: 'Oswald', sans-serif;
}
.logo span {
    color:#34ad00;
}
i.fa.fa-home {
    font-size: 24px;
}
.top-header {
    background-color: #3F84B1;
    border-bottom: 0 none;
	height: 36px;
    line-height: 35px;
}
ul.tp-hd-lft{
    float: left;
}
ul.tp-hd-lft li {
    display: inline-block;
}
li.hm,li.prnt {
    margin-right: 12px;
}
ul.tp-hd-lft a {
    font-size: 13px;
    font-weight: 600;
	color:#fff;
}
ul.tp-hd-rgt{
    float:right;
}
ul.tp-hd-rgt li {
    display: inline-block;
	font-size: 13px;
    font-weight: 600;
	color:#fff;
}
ul.tp-hd-rgt  a {
    font-size: 13px;
    font-weight: 600;
	color:#fff;
}
li.ned,li.wrt,li.tol{
    margin-right: 12px;
}
/*-- /top-header --*/
/*-- header --*/
.header {
    background-color: #fff;
    margin: 0;
	padding: 10px 0 8px;
}
.logo a {
    display: block;
}
.logo {
    float: left;
	 margin-right: 60px;
}
.bus {
    float: left;
	padding-top: 17px;
}
.bus a {
    color: #1f8dd6;
    font-weight: 600;
    font-size: 14px;
    letter-spacing: .05em;
	padding:0 15px;
}
.lock {
    float: right;
    margin-top: 7px;
}
.securetxt {
    color: #1f8dd6;
    line-height: 18px;
    margin-top: 0px;
	font-size: 14px;
	font-weight:600;
}
.lock li {
    display: inline-block;
}
i.fa.fa-lock {
    color:#1f8dd6;
    font-size: 2em;
    padding-right: 10px;
}
/*-- /header --*/
/*-- banner --*/
.banner {
    background: url(../images/3.jpg)no-repeat;
    background-size: cover;
    -webkit-background-size: cover;
    -o-background-size: cover;
    -ms-background-size: cover;
    -moz-background-size: cover;
    min-height: 430px;
}
.banner h1 {
    font-size: 50px;
    margin-bottom: 40px;
    padding: 4em 0 0;
    text-align: center;
    color: #ffffff;
}
.bann-info h2 {
    font-size: 26px;
    margin-bottom: 30px;
    color: #34ad00;
    font-weight: 700;
}
.bann-info {
    padding: 4em 0;
}
.bnr-right input[type="text"] {
    width: 95%;
    color: #9E9E9E;
    outline: none;
    font-size: 14px;
    padding: 10px 10px;
    border: 1px solid #9E9E9E;
    -webkit-appearance: none;
    margin-top: 10px;
}
.date {
    background: url(../images/date-icon.png) no-repeat 95.5% 45% #fff;
    cursor: pointer;
}
.bnr-left input[type="text"] {
    width: 95%;
    color: #9E9E9E;
    outline: none;
    font-size: 14px;
    padding: 10px 10px;
    border: 1px solid #9E9E9E;
    -webkit-appearance: none;
    margin-top: 10px;
}
.ban-top .inputLabel,.ban-bottom  .inputLabel {
    display: block;
    font-weight: 600;
    font-size: 14px;
    margin-bottom: 5px;
	color: #191919;
}
.bann-info1 {
    padding: 8em 5em 0em;
    text-align: center;
}
.bnr-right {
    float: left;
	width:50%;
}
.bnr-left {
    float: left;
	width:50%;
}
.ban-bottom{
    margin-top: 30px;
}
button.seabtn {
    padding: 6px 25px!important;
    font-size: 16px;
	 text-indent: 0;
    padding: 6px 20px;
    color: #fff;
    background-color:#34ad00;
    border: 0;
    border-radius: 2px;
    -webkit-transition: all .2s;
    -moz-transition: all .2s;
    transition: all .2s;
    background-repeat: no-repeat;
    background-position: 96% center;
} 
button.seabtn:focus,button.seabtn:hover{
    background-color:#1f8dd6;
    outline: 0;
}
.sear {
    margin-top: 30px;
}
.bann-info1 h3 {
    font-size: 2.1em;
    font-weight: 700;
    color: #34ad00;
    text-align: center;
    margin-top: 25px;
}
i.fa.fa-columns {
    font-size: 9em;
    color: #1f8dd6;
}
/*-- /banner --*/
/*-- rupes --*/
.rup-left {
    float: left;
    width: 24%;
}
.rup-rgt {
    float: left;
    width: 76%;
}
.rupes {
    padding: 5em 0;
	border-top: 1px solid rgba(236, 236, 236, 0.9);
    border-bottom: 1px solid rgba(236, 236, 236, 0.9);
}
i.fa.fa-usd{
    font-size: 5em;
    color: #1f8dd6;
}
i.fa.fa-h-square{
    font-size: 5em;
    color: #1f8dd6;
}
i.fa.fa-mobile  {
    font-size:5em;
    color: #1f8dd6;
}
.rupes h3 {
    font-size: 20px;
    color: #34ad00;
	 font-weight: 700;
}
.rupes h4 {
    font-size: 18px;
    margin: 8px 0;
    font-weight: 700;
}
.rupes h4 a{
    color: #000000;
}
.rupes h4 a:hover{
    color:#34ad00;
}
.rupes p{
    font-size: 15px;
    line-height: 1.6em;
    font-weight: 300;
	color:#999;
}
/*-- /rupes --*/
/*-- track --*/
a.learn{
    padding: 6px 25px!important;
    font-size: 16px;
    text-indent: 0;
    padding: 6px 20px;
    color: #fff;
    background-color: #34ad00;
    border: 0;
    border-radius: 2px;
    -webkit-transition: all .2s;
    -moz-transition: all .2s;
    transition: all .2s;
    display: inline-block;
}
a.learn:focus,a.learn:hover {
    background-color: #1f8dd6;
    outline: 0;
}
.track {
    padding: 5em 0;
	border-top: 1px solid rgba(236, 236, 236, 0.9);
    border-bottom: 1px solid rgba(236, 236, 236, 0.9);
}
.track h3 {
    font-size: 2em;
    font-weight: 700;
    color: #34AD00;
}
.track p {
    font-size: 1.2em;
    line-height: 1.8em;
    width: 55%;
    margin: 1.5em 0;
    color: #999;
}
.track-right {
    text-align: center;
}
i.fa.fa-map-marker {
    font-size: 3em;
    color: #34ad00;
}
.rup-left a {
    display: inline-block;
}
.track-right a {
    display: inline-block;
}
/*-- /track --*/
/*-- routes --*/
.routes {
    padding: 5em 0;
}
.rou-left {
    float: left;
    width: 23%;
}
.rou-rgt {
    float: left;
    width: 70%;
}
i.fa.fa-truck,i.fa.fa-user,i.fa.fa-ticket {
    font-size: 4em;
	color:#1f8dd6;
}
.routes h3 {
    font-size: 2em;
    font-weight: 700;
    color: #34ad00;
}
.routes p {
    font-size: 1.2em;
    color: #999;
    line-height: 1.8em;
}
/*-- /routes --*/
/*-- holiday --*/
.holiday {
    padding: 5em 0;
}
.holiday h3 {
    font-size: 2em;
    font-weight: 700;
    color: #34ad00;
}
.holiday p {
    font-size: 1.2em;
    line-height: 1.8em;
    margin: 1em 0;
    color: #999;
}
/*-- /holiday --*/
/*-- footer --*/
.footer-left li {
    display: inline-block;
    float: left;
    width: 33.33%;
    line-height: 1.8em;
}
.footer-left li a {
    font-size: 14px;
    color:#847777;
    display: inline-block;
}
.footer-left li a:hover{
    color:#1f8dd6;
}
.footer-top h3 {
    font-size: 1.7em;
    color: #34ad00;
    margin-bottom: 1em;
    font-weight: 700;
}
.footer-top {
    padding: 3em 0;
    background: #e8e8e8;
}
.footer-btm li {
    display: inline-block;
    margin: 0 10px;
	font-size: 14px;
    color: #fff;
}
.footer-btm li a {
    font-size: 15px;
    color: #fff;
    display: inline-block;
    padding: 5px 8px;
}
.footer-btm li a:hover{
    color:#4CFF00;
}
.footer-btm {
    background:#4CB320;
    padding: 0.5em 0;
	text-align:center;
}
.copy-right p {
    color:#fff;
    font-size:14px;
    line-height: 1.8em;
}
.copy-right p a {
    color: #fff;
}
.copy-right p a:hover {
    color:#000000;
}
.copy-right {
    background:#34ad00;
    text-align: center;
    padding: 0.5em 0;
}
/*-- /footer --*/
/*-- bus --*/
.banner-1 {
    background: url(../images/3.jpg)no-repeat;
    background-size: cover;
    -webkit-background-size: cover;
    -o-background-size: cover;
    -ms-background-size: cover;
    -moz-background-size: cover;
    min-height:200px;
}
.banner-1 h1 {
    font-size: 50px;
    margin-bottom: 40px;
    padding: 1.5em 0 0;
    text-align: center;
    color: #ffffff;
}
.bus-tp P {
    float: left;
    font-size: 14px;
    color: #fff;
    line-height: 1.8em;
}
.bus-tp h2 {
    float: right;
    font-size: 24px;
    color: #fff;
}
.bus-tp {
    padding: 0.5em;
    background: #34ad00;
}
.bus-btm li {
    float: left;
    display: inline-block;
}
li.trav {
    width: 34%;
}
li.dept {
    width: 13%;
}
li.arriv {
    width: 13%;
}
li.seat {
    width: 20%;
}
li.fare {
    width: 20%;
}
.bus-btm li a {
    color: #999;
    font-size: 15px;
	display: inline-block;
}
.bus-btm {
    padding: 0.5em 0;
    border-bottom: 1px solid #E4E4E4;
}
.bus-midd li {
    display: inline-block;
    float: left;
}
.bus-ic {
    float: left;
    width: 7%;
    margin-top: 4px;
}
.bus-txt {
    float: right;
    width: 91%;
}
.bus-ic1 {
    float: left;
    width: 18%;
}
.bus-ic3 {
    float: left;
    width: 13%;
    margin-top: 4px;
}
.bus-txt1 {
    float: right;
    width: 82%;
}
.bus-txt3 {
    float: right;
    width: 87%;
}
.bus-midd h4 {
    font-size: 19px;
    font-weight: 700;
    color: #000;
    line-height: inherit;
    padding: 0!important;
}
.bus-midd h4 a{
    font-size: 19px;
    font-weight: 700;
    color: #000;
}
.bus-midd p {
    color: #9A9A9A;
    font-size: 14px;
}
.bus-midd h5 {
    font-weight: 700;
    font-size: 20px;
    color: #34ad00;
}
a.view {
    padding: 6px 18px;
    font-weight: 700;
    color: #fff;
    background-color: #34ad00;
    border: 0;
    font-size: 13px;
    border-radius: 2px;
    -webkit-transition: all .2s;
    -moz-transition: all .2s;
    transition: all .2s;
    margin-top: 20px;
    display: inline-block;
}
i.fa.fa-clock-o {
    font-size: 1.5em;
    color: #9A9A9A;
    margin-top: 4px;
}
ul.first {
    padding: 2em 0;
}
ul.first {
    padding: 2em 0 1em;
    border-bottom: 1px solid #E4E4E4;
}
/*-- /bus --*/
/*-- about --*/
.about-top {
    text-align: center;
}
.about {
    padding: 5em 0;
}
.about h2 {
    font-size: 2.5em;
    color: #34ad00;
    margin-bottom: 1em;
    font-weight: 700;
}
.about h3 {
    font-size: 2.2em;
    color: #34ad00;
    margin-bottom: 1em;
    font-weight: 700;
}
.about p {
    font-size: 1em;
    line-height: 1.8em;
    margin: 0 0 1em;
    color: #999;
    font-weight: 400;
}
.about-mid {
    margin: 4em 0;
}
.about h5 {
    font-size: 1.1em;
    text-align:right;
    color: #1f8dd6;
}
.about h6 {
    font-size: 1em;
    color: #34ad00;
    text-align:right;
}
.ab-tp {
    margin-bottom: 2em;
}
.ab-rt ul li a {
    font-size: 1em;
    color: #999;
    background: url(../images/dot.png)no-repeat 0px 2px;
    padding: 0px 0px 0px 30px;
}
.ab-rt ul li{
    margin: 0em 0em 0.5em 0em;
}
.ab-rt ul li a:hover{
  color: #34ad00;
  text-decoration:none;
}
.ab-rt li{
    display: block;
}
.ab-lt {
    padding-right: 50px;
}
/*-- /about --*/
/*--travel --*/
.travel h3 {
    font-size: 1.7em;
    font-weight: 700;
    color: #34ad00;
}
.travel p {
    font-size: 15px;
    color: #999;
    line-height: 1.8em;
    margin: 1em 0;
}
.tra-top li {
    display: inline-block;
    float: left;
}
ul.rout {
    background: #1f8dd6;
    padding: 0.8em;
    color: #fff;
}
li.rou {
    width:30%;
}
li.ser {
    width: 20%;
}
li.fir{
    width: 15%;
}
li.las {
    width: 15%;
}
li.dat {
    width: 20%;
}
.tra-top h4 {
    font-size: 19px;
    margin-bottom: 10px;
    font-weight: 700;
    color: #34ad00;
}
ul.rou-secnd p {
    margin: 0;
}
ul.rou-secnd {
    padding: 1.5em 0;
    border-bottom: 1px solid #E4E4E4;
}
a.det {
    padding: 6px 18px;
    font-weight: 700;
    color: #fff;
    background-color: #34ad00;
    border: 0;
    font-size: 13px;
    border-radius: 2px;
    -webkit-transition: all .2s;
    -moz-transition: all .2s;
    transition: all .2s;
    display: inline-block;
}
.tra-top h6 a {
    color: #34ad00;
    font-size: 16px;
    font-weight: 700;
    text-decoration: underline;
}
.tra-top {
    margin-top: 3em;
}
/*-- /travel --*/
/*-- offers-1 --*/
.offers-1-left {
    text-align: center;
}
.offers-1 p {
    color: #444;
    font-size: 15px;
    line-height: 1.8em;
    margin-bottom: 5px;
}
.offers-1 h3 {
    font-size: 21px;
    color:#34AD00;
    font-weight: 700;
}
.offers-1 h6 {
    color: #62717d;
    margin: 10px 0;
    line-height: 1.8em;
    font-size: 16px;
}
a.off{
    border-radius: 5px;
    display: inline-block;
    color: #fff;
    font-weight: 400;
    font-size: 14px;
    padding: 8px 18px;
    text-decoration: none;
	background:#34ad00;
}
a.off:hover{
	background:#1f8dd6;
}
.offers-1-left {
    padding: 2em;
    border: 1px solid #e4e4e4;
    margin-bottom: 2em;
}
.offers-1 {
    padding: 5em 0;
}
i.fa.fa-gift{
	font-size: 5em;
    color: #1f8dd6;
}
/*-- /offers-1 --*/
/*-- hotels --*/
.banner-2 {
    background: url(../images/6.jpg)no-repeat;
    background-size: cover;
    -webkit-background-size: cover;
    -o-background-size: cover;
    -ms-background-size: cover;
    -moz-background-size: cover;
    min-height: 430px;
}
.banner-3 {
    background: url(../images/6.jpg)no-repeat;
    background-size: cover;
    -webkit-background-size: cover;
    -o-background-size: cover;
    -ms-background-size: cover;
    -moz-background-size: cover;
    min-height:200px;
}
.banner-2 h1 {
    font-size: 50px;
    margin-bottom: 40px;
    padding: 2em 0 0;
    text-align: center;
    color: #fff;
}
.banner-3 h1 {
    font-size: 50px;
    margin-bottom: 40px;
    padding: 1.5em 0 0;
    text-align: center;
    color: #fff;
}
.hotes-left {
    text-align: center;
}
.room-map iframe {
    min-height: 450px;
}
.hotels-top h3{
    font-size: 26px;
    margin-bottom: 50px;
    color: #34ad00;
    font-weight: 700;
	text-align:center;
}
.hotels-top {
    padding: 4em 0;
}
.hotl-top {
    margin-top: 2em;
}
.view1 {
	width: 100%;
   height: 100%;
   float: left;
   overflow: hidden;
   position: relative;
   text-align: center;
   -webkit-box-shadow: 1px 1px 2px #e6e6e6;
   -moz-box-shadow: 1px 1px 2px #e6e6e6;
   box-shadow: 1px 1px 2px #e6e6e6;
   cursor: default;
   background: #fff url(../images/bgimg.jpg) no-repeat center center;
}
.view1 .mask,.view1 .content {
	width: 100%;
   height: 100%;
   position: absolute;
   overflow: hidden;
   top: 0;
   left: 0;
   cursor:pointer;
}
.view1 img {
   display: block;
   position: relative;
}
.view1 h2 {
   text-transform: uppercase;
   color: #fff;
   text-align: center;
   position: relative;
   font-size: 17px;
   padding: 10px;
   background: rgba(0, 0, 0, 0.8);
   margin: 20px 0 0 0;
}
.view1-sixth img {
   -webkit-transition: all 0.4s ease-in-out 0.5s;
   -moz-transition: all 0.4s ease-in-out 0.5s;
   -o-transition: all 0.4s ease-in-out 0.5s;
   -ms-transition: all 0.4s ease-in-out 0.5s;
   transition: all 0.4s ease-in-out 0.5s;
}
.view1-sixth .mask {
   background-color:rgba(63, 132, 177, 0.72);
   -ms-filter: "progid: DXImageTransform.Microsoft.Alpha(Opacity=0)";
   filter: alpha(opacity=0);
   opacity: 0;
   -webkit-transition: all 0.3s ease-in 0.4s;
   -moz-transition: all 0.3s ease-in 0.4s;
   -o-transition: all 0.3s ease-in 0.4s;
   -ms-transition: all 0.3s ease-in 0.4s;
   transition: all 0.3s ease-in 0.4s;
}
.view1-sixth h2 {
   -ms-filter: "progid: DXImageTransform.Microsoft.Alpha(Opacity=0)";
   filter: alpha(opacity=0);
   opacity: 0;
   background: transparent;
   margin: 130px 40px 0px 40px;
   -webkit-transform: scale(10);
   -moz-transform: scale(10);
   -o-transform: scale(10);
   -ms-transform: scale(10);
   transform: scale(10);
   -webkit-transition: all 0.3s ease-in-out 0.1s;
   -moz-transition: all 0.3s ease-in-out 0.1s;
   -o-transition: all 0.3s ease-in-out 0.1s;
   -ms-transition: all 0.3s ease-in-out 0.1s;
   transition: all 0.3s ease-in-out 0.1s;
}
.view1-sixth:hover .mask {
   -ms-filter: "progid: DXImageTransform.Microsoft.Alpha(Opacity=100)";
   filter: alpha(opacity=100);
   opacity: 1;
   -webkit-transition-delay: 0s;
   -moz-transition-delay: 0s;
   -o-transition-delay: 0s;
   -ms-transition-delay: 0s;
   transition-delay: 0s;
}
.view1-sixth:hover img {
   -webkit-transition-delay: 0s;
   -moz-transition-delay: 0s;
   -o-transition-delay: 0s;
   -ms-transition-delay: 0s;
   transition-delay: 0s;
}
.view1-sixth:hover h2 {
   -ms-filter: "progid: DXImageTransform.Microsoft.Alpha(Opacity=100)";
   filter: alpha(opacity=100);
   opacity: 1;
   -webkit-transform: scale(1);
   -moz-transform: scale(1);
   -o-transform: scale(1);
   -ms-transform: scale(1);
   transform: scale(1);
   -webkit-transition-delay: 0.1s;
   -moz-transition-delay: 0.1s;
   -o-transition-delay: 0.1s;
   -ms-transition-delay: 0.1s;
   transition-delay: 0.1s;
}
/*-- /hotels --*/
.travel {
    padding: 3em 0 5em;
}
/*-- terms --*/
.terms h3 {
    font-size: 1.5em;
    color: #34ad00;
    font-weight: 700;
}
.terms h6 {
    font-size: 1.2em;
    color: #1f8dd6;
    font-weight: 700;
    margin: 1em 0;
}
.terms p {
    font-size: 15px;
    line-height: 1.6em;
    font-weight: 300;
    color: #999;
    margin: 1em 0;
}
.terms {
    padding: 5em 0;
}
.terms span {
    color: #000;
    font-weight: 700;
    font-size: 1.3em;
}
.terms-bottom {
    margin-top: 3em;
}
/*-- /terms --*/
/*-- agent --*/
.agent-left input[type="text"] {
    width: 80%;
    color: #9E9E9E;
    outline: none;
    font-size: 14px;
    padding: 10px 10px;
    border: 1px solid #464646;
    -webkit-appearance: none;
    margin-top: 10px;
}
.agent-left {
    text-align: center;
}
.agent {
    padding: 5em 0;
}
.ag-bt {
    margin-bottom: 2em;
}
a.regist {
    padding: 10px 32px!important;
    color: #fff;
    background-color: #34ad00;
    border: 0;
    border-radius: 2px;
    -webkit-transition: all .2s;
    -moz-transition: all .2s;
    transition: all .2s;
    font-size: 16px;
    text-decoration: none;
    display: inline-block;
}
a.regist:hover{
	background-color:#1f8dd6;
}
.agent-left textarea {
    width: 80%;
    margin: 22px 0;
    resize: none;
    height: 150px;
	 outline: none;
    padding: 10px 10px;
    border: 1px solid #464646;
    background: none;
    font-size: 14px;
    color: #000;
}
.agent-left input[type="submit"] {
    outline: none;
    background: #34ad00;
    transition: 0.5s all;
    -webkit-transition: 0.5s all;
    -moz-transition: 0.5s all;
    -o-transition: 0.5s all;
    -ms-transition: 0.5s all;
    color: #fff;
    font-weight: 600;
    padding: 6px 18px;
    font-size: 15px;
    border: none;
    border-radius: 2px;
}
.agent-left input[type="submit"]:hover{
    background: #1f8dd6;
}
.sub {
    text-align: right;
    margin-right: 3em;
}
select {
    padding: 4px 5px!important;
    width: 80%;
    color: #9E9E9E;
    margin-top: 18px;
    border: 1px solid #464646;
    padding: 5px 10px;
    vertical-align: middle;
}
.agent-right {
    padding-left: 3.4em;
}
.agent h3 {
    font-size: 1.5em;
    color: #34ad00;
    font-weight: 700;
    margin-top: 1em;
}
.agent p {
    font-size: 15px;
    margin: 1em 0;
    color: #999;
    line-height: 1.6em;
}
/*-- /agent --*/
/*-- contact --*/
.contact {
    padding: 5em 0;
}
.contact h3 {
    font-size: 2em;
    color: #34ad00;
    margin-bottom: 1.5em;
    font-weight: 700;
}
.contact h4 {
    font-size: 1.4em;
    color: #1f8dd6;
    margin-bottom:0.6em;
    font-weight: 700;
}
.contact-left li {
    display: block;
    line-height: 1.7em;
    font-size: 13px;
    color: #999;
}
.con-top {
    margin-top: 2em;
}
/*-- /contact --*/
/*-- details --*/
.details-middle li {
    display: inline-block;
    float: left;
    margin: 0 12px 0 0px;
    font-size: 15px;
    color: #999;
}
span.glyphicon.glyphicon-eye-open, span.glyphicon.glyphicon-thumbs-up {
    color: #1f8dd6;
    font-size: 1.1em;
    padding-right: 6px;
}
.details-middle p{
    font-size: 15px;
    color: #999;
    line-height: 1.7em;
    margin: 0.5em 0;
}
.details-top h5 {
    font-size: 1.4em;
    font-weight: 700;
    color: #1f8dd6;
}
.details-top {
    margin-top: 2em;
    box-shadow: 0px 0px 5px -1px rgba(0, 0, 0, 0.37);
}
.details-left {
    padding-left: 0;
}
.details-right {
    padding: 2em 0;
    text-align: center;
}
.details-middle h3 a {
    color: #34ad00;
    text-decoration: none;
}
.details-middle {
    padding: 1.5em 1em;
}
.details-middle h3 {
    font-size: 1.5em;
    font-weight: 700;
}
.details {
    padding: 5em 0;
}
/*-- /details --*/
/*-- rooms --*/
.rooms-top {
    background: url(../images/7.jpg)no-repeat;
    background-size: cover;
    -webkit-background-size: cover;
    -o-background-size: cover;
    -ms-background-size: cover;
    -moz-background-size: cover;
    min-height: 390px;
    padding: 18em 0 0;
}
.rom-info {
    background: rgba(63, 132, 177, 0.79);
    padding: 1em 2em;
}
.rom-info h3 {
    font-size: 1.8em;
    color: #fff;
    font-weight: 700;
}
.rom-info p {
    font-size: 15px;
    margin-top: 0.5em;
    color: #fff;
    line-height: 1.7em;
}
.rt-left {
    float: left;
}
.rt-right {
    float: right;
}
.rom-info h5 {
    font-size: 1.2em;
    font-weight: 700;
    color: #fff;
}
.rom-btm {
    margin-top: 2em;
	box-shadow: 0px 0px 5px -1px rgba(0, 0, 0, 0.37);
}
.room-bottom h3 {
    font-size: 1.8em;
    font-weight: 700;
    color: #34ad00;
}
.room-bottom {
    padding: 2em 0;
}
.rom-btm h4 {
    font-size: 1.5em;
    font-weight: 700;
    color: #34ad00;
}
.rom-btm p {
    font-size: 15px;
    color: #999;
}
.rom-btm h6 {
    font-size: 1em;
    font-weight: 700;
    margin: 0.5em 0;
}
.room-right {
    text-align: right;
    padding: 3em 2em;
}
.room-midle {
    padding: 1em;
}
.rom-btm h5 {
    font-size: 1.2em;
    font-weight: 700;
    color: #999;
}
/*-- /rooms --*/

/*-- sign up --*/
.single-bottom input[type="checkbox"] {
  display: none;
}
.single-bottom input[type="checkbox"]+label {
    position: relative;
    padding-left: 31px;
    border: none;
    outline: none;
    font-size: 14px;
    color: #A9A8A8;
	font-weight:normal;
}
.single-bottom input[type="checkbox"]+label span:first-child {
	width: 14px;
    height: 14px;
    display: inline-block;
    border: 2px solid #4CB320;
    position: absolute;
    left: 0;
    top: 4px;
}
.single-bottom input[type="checkbox"]:checked+label span:first-child:before {
  content: "";
  background:url(../images/mark1.png)no-repeat;
  position: absolute;
  left: -1px;
  top: -1px;
  font-size: 10px;
  width:16px;
  height:16px;
}
.modal-info {
    width: 100%;
}
/*-- //Sign up --*/
.modal-header {
    border-bottom: 1px solid #fff !important;
}
/*-- singlepage --*/
.room-map {
    margin: 4em 0;
}
h4.sing {
    font-size: 1.5em;
    font-weight: 700;
    margin-bottom: 1em;
    color: #34ad00;
}
.hotel-police p {
    font-size: 15px;
    line-height: 1.8em;
    color: #999;
}
.hotel-police {
    margin-bottom: 3em;
}
.hotel-amenit li {
    display: inline-block;
    float: left;
    width: 33.33%;
    line-height: 1.8em;
    color: #999;
}
.hotel-amenit {
    margin-bottom: 3em;
}
/*-- //singlepage --*/
ul.off-mo {
    padding: 2em 1em;
}
ul.off-mo li {
    display: block;
    line-height: 1.8em;
    font-size: 14px;
    color: #999;
    margin-bottom: 1em;
}
ul.off-mo span {
    color:#34ad00;
    font-weight: 700;
    font-size: 1.3em;
}
/*-- selectroom --*/
.selectroom {
    padding: 5em 0 3em;
}
.selectroom_top {
    padding: 2em;
    box-shadow: 0px 0px 10px -4px #000;
    margin-bottom: 2em;
}
.selectroom_right li {
    display: inline-block;
    float: left;
    width: 21%;
}
.grand {
    text-align: right;
}
.selectroom_right h2 {
	font-size: 1.7em;
    color: #999;
    font-weight: 600;
    margin: 0;
}	
.selectroom_right h3 {
    font-size: 1.7em;
    font-weight: 600;
	color:#34ad00;
}
p.dow {
    font-size: 15px;
    color: #999;
    font-weight: 300;
    line-height: 1.8em;
	margin-bottom:1em;
}
.selectroom_right p {
    font-size: 15px;
    line-height: 1.6em;
    font-weight: 300;
    color: #999;
}
.selectroom_right ul {
    margin-top: 1em;
}
.selectroom_right h6 {
    font-size: 1em;
    color: #999;
    line-height: 1.8em;
}
.selectroom_right h4 {
    font-size: 1.2em;
    color: #34ad00;
    line-height: 1.8em;
	font-weight:600;
}
.selectroom_right span {
    font-weight: 700;
}
.selectroom-info li {
    display: inline-block;
    float: left;
}
li.nam {
    width: 22%;
}
li.mr
{
    width: 12%;
}
li.mr select {
    padding: 4px 5px!important;
    width: 72%;
    color: #9E9E9E;
    margin-top: 18px;
	border:none;
    border-bottom:1px solid rgba(0,0,0,.12);
    padding: 5px 10px;
    vertical-align: middle;
}
.selectroom input[type="text"] {
    width: 92%;
    color: #9E9E9E;
    outline: none;
    font-size: 14px;
    padding: 10px 0px;
    border: none;
    border-bottom:1px solid rgba(0,0,0,.12);
    -webkit-appearance: none;
    margin-top: 10px;
}
.selectroom-info ul {
    margin-top: 3em;
}
li.spe {
    width: 100%;
    margin-top: 3em;
}
li.spe  input[type="text"] {
    width: 100%;
}
/*-- write --*/
.writ input[type="text"] {
    width: 92%;
    color: rgba(158, 158, 158, 0.69);
    outline: none;
    font-size: 16px;
    padding: 10px 0px;
    border: none;
    border-bottom: 1px solid rgba(0,0,0,.12);
    -webkit-appearance: none;
}
li.na-me select {
    padding: 8px 0px!important;
    width: 92%;
    color: rgba(158, 158, 158, 0.69);
    margin-top: 0px;
	border:none;
	font-size: 18px;
    border-bottom:1px solid rgba(0,0,0,.12);
    vertical-align: middle;
	    outline: none;
}
.writ li {
    display: inline-block;
    float: left;
	margin-top: 1em;
}
li.na-me {
    width: 50%;
}
li.descrip {
    width: 100%;
}
.writ h4 {
    font-size: 1.5em;
    text-align: center;
    margin-bottom: 0.5em;
    padding: 0 0 0.5em 0;
    color: #34AD00;
    font-weight: 600;
}
.writ {
    padding: 0 2em 3em;
}
.sub-bn {
    text-align: right;
	margin-top:2em;
}
button.subbtn {
    padding: 6px 25px!important;
    font-size: 16px;
    text-indent: 0;
    padding: 6px 20px;
    color: #fff;
    background-color: #34ad00;
    border: 0;
    border-radius: 2px;
    -webkit-transition: all .2s;
    -moz-transition: all .2s;
    transition: all .2s;
    background-repeat: no-repeat;
    background-position: 96% center;
}
button.subbtn:focus, button.subbtn:hover {
    background-color: #1f8dd6;
    outline: 0;
}
/*-- /write --*/
.tracking {
    padding: 5em 0;
}
.tracking-right img {
    display: inline-block;
}
.tracking-right {
    text-align: center;
    padding: 2em;
}
.tracking-top,.tracking-bottom {
    margin-bottom: 3em;
    background: #eeeeee;
    padding: 3em 6em;
}
.tracking p {
    font-size: 1em;
    color: #999;
    line-height: 1.8em;
    font-weight: 300;
}
.tracking h3 {
    font-size: 1.7em;
    font-weight: 600;
    color: #34ad00;
    margin-bottom: 1em;
}
.tracking-midle {
    margin-bottom: 3em;
}
.similar_hotel {
    margin-bottom: 5em;
}

/*-- login --*/
.login-right{
	float:right;
	width:51%;
}
.login-right h3{
    color: #4CB320;
    font-weight: normal;
    font-size: 17px;

}
.login-left {
    float: left;
    width: 42%;
}
.login-right input[type="text"] ,.login-right input[type="password"] {
    width: 100%;
    padding: 10px;
    font-weight: normal;
    background: none;
    border: 1px solid #E6E4E4;
    color: #D2D1D1;
    outline: none;
    font-size: 14px;
    margin-top: 20px;
}
.login-right h4{
	color:#48cfc1;
	font-size:12px;
	margin:20px 0;
}
.login-right h4 a{
	color:#4CB320;
	text-decoration:none;
}
.login-right h4 a:hover{
	color:#A9A8A8;
}
.login-grids p a {
	color:#4CB320;
}
.login-right input[type="submit"] {
  background:#4CB320;
  color: #fff;
  font-size: 20px;
  border: none;
  width: 100%;
  outline: none;
  -webkit-appearance:none;
  padding: 10px 15px;
  transition: 0.5s all;
  -webkit-transition: 0.5s all;
  -moz-transition: 0.5s all;
  -o-transition: 0.5s all;
 margin-top:20px;
}
.login-right input[type="submit"]:hover {
	background:#3F84B1;
}
.login-grids p {
    font-size: 12px;
    margin-top: 25px;
	color:#A9A8A8;
}
.login-grids p span{
	color:#48cfc1;	
}
.login-left ul li{
	list-style-type:none;
	display:block;
    margin: 22px 0;
    font-size: 16px;
}
.login-left ul li a {
    padding: 9px 12px;
    display: block;
    text-align: left;
    color: #fff;
    text-decoration: none;
}
.login-left ul li a:hover{
	opacity:.7;
}
.login-left ul li a.fb{
	background:#3b5998;
}
.login-left ul li a.goog{
	background:#dc4e41;
}
.login-left ul li a.linkin{
	background:#00a0dc;
}
.login-left ul li a.fb i{
    background: url(../images/social.png) no-repeat -45px -1px;
    width: 24px;
    height: 23px;
    display: inline-block;
    vertical-align: text-bottom;
}
.login-left ul li a.goog i{
    background: url(../images/social.png) no-repeat -84px 0px;
    width: 26px;
    height: 23px;
    display: inline-block;
    vertical-align: text-bottom;
}
.login-left ul li a.linkin i{
    background: url(../images/social.png) no-repeat -3px 0px;
    width: 25px;
    height: 23px;
    display: inline-block;
    vertical-align: text-bottom;
}
/*-- //login --*/
.privacy h3 {
    color: #34AD00;
    font-size: 1.7em;
    font-weight: 700;
    margin-bottom: 1em;
}
.privacy {
    padding: 5em 0;
}
.privacy p {
    font-size: 1em;
    line-height: 1.8em;
    color: #999;
    margin: 1em 0;
}
.privacy h4 {
    font-size: 1.3em;
    color: #34AD00;
    font-weight: 400;
    margin: 1em 0;
}
/*-- faq --*/
.faq {
    padding: 5em 0;
}
.faq h2 {
    font-size: 2em;
    font-weight: 700;
    color:#34ad00;
    line-height: 1.8em;
}
.faq h3 {
    font-size: 1.7em;
    color:#34ad00;
    font-weight: 600;
    margin-bottom: 0.5em;
    line-height: 1.8em;
}
.faq p {
    font-size: 1em;
    line-height: 1.8em;
    color: #999;
    margin: 1em 0;
}
.faq li {
    display: block;
    color: #999;
    font-size: 1em;
    margin: 1em 0;
}
/*-- //faq --*/
/*--mobile-app--*/

.mobile-app {
	padding:5em 0;
}
.app-right {
	margin-top:50px;
}
.app-right h3 {
    font-size: 28px;
     color: #34ad00;
    line-height: 35px;
}
.app-right h3 span {
	color:#3F84B1;
	margin:0 7px;
}
.app-right p {
	margin:15px 0 30px 0;
	color:#999;
	font-size:1em;
	line-height:25px;
}
.app-button {
    float: left;
}
.app-button a {
	display:block;
}
.app-button img {
    width:90%;
}
/*-- banner-bottom --*/
.banner-bottom{
  padding: 5em 0;
}
.banner-text {
	text-align: center;
}
.banner-text h3{
  color: #34ad00;
  font-size: 3em;
  font-weight: 400;
  margin: 0;
}
.banner-text p{
  color: #999;
  font-size: 1em;
  margin: 2em auto 0 auto;
  width: 72%;
  line-height: 1.8em;
}
.banner-bottom-grids{
	margin: 6em 0 0 0;
}	
.banner-bottom-grid{
	text-align:center;
}
.banner-bottom-grid h4 {
    color: #34ad00;
    margin: 2em 0 1em 0;
    font-size: 1.6em;
    font-weight: 700;
}
.banner-bottom-grid p{
  color:#999;
  font-size:1em;
  margin: 0 auto;
  width: 80%;
  line-height: 1.8em;
}
.services-icon {
  background: #3F84B1;
  width: 120px;
  height: 120px;
  line-height: 136px;
  margin: 0 auto;
  border-radius: 50%;
  -webkit-border-radius: 50%;
  -ms-border-radius: 50%;
  -moz-border-radius: 50%;
  -o-border-radius: 50%;
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-th-large{
  font-size: 2.5em;
  color: #FFFFFF;
  top: 5px;
}
.red h4{
	 color: #34ad00;
}
.green h4{
	 color: #34ad00;
}
ul.callbacks_tabs.callbacks2_tabs a:after{
	border:2px solid #505b6f;
}
ul.callbacks_tabs.callbacks2_tabs .callbacks_here a:after{
	background: #505b6f;
	left:10%;
}
ul.callbacks_tabs.callbacks2_tabs {
  left: 82%;
  top: 102%;
}
/*-- //mobile-app--*/
/*-- blog --*/
.comments-list h3{
	font-size:2em;
	color:#4CB320;
	margin:0 0 1em;
	text-transform:capitalize;
	text-decoration: none;
	line-height: 1.3em;
}
.comments-list h3 a{
	color:#4CB320;
}
.comments-list h3 a:hover{
	color:#3F84B1;
}
.comments-list ul{
	padding:1.5em 0 2em; 
}
.comments-list ul li{
	display:inline-block;
	font-size:14px;
	color:#999;
}
.comments-list ul li a{
	color:#999;
	text-decoration:none;
}
.comments-list ul li span {
    padding-right: 10px;
    color: #1f8dd6;
}
.comments-list ul li a:hover{
	color:#4CB320;
}
.comments-list ul li i{
	margin:0 1em;
}
a.bake{
	padding: .3em .5em;
    background: #F3AD45;
    color: #fff !important;
}
a.bake:hover{
	background:#454445;
}
.comments-list p{
	margin:2em 0;
	color:#999;
	line-height:1.8em;
	font-size:14px;
}
.comments-list:nth-child(2){
	margin:5em 0;
	padding:3em 0 5em;
	border-top:1px solid #999;
	border-bottom:1px solid #999;
}
ul.paging{
	padding:5em 0 0;
}
.popular h3, .subscribe h3, .categories h3, .instagram h2, .tags h3 {
    padding: 1em;
    background: #3F84B1;
    color: #fff;
    font-size: 1.5em;
    text-align: center;
    margin: 0 0 1.5em;
}
.popular-left{
	float:left;
	width:20%;
}
.popular-right{
	float:right;
	width:80%;
}
.popular-left h4{
	color:#4CB320;
	font-size:1.5em;
	margin:0;
}
.popular-right h5 a{
	font-size:1.5em;
	color:#3F84B1;
	text-decoration:none;
	text-transform:capitalize;
}
.popular-right h5 a:hover{
	 color: #34ad00;
}
.popular-right p{
	font-size:14px;
	color:#999;
	margin:.5em 0 0;
	line-height:1.8em;
}
.popular-right p span{
	display:block;
	font-size:1em;
	margin:.5em 0 0;
}
.popular-grid:nth-child(3){
	margin:2em 0;
}
.subscribe,.instagram{
	margin:3em 0;
}
.subscribe p{
	font-size:14px;
	color:#999;
	margin:0 0 1em;
	line-height:1.8em;
	text-align:center;
}
.subscribe input[type="email"]{
	outline: none;
    border: 1px solid #D1D1D1;
    background: #E1E1E1;
    font-size: 14px;
    color: #999;
    padding: 10px;
    width: 100%;
    margin-bottom: .5em;
}
.subscribe input[type="submit"]{
	outline:none;
	border:none;
	background:#4CB320;
	font-size:1em;
	color:#fff;
	padding:10px 0;
	width:100%;
}
.subscribe input[type="submit"]:hover{
	background:#3F84B1;
}
.categories ul li{
	padding-left: 2em;
    margin-bottom: 1em;
    background: url(../images/dot.png)no-repeat 0px 2px;
    list-style-type: none;
}
.categories ul li a{
	color: #999;
    font-size: 14px;
    text-decoration: none;
    text-transform: capitalize;
}
.categories ul li a:hover{
    color: #4CB320;
}
.instagram-grid{
	float:left;
	width:33.33%;
}
.instagram-grid img:hover{
	opacity:.5;
}
.tags ul li{
	display:inline-block;
	margin: 0 0px 9px;
}
.tags ul li a {
    border: 1px solid #3F84B1;
    padding: 3px 12px;
    font-size: 14px;
    color: #3F84B1;
    text-decoration: none;
}
.recent-comments h3 {
    color: #4CB320;
    font-size: 1.5em;
}
.tags ul li a:hover{
	border: 1px solid #4CB320;
    color: #fff;
	background:#4CB320;
}
.blog {
    padding: 5em 0;
}
/*-- //blog --*/
/*-- single1 --*/
.comments-list p span{
	display:block;
	margin:1em 0 0;
}
.admin{
	padding:2em;
	background:#f5f5f5;
	margin:1em 0 5em;
}
.admin-left{
	float:left;
	width:15%;
}
.admin-right{
	float:right;
	width:80%;
}
.admin-right p{
	font-size:14px;
	color:#999;
	margin:0;
	line-height:1.8em;
}
.admin-right p a{
	color: #4CB320;
    text-decoration: none;
    display: block;
    margin: 1em 0 0;
}
.admin-right p a:hover{
	color:#999;
}
.recent-comments-grids{
	padding:2em;
	background:#f5f5f5;
	margin: 2em 0 0em;
}
.recent-comments-grid-right h4 a {
    font-size: 1em;
    color: #3F84B1;
    text-decoration: none;
}
.recent-comments-grid-right h4 a:hover{
	color:#4CB320;
}
.recent-comments-grid-right p{
	margin:1em 0 0;
	color:#999;
	line-height:1.8em;
	font-size:14px;
}
.recent-comments-grid-right p span{
	display:block;
	margin:1em 0 0;
	color:#4CB320;
}
.recent-comments-grid-right{
	float:right;
	width:80%;
}
.recent-comments-grid-left{
	float:left;
	width:15%;
}
.recent-comments-grid:nth-child(2){
	margin:2em 0;
}
.recent-comments-grid:nth-child(3){
	margin:0em 0 2em;
}
.leave-comment{
	margin:5em 0 0;
}
.leave-comment form{
	margin:3em 0 0;
}
.leave-comment input[type="text"],.leave-comment input[type="email"],.leave-comment textarea{
	outline: none;
    padding: 10px;
    width: 49.2%;
    background: #f5f5f5;
    border: 1px solid #D1D1D1;
    font-size: 14px;
    color: #999;
}
.leave-comment input[type="email"]{
	margin-left:.5em;
}
.leave-comment input[type="text"]:nth-child(3){
	margin:.5em 0;
	width:100% !important;
}
.leave-comment textarea{
	min-height:200px;
	width:100% !important;
	margin-bottom: .2em;
}
.leave-comment input[type="submit"]{
	outline:none;
	padding:10px 0;
	width:100%;
	background:#4CB320;
	border:none;
	font-size:1em;
	color:#fff;
	text-align:center;
}
.leave-comment input[type="submit"]:hover{
	background:#3F84B1;
}
/*-- //single1 --*/
.footer-social-icons ul li {
	display:inline-block;
	margin:0 0.2em;
}
.footer-social-icons ul li a{
	width:30px;
	height:30px;
	background:url('../images/img-sprite.png') no-repeat 0px 0px;
	display:inline-block;
	position: relative;
}
.footer-social-icons ul li a span {
    color: #fff;
    position: absolute;
    bottom: 0;
    left: -25px;
    right: -25px;
    padding: 5px;
    font-size: 14px;
    border-radius: 2px;
    background:#1F8DD6;
    visibility: hidden;
    opacity: 0;
    -o-transition: all .5s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    -webkit-transition: all .5s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    -moz-transition: all .5s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    transition: all .5s cubic-bezier(0.68, -0.55, 0.265, 1.55);
}
.footer-social-icons ul li a span:before {
    content: '';
    width: 0;
    height: 0;
    border-left: 5px solid transparent;
    border-right: 5px solid transparent;
    border-top: 5px solid #1F8DD6;
    position: absolute;
    bottom: -5px;
    left: 34px;
}
.footer-social-icons ul li a:hover span {
    bottom: 41px;
    visibility: visible;
    opacity: 1;
}
.footer-social-icons ul li a.facebook {
	background-position:0px 0px;
}
.footer-social-icons ul li a.facebook:hover {
	background-position:-0px -30px;
}
.footer-social-icons ul li a.twitter {
	background-position:-30px 0px;
}
.footer-social-icons ul li a.twitter:hover {
	background-position:-30px -30px;
}
.footer-social-icons ul li a.flickr {
	background-position:-60px 0px;
}
.footer-social-icons ul li a.flickr:hover {
	background-position:-60px -30px;
}
.footer-social-icons ul li a.googleplus {
	background-position:-90px 0px;
}
.footer-social-icons ul li a.googleplus:hover {
	background-position:-90px -30px;
}
.footer-social-icons ul li a.dribbble {
	background-position:-120px 0px;
}
.footer-social-icons ul li a.dribbble:hover {
	background-position:-120px -30px;
}
.footer-social-icons {
    margin: 10px 0 10px;
}

.lightbox {
	/** Hide the lightbox */
	display: none;
	
	/** Apply basic lightbox styling */
	position: fixed;
	z-index: 9999;
	width: 100%;
	height: 100%;
	top: 0;
	left: 0;
	color:#333333;
	    background: rgba(0, 0, 0, 0.72);
	}

.lightbox:target {
    /** Show lightbox when it is target */
    display: block;
    outline: none;
}

.lightbox .box {
    width: -webkit-min-content;
    width: -moz-min-content;
    width: min-content;
    min-width: 610px;
    border:10px solid rgba(52, 173, 0, 0.56);
    margin: 12% auto;
    padding: 20px 20px 30px 20px;
    background-color: #FFF;
}
.lightbox .content {
	display:block;
	position:relative;
	}
.lightbox .content .desc {
	z-index:99;
	bottom:0;
	position:absolute;
	padding:10px;
	margin:0 0 4px 0;
	background:rgba(0,0,0,0.8);

	color:#fff;
	font-size:17px;
	opacity:0;
	transition: opacity ease-in-out 0.5s;
	}	
	
.lightbox .content:hover .desc	{
	opacity:1;
}

.lightbox .close {
	display:block;
	text-decoration:none;
	font-family:Gotham, "Helvetica Neue", Helvetica, Arial, sans-serif;
	font-size:22px;
	color:#3F84B1;
	opacity: 1;
	}

.close {
	float:right;
	}
	
	.clear {
		display:block;
		clear:both;
		}
ul.set li,ul.set1 li {
    display: inline-block;
    float: left;
    width: 12%;
    margin-top: 1em;
}
ul.set1{
	margin-top:2em
	
}
p.aval {
    padding-left: 12px;
    font-weight: 700;
}
ul.ste1 li {
    display: inline-block;
}
.set-left {
    float: left;
    width: 58%;
}
.set-right {
    float: left;
    width: 42%;
    padding-left: 40px;
}
ul.ste1 {
    margin-top: 0.7em;
}
ul.set-1 {
    margin-top: 1em;
    margin-left: 266px;
}
.navbar-default {
    background-color: #4CB320 !important;
    border-color: #4CB320 !important;
}
.navbar {
    min-height: 0px !important;
    margin-bottom:0px !important;
    border-radius:0px !important;
	border: none !important;
}
ul.nav.navbar-nav li a {
    font-size: 15px ;
    color: #fff;
    display: inline-block;
    padding: 5px 8px;
}
.navbar-default .navbar-nav > li > a:hover, .navbar-default .navbar-nav > li > a:focus {
    color:#4CFF00 !important;
}
.navbar-default .navbar-nav > .active > a, .navbar-default .navbar-nav > .active > a:hover, .navbar-default .navbar-nav > .active > a:focus {
   color:#4CFF00 !important;
    background-color: #4CB320 !important;
}
.navbar-collapse {
    padding-right: 0px !important;
    padding-left: 0px !important;
}
/*-- responsive design --*/
@media (max-width:1024px){
.footer-btm li {
    margin: 0 6px;
    font-size: 14px;
}
ul.nav.navbar-nav li a {
    font-size: 14px;
    padding: 5px 7px;
}
.banner h1 {
    padding: 2.8em 0 0;
	font-size: 46px;
}
.banner {
    min-height: 320px;
}
.bann-info1 {
    padding: 4em 5em 0em;
}
.rupes {
    padding: 3em 0;
}
i.fa.fa-h-square,i.fa.fa-usd,i.fa.fa-mobile {
    font-size: 4em;
}
.rupes h4 {
    font-size: 18px;
    line-height: 1.5em;
}
.holiday {
    padding: 3em 0;
}
.holiday h3 {
    font-size: 1.7em;
}
.holiday p {
    font-size: 1em;
}
.track {
    padding: 3em 0;
}
.track h3 {
    font-size: 1.7em;
}
.track p {
    font-size: 1em;
}
a.learn {
    padding: 6px 20px!important;
    font-size: 15px;
}
.routes {
    padding: 3em 0;
}
i.fa.fa-truck, i.fa.fa-user, i.fa.fa-ticket {
    font-size: 3em;
}
.routes p {
    font-size: 1em;
}
.routes h3 {
    font-size: 1.7em;
}
button.seabtn {
    padding: 6px 20px!important;
    font-size: 15px;
}
.faq p {
    font-size: 15px;
}
.faq li {
    font-size: 15px;
}
.faq {
    padding: 3em 0;
}
.faq h2 {
    font-size: 1.8em;
}
.faq h3 {
    font-size: 1.5em;
}
.banner-1 h1,.banner-2 h1,.banner-3 h1 {
    padding: 1.8em 0 0;
    font-size: 46px;
}
.about {
    padding: 3em 0;
}
.about h2 {
    font-size: 2em;
}
.about h3 {
    font-size: 1.7em;
}
.app-right {
    margin-top: 0px;
}
.app-right h3 {
    font-size: 25px;
}
.mobile-app {
    padding: 3em 0;
}
.banner-bottom {
    padding: 2em 0;
}
.banner-bottom-grids {
    margin: 3em 0 0 0;
}
.banner-bottom-grid h4 {
    margin: 1em 0 0.5em 0;
    font-size: 1.6em;
}
.banner-bottom-grid p {
    width: 100%;
}
.terms {
    padding: 3em 0;
}
.privacy {
    padding: 3em 0;
}
.agent {
    padding: 3em 0;
}
.agent-right iframe {
    width: 390px;
    height: 286px;
}
.contact {
    padding: 3em 0;
}
.contact h3 {
    margin-bottom: 0em;
}
.bann-info1 {
    padding: 3em 4em 0em;
}
.bann-info {
    padding: 3em 0;
}
.bann-info1 h3 {
    font-size: 1.7em;
}
.blog {
    padding: 3em 0;
}
.leave-comment input[type="text"], .leave-comment input[type="email"], .leave-comment textarea {
    width: 49%;
}
.hotels-top {
    padding: 2em 0;
}
.view1-sixth h2 {
    margin: 96px 30px 0px 30px;
}
.banner-2 {
    min-height: 320px;
}
.rooms-top {
    min-height: 295px;
    padding: 12em 0 0;
}
.details {
    padding: 2em 0;
}
.details-middle {
    padding: 1em 1em;
}
.details-middle h3 {
    font-size: 1.4em;
    font-weight: 700;
}
.selectroom {
    padding: 3em 0 1em;
}
.tracking-top, .tracking-bottom {
    padding: 3em 2em;
}
.tracking {
    padding: 3em 0;
}
.offers-1 {
    padding: 3em 0;
}
}
@media (max-width:991px){
ul.nav.navbar-nav li a {
    font-size: 13px;
    padding: 5px 0px;
}
.footer-btm li {
    margin: 0px 4px;
    font-size: 13px;
}
.banner h1 {
    padding: 2.8em 0 0;
    font-size: 43px;
}
.banner {
    min-height: 300px;
}
.bann-info1 {
    padding: 4em 2em 0em 0em;
    float: left;
    width: 30%;
}
.bann-info {
    padding: 4em 0;
    float: left;
    width: 70%;
}
.bann-info1 h3 {
    font-size: 1.5em;
    font-weight: 700;
    color: #34ad00;
    text-align: center;
    margin-top: 25px;
}
.rupes-left {
    float: left;
    width: 33.33%;
}
i.fa.fa-h-square, i.fa.fa-usd, i.fa.fa-mobile {
    font-size: 3.2em;
}
.rupes h4 {
    font-size: 17px;
	margin:5px 0 0;
}
.rupes p {
    font-size: 13px;
}
.holiday-left {
    float: left;
    width: 28%;
}
.holiday-mid {
    float: left;
    width: 44%;
}
.holiday p {
    font-size: 14px;
}
.track-right {
    float: left;
    width: 40%;
}
.track-left {
    float: left;
    width: 60%;
}
.routes-left {
    float: left;
    width: 33.33%;
}
i.fa.fa-truck, i.fa.fa-user, i.fa.fa-ticket {
    font-size: 2.5em;
}
.routes p {
    font-size: 14px;
}
.footer-left {
    margin-top: 2em;
}
.footer-top {
    padding: 1em 0 3em;
}
.banner-1 h1,.banner-2 h1,.banner-3 h1 {
    padding: 1.8em 0 0;
    font-size: 43px;
}
.about h2 {
    margin-bottom: 0.5em;
}
.about-mid {
    margin: 3em 0;
}
.privacy p {
    font-size: 15px;
}
.agent-left input[type="text"] {
    width: 100%;
}
select {
    width: 100%;
}
.agent-left textarea {
    width: 100%;
}
.agent-right {
    padding-left: 1em;
}
.agent-right iframe {
    width: 687px;
    height: 500px;
	margin-top: 2em;
}
.con-top {
    margin-top: 2em;
    float: left;
    width: 33.33%;
}
.app-left {
    float: left;
    width: 40%;
}
.app-right {
    float: right;
    width: 60%;
}
.banner-text h3 {
    font-size: 2.5em;
}
.banner-text p {
    width: 100%;
}
.banner-bottom-grid {
    float: left;
    width: 33.33%;
}
.banner-bottom-grid h4 {
    font-size: 1.5em;
}
.travel {
    padding: 0em 0 3em;
}
li.trav {
    width: 27%;
}
li.dept {
    width: 19%;
}
li.seat {
    width: 21%;
}
.bus-txt3 {
    float: right;
    width: 74%;
}
.bus-ic3 {
    width: 20%;
}
.bus-txt1 {
    width: 75%;
}
.bus-ic1 {
    width: 24%;
}
.comments-list h3 {
    margin: 0 0 0em;
}
.comments-list:nth-child(2) {
    margin: 2em 0;
    padding: 2em 0 2em;
}
.blog-right {
    margin-top: 1em;
}
.leave-comment input[type="text"], .leave-comment input[type="email"], .leave-comment textarea {
    width: 49.1%;
}
.hotels-right {
    float: left;
    width: 50%;
}
.hotels-left {
    float: left;
    width: 33.33%;
}
.view1-sixth h2 {
    margin: 60px 0px 0px 0px;
}
.hotes-left {
    float: left;
    width: 33.33%;
}
.banner-2 {
    min-height: 250px;
}
.rom-info h3 {
    font-size: 1.5em;
}
.rooms-top {
    min-height: 247px;
    padding: 9em 0 0;
}
.details-left {
    padding-left: 0;
    float: left;
    width: 35%;
}
.details-middle {
    padding: 1em 1em;
    float: left;
    width: 49%;
}
.details-right {
    text-align: center;
    float: left;
}
.details-middle h3 {
    font-size: 1.3em;
}
.room-midle {
    padding: 0.5em 0.5em;
    float: left;
    width: 51%;
}
.room-left {
    float: left;
    width: 30%;
}
.room-right {
    padding: 2em 1em;
    float: left;
    width: 19%;
}
.selectroom_left {
    padding: 0;
    margin-bottom: 1.5em;
}
.selectroom_right {
    padding: 0;
}
.tracking-left {
    float: left;
    width: 50%;
}
.tracking-right {
    float: left;
    width: 50%;
}
.tracking-top, .tracking-bottom {
    padding: 3em 1em;
}
.bus-tp {
    padding: 0.5em 0;
}
.app-right p,.banner-text p,.banner-bottom-grid p {
    font-size: 0.9em;
}
}
@media (max-width:768px){
.logo {
    margin-right: 30px;
}
.banner h1 {
    padding: 2.5em 0 0;
    font-size: 40px;
}
.banner {
    min-height: 250px;
}
}
@media (max-width:736px){
.footer-btm li {
    display: block;
    margin: 10px 0;
}
.footer-btm {
    padding: 0;
}
.navbar-toggle {
    margin-top: 2px;
    margin-bottom: 2px;
    background-color: transparent;
    background-image: none;
    border: 1px solid transparent;
    border-radius: 4px;
	margin-right: 0px;
}
.navbar-default .navbar-toggle {
    border-color: #4CB320;
}
.navbar-toggle .icon-bar {
    width: 26px;
    height: 3px;
}
.navbar-default .navbar-toggle:hover, .navbar-default .navbar-toggle:focus {
    background-color: #4CB320;
}
.navbar-default .navbar-toggle .icon-bar {
    background-color: #fff;
}
.navbar-default .navbar-collapse, .navbar-default .navbar-form {
    border-color: #4CB320;
}
ul.nav.navbar-nav li a {
    font-size: 15px;
    padding: 5px 0px;
    display: block;
}
.navbar-nav {
    margin: 7.5px 0px;
}
nav.cl-effect-1 {
    padding: 0em 0 1em;
}
.banner-1 h1,.banner-2 h1,.banner-3 h1 {
    padding: 1.5em 0 0;
    font-size: 40px;
}
.agent-right iframe {
    width: 654px;
    height: 485px;
}
.banner-2 h1 {
    padding: 2.5em 0 0;
}
.rom-info p {
    font-size: 13px;
}
.room-right {
    padding: 2em 0.5em;
}
}
@media (max-width:667px){
.banner h1 {
    padding: 2.2em 0 0;
    font-size: 36px;
}
.banner {
    min-height: 200px;
}
.bann-info {
    padding: 3em 0;
}
.bann-info1 {
    padding: 3em 2em 0em 0em;
}
.bnr-left input[type="text"] {
    padding: 6px 10px;
}
.bnr-right input[type="text"] {
    padding: 6px 10px;
}
i.fa.fa-h-square,i.fa.fa-usd,i.fa.fa-mobile {
    font-size: 2.8em;
}
.rupes h3 {
    font-size: 17px;
}
.rupes h4 {
    font-size: 15px;
}
.holiday h3 {
    font-size: 1.5em;
}
.holiday p {
    font-size: 13px;
}
.routes h3 {
    font-size: 1.5em;
}
i.fa.fa-truck, i.fa.fa-user, i.fa.fa-ticket {
    font-size: 2.2em;
}
.banner-1 h1,.banner-2 h1,.banner-3 h1 {
    padding: 1.2em 0 0;
    font-size: 36px;
}
.agent-right iframe {
    width: 587px;
    height: 449px;
}
.app-right h3 {
    font-size: 22px;
}
.app-button {
    width: 50%;
}
.mobile-app {
    padding: 3em 0 1em;
}
.banner-bottom-grid h4 {
    font-size: 1.3em;
}
.bus-midd h4 {
    font-size: 17px;
}
.bus-midd h4 a {
    font-size: 17px;
}
.bus-ic {
    width: 12%;
}
.bus-txt {
    float: right;
    width: 84%;
}
.view1-sixth h2 {
    margin: 46px 0px 0px 0px;
}
.banner-2 h1 {
    padding: 2.2em 0 0;
}
.rt-left {
    width: 77%;
}
.rom-info h3 {
    font-size: 1.3em;
}
.rom-info p {
    font-size: 14px;
}
.details-left {
    width: 34%;
}
.details-middle {
    padding: 1em 0em;
}
.room-right {
    width: 20%;
}
.room-left {
    width: 29%;
}
li.nam {
    width: 37%;
    margin-bottom: 1em;
}
li.mr {
    width: 24%;
}
li.spe {
    margin-top: 1em;
}
}
@media (max-width:640px){
.securetxt {
    line-height: 17px;
    font-size: 13px;
}
i.fa.fa-lock {
    font-size: 1.7em;
    padding-right: 4px;
}
.logo {
    margin-right: 20px;
}
.bus a {
    font-size: 13px;
    padding: 0 6px;
}
.bann-info1 h3 {
    font-size: 1.4em;
}
.banner-1 h1,.banner-3 h1{
    padding: 1.7em 0 0;
    font-size:30px;
}
.app-right h3 {
    font-size: 21px;
}
.comments-list ul li {
    font-size: 13px;
}
.comments-list h3 {
    font-size: 1.7em;
}
.leave-comment input[type="text"], .leave-comment input[type="email"], .leave-comment textarea {
    width: 48.9%;
}
.view1-sixth h2 {
    margin: 40px 0px 0px 0px;
}
.banner-2 h1 {
    padding: 3em 0 0;
    font-size: 30px;
}
.banner-3 {
    min-height: 190px;
}
.rt-left {
    width: 74%;
}
.details-left {
    width: 33%;
}
.room-left {
    width: 27%;
}
.room-right {
    width: 22%;
}
}
@media (max-width:600px){
.banner h1 {
    padding: 2.2em 0 0;
    font-size: 30px;
}
.banner {
    min-height: 175px;
}
.bann-info1 {
    width: 33%;
}
.bann-info {
    width: 67%;
}
.bann-info h2 {
    font-size: 24px;
}
.bnr-left input[type="text"] {
    font-size: 13px;
    margin-top: 0px;
}
.bnr-right input[type="text"] {
    font-size: 13px;
    margin-top: 0px;
}
.ban-top .inputLabel, .ban-bottom .inputLabel {
    font-size: 13px;
}
button.seabtn {
    padding: 6px 16px!important;
    font-size: 14px;
}
.rupes-left {
    float: left;
    width: 100%;
    margin-bottom: 2em;
}
i.fa.fa-h-square, i.fa.fa-usd, i.fa.fa-mobile {
    font-size: 5em;
}
.rup-left {
    float: left;
    width: 17%;
}
.rup-rgt {
    float: left;
    width: 83%;
}
.rupes h3 {
    font-size: 22px;
}
.rupes h4 {
    font-size: 18px;
}
.rupes {
    padding: 3em 0 1em;
}
.holiday-left {
    width: 100%;
}
.holiday-mid {
    width: 100%;
    margin: 1em 0;
}
.track p {
    width: 84%;
}
.routes-left {
    width: 100%;
    margin-bottom: 1.5em;
}
i.fa.fa-truck, i.fa.fa-user, i.fa.fa-ticket {
    font-size: 4em;
}
.routes h3 {
    font-size: 2em;
}
.routes p {
    font-size: 15px;
}
.routes {
    padding: 3em 0 1em;
}
.banner-1 {
    min-height: 140px;
}
.agent-right iframe {
    width: 521px;
    height: 400px;
}
.agent-right iframe {
    width: 560px;
    height: 425px;
}
.details-left {
    width: 32%;
}
.details-middle h3 {
    font-size: 1.2em;
}
.details-middle {
    padding: 0.5em 0em;
}
.details-middle li {
    margin: 0 7px 0 0px;
    font-size: 14px;

}
.details-middle p {
    font-size: 14px;
}
.details-top h5 {
    font-size: 1.3em;
}
.lightbox .box {
    min-width: 545px;
    margin: 12% auto;
    padding: 10px 10px 20px 10px;
}
p.aval {
    padding-left: 10px;
}
}
@media (max-width:568px){
.bann-info h2 {
    font-size: 22px;
	margin-bottom:15px;
}
.bann-info1 h3 {
    font-size: 1.3em;
}
.rup-left {
    width: 23%;
}
.rup-rgt {
    width: 77%;
}
.agent-right iframe {
    width: 488px;
    height: 375px;
}
.con-top {
    width: 50%;
}
.app-left img {
    display: inline-block;
}
.app-left {
    width: 100%;
	text-align: center;
}
.app-right {
    float: right;
    width: 100%;
    margin-top: 2em;
}
.app-right h3 {
    font-size: 24px;
}
.banner-bottom-grid {
    float: left;
    width: 100%;
    margin-bottom: 2em;
}
.banner-bottom-grid h4 {
    font-size: 1.5em;
}
.travel h3 {
    font-size: 1.5em;
}
.travel p {
    font-size: 14px;
}
a.det {
    padding: 6px 14px;
}
a.view {
    padding: 6px 16px;
}
i.fa.fa-clock-o {
    font-size: 1.2em;
}
.bus-midd h4 {
    font-size: 15px;
}
.bus-midd p {
    font-size: 13px;
}
.bus-midd h4 a {
    font-size: 15px;
}
.comments-list ul li i {
    margin: 0 0.2em;
}
.leave-comment input[type="text"], .leave-comment input[type="email"], .leave-comment textarea {
    width: 48.8%;
}
.view1-sixth h2 {
    margin: 32px 0px 0px 0px;
}
}
@media (max-width:480px){
.logo a {
    font-size: 1.7em;
}
.logo {
    margin-right: 0;
    width: 100%;
    text-align: center;
    margin-bottom: 10px;
}
li.hm, li.prnt {
    margin-right: 2px;
}
.banner h1 {
    padding: 2.2em 0 0;
    font-size: 26px;
}
.banner {
    min-height: 150px;
}
.bann-info1 {
    width: 100%;
    padding: 2em 1em 0em;
}
.bann-info {
    width: 100%;
    padding: 2em 14px;
}
.rupes {
    padding: 2em 0 1em;
}
.footer-left li a {
    font-size: 13px;
}
.faq {
    padding: 2em 0;
}
.banner-1 h1,.banner-2 h1,.banner-3 h1{
    font-size: 26px;
}
.agent-right iframe {
    width: 400px;
    height: 305px;
}
a.det {
    padding: 6px 5px;
}
.tra-top h6 a {
    font-size: 14px;
}
li.ser {
    width: 16%;
	 text-align: center;
}
li.las {
    width: 17%;
	 text-align: center;
}
li.rou {
    width: 32%;
	 text-align: center;
}
li.dat {
    text-align: center;
}
.travel p {
    font-size: 13px;
}
.bus-tp h2 {
    font-size: 17px;
}
.bus-tp P {
    font-size: 13px;
    line-height: 1.5em;
}
.bus-midd h4 {
    font-size: 13px;
}
.bus-midd h4 a {
    font-size: 13px;
}
.bus-midd h5 {
    font-size: 18px;
}
a.view {
    padding: 5px 8px;
	margin-top:6px;
}
ul.first {
    padding: 1em 0 1em;
}
.blog {
    padding: 2em 0;
}
.comments-list h3 {
    font-size: 1.5em;
}
.comments-list ul li span {
    padding-right: 3px;
}
.comments-list ul li i {
    margin: 0 0px;
}
.comments-list ul {
    padding: 1em 0 1em;
}
.comments-list p {
    margin: 1em 0;
}
ul.paging {
    padding: 1em 0 0;
}
.leave-comment {
    margin: 2em 0 0;
}
.leave-comment form {
    margin: 1em 0 0;
}
.leave-comment input[type="text"], .leave-comment input[type="email"], .leave-comment textarea {
    width: 48.6%;
}
.view1-sixth h2 {
    margin: 25px 0px 0px 0px;
	font-size:14px;
}
.routes h3 {
    font-size: 1.7em;
}
.rooms-top {
    min-height: 211px;
    padding: 6em 0 0;
}
.rom-info h3 {
    font-size: 1.1em;
}
.rom-info p {
    font-size: 12px;
}
.rom-info {
    padding: 1em 1em;
}
.room-map {
    margin: 2em 0;
}
.room-map iframe {
    min-height: 200px;
}
.hotel-amenit li {
    font-size: 14px;
}
.hotel-police p {
    font-size: 14px;
}
.details-middle h3 {
    font-size: 1.1em;
}
.details-top h5 {
    font-size: 1.2em;
}
.room-right {
    width: 23%;
}
.room-midle {
    width: 50%;
}
.rom-btm p {
    font-size: 14px;
    color: #999;
}
.tracking-left {
    float: left;
    width: 100%;
}
.tracking-right {
    float: left;
    width: 100%;
}
.offers-1 h3 {
    font-size: 18px;
}
.holiday-left img {
    width: 100%;
}
.lightbox .box {
    min-width: 445px;
}
ul.set-1 {
    margin-top: 1em;
    margin-left: 194px;
}
.set-right {
    padding-left: 9px;
}
.footer-top h3 {
    font-size: 1.5em;
}
.faq p {
    font-size: 13px;
}
.faq li {
    font-size: 13px;
}
.app-right p {
    font-size: 13px;
}
.banner-text p {
    font-size: 13px;
}
.banner-bottom-grid p {
    font-size: 13px;
}
.comments-list p {
    font-size: 13px;
}
.popular-right p {
    font-size: 13px;
}
.categories ul li a {
    font-size: 13px;
}
.comments-list p span {
    font-size: 13px;
}
.admin-right p {
    font-size: 13px;
}
.recent-comments-grid-right p {
    font-size: 13px;
}
.privacy p {
    font-size: 13px;
}
.agent p {
    font-size: 13px;
}
.terms p {
    font-size: 13px;
}
i.fa.fa-h-square {
    font-size: 3em;
}
i.fa.fa-usd, i.fa.fa-mobile {
    font-size: 4em;
}
.login-left {
    float: none;
    width: 53%;
    margin: 0 0 2em;
}
.login-right {
    float: none;
    width: 100%;
}
}
@media (max-width:414px){
ul.tp-hd-rgt a {
    font-size: 11px;
}
ul.tp-hd-rgt li {
    font-size: 11px;
}
ul.tp-hd-lft a {
    font-size: 11px;
}
.banner h1 {
    padding: 2.7em 0 0;
    font-size: 22px;
}
.banner {
    min-height: 140px;
}
.rou-left {
    width: 28%;
}
.rou-rgt {
    width: 72%;
}
.footer-left li {
    width: 50%;
}
.rup-rgt {
    width: 70%;
}
.rup-left {
    width: 30%;
}
.footer-top {
    padding: 1em 0 2em;
}
.faq h2 {
    font-size: 1.7em;
}
.faq h3 {
    font-size: 1.4em;
}
.banner h1,.banner-2 h1,.banner-3 h1 {
    padding: 2.7em 0 0;
    font-size: 22px;
}
.about-mid {
    margin: 2em 0;
}
.about h3 {
    margin-bottom: 0.3em;
}
.ab-lt {
    padding-right: 15px;
}
.terms {
    padding: 2em 0;
}
.privacy h3 {
    margin-bottom: 0em;
}
.privacy p {
    font-size: 14px;
}
.privacy {
    padding: 2em 0;
}
.agent-right iframe {
    width: 335px;
    height: 261px;
}
.agent-left input[type="text"] {
    font-size: 14px;
    padding: 6px 10px;
}
.app-right h3 {
    font-size: 22px;
}
.app-right p {
    font-size: 13px;
	margin: 8px 0 20px 0;
}
.banner-text p {
    font-size: 14px;
}
.banner-bottom-grid p {
    font-size: 14px;
}
.banner-bottom {
    padding: 2em 0 0;
}
.bann-info1 h3 {
    font-size: 1.2em;
}
.bann-info {
    padding: 1em 14px;
}
li.ser {
    text-align: left;
	font-size: 16px;
}
li.las {
    text-align: left;
	font-size: 16px;
}
li.rou {
    text-align: left;
	font-size: 16px;
}
li.dat {
    text-align: center;
	font-size: 16px;
}
li.fir {
    width: 15%;
    font-size: 16px;
}
.travel p {
    font-size: 12px;
}
a.det {
    padding: 6px 6px;
	font-size: 11px;
}
span.sen {
    display: none;
}
.bus-midd p {
    font-size: 10px;
}
.bus-midd h4 a {
    font-size: 12px;
}
a.view {
    font-size: 10px;
}
.bus-tp h2 {
    font-size: 14px;
}
.bus-tp P {
    font-size: 11px;
}
.comments-list h3 {
    font-size: 1.4em;
}
.leave-comment input[type="email"] {
    margin: 0.5em 0 0;
    width: 100%;
}
.admin {
    padding: 1em;
    margin: 1em 0 2em;
}
.leave-comment input[type="text"], .leave-comment input[type="email"], .leave-comment textarea {
    width: 100%;
}
.hotels-right {
    width: 100%;
	margin-bottom: 1em;
}
.view1-sixth h2 {
    margin: 78px 0px 0px 0px;
}
.hotels-left {
   margin-bottom: 1em;
    width: 100%;
}
.hotl-top {
    margin-top: 0em;
}
.hotels-top h3 {
    margin-bottom: 20px;
}
.hotels-top {
    padding: 1em 0;
}
.routes p {
    font-size: 14px;
}
.routes h3 {
    font-size: 1.3em;
}
.routes {
    padding: 0em 0 1em;
}
.banner-2 h1 {
    padding: 3em 0 0;
    font-size: 22px;
}
.banner-2 {
    min-height: 190px;
}
.rom-info {
    padding: 0.7em;
}
.rooms-top {
    min-height: 186px;
    padding: 5em 0 0;
}
.banner-3 {
    min-height: 160px;
}
.similar_hotel {
    margin-bottom: 2em;
}
.details-right {
    text-align: center;
    float: right;
	padding: 0;
}
.details-middle {
    width: 70%;
}
.details-left {
    width: 30%;
}
.details {
    padding: 0em 0 2em;
}
.room-left {
    width: 100%;
    padding: 0;
}
.room-midle {
    width: 100%;
    padding-left: 12px;
}
.room-right {
    width: 100%;
    padding: 0;
}
li.nam {
    width: 100%;
    margin-bottom: 1em;
}
li.mr {
    width: 46%;
    margin-bottom: 1em;
}
.selectroom_right li {
    width: 33.33%;
}
.selectroom_right p {
    font-size: 14px;
}
.selectroom {
    padding: 2em 0 0em;
}
.tracking h3 {
    margin-bottom: 0.5em;
}
.tracking p {
    font-size: 14px;
}
.login-right input[type="submit"] {
    font-size: 14px;
}
.writ input[type="text"] {
    font-size: 14px;
	width: 100%;
}
li.na-me {
    width: 100%;
}
li.na-me select {
    font-size: 14px;
	width: 100%;
}
.lightbox .box {
    min-width: 386px;
}
ul.set-1 {
    margin-left: 166px;
}
.footer-top h3 {
    font-size: 1.4em;
}
.login-left {
    width: 63%;
}
}
@media (max-width:384px){
ul.tp-hd-rgt a {
    font-size: 10px;
}
ul.tp-hd-rgt li {
    font-size: 10px;
}
ul.tp-hd-lft a {
    font-size: 10px;
}
i.fa.fa-home {
    font-size: 18px;
}
.ban-top .inputLabel, .ban-bottom .inputLabel {
    font-size: 12px;
}
.bann-info h2 {
    font-size: 20px;
    margin-bottom: 15px;
}
.agent-right iframe {
    width: 296px;
    height: 229px;
}
.app-right h3 {
    font-size: 20px;
}
.bann-info1 {
    padding: 2em 0.4em 0em;
}
.bus-midd h5 {
    font-size: 15px;
}
a.view {
    font-size: 11px;
    text-align: center;
}
li.fare {
    width: 22%;
	text-align: center;
}
li.seat {
    width: 24%;
	text-align: center;
}
.bus-midd p {
    font-size: 10px;
    text-align: center;
}
.bus-txt3 {
    float: right;
    width: 100%;
}
li.arriv {
    width: 16%;
	text-align: center;
}
li.dept {
    width: 18%;
	text-align: center;
}
.bus-ic1 {
    width: 100%;
    text-align: center;
}
a.view {
    padding: 5px 7px;
}
i.fa.fa-clock-o {
    margin-top: 10px;
}
li.arriv h4 {
    margin-top: 30px;
}
.bus-ic3 {
    width: 100%;
    text-align: center;
}
.bus-ic3 img{
   display:inline-block;
}
.bus-txt4 {
    margin-top: 13px;
}
.bus-txt1 {
    width: 100%;
}
li.trav {
    width: 20%;
	text-align: center;
}
.bus-tp h2 {
    font-size: 12px;
}
.bus-tp P {
    line-height: 1.2em;
}
.bus-ic {
    width: 100%;
    text-align: center;
}
.bus-ic  img{
	display:inline-block;
}
.bus-txt {
    width: 100%;
}
.bus-midd h4 {
    font-size: 13px;
    text-align: center;
}
.comments-list h3 {
    font-size: 1.3em;
}
.banner-2 {
    min-height: 180px;
}
.set-left {
    float: left;
    width: 100%;
}
.set-right {
    padding-left: 0px;
    margin-top: 1em;
    width: 100%;
}
.lightbox .box {
    min-width: 349px;
}
ul.set-1 {
    margin-left: 254px;
}
p.aval {
    font-size: 13px;
}
.login-left {
    width: 68%;
}
}
@media (max-width:375px){
li.ned, li.wrt, li.tol {
    margin-right: 6px;
}
.banner h1,.banner-2 h1,.banner-3 h1 {
    padding: 1.7em 0 0;
    font-size: 25px;
}
.bann-info h2 {
    font-size: 19px;
    margin-bottom: 15px;
}
.track h3 {
    font-size: 1.5em;
}
.track p {
    width: 100%;
	 font-size: 14px;
}
.routes h3 {
    font-size: 1.8em;
}
.rou-left {
    width: 31%;
}
.rou-rgt {
    width: 69%;
}
a.view {
    padding: 5px 6px;
}
.hotes-left {
    float: left;
    width: 100%;
    text-align: left;
    margin-bottom: 1em;
}
.banner-2 h1 {
    padding: 2.7em 0 0;
}
.banner-2 {
    min-height: 180px;
}
.login-left {
    width: 71%;
}
}
@media (max-width:320px){
i.fa.fa-home {
    font-size: 20px;
}
ul.tp-hd-lft a {
    font-size: 12px;
}
ul.tp-hd-lft {
    float: left;
    width: 100%;
    text-align: center;
}
.logo {
    margin-bottom: 2px;
}
ul.tp-hd-rgt {
    float: left;
    width: 100%;
}
ul.tp-hd-rgt li {
    font-size: 12px;
}
ul.tp-hd-rgt a {
    font-size: 12px;
}
li.ned, li.wrt, li.tol {
    margin-right: 20px;
}
.top-header {
    height: 62px;
    line-height: 23px;
    padding: 0.5em 0;
}
.bus a {
    font-size: 12px;
    padding: 0 3px;
}
.securetxt {
    line-height: 17px;
    font-size: 12px;
}
.banner h1,.banner-2 h1,.banner-3 h1 {
    padding: 1.7em 0 0;
    font-size: 22px;
}
.bann-info1 {
    width: 100%;
    padding: 1em 0 0;
}
i.fa.fa-columns {
    font-size: 6em;
}
.bann-info1 h3 {
    font-size: 1.2em;
	margin-top:12px;
}
.bann-info {
    padding: 1em 0px;
}
.bann-info h2 {
    font-size: 17px;
    margin-bottom: 15px;
}
.ban-top .inputLabel, .ban-bottom .inputLabel {
    font-size: 11px;
}
button.seabtn {
    padding: 6px 13px!important;
    font-size: 13px;
}
.sear {
    margin-top: 20px;
}
.ban-bottom {
    margin-top: 20px;
}
i.fa.fa-h-square, i.fa.fa-usd, i.fa.fa-mobile {
    font-size: 4em;
}
.rupes h3 {
    font-size: 20px;
}
.rupes h4 {
    font-size: 16px;
}
.rupes-left {
    padding: 0;
}
.holiday {
    padding: 2em 0;
}
.holiday-left {
    padding: 0;
}
.holiday-mid {
    padding: 0;
}
.track {
    padding: 2em 0;
}
.track-left {
    padding: 0;
}
.track-right {
    padding-left: 0;
}
.routes-left {
    padding: 0;
}
.routes {
    padding: 2em 0 0em;
}
.routes h3 {
    font-size: 1.6em;
}
.routes p {
    font-size: 14px;
}
i.fa.fa-truck, i.fa.fa-user, i.fa.fa-ticket {
    font-size: 3em;
}
.footer-left {
    padding: 0;
}
.footer-top h3 {
    margin-bottom: 0.5em;
}
.banner-1 h1,.banner-2 h1,.banner-3 h1{
    font-size: 22px;
}
.banner-1 {
    min-height: 120px;
}
.faq h2 {
    font-size: 1.4em;
}
.faq h3 {
    font-size: 1.2em;
}
.faq p {
    font-size: 13px;
}
.faq {
    padding: 1em 0;
}
.about {
    padding: 1em 0;
}
.about h2 {
    font-size: 1.7em;
	margin-bottom:0.3em;
}
.about p {
    font-size: 13px;
}
.about h3 {
    font-size: 1.5em;
}
.abt-lft {
    padding: 0;
}
.ab-lt {
    padding: 0;
}
.ab-tp {
    margin-bottom: 1em;
}
.ab-rt {
    padding: 0;
}
.ab-rt ul li a {
    font-size: 13px;
    padding: 0px 0px 0px 22px;
}
.terms h3 {
    font-size: 1.4em;
}
.terms h6 {
    margin: 0.5em 0;
}
.terms p {
    font-size: 13px;
}
.terms-bottom {
    margin-top: 2em;
}
.terms {
    padding: 1.5em 0;
}
.privacy p {
    font-size: 13px;
}
.privacy {
    padding: 1.5em 0;
}
.privacy h4 {
    margin: 1em 0 0;
}
.agent {
    padding: 1.5em 0;
}
.agent-left {
    text-align: center;
    padding: 0;
}
.ag-bt {
    margin-bottom: 1em;
}
.agent-right iframe {
    width: 272px;
    height: 212px;
	margin-top: 1.5em
}
.agent-right {
    padding: 0;
}
.agent p {
    font-size: 13px;
}
.con-top {
    width: 100%;
	margin-top: 1em;
}
.contact {
    padding: 1.5em 0;
}
.contact h4 {
    margin-bottom: 0.3em;
}
.contact-left {
    padding: 0;
}
.app-left {
    padding: 0;
}
.app-right h3 {
    font-size: 19px;
	line-height:25px;
}
.app-right {
    padding: 0;
}
.banner-bottom {
    padding: 0.5em 0 0;
}
.banner-text p {
    font-size: 13px;
    margin: 1em auto 0 auto;
}
.banner-text h3 {
    font-size: 2.2em;
}
.app-right p {
    font-size: 13px;
}
.banner-bottom-grid p {
    font-size: 13px;
}
.banner-bottom-grid {
    margin-bottom: 1.5em;
    padding:0;
}
.glyphicon-th-large {
    font-size: 1.7em;
}
.services-icon {
    width: 100px;
    height: 100px;
    line-height: 111px;
}
.banner-text h3 {
    font-size: 2em;
}
ul.rout {
    padding: 0.5em;
}
.tra-top h6 a {
    font-size: 12px;
}
.bann-info1 {
    padding: 2em 0em 0em;
}
.bann-info {
    padding: 1em 0px;
}
.tra-top h4 {
    font-size: 18px;
}
.tra-top {
    margin-top: 1em;
}
.bus-tp {
    padding: 0.5em 0;
    background: #34ad00;
}
.bus-tp P {
    font-size: 13px;
    text-align: center;
    float: none;
    margin-bottom: 0.5em;
}
.bus-tp h2 {
    font-size: 15px;
    float: none;
    text-align: center;
}
.bus-btm li a {
    font-size: 13px;
}
.bus-midd h4 {
    font-size: 12px;
}
li.trav {
    width: 23%;
}
li.arriv {
    width: 17%;
    text-align: center;
}
li.seat {
    width: 22%;
    text-align: center;
}
li.fare {
    width: 20%;
    text-align: center;
}
.bus-midd h5 {
    font-size: 13px;
}
.blog-left {
    padding: 0;
}
.comments-list p {
    font-size: 13px;
}
.blog {
    padding: 1.5em 0;
}
.comments-list:nth-child(2) {
    margin: 1em 0;
    padding: 1em 0 1em;
}
.blog-right {
    margin-top: 1em;
    padding: 0;
}
.popular h3, .subscribe h3, .categories h3, .instagram h2, .tags h3 {
    padding: 0.5em;
}
.admin-right p {
    font-size: 13px;
}
.admin {
    padding: 1em;
    margin: 1em 0 1em;
}
.recent-comments-grid-right p {
    font-size: 13px;
}
.hotels-right {
    padding: 0;
}
.hotels-left {
    padding: 0;
}
.view1-sixth h2 {
    margin: 70px 0px 0px 0px;
}
.banner-2 h1 {
    padding: 2.7em 0 0;
}
.banner-2 {
    min-height: 160px;
}
.banner-3 {
    min-height: 130px;
}
.rt-left {
    width: 64%;
}
.rom-info h5 {
    font-size: 1.1em;
    text-align: center;
}
.rom-info h3 {
    font-size: 0.95em;
}
.rom-info p {
    font-size: 11px;
    line-height: 1.3em;
}
.rooms-top {
    min-height: 165px;
    padding: 4em 0 0;
}
.hotel-amenit li {
    font-size: 13px;
	width:50%;
}
.hotel-police p {
    font-size: 13px;
}
h4.sing {
    margin-bottom: 0.5em;
}
.hotel-amenit {
    margin-bottom: 2em;
}
.hotel-police {
    margin-bottom: 2em;
}
.footer-left {
    margin-top: 1em;
}
.details-left {
    width: 100%;
    padding: 0;
}
.details-middle {
    width: 100%;
    padding-left: 16px;
}
.details-middle li {
    font-size: 13px;
}
.details-middle p {
    font-size: 13px;
}
.selectroom_top {
    padding: 1em;
}
.selectroom-info ul {
    margin-top: 1em;
}
.selectroom_right p {
    font-size: 13px;
}
.selectroom_right h6 {
    font-size: 0.9em;
}
.selectroom_right h3 {
    font-size: 1.5em;
}
.grand {
    text-align: right;
    margin-top: 0.5em;
}
.tracking {
    padding: 2em 0;
}
.tracking-top, .tracking-bottom {
    padding: 1em 0.5em;
}
.tracking p {
    font-size: 13px;
}
.login-right input[type="submit"] {
    font-size: 12px;
}
.login-right input[type="text"], .login-right input[type="password"] {
    font-size: 12px;
}
.login-left ul li {
    font-size: 14px;
}
.writ {
    padding: 0 1em 1em;
}
.writ h4 {
    font-size: 1.4em;
}
.copy-right p {
    font-size: 13px;
}
.lightbox .box {
    min-width: 280px;
}
ul.set-1 {
    margin-left: 200px;
}
.login-left {
    width: 77%;
}
}
        .errorWrap {
    padding: 10px;
    margin: 0 0 20px 0;
    background: #fff;
    border-left: 4px solid #dd3d36;
    -webkit-box-shadow: 0 1px 1px 0 rgba(0,0,0,.1);
    box-shadow: 0 1px 1px 0 rgba(0,0,0,.1);

}
 .successWrap {
    padding: 10px;
    margin: 0 0 20px 0;
    background: #fff;
    border-left: 4px solid #4caf50;
    -webkit-box-shadow: 0 1px 1px 0 rgba(0,0,0,.1);
    box-shadow: 0 1px 1px 0 rgba(0,0,0,.1);
}
