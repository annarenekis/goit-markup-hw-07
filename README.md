# goit-markup-hw-07

:root { --primary-text-color: #757575; --title-text-color: #212121;
--additional-text-color: #ffff; --accent-color: #2196f3; --primary-bg-color:
#ffff; --additional-bg-color: #2f303a; --button-hover-color: #188ce8;
--grey-bg-color: #f5f4fa; } body { font-family: 'Roboto', sans-serif; font-size:
14px; color: var(--title-text-color); } ul, p, h1, h2, h3, h4 /_ .list,
.footer-list { _/ { list-style: none; padding: 0; margin: 0; } /_
.project-title, .project-text, .text _/ img, .link { display: block; } .link {
text-decoration-line: none; }

.section { padding-top: 94px; padding-bottom: 94px; }

/_ header _/

.nav, .list, .contacts, .header { display: flex; /_ justify-content: center;
align-items: center; _/ }

.header, .nav { align-items: center; } .nav { margin-right: auto; } .header {
width: 1200px; padding-left: 15px; padding-right: 15px; margin: 0 auto; }

.nav**item:not(:last-child), .contacts**item:not(:last-child) { margin-right:
50px; }

img, .link { display: block; } .link { text-decoration-line: none; }

.header\_\_portfolio { border-bottom: 1px solid #ececec; }

.logo, .nav\_\_link { color: var(--title-text-color); }

.nav\_\_link, .contacts { font-weight: 500; font-size: 14px; line-height: 1.14;
letter-spacing: 0.02em; padding: 32px 0; }

/_ .contact-link, _/

.contacts**link { color: var(--primary-text-color); } .header-logo {
margin-right: 93px; } .logo { font-family: 'Raleway', sans-serif; font-weight:
700; font-size: 26px; line-height: 1.19; letter-spacing: 0.03em; }
.nav**link:hover, .nav**link:focus, .footer-address**link.hover:hover,
.footer-address**link.hover:focus, .word-web { color: var(--accent-color); fill:
var(--accent-color); } .contacts**link:hover, .contacts\_\_link:focus { color:
var(--accent-color); }

.contacts\_\_icon:hover { fill: currentColor; }

.nav**link--current { color: var(--accent-color); } .nav**link { position:
relative; } .nav\_\_link--current:after { content: ''; position: absolute;
display: block; width: 100%; height: 4px; border-radius: 2px; background:
var(--accent-color); bottom: 0; } /_ main _/ /_ hero _/

.container { margin-left: auto; margin-right: auto; width: 1200px; padding: 0
15px; box-sizing: border-box; }

.hero { max-width: 1600px; height: 600px; text-align: center; padding-top:
200px; background-color: #c4c4c4; background-image: linear-gradient( rgba(47,
48, 58, 0.4), rgba(47, 48, 58, 0.4) ), url(../img/hero.jpg); background-size:
cover; background-repeat: no-repeat; background-position: center; }

/_ button main page _/

.hero**btn { margin-bottom: 200px; } .hero**btn, .modal-sub**btn, .sub-btn {
font-weight: 700; font-size: 16px; line-height: 1.88; letter-spacing: 0.06em;
background: var(--accent-color); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
border: var(--accent-color); color: var(--additional-text-color); padding: 10px
32px; } .hero**btn:hover, .hero**btn:focus, .modal-sub**btn:hover,
.sub-btn:hover, .modal-sub**btn:focus, .sub-btn:focus { background-color:
var(--button-hover-color); } .hero**title { margin-top: 0; margin-bottom: 30px;
font-weight: 900; font-size: 44px; line-height: 1.36; text-align: center;
letter-spacing: 0.06em; text-transform: uppercase; color:
var(--additional-text-color); } .button { cursor: pointer; border-radius: 4px;
display: inline-block; }

/_ section1 _/

.advantages\_\_item:not(:last-child) { margin-right: 30px; }

.advantages, .about, .team { display: flex; }

.advantages\_\_item { width: 270px; align-items: center; justify-items: center;
}

.advantages**title, .about**text { margin-top: 0; margin-bottom: 10px;
font-weight: 700; font-size: 14px; line-height: 1.14; letter-spacing: 0.03em;
text-transform: uppercase; color: var(--title-text-color); } .advantages**text {
margin-top: 0; margin-bottom: 0; } .advantages**text, .footer-address-link {
font-weight: 400; font-size: 14px; line-height: 1.71; letter-spacing: 0.03em;
color: var(--primary-text-color); }

.hidden { visibility: hidden; position: fixed; transform: scale(0); }

/_ section2 _/

.section**about { padding-top: 0; } .section**title { margin-top: 0;
margin-bottom: 50px; font-weight: 700; font-size: 36px; line-height: 1.16;
text-align: center; letter-spacing: 0.03em; color: var(--title-text-color); }
.about\_\_text { text-transform: uppercase; color: var(--additional-text-color);
margin: 0; position: absolute; background: rgba(47, 48, 58, 0.8); width: 100%;
height: 70px; display: flex; justify-content: center; align-items: center;
bottom: 0; left: 0; }

.about\_\_item { position: relative; }

.about\_\_item:not(:last-child) { margin-right: 30px; }

/_ section3 _/ /_ TEAM _/

.team**text { margin-top: 0; margin-bottom: 16px; color:
var(--primary-text-color); font-size: 16px; line-height: 1.18; text-align:
center; letter-spacing: 0.03em; } .team**title { margin-top: 0; margin-bottom:
0; font-weight: 500; font-size: 16px; line-height: 1.18; text-align: center;
letter-spacing: 0.03em; margin-bottom: 10px; } .section**team { background:
var(--grey-bg-color); } .team**figcaption { padding: 30px 32px; } .team**group {
box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14),
0px 2px 1px rgba(0, 0, 0, 0.2); border-radius: 0px 0px 4px 4px; background:
var(--primary-bg-color); margin: 0; } .team**item:not(:last-child) {
margin-right: 30px; }

/_ footer _/

.section\_\_footer { background-color: var(--additional-bg-color); padding-top:
60px; padding-bottom: 60px; }

<!-- address {
  display: block;
  font-style: normal;
} -->

.footer-address { display: block; font-style: normal; }

.footer-address { margin-top: 20px; } .footer-address**link { color:
var(--additional-text-color); } .footer-address**item:not(:last-child) {
margin-bottom: 9px; } .footer-email, .footer-ph-numb { color: rgba(255, 255,
255, 0.6); } .word-studio-footer { color: var(--additional-text-color); }
.footer { display: flex; align-items: baseline; } .join-group { margin-left:
70px; }

.footer\_\_text { color: var(--additional-text-color); font-weight: 700;
font-size: 14px; line-height: 1.14; letter-spacing: 0.03em; text-transform:
uppercase; margin-bottom: 20px; } .sub { margin-left: 93px; }

.sub\_\_input { width: 358px; height: 50px; background: #2f303a; border: 1px
solid rgba(255, 255, 255, 0.3); filter: drop-shadow(0px 4px 4px rgba(0, 0, 0,
0.15)); border-radius: 4px; padding: 15px 16px 15px; letter-spacing: 0.03em;
color: rgba(255, 255, 255, 0.6); font-size: 16px; line-height: 1.25;
margin-right: 12px; transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.sub-btn\_\_text { margin-right: 10px; }

.sub\_\_div, .sub-button { display: flex; justify-content: center; align-items:
center; }

.sub-button { padding: 0; width: 200px; min-height: 50px; }

/_ portfolio _/

.project\_\_thumb { position: relative; overflow: hidden; }

.overlay { position: absolute; width: 100%; height: 100%; top: 0; left: 0;
background: rgba(33, 150, 243, 0.9); transform: translateY(100%); transition:
transform 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.project\_\_flex-container:hover .overlay { transform: translateY(0); }

.overlay\_\_content { position: absolute; top: 50%; left: 50%; transform:
translate(-50%, -50%); font-size: 18px; line-height: 1.56; letter-spacing:
0.03em; width: 322px; color: var(--additional-text-color); }

.project**title { margin-bottom: 4px; font-weight: 700; font-size: 18px;
line-height: 2; letter-spacing: 0.06em; color: var(--title-text-color); }
.project**text { font-size: 16px; line-height: 1.88; letter-spacing: 0.03em;
color: var(--primary-text-color); }

.project { display: flex; flex-wrap: wrap; margin: 0; padding: 0; }

.project**descr { border: 1px solid #eeeeee; border-top: transparent; padding:
20px 24px; } .project**flex-container { width: 370px; background-color:
var(--primary-bg-color); margin-bottom: 30px; }
.project**flex-container.no-margin { margin-bottom: 0; } .project**item {
margin-right: 30px; } .project**item:nth-child(3n + 3) { margin-right: 0; }
.project**flex-container:hover, .project\_\_flex-container:focus { box-shadow:
0px 1px 1px rgba(0, 0, 0, 0.12), 0px 4px 4px rgba(0, 0, 0, 0.06), 1px 4px 6px
rgba(0, 0, 0, 0.16); }

/_ filter-menu _/

.filter { display: flex; align-items: center; justify-content: center;
margin-bottom: 50px; } .filter\_\_item { font-weight: 500; font-size: 16px;
line-height: 1.62; text-align: center; letter-spacing: 0.03em; color:
var(--title-text-color); border: var(--grey-bg-color); background-color:
var(--grey-bg-color); padding: 6px 22px; box-shadow: 0px 3px 1px rgba(0, 0, 0,
0.1), 0px 1px 2px rgba(0, 0, 0, 0.08), 0px 2px 2px rgba(0, 0, 0, 0.12); }

.filter**item:hover, .filter**item:focus, .filter\_\_item.current { color:
var(--additional-text-color); background-color: var(--accent-color); }

.filter > li:not(:first-child) { margin-left: 8px; }

/_ icons _/

.advantages\_\_thumb { height: 120px; background-color: var(--grey-bg-color);
margin-bottom: 30px; display: flex; justify-content: center; align-items:
center; }

.contacts\_\_icon { margin-right: 10px; fill: var(--primary-text-color);
vertical-align: middle; }

.sites-item\_\_link { display: flex; justify-content: center; align-items:
center; background-color: inherit; box-sizing: border-box; height: 44px; width:
44px; border-radius: 50%; }

.sites-item**icon { width: 20px; height: 20px; fill: #afb1b8; }
.sites-item**link:hover, .sites-item\_\_link:focus { background-color:
var(--accent-color); }

.sites-item**link:hover .sites-item**team-icon, .sites-item**link:focus
.sites-item**team-icon { fill: var(--additional-text-color); }
.sites-item:not(:last-child) { margin-right: 10px; }

ul { margin: 0; padding: 0; }

.sites-item\_\_footer { background-color: #44454e; border-radius: 50%; }

.sites-item\_\_icon-footer { fill: var(--additional-text-color); }

.clients\_\_link { border: solid 1px #afb1b8; border-radius: 4px; width: 170px;
height: 92px; display: flex; justify-content: center; align-items: center;
background-color: inherit; }

.clients**item:not(:last-child) { margin-right: 30px; } .clients**icon { fill:
#afb1b8; display: flex; }

.clients**link:hover .clients**icon, .clients**link:focus .clients**icon { fill:
var(--accent-color); }

.clients**link:hover, .clients**link:focus { border: solid 1px
var(--accent-color); }

.backdrop { position: fixed; top: 0; left: 0; width: 100%; height: 100%;
background: rgba(0, 0, 0, 0.2); }

.is-hidden { opacity: 0; pointer-events: none; }

/_ MODAl _/

.modal { width: 528px; height: 581px; background: var(--primary-bg-color);
box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14),
0px 2px 1px rgba(0, 0, 0, 0.2); border-radius: 4px; position: absolute; top:
50%; left: 50%; transform: translate(-50%, -50%); padding: 40px; letter-spacing:
0.01em; color: var(--primary-text-color); } .modal**close-btn { position:
absolute; top: 8px; right: 8px; width: 30px; height: 30px; color: rgba(0, 0, 0,
1); cursor: pointer; background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.1);
border-radius: 50%; display: flex; justify-content: center; align-items: center;
cursor: pointer; } .modal**close-btn:hover, .modal\_\_close-btn:focus { fill:
var(--accent-color); } /_ form-modal _/

.modal-form\_\_title { margin: 0; margin-bottom: 12px; font-weight: 700;
font-size: 20px; line-height: 1.15; text-align: center; letter-spacing: 0.03em;
color: var(--title-text-color); } /_ CHECKBOX _/

.visually-hidden { appearance: none; position: absolute; } .modal-form**label {
display: block; } .modal-checkbox**label { display: flex; justify-content:
center; align-items: center; margin-top: 20px; font-size: 14px; line-height:
1.71; letter-spacing: 0.03em; color: var(--primary-text-color); }

.modal-checkbox**icon { display: inline-block; width: 16px; height: 15px;
outline: 2px solid var(--title-text-color); margin-right: 7px; }
.modal-checkbox**input:checked + .modal-checkbox**icon { background-color:
var(--accent-color); outline: none; background-image:
url(../img/svg/icon-check.svg); background-size: contain; background-repeat:
no-repeat; background-position: center; background-origin: content-box; }
.modal-checkbox**icon:hover, .modal-checkbox\_\_icon:focus { outline-color:
var(--accent-color); }

/_ CHECKBOX _/

.modal-form**label { font-size: 12px; line-height: 1.16; letter-spacing: 0.01em;
margin-bottom: 4px; } .modal-form**comment { padding: 15px 16px; color:
rgba(117, 117, 117, 0.5); height: 120px; resize: none; outline: transparent; }
.modal-form**input { padding-top: 12px; padding-left: 42px; padding-bottom:
12px; outline: transparent; } .modal-form**data { position: relative; display:
block; }

.modal-form\_\_icon { position: absolute; width: 18px; height: 18px; top: 25%;
left: 12px; transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.modal-form**input, .modal-form**comment { border: 1px solid rgba(33, 33, 33,
0.2); border-radius: 4px; width: 100%; transition: color 250ms cubic-bezier(0.4,
0, 0.2, 1); } .modal-form**li { display: block; }
.modal-form**li:not(:last-child) { margin-bottom: 10px; } .modal-sub\_\_btn {
margin-top: 30px; width: 200px; height: 50px; border: none; padding: 0; }
.modal-sub { justify-content: center; display: flex; } .modal-checkbox-link {
padding-left: 3px; color: var(--accent-color); } .modal-checkbox-link:hover,
.modal-checkbox-link:focus { color: var(--button-hover-color); }

/_ animations _/

.clients**link, .modal-checkbox-link, .nav**link, .contacts**link,
.footer-address**item { transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.hero**btn, .sites-item**footer, .modal-sub\_\_btn, .sub-btn { transition:
background-color 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.sites-item**link, .filter**item, .modal-form\_\_label { transition: all 250ms
cubic-bezier(0.4, 0, 0.2, 1); }

.project\_\_flex-container { transition: box-shadow 250ms cubic-bezier(0.4, 0,
0.2, 1); }

.modal-form**data:hover .modal-form**icon, .modal-form**data:focus-within
.modal-form**icon { fill: var(--accent-color); }

.modal-form-input:hover, .modal-form**comment:hover, .modal-form-input:focus,
.modal-form**comment:focus, .sub**input:hover, .sub**input:focus { outline: 1px
solid var(--accent-color); }
