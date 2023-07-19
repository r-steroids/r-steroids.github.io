body {
    background: #fff;
    font-family: "Calibri", Verdana, sans-serif;
}

.comments-page .sitetable.nestedlisting > .thing.id-t1_cmn5xjb, .comments-page .sitetable.nestedlisting > .thing.id-t1_cmoioub, .comments-page .sitetable.nestedlisting > .thing.id-t1_cmov5mu {
    background-color: #ddffdd;
    border: 2px solid green !important;
    order: -1;
}
.res-commentBoxes .comment {
    margin-left: 10px !important;
}
.comment, .content .details {
    margin-left: 10px;
}
body, div, dl, dt, dd, ul, ol, li, h1, h2, h3, h4, h5, h6, pre, form, fieldset, input, p, blockquote, th, td, iframe {
    margin: 0;
    padding: 0;
}
# header {
    background-color: #fff;
    height: 120px;
    margin-bottom: 20px;
    position: relative;
    padding-bottom: 7px;
}
.submit-text:before, .submit-link:before {
    background-color: #e1ba57;
    border-radius: 2px;
    color: #fff;
    content: "Read the rules first!";
    font-size: 16px;
    height: 0;
    left: 20px;
    opacity: 0;
    padding: 7px;
    position: relative;
    top: 28px;
    transition: top 0.35s ease 0s, opacity 0.31s linear 0s, left 0.35s ease 0s;
    width: 0;
    z-index: 96;
}
.submit-text, .submit-link {
    margin-top: -20px;
}
body, div, dl, dt, dd, ul, ol, li, h1, h2, h3, h4, h5, h6, pre, form, fieldset, input, p, blockquote, th, td, iframe {
    margin: 0;
    padding: 0;
}
.res .RES-keyNav-activeElement {
    background-attachment: scroll;
    background-clip: border-box;
    background-color: #fafafa !important;
    background-image: linear-gradient(to right, #fff 0%, #fafafa 8%, #fafafa 100%);
    background-origin: padding-box;
    background-position: 0 0;
    background-repeat: repeat;
    background-size: auto auto;
    padding-left: 19px;
}

textarea {
    background-color: #fff;
}

/* header list styling
======================================*/

# sr-header-area {
    background-color: #000000 !important;
    border-bottom: 1px solid #333;
    color: #FFFFFF !important;
    display: block !important;
    font-size: 10px;
    padding: 5px 0 6px;
}

ul.sr-bar li a, .separator,
a.subbarlink, a.undefined,
# srDropdown #srDropdownContainer a {
    color: #FFFFFF !important;
}

ul.sr-bar li a:hover, 
a.subbarlink:hover, a.undefined:hover,
# srDropdown #srDropdownContainer a:hover {
    color: #000 !important;
    text-decoration: none;
}

div.sr-bar .RESShortcutsCurrentSub {
    color: #fff !important;
    font-weight: bold !important;
}

/* main header */

# header-bottom-left {
    background: #000 url(%%participate-educate-grow%%) no-repeat 0% 100%;
    height: 120px;
    width: 100%;
}

# header-bottom-left .redditname {
    position: absolute;
    top: 105px;
    left: 320px;
}

# header-bottom-left .redditname a {
    /*background: url(%%snoo-years2%%);*/
    width: 75px;
    height: 20px;
    display:block;
text-indent: -9999px;
}

/* tab menu to choose how topics are displayed
======================================*/

# header-bottom-left > ul.tabmenu {
    position: absolute;
    bottom: -53px !important;
    left: 0px !important;
    background: #1baeed url(%%nav-bg%%) repeat-x;
    width: 100%;
    height: 30px;
    padding-left: 15px;
}

# header-bottom-left > ul.tabmenu li {
    margin-right: 5px;
    padding-top: 10px;
}

# header-bottom-left > ul.tabmenu li:last-of-type {
    margin-right: 0;
}

# header-bottom-left > ul.tabmenu a {
    background: none;
    font-size: 16px;
    position: relative;
    top: 4px;
    text-transform: capitalize;
    display: inline-block;
}

.choice { text-transform: capitalize!important; }

# header-bottom-left > ul.tabmenu li a {
    color: #fff;
}

# header-bottom-left > ul.tabmenu li a:hover {
    text-decoration: underline;
}

# header-bottom-left > ul.tabmenu li.selected {
    border: none!important;
}

.tabmenu li.selected a { border: none; }

# header-bottom-left > ul.tabmenu li.selected a {
    border: none!important;    
}

/* wiki draw-to image 
======================================*/

# header-bottom-left > ul.tabmenu li a[href*="/wiki/"] {
    position: relative;
}

# header-bottom-left > ul.tabmenu li a[href*="/wiki/"]:before {
    
    height: 74px !important;
    position: absolute;
        top: -90px !important;
        left: -325px !important;
    width: 430px !important;
    z-index: 100;
   
}

# header-img.default-header,
# header-bottom-left a[id*="img"] {
    visibility: hidden;
}

/* styling for the user bar 
======================================*/

div#header-bottom-right {
   background: none !important;
   color: #000000 !important;
   border-right: none; 
   border-bottom: none;
   border-radius: 0px;
   font-size: 12px;
   position: absolute !important;
   top: 30px !important;
   padding: 5px 0 0;
}

div#userbarToggle, div#header-bottom-right.res-navTop {
   background: #000000 !important;
   color: #ffffff !important;
   border-bottom: 1px solid #000000;
   border-right: none; 
   border-top: none;
   border-radius: 0px;
   padding: 5px 0 2px;
}

div#header-bottom-right.res-navTop {
   padding: 5px 8px 6px;
}

div#header-bottom-right span.user {
    color: #000000;
    padding-left: 20px;
}

div#userbarToggle.userbarHide {
    border-top: none;
    border-left: 5px solid #000000;
    border-right: 1px solid #000000;
    border-bottom: 0;
    padding: 1px 10px 0 5px !important;
    position: absolute !important;
    top: 0;
    left: 0;
}

div#header-bottom-right a {
   color: #FFFFFF !important;
}

div#header-bottom-right a.login-required, div#remember-me a {
   color: #fff !important;
}

/* mail icon styling
======================================*/

# mail {
    position: relative;
    display: inline-block;
    text-indent: -9999px;
    overflow: hidden;
    width: 15px; /*These values for the standard mail icon, customize to your own*/
    height: 15px;
    padding: 0;
}

# mail.havemail {
    background: url(%%mail%%);
}

# mail.nohavemail {
    background: url(%%nomail%%);
}

/* comment warning
 * ======================================*/

.commentarea .usertext-edit textarea {  
    background: #ffffff url(%%post-warning%%) no-repeat;
    background-position: center; 
   
}

.commentarea .usertext-edit textarea:active,
.commentarea .usertext-edit textarea:focus { 
    background: #ffffff;
}

.roundfield-content>.usertext textarea { 
    background-image: url(%%post-warning%%); 
    background-repeat: no-repeat; 
    border: 1px solid #ccc; 
}

.roundfield-content>.usertext textarea:focus { 
    background-position: -504px -104px; 
}

/* content area where topics are shown 
 * ======================================*/

# siteTable .thing {
    background-color: #fff !important;
    border: 1px solid #cdcdcd !important;
    padding: 10px 10px 10px 0 !important;
    margin: 0 320px 5px 10px;
    width: auto !important;
   
}

.res-nightmode #siteTable .thing { background: #111!important; border: 1px solid #000 !important; }

# siteTable .thing:last-of-type {
    margin: 0 !important;
}

.thumbnail.self {
    background-image: url(%%testosterone%%);
    opacity: 1;
    background-position: 5px 10px;
    background-repeat: no-repeat;
    padding-right: 5px;
    height: 57px;
}

.res-nightmode .thumbnail.self {
    background-image: url(%%testosterone-night%%);
    opacity: 1;
    background-position: 0px 10px;
    background-repeat: no-repeat;
}

/* Voting arrows
 *======================================*/ 
.arrow.up, .res-nightmode .arrow.up {
    background-image: url(%%up%%); 
    background-position: 0px 0px; 
    height: 15px; 
    width: 15px; 
}

.arrow.upmod, .res-nightmode .arrow.upmod { 
    background-image: url(%%up-click%%); 
    background-position: 0px 0px; 
    height: 15px; 
    width: 15px;  
}

.arrow.down, .res-nightmode .arrow.down {
    background-image: url(%%down%%); 
    background-position: 0px 0px; 
    height: 15px; 
    width: 15px; 
}

.arrow.downmod, .res-nightmode .arrow.downmod { 
    background-image: url(%%down-click%%); 
    background-position: 0px 0px; 
    height: 15px; 
    width: 15px; 
}

/*submitter and moderator styles
======================================*/

div.commentarea .author.submitter {
   background-color: #060606 !important;
   color: #fff !important;
   padding: 0px 3px;
   border-left-color: #FF0000;
}

/*This allows arrows wider than 15px just change it to the width of your arrows
======================================*/
.midcol  { 
    width: 25px !important; 
}

/* changes to the submit page styling 
 */

.formtabs-content {
    border-top: 4px solid #060606 !important;
    padding-top: 10px;
    width: 520px;
}

.tabmenu.formtab .selected a {
    background-color: #060606 !important;
    border: medium none;
    color: white;
    font-size: 130%;
}

.tabmenu.formtab a {
    background-color: #efefef !important;
    border: 1px solid #060606 !important;
    font-weight: normal;
    outline: medium none;
    padding: 0 12px;
    vertical-align: bottom;
}

# text-desc, #link-desc {
    background-color: #ce0101 !important;
    border: 1px solid #cdcdcd !important;
    color: #fff !important;
}

# text-desc::after{
    display: block;
    margin-top: 1em;
    content: " ANY source discussion will result in a ban. Message the mods if in doubt. If your post can be answered easily by the wiki it will be removed.";
    font-weight: bold;
    font-size: 200%;
    text-align: center;
}

# link-desc::after {
    display: block;
    margin-top: 1em;
    content: " ANY linking to sources will result in a ban. Message the mods if in doubt. If your post can be answered easily by the wiki it will be removed.";
    font-weight: bold;
    font-size: 200%;
    text-align: center;
}

div#title-field.roundfield,
div#text-field.roundfield,
div#url-field.roundfield,
div#reddit-field.roundfield,
div.roundfield.info-notice {
    background-color: #efefef !important;
    border: 1px solid #cdcdcd !important;
    border-radius: 0;
}

/* sidebar
======================================*/

.side {
    background: none;
    color: #060606;
    display: block !important;
    margin: 38px 0 10px 0;
    padding: 0 5px;
    width: 300px;
}

.side .spacer {
    width: 300px;
}

# search {
    width: 300px;
}

ul.flat-vert.icon-menu.hover li a {
    background-color: #efefef;
}

div.leavemoderator, form.toggle.leavecontributor-button {
    background-color: #efefef;
} 

div.linkinfo {
    background-color: #efefef !important;
    border: 1px solid #060606 !important;
}

div.titlebox {
    margin-top: 105px;
}

/* fixes the submit button
======================================*/

.sidebox.submit.submit-link { 
    position: absolute; 
    width: 300px; 
    top: 310px; /*Change this to position it*/
}

div.morelink a {
    background: url(%%Submit1%%) no-repeat;
    height: 124px;
    text-indent: -9999em;
    overflow: hidden !important;
    width: 300px;
}

div.morelink a:hover {
    background: url(%%Hover1%%) no-repeat;
    height: 124px;
    text-indent: -9999em;
    overflow: hidden !important;
    width: 300px;
}

/*.sidebox.submit:hover:after {
    color: #fff;
    display: block;
    position: absolute;
    width: 290px;
    top: 130px;
    padding: 11px 6px 6px 6px;
    background: #ce0101;
    color: #fff;
    font-size: 14pt;
    text-align: center;
    content: "Any source discussion will result in a ban. Message the mods if in doubt."
}*/

.sidebox.submit.submit-link { 
    visibility: hidden;
}

/* Kills the community button/nub/spacer
======================================*/

.sidebox.create .morelink {
    display: none;
}

.sidebox.create .spacer {
    display: none;
}

.sidebox.submit .spacer a, .sidebox.create .spacer a {
    display: none;
}
.morelink .nub, .morelink .nub:hover {
    display: none;
}

/* Kills the created by section
======================================*/

.titlebox .bottom {
    display: none;
    visibility: hidden;
}

/* sidebar dropdown menus 
======================================*/

.titlebox .md ul {
    margin: 0;
    padding-left: 0px !important;
}

.titlebox ul li {
    width: 274px;
    background-color: #fff;
    border: none;
    color: #000;
    display: none;
    padding: 4px 4px 4px 4px;
    margin: 0 0 -1px 0;
    text-align: left;
    border: 1px solid #efefef !important;
    font-size: 14px !important;
}

.titlebox ul li:hover {
    background-color: #efefef;
    color: #060606;
}

.titlebox ul li:nth-child(1) {
    display: block;
    font-weight: 300;
    background-color: #000000;
    color: #fff;
    display: inline-block;
    border: 1px solid #060606 !important;
    font-size: 15px;
    padding: 4px 4px 4px 4px;
}

.titlebox ul li:nth-child(1):hover {
    border: 1px solid #3167B5 !important;
    background-color: #3167B5;
    color: #fff;
}

.titlebox ul:hover > li {
    display: block;
}

.titlebox ul li a {
    color: #ce0101;
}

.titlebox ul li a:hover {
    color: #ce0101;
}

.side .titlebox ul ~ p {
    text-indent: -9999em !important;
    margin-top: -10px !important;
    overflow: hidden !important;
    visibility: hidden;
}

.side .titlebox hr {
    border: none;
    margin-bottom: 10px;
}

/* changes the text for the subscribers section 
======================================*/

.subscribers .word, .users-online .word {
    display:none;
}

.subscribers .number:after { 
    content: " Chemically Engineered Users"
}
.users-online .number:after { 
    content: " users here now" 
}

/* Table Styling
======================================*/

.wiki-page-content thead,
.usertext-body .md thead {
    background-color: #060606;
    color: #fff;
}

.wiki-page-content tbody tr:nth-of-type(even),
.usertext-body .md tbody tr:nth-of-type(even) {
    background-color: #fff;
}

.wiki-page-content tbody tr:nth-of-type(odd),
.usertext-body .md tbody tr:nth-of-type(odd) {
    background-color: #efefef;
}

/* type styling 
 ======================================*/

ul.flat-list.buttons li a,
.usertext-body a,
.flat-vert.icon-menu.hover a,
a.helplink,
.sidecontentbox .content a,
.reddit-link.even.first-half.thing .reddit-entry.entry.likes a,
.account-activity-box a {
    color: #000000;
}

.wiki-page-content .md h1 {
    font-size: 32px;
    font-weight: bold;
}

.wiki-page-content .md h2 {
    font-size: 24px;
    font-weight: bold;
}

.wiki-page-content .md h3 {
    font-size: 18px;
    font-weight: bold;
}

div.thing div.entry p.title a.title {
    color: #000000;
    font-size: 20px;
}

div.thing div.entry p.title a.title:visited {
    color: #757575;
}

.usertext-body .md p,
.usertext-body .md ul li,
.usertext-body .md ol li,
.wiki-page-content .md p,
.wiki-page-content table {
    font-size: 14px;
    /*line-height: 18px;*/
}

.usertext-body .md p + p {
    margin-top: 8px;
}

div.entry p.tagline,
ul.flat-list.buttons li a {
    font-size: 12px;
}

div.commentarea div.sitetable.nestedlisting div.entry div.noncollapsed p.tagline {
    font-size: 13px;
border-left-color: #FF0000;
 
}

div.content a {
    color: #FF8365;
    text-decoration: none;
}

div.content a:visited {
    color: #8c0101;
    text-decoration: none;
}

div.usertext-body div.md a {
    color: #ce0101;
    text-decoration: underline;
}

div.usertext-body div.md a:visited {
    color: #8c0101;
    text-decoration: underline;
}

div.usertext-body div.md a:hover {
    color: #ce0101; /* formerly b90000 */
    text-decoration: underline;
}

div.usertext-body div.md a:visited {
    color: #880101;
    text-decoration: underline;
}

.link:hover {
    border: 2px solid #32373C;
    box-shadow: 0 0 5px #939DCD;
}
div.comment div.child > .sitetable > .thing, div.comment div.child div.child div.child > .sitetable > .thing, div.comment div.child div.child div.child div.child div.child > .sitetable > .thing, div.comment div.child div.child div.child div.child div.child div.child div.child > .sitetable > .thing, div.comment div.child div.child div.child div.child div.child div.child div.child div.child div.child > .sitetable > .thing, div.comment div.child div.child div.child div.child div.child div.child div.child div.child div.child div.child div.child > .sitetable > .thing {
    border-left: 3px solid #000000 !important;
}

.report-button .option:hover:not(.error):before {
    content: "Point em out, point em out, point em out...";
    margin: -4px 0 0 36px;
}

.report-button .option:hover:not(.error):before {
    content: "Point em out, point em out, point em out...";
    margin: -4px 0 0 36px;
}

/* heading styling
======================================*/

.md h1 { color: #074982 !important; text-decoration: underline;
font-weight: bold; font-size: 24px; cursor:default}

.md h2 { color: #07699E !important; text-decoration:
font-weight: bold; font-size: 20px; cursor:default}

.md h3 { color: #07699E !important;
font-weight: bold; font-size: 18px}

.md h4 { color: #000 !important;
font-weight: bold; font-size: 14px; cursor:default: underline}

.md h5 { color: #000; font-size: 12px; 
cursor:default}

/*deleted/removed from /r/askscience*/
form.grayed, form.grayed ~ ul.flat-list.buttons {
    display: none
    }
p.tagline > a.expand:first-child + em:after, div.collapsed > a.expand:first-child + em:after {
    visibility: visible;
    font-size: medium;
    font-weight: bold;
    color: red!important;
    content: "(PIP)"
    }
p.tagline > a.expand:first-child + em, div.collapsed > a.expand:first-child + em {
    visibility: hidden;
    font-size: 0
    }
div.collapsed > a.expand:first-child + em + time + a.expand, div.collapsed > a.expand:first-child + em + time + em + a.expand {
    display: none
    }

# siteTable {
    margin-top: 35px;
    }

/*up and down arrow customization*/
.arrow.up:hover:before { position: absolute; display: block; z-index: 1000; width: auto; padding: 5px 20px 5px 20px; border: 1px solid #333; background-color: #cee3f8; content: " Constructive"; text-align: left; font-size: 10px; font-weight: 400; margin-left: 25px; margin-top: 5px; vertical-align : top; }

.arrow.down:hover:before { position: absolute; display: block; z-index: 1000; width: auto; padding: 5px 20px 5px 20px; border: 1px solid #333; background-color: #9e0b0f; color:#fff; content: " Off topic"; text-align: left; font-size: 10px; font-weight: 400; margin-left: 25px; margin-top: 5px; vertical-align : top; }

/* Moderator assigned flair
======================================*/

.flair,.linkflairlabel {
    display:inline-block;
    margin-right:.5em;
    padding:0 2px;
    color:#FF8365;
    border: 0;
    font-weight: bold;
}

.RESUserTag {
    float: right;
}

.flair:before,.linkflairlabel:before {
    content: "[";
}

.flair:after,.linkflairlabel:after {
    content: "]";
}

.author.submitter {
   background-color: #060606 !important;
   color: #fff !important;
   padding: 0px 3px;
}

.author.moderator:after {
    content: " [moderator]";
}

a.author.friend {
    background-color: #ce0101 !important;
    color: #FFF !important;
}

.author[href$="/killyouintheface"]:before { 
    content: "[cripplesterone] " 
}

.author[href$="/FesterTheNoEster"]:after {
    content: " [Pins Tequila]"
}

.author[href$="/schqnsense"]:after {
    content: " [EQ, not just for bike chains anymore]"
}

.author[href$="/flushbrah"]:after {
    content: " [Swimming in Tren Ace]" 
}

.author[href$="/protein7g"]:after {
    content: " [Faps To His Sister]" 
}

.author[href$="/kilimanjaro13"]:after {
    content: " [255,370,425]"
}

.author[href$="/throwawayosterone"]:after {
    content: " [Gear Geek]"
}

.author[href$="/5345dhk"]:after {
    content: " [Gear Biochemist]"
}

.author[href$="/datworkaccount13"]:after {
    content: " [Blast and Cruise]" 
}

.author[href$="/Owwmybutt"]:after {
    content: " [1 & 3/4 pinkies]"
}

.author[href$="/Sdmonster"]:after {
    content: " [Bulking with duck jerky]"
}

.author[href$="/toothpickarms"]:after {
    content: " [Forever bulking]" 
}

.author[href$="/karlmalonestelone"]:after { 
    content: " [Dreams about steroid profiles]"
}

.author[href$="/totallyforwork"]:after {
    content: " [Ph.D. in Broscience]" 
}

.author[href$="/herman_gill"]:after {
    content: " [Supplementing the D]" 
}

.author[href$="/Jake258"]:after {
    content: " [Young Buck.  Be nice.]" 
}

.author[href$="/dLuR"]:after {
    content: " [Vigilante Mod]" 
}

/* Deaposmi CC 
=================== */

.linkflair a.thumbnail {
  border-left: 10px solid #333;
  margin-left: 0!important;
}

.linkflair a.thumbnail:hover::before {
  display: block;
  padding: 3px 2px 2px 16px;
  color: #fff;
  width: 100px;
  font-size: 12px;
  border-bottom-right-radius: 10px;
  border-top-right-radius: 10px;
  position: absolute;
  opacity: 1.0;
  z-index: 100;
  height: 15px;
  background: #35566e url(%%flair-icons%%) no-repeat;
}

.linkflair-cycle a.thumbnail:hover::before {
  content: "Topic: Cycle";
  background-color: #35566e;
}
.linkflair-cycle .linkflairlabel {border: none; background: #35566e; color: black;}

.linkflair-bloodwork a.thumbnail:hover::before {
  content: "Topic: Bloodwork";
  border: none; background: #bb2227; color: white;
}
.linkflair-bloodwork .linkflairlabel {border: none; background: #bb2227; color: black;}

.linkflair-compounds a.thumbnail:hover::before {
  content: "Topic: Compounds";
  background-color: #79cdcd;
  background-position: 0 -38px;
}
.linkflair-compounds .linkflairlabel {border: none; background: #79cdcd; color: black;}

.linkflair-help a.thumbnail:hover::before {
  content: "Topic: Help";
  background-color: #e4d256;
  background-position: 0 -57px;
}
.linkflair-help .linkflairlabel {border: none; background: #e4d256; color: black;}

.linkflair-homebrew a.thumbnail:hover::before {
  content: "Topic: Homebrew";
  background-color: #3f8905;
  background-position: 0 -76px;
}
.linkflair-homebrew .linkflairlabel {border: none; background: #3f8905; color: black;}

.linkflair-nutrition a.thumbnail:hover::before {
  content: "Topic: Nutrition";
  background-color: #f7941d;
  background-position: 0 -95px;
}
.linkflair-nutrition .linkflairlabel {border: none; background: #f7941d; color: black;}

.linkflair-female a.thumbnail:hover::before {
  content: "Topic: Female";
  background-color: #ea6ba5;
  background-position: 0 -114px;
}
.linkflair-female .linkflairlabel {border: none; background: #ea6ba5; color: black;}

.linkflair-forum a.thumbnail:hover::before {
  content: "Topic: Forum";
  background-color: #a187be;
  background-position: 0 -133px;
}
.linkflair-forum .linkflairlabel {border: none; background: #a187be; color: black;}

.linkflair-offtopic a.thumbnail:hover::before {
  content: "Topic: Off-Topic";
  background-color: #5574b9;
  background-position: 0 -152px;
}
.linkflair-offtopic .linkflairlabel {border: none; background: #5574b9; color: black;}

.linkflair-discussion a.thumbnail:hover::before {
  content: "Topic: Discussion";
  background-color: #d76045;
  background-position: 0 -171px;
}
.linkflair-discussion .linkflairlabel {border: none; background: #d76045; color: black;}

.linkflair-cycle a.thumbnail {
  border-color: #35566e;
  background: url(%%cycle-icon%%) no-repeat center center;
}

.linkflair-bloodwork a.thumbnail {
  border-color: #bb2227;
  background: url(%%blood-icon%%) no-repeat center center;
}

.linkflair-compounds a.thumbnail {
  border-color: #79cdcd;
  background: url(%%compounds-icon%%) no-repeat center center;
}

.linkflair-help a.thumbnail {
  border-color: #e4d256;
  background: url(%%help-icon%%) no-repeat center center;
}

.linkflair-homebrew a.thumbnail {
  border-color: #3f8905;
  background: url(%%homebrew-icon%%) no-repeat center center;
}

.linkflair-nutrition a.thumbnail {
  border-color: #f7941d;
  background: url(%%nutrition-icon%%) no-repeat center center;
}

.linkflair-female a.thumbnail {
  border-color: #ea6ba5;
  background: url(%%female-icon%%) no-repeat center center;
}

.linkflair-forum a.thumbnail {
  border-color: #a187be;
  background: url(%%forum-icon%%) no-repeat center center;
}

.linkflair-offtopic a.thumbnail {
  border-color: #5574b9;
  background: url(%%offtopic-icon%%) no-repeat center center;
}

.linkflair-discussion a.thumbnail {
  border-color: #d76045;
  background: url(%%discussion-icon%%) no-repeat center center;
}

a[href*="#topic"] {
  display: inline-block;
  width: 19px;
  height: 19px;
  border: 1px solid #000;
  margin-left: 2px;
  background: #35566e url(%%flair-icons%%) no-repeat;
}

a[href*="#topiccycle"] {
  background-color: #35566e;
  background-position: 3px 0px;
}

a[href*="#topicbloodwork"] {
  background-color: #bb2227;
  background-position: 3px -19px;
}

a[href*="#topiccompounds"] {
  background-color: #79cdcd;
  background-position: 3px -38px;
}

a[href*="#topichelp"] {
  background-color: #e4d256;
  background-position: 3px -57px;
}

a[href*="#topichomebrew"] {
  background-color: #3f8905;
  background-position: 3px -76px;
}

a[href*="#topicnutrition"] {
  background-color: #f7941d;
  background-position: 3px -95px;
}

a[href*="#topicfemale"] {
  background-color: #ea6ba5;
  background-position: 3px -114px;
}

a[href*="#topicforum"] {
  background-color: #a187be;
  background-position: 3px -133px;
}

a[href*="#topicofftopic"] {
  background-color: #5574b9;
  background-position: 3px -152px;
}

a[href*="#topicdiscussion"] {
  background-color: #d76045;
  background-position: 3px -171px;
}

a[href*="#topic"]:hover::before{
  display:block;
  position:absolute;
  margin-top:-27px;
  margin-left:-40px;
  height:18px;
  width:100px;
  background-color:#FFFFCC;
  color:#444;border:
  1px solid #999;
  text-align:center;
  padding-top:3px
}

a[href*="#topiccycle"]:hover::before{
  content: "Cycle";
}

a[href*="#topicbloodwork"]:hover::before{
  content: "Bloodwork";
}

a[href*="#topiccompounds"]:hover::before{
  content: "Compounds";
}

a[href*="#topichelp"]:hover::before{
  content: "Help";
}

a[href*="#topichomebrew"]:hover::before{
  content: "Homebrew";
}

a[href*="#topicnutrition"]:hover::before{
  content: "Nutrition";
}

a[href*="#topicfemale"]:hover::before{
  content: "Female";
}

a[href*="#topicforum"]:hover::before{
  content: "Forum";
}

a[href*="#topicofftopic"]:hover::before{
  content: "Off-Topic";
}

a[href*="#topicdiscussion"]:hover::before{
  content: "Discussion";
}

.content { margin-top: 65px; }

.link .rank { margin-top: 19px; }

# siteTable .thing.stickied { border: 3px solid #0e76a5!important; box-shadow: 0 0px 5px rgba( 0, 0, 0, .7) inset; }

/* flair
======================================*/

.author.submitter {
   background-color: #060606 !important;
   color: #fff !important;
   padding: 0px 3px;
}

.author.moderator:after {
    content: " [moderator]";
}

a.author.friend {
    background-color: #B90000 !important;
    color: #FFF !important;
}

.author[href$="/killyouintheface"]:after { 
    content: " [cripplesterone]" 
}

.author[href$="/throwawayosterone"]:after {
    content: " [Gear Geek]"
}

.author[href$="/datworkaccount13"]:after {
    content: " [Blast and Cruise]" 
}

.author[href$="/crackerdoctor"]:after {
    content: " [Source Talk Advocate #1]" 
}

.author[href$="/totallyforwork"]:after {
    content: " [Geared Grunt]" 
}

.author[href$="/sambianchetto"]:after {
    content: " [Clen Poppin']" 
}

.author[href$="/forthegains"]:after {
    content: " [Gear Chef]" 
}

.author[href$="/AASresearch"]:after {
    content: " [Warchest of Viagra]" 
}

.author[href$="/stolenlunches"]:after {
    content: " [Pay Attention]" 
}

.author[href$="/Sevion"]:after {
    content: " [Analyzing Your Study]" 
}

.author[href$="/h8speech"]:after {
    content: " [Voice of Reason]" 
}

.author[href$="/BeyondDedication"]:after {
    content: " [6 lb Potato Swole]" 
}

.author[href$="/roidie"]:after {
    content: " [Banned Everywhere Else]" 
}

.author[href$="/OneTimeThingOnly"]:after {
    content: " [Singulair Shill]" 
}

.author[href$="/beenonymous"]:after {
    content: " [Mr. SubQ, Old and Busted]" 
}

.author[href$="/ThemsFightinWords"]:after {
    content: " [Are You Lactating?]" 
}

.author[href$="/quinnclever"]:after {
    content: " [19 years old]" 
}

.author[href$="/hypnotoadIRL"]:after {
    content: " [90% Synthol]" 
}

.author[href$="/Sdmonster"]:after {
    content: " [Deca's Soul Mate]" 
}

.author[href$="/hr_shovenstuff"]:after {
    content: " [Roid Rage Rapture]" 
}

.author[href$="/Fimbul"]:after {
    content: " [Maker of steroidplot.com]" 
}

.author[href$="/Swolenerd"]:after {
    content: " [D&D Str: 15]" 
}

.author[href$="/TestTrening2"]:after {
    content: " [Trendrama]" 
}

.author[href$="/SwoleLottaLove"]:after {
    content: " [Cycling Models]" 
}

.author[href$="/JuicedNewton"]:after {
    content: " [Aspiring Chemist]" 
}

.author[href$="/AlmightyThumbs"]:after {
    content: " [Surviving Wrecks]" 
}

.author[href$="/petethepianist"]:after {
    content: " [Conquering Self]" 
}

.author[href$="/UsernameRandomNumber"]:after {
    content: " [VentroGlute Meister]" 
}

.author[href$="/HyperactiveGray"]:after {
    content: " [Dyslexic Gary]" 
}

.author[href$="/DiplomaticSham"]:after {
    content: " [Ink-tastic]" 
}

.author[href$="/Aussie_muscle"]:after {
    content: " [Shower Chugging]" 
}

.author[href$="/pinittowinit"]:after {
    content: " [Halo Hard]" 
}

.author[href$="/doccount"]:after {
    content: " [Taste the Gainsbro]" 
}

.author[href$="/Jooceyjooce"]:after {
    content: " [IV Martini Pro]" 
}

.author[href$="/UncleNatty"]:after {
    content: " [Potently Descriptive]" 
}

.author[href$="/HalfBull"]:after {
    content: " [The Boy]" 
}

.author[href$="/hoponthe"]:after {
    content: " [Superdrol's BFF]" 
}

.author[href$="/GooberSmudge"]:after {
    content: " [HGH Hero]" 
}

.author[href$="/franksbrother"]:after {
    content: " [Pin Crippled]" 
}

.author[href$="/Metric3036"]:after {
    content: " [Apodo: Steroids]" 
}

.author[href$="/orionxx"]:after {
    content: " ['Slin-spertese]" 
}

.author[href$="/CAPSLOCKISCOOLBRO"]:after {
    content: " [ORB SEMORDNILAP]" 
}

.author[href$="/SWOLE_FEDORA"]:after {
    content: " [Yamming Libidinously]" 
}

.author[href$="/MaK_Ultra"]:after {
    content: " [Tren Kitty]" 
}

.author[href$="/foo-dog"]:after {
    content: " [Fulvestrant Pioneer]" 
}

.author[href$="/Roid-Away"]:after {
    content: " [TUDCA Prime]" 
}

.author[href$="/redwingpanda"]:after {
    content: " [FTM FTW]" 
}

.author[href$="/TerribleFries"]:after {
    content: " [Love Hands]" 
}

.author[href$="/mnch"]:after {
    content: " [Cambodian Prisoner]" 
}

.author[href$="/fluoxymesterone"]:after {
    content: " [Policy Swole]" 
}

.author[href$="/OilKnight"]:after {
    content: " [Fuzzy Inside]" 
}

.author[href$="/Juicedupmonkeyman"]:after {
    content: " [Wanna-be Smart]" 
}

.author[href$="/snowpatrol123"]:after {
    content: " [Jesus' Conscience]" 
}

.author[href$="/tacoLink"]:after {
    content: " [extra cilantro]" 
}

.author[href$="/Bovine_University"]:after {
    content: " [Distinguished Professor]" 
}

.author[href$="/pinned4life"]:after {
    content: " [The Last]" 
}

/*.author[href$="/deaposmi"]{
    position: relative;
    display: inline;
    color: rgba(0, 0, 255, .5)!important;
    font-weight: bold!important;
    font-size: 14px;
}

.author[href$="/deaposmi"]:after {
    content: "deaposmi";
    position: absolute;
    left: 1px;
    top: 1px;
    color: rgba(255, 0, 0, .5)!important; 
}*/

.author[href$="/deaposmi"] {
  font-weight:700;
  text-decoration: none;
  text-transform:uppercase;
  color: #fff;
  padding: 3px 4px 2px 4px;
  position: relative;
  background: #9dd53a /* Old browsers */
  background: -moz-linear-gradient(top,  #9dd53a 0%, #a1d54f 50%, #80c217 51%, #7cbc0a 100%);
  background: -webkit-linear-gradient(top,  #9dd53a 0%,#a1d54f 50%,#80c217 51%,#7cbc0a 100%);
  background: linear-gradient(to bottom,  #9dd53a 0%,#a1d54f 50%,#80c217 51%,#7cbc0a 100%);

}

.author[href$="/deaposmi"]:after {
    content: " ⇜⇜⇜";
    color: #fff;
    animation:blur 2s ease-out infinite;
}

.author[href$="/deaposmi"]:before {
    content: "⇝⇝⇝ ";
    color: #fff;
    animation: blur 2s ease-out infinite;
}

@keyframes blur{
  0% {
    opacity: 0;
  }
  40% {
    opacity: 1;
  }
  45% {
    opacity: 0;
  }
  50% {
    opacity: 1;
  }
  55% {
    opacity: 0;
  }
  60% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}

# siteTable .thing.linkflair-forum { border: 3px solid #a187be!important; box-shadow: 0 0px 5px rgba( 0, 0, 0, .7) inset; }

a:hover.helplink::before {
	content: "!!! DO NOT ASK US WHY YOU CANNOT MAKE A POST !!!";
	position: fixed;
	top: 0;
	right: 0;
	background: #ff0;
	padding: 20px;
	font-size: 19px;
	z-index: 99999;
	width: 450px;
	font-weight: bold;
	background: #ff0;
	animation: backgroundblur 1.5s ease-out infinite;
	text-align: justify;
}

a:hover.helplink::after {
	content: "You need to participate in the community for 90 days (comments). So, participate in the community, ask your questions, and have fun. If you have a question, use the daily [Forum] Ask Anything thread. If you have a post in this subreddit that is >90 days old, THEN you may message us linking it in your message and we'll approve you.";
	position: fixed;
	top: 60px;
	right: 0;
	background: #f00;
	padding: 20px;
	font-size: 19px;
	z-index: 99999;
	width: 450px;
	text-align: justify;
}

@keyframes backgroundblur {
  0% {
    background: #ff0;
  }
  50% {
    background: #000;
    color: #ff0;
  }
  100% {
    background: #ff0;
  }
}

.flair-green{ color:ForestGreen}
.flair-red{ color:Crimson}
.flair-yellow{ color:Gold}
.flair-purple{ color:Indigo}
.flair-black{ color:black}
.flair-pink{ color:Orchid}
.flair-cyan{ color:PaleTurquoise}
.flair-blue{ color:SteelBlue}
.flair-rainbow1 {
    background-image: -webkit-linear-gradient(left, red 0%, red 14%, orange 14%, orange 28%, yellow 28%, yellow 43%, green 43%, green 57%, blue 57%, blue 72%, indigo 72%, indigo 86%, violet 86%, violet 100%);
    background-image: -moz-linear-gradient(left, red 0%, red 14%, orange 14%, orange 28%, yellow 28%, yellow 43%, green 43%, green 57%, blue 57%, blue 72%, indigo 72%, indigo 86%, violet 86%, violet 100%);
    background-image: -ms-linear-gradient(left, red 0%, red 14%, orange 14%, orange 28%, yellow 28%, yellow 43%, green 43%, green 57%, blue 57%, blue 72%, indigo 72%, indigo 86%, violet 86%, violet 100%);
    background-image: -o-linear-gradient(left, red 0%, red 14%, orange 14%, orange 28%, yellow 28%, yellow 43%, green 43%, green 57%, blue 57%, blue 72%, indigo 72%, indigo 86%, violet 86%, violet 100%);
    background-image: linear-gradient(to right, red 0%, red 14%, orange 14%, orange 28%, yellow 28%, yellow 43%, green 43%, green 57%, blue 57%, blue 72%, indigo 72%, indigo 86%, violet 86%, violet 100%);
    color: White;
    text-shadow: -1px -1px 0 Indigo, 1px -1px 0 Indigo, -1px 1px 0 Indigo, 1px 1px 0 Indigo;
    
}

@keyframes rainbow {0% {color:red;}14% {color:orange;}28% {color:goldenrod;}42% {color:ForestGreen;}56% {color:DodgerBlue;}70% {color:BlueViolet;}84% {color:indigo;}}
@-moz-keyframes rainbow {0% {color:red;}14% {color:orange;}28% {color:goldenrod;}42% {color:ForestGreen;}56% {color:DodgerBlue;}70% {color:BlueViolet;}84% {color:indigo;}}
@-webkit-keyframes rainbow {0% {color:red;}14% {color:orange;}28% {color:goldenrod;}42% {color:ForestGreen;}56% {color:DodgerBlue;}70% {color:BlueViolet;}84% {color:indigo;}}

.flair-rainbow6{color:red; -webkit-animation:rainbow 5s linear infinite; -moz-animation:rainbow 5s linear infinite; animation:rainbow 5s linear infinite;}