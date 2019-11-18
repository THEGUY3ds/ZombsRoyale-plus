// ==UserScript==
// @name         zombsroyale plus
// @namespace    overhax.ml
// @version      0.01
// @description  Best zombsroyale hack
// @author       OVERHAX | THEGUY3ds
// @match        *://zombsroyale.io/*
// @require      http://code.jquery.com/jquery-1.12.4.min.js
// @require      https://greasyfork.org/scripts/368273-msgpack/code/msgpack.js?version=598723
// @require      http://code.jquery.com/jquery-3.3.1.min.js
// @require      https://code.jquery.com/ui/1.12.0/jquery-ui.min.js
// @require      https://cdnjs.cloudflare.com/ajax/libs/jquery-confirm/3.3.0/jquery-confirm.min.js
// @grant        GM_xmlhttpRequest
// @connect      zombsroyale.io
// @grant        none
// ==/UserScript==
// Change page title
document.title = "OVERHAX ZombsRoyale Plus";
//Tells u if hack is working.
alert("INJECTED ZombsRoyale Plus")
//Hub change
//Loading change
var x = document.getElementsByClassName("loading-message");
var i;
for (i = 0; i < x.length; i++) {
  x[i].style.backgroundColor = "red";
  x[i].innerHTML = 'ZombsRoyalePlus loading.... only at overhax.ml';
}
//Bg image
document.getElementById("#canvas").style.backgroundImage = "url('https://i.imgur.com/TePdLdt.png')";
//Adblock
window.onload="Adblock()"

		function Adblock(){
            const removeElements = (elms) => elms.forEach(el => el.remove());
            removeElements( document.querySelectorAll(".ad-unit") );

		}		setInterval(Adblock, 1000);
// Fullscreen
document.fullscreenEnabled =
	document.fullscreenEnabled ||
	document.mozFullScreenEnabled ||
	document.documentElement.webkitRequestFullScreen;

function requestFullscreen(element) {
	if (element.requestFullscreen) {
		element.requestFullscreen();
	} else if (element.mozRequestFullScreen) {
		element.mozRequestFullScreen();
	} else if (element.webkitRequestFullScreen) {
		element.webkitRequestFullScreen(Element.ALLOW_KEYBOARD_INPUT);
	}
}

if (document.fullscreenEnabled) {
	requestFullscreen(document.documentElement);
}
    function read(url) {
    return new Promise(resolve => {
        fetch(url).then(res => res.text()).then(res => {
            return resolve(res);
        });
    });
};
//End Hub change
