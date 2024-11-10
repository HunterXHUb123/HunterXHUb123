/* ==UserStyle==
@name           kirka.io
@namespace      github.com/openstyles/stylus
@version        1.0.0
@description    A new userstyle
@author         Me
==/UserStyle== */
@-HASSAAN-document url-prefix("https://kirka.io/") {
    /* @import url(https://drive.google.com/uc?export=view&id=1ExijPyhKMZTdjSXSgnFUp71Yxt6yUCHP)
    ;} */
/*	Original CSS made by OnFire29
    Modified by NeverGonna#I0VR0Q (That's my kirka account)
    recomended Resolution: 1920x1080
    CSS origin: Nizzq#9235 */
@font-face {
    font-family: gamefont;
    src: url("https://raw.githubusercontent.com/MOF1/krunker_css/main/css/fonts/Steradian-Bold.otf");
}

* {
    font-family: gamefont;
}
    
/* fire kill icon */
.animate-cont {
    content: url(https://i.postimg.cc/y8Dh6SXH/Pngtree-purple-beautiful-moon-illustration-4618269.png);
    height: 100px;
    text-align: center;
    display: inline-block;
}
    
/* red buttons that I changed to purple*/
    
    .button[data-v-02c36fca]:after{--hover-color: #06bbbb}

/* borders around stuff */

.container[data-v-d54ab83a] {
    border: #06bbbb !important;
    background: #221c35 !important;
}

.select-regions-cont {   
    border: 1px solid #06bbbb !important;
    border-radius: 5px !important;
    background: #221c35 !important;
}

.bg[data-v-4c542c70] {
    border: 1px solid #06bbbb !important;
    border-radius: 5px !important;
    background: #221c35 !important;
}
    
.hub-container {
    border: 1px solid #06bbbb !important;
    border-radius: 5px !important;
    background: #221c35 !important;
}
    
.store {    
    border: 1px solid #06bbbb !important;
    border-radius: 5px !important;
    background: #221c35 !important;
}
    
.container-card[data-v-1bf1e387] {
    border: 1px solid #06bbbb !important;
    border-radius: 5px !important;
    background: #221c35 !important;        
}

.container[data-v-d54ab83a]{
    border: 1px solid #06bbbb !important;
    border-radius: 5px !important;
    background: #221c35 !important;
}
    
    
/* Hide Logo */
.interface .logo {
    content: url(https://i.postimg.cc/y8Dh6SXH/Pngtree-purple-beautiful-moon-illustration-4618269.png);
    margin-top: 20px;
    max-width: 200px;
    max-height: 200px;
}


/*	Ad Removal */
.ad-bottom,
.ad-left {
    visibility: hidden !important;
}
/*	CROSSHAIR */
.crosshair-static {
    visibility: visible !important;
    position: absolute;
    display:flex !important;
}
    
/* Animation */
@-webkit-keyframes glow {
    from {
        text-shadow: 0 0 5px #ffd9fd, 0 0 5px #ffc3fc, 0 0 5px #ffacfb, 0 0 5px #ff9dfa, 0 0 6px #fa77f3, 0 0 7px #ff71f7, 0 0 8px #ff6af7;
    }
}

@-webkit-keyframes animate{
    to {transform:translateY(30%);}
}

.heads .clan-tag {
	color: #292929;
    -webkit-animation: glow 2s ease-in-out infinite alternate;
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
    visibility: visible;
}

/* Background */
.interface .nickname:after {
    content: url(https://cdn.discordapp.com/attachments/842898946765881367/1064858033957646336/fire-emoji-402x512-8ma95d17.png) !important;
    margin-top: -2%;
  }
 .interface .nickname:before {
    content: url(https://cdn.discordapp.com/attachments/842898946765881367/1064858033957646336/fire-emoji-402x512-8ma95d17.png) !important;
    margin-top: -2%;
  }
    
.pattern-bg,
.bg-radial {
    display: none;
}

.interface .background{
    background: url(https://i.postimg.cc/NfYP0b5w/wallpaperflare-com-wallpaper-1.png) repeat !important;
    background-size: cover !important;
}

.end-modal {
    background: url(https://i.postimg.cc/NfYP0b5w/wallpaperflare-com-wallpaper-1.png) repeat !important;
}

/* Loading Scene*/
.loading-scene .progress {
    background: -webkit-gradient(linear, left top, right top, from(#84a1ff), to(#39ffd4)) !important;
    background: linear-gradient(to right, #84a1ff, #39ffd4) !important;
}

.loading-scene .name .label {
    -webkit-animation: glow 2s ease-in-out infinite alternate;
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

.loading-scene .players .level {
    color: #b84fff;
}

/* Join URL Button (For client only) */
.join-using-link {
    background: #292929 !important;
    border-radius: 0 !important;
    border: 4px solid #ffffff1c !important;
}

.join-using-link:active {
    background: #292929 !important;
}

#clientJoinButton {
	background: #ffacfb !important;
    border-radius: 0 !important;
    border: 4px solid #ffffff1c !important;
}

#clientJoinButton:active {
    background: #292929!important;
}

/* Stream 
.live-streams {
    background: rgba(55, 55, 55, .61);
    backdrop-filter: blur(5px);
    position: fixed;
    left: 95px;
    top: 80px;
    width: 300px !important;
    height: 1200px;
    border-left: 4px solid #ffffff1c;
    -webkit-transition: 1s;
    transition: 1s;
}

.live-streams:before {
    content: url(https://media.discordapp.net/attachments/523517791886770188/947364113770758194/pngfind.com-chevron-png-95287.png?width=30&height=30);
    position: fixed;
    right: 320px;
    top: 15px;
    transition: 0.2s;
}

.live-streams:hover:before {
    opacity: 0;
}

.live-streams:after {
    content: "CSS by NizzQ#9235";
    position: fixed;
    top: 505px;
    right: 115px;
}

.live-streams:hover {
    left: -115px;
}

.live-streams .head {
    display: none;
}

.live-streams .list {
    width: 180px;
    padding: 0 9px;
    overflow: visible;
}
*/
/* Login/Signup*/
.auth-form {
    margin-left: 0 !important;
    background: none !important;
    backdrop-filter: none;
    border: none !important;
    border-left: none !important;
    border-right: none !important;
    box-shadow: none !important;
    border-bottom: none !important;
    border-radius: 0 !important;
    width: 2500px !important;
    height: 118px !important;
}

.auth-form .btns button {
    transform: none !important;
    padding: 0px;
	left: -450%;
}

.auth-user .loading {
    background: rgba(55, 55, 55, .61);
	backdrop-filter: blur(5px);
	border: none;
	border-bottom: 5px solid #ffffff1c !important;
	border-radius: 0;
	width: 2500px;
    height: 118px !important;
}

.auth-user .loader-container {
	margin-right: 95% !important;
}

.button {
    -webkit-text-stroke: 0px !important;
}

.auth-form .btns button:hover {
    background-color: transparent !important;
    box-shadow: none !important;
}

.auth-form button,
.auth-form button .border-top,
.auth-form button .border-bottom{
    background: transparent !important;
    box-shadow: none !important;
}

.auth-form button .triangle {
    display: none;
}

.auth-form .text {
    font-size: 26px !important;
}

.auth-form button:hover {
    color: aqua;
}

.button:after {
    border: none;
}

/* Left Interface*/
.left-interface .profile {
    background: transparent;
    width: 2500px;
    height: 14px;
    margin-bottom: 0px;
}

.left-interface .progress-label {
    display: none;
    visibility: hidden;
}

.left-interface .progress-lvl {
    margin-bottom: 20px;
    visibility: visible;
}

.left-interface .progress-line {
    background: #ca91c3 !important;
    height: 17px;
}

.left-interface .progress {
    background: -webkit-gradient(linear, left top, right top, from(#84a1ff), to(#39ffd4)) !important;
    background: linear-gradient(to right, #84a1ff, #39ffd4) !important;
}

.left-interface .level {
    color: #b84fff;
}

.left-interface .avatar-info,
.left-interface .user-info{
    background: transparent !important;
	margin-left: -18px;
	border: none;
}
.left-interface .money {
    background: transparent !important;
	margin-left: -18px;
    margin-top: 3%;
	border: none;
}
.left-interface .avatar-info:hover,
.left-interface .user-info:hover {
    background: transparent;
}

/* Left icons */
.left-icons {
    background: transparent !important;
    left: 0 !important;
	border-radius: 0 !important;
}

.left-icons .icon-btn {
    background: transparent;
	border: none;
    width: 107px;
    border-radius: 0;
}

.left-icons .icon-btn .text-icon,
.left-icons .icon-btn svg {
    display: none;
}

.left-icons .icon-btn:nth-child(1) {
    background: url(https://i.postimg.cc/nrFCw6ck/Untitlp.png);
    background-size: 55px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 1.5rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
}

.left-icons .icon-btn:nth-child(1):hover {
    background: url(https://i.postimg.cc/nrFCw6ck/Untitlp.png);
    background-repeat: no-repeat;
    transform: scale(1.5)
}

.left-icons .icon-btn:nth-child(2) {
    background: url(https://i.postimg.cc/jdvzK4p2/Untitled-1-ppng.png);
    background-size: 55px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 1.5rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
}

.left-icons .icon-btn:nth-child(2):hover {
    background: url(https://i.postimg.cc/jdvzK4p2/Untitled-1-ppng.png);
    background-repeat: no-repeat;
    transform: scale(1.5)
}

.left-icons .icon-btn:nth-child(3) {
    background: url(https://i.postimg.cc/52FDDyrP/Untpecovered.png);
    background-size: 55px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 1.5rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
}

.left-icons .icon-btn:nth-child(3):hover {
    background: url(https://i.postimg.cc/52FDDyrP/Untpecovered.png);
    background-repeat: no-repeat;
    transform: scale(1.5)
}

.left-icons .icon-btn:nth-child(4) {
    background: url(https://i.postimg.cc/C1HgX5Ry/Untitledu-Recovered.png);
    background-size: 55px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 1.5rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
}

.left-icons .icon-btn:nth-child(4):hover {
    background: url(https://i.postimg.cc/C1HgX5Ry/Untitledu-Recovered.png);
    background-repeat: no-repeat;
    transform: scale(1.5)
}

.left-icons .icon-btn:nth-child(5) {
    background: url(https://i.postimg.cc/wvdzwLTc/Untitlel1-Recovered.png) ;
    background-size: 55px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 1.5rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
}

.left-icons .icon-btn:nth-child(5):hover {
    background: url(https://i.postimg.cc/wvdzwLTc/Untitlel1-Recovered.png);
    background-repeat: no-repeat;
    transform: scale(1.5)
}

.left-icons .icon-btn:nth-child(6) {
    background: url(https://i.postimg.cc/B6sWT3Mm/Untitled-1-Recovered.png) ;
    background-size: 65px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 1.2rem !important;
    background-position-y: 0.5rem !important;
    transition: 0.3s;
}

.left-icons .icon-btn:nth-child(6):hover {
    background: url(https://i.postimg.cc/B6sWT3Mm/Untitled-1-Recovered.png);
    background-repeat: no-repeat;
    transform: scale(1.5)
}

.left-icons .icon-btn:nth-child(7) {
    background: url(https://i.postimg.cc/GtMZJ7K4/Untitled-1-Recovered.png) ;
    background-size: 55px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 1.5rem !important;
    background-position-y: 0.1rem !important;
    transition: 0.3s;
}

.left-icons .icon-btn:nth-child(7):hover {
    background: url(https://i.postimg.cc/GtMZJ7K4/Untitled-1-Recovered.png);
    background-repeat: no-repeat;
}

.coin-icon {
    padding-right: 10px !important;

}

/* Right Interface */
.right-interface {
	padding-top: 20px;
}

.soc-group:nth-child(1),
.soc-group:nth-child(2) {
	background: transparent !important;
	border: none;
    visibility: hidden;
}

.soc-group:nth-child(1):hover,
.soc-group:nth-child(2):hover {
	background: none !important;
	transform: scale(1.5);
    visibility: hidden;
}

.right-interface .settings {
	background: transparent;
	border: none;
	width: 20px !important;
	transition: 0.3s;
    z-index: 2;
} 

.right-interface .settings:hover {
	background: none;
	transform: scale(1.5);
}

.right-interface {
    z-index: 999 !important;
}
/*
.soc-group:nth-child(2) {
    background: url(https://media.discordapp.net/attachments/523517791886770188/947500791365787729/monitor-512.png) !important;
    background-repeat: no-repeat !important;
    background-size: 50px !important;
    background-position-x: 1rem !important;
    background-position-y: 1rem !important;
	border: none;
    position: fixed;
    right: 80px;
    top: 12px;
}

.soc-group:nth-child(2):hover {
    background: url(https://media.discordapp.net/attachments/523517791886770188/947500791365787729/monitor-512.png) !important;
    background-repeat: no-repeat !important;
    background-size: 50px !important;
    background-position-x: 1rem !important;
    background-position-y: 1rem !important;
    transform: scale(1.2);
}

.soc-group:nth-child(2) svg {
    opacity: 0;
}
*/

/* Daily Quest */
#dailyQuests {
    background-color: #292929 !important; /* Ensures background color is transparent */
    background-image: none !important; /* Removes any background images */
    border: none;
    border-radius: 0;
    z-index: -1 !important;
    overflow: auto;
}

.quest {
    background-color: #292929 !important; /* Removes background color */
    background-image: none !important; /* Removes any background images */
}

#dailyQuests, #dailyQuests * {
    background: none !important; /* Remove background color and images for all child elements */
    background-color: #292929 !important;
    background-image: none !important;
    border: none !important;
    border-radius: 0 !important;
}

.quest {
    background: none !important; /* Remove background color and images */
    background-color: transparent !important;
    background-image: none !important;
}

#dailyQuests {
	background: #292929 url('https://i.postimg.cc/8CsR5fRG/p.pngyour-image-url-here') no-repeat center center;
    background-size: cover;
    border: none;
	border-radius: 0;
	z-index: -1 !important;
	overflow: auto;
}

.quest {
	background: #292929 !important;
}

#dailyQuests .tip {
	background: #292929 url('https://i.postimg.cc/8CsR5fRG/p.png') no-repeat center center;
    background-size: cover;
	border-radius: 0 !important;
	margin-left: 15px;
}

.quest .progress-line {
	background: #ca91c3;
}

#dailyQuests .reward {
	background: #ca91c3;
}

.quest .amount {
	color: #eee5f1;
}

.quest .progress2 {
	color: #eedeed;
}

.quest .progress-line .progress {
	background: -webkit-gradient(linear, left top, right top, from(#e6dded), to(#292929)) !important;
    background: linear-gradient(to right, #292929, #292929) !important;
}


/* Container */
.container {
    background: #292929 !important;
    box-shadow: none !important;
    border-radius: 0 !important;
}

.container-card {
    background: #292929 !important;
    box-shadow: none !important;
    border: none !important;
    border-radius: 0 !important;
}

.loader  {
	background: #292929 !important;
	border: none !important;
}

.background {
    background: transparent !important;
    border-radius: 0;
}

.tabs {
    background: transparent !important;
    border-bottom: none !important;
    box-shadow: none !important;
    border-right: none !important;
}

.tab {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}

.tab:hover,
.nav:hover {
	color: #1e1e1e !important;
}

.tab.active {
	color: #ffffff;
	border-bottom: 3px solid #ffffff;
}

.active-tab {
	color: #ffffff !important;
	border-bottom: 3px solid #ffffff;
}

.nav.active {
	color: #ffffff;
}

.head-text {
    background: transparent !important;
    box-shadow: none !important;
}

.add-friends,
.top-items {
    background: transparent !important;
}

.limit {
    border-left: none !important;
}

.top-bar,
.close,
.home,
.name-page,
.select-mods-cont hr,
.info-icon,
.container button .border-top,
.container button .border-bottom {
    display: none !important;
}

.reset-time,
.info-awards,
.news {
    background: transparent !important;
    box-shadow: none !important;
}

.settings .box {
    background: transparent;
    border: none;
}

    .select-mods-cont {
    border: 1px solid #457070 !important;
    border-radius: 5px !important;
    background: #221c35 !important;
    overflow: visible;
	z-index: 999 !important;
    width: 400px !important;
    height: 770px !important;
    left: -400px !important;
    top: -470px !important;
}
    
    .card-cont settings card-1 {top: -100px}

    .settings {
    border: 1px solid #06bbbb !important;
    border-radius: 5px !important;  
}
    
    .info-key-cont-enter{display:none}
    
    .select-mods-maps {
    position:absolute; left:0px; top:180px;
}
    
.interface.text-2 > .play > div > .play-content-up > div > div > .select-mods-maps {
    display: grid;
    text-align: left;
    padding: 0 0px;
    width: 100% !important;
    height: 75% !important;
}

.select-regions-cont {
    border: 1px solid #292929 !important;
    border-radius: 0
        px !important;
    background: #292929 !important

}

    .select-regions-cont[data-v-3613f89e] {height: 165px; width: 130px; position: fixed; left: 25%; top: -30%;}

.container button {
    background: #221c35 !important;
    border-radius: 0 !important;
    transform: none !important;
}

.container button {
    background: rgb(68, 68, 68) !important;
    border-radius: 0 !important;
    transform: none !important;
}

.container button .border-top,
.container button .border-bottom {
    display: none;
}

.text {
    transform: none !important;
}

.settings .header,
.vm--container .cont .head {
	color: #dc91d8 !important;
}

.settings .label {
	color: #ca91c3 ;
}

.select-regions-regions .region:nth-child(1) span,
.select-regions-regions .region:nth-child(2) span,
.select-regions-regions .region:nth-child(3) span,
.select-mods-mods .mod:nth-child(1) span,
.select-mods-mods .mod:nth-child(2) span {
	visibility: hidden;
}

.select-regions-regions .region:nth-child(1) span:before,
.select-regions-regions .region:nth-child(2) span:before,
.select-regions-regions .region:nth-child(3) span:before,
.select-mods-mods .mod:nth-child(1) span:before,
.select-mods-mods .mod:nth-child(2) span:before {
	visibility: visible;
}

.select-regions-regions .region:nth-child(1) span:after{
	visibility: visible;
	content: "NA";
	margin-left: -130px;
}

.select-regions-regions .region:nth-child(2) span:after{
	visibility: visible;
	content: "EU";
	margin-left: -60px;
}

.select-regions-regions .region:nth-child(3) span:after{
	visibility: visible;
	content: "SEA";
	margin-left: -32px;
}

.select-mods-mods .mod:nth-child(1) span:after{
	visibility: visible;
	content: "FFA";
	margin-left: -40px;
}

.select-mods-mods .mod:nth-child(2) span:after{
	visibility: visible;
	content: "TDM";
	margin-left: -47px;
}

/* Profile */
.profile .statistics,
.profile .progress,
.profile .k-d,
.card-profile {
    background: transparent !important;
    box-shadow: none !important;
}

.profile .you {
    visibility: hidden;
}

.profile .progress-line {
    background: #4f4e4e00;
}

.profile .progress-level-value,
.stat-name {
    color: white !important;
}

.profile .progress {
    background: -webkit-gradient(linear, left top, right top, from(#fcd1fc), to(#dc91d8)) !important;
    background: linear-gradient(to right, #171717, #171717) !important;
}

.heads .levels {
    display: none;
    color: #b84fff;
}

.stat-value {
    color: #87898c !important;
}

.news img {
    border-radius: 0 !important;
}

.news .info {
    background: #221c35 !important;
}

.news .info-content {
    background: #221c35 !important;
}

.info h1 {
    background: #221c35 !important;
}

.changelog-item {
    background: transparent !important;
    border: none !important;
}

/* Inventory */
.tab-bar,
.subject,
.inventory .avatar {
    background: #29292900 !important;
}

.subjects,
.gun {
    background: #29292900 !important;
    border: none !important;
}

.inventory .avatar-head {
    display: none;
}

.inventory .bottom {
    background: transparent !important;
    backdrop-filter: blur(2px) !important;
    background-image: linear-gradient(to left, #39ffd400, #39ffd417) !important;
}

/* Play Content */
.play-content .select-region,
.play-content .select-mod {
    background: #292929;
    border-radius: 0;
    border: 4px solid #ffffff1c;
}

.play-content .select-region:hover {
    background: #0f0118;
    backdrop-filter: blur(5px);
}

.play-content .select-mod:hover {
    background: #38353a;
}

#play-btn {
    background: #fff !important;
    color: #292929 !important;
    width: 310px;
    box-shadow: none !important;
    transform: none !important;
    transition: all .25s linear;
}

#play-btn:hover {
    background: #dc91d8 !important;
    color: #020003 !important;
}

#play-btn .border-top,
#play-btn .border-bottom {
    background: none !important;
}

.triangle {
    display: none !important;
}
/* create Content */
.create-content .select-region,
.create-content .select-mod {
    background: #292929;
    border-radius: 0;
    border: 4px solid #ffffff1c;
}

.create-content .select-region:hover {
    background: #0f0118;
    backdrop-filter: blur(5px);
}

.create-content .select-mod:hover {
    background: #38353a;
}

#create-btn {
    background: #fff !important;
    color: #292929 !important;
    width: 160px;
    box-shadow: none !important;
    transform: none !important;
    transition: all .25s linear;
}

#create-btn:hover {
    background: #dc91d8 !important;
    color: #020003 !important;
}
/* join Content */
.join-content .select-region,
.join-content .select-mod {
    background: #292929;
    border-radius: 0;
    border: 4px solid #ffffff1c;
}

.join-content .select-region:hover {
    background: #0f0118;
    backdrop-filter: blur(5px);
}

.join-content .select-mod:hover {
    background: #38353a;
}

#join-btn {
    background: #fff !important;
    color: #292929 !important;
    width: 160px;
    box-shadow: none !important;
    transform: none !important;
    transition: all .25s linear;
}

#join-btn:hover {
    background: #dc91d8 !important;
    color: #020003 !important;
}

#join-btn .border-top,
#join-btn .border-bottom {
    background: none !important;
}

#create-btn .border-top,
#create-btn .border-bottom {
    background: none !important;
}
/* ready Content */
.ready-content .select-region,
.ready-content .select-mod {
    background: #292929;
    border-radius: 0;
    border: 4px solid #ffffff1c;
}

.ready-content .select-region:hover {
    background: #0f0118;
    backdrop-filter: blur(5px);
}

.ready-content .select-mod:hover {
    background: #38353a;
}

#ready-btn {
    background: #fff !important;
    color: #292929 !important;
    width: 160px;
    box-shadow: none !important;
    transform: none !important;
    transition: all .25s linear;
}

#ready-btn:hover {
    background: #fa77f3 !important;
    color: #020003 !important;
}

#ready-btn .border-top,
#ready-btn .border-bottom {
    background: none !important;
}
/* leave Content */
.leave-content .select-region,
.leave-content .select-mod {
    background: #292929;
    border-radius: 0;
    border: 4px solid #ffffff1c;
}

.leave-content .select-region:hover {
    background: #0f0118;
    backdrop-filter: blur(5px);
}

.leave-content .select-mod:hover {
    background: #38353a;
}

#leave-btn {
    background: #fff !important;
    color: #292929 !important;
    width: 160px;
    box-shadow: none !important;
    transform: none !important;
    transition: all .25s linear;
}

#leave-btn:hover {
    background: #fa77f3 !important;
    color: #020003 !important;
}

#leave-btn .border-top,
#leave-btn .border-bottom {
    background: none !important;
}
    
/* Leaderboard */
.leaders .clan-tag {
    -webkit-animation: glow 2s ease-in-out infinite alternate;
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

.lvl-leader {
    color: white !important;
}

.list-cont,
.list-champions,
.top-items .items .item,
.bottom-items .item,
.leaderboard-cont .items {
    background: transparent !important;
    box-shadow: none !important;
}

.list-players .top-items {
    box-shadow: none !important;
}

/* Clan */
.clans,
.clans .items .item,
.my-clan .list-container .list .item .item-content {
    background: transparent !important;
}

.my-clan .card-cont,
.my-clan .list-container,
.champions-list {
    background: transparent !important;
    box-shadow: none !important;
}

.my-clan .card-cont .name {
	color: #292929;
	-webkit-animation: glow 2s ease-in-out infinite alternate;
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

.my-clan .champions-league,
.my-clan .champions-scores,
.my-clan .all-scores-label {
	color: white !important;
}

.my-clan .champions-values,
.my-clan .all-scores-value,
.my-clan .description {
	color: whitesmoke;
}

/* Market */
.bottom-subj .count {
    background: transparent;
}

/* Esc Interface*/
.esc-interface {
    backdrop-filter: blur(5px);
}

.esc-interface .head-right button,
.esc-interface .head-right button .border-top,
.esc-interface .head-right button .border-bottom {
    background: #fad0fa !important;
    box-shadow: none;
    border-radius: 0;
}

.esc-interface .head-right button:hover {
    background: #fad0fa !important;
    border-bottom: 5px solid #fad0fa;
}

.esc-interface .left-container .player {
    background: rgb(255, 255, 255);
    background-image: linear-gradient(to left, #39ffd408, #39ffd440) !important;
}

.esc-interface .right-container {
    background: rgb(255, 255, 255) !important;
}

.esc-interface .player .label {
    -webkit-animation: glow 2s ease-in-out infinite alternate;
    
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

.esc-interface .primary {
	color: #ffffff !important;
}

.esc-interface .level{
	color: #292929;
}

.continue {
	background: rgb(68, 68, 68) !important;
	box-shadow: none !important;
}

.continue .border-top,
.continue .border-bottom {
	background: transparent !important;
	box-shadow: none !important;
}

/* HUD */
.mini-map-cont .name,
.desktop-game-interface .info-key-cont,
.list-weapons,
.hp-title,
.mWwn,
.instruction {
    display: none !important;
}

.cont-hp {
    background: transparent !important;
}

.hp {
    margin-right: 20%;
}

.hp-progress {
    background: #292929 !important;
}

.desktop-game-interface .state {
    position: fixed;
    width: 500px !important;
    top: 93%;
    left: 37% !important;
}

.cont-endurance {
    margin-left: 1.5%;
    background: transparent !important;
    border: #1e1e1e;
}

.endurance-progress {
	background: -webkit-gradient(linear, left top, right top, from(#b84fff), to(#b84fff)) !important;
    background: linear-gradient(to right, #b84fff, #b84fff) !important;
}

.weapons-cont {
    position: fixed;
    width: 300px;
    top: 95%;
    left: 5%;
    margin-top: -100px;
    margin-left: 252px ;
}

.ammunition {
    display: inline-block;
    position: fixed;
    left: calc(38% + 188px);
  }

.kill-death {
    margin-top: 60px;
    margin-left: 2px;
}

.kill-death .kill,
.kill-death .death {
    background: transparent;
    box-shadow: none;
}

.state-cont .timer {
    position: fixed;
    top: 18px;
    background: transparent !important;
    box-shadow: none !important;
    font-size: 50px;
}

/* In Game Leaderboard */
     /* General Background */
.tab-info {
    background: rgba(55, 55, 55, .61) !important;
    box-shadow: none !important;
    border-radius: 0 !important;
    border: 5px solid #06bbbb;
    }
    
    .tab-info .head {
    display: none;
    }
    
    .tab-info .player {
    background: transparent !important;	
    }
    
    .tab-info .primary {
    color: white !important;
    }
    
    .tab-info .nickname,
    .tab-info .player-right {
    color: #87898c;
    }
    
    .tab-info .list {
    color: white;
    margin: 0 !important;
    }
    
    .tab-info .list .list-value:nth-child(1),
    .tab-info .list .list-value:nth-child(2),
    .tab-info .list .list-value:nth-child(3) {
    visibility: hidden;
    }
    
    .tab-info .list .list-value:nth-child(1):after {
    visibility: visible;
    content: "H-K";
    margin-left: -36px;
    }
    
    .tab-info .list .list-value:nth-child(2):after {
    visibility: visible;
    content: "H-D";
    margin-left: -36px;
    }
    
    .tab-info .list .list-value:nth-child(3):after {
    visibility: visible;
    content: "H-S";
    margin-left: -49px;
    }

    .achive-cont{
        content: url(https://i.postimg.cc/NGTyR84f/apparently-alot-of-people-really-like-my-scopes-so-heres-v0-wnkar0ztz1981.png ) !important;
        position: absolute !important;
        right: 46% !important;
        width:10em; 
        height:10em;
        }

.kill-bar-item {
	background: rgba(55, 55, 55, .61) !important;
	border: 3px solid black;
}

.kill-bar-item .name {
	color: #06bbbb;
}

.kill-bar-item .name-kill {
	color: #b84fff;
}

/* Chat */

.chat {
    visibility: visible;
    background-image: url('your-image-url-here');
    background-size: cover; /* Adjusts the size of the image */
}

.messages .messages-cont {
    visibility: visible;
    background-image: url('your-image-url-here');
    background-size: cover; /* Adjusts the size of the image */
}

/*    
.chat {
    margin-bottom: -53px;
    border-radius: 5px;
}

.chat .input-wrapper {
    top: 400px !important;
    width: 103%;
    height: 15px;
}

.chat .name {
    color: white;
}

.message{
    color: #87898c !important;
}

.message .lvl {
    color: #b84fff;
} 

/* End Screen */
.end-modal .bottom {
    display: none;
}

.end-modal .progress-line {
    background: #4f4e4ead;
}

.end-modal .progress {
    background: -webkit-gradient(linear, left top, right top, from(#ffffff), to(#ffffff)) !important;
    background: linear-gradient(to right, #ffffff, #ffffff) !important;
}

.end-modal .team-list-players .card-cont:nth-child(1),
.end-modal .team-list-players .card-cont:nth-child(2),
.end-modal .items {
    background: transparent !important;
    box-shadow: none !important;
}

.end-modal .team-list-players .label {
    background: transparent;
}

.end-modal .label-text,
.end-modal .points,
.end-modal .lvl-leader {
    color: white;
}

.end-modal .chat {
    margin-bottom: -53px;
    border-radius: 5px;
}

.end-modal .chat .input-wrapper {
    top: 400px !important;
    width: 103%;
    height: 130px;
}

.end-modal #WMNn {
    width: 310px;
    margin-left: 20px;
}

.end-modal .team-list-players .list .player {
    background: transparent;
}

.end-modal .clan-tag {
    -webkit-animation: glow 2s ease-in-out infinite alternate;
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

/* Reward Container */
.progress,
.lvl,
.progress-helper {
    background: -webkit-gradient(linear, left top, right top, from(#fad0fa), to(#fad0fa)) !important;
    background: linear-gradient(to right, transparent, transparent) !important;
}

.buy-btn {
	display: none !important;
}

.level-head {
    display: none !important;
    color: #fad0fa;
}

.decor-bg {
	display: none;
}

/* Inputs */
.private-btn > span {
	content: url(https://media.discordapp.net/attachments/523517791886770188/953239076457316382/openlock.png);
	position: fixed;
	left: 25px;
	width: 40px;
}

.private-btn > input:checked + span {
    content: url(https://media.discordapp.net/attachments/523517791886770188/953239093955948544/lock.png);
}

.custom-checkbox > span:before {
    border-radius: 50px;
    background-color: white;
    border: none;
}

.custom-checkbox > input:checked + span:before {
    background-color: rgb(9, 148, 148);
}

input {
    background: white !important;
    color: black !important;
    border-radius: 10px !important;
}

.selected {
    background: #b84fff;
}

.items {
    background: #292e39 !important;
    box-shadow: none !important;
}

.settings .input {
    background: transparent !important;
    border: none !important;
    box-shadow: none !important;
    color: white !important;
}

.copy button {
	background: #b84fff !important;
	box-shadow: none !important;
}

.copy .border {
	display: none;
}
