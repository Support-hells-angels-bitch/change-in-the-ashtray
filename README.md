# change-in-the-ashtray
geanie
function() {
    /* HTML content inlined from HTML import */
    const d = document.createElement("div");
    d.setAttribute("inlined-html", "");
    const finalStyleText = "html:not(.style-scope) {\n  --primary-text-color: var(--light-theme-text-color);\n  --primary-background-color: var(--light-theme-background-color);\n  --secondary-text-color: var(--light-theme-secondary-color);\n  --disabled-text-color: var(--light-theme-disabled-color);\n  --divider-color: var(--light-theme-divider-color);\n  --error-color: #dd2c00;\n  --primary-color: #3f51b5;\n  --light-primary-color: #c5cae9;\n  --dark-primary-color: #303f9f;\n  --accent-color: #ff4081;\n  --light-accent-color: #ff80ab;\n  --dark-accent-color: #f50057;\n  --light-theme-background-color: #fff;\n  --light-theme-base-color: #000;\n  --light-theme-text-color: #212121;\n  --light-theme-secondary-color: #737373;\n  --light-theme-disabled-color: #9b9b9b;\n  --light-theme-divider-color: #dbdbdb;\n  --dark-theme-background-color: #212121;\n  --dark-theme-base-color: #fff;\n  --dark-theme-text-color: #fff;\n  --dark-theme-secondary-color: #bcbcbc;\n  --dark-theme-disabled-color: #646464;\n  --dark-theme-divider-color: #3c3c3c;\n  --text-primary-color: var(--dark-theme-text-color);\n  --default-primary-color: var(--primary-color);\n}\n\npaper-ripple {\n  display: block;\n        position: absolute;\n        border-radius: inherit;\n        overflow: hidden;\n        top: 0;\n        left: 0;\n        right: 0;\n        bottom: 0;\n\n        \n        pointer-events: none;\n}\n\npaper-ripple[animating] {\n  -webkit-transform: translate(0, 0);\n        transform: translate3d(0, 0, 0);\n}\n\n#background.paper-ripple,#waves.paper-ripple,.wave-container.paper-ripple,.wave.paper-ripple {\n  pointer-events: none;\n        position: absolute;\n        top: 0;\n        left: 0;\n        width: 100%;\n        height: 100%;\n}\n\n#background.paper-ripple,.wave.paper-ripple {\n  opacity: 0;\n}\n\n#waves.paper-ripple,.wave.paper-ripple {\n  overflow: hidden;\n}\n\n.wave-container.paper-ripple,.wave.paper-ripple {\n  border-radius: 50%;\n}\n\npaper-ripple.circle #background.paper-ripple,paper-ripple.circle #waves.paper-ripple {\n  border-radius: 50%;\n}\n\npaper-ripple.circle .wave-container.paper-ripple {\n  overflow: hidden;\n}\n\ntp-yt-paper-button {\n  display: -ms-inline-flexbox;\n  display: -webkit-inline-flex;\n  display: inline-flex;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  -ms-flex-pack: center;\n  -webkit-justify-content: center;\n  justify-content: center;\n  position: relative;\n  box-sizing: border-box;\n  min-width: 5.14em;\n  margin: 0 0.29em;\n  background: transparent;\n  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);\n  -webkit-tap-highlight-color: transparent;\n  font: inherit;\n  text-transform: uppercase;\n  outline-width: 0;\n  border-radius: 3px;\n  -moz-user-select: none;\n  -ms-user-select: none;\n  -webkit-user-select: none;\n  user-select: none;\n  cursor: pointer;\n  z-index: 0;\n  padding: 0.7em 0.57em;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n}\n\ntp-yt-paper-button[elevation=\"1\"] {\n  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);\n}\n\ntp-yt-paper-button[elevation=\"2\"] {\n  box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-button[elevation=\"3\"] {\n  box-shadow: 0 6px 10px 0 rgba(0, 0, 0, 0.14), 0 1px 18px 0 rgba(0, 0, 0, 0.12), 0 3px 5px -1px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-button[elevation=\"4\"] {\n  box-shadow: 0 8px 10px 1px rgba(0, 0, 0, 0.14), 0 3px 14px 2px rgba(0, 0, 0, 0.12), 0 5px 5px -3px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-button[elevation=\"5\"] {\n  box-shadow: 0 16px 24px 2px rgba(0, 0, 0, 0.14), 0 6px 30px 5px rgba(0, 0, 0, 0.12), 0 8px 10px -5px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-button[hidden] {\n  display: none !important;\n}\n\ntp-yt-paper-button[raised].keyboard-focus {\n  font-weight: bold;\n}\n\ntp-yt-paper-button:not([raised]).keyboard-focus {\n  background-color: var(--paper-button-flat-keyboard-focus-background-color);\n  font-weight: var(--paper-button-flat-keyboard-focus-font-weight, bold);\n  outline: var(--paper-button-flat-keyboard-focus-outline);\n}\n\ntp-yt-paper-button[disabled] {\n  background: none;\n  color: #a8a8a8;\n  cursor: auto;\n  pointer-events: none;\n}\n\ntp-yt-paper-button[disabled][raised] {\n  background: #eaeaea;\n}\n\ntp-yt-paper-button[animated] {\n  transition: box-shadow 0.28s cubic-bezier(0.4, 0, 0.2, 1);\n}\n\npaper-ripple.tp-yt-paper-button {\n  color: var(--paper-button-ink-color);\n}\n\ntp-yt-paper-spinner-lite {\n  display: inline-block;\n  position: relative;\n  width: 28px;\n  height: 28px;\n  --paper-spinner-container-rotation-duration: 1568ms;\n  --paper-spinner-expand-contract-duration: 1333ms;\n  --paper-spinner-full-cycle-duration: 5332ms;\n  --paper-spinner-cooldown-duration: 400ms;\n}\n\n#spinnerContainer.tp-yt-paper-spinner-lite {\n  width: 100%;\n  height: 100%;\n  direction: ltr;\n}\n\n#spinnerContainer.active.tp-yt-paper-spinner-lite {\n  -webkit-animation: container-rotate var(--paper-spinner-container-rotation-duration) linear infinite;\n  animation: container-rotate var(--paper-spinner-container-rotation-duration) linear infinite;\n}\n\n@-webkit-keyframes container-rotate {\nto {\n  -webkit-transform: rotate(360deg);\n}\n\n}\n\n@keyframes container-rotate {\nto {\n  transform: rotate(360deg);\n}\n\n}\n\n.spinner-layer.tp-yt-paper-spinner-lite {\n  position: absolute;\n  width: 100%;\n  height: 100%;\n  opacity: 0;\n  white-space: nowrap;\n  color: var(--paper-spinner-color, #4285f4);\n}\n\n.layer-1.tp-yt-paper-spinner-lite {\n  color: var(--paper-spinner-layer-1-color, #4285f4);\n}\n\n.layer-2.tp-yt-paper-spinner-lite {\n  color: var(--paper-spinner-layer-2-color, #db4437);\n}\n\n.layer-3.tp-yt-paper-spinner-lite {\n  color: var(--paper-spinner-layer-3-color, #f4b400);\n}\n\n.layer-4.tp-yt-paper-spinner-lite {\n  color: var(--paper-spinner-layer-4-color, #0f9d58);\n}\n\n.active.tp-yt-paper-spinner-lite .spinner-layer.tp-yt-paper-spinner-lite {\n  -webkit-animation-name: fill-unfill-rotate;\n  -webkit-animation-duration: var(--paper-spinner-full-cycle-duration);\n  -webkit-animation-timing-function: cubic-bezier(0.4, 0, 0.2, 1);\n  -webkit-animation-iteration-count: infinite;\n  animation-name: fill-unfill-rotate;\n  animation-duration: var(--paper-spinner-full-cycle-duration);\n  animation-timing-function: cubic-bezier(0.4, 0, 0.2, 1);\n  animation-iteration-count: infinite;\n  opacity: 1;\n}\n\n.active.tp-yt-paper-spinner-lite .spinner-layer.layer-1.tp-yt-paper-spinner-lite {\n  -webkit-animation-name: fill-unfill-rotate, layer-1-fade-in-out;\n  animation-name: fill-unfill-rotate, layer-1-fade-in-out;\n}\n\n.active.tp-yt-paper-spinner-lite .spinner-layer.layer-2.tp-yt-paper-spinner-lite {\n  -webkit-animation-name: fill-unfill-rotate, layer-2-fade-in-out;\n  animation-name: fill-unfill-rotate, layer-2-fade-in-out;\n}\n\n.active.tp-yt-paper-spinner-lite .spinner-layer.layer-3.tp-yt-paper-spinner-lite {\n  -webkit-animation-name: fill-unfill-rotate, layer-3-fade-in-out;\n  animation-name: fill-unfill-rotate, layer-3-fade-in-out;\n}\n\n.active.tp-yt-paper-spinner-lite .spinner-layer.layer-4.tp-yt-paper-spinner-lite {\n  -webkit-animation-name: fill-unfill-rotate, layer-4-fade-in-out;\n  animation-name: fill-unfill-rotate, layer-4-fade-in-out;\n}\n\n@-webkit-keyframes fill-unfill-rotate {\n12.5% {\n  -webkit-transform: rotate(135deg);\n}\n\n25% {\n  -webkit-transform: rotate(270deg);\n}\n\n37.5% {\n  -webkit-transform: rotate(405deg);\n}\n\n50% {\n  -webkit-transform: rotate(540deg);\n}\n\n62.5% {\n  -webkit-transform: rotate(675deg);\n}\n\n75% {\n  -webkit-transform: rotate(810deg);\n}\n\n87.5% {\n  -webkit-transform: rotate(945deg);\n}\n\nto {\n  -webkit-transform: rotate(1080deg);\n}\n\n}\n\n@keyframes fill-unfill-rotate {\n12.5% {\n  transform: rotate(135deg);\n}\n\n25% {\n  transform: rotate(270deg);\n}\n\n37.5% {\n  transform: rotate(405deg);\n}\n\n50% {\n  transform: rotate(540deg);\n}\n\n62.5% {\n  transform: rotate(675deg);\n}\n\n75% {\n  transform: rotate(810deg);\n}\n\n87.5% {\n  transform: rotate(945deg);\n}\n\nto {\n  transform: rotate(1080deg);\n}\n\n}\n\n@-webkit-keyframes layer-1-fade-in-out {\n0% {\n  opacity: 1;\n}\n\n25% {\n  opacity: 1;\n}\n\n26% {\n  opacity: 0;\n}\n\n89% {\n  opacity: 0;\n}\n\n90% {\n  opacity: 1;\n}\n\nto {\n  opacity: 1;\n}\n\n}\n\n@keyframes layer-1-fade-in-out {\n0% {\n  opacity: 1;\n}\n\n25% {\n  opacity: 1;\n}\n\n26% {\n  opacity: 0;\n}\n\n89% {\n  opacity: 0;\n}\n\n90% {\n  opacity: 1;\n}\n\nto {\n  opacity: 1;\n}\n\n}\n\n@-webkit-keyframes layer-2-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n15% {\n  opacity: 0;\n}\n\n25% {\n  opacity: 1;\n}\n\n50% {\n  opacity: 1;\n}\n\n51% {\n  opacity: 0;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@keyframes layer-2-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n15% {\n  opacity: 0;\n}\n\n25% {\n  opacity: 1;\n}\n\n50% {\n  opacity: 1;\n}\n\n51% {\n  opacity: 0;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@-webkit-keyframes layer-3-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n40% {\n  opacity: 0;\n}\n\n50% {\n  opacity: 1;\n}\n\n75% {\n  opacity: 1;\n}\n\n76% {\n  opacity: 0;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@keyframes layer-3-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n40% {\n  opacity: 0;\n}\n\n50% {\n  opacity: 1;\n}\n\n75% {\n  opacity: 1;\n}\n\n76% {\n  opacity: 0;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@-webkit-keyframes layer-4-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n65% {\n  opacity: 0;\n}\n\n75% {\n  opacity: 1;\n}\n\n90% {\n  opacity: 1;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@keyframes layer-4-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n65% {\n  opacity: 0;\n}\n\n75% {\n  opacity: 1;\n}\n\n90% {\n  opacity: 1;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n.circle-clipper.tp-yt-paper-spinner-lite {\n  display: inline-block;\n  position: relative;\n  width: 50%;\n  height: 100%;\n  overflow: hidden;\n}\n\n.spinner-layer.tp-yt-paper-spinner-lite::after {\n  content: \"\";\n  left: 45%;\n  width: 10%;\n  border-top-style: solid;\n}\n\n.spinner-layer.tp-yt-paper-spinner-lite::after,.circle-clipper.tp-yt-paper-spinner-lite .circle.tp-yt-paper-spinner-lite {\n  box-sizing: border-box;\n  position: absolute;\n  top: 0;\n  border-width: var(--paper-spinner-stroke-width, 3px);\n  border-radius: 50%;\n}\n\n.circle-clipper.tp-yt-paper-spinner-lite .circle.tp-yt-paper-spinner-lite {\n  bottom: 0;\n  width: 200%;\n  border-style: solid;\n  border-bottom-color: transparent !important;\n}\n\n.circle-clipper.left.tp-yt-paper-spinner-lite .circle.tp-yt-paper-spinner-lite {\n  left: 0;\n  border-right-color: transparent !important;\n  -webkit-transform: rotate(129deg);\n  transform: rotate(129deg);\n}\n\n.circle-clipper.right.tp-yt-paper-spinner-lite .circle.tp-yt-paper-spinner-lite {\n  left: -100%;\n  border-left-color: transparent !important;\n  -webkit-transform: rotate(-129deg);\n  transform: rotate(-129deg);\n}\n\n.active.tp-yt-paper-spinner-lite .gap-patch.tp-yt-paper-spinner-lite::after,.active.tp-yt-paper-spinner-lite .circle-clipper.tp-yt-paper-spinner-lite .circle.tp-yt-paper-spinner-lite {\n  -webkit-animation-duration: var(--paper-spinner-expand-contract-duration);\n  -webkit-animation-timing-function: cubic-bezier(0.4, 0, 0.2, 1);\n  -webkit-animation-iteration-count: infinite;\n  animation-duration: var(--paper-spinner-expand-contract-duration);\n  animation-timing-function: cubic-bezier(0.4, 0, 0.2, 1);\n  animation-iteration-count: infinite;\n}\n\n.active.tp-yt-paper-spinner-lite .circle-clipper.left.tp-yt-paper-spinner-lite .circle.tp-yt-paper-spinner-lite {\n  -webkit-animation-name: left-spin;\n  animation-name: left-spin;\n}\n\n.active.tp-yt-paper-spinner-lite .circle-clipper.right.tp-yt-paper-spinner-lite .circle.tp-yt-paper-spinner-lite {\n  -webkit-animation-name: right-spin;\n  animation-name: right-spin;\n}\n\n@-webkit-keyframes left-spin {\n0% {\n  -webkit-transform: rotate(130deg);\n}\n\n50% {\n  -webkit-transform: rotate(-5deg);\n}\n\nto {\n  -webkit-transform: rotate(130deg);\n}\n\n}\n\n@keyframes left-spin {\n0% {\n  transform: rotate(130deg);\n}\n\n50% {\n  transform: rotate(-5deg);\n}\n\nto {\n  transform: rotate(130deg);\n}\n\n}\n\n@-webkit-keyframes right-spin {\n0% {\n  -webkit-transform: rotate(-130deg);\n}\n\n50% {\n  -webkit-transform: rotate(5deg);\n}\n\nto {\n  -webkit-transform: rotate(-130deg);\n}\n\n}\n\n@keyframes right-spin {\n0% {\n  transform: rotate(-130deg);\n}\n\n50% {\n  transform: rotate(5deg);\n}\n\nto {\n  transform: rotate(-130deg);\n}\n\n}\n\n#spinnerContainer.cooldown.tp-yt-paper-spinner-lite {\n  -webkit-animation: container-rotate var(--paper-spinner-container-rotation-duration) linear infinite, fade-out var(--paper-spinner-cooldown-duration) cubic-bezier(0.4, 0, 0.2, 1);\n  animation: container-rotate var(--paper-spinner-container-rotation-duration) linear infinite, fade-out var(--paper-spinner-cooldown-duration) cubic-bezier(0.4, 0, 0.2, 1);\n}\n\n@-webkit-keyframes fade-out {\n0% {\n  opacity: 1;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@keyframes fade-out {\n0% {\n  opacity: 1;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\ntp-yt-paper-tooltip {\n  display: block;\n  position: absolute;\n  outline: none;\n  z-index: 1002;\n  -moz-user-select: none;\n  -ms-user-select: none;\n  -webkit-user-select: none;\n  user-select: none;\n  cursor: default;\n}\n\n.tp-yt-paper-tooltip[style-target=tooltip] {\n  display: block;\n  outline: none;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 10px;\n  line-height: 1;\n  background-color: var(--paper-tooltip-background, #616161);\n  color: var(--paper-tooltip-text-color, white);\n  padding: 8px;\n  border-radius: 2px;\n}\n\n@keyframes keyFrameScaleUp {\n0% {\n  transform: scale(0);\n}\n\n100% {\n  transform: scale(1);\n}\n\n}\n\n@keyframes keyFrameScaleDown {\n0% {\n  transform: scale(1);\n}\n\n100% {\n  transform: scale(0);\n}\n\n}\n\n@keyframes keyFrameFadeInOpacity {\n0% {\n  opacity: 0;\n}\n\n100% {\n  opacity: var(--paper-tooltip-opacity, 0.9);\n}\n\n}\n\n@keyframes keyFrameFadeOutOpacity {\n0% {\n  opacity: var(--paper-tooltip-opacity, 0.9);\n}\n\n100% {\n  opacity: 0;\n}\n\n}\n\n@keyframes keyFrameSlideDownIn {\n0% {\n  transform: translateY(-2000px);\n    opacity: 0;\n}\n\n10% {\n  opacity: 0.2;\n}\n\n100% {\n  transform: translateY(0);\n    opacity: var(--paper-tooltip-opacity, 0.9);\n}\n\n}\n\n@keyframes keyFrameSlideDownOut {\n0% {\n  transform: translateY(0);\n    opacity: var(--paper-tooltip-opacity, 0.9);\n}\n\n10% {\n  opacity: 0.2;\n}\n\n100% {\n  transform: translateY(-2000px);\n    opacity: 0;\n}\n\n}\n\n.fade-in-animation.tp-yt-paper-tooltip {\n  opacity: 0;\n  animation-delay: var(--paper-tooltip-delay-in, 500ms);\n  animation-name: keyFrameFadeInOpacity;\n  animation-iteration-count: 1;\n  animation-timing-function: ease-in;\n  animation-duration: var(--paper-tooltip-duration-in, 500ms);\n  animation-fill-mode: forwards;\n}\n\n.fade-out-animation.tp-yt-paper-tooltip {\n  opacity: var(--paper-tooltip-opacity, 0.9);\n  animation-delay: var(--paper-tooltip-delay-out, 0ms);\n  animation-name: keyFrameFadeOutOpacity;\n  animation-iteration-count: 1;\n  animation-timing-function: ease-in;\n  animation-duration: var(--paper-tooltip-duration-out, 500ms);\n  animation-fill-mode: forwards;\n}\n\n.scale-up-animation.tp-yt-paper-tooltip {\n  transform: scale(0);\n  opacity: var(--paper-tooltip-opacity, 0.9);\n  animation-delay: var(--paper-tooltip-delay-in, 500ms);\n  animation-name: keyFrameScaleUp;\n  animation-iteration-count: 1;\n  animation-timing-function: ease-in;\n  animation-duration: var(--paper-tooltip-duration-in, 500ms);\n  animation-fill-mode: forwards;\n}\n\n.scale-down-animation.tp-yt-paper-tooltip {\n  transform: scale(1);\n  opacity: var(--paper-tooltip-opacity, 0.9);\n  animation-delay: var(--paper-tooltip-delay-out, 500ms);\n  animation-name: keyFrameScaleDown;\n  animation-iteration-count: 1;\n  animation-timing-function: ease-in;\n  animation-duration: var(--paper-tooltip-duration-out, 500ms);\n  animation-fill-mode: forwards;\n}\n\n.slide-down-animation.tp-yt-paper-tooltip {\n  transform: translateY(-2000px);\n  opacity: 0;\n  animation-delay: var(--paper-tooltip-delay-out, 500ms);\n  animation-name: keyFrameSlideDownIn;\n  animation-iteration-count: 1;\n  animation-timing-function: cubic-bezier(0, 0, 0.2, 1);\n  animation-duration: var(--paper-tooltip-duration-out, 500ms);\n  animation-fill-mode: forwards;\n}\n\n.slide-down-animation-out.tp-yt-paper-tooltip {\n  transform: translateY(0);\n  opacity: var(--paper-tooltip-opacity, 0.9);\n  animation-delay: var(--paper-tooltip-delay-out, 500ms);\n  animation-name: keyFrameSlideDownOut;\n  animation-iteration-count: 1;\n  animation-timing-function: cubic-bezier(0.4, 0, 1, 1);\n  animation-duration: var(--paper-tooltip-duration-out, 500ms);\n  animation-fill-mode: forwards;\n}\n\n.cancel-animation.tp-yt-paper-tooltip {\n  animation-delay: -30s !important;\n}\n\n.hidden.tp-yt-paper-tooltip {\n  display: none !important;\n}\n\niron-a11y-announcer {\n  display: inline-block;\n        position: fixed;\n        clip: rect(0px,0px,0px,0px);\n}\n\niron-collapse {\n  display: block;\n        transition-duration: var(--iron-collapse-transition-duration, 300ms);\n        \n        -webkit-transition-duration: var(--iron-collapse-transition-duration, 300ms);\n        overflow: visible;\n}\n\niron-collapse.iron-collapse-closed {\n  display: none;\n}\n\niron-collapse:not(.iron-collapse-opened) {\n  overflow: hidden;\n}\n\niron-image {\n  display: inline-block;\n        overflow: hidden;\n        position: relative;\n}\n\n#baseURIAnchor.iron-image {\n  display: none;\n}\n\n#sizedImgDiv.iron-image {\n  position: absolute;\n        top: 0px;\n        right: 0px;\n        bottom: 0px;\n        left: 0px;\n\n        display: none;\n}\n\n#img.iron-image {\n  display: block;\n        width: var(--iron-image-width, auto);\n        height: var(--iron-image-height, auto);\n}\n\niron-image[sizing] #sizedImgDiv.iron-image {\n  display: block;\n}\n\niron-image[sizing] #img.iron-image {\n  display: none;\n}\n\n#placeholder.iron-image {\n  position: absolute;\n        top: 0px;\n        right: 0px;\n        bottom: 0px;\n        left: 0px;\n\n        background-color: inherit;\n        opacity: 1;\n\n        ;\n}\n\n#placeholder.faded-out.iron-image {\n  transition: opacity 0.5s linear;\n        opacity: 0;\n}\n\niron-input {\n  display: inline-block;\n}\n\niron-pages {\n  display: block;\n}\n\niron-pages > :not(slot):not(.iron-selected) {\n  display: none !important;\n}\n\npaper-tooltip {\n  display: block;\n        position: absolute;\n        outline: none;\n        z-index: 1002;\n        -moz-user-select: none;\n        -ms-user-select: none;\n        -webkit-user-select: none;\n        user-select: none;\n        cursor: default;\n}\n\n#tooltip.paper-tooltip {\n  display: block;\n        outline: none;\n        ;\n        font-size: 10px;\n        line-height: 1;\n        background-color: var(--paper-tooltip-background, #616161);\n        color: var(--paper-tooltip-text-color, white);\n        padding: 8px;\n        border-radius: 2px;\n        ;\n}\n\n@keyframes keyFrameScaleUp {\n0% {\n  transform: scale(0.0);\n}\n\n100% {\n  transform: scale(1.0);\n}\n\n}\n\n@keyframes keyFrameScaleDown {\n0% {\n  transform: scale(1.0);\n}\n\n100% {\n  transform: scale(0.0);\n}\n\n}\n\n@keyframes keyFrameFadeInOpacity {\n0% {\n  opacity: 0;\n}\n\n100% {\n  opacity: var(--paper-tooltip-opacity, 0.9);\n}\n\n}\n\n@keyframes keyFrameFadeOutOpacity {\n0% {\n  opacity: var(--paper-tooltip-opacity, 0.9);\n}\n\n100% {\n  opacity: 0;\n}\n\n}\n\n@keyframes keyFrameSlideDownIn {\n0% {\n  transform: translateY(-2000px);\n          opacity: 0;\n}\n\n10% {\n  opacity: 0.2;\n}\n\n100% {\n  transform: translateY(0);\n          opacity: var(--paper-tooltip-opacity, 0.9);\n}\n\n}\n\n@keyframes keyFrameSlideDownOut {\n0% {\n  transform: translateY(0);\n          opacity: var(--paper-tooltip-opacity, 0.9);\n}\n\n10% {\n  opacity: 0.2;\n}\n\n100% {\n  transform: translateY(-2000px);\n          opacity: 0;\n}\n\n}\n\n.fade-in-animation.paper-tooltip {\n  opacity: 0;\n        animation-delay: var(--paper-tooltip-delay-in, 500ms);\n        animation-name: keyFrameFadeInOpacity;\n        animation-iteration-count: 1;\n        animation-timing-function: ease-in;\n        animation-duration: var(--paper-tooltip-duration-in, 500ms);\n        animation-fill-mode: forwards;\n        ;\n}\n\n.fade-out-animation.paper-tooltip {\n  opacity: var(--paper-tooltip-opacity, 0.9);\n        animation-delay: var(--paper-tooltip-delay-out, 0ms);\n        animation-name: keyFrameFadeOutOpacity;\n        animation-iteration-count: 1;\n        animation-timing-function: ease-in;\n        animation-duration: var(--paper-tooltip-duration-out, 500ms);\n        animation-fill-mode: forwards;\n        ;\n}\n\n.scale-up-animation.paper-tooltip {\n  transform: scale(0);\n        opacity: var(--paper-tooltip-opacity, 0.9);\n        animation-delay: var(--paper-tooltip-delay-in, 500ms);\n        animation-name: keyFrameScaleUp;\n        animation-iteration-count: 1;\n        animation-timing-function: ease-in;\n        animation-duration: var(--paper-tooltip-duration-in, 500ms);\n        animation-fill-mode: forwards;\n        ;\n}\n\n.scale-down-animation.paper-tooltip {\n  transform: scale(1);\n        opacity: var(--paper-tooltip-opacity, 0.9);\n        animation-delay: var(--paper-tooltip-delay-out, 500ms);\n        animation-name: keyFrameScaleDown;\n        animation-iteration-count: 1;\n        animation-timing-function: ease-in;\n        animation-duration: var(--paper-tooltip-duration-out, 500ms);\n        animation-fill-mode: forwards;\n        ;\n}\n\n.slide-down-animation.paper-tooltip {\n  transform: translateY(-2000px);\n        opacity: 0;\n        animation-delay: var(--paper-tooltip-delay-out, 500ms);\n        animation-name: keyFrameSlideDownIn;\n        animation-iteration-count: 1;\n        animation-timing-function: cubic-bezier(0.0, 0.0, 0.2, 1);\n        animation-duration: var(--paper-tooltip-duration-out, 500ms);\n        animation-fill-mode: forwards;\n        ;\n}\n\n.slide-down-animation-out.paper-tooltip {\n  transform: translateY(0);\n        opacity: var(--paper-tooltip-opacity, 0.9);\n        animation-delay: var(--paper-tooltip-delay-out, 500ms);\n        animation-name: keyFrameSlideDownOut;\n        animation-iteration-count: 1;\n        animation-timing-function: cubic-bezier(0.4, 0.0, 1, 1);\n        animation-duration: var(--paper-tooltip-duration-out, 500ms);\n        animation-fill-mode: forwards;\n        ;\n}\n\n.cancel-animation.paper-tooltip {\n  animation-delay: -30s !important;\n}\n\n.hidden.paper-tooltip {\n  display: none !important;\n}\n\ntp-yt-app-header-layout {\n  display: block;\n  position: relative;\n  z-index: 0;\n}\n\n#wrapper.tp-yt-app-header-layout > [slot=header] {\n  position: fixed;\n  top: 0;\n  left: 0;\n  right: 0;\n  z-index: 1;\n}\n\n#wrapper.initializing.tp-yt-app-header-layout > [slot=header] {\n  position: relative;\n}\n\ntp-yt-app-header-layout[has-scrolling-region] {\n  height: 100%;\n}\n\ntp-yt-app-header-layout[has-scrolling-region] #wrapper.tp-yt-app-header-layout > [slot=header] {\n  position: absolute;\n}\n\ntp-yt-app-header-layout[has-scrolling-region] #wrapper.initializing.tp-yt-app-header-layout > [slot=header] {\n  position: relative;\n}\n\ntp-yt-app-header-layout[has-scrolling-region] #wrapper.tp-yt-app-header-layout #contentContainer.tp-yt-app-header-layout {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n  overflow-y: auto;\n  -webkit-overflow-scrolling: touch;\n}\n\ntp-yt-app-header-layout[has-scrolling-region] #wrapper.initializing.tp-yt-app-header-layout #contentContainer.tp-yt-app-header-layout {\n  position: relative;\n}\n\ntp-yt-app-header-layout[fullbleed] {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: column;\n  -webkit-flex-direction: column;\n  flex-direction: column;\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n}\n\ntp-yt-app-header-layout[fullbleed] #wrapper.tp-yt-app-header-layout,tp-yt-app-header-layout[fullbleed] #wrapper.tp-yt-app-header-layout #contentContainer.tp-yt-app-header-layout {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: column;\n  -webkit-flex-direction: column;\n  flex-direction: column;\n  -ms-flex: 1 1 0.000000001px;\n  -webkit-flex: 1;\n  flex: 1;\n  -webkit-flex-basis: 0.000000001px;\n  flex-basis: 0.000000001px;\n}\n\n#contentContainer.tp-yt-app-header-layout {\n  position: relative;\n  z-index: 0;\n}\n\n@media print {\ntp-yt-app-header-layout[has-scrolling-region] #wrapper.tp-yt-app-header-layout #contentContainer.tp-yt-app-header-layout {\n  overflow-y: visible;\n}\n\n}\n\ntp-yt-app-header {\n  position: relative;\n  display: block;\n  transition-timing-function: linear;\n  transition-property: -webkit-transform;\n  transition-property: transform;\n}\n\ntp-yt-app-header::before {\n  position: absolute;\n  right: 0px;\n  bottom: -5px;\n  left: 0px;\n  width: 100%;\n  height: 5px;\n  content: \"\";\n  transition: opacity 0.4s;\n  pointer-events: none;\n  opacity: 0;\n  box-shadow: inset 0px 5px 6px -3px rgba(0, 0, 0, 0.4);\n  will-change: opacity;\n}\n\ntp-yt-app-header[shadow]::before {\n  opacity: 1;\n}\n\n#background.tp-yt-app-header {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n  overflow: hidden;\n}\n\n#backgroundFrontLayer.tp-yt-app-header,#backgroundRearLayer.tp-yt-app-header {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n  height: 100%;\n  pointer-events: none;\n  background-size: cover;\n}\n\n#backgroundFrontLayer.tp-yt-app-header {\n  background-image: var(--app-header-background-front-layer-background-image);\n  background-position: var(--app-header-background-front-layer-background-position);\n  background-repeat: var(--app-header-background-front-layer-background-repeat);\n  background-size: var(--app-header-background-front-layer-background-size);\n}\n\n#backgroundRearLayer.tp-yt-app-header {\n  opacity: 0;\n}\n\n#contentContainer.tp-yt-app-header {\n  position: relative;\n  width: 100%;\n  height: 100%;\n}\n\ntp-yt-app-header[disabled],tp-yt-app-header[disabled]::after,tp-yt-app-header[disabled] #backgroundFrontLayer.tp-yt-app-header,tp-yt-app-header[disabled] #backgroundRearLayer.tp-yt-app-header,tp-yt-app-header[silent-scroll],tp-yt-app-header[silent-scroll]::after,tp-yt-app-header[silent-scroll] #backgroundFrontLayer.tp-yt-app-header,tp-yt-app-header[silent-scroll] #backgroundRearLayer.tp-yt-app-header {\n  transition: none !important;\n}\n\ntp-yt-app-header[disabled] > app-toolbar:first-of-type,tp-yt-app-header[disabled] > [sticky],tp-yt-app-header[silent-scroll] > app-toolbar:first-of-type,tp-yt-app-header[silent-scroll] > [sticky] {\n  transition: none !important;\n}\n\ntp-yt-app-toolbar {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row;\n  -webkit-flex-direction: row;\n  flex-direction: row;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  position: relative;\n  height: 64px;\n  padding: 0 16px;\n  pointer-events: none;\n  font-size: var(--app-toolbar-font-size, 20px);\n}\n\ntp-yt-app-toolbar > * {\n  pointer-events: auto;\n}\n\ntp-yt-app-toolbar > paper-icon-button {\n  font-size: 0;\n}\n\ntp-yt-app-toolbar > [main-title],tp-yt-app-toolbar > [condensed-title] {\n  pointer-events: none;\n  -ms-flex: 1 1 0.000000001px;\n  -webkit-flex: 1;\n  flex: 1;\n  -webkit-flex-basis: 0.000000001px;\n  flex-basis: 0.000000001px;\n}\n\ntp-yt-app-toolbar > [bottom-item] {\n  position: absolute;\n  right: 0;\n  bottom: 0;\n  left: 0;\n}\n\ntp-yt-app-toolbar > [top-item] {\n  position: absolute;\n  top: 0;\n  right: 0;\n  left: 0;\n}\n\ntp-yt-app-toolbar > [spacer] {\n  margin-left: 64px;\n}\n\ntp-yt-iron-autogrow-textarea {\n  display: inline-block;\n  position: relative;\n  width: 400px;\n  border: 1px solid;\n  padding: 2px;\n  -moz-appearance: textarea;\n  -webkit-appearance: textarea;\n  overflow: hidden;\n}\n\n.mirror-text.tp-yt-iron-autogrow-textarea {\n  visibility: hidden;\n  word-wrap: break-word;\n  white-space: pre-wrap;\n}\n\n.fit.tp-yt-iron-autogrow-textarea {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n}\n\ntextarea.tp-yt-iron-autogrow-textarea {\n  position: relative;\n  outline: none;\n  border: none;\n  resize: none;\n  background: inherit;\n  color: inherit;\n  width: 100%;\n  height: 100%;\n  font-size: inherit;\n  font-family: inherit;\n  line-height: inherit;\n  text-align: inherit;\n}\n\ntextarea.tp-yt-iron-autogrow-textarea::-webkit-input-placeholder {\n  padding: var(--iron-autogrow-textarea-placeholder-padding);\n}\n\ntextarea.tp-yt-iron-autogrow-textarea:-moz-placeholder {\n  padding: var(--iron-autogrow-textarea-placeholder-padding);\n}\n\ntextarea.tp-yt-iron-autogrow-textarea::-moz-placeholder {\n  padding: var(--iron-autogrow-textarea-placeholder-padding);\n}\n\ntextarea.tp-yt-iron-autogrow-textarea:-ms-input-placeholder {\n  padding: var(--iron-autogrow-textarea-placeholder-padding);\n}\n\ntp-yt-iron-overlay-backdrop {\n  position: fixed;\n  top: 0;\n  left: 0;\n  width: 100%;\n  height: 100%;\n  background-color: var(--iron-overlay-backdrop-background-color, #000);\n  opacity: 0;\n  transition: opacity 0.2s;\n  pointer-events: none;\n}\n\ntp-yt-iron-overlay-backdrop.opened {\n  opacity: var(--iron-overlay-backdrop-opacity, 0.6);\n  pointer-events: auto;\n  z-index: var(--iron-overlay-backdrop-opened-z-index);\n}\n\ntp-yt-iron-dropdown {\n  position: fixed;\n}\n\n#contentWrapper.tp-yt-iron-dropdown > * {\n  overflow: auto;\n}\n\n#contentWrapper.animating.tp-yt-iron-dropdown > * {\n  overflow: hidden;\n  pointer-events: none;\n}\n\ntp-yt-iron-icon {\n  display: -ms-inline-flexbox;\n  display: -webkit-inline-flex;\n  display: inline-flex;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  -ms-flex-pack: center;\n  -webkit-justify-content: center;\n  justify-content: center;\n  position: relative;\n  vertical-align: middle;\n  fill: var(--iron-icon-fill-color, currentcolor);\n  stroke: var(--iron-icon-stroke-color, none);\n  width: var(--iron-icon-width, 24px);\n  height: var(--iron-icon-height, 24px);\n  animation: var(--iron-icon-animation);\n  margin-top: var(--iron-icon-margin-top);\n  margin-right: var(--iron-icon-margin-right);\n  margin-bottom: var(--iron-icon-margin-bottom);\n  margin-left: var(--iron-icon-margin-left);\n  padding: var(--iron-icon-padding);\n}\n\ntp-yt-iron-icon[hidden] {\n  display: none;\n}\n\ntp-yt-iron-list {\n  display: block;\n}\n\n@media only screen and (-webkit-max-device-pixel-ratio: 1) {\ntp-yt-iron-list {\n  will-change: transform;\n}\n\n}\n\n#items.tp-yt-iron-list {\n  position: relative;\n}\n\ntp-yt-iron-list:not([grid]) #items.tp-yt-iron-list > * {\n  width: 100%;\n}\n\n#items.tp-yt-iron-list > * {\n  box-sizing: border-box;\n  margin: 0;\n  position: absolute;\n  top: 0;\n  will-change: transform;\n}\n\ntp-yt-paper-card {\n  position: relative;\n  box-sizing: border-box;\n  background-color: var(--paper-card-background-color, var(--primary-background-color));\n  border-radius: 2px;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  display: var(--paper-card-display, inline-block);\n}\n\ntp-yt-paper-card[hidden],.tp-yt-paper-card[hidden] {\n  display: none !important;\n}\n\n.header.tp-yt-paper-card {\n  position: relative;\n  border-top-left-radius: inherit;\n  border-top-right-radius: inherit;\n  overflow: hidden;\n}\n\n.header.tp-yt-paper-card iron-image.tp-yt-paper-card {\n  display: block;\n  width: 100%;\n  --iron-image-width: 100%;\n  pointer-events: none;\n}\n\n.header.tp-yt-paper-card .title-text.tp-yt-paper-card {\n  color: var(--paper-card-header-color, #000);\n}\n\n.header.tp-yt-paper-card .title-text.over-image.tp-yt-paper-card {\n  position: absolute;\n  bottom: 0px;\n}\n\ntp-yt-paper-card > .card-content {\n  position: relative;\n}\n\ntp-yt-paper-card > .card-actions {\n  border-top: 1px solid #e8e8e8;\n  position: relative;\n}\n\ntp-yt-paper-card[elevation=\"1\"] {\n  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);\n}\n\ntp-yt-paper-card[elevation=\"2\"] {\n  box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-card[elevation=\"3\"] {\n  box-shadow: 0 6px 10px 0 rgba(0, 0, 0, 0.14), 0 1px 18px 0 rgba(0, 0, 0, 0.12), 0 3px 5px -1px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-card[elevation=\"4\"] {\n  box-shadow: 0 8px 10px 1px rgba(0, 0, 0, 0.14), 0 3px 14px 2px rgba(0, 0, 0, 0.12), 0 5px 5px -3px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-card[elevation=\"5\"] {\n  box-shadow: 0 16px 24px 2px rgba(0, 0, 0, 0.14), 0 6px 30px 5px rgba(0, 0, 0, 0.12), 0 8px 10px -5px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-checkbox {\n  display: inline-block;\n  white-space: nowrap;\n  cursor: pointer;\n  --calculated-paper-checkbox-size: var(--paper-checkbox-size, 18px);\n  --calculated-paper-checkbox-ink-size: var(--paper-checkbox-ink-size, -1px);\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  line-height: 0;\n  -webkit-tap-highlight-color: transparent;\n}\n\ntp-yt-paper-checkbox[hidden] {\n  display: none !important;\n}\n\ntp-yt-paper-checkbox:focus {\n  outline: none;\n}\n\n.hidden.tp-yt-paper-checkbox {\n  display: none;\n}\n\n#checkboxContainer.tp-yt-paper-checkbox {\n  display: inline-block;\n  position: relative;\n  width: var(--calculated-paper-checkbox-size);\n  height: var(--calculated-paper-checkbox-size);\n  min-width: var(--calculated-paper-checkbox-size);\n  margin: var(--paper-checkbox-margin, initial);\n  vertical-align: var(--paper-checkbox-vertical-align, middle);\n  background-color: var(--paper-checkbox-unchecked-background-color, transparent);\n}\n\n#ink.tp-yt-paper-checkbox {\n  position: absolute;\n  top: calc(0px - (var(--calculated-paper-checkbox-ink-size) - var(--calculated-paper-checkbox-size)) / 2);\n  left: calc(0px - (var(--calculated-paper-checkbox-ink-size) - var(--calculated-paper-checkbox-size)) / 2);\n  width: var(--calculated-paper-checkbox-ink-size);\n  height: var(--calculated-paper-checkbox-ink-size);\n  color: var(--paper-checkbox-unchecked-ink-color, var(--primary-text-color));\n  opacity: 0.6;\n  pointer-events: none;\n}\n\n[dir=\"rtl\"] #ink.tp-yt-paper-checkbox, #ink.tp-yt-paper-checkbox[dir=\"rtl\"] {\n  right: calc(0px - (var(--calculated-paper-checkbox-ink-size) - var(--calculated-paper-checkbox-size)) / 2);\n  left: auto;\n}\n\n#ink.tp-yt-paper-checkbox[checked] {\n  color: var(--paper-checkbox-checked-ink-color, var(--primary-color));\n}\n\n#checkbox.tp-yt-paper-checkbox {\n  position: relative;\n  box-sizing: border-box;\n  height: 100%;\n  border: solid 2px;\n  border-color: var(--paper-checkbox-unchecked-color, var(--primary-text-color));\n  border-radius: 2px;\n  pointer-events: none;\n  -webkit-transition: background-color 140ms, border-color 140ms;\n  transition: background-color 140ms, border-color 140ms;\n  -webkit-transition-duration: var(--paper-checkbox-animation-duration, 140ms);\n  transition-duration: var(--paper-checkbox-animation-duration, 140ms);\n}\n\n#checkbox.checked.tp-yt-paper-checkbox #checkmark.tp-yt-paper-checkbox {\n  -webkit-animation: checkmark-expand 140ms ease-out forwards;\n  animation: checkmark-expand 140ms ease-out forwards;\n  -webkit-animation-duration: var(--paper-checkbox-animation-duration, 140ms);\n  animation-duration: var(--paper-checkbox-animation-duration, 140ms);\n}\n\n@-webkit-keyframes checkmark-expand {\n0% {\n  -webkit-transform: scale(0, 0) rotate(45deg);\n}\n\n100% {\n  -webkit-transform: scale(1, 1) rotate(45deg);\n}\n\n}\n\n@keyframes checkmark-expand {\n0% {\n  transform: scale(0, 0) rotate(45deg);\n}\n\n100% {\n  transform: scale(1, 1) rotate(45deg);\n}\n\n}\n\n#checkbox.checked.tp-yt-paper-checkbox {\n  background-color: var(--paper-checkbox-checked-color, var(--primary-color));\n  border-color: var(--paper-checkbox-checked-color, var(--primary-color));\n}\n\n#checkmark.tp-yt-paper-checkbox {\n  position: absolute;\n  width: 36%;\n  height: 70%;\n  border-style: solid;\n  border-top: none;\n  border-left: none;\n  border-right-width: calc(0.1333333333 * var(--calculated-paper-checkbox-size));\n  border-bottom-width: calc(0.1333333333 * var(--calculated-paper-checkbox-size));\n  border-color: var(--paper-checkbox-checkmark-color, white);\n  -webkit-transform-origin: 97% 86%;\n  transform-origin: 97% 86%;\n  box-sizing: content-box;\n}\n\n[dir=\"rtl\"] #checkmark.tp-yt-paper-checkbox, #checkmark.tp-yt-paper-checkbox[dir=\"rtl\"] {\n  -webkit-transform-origin: 50% 14%;\n  transform-origin: 50% 14%;\n}\n\ntp-yt-paper-checkbox tp-yt-paper-checkbox .tp-yt-paper-checkbox[style-target=label],.tp-yt-paper-checkbox[style-target=label] {\n  position: relative;\n  display: inline-block;\n  vertical-align: middle;\n  padding-left: var(--paper-checkbox-label-spacing, 8px);\n  white-space: normal;\n  line-height: normal;\n  color: var(--paper-checkbox-label-color, var(--primary-text-color));\n}\n\n[dir=\"rtl\"] tp-yt-paper-checkbox .tp-yt-paper-checkbox[style-target=label], tp-yt-paper-checkbox tp-yt-paper-checkbox[dir=\"rtl\"] .tp-yt-paper-checkbox[style-target=label],[dir=\"rtl\"] .tp-yt-paper-checkbox[style-target=label].tp-yt-paper-checkbox, .tp-yt-paper-checkbox[style-target=label].tp-yt-paper-checkbox[dir=\"rtl\"] {\n  padding-right: var(--paper-checkbox-label-spacing, 8px);\n  padding-left: 0;\n}\n\ntp-yt-paper-checkbox tp-yt-paper-checkbox[hidden] .tp-yt-paper-checkbox[style-target=label],.tp-yt-paper-checkbox[style-target=label].tp-yt-paper-checkbox[hidden] {\n  display: none;\n}\n\ntp-yt-paper-checkbox tp-yt-paper-checkbox[hidden] .tp-yt-paper-checkbox[style-target=label] {\n  display: none;\n}\n\ntp-yt-paper-checkbox tp-yt-paper-checkbox[checked] .tp-yt-paper-checkbox[style-target=label],tp-yt-paper-checkbox[checked] .tp-yt-paper-checkbox[style-target=label] {\n  color: var(--paper-checkbox-label-checked-color, var(--paper-checkbox-label-color, var(--primary-text-color)));\n}\n\ntp-yt-paper-checkbox[disabled] #checkbox.tp-yt-paper-checkbox {\n  opacity: 0.5;\n  border-color: var(--paper-checkbox-unchecked-color, var(--primary-text-color));\n}\n\ntp-yt-paper-checkbox[disabled][checked] #checkbox.tp-yt-paper-checkbox {\n  background-color: var(--paper-checkbox-unchecked-color, var(--primary-text-color));\n  opacity: 0.5;\n}\n\ntp-yt-paper-checkbox tp-yt-paper-checkbox[disabled] .tp-yt-paper-checkbox[style-target=label],tp-yt-paper-checkbox[disabled] .tp-yt-paper-checkbox[style-target=label] {\n  opacity: 0.65;\n}\n\n#checkbox.invalid.tp-yt-paper-checkbox:not(.checked) {\n  border-color: var(--paper-checkbox-error-color, var(--error-color));\n}\n\ntp-yt-paper-dialog {\n  display: block;\n  margin: 24px 40px;\n  background: var(--paper-dialog-background-color, var(--primary-background-color));\n  color: var(--paper-dialog-color, var(--primary-text-color));\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 14px;\n  font-weight: 400;\n  line-height: 20px;\n  box-shadow: 0 16px 24px 2px rgba(0, 0, 0, 0.14), 0 6px 30px 5px rgba(0, 0, 0, 0.12), 0 8px 10px -5px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-dialog > * {\n  margin-top: 20px;\n  padding: 0 24px;\n}\n\ntp-yt-paper-dialog > .no-padding {\n  padding: 0;\n}\n\ntp-yt-paper-dialog[modern] {\n  border-radius: 12px;\n  overflow: hidden;\n  box-shadow: 0 0 24px 12px var(--paper-dialog-shadow-color, rgba(0, 0, 0, 0.15));\n}\n\ntp-yt-paper-dialog > *:first-child {\n  margin-top: 24px;\n}\n\ntp-yt-paper-dialog > *:last-child {\n  margin-bottom: 24px;\n}\n\ntp-yt-paper-dialog > h2 {\n  position: relative;\n  margin: 0;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  white-space: nowrap;\n  overflow: hidden;\n  text-overflow: ellipsis;\n  font-size: 20px;\n  font-weight: 500;\n  line-height: 28px;\n}\n\ntp-yt-paper-dialog > h2:first-child {\n  margin-top: 24px;\n}\n\ntp-yt-paper-dialog > h2:last-child {\n  margin-bottom: 24px;\n}\n\ntp-yt-paper-dialog > .paper-dialog-buttons,tp-yt-paper-dialog > .buttons {\n  position: relative;\n  padding: 8px 8px 8px 24px;\n  margin: 0;\n  color: var(--paper-dialog-button-color, var(--primary-color));\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row;\n  -webkit-flex-direction: row;\n  flex-direction: row;\n  -ms-flex-pack: end;\n  -webkit-justify-content: flex-end;\n  justify-content: flex-end;\n}\n\ntp-yt-paper-dialog-scrollable {\n  display: block;\n  position: relative;\n}\n\ntp-yt-paper-dialog-scrollable.is-scrolled:not(:first-child)::before {\n  content: \"\";\n  position: absolute;\n  top: 0;\n  left: 0;\n  right: 0;\n  height: 1px;\n  background: var(--divider-color);\n}\n\ntp-yt-paper-dialog-scrollable.can-scroll:not(.scrolled-to-bottom):not(:last-child)::after {\n  content: \"\";\n  position: absolute;\n  bottom: 0;\n  left: 0;\n  right: 0;\n  height: 1px;\n  background: var(--divider-color);\n}\n\n.scrollable.tp-yt-paper-dialog-scrollable {\n  -webkit-overflow-scrolling: touch;\n  overflow: auto;\n  box-sizing: var(--paper-dialog-scrollable-box-sizing);\n  height: var(--paper-dialog-scrollable-height);\n  min-width: var(--paper-dialog-scrollable-min-width);\n  overflow-x: var(--paper-dialog-scrollable-overflow-x);\n  padding: var(--paper-dialog-scrollable-padding, 0 24px);\n}\n\n.fit.tp-yt-paper-dialog-scrollable {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n}\n\ntp-yt-paper-menu-button {\n  display: inline-block;\n  position: relative;\n  outline: none;\n  background-color: var(--paper-menu-button-background-color);\n  border-radius: var(--paper-menu-button-border-radius);\n  padding: var(--paper-menu-button-padding, 8px);\n  width: var(--paper-menu-button-width);\n}\n\ntp-yt-paper-menu-button[disabled] {\n  cursor: auto;\n  color: var(--disabled-text-color);\n  opacity: var(--paper-menu-button-disabled-opacity);\n}\n\ntp-yt-iron-dropdown.tp-yt-paper-menu-button {\n  max-height: var(--paper-menu-button-dropdown-max-height);\n  width: var(--paper-menu-button-dropdown-width);\n}\n\n.dropdown-content.tp-yt-paper-menu-button {\n  background: var(--paper-menu-button-content-background);\n  background-color: var(--paper-menu-button-content-background-color, var(--paper-menu-button-dropdown-background, var(--primary-background-color)));\n  border-radius: var(--paper-menu-button-content-border-radius, 2px);\n  box-shadow: var(--paper-menu-button-content-box-shadow, 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2));\n  position: var(--paper-menu-button-content-position, relative);\n}\n\ntp-yt-paper-menu-button[vertical-align=top] .dropdown-content.tp-yt-paper-menu-button {\n  margin-bottom: 20px;\n  margin-top: -10px;\n  top: 10px;\n}\n\ntp-yt-paper-menu-button[vertical-align=bottom] .dropdown-content.tp-yt-paper-menu-button {\n  bottom: 10px;\n  margin-bottom: -10px;\n  margin-top: 20px;\n}\n\n#trigger.tp-yt-paper-menu-button {\n  cursor: pointer;\n}\n\ntp-yt-paper-dropdown-menu-light {\n  display: inline-block;\n  position: relative;\n  text-align: left;\n  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);\n  -webkit-tap-highlight-color: transparent;\n  --paper-input-container-input_-_overflow:  hidden; --paper-input-container-input_-_white-space:  nowrap; --paper-input-container-input_-_text-overflow:  ellipsis; --paper-input-container-input_-_max-width:  100%; --paper-input-container-input_-_box-sizing:  border-box; --paper-input-container-input_-_cursor:  pointer; --paper-input-container-input_-_text-align: initial;;\n}\n\ntp-yt-paper-dropdown-menu-light:focus {\n  outline: none;\n}\n\n[dir=\"rtl\"] tp-yt-paper-dropdown-menu-light, tp-yt-paper-dropdown-menu-light[dir=\"rtl\"] {\n  text-align: right;\n}\n\ntp-yt-paper-dropdown-menu-light[noink] paper-ripple.tp-yt-paper-dropdown-menu-light {\n  display: none;\n}\n\ntp-yt-paper-dropdown-menu-light[no-label-float] paper-ripple.tp-yt-paper-dropdown-menu-light {\n  top: 8px;\n}\n\npaper-ripple.tp-yt-paper-dropdown-menu-light {\n  top: 12px;\n  left: 0px;\n  bottom: 8px;\n  right: 0px;\n}\n\ntp-yt-paper-menu-button.tp-yt-paper-dropdown-menu-light {\n  display: block;\n  padding: 0;\n}\n\ntp-yt-iron-icon.tp-yt-paper-dropdown-menu-light {\n  color: var(--paper-dropdown-menu-icon-color, var(--disabled-text-color));\n}\n\ntp-yt-paper-dropdown-menu-light {\n  width: 200px;\n}\n\n.tp-yt-paper-dropdown-menu-light[slot=dropdown-trigger] {\n  box-sizing: border-box;\n  position: relative;\n  width: 100%;\n  padding: 16px 0 8px;\n}\n\n.tp-yt-paper-dropdown-menu-light[slot=dropdown-trigger].tp-yt-paper-dropdown-menu-light:focus {\n  outline: none;\n}\n\ntp-yt-paper-dropdown-menu-light[disabled] .tp-yt-paper-dropdown-menu-light[slot=dropdown-trigger] {\n  pointer-events: none;\n  opacity: var(--paper-dropdown-menu-disabled-opacity, 0.33);\n}\n\ntp-yt-paper-dropdown-menu-light[no-label-float] .tp-yt-paper-dropdown-menu-light[slot=dropdown-trigger] {\n  padding-top: 8px;\n}\n\ntp-yt-paper-dropdown-menu-light tp-yt-paper-dropdown-menu-light .tp-yt-paper-dropdown-menu-light[style-target=input],.tp-yt-paper-dropdown-menu-light[style-target=input] {\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  line-height: 1.5;\n  border-bottom: 1px solid var(--paper-dropdown-menu-color, var(--secondary-text-color));\n  color: var(--paper-dropdown-menu-color, var(--primary-text-color));\n  width: 100%;\n  box-sizing: border-box;\n  padding: 12px 20px 0 0;\n  outline: none;\n}\n\n[dir=\"rtl\"] tp-yt-paper-dropdown-menu-light .tp-yt-paper-dropdown-menu-light[style-target=input], tp-yt-paper-dropdown-menu-light tp-yt-paper-dropdown-menu-light[dir=\"rtl\"] .tp-yt-paper-dropdown-menu-light[style-target=input],[dir=\"rtl\"] .tp-yt-paper-dropdown-menu-light[style-target=input].tp-yt-paper-dropdown-menu-light, .tp-yt-paper-dropdown-menu-light[style-target=input].tp-yt-paper-dropdown-menu-light[dir=\"rtl\"] {\n  padding-right: 0px;\n  padding-left: 20px;\n}\n\ntp-yt-paper-dropdown-menu-light[disabled] .tp-yt-paper-dropdown-menu-light[style-target=input] {\n  border-bottom: 1px dashed var(--paper-dropdown-menu-color, var(--secondary-text-color));\n}\n\ntp-yt-paper-dropdown-menu-light[invalid] .tp-yt-paper-dropdown-menu-light[style-target=input] {\n  border-bottom: 2px solid var(--paper-dropdown-error-color, var(--error-color));\n}\n\ntp-yt-paper-dropdown-menu-light[no-label-float] .tp-yt-paper-dropdown-menu-light[style-target=input] {\n  padding-top: 0;\n}\n\n.label.tp-yt-paper-dropdown-menu-light {\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  display: block;\n  position: absolute;\n  bottom: 0;\n  left: 0;\n  right: 0;\n  top: 28px;\n  box-sizing: border-box;\n  width: 100%;\n  padding-right: 20px;\n  text-align: left;\n  transition-duration: 0.2s;\n  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);\n  color: var(--paper-dropdown-menu-color, var(--secondary-text-color));\n}\n\n[dir=\"rtl\"] .label.tp-yt-paper-dropdown-menu-light, .label.tp-yt-paper-dropdown-menu-light[dir=\"rtl\"] {\n  padding-right: 0px;\n  padding-left: 20px;\n  text-align: right;\n}\n\n.label.label-is-floating.tp-yt-paper-dropdown-menu-light {\n  font-size: 12px;\n  top: 8px;\n}\n\n.label.label-is-hidden.tp-yt-paper-dropdown-menu-light {\n  visibility: hidden;\n}\n\n.label.tp-yt-paper-dropdown-menu-light:after {\n  background-color: var(--paper-dropdown-menu-focus-color, var(--primary-color));\n  bottom: 7px;\n  content: \"\";\n  height: 2px;\n  left: 45%;\n  position: absolute;\n  transition-duration: 0.2s;\n  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);\n  visibility: hidden;\n  width: 8px;\n  z-index: 10;\n}\n\ntp-yt-paper-dropdown-menu-light[no-label-float] .label.tp-yt-paper-dropdown-menu-light,tp-yt-paper-dropdown-menu-light[no-label-float] .tp-yt-paper-dropdown-menu-light[style-target=label] {\n  top: 8px;\n  transition-duration: 0s;\n}\n\ntp-yt-paper-dropdown-menu-light[focused] .label.label-is-floating.tp-yt-paper-dropdown-menu-light,tp-yt-paper-dropdown-menu-light[focused] .tp-yt-paper-dropdown-menu-light[style-target=label].label-is-floating.tp-yt-paper-dropdown-menu-light {\n  color: var(--paper-dropdown-menu-focus-color, var(--primary-color));\n}\n\ntp-yt-paper-dropdown-menu-light[invalid] .label.label-is-floating.tp-yt-paper-dropdown-menu-light,tp-yt-paper-dropdown-menu-light[invalid] .tp-yt-paper-dropdown-menu-light[style-target=label].label-is-floating.tp-yt-paper-dropdown-menu-light {\n  color: var(--paper-dropdown-error-color, var(--error-color));\n}\n\ntp-yt-paper-dropdown-menu-light[invalid] .label.tp-yt-paper-dropdown-menu-light:after,tp-yt-paper-dropdown-menu-light[invalid] .tp-yt-paper-dropdown-menu-light[style-target=label].tp-yt-paper-dropdown-menu-light:after {\n  background-color: var(--paper-dropdown-error-color, var(--error-color));\n}\n\ntp-yt-paper-dropdown-menu-light[no-label-float] .label.tp-yt-paper-dropdown-menu-light:after,tp-yt-paper-dropdown-menu-light[no-label-float] .tp-yt-paper-dropdown-menu-light[style-target=label].tp-yt-paper-dropdown-menu-light:after {\n  bottom: 7px;\n}\n\ntp-yt-paper-dropdown-menu-light[focused]:not([disabled]) .label.tp-yt-paper-dropdown-menu-light:after,tp-yt-paper-dropdown-menu-light[focused]:not([disabled]) .tp-yt-paper-dropdown-menu-light[style-target=label].tp-yt-paper-dropdown-menu-light:after {\n  left: 0;\n  visibility: visible;\n  width: 100%;\n}\n\ntp-yt-iron-icon.tp-yt-paper-dropdown-menu-light {\n  position: absolute;\n  right: 0px;\n  bottom: 8px;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  color: var(--paper-dropdown-menu-icon-color, var(--disabled-text-color));\n}\n\n[dir=\"rtl\"] tp-yt-iron-icon.tp-yt-paper-dropdown-menu-light, tp-yt-iron-icon.tp-yt-paper-dropdown-menu-light[dir=\"rtl\"] {\n  left: 0;\n  right: auto;\n}\n\ntp-yt-paper-dropdown-menu-light[no-label-float] tp-yt-iron-icon.tp-yt-paper-dropdown-menu-light {\n  margin-top: 0px;\n}\n\n.error.tp-yt-paper-dropdown-menu-light {\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  white-space: nowrap;\n  overflow: hidden;\n  text-overflow: ellipsis;\n  font-size: 12px;\n  font-weight: 400;\n  letter-spacing: 0.011em;\n  line-height: 20px;\n  display: inline-block;\n  visibility: hidden;\n  color: var(--paper-dropdown-error-color, var(--error-color));\n  position: absolute;\n  left: 0;\n  right: 0;\n  bottom: -12px;\n}\n\ntp-yt-paper-dropdown-menu-light[invalid] .error.tp-yt-paper-dropdown-menu-light {\n  visibility: visible;\n}\n\ntp-yt-paper-input-char-counter {\n  display: inline-block;\n  float: right;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  white-space: nowrap;\n  overflow: hidden;\n  text-overflow: ellipsis;\n  font-size: 12px;\n  font-weight: 400;\n  letter-spacing: 0.011em;\n  line-height: 20px;\n}\n\ntp-yt-paper-input-char-counter[hidden] {\n  display: none !important;\n}\n\n[dir=\"rtl\"] tp-yt-paper-input-char-counter, tp-yt-paper-input-char-counter[dir=\"rtl\"] {\n  float: left;\n}\n\ntp-yt-paper-input-container {\n  display: block;\n  padding: 8px 0;\n}\n\ntp-yt-paper-input-container[inline] {\n  display: inline-block;\n}\n\ntp-yt-paper-input-container[disabled] {\n  pointer-events: none;\n  color: var(--paper-input-container-disabled-color);\n  opacity: var(--paper-input-container-disabled-opacity, 0.33);\n}\n\ntp-yt-paper-input-container[hidden] {\n  display: none !important;\n}\n\n.tp-yt-paper-input-container[hidden] {\n  display: none !important;\n}\n\n.floated-label-placeholder.tp-yt-paper-input-container {\n  display: var(--paper-input-container-floated-label-placeholder-display, block);\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  white-space: nowrap;\n  overflow: hidden;\n  text-overflow: ellipsis;\n  font-size: 12px;\n  font-weight: 400;\n  letter-spacing: 0.011em;\n  line-height: 20px;\n}\n\n.underline.tp-yt-paper-input-container {\n  height: var(--paper-input-container-underline-wrapper-height, 2px);\n  position: relative;\n}\n\n.focused-line.tp-yt-paper-input-container {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n  -webkit-transform-origin: center center;\n  transform-origin: center center;\n  -webkit-transform: scale3d(0, 1, 1);\n  transform: scale3d(0, 1, 1);\n  display: var(--paper-input-container-underline-focus-display, block);\n  border-color: var(--paper-input-container-underline-focus-border-color);\n  border-bottom: var(--paper-input-container-underline-focus-height, 2px) solid var(--paper-input-container-underline-focus-border-color, var(--paper-input-container-underline-focus-color, var(--paper-input-container-focus-color, var(--primary-color))));\n}\n\n.underline.is-highlighted.tp-yt-paper-input-container .focused-line.tp-yt-paper-input-container {\n  -webkit-transform: none;\n  transform: none;\n  -webkit-transition: -webkit-transform 0.25s;\n  transition: transform 0.25s;\n}\n\n.underline.is-invalid.tp-yt-paper-input-container .focused-line.tp-yt-paper-input-container {\n  border-bottom: var(--paper-input-container-underline-focus-height, 2px) solid var(--paper-input-container-underline-invalid-focus-color, var(--paper-input-container-invalid-color, var(--error-color)));\n  -webkit-transform: none;\n  transform: none;\n  -webkit-transition: -webkit-transform 0.25s;\n  transition: transform 0.25s;\n  display: var(--paper-input-container-underline-focus-display, block);\n}\n\n.unfocused-line.tp-yt-paper-input-container {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n  background: var(--paper-input-container-underline-background);\n  border-bottom: var(--paper-input-container-underline-border-bottom, var(--paper-input-container-underline-height, 1px solid var(--paper-input-container-underline-color, var(--paper-input-container-color, var(--secondary-text-color)))));\n  box-sizing: var(--paper-input-container-underline-box-sizing);\n  display: var(--paper-input-container-underline-display, block);\n  height: var(--paper-input-container-underline-height, var(--paper-input-container-underline-legacy-height));\n}\n\ntp-yt-paper-input-container[disabled] .unfocused-line.tp-yt-paper-input-container {\n  border-bottom: var(--paper-input-container-underline-height, 1px) var(--paper-input-container-underline-disabled-border-bottom-style, dashed) var(--paper-input-container-underline-color, var(--paper-input-container-color, var(--secondary-text-color)));\n  display: var(--paper-input-container-underline-disabled-display, block);\n}\n\n.input-wrapper.tp-yt-paper-input-container {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row;\n  -webkit-flex-direction: row;\n  flex-direction: row;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  position: relative;\n  flex: var(--paper-input-container-input-wrapper-flex);\n  min-width: var(--paper-input-container-input-wrapper-min-width);\n}\n\n.input-content.tp-yt-paper-input-container {\n  -ms-flex: 1 1 auto;\n  -webkit-flex: 1 1 auto;\n  flex: 1 1 auto;\n  position: relative;\n  max-width: 100%;\n}\n\n#labelAndInputContainer.tp-yt-paper-input-container > label,#labelAndInputContainer.tp-yt-paper-input-container > .paper-input-label {\n  position: absolute;\n  top: 0;\n  left: 0;\n  width: 100%;\n  font: inherit;\n  color: var(--paper-input-container-color, var(--secondary-text-color));\n  -webkit-transition: -webkit-transform 0.25s, width 0.25s;\n  transition: transform 0.25s, width 0.25s;\n  -webkit-transform-origin: left top;\n  transform-origin: left top;\n  min-height: 1px;\n  white-space: nowrap;\n  overflow: hidden;\n  text-overflow: ellipsis;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n}\n\n#labelAndInputContainer#labelAndInputContainer.label-is-floating.tp-yt-paper-input-container > label,#labelAndInputContainer#labelAndInputContainer.label-is-floating.tp-yt-paper-input-container > .paper-input-label {\n  -webkit-transform: translateY(-75%) scale(0.75);\n  transform: translateY(-75%) scale(0.75);\n  width: 133%;\n}\n\n[dir=\"rtl\"] tp-yt-paper-input-container #labelAndInputContainer#labelAndInputContainer.label-is-floating.tp-yt-paper-input-container > label, tp-yt-paper-input-container[dir=\"rtl\"] #labelAndInputContainer#labelAndInputContainer.label-is-floating.tp-yt-paper-input-container > label,[dir=\"rtl\"] tp-yt-paper-input-container #labelAndInputContainer#labelAndInputContainer.label-is-floating.tp-yt-paper-input-container > .paper-input-label, tp-yt-paper-input-container[dir=\"rtl\"] #labelAndInputContainer#labelAndInputContainer.label-is-floating.tp-yt-paper-input-container > .paper-input-label {\n  right: 0;\n  left: auto;\n  -webkit-transform-origin: right top;\n  transform-origin: right top;\n}\n\n#labelAndInputContainer#labelAndInputContainer.label-is-highlighted.tp-yt-paper-input-container > label,#labelAndInputContainer#labelAndInputContainer.label-is-highlighted.tp-yt-paper-input-container > .paper-input-label {\n  color: var(--paper-input-container-label-focus-color, var(--paper-input-container-focus-color, var(--primary-color)));\n}\n\n#labelAndInputContainer#labelAndInputContainer.is-invalid.tp-yt-paper-input-container > label,#labelAndInputContainer#labelAndInputContainer.is-invalid.tp-yt-paper-input-container > .paper-input-label {\n  color: var(--paper-input-container-invalid-color, var(--error-color));\n}\n\n#labelAndInputContainer#labelAndInputContainer.label-is-hidden.tp-yt-paper-input-container > label,#labelAndInputContainer#labelAndInputContainer.label-is-hidden.tp-yt-paper-input-container > .paper-input-label {\n  visibility: hidden;\n}\n\n.input-content.tp-yt-paper-input-container > input,.input-content.tp-yt-paper-input-container > iron-input,.input-content.tp-yt-paper-input-container > textarea,.input-content.tp-yt-paper-input-container > iron-autogrow-textarea,.input-content.tp-yt-paper-input-container > .paper-input-input {\n  position: relative;\n  outline: none;\n  box-shadow: none;\n  padding: var(--paper-input-container-shared-input-style-padding, 0);\n  margin: 0;\n  width: var(--paper-input-container-shared-input-style-width, 100%);\n  max-width: 100%;\n  background: transparent;\n  border: none;\n  color: var(--paper-input-container-input-color, var(--primary-text-color));\n  -webkit-appearance: none;\n  text-align: inherit;\n  vertical-align: var(--paper-input-container-input-align, bottom);\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  color: var(--paper-input-container-input-color, var(--primary-text-color));\n}\n\n.input-content.tp-yt-paper-input-container > input::-webkit-outer-spin-button,.input-content.tp-yt-paper-input-container > input::-webkit-inner-spin-button {\n  -webkit-appearance: var(--paper-input-container-input-webkit-spinner--webkit-appearance);\n  display: var(--paper-input-container-input-webkit-spinner-display);\n}\n\n.prefix.tp-yt-paper-input-container > * {\n  display: inline-block;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  -ms-flex: none;\n  -webkit-flex: none;\n  flex: none;\n  color: var(--paper-input-prefix-color);\n}\n\n.suffix.tp-yt-paper-input-container > * {\n  display: inline-block;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  -ms-flex: none;\n  -webkit-flex: none;\n  flex: none;\n  top: var(--paper-input-suffix-top);\n}\n\n.input-content.tp-yt-paper-input-container > input {\n  min-width: 0;\n}\n\n.input-content.tp-yt-paper-input-container > textarea {\n  resize: none;\n}\n\n.add-on-content.tp-yt-paper-input-container {\n  position: relative;\n}\n\n.add-on-content.is-invalid.tp-yt-paper-input-container > * {\n  color: var(--paper-input-container-invalid-color, var(--error-color));\n}\n\n.add-on-content.is-highlighted.tp-yt-paper-input-container > * {\n  color: var(--paper-input-container-focus-color, var(--primary-color));\n}\n\ntp-yt-paper-input-error {\n  display: inline-block;\n  visibility: hidden;\n  color: var(--paper-input-container-invalid-color, var(--error-color));\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  white-space: nowrap;\n  overflow: hidden;\n  text-overflow: ellipsis;\n  font-size: 12px;\n  font-weight: 400;\n  letter-spacing: 0.011em;\n  line-height: 20px;\n  position: absolute;\n  left: 0;\n  right: 0;\n}\n\ntp-yt-paper-input-error[invalid] {\n  visibility: visible;\n}\n\n#a11yWrapper.tp-yt-paper-input-error {\n  visibility: hidden;\n}\n\ntp-yt-paper-input-error[invalid] #a11yWrapper.tp-yt-paper-input-error {\n  visibility: visible;\n}\n\ntp-yt-paper-input {\n  display: block;\n}\n\ntp-yt-paper-input[focused] {\n  outline: none;\n}\n\ntp-yt-paper-input[hidden] {\n  display: none !important;\n}\n\ninput.tp-yt-paper-input {\n  min-width: 0;\n  -moz-appearance: var(--paper-input-input-moz-appearance) !important;\n}\n\niron-input.tp-yt-paper-input > input.tp-yt-paper-input {\n  position: relative;\n  outline: none;\n  box-shadow: none;\n  padding: var(--paper-input-container-shared-input-style-padding, 0);\n  margin: 0;\n  width: var(--paper-input-container-shared-input-style-width, 100%);\n  max-width: 100%;\n  background: transparent;\n  border: none;\n  color: var(--paper-input-container-input-color, var(--primary-text-color));\n  -webkit-appearance: none;\n  text-align: inherit;\n  vertical-align: var(--paper-input-container-input-align, bottom);\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  font-family: inherit;\n  font-weight: inherit;\n  font-size: inherit;\n  letter-spacing: inherit;\n  word-spacing: inherit;\n  line-height: inherit;\n  text-shadow: inherit;\n  color: inherit;\n  cursor: inherit;\n}\n\ninput.tp-yt-paper-input::-webkit-outer-spin-button,input.tp-yt-paper-input::-webkit-inner-spin-button {\n  -webkit-appearance: var(--paper-input-container-input-webkit-spinner--webkit-appearance);\n  display: var(--paper-input-container-input-webkit-spinner-display);\n}\n\ninput.tp-yt-paper-input::-webkit-input-placeholder {\n  color: var(--paper-input-container-color, var(--secondary-text-color));\n}\n\ninput.tp-yt-paper-input:-moz-placeholder {\n  color: var(--paper-input-container-color, var(--secondary-text-color));\n}\n\ninput.tp-yt-paper-input::-moz-placeholder {\n  color: var(--paper-input-container-color, var(--secondary-text-color));\n}\n\ninput.tp-yt-paper-input::-ms-clear {\n  display: var(--paper-input-container-ms-clear-display);\n}\n\ninput.tp-yt-paper-input:-ms-input-placeholder {\n  color: var(--paper-input-container-color, var(--secondary-text-color));\n}\n\nlabel.tp-yt-paper-input {\n  pointer-events: none;\n}\n\ntp-yt-paper-dropdown-menu {\n  display: inline-block;\n  position: relative;\n  text-align: left;\n  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);\n  -webkit-tap-highlight-color: transparent;\n  --paper-input-container-input_-_overflow:  hidden; --paper-input-container-input_-_white-space:  nowrap; --paper-input-container-input_-_text-overflow:  ellipsis; --paper-input-container-input_-_max-width:  100%; --paper-input-container-input_-_box-sizing:  border-box; --paper-input-container-input_-_cursor:  pointer; --paper-input-container-input_-_text-align: initial;;\n}\n\ntp-yt-paper-dropdown-menu:focus {\n  outline: none;\n}\n\n[dir=\"rtl\"] tp-yt-paper-dropdown-menu, tp-yt-paper-dropdown-menu[dir=\"rtl\"] {\n  text-align: right;\n}\n\ntp-yt-paper-dropdown-menu[noink] paper-ripple.tp-yt-paper-dropdown-menu {\n  display: none;\n}\n\ntp-yt-paper-dropdown-menu[no-label-float] paper-ripple.tp-yt-paper-dropdown-menu {\n  top: 8px;\n}\n\npaper-ripple.tp-yt-paper-dropdown-menu {\n  top: 12px;\n  left: 0px;\n  bottom: 8px;\n  right: 0px;\n}\n\ntp-yt-paper-menu-button.tp-yt-paper-dropdown-menu {\n  display: block;\n  padding: 0;\n}\n\ntp-yt-iron-icon.tp-yt-paper-dropdown-menu {\n  color: var(--paper-dropdown-menu-icon-color, var(--disabled-text-color));\n}\n\ntp-yt-paper-icon-button {\n  display: inline-block;\n  position: relative;\n  padding: 8px;\n  outline: none;\n  -webkit-user-select: none;\n  -moz-user-select: none;\n  -ms-user-select: none;\n  user-select: none;\n  cursor: pointer;\n  z-index: 0;\n  line-height: 1;\n  width: 40px;\n  height: 40px;\n  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);\n  -webkit-tap-highlight-color: transparent;\n  box-sizing: border-box !important;\n}\n\ntp-yt-paper-icon-button #ink.tp-yt-paper-icon-button {\n  color: var(--paper-icon-button-ink-color, var(--primary-text-color));\n  opacity: 0.6;\n}\n\ntp-yt-paper-icon-button[disabled] {\n  color: var(--paper-icon-button-disabled-text, var(--disabled-text-color));\n  pointer-events: none;\n  cursor: auto;\n}\n\ntp-yt-paper-icon-button[hidden] {\n  display: none !important;\n}\n\ntp-yt-paper-icon-button:hover {\n  -moz-transform: var(--paper-icon-button-hover-transform);\n  -webkit-transform: var(--paper-icon-button-hover-transform);\n  transform: var(--paper-icon-button-hover-transform);\n  color: var(--paper-icon-button-hover-color);\n  opacity: var(--paper-icon-button-hover-opacity);\n}\n\ntp-yt-iron-icon.tp-yt-paper-icon-button {\n  --iron-icon-width: 100%;\n  --iron-icon-height: 100%;\n}\n\ntp-yt-paper-textarea {\n  display: block;\n}\n\ntp-yt-paper-textarea[hidden] {\n  display: none !important;\n}\n\nlabel.tp-yt-paper-textarea {\n  pointer-events: none;\n}\n\ntp-yt-paper-icon-item,.tp-yt-paper-item.tp-yt-paper-icon-item {\n  display: block;\n  position: relative;\n  min-height: var(--paper-item-min-height, 48px);\n  padding: 0px 16px;\n}\n\n.tp-yt-paper-item.tp-yt-paper-icon-item {\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  border: none;\n  outline: none;\n  background: white;\n  width: 100%;\n  text-align: left;\n}\n\ntp-yt-paper-icon-item[hidden],.tp-yt-paper-item.tp-yt-paper-icon-item[hidden] {\n  display: none !important;\n}\n\ntp-yt-paper-icon-item.iron-selected,.tp-yt-paper-item.iron-selected.tp-yt-paper-icon-item {\n  font-weight: var(--paper-item-selected-weight, bold);\n  background: var(--paper-item-selected-background);\n}\n\ntp-yt-paper-icon-item[disabled],.tp-yt-paper-item.tp-yt-paper-icon-item[disabled] {\n  color: var(--paper-item-disabled-color, var(--disabled-text-color));\n}\n\ntp-yt-paper-icon-item:focus,.tp-yt-paper-item.tp-yt-paper-icon-item:focus {\n  position: relative;\n  outline: 0;\n  background-color: var(--paper-item-focused-background-color);\n}\n\ntp-yt-paper-icon-item:focus:before,.tp-yt-paper-item.tp-yt-paper-icon-item:focus:before {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n  pointer-events: none;\n  background: var(--paper-item-focused-before-background, currentColor);\n  border-radius: var(--paper-item-focused-before-border-radius, 0);\n  content: var(--paper-item-focused-before-content, \"\");\n  opacity: var(--paper-item-focused-before-opacity, var(--dark-divider-opacity, 0.12));\n}\n\ntp-yt-paper-icon-item {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row;\n  -webkit-flex-direction: row;\n  flex-direction: row;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  min-height: var(--paper-item-min-height, 48px);\n}\n\n.content-icon.tp-yt-paper-icon-item {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row;\n  -webkit-flex-direction: row;\n  flex-direction: row;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  width: var(--paper-item-icon-width, 56px);\n  margin-left: var(--paper-item-icon-margin-left);\n  margin-right: var(--paper-item-icon-margin-right);\n}\n\ntp-yt-paper-item-body {\n  overflow: hidden;\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: column;\n  -webkit-flex-direction: column;\n  flex-direction: column;\n  -ms-flex-pack: center;\n  -webkit-justify-content: center;\n  justify-content: center;\n  -ms-flex: 1 1 0.000000001px;\n  -webkit-flex: 1;\n  flex: 1;\n  -webkit-flex-basis: 0.000000001px;\n  flex-basis: 0.000000001px;\n}\n\ntp-yt-paper-item-body[two-line] {\n  min-height: var(--paper-item-body-two-line-min-height, 72px);\n}\n\ntp-yt-paper-item-body[three-line] {\n  min-height: var(--paper-item-body-three-line-min-height, 88px);\n}\n\ntp-yt-paper-item-body > * {\n  overflow: hidden;\n  text-overflow: ellipsis;\n  white-space: nowrap;\n}\n\ntp-yt-paper-item-body > [secondary] {\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 14px;\n  font-weight: 400;\n  line-height: 20px;\n  color: var(--paper-item-body-secondary-color, var(--secondary-text-color));\n}\n\ntp-yt-paper-item,.tp-yt-paper-item.tp-yt-paper-item {\n  display: block;\n  position: relative;\n  min-height: var(--paper-item-min-height, 48px);\n  padding: 0px 16px;\n}\n\n.tp-yt-paper-item.tp-yt-paper-item {\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  border: none;\n  outline: none;\n  background: white;\n  width: 100%;\n  text-align: left;\n}\n\ntp-yt-paper-item[hidden],.tp-yt-paper-item.tp-yt-paper-item[hidden] {\n  display: none !important;\n}\n\ntp-yt-paper-item.iron-selected,.tp-yt-paper-item.iron-selected.tp-yt-paper-item {\n  font-weight: var(--paper-item-selected-weight, bold);\n  background: var(--paper-item-selected-background);\n}\n\ntp-yt-paper-item[disabled],.tp-yt-paper-item.tp-yt-paper-item[disabled] {\n  color: var(--paper-item-disabled-color, var(--disabled-text-color));\n}\n\ntp-yt-paper-item:focus,.tp-yt-paper-item.tp-yt-paper-item:focus {\n  position: relative;\n  outline: 0;\n  background-color: var(--paper-item-focused-background-color);\n}\n\ntp-yt-paper-item:focus:before,.tp-yt-paper-item.tp-yt-paper-item:focus:before {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n  pointer-events: none;\n  background: var(--paper-item-focused-before-background, currentColor);\n  border-radius: var(--paper-item-focused-before-border-radius, 0);\n  content: var(--paper-item-focused-before-content, \"\");\n  opacity: var(--paper-item-focused-before-opacity, var(--dark-divider-opacity, 0.12));\n}\n\ntp-yt-paper-item {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row;\n  -webkit-flex-direction: row;\n  flex-direction: row;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  font-size: 16px;\n  font-weight: 400;\n  line-height: 24px;\n  min-height: var(--paper-item-min-height, 48px);\n}\n\ntp-yt-paper-listbox {\n  display: block;\n  padding: 8px 0;\n  background: var(--paper-listbox-background-color, var(--primary-background-color));\n  color: var(--paper-listbox-color, var(--primary-text-color));\n  border: var(--paper-listbox-border);\n}\n\ntp-yt-paper-material[animated] {\n  transition: box-shadow 0.28s cubic-bezier(0.4, 0, 0.2, 1);\n}\n\ntp-yt-paper-material {\n  display: block;\n  position: relative;\n}\n\ntp-yt-paper-material[elevation=\"1\"] {\n  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);\n}\n\ntp-yt-paper-material[elevation=\"2\"] {\n  box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-material[elevation=\"3\"] {\n  box-shadow: 0 6px 10px 0 rgba(0, 0, 0, 0.14), 0 1px 18px 0 rgba(0, 0, 0, 0.12), 0 3px 5px -1px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-material[elevation=\"4\"] {\n  box-shadow: 0 8px 10px 1px rgba(0, 0, 0, 0.14), 0 3px 14px 2px rgba(0, 0, 0, 0.12), 0 5px 5px -3px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-material[elevation=\"5\"] {\n  box-shadow: 0 16px 24px 2px rgba(0, 0, 0, 0.14), 0 6px 30px 5px rgba(0, 0, 0, 0.12), 0 8px 10px -5px rgba(0, 0, 0, 0.4);\n}\n\ntp-yt-paper-radio-button {\n  display: inline-block;\n  line-height: 0;\n  white-space: nowrap;\n  cursor: pointer;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  --calculated-paper-radio-button-size: var(--paper-radio-button-size, 16px);\n  --calculated-paper-radio-button-ink-size: var(\n    --paper-radio-button-ink-size,\n    -1px\n  );\n}\n\ntp-yt-paper-radio-button:focus {\n  outline: none;\n}\n\ntp-yt-paper-radio-button tp-yt-paper-radio-button .tp-yt-paper-radio-button[style-target=container],.tp-yt-paper-radio-button[style-target=container] {\n  display: -ms-inline-flexbox;\n  display: -webkit-inline-flex;\n  display: inline-flex;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  -ms-flex-pack: center;\n  -webkit-justify-content: center;\n  justify-content: center;\n  position: relative;\n  min-width: var(--calculated-paper-radio-button-size);\n  width: var(--calculated-paper-radio-button-size);\n  height: var(--calculated-paper-radio-button-size);\n  vertical-align: middle;\n}\n\n#ink.tp-yt-paper-radio-button {\n  position: absolute;\n  top: 50%;\n  left: 50%;\n  right: auto;\n  width: var(--calculated-paper-radio-button-ink-size);\n  height: var(--calculated-paper-radio-button-ink-size);\n  color: var(--paper-radio-button-unchecked-ink-color, var(--primary-text-color));\n  opacity: 0.6;\n  pointer-events: none;\n  -webkit-transform: translate(-50%, -50%);\n  transform: translate(-50%, -50%);\n}\n\n#ink.tp-yt-paper-radio-button[checked] {\n  color: var(--paper-radio-button-checked-ink-color, var(--primary-color));\n}\n\n#offRadio.tp-yt-paper-radio-button,#onRadio.tp-yt-paper-radio-button {\n  position: absolute;\n  box-sizing: border-box;\n  top: 0;\n  left: 0;\n  width: 100%;\n  height: 100%;\n  border-radius: 50%;\n}\n\n#offRadio.tp-yt-paper-radio-button {\n  border: 2px solid var(--paper-radio-button-unchecked-color, var(--primary-text-color));\n  background-color: var(--paper-radio-button-unchecked-background-color, transparent);\n  transition: border-color 0.28s;\n}\n\n#onRadio.tp-yt-paper-radio-button {\n  background-color: var(--paper-radio-button-checked-color, var(--primary-color));\n  -webkit-transform: scale(0);\n  transform: scale(0);\n  transition: -webkit-transform ease 0.28s;\n  transition: transform ease 0.28s;\n  will-change: transform;\n}\n\ntp-yt-paper-radio-button[checked] #offRadio.tp-yt-paper-radio-button {\n  border-color: var(--paper-radio-button-checked-color, var(--primary-color));\n}\n\ntp-yt-paper-radio-button[checked] #onRadio.tp-yt-paper-radio-button {\n  -webkit-transform: scale(0.5);\n  transform: scale(0.5);\n}\n\ntp-yt-paper-radio-button tp-yt-paper-radio-button .tp-yt-paper-radio-button[style-target=label],.tp-yt-paper-radio-button[style-target=label] {\n  line-height: normal;\n  position: relative;\n  display: inline-block;\n  vertical-align: middle;\n  margin-inline-start: var(--paper-radio-button-label-spacing, 10px);\n  white-space: normal;\n  color: var(--paper-radio-button-label-color, var(--primary-text-color));\n}\n\ntp-yt-paper-radio-button tp-yt-paper-radio-button[hidden] .tp-yt-paper-radio-button[style-target=label],.tp-yt-paper-radio-button[style-target=label].tp-yt-paper-radio-button[hidden] {\n  display: none;\n}\n\ntp-yt-paper-radio-button tp-yt-paper-radio-button[hidden] .tp-yt-paper-radio-button[style-target=label] {\n  display: none;\n}\n\ntp-yt-paper-radio-button[disabled] #offRadio.tp-yt-paper-radio-button {\n  border-color: var(--paper-radio-button-unchecked-color, var(--primary-text-color));\n  opacity: 0.5;\n}\n\ntp-yt-paper-radio-button[disabled][checked] #onRadio.tp-yt-paper-radio-button {\n  background-color: var(--paper-radio-button-unchecked-color, var(--primary-text-color));\n  opacity: 0.5;\n}\n\ntp-yt-paper-radio-button tp-yt-paper-radio-button[disabled] .tp-yt-paper-radio-button[style-target=label],tp-yt-paper-radio-button[disabled] .tp-yt-paper-radio-button[style-target=label] {\n  opacity: 0.65;\n}\n\n@media (forced-colors: active) {\n#onRadio.tp-yt-paper-radio-button,tp-yt-paper-radio-button[disabled][checked] #onRadio.tp-yt-paper-radio-button {\n  background-color: ButtonText;\n    color-scheme: only dark;\n}\n\n}\n\ntp-yt-paper-radio-group {\n  display: inline-block;\n}\n\ntp-yt-paper-radio-group > * {\n  padding: var(--paper-radio-group-item-padding, 12px);\n}\n\ntp-yt-paper-spinner {\n  display: inline-block;\n  position: relative;\n  width: 28px;\n  height: 28px;\n  --paper-spinner-container-rotation-duration: 1568ms;\n  --paper-spinner-expand-contract-duration: 1333ms;\n  --paper-spinner-full-cycle-duration: 5332ms;\n  --paper-spinner-cooldown-duration: 400ms;\n}\n\n#spinnerContainer.tp-yt-paper-spinner {\n  width: 100%;\n  height: 100%;\n  direction: ltr;\n}\n\n#spinnerContainer.active.tp-yt-paper-spinner {\n  -webkit-animation: container-rotate var(--paper-spinner-container-rotation-duration) linear infinite;\n  animation: container-rotate var(--paper-spinner-container-rotation-duration) linear infinite;\n}\n\n@-webkit-keyframes container-rotate {\nto {\n  -webkit-transform: rotate(360deg);\n}\n\n}\n\n@keyframes container-rotate {\nto {\n  transform: rotate(360deg);\n}\n\n}\n\n.spinner-layer.tp-yt-paper-spinner {\n  position: absolute;\n  width: 100%;\n  height: 100%;\n  opacity: 0;\n  white-space: nowrap;\n  color: var(--paper-spinner-color, #4285f4);\n}\n\n.layer-1.tp-yt-paper-spinner {\n  color: var(--paper-spinner-layer-1-color, #4285f4);\n}\n\n.layer-2.tp-yt-paper-spinner {\n  color: var(--paper-spinner-layer-2-color, #db4437);\n}\n\n.layer-3.tp-yt-paper-spinner {\n  color: var(--paper-spinner-layer-3-color, #f4b400);\n}\n\n.layer-4.tp-yt-paper-spinner {\n  color: var(--paper-spinner-layer-4-color, #0f9d58);\n}\n\n.active.tp-yt-paper-spinner .spinner-layer.tp-yt-paper-spinner {\n  -webkit-animation-name: fill-unfill-rotate;\n  -webkit-animation-duration: var(--paper-spinner-full-cycle-duration);\n  -webkit-animation-timing-function: cubic-bezier(0.4, 0, 0.2, 1);\n  -webkit-animation-iteration-count: infinite;\n  animation-name: fill-unfill-rotate;\n  animation-duration: var(--paper-spinner-full-cycle-duration);\n  animation-timing-function: cubic-bezier(0.4, 0, 0.2, 1);\n  animation-iteration-count: infinite;\n  opacity: 1;\n}\n\n.active.tp-yt-paper-spinner .spinner-layer.layer-1.tp-yt-paper-spinner {\n  -webkit-animation-name: fill-unfill-rotate, layer-1-fade-in-out;\n  animation-name: fill-unfill-rotate, layer-1-fade-in-out;\n}\n\n.active.tp-yt-paper-spinner .spinner-layer.layer-2.tp-yt-paper-spinner {\n  -webkit-animation-name: fill-unfill-rotate, layer-2-fade-in-out;\n  animation-name: fill-unfill-rotate, layer-2-fade-in-out;\n}\n\n.active.tp-yt-paper-spinner .spinner-layer.layer-3.tp-yt-paper-spinner {\n  -webkit-animation-name: fill-unfill-rotate, layer-3-fade-in-out;\n  animation-name: fill-unfill-rotate, layer-3-fade-in-out;\n}\n\n.active.tp-yt-paper-spinner .spinner-layer.layer-4.tp-yt-paper-spinner {\n  -webkit-animation-name: fill-unfill-rotate, layer-4-fade-in-out;\n  animation-name: fill-unfill-rotate, layer-4-fade-in-out;\n}\n\n@-webkit-keyframes fill-unfill-rotate {\n12.5% {\n  -webkit-transform: rotate(135deg);\n}\n\n25% {\n  -webkit-transform: rotate(270deg);\n}\n\n37.5% {\n  -webkit-transform: rotate(405deg);\n}\n\n50% {\n  -webkit-transform: rotate(540deg);\n}\n\n62.5% {\n  -webkit-transform: rotate(675deg);\n}\n\n75% {\n  -webkit-transform: rotate(810deg);\n}\n\n87.5% {\n  -webkit-transform: rotate(945deg);\n}\n\nto {\n  -webkit-transform: rotate(1080deg);\n}\n\n}\n\n@keyframes fill-unfill-rotate {\n12.5% {\n  transform: rotate(135deg);\n}\n\n25% {\n  transform: rotate(270deg);\n}\n\n37.5% {\n  transform: rotate(405deg);\n}\n\n50% {\n  transform: rotate(540deg);\n}\n\n62.5% {\n  transform: rotate(675deg);\n}\n\n75% {\n  transform: rotate(810deg);\n}\n\n87.5% {\n  transform: rotate(945deg);\n}\n\nto {\n  transform: rotate(1080deg);\n}\n\n}\n\n@-webkit-keyframes layer-1-fade-in-out {\n0% {\n  opacity: 1;\n}\n\n25% {\n  opacity: 1;\n}\n\n26% {\n  opacity: 0;\n}\n\n89% {\n  opacity: 0;\n}\n\n90% {\n  opacity: 1;\n}\n\nto {\n  opacity: 1;\n}\n\n}\n\n@keyframes layer-1-fade-in-out {\n0% {\n  opacity: 1;\n}\n\n25% {\n  opacity: 1;\n}\n\n26% {\n  opacity: 0;\n}\n\n89% {\n  opacity: 0;\n}\n\n90% {\n  opacity: 1;\n}\n\nto {\n  opacity: 1;\n}\n\n}\n\n@-webkit-keyframes layer-2-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n15% {\n  opacity: 0;\n}\n\n25% {\n  opacity: 1;\n}\n\n50% {\n  opacity: 1;\n}\n\n51% {\n  opacity: 0;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@keyframes layer-2-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n15% {\n  opacity: 0;\n}\n\n25% {\n  opacity: 1;\n}\n\n50% {\n  opacity: 1;\n}\n\n51% {\n  opacity: 0;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@-webkit-keyframes layer-3-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n40% {\n  opacity: 0;\n}\n\n50% {\n  opacity: 1;\n}\n\n75% {\n  opacity: 1;\n}\n\n76% {\n  opacity: 0;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@keyframes layer-3-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n40% {\n  opacity: 0;\n}\n\n50% {\n  opacity: 1;\n}\n\n75% {\n  opacity: 1;\n}\n\n76% {\n  opacity: 0;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@-webkit-keyframes layer-4-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n65% {\n  opacity: 0;\n}\n\n75% {\n  opacity: 1;\n}\n\n90% {\n  opacity: 1;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@keyframes layer-4-fade-in-out {\n0% {\n  opacity: 0;\n}\n\n65% {\n  opacity: 0;\n}\n\n75% {\n  opacity: 1;\n}\n\n90% {\n  opacity: 1;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n.circle-clipper.tp-yt-paper-spinner {\n  display: inline-block;\n  position: relative;\n  width: 50%;\n  height: 100%;\n  overflow: hidden;\n}\n\n.spinner-layer.tp-yt-paper-spinner::after {\n  content: \"\";\n  left: 45%;\n  width: 10%;\n  border-top-style: solid;\n}\n\n.spinner-layer.tp-yt-paper-spinner::after,.circle-clipper.tp-yt-paper-spinner .circle.tp-yt-paper-spinner {\n  box-sizing: border-box;\n  position: absolute;\n  top: 0;\n  border-width: var(--paper-spinner-stroke-width, 3px);\n  border-radius: 50%;\n}\n\n.circle-clipper.tp-yt-paper-spinner .circle.tp-yt-paper-spinner {\n  bottom: 0;\n  width: 200%;\n  border-style: solid;\n  border-bottom-color: transparent !important;\n}\n\n.circle-clipper.left.tp-yt-paper-spinner .circle.tp-yt-paper-spinner {\n  left: 0;\n  border-right-color: transparent !important;\n  -webkit-transform: rotate(129deg);\n  transform: rotate(129deg);\n}\n\n.circle-clipper.right.tp-yt-paper-spinner .circle.tp-yt-paper-spinner {\n  left: -100%;\n  border-left-color: transparent !important;\n  -webkit-transform: rotate(-129deg);\n  transform: rotate(-129deg);\n}\n\n.active.tp-yt-paper-spinner .gap-patch.tp-yt-paper-spinner::after,.active.tp-yt-paper-spinner .circle-clipper.tp-yt-paper-spinner .circle.tp-yt-paper-spinner {\n  -webkit-animation-duration: var(--paper-spinner-expand-contract-duration);\n  -webkit-animation-timing-function: cubic-bezier(0.4, 0, 0.2, 1);\n  -webkit-animation-iteration-count: infinite;\n  animation-duration: var(--paper-spinner-expand-contract-duration);\n  animation-timing-function: cubic-bezier(0.4, 0, 0.2, 1);\n  animation-iteration-count: infinite;\n}\n\n.active.tp-yt-paper-spinner .circle-clipper.left.tp-yt-paper-spinner .circle.tp-yt-paper-spinner {\n  -webkit-animation-name: left-spin;\n  animation-name: left-spin;\n}\n\n.active.tp-yt-paper-spinner .circle-clipper.right.tp-yt-paper-spinner .circle.tp-yt-paper-spinner {\n  -webkit-animation-name: right-spin;\n  animation-name: right-spin;\n}\n\n@-webkit-keyframes left-spin {\n0% {\n  -webkit-transform: rotate(130deg);\n}\n\n50% {\n  -webkit-transform: rotate(-5deg);\n}\n\nto {\n  -webkit-transform: rotate(130deg);\n}\n\n}\n\n@keyframes left-spin {\n0% {\n  transform: rotate(130deg);\n}\n\n50% {\n  transform: rotate(-5deg);\n}\n\nto {\n  transform: rotate(130deg);\n}\n\n}\n\n@-webkit-keyframes right-spin {\n0% {\n  -webkit-transform: rotate(-130deg);\n}\n\n50% {\n  -webkit-transform: rotate(5deg);\n}\n\nto {\n  -webkit-transform: rotate(-130deg);\n}\n\n}\n\n@keyframes right-spin {\n0% {\n  transform: rotate(-130deg);\n}\n\n50% {\n  transform: rotate(5deg);\n}\n\nto {\n  transform: rotate(-130deg);\n}\n\n}\n\n#spinnerContainer.cooldown.tp-yt-paper-spinner {\n  -webkit-animation: container-rotate var(--paper-spinner-container-rotation-duration) linear infinite, fade-out var(--paper-spinner-cooldown-duration) cubic-bezier(0.4, 0, 0.2, 1);\n  animation: container-rotate var(--paper-spinner-container-rotation-duration) linear infinite, fade-out var(--paper-spinner-cooldown-duration) cubic-bezier(0.4, 0, 0.2, 1);\n}\n\n@-webkit-keyframes fade-out {\n0% {\n  opacity: 1;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\n@keyframes fade-out {\n0% {\n  opacity: 1;\n}\n\nto {\n  opacity: 0;\n}\n\n}\n\ntp-yt-paper-tab {\n  display: -ms-inline-flexbox;\n  display: -webkit-inline-flex;\n  display: inline-flex;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  -ms-flex-pack: center;\n  -webkit-justify-content: center;\n  justify-content: center;\n  -ms-flex: 1 1 auto;\n  -webkit-flex: 1 1 auto;\n  flex: 1 1 auto;\n  position: relative;\n  padding: 0 12px;\n  overflow: hidden;\n  cursor: pointer;\n  vertical-align: middle;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n}\n\ntp-yt-paper-tab:focus {\n  outline: none;\n}\n\ntp-yt-paper-tab[link] {\n  padding: 0;\n}\n\ntp-yt-paper-tab tp-yt-paper-tab .tp-yt-paper-tab[style-target=tab-content],.tp-yt-paper-tab[style-target=tab-content] {\n  height: 100%;\n  transform: translateZ(0);\n  -webkit-transform: translateZ(0);\n  transition: opacity 0.1s cubic-bezier(0.4, 0, 1, 1);\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row;\n  -webkit-flex-direction: row;\n  flex-direction: row;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  -ms-flex-pack: center;\n  -webkit-justify-content: center;\n  justify-content: center;\n  -ms-flex: 1 1 auto;\n  -webkit-flex: 1 1 auto;\n  flex: 1 1 auto;\n}\n\ntp-yt-paper-tab:not(.iron-selected) .tp-yt-paper-tab[style-target=tab-content] {\n  opacity: 0.8;\n}\n\ntp-yt-paper-tab:focus .tp-yt-paper-tab[style-target=tab-content] {\n  opacity: 1;\n}\n\ntp-yt-paper-tab:focus:not([noBoldOnFocus]) .tp-yt-paper-tab[style-target=tab-content] {\n  font-weight: var(--paper-tab-content-focused-font-weight, 700);\n}\n\npaper-ripple.tp-yt-paper-tab {\n  color: var(--paper-tab-ink, #ffff8d);\n}\n\n.tab-content.tp-yt-paper-tab > a {\n  -ms-flex: 1 1 auto;\n  -webkit-flex: 1 1 auto;\n  flex: 1 1 auto;\n  height: 100%;\n}\n\ntp-yt-paper-tabs {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  height: 48px;\n  font-size: 14px;\n  font-weight: 500;\n  overflow: hidden;\n  -moz-user-select: none;\n  -ms-user-select: none;\n  -webkit-user-select: none;\n  user-select: none;\n  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);\n  -webkit-tap-highlight-color: transparent;\n}\n\n[dir=\"rtl\"] tp-yt-paper-tabs, tp-yt-paper-tabs[dir=\"rtl\"] {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row-reverse;\n  -webkit-flex-direction: row-reverse;\n  flex-direction: row-reverse;\n}\n\n#tabsContainer.tp-yt-paper-tabs {\n  position: relative;\n  height: 100%;\n  white-space: nowrap;\n  overflow: hidden;\n  -ms-flex: 1 1 auto;\n  -webkit-flex: 1 1 auto;\n  flex: 1 1 auto;\n}\n\n.tabs-content.tp-yt-paper-tabs {\n  height: 100%;\n  -moz-flex-basis: auto;\n  -ms-flex-basis: auto;\n  flex-basis: auto;\n}\n\n.tabs-content.scrollable.tp-yt-paper-tabs {\n  position: absolute;\n  white-space: nowrap;\n}\n\n.tabs-content.tp-yt-paper-tabs:not(.scrollable),.tabs-content.scrollable.fit-container.tp-yt-paper-tabs {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row;\n  -webkit-flex-direction: row;\n  flex-direction: row;\n}\n\n.tabs-content.scrollable.fit-container.tp-yt-paper-tabs {\n  min-width: 100%;\n}\n\n#tabsContent.scrollable.fit-container.tp-yt-paper-tabs > * {\n  -ms-flex: 1 0 auto;\n  -webkit-flex: 1 0 auto;\n  flex: 1 0 auto;\n}\n\n.hidden.tp-yt-paper-tabs {\n  display: none;\n}\n\n.not-visible.tp-yt-paper-tabs {\n  opacity: 0;\n  cursor: default;\n}\n\ntp-yt-paper-icon-button.tp-yt-paper-tabs {\n  width: 48px;\n  height: 48px;\n  padding: 12px;\n  margin: 0 4px;\n}\n\n.selection-bar.tp-yt-paper-tabs {\n  position: absolute;\n  height: 0;\n  bottom: 0;\n  left: 0;\n  right: 0;\n  border-bottom: 2px solid var(--paper-tabs-selection-bar-color, #ffff8d);\n  -webkit-transform: scale(0);\n  transform: scale(0);\n  -webkit-transform-origin: left center;\n  transform-origin: left center;\n  transition: -webkit-transform;\n  transition: transform;\n}\n\n.selection-bar.align-bottom.tp-yt-paper-tabs {\n  top: 0;\n  bottom: auto;\n}\n\n.selection-bar.expand.tp-yt-paper-tabs {\n  transition-duration: 0.15s;\n  transition-timing-function: cubic-bezier(0.4, 0, 1, 1);\n}\n\n.selection-bar.contract.tp-yt-paper-tabs {\n  transition-duration: 0.18s;\n  transition-timing-function: cubic-bezier(0, 0, 0.2, 1);\n}\n\n#tabsContent.tp-yt-paper-tabs > :not(#selectionBar) {\n  height: 100%;\n}\n\ntp-yt-paper-toast {\n  display: block;\n  position: fixed;\n  background-color: var(--paper-toast-background-color, #323232);\n  color: var(--paper-toast-color, #f1f1f1);\n  min-height: 48px;\n  min-width: 288px;\n  padding: 16px 24px;\n  box-sizing: border-box;\n  box-shadow: 0 2px 5px 0 rgba(0, 0, 0, 0.26);\n  border-radius: 2px;\n  margin: 12px;\n  font-size: 14px;\n  cursor: default;\n  -webkit-transition: -webkit-transform 0.3s, opacity 0.3s;\n  transition: transform 0.3s, opacity 0.3s;\n  opacity: 0;\n  -webkit-transform: translateY(100px);\n  transform: translateY(100px);\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n}\n\ntp-yt-paper-toast.capsule {\n  border-radius: 24px;\n}\n\ntp-yt-paper-toast.fit-bottom {\n  width: 100%;\n  min-width: 0;\n  border-radius: 0;\n  margin: 0;\n}\n\ntp-yt-paper-toast.paper-toast-open {\n  opacity: 1;\n  -webkit-transform: translateY(0px);\n  transform: translateY(0px);\n}\n\ntp-yt-paper-toggle-button {\n  display: inline-block;\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row;\n  -webkit-flex-direction: row;\n  flex-direction: row;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  font-family: \"Roboto\", \"Noto\", sans-serif;\n  -webkit-font-smoothing: antialiased;\n  --transition-duration: var(--paper-toggle-button-transition-duration, 0.08s);\n}\n\ntp-yt-paper-toggle-button[disabled] {\n  pointer-events: none;\n}\n\ntp-yt-paper-toggle-button:focus {\n  outline: none;\n}\n\n.toggle-bar.tp-yt-paper-toggle-button {\n  position: absolute;\n  height: 100%;\n  width: 100%;\n  border-radius: 8px;\n  pointer-events: none;\n  transition: background-color linear var(--transition-duration);\n  background-color: var(--paper-toggle-button-unchecked-bar-color, #000);\n  opacity: var(--paper-toggle-button-unchecked-bar-opacity, 0.4);\n}\n\n.toggle-button.tp-yt-paper-toggle-button {\n  position: absolute;\n  top: -3px;\n  left: 0;\n  right: auto;\n  height: 20px;\n  width: 20px;\n  border-radius: 50%;\n  box-shadow: var(--paper-toggle-button-box-shadow, 0 1px 5px 0 rgba(0, 0, 0, 0.6));\n  transition: -webkit-transform linear var(--transition-duration), background-color linear var(--transition-duration);\n  transition: transform linear var(--transition-duration), background-color linear var(--transition-duration);\n  will-change: transform;\n  background-color: var(--paper-toggle-button-unchecked-button-color, #fafafa);\n}\n\n[dir=\"rtl\"] tp-yt-paper-toggle-button .toggle-button.tp-yt-paper-toggle-button, tp-yt-paper-toggle-button[dir=\"rtl\"] .toggle-button.tp-yt-paper-toggle-button,tp-yt-paper-toggle-button[dir=rtl] .toggle-button.tp-yt-paper-toggle-button {\n  right: 0;\n  left: auto;\n}\n\n.toggle-button.dragging.tp-yt-paper-toggle-button {\n  -webkit-transition: none;\n  transition: none;\n}\n\ntp-yt-paper-toggle-button[checked]:not([disabled]) .toggle-bar.tp-yt-paper-toggle-button {\n  background-color: var(--paper-toggle-button-checked-bar-color, var(--primary-color));\n  opacity: var(--paper-toggle-button-checked-bar-opacity, 0.5);\n}\n\ntp-yt-paper-toggle-button[disabled] .toggle-bar.tp-yt-paper-toggle-button {\n  background-color: var(--paper-toggle-button-disabled-bar-color, #000);\n  opacity: 0.12;\n}\n\ntp-yt-paper-toggle-button[checked] .toggle-button.tp-yt-paper-toggle-button {\n  -webkit-transform: translate(16px, 0);\n  transform: translate(16px, 0);\n}\n\n[dir=\"rtl\"] tp-yt-paper-toggle-button[checked] .toggle-button.tp-yt-paper-toggle-button, tp-yt-paper-toggle-button[checked][dir=\"rtl\"] .toggle-button.tp-yt-paper-toggle-button,tp-yt-paper-toggle-button[dir=rtl][checked] .toggle-button.tp-yt-paper-toggle-button {\n  -webkit-transform: translate(-16px, 0);\n  transform: translate(-16px, 0);\n}\n\ntp-yt-paper-toggle-button[dir=rtl] {\n  -webkit-transform: unset;\n  transform: unset;\n}\n\ntp-yt-paper-toggle-button[checked]:not([disabled]) .toggle-button.tp-yt-paper-toggle-button {\n  background-color: var(--paper-toggle-button-checked-button-color, var(--primary-color));\n}\n\ntp-yt-paper-toggle-button[disabled] .toggle-button.tp-yt-paper-toggle-button {\n  background-color: var(--paper-toggle-button-disabled-button-color, #bdbdbd);\n  opacity: 1;\n}\n\n.toggle-ink.tp-yt-paper-toggle-button {\n  position: absolute;\n  top: -14px;\n  left: -14px;\n  right: auto;\n  bottom: auto;\n  width: 48px;\n  height: 48px;\n  opacity: 0.5;\n  pointer-events: none;\n}\n\n.toggle-container.tp-yt-paper-toggle-button {\n  display: inline-block;\n  position: relative;\n  width: 36px;\n  height: 14px;\n  margin: 4px 1px;\n}\n\n.toggle-label.tp-yt-paper-toggle-button {\n  position: relative;\n  display: inline-block;\n  vertical-align: middle;\n  padding-left: var(--paper-toggle-button-label-spacing, 8px);\n  pointer-events: none;\n}\n\ntp-yt-paper-toggle-button[invalid] .toggle-bar.tp-yt-paper-toggle-button {\n  background-color: var(--paper-toggle-button-invalid-bar-color, var(--error-color));\n}\n\ntp-yt-paper-toggle-button[invalid] .toggle-button.tp-yt-paper-toggle-button {\n  background-color: var(--paper-toggle-button-invalid-button-color, var(--error-color));\n}\n\ntp-yt-app-drawer {\n  position: fixed;\n  z-index: 1;\n  top: -120px;\n  right: 0;\n  bottom: -120px;\n  left: 0;\n  visibility: hidden;\n  transition-property: visibility;\n}\n\ntp-yt-app-drawer[opened] {\n  visibility: visible;\n}\n\ntp-yt-app-drawer[persistent] {\n  width: var(--app-drawer-width, 256px);\n}\n\ntp-yt-app-drawer[persistent][position=left] {\n  right: auto;\n}\n\ntp-yt-app-drawer[persistent][position=right] {\n  left: auto;\n}\n\n#contentContainer.tp-yt-app-drawer {\n  position: absolute;\n  top: 0;\n  bottom: 0;\n  left: 0;\n  width: var(--app-drawer-width, 256px);\n  padding: var(--app-drawer-content-padding, 120px 0);\n  transition-property: -webkit-transform;\n  transition-property: transform;\n  -webkit-transform: translate3d(-100%, 0, 0);\n  transform: translate3d(-100%, 0, 0);\n  background-color: #fff;\n  background-color: var(--app-drawer-content-container-background-color);\n}\n\n#contentContainer.tp-yt-app-drawer[persistent] {\n  width: 100%;\n}\n\n#contentContainer.tp-yt-app-drawer[position=right] {\n  right: 0;\n  left: auto;\n  -webkit-transform: translate3d(100%, 0, 0);\n  transform: translate3d(100%, 0, 0);\n}\n\n#contentContainer.tp-yt-app-drawer[swipe-open].tp-yt-app-drawer::after {\n  position: fixed;\n  top: 0;\n  bottom: 0;\n  left: 100%;\n  visibility: visible;\n  width: 20px;\n  content: \"\";\n}\n\n#contentContainer.tp-yt-app-drawer[swipe-open].tp-yt-app-drawer[position=right].tp-yt-app-drawer::after {\n  right: 100%;\n  left: auto;\n}\n\n#contentContainer.tp-yt-app-drawer[opened] {\n  -webkit-transform: translate3d(0, 0, 0);\n  transform: translate3d(0, 0, 0);\n}\n\n#scrim.tp-yt-app-drawer {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n  transition-property: opacity;\n  -webkit-transform: translateZ(0);\n  transform: translateZ(0);\n  opacity: 0;\n  background: var(--app-drawer-scrim-background, rgba(0, 0, 0, 0.5));\n}\n\n#scrim.visible.tp-yt-app-drawer {\n  opacity: 1;\n}\n\ntp-yt-app-drawer[no-transition] #contentContainer.tp-yt-app-drawer {\n  transition-property: none;\n}\n\ntp-yt-paper-progress {\n  display: block;\n  width: 200px;\n  position: relative;\n  overflow: hidden;\n}\n\n[dir=\"rtl\"] tp-yt-paper-progress[mirror-in-rtl], tp-yt-paper-progress[mirror-in-rtl][dir=\"rtl\"] {\n  transform: scaleX(-1);\n}\n\ntp-yt-paper-progress[hidden],.tp-yt-paper-progress[hidden] {\n  display: none !important;\n}\n\n#progressContainer.tp-yt-paper-progress {\n  position: relative;\n}\n\n#progressContainer.tp-yt-paper-progress,.indeterminate.tp-yt-paper-progress::after {\n  height: var(--paper-progress-height, 4px);\n  border-radius: var(--paper-progress-container-border-radius, 0px);\n  overflow: var(--paper-progress-container-overflow, visible);\n  transform: var(--paper-progress-container-transform, none);\n}\n\n#primaryProgress.tp-yt-paper-progress,#secondaryProgress.tp-yt-paper-progress,.indeterminate.tp-yt-paper-progress::after {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n}\n\n#progressContainer.tp-yt-paper-progress,.indeterminate.tp-yt-paper-progress::after {\n  background: var(--paper-progress-container-color, #e0e0e0);\n}\n\ntp-yt-paper-progress.transiting #primaryProgress.tp-yt-paper-progress,tp-yt-paper-progress.transiting #secondaryProgress.tp-yt-paper-progress {\n  -webkit-transition-property: -webkit-transform;\n  transition-property: transform;\n  -webkit-transition-duration: var(--paper-progress-transition-duration, 0.08s);\n  transition-duration: var(--paper-progress-transition-duration, 0.08s);\n  -webkit-transition-timing-function: var(--paper-progress-transition-timing-function, ease);\n  transition-timing-function: var(--paper-progress-transition-timing-function, ease);\n  -webkit-transition-delay: var(--paper-progress-transition-delay, 0s);\n  transition-delay: var(--paper-progress-transition-delay, 0s);\n}\n\n#primaryProgress.tp-yt-paper-progress,#secondaryProgress.tp-yt-paper-progress {\n  position: absolute;\n  top: 0;\n  right: 0;\n  bottom: 0;\n  left: 0;\n  -webkit-transform-origin: left center;\n  transform-origin: left center;\n  -webkit-transform: scaleX(0);\n  transform: scaleX(0);\n  will-change: transform;\n}\n\n#primaryProgress.tp-yt-paper-progress {\n  background: var(--paper-progress-active-color, #0f9d58);\n}\n\n#secondaryProgress.tp-yt-paper-progress {\n  background: var(--paper-progress-secondary-color, #b7e1cd);\n}\n\ntp-yt-paper-progress[disabled] #primaryProgress.tp-yt-paper-progress {\n  background: var(--paper-progress-disabled-active-color, #9e9e9e);\n}\n\ntp-yt-paper-progress[disabled] #secondaryProgress.tp-yt-paper-progress {\n  background: var(--paper-progress-disabled-secondary-color, #e0e0e0);\n}\n\ntp-yt-paper-progress:not([disabled]) #primaryProgress.indeterminate.tp-yt-paper-progress {\n  -webkit-transform-origin: right center;\n  transform-origin: right center;\n  -webkit-animation: indeterminate-bar var(--paper-progress-indeterminate-cycle-duration, 2s) linear infinite;\n  animation: indeterminate-bar var(--paper-progress-indeterminate-cycle-duration, 2s) linear infinite;\n}\n\ntp-yt-paper-progress:not([disabled]) #primaryProgress.indeterminate.tp-yt-paper-progress::after {\n  content: \"\";\n  -webkit-transform-origin: center center;\n  transform-origin: center center;\n  -webkit-animation: indeterminate-splitter var(--paper-progress-indeterminate-cycle-duration, 2s) linear infinite;\n  animation: indeterminate-splitter var(--paper-progress-indeterminate-cycle-duration, 2s) linear infinite;\n}\n\n@-webkit-keyframes indeterminate-bar {\n0% {\n  -webkit-transform: scaleX(1) translateX(-100%);\n}\n\n50% {\n  -webkit-transform: scaleX(1) translateX(0%);\n}\n\n75% {\n  -webkit-transform: scaleX(1) translateX(0%);\n    -webkit-animation-timing-function: cubic-bezier(0.28, 0.62, 0.37, 0.91);\n}\n\n100% {\n  -webkit-transform: scaleX(0) translateX(0%);\n}\n\n}\n\n@-webkit-keyframes indeterminate-splitter {\n0% {\n  -webkit-transform: scaleX(0.75) translateX(-125%);\n}\n\n30% {\n  -webkit-transform: scaleX(0.75) translateX(-125%);\n    -webkit-animation-timing-function: cubic-bezier(0.42, 0, 0.6, 0.8);\n}\n\n90% {\n  -webkit-transform: scaleX(0.75) translateX(125%);\n}\n\n100% {\n  -webkit-transform: scaleX(0.75) translateX(125%);\n}\n\n}\n\n@keyframes indeterminate-bar {\n0% {\n  transform: scaleX(1) translateX(-100%);\n}\n\n50% {\n  transform: scaleX(1) translateX(0%);\n}\n\n75% {\n  transform: scaleX(1) translateX(0%);\n    animation-timing-function: cubic-bezier(0.28, 0.62, 0.37, 0.91);\n}\n\n100% {\n  transform: scaleX(0) translateX(0%);\n}\n\n}\n\n@keyframes indeterminate-splitter {\n0% {\n  transform: scaleX(0.75) translateX(-125%);\n}\n\n30% {\n  transform: scaleX(0.75) translateX(-125%);\n    animation-timing-function: cubic-bezier(0.42, 0, 0.6, 0.8);\n}\n\n90% {\n  transform: scaleX(0.75) translateX(125%);\n}\n\n100% {\n  transform: scaleX(0.75) translateX(125%);\n}\n\n}\n\ntp-yt-paper-slider {\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-pack: justify;\n  -webkit-justify-content: space-between;\n  justify-content: space-between;\n  -ms-flex-align: center;\n  -webkit-align-items: center;\n  align-items: center;\n  width: 200px;\n  cursor: default;\n  -webkit-user-select: none;\n  -moz-user-select: none;\n  -ms-user-select: none;\n  user-select: none;\n  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);\n  --paper-progress-active-color: var(\n    --paper-slider-active-color,\n    #3367d6\n  );\n  --paper-progress-secondary-color: var(\n    --paper-slider-secondary-color,\n    #7baaf7\n  );\n  --paper-progress-disabled-active-color: var(\n    --paper-slider-disabled-active-color,\n    #bdbdbd\n  );\n  --paper-progress-disabled-secondary-color: var(\n    --paper-slider-disabled-secondary-color,\n    #bdbdbd\n  );\n  --calculated-paper-slider-height: var(--paper-slider-height, 2px);\n}\n\ntp-yt-paper-slider:focus {\n  outline: none;\n}\n\n[dir=\"rtl\"] .tp-yt-paper-slider #sliderContainer.tp-yt-paper-slider, .tp-yt-paper-slider[dir=\"rtl\"] #sliderContainer.tp-yt-paper-slider {\n  -webkit-transform: scaleX(-1);\n  transform: scaleX(-1);\n}\n\ntp-yt-paper-slider[dir=rtl] #sliderContainer.tp-yt-paper-slider {\n  -webkit-transform: scaleX(-1);\n  transform: scaleX(-1);\n}\n\ntp-yt-paper-slider[dir=ltr] #sliderContainer.tp-yt-paper-slider {\n  -webkit-transform: scaleX(1);\n  transform: scaleX(1);\n}\n\n#sliderContainer.tp-yt-paper-slider {\n  position: relative;\n  width: 100%;\n  height: calc(30px + var(--calculated-paper-slider-height));\n  margin-left: var(--paper-slider-container-margin, calc(15px + var(--calculated-paper-slider-height) / 2));\n  margin-right: var(--paper-slider-container-margin, calc(15px + var(--calculated-paper-slider-height) / 2));\n  padding: 0 var(--paper-slider-container-padding, 0);\n}\n\n#sliderContainer.tp-yt-paper-slider:focus {\n  outline: 0;\n}\n\n#sliderContainer.editable.tp-yt-paper-slider {\n  margin-top: 12px;\n  margin-bottom: 12px;\n}\n\n.bar-container.tp-yt-paper-slider {\n  position: absolute;\n  top: 0;\n  bottom: 0;\n  left: 0;\n  right: 0;\n  overflow: hidden;\n}\n\n.ring.tp-yt-paper-slider > .bar-container.tp-yt-paper-slider {\n  left: var(--paper-slider-bar-container-ring-left, calc(5px + var(--calculated-paper-slider-height) / 2));\n  transition: left 0.18s ease;\n}\n\n.ring.expand.dragging.tp-yt-paper-slider > .bar-container.tp-yt-paper-slider {\n  transition: none;\n}\n\n.ring.expand.tp-yt-paper-slider:not(.pin) > .bar-container.tp-yt-paper-slider {\n  left: var(--paper-slider-bar-container-ring-left, calc(8px + var(--calculated-paper-slider-height) / 2));\n}\n\n#sliderBar.tp-yt-paper-slider {\n  padding: 15px 0;\n  width: 100%;\n  background-color: var(--paper-slider-bar-color, transparent);\n  --paper-progress-container-color: var(\n    --paper-slider-container-color,\n    #bdbdbd\n  );\n  --paper-progress-height: var(--calculated-paper-slider-height);\n  --paper-progress-container-border-radius: var(\n    --paper-slider-progress-container-border-radius,\n    0\n  );\n  --paper-progress-container-overflow: var(\n    --paper-slider-progress-container-overflow,\n    visible\n  );\n  --paper-progress-container-transform: var(\n    --paper-slider-progress-container-transform,\n    none\n  );\n}\n\n.slider-markers.tp-yt-paper-slider {\n  padding: inherit;\n  position: absolute;\n  top: 15px;\n  height: var(--calculated-paper-slider-height);\n  margin-top: var(--paper-slider-markers-margin, 0);\n  margin-left: var(--paper-slider-markers-margin, 0);\n  margin-right: 0;\n  left: 0;\n  right: -1px;\n  box-sizing: border-box;\n  pointer-events: none;\n  display: -ms-flexbox;\n  display: -webkit-flex;\n  display: flex;\n  -ms-flex-direction: row;\n  -webkit-flex-direction: row;\n  flex-direction: row;\n}\n\n.slider-marker.tp-yt-paper-slider {\n  -ms-flex: 1 1 0.000000001px;\n  -webkit-flex: 1;\n  flex: 1;\n  -webkit-flex-basis: 0.000000001px;\n  flex-basis: 0.000000001px;\n}\n\n.slider-markers.tp-yt-paper-slider::after,.slider-marker.tp-yt-paper-slider::after {\n  content: \"\";\n  display: block;\n  margin-left: var(--paper-slider-markers-margin-left, -1px);\n  width: var(--paper-slider-markers-width, 2px);\n  height: var(--paper-slider-markers-height, var(--calculated-paper-slider-height));\n  border-radius: 50%;\n  background-color: var(--paper-slider-markers-color, #000);\n}\n\n#sliderKnobContainer.tp-yt-paper-slider {\n  position: relative;\n  width: calc(100% - var(--paper-slider-container-padding, 0) * 2);\n  margin: auto;\n}\n\n.slider-knob.tp-yt-paper-slider {\n  position: absolute;\n  left: 0;\n  top: var(--paper-slider-knob-top, 0);\n  margin-left: calc(-15px - var(--calculated-paper-slider-height) / 2);\n  width: var(--paper-slider-knob-size, calc(30px + var(--calculated-paper-slider-height)));\n  height: var(--paper-slider-knob-size, calc(30px + var(--calculated-paper-slider-height)));\n}\n\n.transiting.tp-yt-paper-slider > .slider-knob.tp-yt-paper-slider {\n  transition: left 0.08s ease;\n}\n\n.slider-knob.tp-yt-paper-slider:focus {\n  outline: none;\n}\n\n.slider-knob.dragging.tp-yt-paper-slider {\n  transition: none;\n}\n\n.snaps.tp-yt-paper-slider > .slider-knob.dragging.tp-yt-paper-slider {\n  transition: -webkit-transform 0.08s ease;\n  transition: transform 0.08s ease;\n}\n\n.slider-knob-inner.tp-yt-paper-slider {\n  margin: 10px;\n  width: var(--paper-slider-knob-inner-size, calc(100% - 20px));\n  height: var(--paper-slider-knob-inner-size, calc(100% - 20px));\n  background-color: var(--paper-slider-knob-color, #3367d6);\n  border: var(--paper-slider-knob-border-style, 2px solid var(--paper-slider-knob-color, #3367d6));\n  border-radius: 50%;\n  box-shadow: var(--paper-slider-knob-box-shadow-style, none);\n  -moz-box-sizing: border-box;\n  box-sizing: border-box;\n  transition-property: -webkit-transform, background-color, border;\n  transition-property: transform, background-color, border;\n  transition-duration: 0.18s;\n  transition-timing-function: ease;\n}\n\n.expand.tp-yt-paper-slider:not(.pin) > .slider-knob-container.tp-yt-paper-slider > .slider-knob.tp-yt-paper-slider > .slider-knob-inner.tp-yt-paper-slider {\n  -webkit-transform: scale(1.5);\n  transform: scale(1.5);\n}\n\n.ring.tp-yt-paper-slider > .slider-knob-container.tp-yt-paper-slider > .slider-knob.tp-yt-paper-slider > .slider-knob-inner.tp-yt-paper-slider {\n  background-color: var(--paper-slider-knob-start-color, transparent);\n  border: var(--paper-slider-knob-start-border-style, 2px solid var(--paper-slider-knob-start-border-color, #bdbdbd));\n}\n\n.slider-knob-inner.tp-yt-paper-slider::before {\n  background-color: var(--paper-slider-pin-color, #3367d6);\n}\n\n.pin.tp-yt-paper-slider > .slider-knob-container.tp-yt-paper-slider > .slider-knob.tp-yt-paper-slider > .slider-knob-inner.tp-yt-paper-slider::before {\n  content: \"\";\n  position: absolute;\n  top: 0;\n  left: 50%;\n  margin-left: -13px;\n  width: 26px;\n  height: 26px;\n  border-radius: 50% 50% 50% 0;\n  -webkit-transform: rotate(-45deg) scale(0) translate(0);\n  transform: rotate(-45deg) scale(0) translate(0);\n}\n\n.slider-knob-inner.tp-yt-paper-slider::before,.slider-knob-inner.tp-yt-paper-slider::after {\n  transition: -webkit-transform 0.18s ease, background-color 0.18s ease;\n  transition: transform 0.18s ease, background-color 0.18s ease;\n}\n\n.pin.ring.tp-yt-paper-slider > .slider-knob-container.tp-yt-paper-slider > .slider-knob.tp-yt-paper-slider > .slider-knob-inner.tp-yt-paper-slider::before {\n  background-color: var(--paper-slider-pin-start-color, #bdbdbd);\n}\n\n.pin.expand.tp-yt-paper-slider > .slider-knob-container.tp-yt-paper-slider > .slider-knob.tp-yt-paper-slider > .slider-knob-inner.tp-yt-paper-slider::before {\n  -webkit-transform: rotate(-45deg) scale(1) translate(17px, -17px);\n  transform: rotate(-45deg) scale(1) translate(17px, -17px);\n}\n\n.pin.tp-yt-paper-slider > .slider-knob-container.tp-yt-paper-slider > .slider-knob.tp-yt-paper-slider > .slider-knob-inner.tp-yt-paper-slider::after {\n  content: attr(value);\n  position: absolute;\n  top: 0;\n  left: 50%;\n  margin-left: -16px;\n  width: 32px;\n  height: 26px;\n  text-align: center;\n  font-size: 10px;\n  -webkit-transform: scale(0) translate(0);\n  transform: scale(0) translate(0);\n}\n\n.pin.expand.tp-yt-paper-slider > .slider-knob-container.tp-yt-paper-slider > .slider-knob.tp-yt-paper-slider > .slider-knob-inner.tp-yt-paper-slider::after {\n  -webkit-transform: scale(1) translate(0, -17px);\n  transform: scale(1) translate(0, -17px);\n}\n\n.slider-input.tp-yt-paper-slider {\n  width: 50px;\n  overflow: hidden;\n  --paper-input-container-input_-_text-align:  center; --paper-input-container-input_-_overflow: initial; --paper-input-container-input_-_white-space: initial; --paper-input-container-input_-_text-overflow: initial; --paper-input-container-input_-_max-width: initial; --paper-input-container-input_-_box-sizing: initial; --paper-input-container-input_-_cursor: initial;;\n}\n\n#sliderContainer.disabled.tp-yt-paper-slider {\n  pointer-events: none;\n}\n\n.disabled.tp-yt-paper-slider > .slider-knob-container.tp-yt-paper-slider > .slider-knob.tp-yt-paper-slider > .slider-knob-inner.tp-yt-paper-slider {\n  background-color: var(--paper-slider-disabled-knob-color, #bdbdbd);\n  border: 2px solid var(--paper-slider-disabled-knob-color, #bdbdbd);\n  -webkit-transform: scale3d(0.75, 0.75, 1);\n  transform: scale3d(0.75, 0.75, 1);\n}\n\n.disabled.ring.tp-yt-paper-slider > .slider-knob-container.tp-yt-paper-slider > .slider-knob.tp-yt-paper-slider > .slider-knob-inner.tp-yt-paper-slider {\n  background-color: var(--paper-slider-knob-start-color, transparent);\n  border: 2px solid var(--paper-slider-knob-start-border-color, #bdbdbd);\n}\n\n";
    d.appendChild(document.createElement("style"));
    d.lastChild.setAttribute("css-build-single", "");
    d.lastChild.textContent = finalStyleText;
    document.head.appendChild(d);
}
)();
if (window["ytcsi"])
    window["ytcsi"]["tick"]("rses_dpj");
(function() {
    'use strict';
    var f, aaa = function(a) {
        var b = 0;
        return function() {
            return b < a.length ? {
                done: !1,
                value: a[b++]
            } : {
                done: !0
            }
        }
    }, aa = typeof Object.defineProperties == "function" ? Object.defineProperty : function(a, b, c) {
        if (a == Array.prototype || a == Object.prototype)
            return a;
        a[b] = c.value;
        return a
    }
    , baa = function(a) {
        a = ["object" == typeof globalThis && globalThis, a, "object" == typeof window && window, "object" == typeof self && self, "object" == typeof global && global];
        for (var b = 0; b < a.length; ++b) {
            var c = a[b];
            if (c && c.Math == Math)
                return c
        }
        throw Error("Cannot find global object")
    }, da = baa(this), ha = function(a, b) {
        if (b)
            a: {
                var c = da;
                a = a.split(".");
                for (var d = 0; d < a.length - 1; d++) {
                    var e = a[d];
                    if (!(e in c))
                        break a;
                    c = c[e]
                }
                a = a[a.length - 1];
                d = c[a];
                b = b(d);
                b != d && b != null && aa(c, a, {
                    configurable: !0,
                    writable: !0,
                    value: b
                })
            }
    };
    ha("Symbol", function(a) {
        if (a)
            return a;
        var b = function(h, l) {
            this.$jscomp$symbol$id_ = h;
            aa(this, "description", {
                configurable: !0,
                writable: !0,
                value: l
            })
        };
        b.prototype.toString = function() {
            return this.$jscomp$symbol$id_
        }
        ;
        var c = "jscomp_symbol_" + (Math.random() * 1E9 >>> 0) + "_"
          , d = 0
          , e = function(h) {
            if (this instanceof e)
                throw new TypeError("Symbol is not a constructor");
            return new b(c + (h || "") + "_" + d++,h)
        };
        return e
    });
    ha("Symbol.iterator", function(a) {
        if (a)
            return a;
        a = Symbol("Symbol.iterator");
        for (var b = "Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "), c = 0; c < b.length; c++) {
            var d = da[b[c]];
            typeof d === "function" && typeof d.prototype[a] != "function" && aa(d.prototype, a, {
                configurable: !0,
                writable: !0,
                value: function() {
                    return caa(aaa(this))
                }
            })
        }
        return a
    });
    ha("Symbol.asyncIterator", function(a) {
        return a ? a : Symbol("Symbol.asyncIterator")
    });
    var caa = function(a) {
        a = {
            next: a
        };
        a[Symbol.iterator] = function() {
            return this
        }
        ;
        return a
    }
      , ja = function(a) {
        return a.raw = a
    }
      , ka = function(a, b) {
        a.raw = b;
        return a
    }
      , g = function(a) {
        var b = typeof Symbol != "undefined" && Symbol.iterator && a[Symbol.iterator];
        if (b)
            return b.call(a);
        if (typeof a.length == "number")
            return {
                next: aaa(a)
            };
        throw Error(String(a) + " is not an iterable or ArrayLike")
    }
      , ma = function(a) {
        for (var b, c = []; !(b = a.next()).done; )
            c.push(b.value);
        return c
    }
      , oa = function(a) {
        return a instanceof Array ? a : ma(g(a))
    }
      , qa = function(a, b) {
        return Object.prototype.hasOwnProperty.call(a, b)
    }
      , daa = typeof Object.assign == "function" ? Object.assign : function(a, b) {
        for (var c = 1; c < arguments.length; c++) {
            var d = arguments[c];
            if (d)
                for (var e in d)
                    qa(d, e) && (a[e] = d[e])
        }
        return a
    }
    ;
    ha("Object.assign", function(a) {
        return a || daa
    });
    var eaa = typeof Object.create == "function" ? Object.create : function(a) {
        var b = function() {};
        b.prototype = a;
        return new b
    }
    , faa = function() {
        function a() {
            function c() {}
            new c;
            Reflect.construct(c, [], function() {});
            return new c instanceof c
        }
        if (typeof Reflect != "undefined" && Reflect.construct) {
            if (a())
                return Reflect.construct;
            var b = Reflect.construct;
            return function(c, d, e) {
                c = b(c, d);
                e && Reflect.setPrototypeOf(c, e.prototype);
                return c
            }
        }
        return function(c, d, e) {
            e === void 0 && (e = c);
            e = eaa(e.prototype || Object.prototype);
            return Function.prototype.apply.call(c, e, d) || e
        }
    }(), gaa;
    if (typeof Object.setPrototypeOf == "function")
        gaa = Object.setPrototypeOf;
    else {
        var haa;
        a: {
            var iaa = {
                a: !0
            }
              , jaa = {};
            try {
                jaa.__proto__ = iaa;
                haa = jaa.a;
                break a
            } catch (a) {}
            haa = !1
        }
        gaa = haa ? function(a, b) {
            a.__proto__ = b;
            if (a.__proto__ !== b)
                throw new TypeError(a + " is not extensible");
            return a
        }
        : null
    }
    var ra = gaa
      , k = function(a, b) {
        a.prototype = eaa(b.prototype);
        a.prototype.constructor = a;
        if (ra)
            ra(a, b);
        else
            for (var c in b)
                if (c != "prototype")
                    if (Object.defineProperties) {
                        var d = Object.getOwnPropertyDescriptor(b, c);
                        d && Object.defineProperty(a, c, d)
                    } else
                        a[c] = b[c];
        a.superClass_ = b.prototype
    }
      , sa = function() {
        this.isRunning_ = !1;
        this.yieldAllIterator_ = null;
        this.yieldResult = void 0;
        this.nextAddress = 1;
        this.finallyAddress_ = this.catchAddress_ = 0;
        this.finallyContexts_ = this.abruptCompletion_ = null
    }
      , kaa = function(a) {
        if (a.isRunning_)
            throw new TypeError("Generator is already running");
        a.isRunning_ = !0
    };
    sa.prototype.JSC$6242_next_ = function(a) {
        this.yieldResult = a
    }
    ;
    var laa = function(a, b) {
        a.abruptCompletion_ = {
            exception: b,
            isException: !0
        };
        a.nextAddress = a.catchAddress_ || a.finallyAddress_
    };
    sa.prototype.return = function(a) {
        this.abruptCompletion_ = {
            return: a
        };
        this.nextAddress = this.finallyAddress_
    }
    ;
    var n = function(a, b, c) {
        a.nextAddress = c;
        return {
            value: b
        }
    };
    sa.prototype.jumpTo = function(a) {
        this.nextAddress = a
    }
    ;
    var ta = function(a) {
        a.nextAddress = 0
    }
      , va = function(a, b, c) {
        a.catchAddress_ = b;
        c != void 0 && (a.finallyAddress_ = c)
    }
      , ya = function(a, b, c) {
        a.nextAddress = b;
        a.catchAddress_ = c || 0
    }
      , za = function(a, b) {
        a.catchAddress_ = b || 0;
        b = a.abruptCompletion_.exception;
        a.abruptCompletion_ = null;
        return b
    }
      , Aa = function(a, b, c, d) {
        d ? a.finallyContexts_[d] = a.abruptCompletion_ : a.finallyContexts_ = [a.abruptCompletion_];
        a.catchAddress_ = b || 0;
        a.finallyAddress_ = c || 0
    }
      , Ca = function(a, b, c) {
        c = a.finallyContexts_.splice(c || 0)[0];
        (c = a.abruptCompletion_ = a.abruptCompletion_ || c) ? c.isException ? a.nextAddress = a.catchAddress_ || a.finallyAddress_ : c.jumpTo != void 0 && a.finallyAddress_ < c.jumpTo ? (a.nextAddress = c.jumpTo,
        a.abruptCompletion_ = null) : a.nextAddress = a.finallyAddress_ : a.nextAddress = b
    }
      , maa = function(a) {
        this.JSC$6247_context_ = new sa;
        this.program_ = a
    }
      , oaa = function(a, b) {
        kaa(a.JSC$6247_context_);
        var c = a.JSC$6247_context_.yieldAllIterator_;
        if (c)
            return naa(a, "return"in c ? c["return"] : function(d) {
                return {
                    value: d,
                    done: !0
                }
            }
            , b, a.JSC$6247_context_.return);
        a.JSC$6247_context_.return(b);
        return Da(a)
    }
      , naa = function(a, b, c, d) {
        try {
            var e = b.call(a.JSC$6247_context_.yieldAllIterator_, c);
            if (!(e instanceof Object))
                throw new TypeError("Iterator result " + e + " is not an object");
            if (!e.done)
                return a.JSC$6247_context_.isRunning_ = !1,
                e;
            var h = e.value
        } catch (l) {
            return a.JSC$6247_context_.yieldAllIterator_ = null,
            laa(a.JSC$6247_context_, l),
            Da(a)
        }
        a.JSC$6247_context_.yieldAllIterator_ = null;
        d.call(a.JSC$6247_context_, h);
        return Da(a)
    }
      , Da = function(a) {
        for (; a.JSC$6247_context_.nextAddress; )
            try {
                var b = a.program_(a.JSC$6247_context_);
                if (b)
                    return a.JSC$6247_context_.isRunning_ = !1,
                    {
                        value: b.value,
                        done: !1
                    }
            } catch (c) {
                a.JSC$6247_context_.yieldResult = void 0,
                laa(a.JSC$6247_context_, c)
            }
        a.JSC$6247_context_.isRunning_ = !1;
        if (a.JSC$6247_context_.abruptCompletion_) {
            b = a.JSC$6247_context_.abruptCompletion_;
            a.JSC$6247_context_.abruptCompletion_ = null;
            if (b.isException)
                throw b.exception;
            return {
                value: b.return,
                done: !0
            }
        }
        return {
            value: void 0,
            done: !0
        }
    }
      , paa = function(a) {
        this.next = function(b) {
            kaa(a.JSC$6247_context_);
            a.JSC$6247_context_.yieldAllIterator_ ? b = naa(a, a.JSC$6247_context_.yieldAllIterator_.next, b, a.JSC$6247_context_.JSC$6242_next_) : (a.JSC$6247_context_.JSC$6242_next_(b),
            b = Da(a));
            return b
        }
        ;
        this.throw = function(b) {
            kaa(a.JSC$6247_context_);
            a.JSC$6247_context_.yieldAllIterator_ ? b = naa(a, a.JSC$6247_context_.yieldAllIterator_["throw"], b, a.JSC$6247_context_.JSC$6242_next_) : (laa(a.JSC$6247_context_, b),
            b = Da(a));
            return b
        }
        ;
        this.return = function(b) {
            return oaa(a, b)
        }
        ;
        this[Symbol.iterator] = function() {
            return this
        }
    }
      , qaa = function(a) {
        var b = Ea;
        a = new paa(new maa(a));
        ra && b.prototype && ra(a, b.prototype);
        return a
    }
      , raa = function(a) {
        function b(d) {
            return a.next(d)
        }
        function c(d) {
            return a.throw(d)
        }
        return new Promise(function(d, e) {
            function h(l) {
                l.done ? d(l.value) : Promise.resolve(l.value).then(b, c).then(h, e)
            }
            h(a.next())
        }
        )
    }
      , t = function(a) {
        return raa(new paa(new maa(a)))
    }
      , saa = function(a) {
        this[Symbol.asyncIterator] = function() {
            return this
        }
        ;
        this[Symbol.iterator] = function() {
            return a
        }
        ;
        this.next = function(b) {
            return Promise.resolve(a.next(b))
        }
        ;
        this["throw"] = function(b) {
            return new Promise(function(c, d) {
                var e = a["throw"];
                e !== void 0 ? c(e.call(a, b)) : (c = a["return"],
                c !== void 0 && c.call(a),
                d(new TypeError("no `throw` method")))
            }
            )
        }
        ;
        a["return"] !== void 0 && (this["return"] = function(b) {
            return Promise.resolve(a["return"](b))
        }
        )
    }
      , Fa = function() {
        for (var a = Number(this), b = [], c = a; c < arguments.length; c++)
            b[c - a] = arguments[c];
        return b
    };
    ha("Reflect", function(a) {
        return a ? a : {}
    });
    ha("Reflect.construct", function() {
        return faa
    });
    ha("Reflect.setPrototypeOf", function(a) {
        return a ? a : ra ? function(b, c) {
            try {
                return ra(b, c),
                !0
            } catch (d) {
                return !1
            }
        }
        : null
    });
    ha("Promise", function(a) {
        function b() {
            this.batch_ = null
        }
        function c(l) {
            return l instanceof e ? l : new e(function(m) {
                m(l)
            }
            )
        }
        if (a && (typeof da.PromiseRejectionEvent !== "undefined" || !da.Promise || da.Promise.toString().indexOf("[native code]") === -1))
            return a;
        b.prototype.asyncExecute = function(l) {
            if (this.batch_ == null) {
                this.batch_ = [];
                var m = this;
                this.asyncExecuteFunction(function() {
                    m.executeBatch_()
                })
            }
            this.batch_.push(l)
        }
        ;
        var d = da.setTimeout;
        b.prototype.asyncExecuteFunction = function(l) {
            d(l, 0)
        }
        ;
        b.prototype.executeBatch_ = function() {
            for (; this.batch_ && this.batch_.length; ) {
                var l = this.batch_;
                this.batch_ = [];
                for (var m = 0; m < l.length; ++m) {
                    var p = l[m];
                    l[m] = null;
                    try {
                        p()
                    } catch (q) {
                        this.asyncThrow_(q)
                    }
                }
            }
            this.batch_ = null
        }
        ;
        b.prototype.asyncThrow_ = function(l) {
            this.asyncExecuteFunction(function() {
                throw l
            })
        }
        ;
        var e = function(l) {
            this.state_ = 0;
            this.result_ = void 0;
            this.onSettledCallbacks_ = [];
            this.isRejectionHandled_ = !1;
            var m = this.createResolveAndReject_();
            try {
                l(m.resolve, m.reject)
            } catch (p) {
                m.reject(p)
            }
        };
        e.prototype.createResolveAndReject_ = function() {
            function l(q) {
                return function(r) {
                    p || (p = !0,
                    q.call(m, r))
                }
            }
            var m = this
              , p = !1;
            return {
                resolve: l(this.resolveTo_),
                reject: l(this.JSC$6263_reject_)
            }
        }
        ;
        e.prototype.resolveTo_ = function(l) {
            if (l === this)
                this.JSC$6263_reject_(new TypeError("A Promise cannot resolve to itself"));
            else if (l instanceof e)
                this.settleSameAsPromise_(l);
            else {
                a: switch (typeof l) {
                case "object":
                    var m = l != null;
                    break a;
                case "function":
                    m = !0;
                    break a;
                default:
                    m = !1;
                }
                m ? this.resolveToNonPromiseObj_(l) : this.fulfill_(l)
            }
        }
        ;
        e.prototype.resolveToNonPromiseObj_ = function(l) {
            var m = void 0;
            try {
                m = l.then
            } catch (p) {
                this.JSC$6263_reject_(p);
                return
            }
            typeof m == "function" ? this.settleSameAsThenable_(m, l) : this.fulfill_(l)
        }
        ;
        e.prototype.JSC$6263_reject_ = function(l) {
            this.settle_(2, l)
        }
        ;
        e.prototype.fulfill_ = function(l) {
            this.settle_(1, l)
        }
        ;
        e.prototype.settle_ = function(l, m) {
            if (this.state_ != 0)
                throw Error("Cannot settle(" + l + ", " + m + "): Promise already settled in state" + this.state_);
            this.state_ = l;
            this.result_ = m;
            this.state_ === 2 && this.scheduleUnhandledRejectionCheck_();
            this.executeOnSettledCallbacks_()
        }
        ;
        e.prototype.scheduleUnhandledRejectionCheck_ = function() {
            var l = this;
            d(function() {
                if (l.notifyUnhandledRejection_()) {
                    var m = da.console;
                    typeof m !== "undefined" && m.error(l.result_)
                }
            }, 1)
        }
        ;
        e.prototype.notifyUnhandledRejection_ = function() {
            if (this.isRejectionHandled_)
                return !1;
            var l = da.CustomEvent
              , m = da.Event
              , p = da.dispatchEvent;
            if (typeof p === "undefined")
                return !0;
            typeof l === "function" ? l = new l("unhandledrejection",{
                cancelable: !0
            }) : typeof m === "function" ? l = new m("unhandledrejection",{
                cancelable: !0
            }) : (l = da.document.createEvent("CustomEvent"),
            l.initCustomEvent("unhandledrejection", !1, !0, l));
            l.promise = this;
            l.reason = this.result_;
            return p(l)
        }
        ;
        e.prototype.executeOnSettledCallbacks_ = function() {
            if (this.onSettledCallbacks_ != null) {
                for (var l = 0; l < this.onSettledCallbacks_.length; ++l)
                    h.asyncExecute(this.onSettledCallbacks_[l]);
                this.onSettledCallbacks_ = null
            }
        }
        ;
        var h = new b;
        e.prototype.settleSameAsPromise_ = function(l) {
            var m = this.createResolveAndReject_();
            l.callWhenSettled_(m.resolve, m.reject)
        }
        ;
        e.prototype.settleSameAsThenable_ = function(l, m) {
            var p = this.createResolveAndReject_();
            try {
                l.call(m, p.resolve, p.reject)
            } catch (q) {
                p.reject(q)
            }
        }
        ;
        e.prototype.then = function(l, m) {
            function p(z, C) {
                return typeof z == "function" ? function(E) {
                    try {
                        q(z(E))
                    } catch (K) {
                        r(K)
                    }
                }
                : C
            }
            var q, r, x = new e(function(z, C) {
                q = z;
                r = C
            }
            );
            this.callWhenSettled_(p(l, q), p(m, r));
            return x
        }
        ;
        e.prototype.catch = function(l) {
            return this.then(void 0, l)
        }
        ;
        e.prototype.callWhenSettled_ = function(l, m) {
            function p() {
                switch (q.state_) {
                case 1:
                    l(q.result_);
                    break;
                case 2:
                    m(q.result_);
                    break;
                default:
                    throw Error("Unexpected state: " + q.state_);
                }
            }
            var q = this;
            this.onSettledCallbacks_ == null ? h.asyncExecute(p) : this.onSettledCallbacks_.push(p);
            this.isRejectionHandled_ = !0
        }
        ;
        e.resolve = c;
        e.reject = function(l) {
            return new e(function(m, p) {
                p(l)
            }
            )
        }
        ;
        e.race = function(l) {
            return new e(function(m, p) {
                for (var q = g(l), r = q.next(); !r.done; r = q.next())
                    c(r.value).callWhenSettled_(m, p)
            }
            )
        }
        ;
        e.all = function(l) {
            var m = g(l)
              , p = m.next();
            return p.done ? c([]) : new e(function(q, r) {
                function x(E) {
                    return function(K) {
                        z[E] = K;
                        C--;
                        C == 0 && q(z)
                    }
                }
                var z = []
                  , C = 0;
                do
                    z.push(void 0),
                    C++,
                    c(p.value).callWhenSettled_(x(z.length - 1), r),
                    p = m.next();
                while (!p.done)
            }
            )
        }
        ;
        return e
    });
    ha("Object.setPrototypeOf", function(a) {
        return a || ra
    });
    ha("Symbol.dispose", function(a) {
        return a ? a : Symbol("Symbol.dispose")
    });
    ha("WeakMap", function(a) {
        function b() {}
        function c(p) {
            var q = typeof p;
            return q === "object" && p !== null || q === "function"
        }
        function d(p) {
            if (!qa(p, h)) {
                var q = new b;
                aa(p, h, {
                    value: q
                })
            }
        }
        function e(p) {
            var q = Object[p];
            q && (Object[p] = function(r) {
                if (r instanceof b)
                    return r;
                Object.isExtensible(r) && d(r);
                return q(r)
            }
            )
        }
        if (function() {
            if (!a || !Object.seal)
                return !1;
            try {
                var p = Object.seal({})
                  , q = Object.seal({})
                  , r = new a([[p, 2], [q, 3]]);
                if (r.get(p) != 2 || r.get(q) != 3)
                    return !1;
                r.delete(p);
                r.set(q, 4);
                return !r.has(p) && r.get(q) == 4
            } catch (x) {
                return !1
            }
        }())
            return a;
        var h = "$jscomp_hidden_" + Math.random();
        e("freeze");
        e("preventExtensions");
        e("seal");
        var l = 0
          , m = function(p) {
            this.JSC$6267_id_ = (l += Math.random() + 1).toString();
            if (p) {
                p = g(p);
                for (var q; !(q = p.next()).done; )
                    q = q.value,
                    this.set(q[0], q[1])
            }
        };
        m.prototype.set = function(p, q) {
            if (!c(p))
                throw Error("Invalid WeakMap key");
            d(p);
            if (!qa(p, h))
                throw Error("WeakMap key fail: " + p);
            p[h][this.JSC$6267_id_] = q;
            return this
        }
        ;
        m.prototype.get = function(p) {
            return c(p) && qa(p, h) ? p[h][this.JSC$6267_id_] : void 0
        }
        ;
        m.prototype.has = function(p) {
            return c(p) && qa(p, h) && qa(p[h], this.JSC$6267_id_)
        }
        ;
        m.prototype.delete = function(p) {
            return c(p) && qa(p, h) && qa(p[h], this.JSC$6267_id_) ? delete p[h][this.JSC$6267_id_] : !1
        }
        ;
        return m
    });
    ha("Map", function(a) {
        if (function() {
            if (!a || typeof a != "function" || !a.prototype.entries || typeof Object.seal != "function")
                return !1;
            try {
                var m = Object.seal({
                    x: 4
                })
                  , p = new a(g([[m, "s"]]));
                if (p.get(m) != "s" || p.size != 1 || p.get({
                    x: 4
                }) || p.set({
                    x: 4
                }, "t") != p || p.size != 2)
                    return !1;
                var q = p.entries()
                  , r = q.next();
                if (r.done || r.value[0] != m || r.value[1] != "s")
                    return !1;
                r = q.next();
                return r.done || r.value[0].x != 4 || r.value[1] != "t" || !q.next().done ? !1 : !0
            } catch (x) {
                return !1
            }
        }())
            return a;
        var b = new WeakMap
          , c = function(m) {
            this[0] = {};
            this[1] = h();
            this.size = 0;
            if (m) {
                m = g(m);
                for (var p; !(p = m.next()).done; )
                    p = p.value,
                    this.set(p[0], p[1])
            }
        };
        c.prototype.set = function(m, p) {
            m = m === 0 ? 0 : m;
            var q = d(this, m);
            q.list || (q.list = this[0][q.id] = []);
            q.entry ? q.entry.value = p : (q.entry = {
                next: this[1],
                previous: this[1].previous,
                head: this[1],
                key: m,
                value: p
            },
            q.list.push(q.entry),
            this[1].previous.next = q.entry,
            this[1].previous = q.entry,
            this.size++);
            return this
        }
        ;
        c.prototype.delete = function(m) {
            m = d(this, m);
            return m.entry && m.list ? (m.list.splice(m.index, 1),
            m.list.length || delete this[0][m.id],
            m.entry.previous.next = m.entry.next,
            m.entry.next.previous = m.entry.previous,
            m.entry.head = null,
            this.size--,
            !0) : !1
        }
        ;
        c.prototype.clear = function() {
            this[0] = {};
            this[1] = this[1].previous = h();
            this.size = 0
        }
        ;
        c.prototype.has = function(m) {
            return !!d(this, m).entry
        }
        ;
        c.prototype.get = function(m) {
            return (m = d(this, m).entry) && m.value
        }
        ;
        c.prototype.entries = function() {
            return e(this, function(m) {
                return [m.key, m.value]
            })
        }
        ;
        c.prototype.keys = function() {
            return e(this, function(m) {
                return m.key
            })
        }
        ;
        c.prototype.values = function() {
            return e(this, function(m) {
                return m.value
            })
        }
        ;
        c.prototype.forEach = function(m, p) {
            for (var q = this.entries(), r; !(r = q.next()).done; )
                r = r.value,
                m.call(p, r[1], r[0], this)
        }
        ;
        c.prototype[Symbol.iterator] = c.prototype.entries;
        var d = function(m, p) {
            var q = p && typeof p;
            q == "object" || q == "function" ? b.has(p) ? q = b.get(p) : (q = "" + ++l,
            b.set(p, q)) : q = "p_" + p;
            var r = m[0][q];
            if (r && qa(m[0], q))
                for (m = 0; m < r.length; m++) {
                    var x = r[m];
                    if (p !== p && x.key !== x.key || p === x.key)
                        return {
                            id: q,
                            list: r,
                            index: m,
                            entry: x
                        }
                }
            return {
                id: q,
                list: r,
                index: -1,
                entry: void 0
            }
        }
          , e = function(m, p) {
            var q = m[1];
            return caa(function() {
                if (q) {
                    for (; q.head != m[1]; )
                        q = q.previous;
                    for (; q.next != q.head; )
                        return q = q.next,
                        {
                            done: !1,
                            value: p(q)
                        };
                    q = null
                }
                return {
                    done: !0,
                    value: void 0
                }
            })
        }
          , h = function() {
            var m = {};
            return m.previous = m.next = m.head = m
        }
          , l = 0;
        return c
    });
    var Ga = function(a, b, c) {
        if (a == null)
            throw new TypeError("The 'this' value for String.prototype." + c + " must not be null or undefined");
        if (b instanceof RegExp)
            throw new TypeError("First argument to String.prototype." + c + " must not be a regular expression");
        return a + ""
    };
    ha("String.prototype.endsWith", function(a) {
        return a ? a : function(b, c) {
            var d = Ga(this, b, "endsWith");
            b += "";
            c === void 0 && (c = d.length);
            c = Math.max(0, Math.min(c | 0, d.length));
            for (var e = b.length; e > 0 && c > 0; )
                if (d[--c] != b[--e])
                    return !1;
            return e <= 0
        }
    });
    var taa = function(a, b) {
        a instanceof String && (a += "");
        var c = 0
          , d = !1
          , e = {
            next: function() {
                if (!d && c < a.length) {
                    var h = c++;
                    return {
                        value: b(h, a[h]),
                        done: !1
                    }
                }
                d = !0;
                return {
                    done: !0,
                    value: void 0
                }
            }
        };
        e[Symbol.iterator] = function() {
            return e
        }
        ;
        return e
    };
    ha("Array.prototype.entries", function(a) {
        return a ? a : function() {
            return taa(this, function(b, c) {
                return [b, c]
            })
        }
    });
    ha("Array.prototype.keys", function(a) {
        return a ? a : function() {
            return taa(this, function(b) {
                return b
            })
        }
    });
    ha("String.prototype.startsWith", function(a) {
        return a ? a : function(b, c) {
            var d = Ga(this, b, "startsWith");
            b += "";
            var e = d.length
              , h = b.length;
            c = Math.max(0, Math.min(c | 0, d.length));
            for (var l = 0; l < h && c < e; )
                if (d[c++] != b[l++])
                    return !1;
            return l >= h
        }
    });
    ha("Number.isFinite", function(a) {
        return a ? a : function(b) {
            return typeof b !== "number" ? !1 : !isNaN(b) && b !== Infinity && b !== -Infinity
        }
    });
    ha("String.prototype.repeat", function(a) {
        return a ? a : function(b) {
            var c = Ga(this, null, "repeat");
            if (b < 0 || b > 1342177279)
                throw new RangeError("Invalid count value");
            b |= 0;
            for (var d = ""; b; )
                if (b & 1 && (d += c),
                b >>>= 1)
                    c += c;
            return d
        }
    });
    var uaa = function(a, b, c) {
        a instanceof String && (a = String(a));
        for (var d = a.length, e = 0; e < d; e++) {
            var h = a[e];
            if (b.call(c, h, e, a))
                return {
                    i: e,
                    v: h
                }
        }
        return {
            i: -1,
            v: void 0
        }
    };
    ha("Array.prototype.find", function(a) {
        return a ? a : function(b, c) {
            return uaa(this, b, c).v
        }
    });
    ha("Math.log2", function(a) {
        return a ? a : function(b) {
            return Math.log(b) / Math.LN2
        }
    });
    ha("Object.values", function(a) {
        return a ? a : function(b) {
            var c = [], d;
            for (d in b)
                qa(b, d) && c.push(b[d]);
            return c
        }
    });
    ha("Object.is", function(a) {
        return a ? a : function(b, c) {
            return b === c ? b !== 0 || 1 / b === 1 / c : b !== b && c !== c
        }
    });
    ha("Array.prototype.includes", function(a) {
        return a ? a : function(b, c) {
            var d = this;
            d instanceof String && (d = String(d));
            var e = d.length;
            c = c || 0;
            for (c < 0 && (c = Math.max(c + e, 0)); c < e; c++) {
                var h = d[c];
                if (h === b || Object.is(h, b))
                    return !0
            }
            return !1
        }
    });
    ha("String.prototype.includes", function(a) {
        return a ? a : function(b, c) {
            return Ga(this, b, "includes").indexOf(b, c || 0) !== -1
        }
    });
    ha("Number.MAX_SAFE_INTEGER", function() {
        return 9007199254740991
    });
    ha("Number.isInteger", function(a) {
        return a ? a : function(b) {
            return Number.isFinite(b) ? b === Math.floor(b) : !1
        }
    });
    ha("Number.isSafeInteger", function(a) {
        return a ? a : function(b) {
            return Number.isInteger(b) && Math.abs(b) <= Number.MAX_SAFE_INTEGER
        }
    });
    ha("Math.trunc", function(a) {
        return a ? a : function(b) {
            b = Number(b);
            if (isNaN(b) || b === Infinity || b === -Infinity || b === 0)
                return b;
            var c = Math.floor(Math.abs(b));
            return b < 0 ? -c : c
        }
    });
    ha("Number.isNaN", function(a) {
        return a ? a : function(b) {
            return typeof b === "number" && isNaN(b)
        }
    });
    ha("Array.prototype.values", function(a) {
        return a ? a : function() {
            return taa(this, function(b, c) {
                return c
            })
        }
    });
    ha("Array.from", function(a) {
        return a ? a : function(b, c, d) {
            c = c != null ? c : function(m) {
                return m
            }
            ;
            var e = []
              , h = typeof Symbol != "undefined" && Symbol.iterator && b[Symbol.iterator];
            if (typeof h == "function") {
                b = h.call(b);
                for (var l = 0; !(h = b.next()).done; )
                    e.push(c.call(d, h.value, l++))
            } else
                for (h = b.length,
                l = 0; l < h; l++)
                    e.push(c.call(d, b[l], l));
            return e
        }
    });
    ha("Math.clz32", function(a) {
        return a ? a : function(b) {
            b = Number(b) >>> 0;
            if (b === 0)
                return 32;
            var c = 0;
            (b & 4294901760) === 0 && (b <<= 16,
            c += 16);
            (b & 4278190080) === 0 && (b <<= 8,
            c += 8);
            (b & 4026531840) === 0 && (b <<= 4,
            c += 4);
            (b & 3221225472) === 0 && (b <<= 2,
            c += 2);
            (b & 2147483648) === 0 && c++;
            return c
        }
    });
    ha("Math.log10", function(a) {
        return a ? a : function(b) {
            return Math.log(b) / Math.LN10
        }
    });
    ha("Array.prototype.fill", function(a) {
        return a ? a : function(b, c, d) {
            var e = this.length || 0;
            c < 0 && (c = Math.max(0, e + c));
            if (d == null || d > e)
                d = e;
            d = Number(d);
            d < 0 && (d = Math.max(0, e + d));
            for (c = Number(c || 0); c < d; c++)
                this[c] = b;
            return this
        }
    });
    var Ha = function(a) {
        return a ? a : Array.prototype.fill
    };
    ha("Int8Array.prototype.fill", Ha);
    ha("Uint8Array.prototype.fill", Ha);
    ha("Uint8ClampedArray.prototype.fill", Ha);
    ha("Int16Array.prototype.fill", Ha);
    ha("Uint16Array.prototype.fill", Ha);
    ha("Int32Array.prototype.fill", Ha);
    ha("Uint32Array.prototype.fill", Ha);
    ha("Float32Array.prototype.fill", Ha);
    ha("Float64Array.prototype.fill", Ha);
    ha("Set", function(a) {
        if (function() {
            if (!a || typeof a != "function" || !a.prototype.entries || typeof Object.seal != "function")
                return !1;
            try {
                var c = Object.seal({
                    x: 4
                })
                  , d = new a(g([c]));
                if (!d.has(c) || d.size != 1 || d.add(c) != d || d.size != 1 || d.add({
                    x: 4
                }) != d || d.size != 2)
                    return !1;
                var e = d.entries()
                  , h = e.next();
                if (h.done || h.value[0] != c || h.value[1] != c)
                    return !1;
                h = e.next();
                return h.done || h.value[0] == c || h.value[0].x != 4 || h.value[1] != h.value[0] ? !1 : e.next().done
            } catch (l) {
                return !1
            }
        }())
            return a;
        var b = function(c) {
            this.JSC$6283_map_ = new Map;
            if (c) {
                c = g(c);
                for (var d; !(d = c.next()).done; )
                    this.add(d.value)
            }
            this.size = this.JSC$6283_map_.size
        };
        b.prototype.add = function(c) {
            c = c === 0 ? 0 : c;
            this.JSC$6283_map_.set(c, c);
            this.size = this.JSC$6283_map_.size;
            return this
        }
        ;
        b.prototype.delete = function(c) {
            c = this.JSC$6283_map_.delete(c);
            this.size = this.JSC$6283_map_.size;
            return c
        }
        ;
        b.prototype.clear = function() {
            this.JSC$6283_map_.clear();
            this.size = 0
        }
        ;
        b.prototype.has = function(c) {
            return this.JSC$6283_map_.has(c)
        }
        ;
        b.prototype.entries = function() {
            return this.JSC$6283_map_.entries()
        }
        ;
        b.prototype.values = function() {
            return this.JSC$6283_map_.values()
        }
        ;
        b.prototype.keys = b.prototype.values;
        b.prototype[Symbol.iterator] = b.prototype.values;
        b.prototype.forEach = function(c, d) {
            var e = this;
            this.JSC$6283_map_.forEach(function(h) {
                return c.call(d, h, h, e)
            })
        }
        ;
        return b
    });
    ha("Object.entries", function(a) {
        return a ? a : function(b) {
            var c = [], d;
            for (d in b)
                qa(b, d) && c.push([d, b[d]]);
            return c
        }
    });
    ha("Object.getOwnPropertySymbols", function(a) {
        return a ? a : function() {
            return []
        }
    });
    ha("globalThis", function(a) {
        return a || da
    });
    ha("Promise.prototype.finally", function(a) {
        return a ? a : function(b) {
            return this.then(function(c) {
                return Promise.resolve(b()).then(function() {
                    return c
                })
            }, function(c) {
                return Promise.resolve(b()).then(function() {
                    throw c;
                })
            })
        }
    });
    var vaa = function(a) {
        a = Math.trunc(a) || 0;
        a < 0 && (a += this.length);
        if (!(a < 0 || a >= this.length))
            return this[a]
    };
    ha("Array.prototype.at", function(a) {
        return a ? a : vaa
    });
    var Ja = function(a) {
        return a ? a : vaa
    };
    ha("Int8Array.prototype.at", Ja);
    ha("Uint8Array.prototype.at", Ja);
    ha("Uint8ClampedArray.prototype.at", Ja);
    ha("Int16Array.prototype.at", Ja);
    ha("Uint16Array.prototype.at", Ja);
    ha("Int32Array.prototype.at", Ja);
    ha("Uint32Array.prototype.at", Ja);
    ha("Float32Array.prototype.at", Ja);
    ha("Float64Array.prototype.at", Ja);
    ha("String.prototype.at", function(a) {
        return a ? a : vaa
    });
    ha("Math.sign", function(a) {
        return a ? a : function(b) {
            b = Number(b);
            return b === 0 || isNaN(b) ? b : b > 0 ? 1 : -1
        }
    });
    ha("Object.fromEntries", function(a) {
        return a ? a : function(b) {
            var c = {};
            if (!(Symbol.iterator in b))
                throw new TypeError("" + b + " is not iterable");
            b = b[Symbol.iterator].call(b);
            for (var d = b.next(); !d.done; d = b.next()) {
                d = d.value;
                if (Object(d) !== d)
                    throw new TypeError("iterable for fromEntries should yield objects");
                c[d[0]] = d[1]
            }
            return c
        }
    });
    ha("Array.prototype.flat", function(a) {
        return a ? a : function(b) {
            b = b === void 0 ? 1 : b;
            var c = [];
            Array.prototype.forEach.call(this, function(d) {
                Array.isArray(d) && b > 0 ? (d = Array.prototype.flat.call(d, b - 1),
                c.push.apply(c, d)) : c.push(d)
            });
            return c
        }
    });
    ha("String.prototype.replaceAll", function(a) {
        return a ? a : function(b, c) {
            if (b instanceof RegExp && !b.global)
                throw new TypeError("String.prototype.replaceAll called with a non-global RegExp argument.");
            return b instanceof RegExp ? this.replace(b, c) : this.replace(new RegExp(String(b).replace(/([-()\[\]{}+?*.$\^|,:#<!\\])/g, "\\$1").replace(/\x08/g, "\\x08"),"g"), c)
        }
    });
    ha("Array.prototype.findIndex", function(a) {
        return a ? a : function(b, c) {
            return uaa(this, b, c).i
        }
    });
    ha("String.raw", function(a) {
        return a ? a : function(b, c) {
            if (b == null)
                throw new TypeError("Cannot convert undefined or null to object");
            for (var d = b.raw, e = d.length, h = "", l = 0; l < e; ++l)
                h += d[l],
                l + 1 < e && l + 1 < arguments.length && (h += String(arguments[l + 1]));
            return h
        }
    });
    ha("String.prototype.padStart", function(a) {
        return a ? a : function(b, c) {
            var d = Ga(this, null, "padStart");
            b -= d.length;
            c = c !== void 0 ? String(c) : " ";
            return (b > 0 && c ? c.repeat(Math.ceil(b / c.length)).substring(0, b) : "") + d
        }
    });
    ha("String.fromCodePoint", function(a) {
        return a ? a : function(b) {
            for (var c = "", d = 0; d < arguments.length; d++) {
                var e = Number(arguments[d]);
                if (e < 0 || e > 1114111 || e !== Math.floor(e))
                    throw new RangeError("invalid_code_point " + e);
                e <= 65535 ? c += String.fromCharCode(e) : (e -= 65536,
                c += String.fromCharCode(e >>> 10 & 1023 | 55296),
                c += String.fromCharCode(e & 1023 | 56320))
            }
            return c
        }
    });
    ha("String.prototype.codePointAt", function(a) {
        return a ? a : function(b) {
            var c = Ga(this, null, "codePointAt")
              , d = c.length;
            b = Number(b) || 0;
            if (b >= 0 && b < d) {
                b |= 0;
                var e = c.charCodeAt(b);
                if (e < 55296 || e > 56319 || b + 1 === d)
                    return e;
                b = c.charCodeAt(b + 1);
                return b < 56320 || b > 57343 ? e : (e - 55296) * 1024 + b + 9216
            }
        }
    });
    ha("Array.prototype.flatMap", function(a) {
        return a ? a : function(b, c) {
            var d = [];
            Array.prototype.forEach.call(this, function(e, h) {
                e = b.call(c, e, h, this);
                Array.isArray(e) ? d.push.apply(d, e) : d.push(e)
            });
            return d
        }
    });
    ha("Reflect.ownKeys", function(a) {
        return a ? a : function(b) {
            var c = []
              , d = Object.getOwnPropertyNames(b);
            b = Object.getOwnPropertySymbols(b);
            for (var e = 0; e < d.length; e++)
                (d[e].substring(0, 14) == "jscomp_symbol_" ? b : c).push(d[e]);
            return c.concat(b)
        }
    });
    ha("Object.getOwnPropertyDescriptors", function(a) {
        return a ? a : function(b) {
            for (var c = {}, d = Reflect.ownKeys(b), e = 0; e < d.length; e++)
                c[d[e]] = Object.getOwnPropertyDescriptor(b, d[e]);
            return c
        }
    });
    ha("Number.parseInt", function(a) {
        return a || parseInt
    });
    ha("WeakSet", function(a) {
        if (function() {
            if (!a || !Object.seal)
                return !1;
            try {
                var c = Object.seal({})
                  , d = Object.seal({})
                  , e = new a([c]);
                if (!e.has(c) || e.has(d))
                    return !1;
                e.delete(c);
                e.add(d);
                return !e.has(c) && e.has(d)
            } catch (h) {
                return !1
            }
        }())
            return a;
        var b = function(c) {
            this.JSC$6288_map_ = new WeakMap;
            if (c) {
                c = g(c);
                for (var d; !(d = c.next()).done; )
                    this.add(d.value)
            }
        };
        b.prototype.add = function(c) {
            this.JSC$6288_map_.set(c, !0);
            return this
        }
        ;
        b.prototype.has = function(c) {
            return this.JSC$6288_map_.has(c)
        }
        ;
        b.prototype.delete = function(c) {
            return this.JSC$6288_map_.delete(c)
        }
        ;
        return b
    });
    ha("Promise.allSettled", function(a) {
        function b(d) {
            return {
                status: "fulfilled",
                value: d
            }
        }
        function c(d) {
            return {
                status: "rejected",
                reason: d
            }
        }
        return a ? a : function(d) {
            var e = this;
            d = Array.from(d, function(h) {
                return e.resolve(h).then(b, c)
            });
            return e.all(d)
        }
    });
    /*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
    var waa = waa || {}
      , Na = this || self
      , Oa = function(a, b, c) {
        a = a.split(".");
        c = c || Na;
        a[0]in c || typeof c.execScript == "undefined" || c.execScript("var " + a[0]);
        for (var d; a.length && (d = a.shift()); )
            a.length || b === void 0 ? c[d] && c[d] !== Object.prototype[d] ? c = c[d] : c = c[d] = {} : c[d] = b
    }
      , Qa = function(a, b) {
        var c = Pa("WIZ_global_data.oxN3nb");
        a = c && c[a];
        return a != null ? a : b
    }
      , xaa = /^[a-zA-Z_$][a-zA-Z0-9._$]*$/
      , Ua = function(a) {
        if (typeof a !== "string" || !a || a.search(xaa) == -1)
            throw Error("Invalid module identifier");
        if (!Sa || Sa.type != "goog")
            throw Error("Module " + a + " has been loaded incorrectly. Note, modules cannot be loaded as normal scripts. They require some kind of pre-processing step. You're likely trying to load a module via a script tag or as a part of a concatenated bundle without rewriting the module. For more info see: https://github.com/google/closure-library/wiki/goog.module:-an-ES6-module-like-alternative-to-goog.provide.");
        if (Sa.moduleName)
            throw Error("goog.module may only be called once per module.");
        Sa.moduleName = a
    };
    Ua.get = function() {
        return null
    }
    ;
    var Sa = null
      , Pa = function(a, b) {
        a = a.split(".");
        b = b || Na;
        for (var c = 0; c < a.length; c++)
            if (b = b[a[c]],
            b == null)
                return null;
        return b
    }
      , Va = function(a) {
        a.instance_ = void 0;
        a.getInstance = function() {
            return a.instance_ ? a.instance_ : a.instance_ = new a
        }
    }
      , Xa = function(a) {
        var b = typeof a;
        return b != "object" ? b : a ? Array.isArray(a) ? "array" : b : "null"
    }
      , Ya = function(a) {
        var b = Xa(a);
        return b == "array" || b == "object" && typeof a.length == "number"
    }
      , $a = function(a) {
        var b = typeof a;
        return b == "object" && a != null || b == "function"
    }
      , ab = function(a) {
        return Object.prototype.hasOwnProperty.call(a, yaa) && a[yaa] || (a[yaa] = ++zaa)
    }
      , yaa = "closure_uid_" + (Math.random() * 1E9 >>> 0)
      , zaa = 0
      , Aaa = function(a) {
        var b = Xa(a);
        if (b == "object" || b == "array") {
            if (typeof a.clone === "function")
                return a.clone();
            if (typeof Map !== "undefined" && a instanceof Map)
                return new Map(a);
            if (typeof Set !== "undefined" && a instanceof Set)
                return new Set(a);
            b = b == "array" ? [] : {};
            for (var c in a)
                b[c] = Aaa(a[c]);
            return b
        }
        return a
    }
      , Baa = function(a, b, c) {
        return a.call.apply(a.bind, arguments)
    }
      , Caa = function(a, b, c) {
        if (!a)
            throw Error();
        if (arguments.length > 2) {
            var d = Array.prototype.slice.call(arguments, 2);
            return function() {
                var e = Array.prototype.slice.call(arguments);
                Array.prototype.unshift.apply(e, d);
                return a.apply(b, e)
            }
        }
        return function() {
            return a.apply(b, arguments)
        }
    }
      , bb = function(a, b, c) {
        bb = Function.prototype.bind && Function.prototype.bind.toString().indexOf("native code") != -1 ? Baa : Caa;
        return bb.apply(null, arguments)
    }
      , cb = function(a, b) {
        var c = Array.prototype.slice.call(arguments, 1);
        return function() {
            var d = c.slice();
            d.push.apply(d, arguments);
            return a.apply(this, d)
        }
    }
      , eb = function() {
        return Date.now()
    }
      , fb = function(a, b) {
        function c() {}
        c.prototype = b.prototype;
        a.superClass_ = b.prototype;
        a.prototype = new c;
        a.prototype.constructor = a;
        a.base = function(d, e, h) {
            for (var l = Array(arguments.length - 2), m = 2; m < arguments.length; m++)
                l[m - 2] = arguments[m];
            return b.prototype[e].apply(d, l)
        }
    }
      , Daa = function(a) {
        return a
    }
      , Eaa = function(a) {
        var b = null
          , c = Na.trustedTypes;
        if (!c || !c.createPolicy)
            return b;
        try {
            b = c.createPolicy(a, {
                createHTML: Daa,
                createScript: Daa,
                createScriptURL: Daa
            })
        } catch (d) {
            Na.console && Na.console.error(d.message)
        }
        return b
    };
    var u = function(a, b, c, d) {
        var e = arguments.length, h = e < 3 ? b : d === null ? d = Object.getOwnPropertyDescriptor(b, c) : d, l;
        if (typeof Reflect === "object" && Reflect && typeof Reflect.decorate === "function")
            h = Reflect.decorate(a, b, c, d);
        else
            for (var m = a.length - 1; m >= 0; m--)
                if (l = a[m])
                    h = (e < 3 ? l(h) : e > 3 ? l(b, c, h) : l(b, c)) || h;
        return e > 3 && h && Object.defineProperty(b, c, h),
        h
    }
      , v = function(a, b) {
        if (typeof Reflect === "object" && Reflect && typeof Reflect.metadata === "function")
            return Reflect.metadata(a, b)
    };
    function hb(a, b) {
        if (Error.captureStackTrace)
            Error.captureStackTrace(this, hb);
        else {
            var c = Error().stack;
            c && (this.stack = c)
        }
        a && (this.message = String(a));
        b !== void 0 && (this.cause = b)
    }
    fb(hb, Error);
    hb.prototype.name = "CustomError";
    var Faa;
    function Gaa(a, b) {
        var c = hb.call;
        a = a.split("%s");
        for (var d = "", e = a.length - 1, h = 0; h < e; h++)
            d += a[h] + (h < b.length ? b[h] : "%s");
        c.call(hb, this, d + a[e])
    }
    fb(Gaa, hb);
    Gaa.prototype.name = "AssertionError";
    var Haa = function(a) {
        a = a.url;
        var b = /[?&]dsh=1(&|$)/.test(a);
        this.isSonicV2OrV3_ = !b && /[?&]ae=1(&|$)/.test(a);
        this.isSonicV4_ = !b && /[?&]ae=2(&|$)/.test(a);
        if ((this.adurlMatches_ = /[?&]adurl=([^&]*)/.exec(a)) && this.adurlMatches_[1]) {
            try {
                var c = decodeURIComponent(this.adurlMatches_[1])
            } catch (d) {
                c = null
            }
            this.adurl_ = c
        }
    };
    var lb = function(a, b) {
        return a.lastIndexOf(b, 0) == 0
    }
      , mb = function(a, b) {
        var c = a.length - b.length;
        return c >= 0 && a.indexOf(b, c) == c
    }
      , nb = function(a) {
        return /^[\s\xa0]*$/.test(a)
    }
      , ob = String.prototype.trim ? function(a) {
        return a.trim()
    }
    : function(a) {
        return /^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]
    }
      , Iaa = /&/g
      , Jaa = /</g
      , Kaa = />/g
      , Laa = /"/g
      , Maa = /'/g
      , Naa = /\x00/g
      , Oaa = /[\x00&<>"']/
      , pb = function(a, b) {
        return a.indexOf(b) != -1
    }
      , qb = function(a, b) {
        return pb(a.toLowerCase(), b.toLowerCase())
    }
      , rb = function(a, b) {
        var c = 0;
        a = ob(String(a)).split(".");
        b = ob(String(b)).split(".");
        for (var d = Math.max(a.length, b.length), e = 0; c == 0 && e < d; e++) {
            var h = a[e] || ""
              , l = b[e] || "";
            do {
                h = /(\d*)(\D*)(.*)/.exec(h) || ["", "", "", ""];
                l = /(\d*)(\D*)(.*)/.exec(l) || ["", "", "", ""];
                if (h[0].length == 0 && l[0].length == 0)
                    break;
                c = Paa(h[1].length == 0 ? 0 : parseInt(h[1], 10), l[1].length == 0 ? 0 : parseInt(l[1], 10)) || Paa(h[2].length == 0, l[2].length == 0) || Paa(h[2], l[2]);
                h = h[3];
                l = l[3]
            } while (c == 0)
        }
        return c
    }
      , Paa = function(a, b) {
        return a < b ? -1 : a > b ? 1 : 0
    };
    /*

 SPDX-License-Identifier: Apache-2.0
*/
    function sb(a) {
        return {
            valueOf: a
        }.valueOf()
    }
    ;var Qaa, Raa = function() {
        Qaa === void 0 && (Qaa = Eaa("goog#html"));
        return Qaa
    };
    var tb = function(a, b) {
        this.stringConstValueWithSecurityContract__googStringSecurityPrivate_ = a === Saa && b || "";
        this.STRING_CONST_TYPE_MARKER__GOOG_STRING_SECURITY_PRIVATE_ = Taa
    };
    tb.prototype.toString = function() {
        return this.stringConstValueWithSecurityContract__googStringSecurityPrivate_
    }
    ;
    var vb = function(a) {
        return a instanceof tb && a.constructor === tb && a.STRING_CONST_TYPE_MARKER__GOOG_STRING_SECURITY_PRIVATE_ === Taa ? a.stringConstValueWithSecurityContract__googStringSecurityPrivate_ : "type_error:Const"
    }
      , xb = function(a) {
        return new tb(Saa,a)
    }
      , Taa = {}
      , Saa = {};
    xb("");
    var zb = function(a) {
        this.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue_ = a
    };
    zb.prototype.toString = function() {
        return this.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue_ + ""
    }
    ;
    var Waa = function(a, b) {
        a = Uaa.exec(Ab(a).toString());
        var c = a[3] || "";
        return Db(a[1] + Vaa("?", a[2] || "", b) + Vaa("#", c))
    }
      , Ab = function(a) {
        return a instanceof zb && a.constructor === zb ? a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue_ : "type_error:TrustedResourceUrl"
    }
      , Uaa = /^([^?#]*)(\?[^#]*)?(#[\s\S]*)?/
      , Xaa = {}
      , Db = function(a) {
        var b = Raa();
        a = b ? b.createScriptURL(a) : a;
        return new zb(a,Xaa)
    }
      , Vaa = function(a, b, c) {
        if (c == null)
            return b;
        if (typeof c === "string")
            return c ? a + encodeURIComponent(c) : "";
        for (var d in c)
            if (Object.prototype.hasOwnProperty.call(c, d)) {
                var e = c[d];
                e = Array.isArray(e) ? e : [e];
                for (var h = 0; h < e.length; h++) {
                    var l = e[h];
                    l != null && (b || (b = a),
                    b += (b.length > a.length ? "&" : "") + encodeURIComponent(d) + "=" + encodeURIComponent(String(l)))
                }
            }
        return b
    };
    var Yaa = ja([""])
      , Zaa = ka([""], ["\\0"])
      , $aa = ka(["\n"], ["\\n"])
      , aba = ka([""], ["\\u0000"]);
    function Eb(a) {
        return a.toString().indexOf("`") === -1
    }
    Eb(function(a) {
        return a(Yaa)
    }) || Eb(function(a) {
        return a(Zaa)
    }) || Eb(function(a) {
        return a($aa)
    }) || Eb(function(a) {
        return a(aba)
    });
    var bba = {};
    var Fb = function(a, b) {
        this.privateDoNotAccessOrElseWrappedUrl = b
    };
    Fb.prototype.toString = function() {
        return this.privateDoNotAccessOrElseWrappedUrl
    }
    ;
    function Gb(a) {
        return new Fb(bba,a)
    }
    var cba = Gb("about:blank")
      , Hb = Gb("about:invalid#zClosurez");
    function Ib(a) {
        return a instanceof Fb
    }
    function Jb(a) {
        if (Ib(a))
            return a.privateDoNotAccessOrElseWrappedUrl;
        throw Error("")
    }
    ;var dba = function(a) {
        this.isValid = a
    };
    function Kb(a) {
        return new dba(function(b) {
            return b.substr(0, a.length + 1).toLowerCase() === a + ":"
        }
        )
    }
    var eba = new dba(function(a) {
        return /^[^:]*([/?#]|$)/.test(a)
    }
    )
      , fba = Kb("data")
      , gba = Kb("http")
      , hba = Kb("https")
      , iba = Kb("ftp")
      , jba = Kb("mailto")
      , kba = Kb("intent")
      , lba = Kb("vnd.youtube")
      , mba = [fba, gba, hba, jba, iba, eba];
    function Nb(a, b) {
        b = b === void 0 ? mba : b;
        if (Ib(a))
            return a;
        for (var c = 0; c < b.length; ++c) {
            var d = b[c];
            if (d instanceof dba && d.isValid(a))
                return Gb(a)
        }
    }
    function Ob(a, b) {
        b = b === void 0 ? mba : b;
        return Nb(a, b) || Hb
    }
    function Qb(a) {
        if (typeof MediaSource !== "undefined" && a instanceof MediaSource)
            return Gb(URL.createObjectURL(a));
        var b = a.type.match(/^([^;]+)(?:;\w+=(?:\w+|"[\w;,= ]+"))*$/i);
        if ((b == null ? void 0 : b.length) !== 2 || !(/^image\/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon|heic|heif|avif|x-ms-bmp)$/i.test(b[1]) || /^video\/(?:mpeg|mp4|ogg|webm|x-matroska|quicktime|x-ms-wmv)$/i.test(b[1]) || /^audio\/(?:3gpp2|3gpp|aac|amr|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)$/i.test(b[1]) || /^font\/\w+/i.test(b[1])))
            throw Error("");
        return Gb(URL.createObjectURL(a))
    }
    function Sb(a) {
        for (var b = Fa.apply(1, arguments), c = [a[0]], d = 0; d < b.length; d++)
            c.push(String(b[d])),
            c.push(a[d + 1]);
        return Gb(c.join(""))
    }
    var nba = sb(function() {
        return typeof URL === "function"
    });
    function oba(a) {
        if (!nba) {
            a: {
                var b = document.createElement("a");
                try {
                    b.href = a
                } catch (c) {
                    a = void 0;
                    break a
                }
                a = b.protocol;
                a = a === ":" || a === "" ? "https:" : a
            }
            return a
        }
        try {
            b = new URL(a)
        } catch (c) {
            return "https:"
        }
        return b.protocol
    }
    var pba = ["data:", "http:", "https:", "mailto:", "ftp:"]
      , qba = /^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
    function Ub(a) {
        a instanceof Fb ? a = Jb(a) : a = qba.test(a) ? a : void 0;
        return a
    }
    ;function Vb(a, b) {
        b = Ub(b);
        b !== void 0 && (a.href = b)
    }
    ;var rba = function(a) {
        this.privateDoNotAccessOrElseWrappedAttributePrefix = a
    };
    rba.prototype.toString = function() {
        return this.privateDoNotAccessOrElseWrappedAttributePrefix
    }
    ;
    function Xb(a) {
        return a[a.length - 1]
    }
    var Yb = function(a, b) {
        return Array.prototype.indexOf.call(a, b, void 0)
    }
      , Zb = function(a, b, c) {
        Array.prototype.forEach.call(a, b, c)
    };
    function sba(a, b, c) {
        var d = a.length
          , e = typeof a === "string" ? a.split("") : a;
        for (--d; d >= 0; --d)
            d in e && b.call(c, e[d], d, a)
    }
    var ac = function(a, b, c) {
        return Array.prototype.filter.call(a, b, c)
    }
      , bc = function(a, b, c) {
        return Array.prototype.map.call(a, b, c)
    }
      , tba = function(a, b, c) {
        return Array.prototype.reduce.call(a, b, c)
    }
      , dc = function(a, b, c) {
        return Array.prototype.some.call(a, b, c)
    }
      , uba = function(a, b, c) {
        return Array.prototype.every.call(a, b, c)
    };
    function ec(a, b, c) {
        b = vba(a, b, c);
        return b < 0 ? null : typeof a === "string" ? a.charAt(b) : a[b]
    }
    function vba(a, b, c) {
        for (var d = a.length, e = typeof a === "string" ? a.split("") : a, h = 0; h < d; h++)
            if (h in e && b.call(c, e[h], h, a))
                return h;
        return -1
    }
    function wba(a) {
        var b = fc
          , c = a.length
          , d = typeof a === "string" ? a.split("") : a;
        for (--c; c >= 0; c--)
            if (c in d && b.call(void 0, d[c], c, a))
                return c;
        return -1
    }
    function hc(a, b) {
        return Yb(a, b) >= 0
    }
    function xba(a, b) {
        hc(a, b) || a.push(b)
    }
    function ic(a, b) {
        b = Yb(a, b);
        var c;
        (c = b >= 0) && jc(a, b);
        return c
    }
    function jc(a, b) {
        Array.prototype.splice.call(a, b, 1)
    }
    function yba(a, b) {
        b = vba(a, b);
        b >= 0 && jc(a, b)
    }
    function zba(a) {
        return Array.prototype.concat.apply([], arguments)
    }
    function lc(a) {
        var b = a.length;
        if (b > 0) {
            for (var c = Array(b), d = 0; d < b; d++)
                c[d] = a[d];
            return c
        }
        return []
    }
    function mc(a, b) {
        for (var c = 1; c < arguments.length; c++) {
            var d = arguments[c];
            if (Ya(d)) {
                var e = a.length || 0
                  , h = d.length || 0;
                a.length = e + h;
                for (var l = 0; l < h; l++)
                    a[e + l] = d[l]
            } else
                a.push(d)
        }
    }
    function Aba(a, b, c, d) {
        Array.prototype.splice.apply(a, Bba(arguments, 1))
    }
    function Bba(a, b, c) {
        return arguments.length <= 2 ? Array.prototype.slice.call(a, b) : Array.prototype.slice.call(a, b, c)
    }
    function nc(a, b) {
        b = b || a;
        for (var c = 0, d = 0, e = {}; d < a.length; ) {
            var h = a[d++]
              , l = $a(h) ? "o" + ab(h) : (typeof h).charAt(0) + h;
            Object.prototype.hasOwnProperty.call(e, l) || (e[l] = !0,
            b[c++] = h)
        }
        b.length = c
    }
    function Cba(a, b, c) {
        c = c || Dba;
        for (var d = 0, e = a.length, h; d < e; ) {
            var l = d + (e - d >>> 1);
            var m = c(b, a[l]);
            m > 0 ? d = l + 1 : (e = l,
            h = !m)
        }
        return h ? d : -d - 1
    }
    function oc(a, b, c) {
        if (!Ya(a) || !Ya(b) || a.length != b.length)
            return !1;
        var d = a.length;
        c = c || Eba;
        for (var e = 0; e < d; e++)
            if (!c(a[e], b[e]))
                return !1;
        return !0
    }
    function Dba(a, b) {
        return a > b ? 1 : a < b ? -1 : 0
    }
    function Eba(a, b) {
        return a === b
    }
    function Fba(a, b, c) {
        b = Array.prototype.splice.call(a, b, 1);
        Array.prototype.splice.call(a, c, 0, b[0])
    }
    ;var pc = {};
    function Gba(a) {
        var b = [], c = 0, d;
        for (d in a)
            b[c++] = d;
        return b
    }
    function Hba(a, b) {
        for (var c in a)
            if (a[c] == b)
                return !0;
        return !1
    }
    function Iba(a, b, c) {
        for (var d in a)
            if (b.call(c, a[d], d, a))
                return d
    }
    function Jba(a) {
        if (!a || typeof a !== "object")
            return a;
        if (typeof a.clone === "function")
            return a.clone();
        if (typeof Map !== "undefined" && a instanceof Map)
            return new Map(a);
        if (typeof Set !== "undefined" && a instanceof Set)
            return new Set(a);
        if (a instanceof Date)
            return new Date(a.getTime());
        var b = Array.isArray(a) ? [] : typeof ArrayBuffer !== "function" || typeof ArrayBuffer.isView !== "function" || !ArrayBuffer.isView(a) || a instanceof DataView ? {} : new a.constructor(a.length), c;
        for (c in a)
            b[c] = Jba(a[c]);
        return b
    }
    var Kba = "constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");
    function Lba(a) {
        var b = arguments.length;
        if (b == 1 && Array.isArray(arguments[0]))
            return Lba.apply(null, arguments[0]);
        if (b % 2)
            throw Error("Uneven number of arguments");
        for (var c = {}, d = 0; d < b; d += 2)
            c[arguments[d]] = arguments[d + 1];
        return c
    }
    function Mba(a) {
        var b = arguments.length;
        if (b == 1 && Array.isArray(arguments[0]))
            return Mba.apply(null, arguments[0]);
        for (var c = {}, d = 0; d < b; d++)
            c[arguments[d]] = !0;
        return c
    }
    pc.add = function(a, b, c) {
        if (a !== null && b in a)
            throw Error("The object already contains the key \"" + b + "\"");
        a[b] = c
    }
    ;
    pc.clear = function(a) {
        for (var b in a)
            delete a[b]
    }
    ;
    pc.clone = function(a) {
        var b = {}, c;
        for (c in a)
            b[c] = a[c];
        return b
    }
    ;
    pc.contains = function(a, b) {
        return Hba(a, b)
    }
    ;
    pc.containsKey = function(a, b) {
        return a !== null && b in a
    }
    ;
    pc.containsValue = Hba;
    pc.create = Lba;
    pc.createImmutableView = function(a) {
        var b = a;
        Object.isFrozen && !Object.isFrozen(a) && (b = Object.create(a),
        Object.freeze(b));
        return b
    }
    ;
    pc.createSet = Mba;
    pc.equals = function(a, b) {
        for (var c in a)
            if (!(c in b) || a[c] !== b[c])
                return !1;
        for (var d in b)
            if (!(d in a))
                return !1;
        return !0
    }
    ;
    pc.every = function(a, b, c) {
        for (var d in a)
            if (!b.call(c, a[d], d, a))
                return !1;
        return !0
    }
    ;
    pc.extend = function(a, b) {
        for (var c, d, e = 1; e < arguments.length; e++) {
            d = arguments[e];
            for (c in d)
                a[c] = d[c];
            for (var h = 0; h < Kba.length; h++)
                c = Kba[h],
                Object.prototype.hasOwnProperty.call(d, c) && (a[c] = d[c])
        }
    }
    ;
    pc.filter = function(a, b, c) {
        var d = {}, e;
        for (e in a)
            b.call(c, a[e], e, a) && (d[e] = a[e]);
        return d
    }
    ;
    pc.findKey = Iba;
    pc.findValue = function(a, b, c) {
        return (b = Iba(a, b, c)) && a[b]
    }
    ;
    pc.forEach = function(a, b, c) {
        for (var d in a)
            b.call(c, a[d], d, a)
    }
    ;
    pc.get = function(a, b, c) {
        return a !== null && b in a ? a[b] : c
    }
    ;
    pc.getAllPropertyNames = function(a, b, c) {
        if (!a)
            return [];
        if (!Object.getOwnPropertyNames || !Object.getPrototypeOf)
            return Gba(a);
        for (var d = {}; a && (a !== Object.prototype || b) && (a !== Function.prototype || c); ) {
            for (var e = Object.getOwnPropertyNames(a), h = 0; h < e.length; h++)
                d[e[h]] = !0;
            a = Object.getPrototypeOf(a)
        }
        return Gba(d)
    }
    ;
    pc.getAnyKey = function(a) {
        for (var b in a)
            return b
    }
    ;
    pc.getAnyValue = function(a) {
        for (var b in a)
            return a[b]
    }
    ;
    pc.getCount = function(a) {
        var b = 0, c;
        for (c in a)
            b++;
        return b
    }
    ;
    pc.getKeys = Gba;
    pc.getSuperClass = function(a) {
        return (a = Object.getPrototypeOf(a.prototype)) && a.constructor
    }
    ;
    pc.getValueByKeys = function(a, b) {
        var c = Ya(b)
          , d = c ? b : arguments;
        for (c = c ? 0 : 1; c < d.length; c++) {
            if (a == null)
                return;
            a = a[d[c]]
        }
        return a
    }
    ;
    pc.getValues = function(a) {
        var b = [], c = 0, d;
        for (d in a)
            b[c++] = a[d];
        return b
    }
    ;
    pc.isEmpty = function(a) {
        for (var b in a)
            return !1;
        return !0
    }
    ;
    pc.isImmutableView = function(a) {
        return !!Object.isFrozen && Object.isFrozen(a)
    }
    ;
    pc.map = function(a, b, c) {
        var d = {}, e;
        for (e in a)
            d[e] = b.call(c, a[e], e, a);
        return d
    }
    ;
    pc.remove = function(a, b) {
        var c;
        (c = b in a) && delete a[b];
        return c
    }
    ;
    pc.set = function(a, b, c) {
        a[b] = c
    }
    ;
    pc.setIfUndefined = function(a, b, c) {
        return b in a ? a[b] : a[b] = c
    }
    ;
    pc.setWithReturnValueIfNotSet = function(a, b, c) {
        if (b in a)
            return a[b];
        c = c();
        return a[b] = c
    }
    ;
    pc.some = function(a, b, c) {
        for (var d in a)
            if (b.call(c, a[d], d, a))
                return !0;
        return !1
    }
    ;
    pc.transpose = function(a) {
        var b = {}, c;
        for (c in a)
            b[a[c]] = c;
        return b
    }
    ;
    pc.unsafeClone = Jba;
    var Nba = {}
      , rc = function(a) {
        this.privateDoNotAccessOrElseSafeStyleWrappedValue_ = a
    };
    rc.prototype.toString = function() {
        return this.privateDoNotAccessOrElseSafeStyleWrappedValue_.toString()
    }
    ;
    var Oba = function(a) {
        return a instanceof rc && a.constructor === rc ? a.privateDoNotAccessOrElseSafeStyleWrappedValue_ : "type_error:SafeStyle"
    }
      , tc = function(a) {
        return new rc(a,Nba)
    }
      , uc = function(a) {
        var b = "", c;
        for (c in a)
            if (Object.prototype.hasOwnProperty.call(a, c)) {
                if (!/^[-_a-zA-Z0-9]+$/.test(c))
                    throw Error("Name allows only [-_a-zA-Z0-9], got: " + c);
                var d = a[c];
                d != null && (d = Array.isArray(d) ? d.map(Pba).join(" ") : Pba(d),
                b += c + ":" + d + ";")
            }
        return b ? tc(b) : Qba
    }
      , Qba = tc("");
    function Pba(a) {
        if (a instanceof Fb)
            return "url(\"" + a.toString().replace(/</g, "%3c").replace(/[\\"]/g, "\\$&") + "\")";
        if (a instanceof tb)
            a = vb(a);
        else {
            a = String(a);
            var b = a.replace(Rba, "$1").replace(Rba, "$1").replace(Sba, "url");
            if (Tba.test(b)) {
                if (b = !Uba.test(a)) {
                    for (var c = b = !0, d = 0; d < a.length; d++) {
                        var e = a.charAt(d);
                        e == "'" && c ? b = !b : e == "\"" && b && (c = !c)
                    }
                    b = b && c && Vba(a)
                }
                a = b ? Wba(a) : "zClosurez"
            } else
                a = "zClosurez"
        }
        if (/[{;}]/.test(a))
            throw new Gaa("Value does not allow [{;}], got: %s.",[a]);
        return a
    }
    function Vba(a) {
        for (var b = !0, c = /^[-_a-zA-Z0-9]$/, d = 0; d < a.length; d++) {
            var e = a.charAt(d);
            if (e == "]") {
                if (b)
                    return !1;
                b = !0
            } else if (e == "[") {
                if (!b)
                    return !1;
                b = !1
            } else if (!b && !c.test(e))
                return !1
        }
        return b
    }
    var Tba = RegExp("^[-+,.\"'%_!#/ a-zA-Z0-9\\[\\]]+$")
      , Sba = RegExp("\\b(url\\([ \t\n]*)('[ -&(-\\[\\]-~]*'|\"[ !#-\\[\\]-~]*\"|[!#-&*-\\[\\]-~]*)([ \t\n]*\\))", "g")
      , Rba = RegExp("\\b(calc|cubic-bezier|fit-content|hsl|hsla|linear-gradient|matrix|minmax|radial-gradient|repeat|rgb|rgba|(rotate|scale|translate)(X|Y|Z|3d)?|steps|var)\\([-+*/0-9a-zA-Z.%#\\[\\], ]+\\)", "g")
      , Uba = /\/\*/;
    function Wba(a) {
        return a.replace(Sba, function(b, c, d, e) {
            var h = "";
            d = d.replace(/^(['"])(.*)\1$/, function(l, m, p) {
                h = m;
                return p
            });
            b = Ob(d).toString();
            return c + h + b + h + e
        })
    }
    ;var Xba = {}
      , vc = function(a) {
        this.privateDoNotAccessOrElseSafeHtmlWrappedValue_ = a
    };
    vc.prototype.toString = function() {
        return this.privateDoNotAccessOrElseSafeHtmlWrappedValue_.toString()
    }
    ;
    var wc = function(a) {
        return a instanceof vc && a.constructor === vc ? a.privateDoNotAccessOrElseSafeHtmlWrappedValue_ : "type_error:SafeHtml"
    }
      , xc = function(a) {
        var b = Raa();
        a = b ? b.createHTML(a) : a;
        return new vc(a,Xba)
    }
      , Yba = new vc(Na.trustedTypes && Na.trustedTypes.emptyHTML || "",Xba);
    function Zba(a) {
        return Oba(a)
    }
    ;function yc(a, b) {
        if (a.nodeType === 1) {
            var c = a.tagName;
            if (c === "SCRIPT" || c === "STYLE")
                throw Error("")
        }
        a.innerHTML = wc(b)
    }
    function Ac(a, b, c, d) {
        if (a.length === 0)
            throw Error("");
        a = a.map(function(h) {
            if (h instanceof rba)
                h = h.privateDoNotAccessOrElseWrappedAttributePrefix;
            else
                throw Error("");
            return h
        });
        var e = c.toLowerCase();
        if (a.every(function(h) {
            return e.indexOf(h) !== 0
        }))
            throw Error("Attribute \"" + c + "\" does not match any of the allowed prefixes.");
        b.setAttribute(c, d)
    }
    ;function Bc(a, b) {
        throw Error(b === void 0 ? "unexpected value " + a + "!" : b)
    }
    ;function Dc(a, b) {
        a.src = Ab(b).toString()
    }
    var $ba = {
        FORMATTED_HTML_CONTENT: 0,
        EMBEDDED_INTERNAL_CONTENT: 1,
        EMBEDDED_TRUSTED_EXTERNAL_CONTENT: 2,
        0: "FORMATTED_HTML_CONTENT",
        1: "EMBEDDED_INTERNAL_CONTENT",
        2: "EMBEDDED_TRUSTED_EXTERNAL_CONTENT"
    };
    function aca(a, b) {
        a.setAttribute("sandbox", "");
        for (var c = 0; c < b.length; c++)
            a.sandbox.supports && !a.sandbox.supports(b[c]) || a.sandbox.add(b[c])
    }
    var Fc = function(a, b) {
        var c = Error.call(this, a + " cannot be used with intent " + $ba[b]);
        this.message = c.message;
        "stack"in c && (this.stack = c.stack);
        this.type = a;
        this.intent = b;
        this.name = "TypeCannotBeUsedWithIntentError"
    };
    k(Fc, Error);
    function bca(a, b, c) {
        a.removeAttribute("srcdoc");
        switch (b) {
        case 0:
            if (c instanceof zb)
                throw new Fc("TrustedResourceUrl",0);
            aca(a, []);
            b = Ub(c);
            b !== void 0 && (a.src = b);
            break;
        case 1:
            if (!(c instanceof zb))
                throw new Fc(typeof c,1);
            aca(a, "allow-same-origin allow-scripts allow-forms allow-popups allow-popups-to-escape-sandbox allow-storage-access-by-user-activation".split(" "));
            Dc(a, c);
            break;
        case 2:
            if (c instanceof zb)
                throw new Fc("TrustedResourceUrl",2);
            aca(a, "allow-same-origin allow-scripts allow-forms allow-popups allow-popups-to-escape-sandbox allow-storage-access-by-user-activation".split(" "));
            b = Ub(c);
            b !== void 0 && (a.src = b);
            break;
        default:
            Bc(b);
        }
    }
    ;var cca = "alternate author bookmark canonical cite help icon license modulepreload next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");
    function dca(a, b) {
        if (b instanceof zb)
            a.href = Ab(b).toString(),
            a.rel = "stylesheet";
        else {
            if (cca.indexOf("stylesheet") === -1)
                throw Error("TrustedResourceUrl href attribute required with rel=\"stylesheet\"");
            b = Ub(b);
            b !== void 0 && (a.href = b,
            a.rel = "stylesheet")
        }
    }
    ;function Gc(a, b, c, d) {
        b = Ub(b);
        return b !== void 0 ? a.open(b, c, d) : null
    }
    function Ic(a) {
        var b, c;
        return (a = (c = (b = a.document).querySelector) == null ? void 0 : c.call(b, "script[nonce]")) ? a.nonce || a.getAttribute("nonce") || "" : ""
    }
    ;var Lc = function(a) {
        this.privateDoNotAccessOrElseWrappedScript = a
    };
    Lc.prototype.toString = function() {
        return this.privateDoNotAccessOrElseWrappedScript.toString()
    }
    ;
    function Mc(a) {
        var b = Raa();
        return new Lc(b ? b.createScript(a) : a)
    }
    function Nc(a) {
        if (a instanceof Lc)
            return a.privateDoNotAccessOrElseWrappedScript;
        throw Error("")
    }
    ;function eca(a) {
        var b = Ic(a.ownerDocument && a.ownerDocument.defaultView || window);
        b && a.setAttribute("nonce", b)
    }
    function Oc(a, b) {
        a.textContent = Nc(b);
        eca(a)
    }
    function Rc(a, b) {
        a.src = Ab(b);
        eca(a)
    }
    ;var fca = function(a, b) {
        a.__closure__error__context__984382 || (a.__closure__error__context__984382 = {});
        a.__closure__error__context__984382.severity = b
    };
    var hca = function(a) {
        var b = Pa("window.location.href");
        a == null && (a = "Unknown Error of type \"null/undefined\"");
        if (typeof a === "string")
            return {
                message: a,
                name: "Unknown error",
                lineNumber: "Not available",
                fileName: b,
                stack: "Not available"
            };
        var c = !1;
        try {
            var d = a.lineNumber || a.line || "Not available"
        } catch (l) {
            d = "Not available",
            c = !0
        }
        try {
            var e = a.fileName || a.filename || a.sourceURL || Na.$googDebugFname || b
        } catch (l) {
            e = "Not available",
            c = !0
        }
        b = gca(a);
        if (!(!c && a.lineNumber && a.fileName && a.stack && a.message && a.name)) {
            c = a.message;
            if (c == null) {
                if (a.constructor && a.constructor instanceof Function) {
                    if (a.constructor.name)
                        c = a.constructor.name;
                    else if (c = a.constructor,
                    Sc[c])
                        c = Sc[c];
                    else {
                        c = String(c);
                        if (!Sc[c]) {
                            var h = /function\s+([^\(]+)/m.exec(c);
                            Sc[c] = h ? h[1] : "[Anonymous]"
                        }
                        c = Sc[c]
                    }
                    c = "Unknown Error of type \"" + c + "\""
                } else
                    c = "Unknown Error of unknown type";
                typeof a.toString === "function" && Object.prototype.toString !== a.toString && (c += ": " + a.toString())
            }
            return {
                message: c,
                name: a.name || "UnknownError",
                lineNumber: d,
                fileName: e,
                stack: b || "Not available"
            }
        }
        return {
            message: a.message,
            name: a.name,
            lineNumber: a.lineNumber,
            fileName: a.fileName,
            stack: b
        }
    }
      , gca = function(a, b) {
        b || (b = {});
        b[ica(a)] = !0;
        var c = a.stack || "";
        (a = a.cause) && !b[ica(a)] && (c += "\nCaused by: ",
        a.stack && a.stack.indexOf(a.toString()) == 0 || (c += typeof a === "string" ? a : a.message + "\n"),
        c += gca(a, b));
        return c
    }
      , ica = function(a) {
        var b = "";
        typeof a.toString === "function" && (b = "" + a);
        return b + a.stack
    }
      , Sc = {};
    function Tc(a, b) {
        b = Ub(b);
        b !== void 0 && (a.href = b)
    }
    ;var jca = function(a, b) {
        for (var c = a.split("%s"), d = "", e = Array.prototype.slice.call(arguments, 1); e.length && c.length > 1; )
            d += c.shift() + e.shift();
        return d + c.join("%s")
    }
      , Uc = function(a) {
        return encodeURIComponent(String(a))
    }
      , Wc = function(a) {
        return decodeURIComponent(a.replace(/\+/g, " "))
    }
      , Xc = function(a) {
        Oaa.test(a) && (a.indexOf("&") != -1 && (a = a.replace(Iaa, "&amp;")),
        a.indexOf("<") != -1 && (a = a.replace(Jaa, "&lt;")),
        a.indexOf(">") != -1 && (a = a.replace(Kaa, "&gt;")),
        a.indexOf("\"") != -1 && (a = a.replace(Laa, "&quot;")),
        a.indexOf("'") != -1 && (a = a.replace(Maa, "&#39;")),
        a.indexOf("\0") != -1 && (a = a.replace(Naa, "&#0;")));
        return a
    }
      , lca = function(a) {
        var b = {
            "&amp;": "&",
            "&lt;": "<",
            "&gt;": ">",
            "&quot;": "\""
        };
        var c = Na.document.createElement("div");
        return a.replace(kca, function(d, e) {
            var h = b[d];
            if (h)
                return h;
            e.charAt(0) == "#" && (e = Number("0" + e.slice(1)),
            isNaN(e) || (h = String.fromCharCode(e)));
            h || (yc(c, xc(d + " ")),
            h = c.firstChild.nodeValue.slice(0, -1));
            return b[d] = h
        })
    }
      , mca = function(a) {
        return a.replace(/&([^;]+);/g, function(b, c) {
            switch (c) {
            case "amp":
                return "&";
            case "lt":
                return "<";
            case "gt":
                return ">";
            case "quot":
                return "\"";
            default:
                return c.charAt(0) != "#" || (c = Number("0" + c.slice(1)),
                isNaN(c)) ? b : String.fromCharCode(c);
            }
        })
    }
      , kca = /&([^;\s<&]+);?/g
      , nca = function(a) {
        return String(a).replace(/([-()\[\]{}+?*.$\^|,:#<!\\])/g, "\\$1").replace(/\x08/g, "\\x08")
    }
      , Zc = String.prototype.repeat ? function(a, b) {
        return a.repeat(b)
    }
    : function(a, b) {
        return Array(b + 1).join(a)
    }
      , $c = function(a, b) {
        if (!Number.isFinite(a))
            return String(a);
        a = String(a);
        var c = a.indexOf(".");
        c === -1 && (c = a.length);
        var d = a[0] === "-" ? "-" : "";
        d && (a = a.substring(1));
        return d + Zc("0", Math.max(0, b - c)) + a
    }
      , ad = function() {
        return Math.floor(Math.random() * 2147483648).toString(36) + Math.abs(Math.floor(Math.random() * 2147483648) ^ eb()).toString(36)
    }
      , bd = function(a) {
        for (var b = 0, c = 0; c < a.length; ++c)
            b = 31 * b + a.charCodeAt(c) >>> 0;
        return b
    }
      , cd = function(a) {
        return String(a).replace(/\-([a-z])/g, function(b, c) {
            return c.toUpperCase()
        })
    }
      , dd = function(a) {
        return String(a).replace(/([A-Z])/g, "-$1").toLowerCase()
    }
      , oca = function(a) {
        return a.replace(RegExp("(^|[\\s]+)([a-z])", "g"), function(b, c, d) {
            return c + d.toUpperCase()
        })
    }
      , pca = function(a) {
        var b = 1;
        a = a.split(":");
        for (var c = []; b > 0 && a.length; )
            c.push(a.shift()),
            b--;
        a.length && c.push(a.join(":"));
        return c
    };
    var qca = function(a, b, c, d, e, h, l) {
        var m = "";
        a && (m += a + ":");
        c && (m += "//",
        b && (m += b + "@"),
        m += c,
        d && (m += ":" + d));
        e && (m += e);
        h && (m += "?" + h);
        l && (m += "#" + l);
        return m
    }
      , rca = RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$")
      , ed = function(a) {
        return a.match(rca)
    }
      , sca = function(a) {
        return a ? decodeURI(a) : a
    }
      , tca = function(a) {
        a = ed(a)[1] || null;
        !a && Na.self && Na.self.location && (a = Na.self.location.protocol.slice(0, -1));
        return a ? a.toLowerCase() : ""
    }
      , fd = function(a) {
        return sca(ed(a)[3] || null)
    }
      , gd = function(a) {
        return sca(ed(a)[5] || null)
    }
      , uca = function(a) {
        a = ed(a);
        return qca(a[1], a[2], a[3], a[4])
    }
      , hd = function(a) {
        a = ed(a);
        return qca(a[1], null, a[3], a[4])
    }
      , jd = function(a) {
        a = ed(a);
        return qca(null, null, null, null, a[5], a[6], a[7])
    }
      , kd = function(a) {
        var b = a.indexOf("#");
        return b < 0 ? a : a.slice(0, b)
    }
      , ld = function(a, b) {
        a = ed(a);
        b = ed(b);
        return a[3] == b[3] && a[1] == b[1] && a[4] == b[4]
    }
      , vca = function(a, b) {
        if (a) {
            a = a.split("&");
            for (var c = 0; c < a.length; c++) {
                var d = a[c].indexOf("=")
                  , e = null;
                if (d >= 0) {
                    var h = a[c].substring(0, d);
                    e = a[c].substring(d + 1)
                } else
                    h = a[c];
                b(h, e ? Wc(e) : "")
            }
        }
    }
      , wca = function(a) {
        var b = a.indexOf("#");
        b < 0 && (b = a.length);
        var c = a.indexOf("?");
        if (c < 0 || c > b) {
            c = b;
            var d = ""
        } else
            d = a.substring(c + 1, b);
        return [a.slice(0, c), d, a.slice(b)]
    }
      , xca = function(a, b) {
        return b ? a ? a + "&" + b : b : a
    }
      , yca = function(a, b) {
        if (!b)
            return a;
        a = wca(a);
        a[1] = xca(a[1], b);
        return a[0] + (a[1] ? "?" + a[1] : "") + a[2]
    }
      , zca = function(a, b, c) {
        if (Array.isArray(b))
            for (var d = 0; d < b.length; d++)
                zca(a, String(b[d]), c);
        else
            b != null && c.push(a + (b === "" ? "" : "=" + Uc(b)))
    }
      , Aca = function(a, b) {
        var c = [];
        for (b = b || 0; b < a.length; b += 2)
            zca(a[b], a[b + 1], c);
        return c.join("&")
    }
      , nd = function(a) {
        var b = [], c;
        for (c in a)
            zca(c, a[c], b);
        return b.join("&")
    }
      , Bca = function(a, b) {
        var c = arguments.length == 2 ? Aca(arguments[1], 0) : Aca(arguments, 1);
        return yca(a, c)
    }
      , pd = function(a, b) {
        b = nd(b);
        return yca(a, b)
    }
      , qd = function(a, b, c) {
        c = c != null ? "=" + Uc(c) : "";
        return yca(a, b + c)
    }
      , Cca = function(a, b, c, d) {
        for (var e = c.length; (b = a.indexOf(c, b)) >= 0 && b < d; ) {
            var h = a.charCodeAt(b - 1);
            if (h == 38 || h == 63)
                if (h = a.charCodeAt(b + e),
                !h || h == 61 || h == 38 || h == 35)
                    return b;
            b += e + 1
        }
        return -1
    }
      , Dca = /#|$/
      , rd = function(a, b) {
        var c = a.search(Dca)
          , d = Cca(a, 0, b, c);
        if (d < 0)
            return null;
        var e = a.indexOf("&", d);
        if (e < 0 || e > c)
            e = c;
        d += b.length + 1;
        return Wc(a.slice(d, e !== -1 ? e : 0))
    }
      , Eca = /[?&]($|#)/
      , sd = function(a, b) {
        for (var c = a.search(Dca), d = 0, e, h = []; (e = Cca(a, d, b, c)) >= 0; )
            h.push(a.substring(d, e)),
            d = Math.min(a.indexOf("&", e) + 1 || c, c);
        h.push(a.slice(d));
        return h.join("").replace(Eca, "$1")
    }
      , wd = function(a, b, c) {
        return qd(sd(a, b), b, c)
    }
      , Fca = function(a) {
        var b = wca(window.location.href)
          , c = b[1]
          , d = [];
        c && c.split("&").forEach(function(e) {
            var h = e.indexOf("=");
            h = h >= 0 ? e.slice(0, h) : e;
            a.hasOwnProperty(h) || d.push(e)
        });
        b[1] = xca(d.join("&"), nd(a));
        return b[0] + (b[1] ? "?" + b[1] : "") + b[2]
    };
    function xd() {
        throw Error("Invalid UTF8")
    }
    function Gca(a, b) {
        b = String.fromCharCode.apply(null, b);
        return a == null ? b : a + b
    }
    var yd = void 0, Hca, Ica = typeof TextDecoder !== "undefined", Jca, Kca = typeof String.prototype.isWellFormed === "function", Lca = typeof TextEncoder !== "undefined";
    function Mca(a) {
        var b = !1;
        b = b === void 0 ? !1 : b;
        if (Lca) {
            if (b && (Kca ? !a.isWellFormed() : /(?:[^\uD800-\uDBFF]|^)[\uDC00-\uDFFF]|[\uD800-\uDBFF](?![\uDC00-\uDFFF])/.test(a)))
                throw Error("Found an unpaired surrogate");
            a = (Jca || (Jca = new TextEncoder)).encode(a)
        } else {
            for (var c = 0, d = new Uint8Array(3 * a.length), e = 0; e < a.length; e++) {
                var h = a.charCodeAt(e);
                if (h < 128)
                    d[c++] = h;
                else {
                    if (h < 2048)
                        d[c++] = h >> 6 | 192;
                    else {
                        if (h >= 55296 && h <= 57343) {
                            if (h <= 56319 && e < a.length) {
                                var l = a.charCodeAt(++e);
                                if (l >= 56320 && l <= 57343) {
                                    h = (h - 55296) * 1024 + l - 56320 + 65536;
                                    d[c++] = h >> 18 | 240;
                                    d[c++] = h >> 12 & 63 | 128;
                                    d[c++] = h >> 6 & 63 | 128;
                                    d[c++] = h & 63 | 128;
                                    continue
                                } else
                                    e--
                            }
                            if (b)
                                throw Error("Found an unpaired surrogate");
                            h = 65533
                        }
                        d[c++] = h >> 12 | 224;
                        d[c++] = h >> 6 & 63 | 128
                    }
                    d[c++] = h & 63 | 128
                }
            }
            a = c === d.length ? d : d.subarray(0, c)
        }
        return a
    }
    ;function zd(a) {
        Na.setTimeout(function() {
            throw a
        }, 0)
    }
    ;var Ad = function(a) {
        for (var b = [], c = 0, d = 0; d < a.length; d++) {
            var e = a.charCodeAt(d);
            e < 128 ? b[c++] = e : (e < 2048 ? b[c++] = e >> 6 | 192 : ((e & 64512) == 55296 && d + 1 < a.length && (a.charCodeAt(d + 1) & 64512) == 56320 ? (e = 65536 + ((e & 1023) << 10) + (a.charCodeAt(++d) & 1023),
            b[c++] = e >> 18 | 240,
            b[c++] = e >> 12 & 63 | 128) : b[c++] = e >> 12 | 224,
            b[c++] = e >> 6 & 63 | 128),
            b[c++] = e & 63 | 128)
        }
        return b
    }
      , Nca = function(a) {
        for (var b = [], c = 0, d = 0; c < a.length; ) {
            var e = a[c++];
            if (e < 128)
                b[d++] = String.fromCharCode(e);
            else if (e > 191 && e < 224) {
                var h = a[c++];
                b[d++] = String.fromCharCode((e & 31) << 6 | h & 63)
            } else if (e > 239 && e < 365) {
                h = a[c++];
                var l = a[c++]
                  , m = a[c++];
                e = ((e & 7) << 18 | (h & 63) << 12 | (l & 63) << 6 | m & 63) - 65536;
                b[d++] = String.fromCharCode(55296 + (e >> 10));
                b[d++] = String.fromCharCode(56320 + (e & 1023))
            } else
                h = a[c++],
                l = a[c++],
                b[d++] = String.fromCharCode((e & 15) << 12 | (h & 63) << 6 | l & 63)
        }
        return b.join("")
    };
    var Bd = Qa(1, !1)
      , Cd = Qa(610401301, !1);
    Qa(899588437, !1);
    var Oca = Qa(188588736, !0)
      , Pca = Qa(641353869, Bd)
      , Qca = Qa(644029907, !1)
      , Rca = Qa(1822726157, Bd)
      , Sca = Qa(645172343, Bd);
    Qa(651175828, !1);
    var Tca = Qa(653718497, Bd);
    Qa(2147483644, !1);
    Qa(2147483645, !1);
    Qa(2147483646, Bd);
    Qa(2147483647, !0);
    function Dd() {
        var a = Na.navigator;
        return a && (a = a.userAgent) ? a : ""
    }
    var Ed, Uca = Na.navigator;
    Ed = Uca ? Uca.userAgentData || null : null;
    function Fd(a) {
        return Cd ? Ed ? Ed.brands.some(function(b) {
            return (b = b.brand) && pb(b, a)
        }) : !1 : !1
    }
    function Hd(a) {
        return pb(Dd(), a)
    }
    ;function Id() {
        return Cd ? !!Ed && Ed.brands.length > 0 : !1
    }
    function Jd() {
        return Id() ? !1 : Hd("Opera")
    }
    function Vca() {
        return Id() ? !1 : Hd("Trident") || Hd("MSIE")
    }
    function Wca() {
        return Id() ? Fd("Microsoft Edge") : Hd("Edg/")
    }
    function Kd() {
        return Hd("Firefox") || Hd("FxiOS")
    }
    function Ld() {
        return Hd("Safari") && !(Md() || (Id() ? 0 : Hd("Coast")) || Jd() || (Id() ? 0 : Hd("Edge")) || Wca() || (Id() ? Fd("Opera") : Hd("OPR")) || Kd() || Hd("Silk") || Hd("Android"))
    }
    function Md() {
        return Id() ? Fd("Chromium") : (Hd("Chrome") || Hd("CriOS")) && !(Id() ? 0 : Hd("Edge")) || Hd("Silk")
    }
    function Xca() {
        return Hd("Android") && !(Md() || Kd() || Jd() || Hd("Silk"))
    }
    function Yca(a) {
        var b = {};
        a.forEach(function(c) {
            b[c[0]] = c[1]
        });
        return function(c) {
            return b[c.find(function(d) {
                return d in b
            })] || ""
        }
    }
    function Zca(a) {
        var b = Dd();
        if (a === "Internet Explorer") {
            if (Vca()) {
                if ((a = /rv: *([\d\.]*)/.exec(b)) && a[1])
                    b = a[1];
                else {
                    a = "";
                    var c = /MSIE +([\d\.]+)/.exec(b);
                    if (c && c[1])
                        if (b = /Trident\/(\d.\d)/.exec(b),
                        c[1] == "7.0") {
                            if (b && b[1])
                                switch (b[1]) {
                                case "4.0":
                                    a = "8.0";
                                    break;
                                case "5.0":
                                    a = "9.0";
                                    break;
                                case "6.0":
                                    a = "10.0";
                                    break;
                                case "7.0":
                                    a = "11.0";
                                }
                            else
                                a = "7.0";
                        } else
                            a = c[1];
                    b = a
                }
            } else
                b = "";
            return b
        }
        var d = RegExp("([A-Z][\\w ]+)/([^\\s]+)\\s*(?:\\((.*?)\\))?", "g");
        c = [];
        for (var e; e = d.exec(b); )
            c.push([e[1], e[2], e[3] || void 0]);
        b = Yca(c);
        switch (a) {
        case "Opera":
            if (Jd())
                return b(["Version", "Opera"]);
            if (Id() ? Fd("Opera") : Hd("OPR"))
                return b(["OPR"]);
            break;
        case "Microsoft Edge":
            if (Id() ? 0 : Hd("Edge"))
                return b(["Edge"]);
            if (Wca())
                return b(["Edg"]);
            break;
        case "Chromium":
            if (Md())
                return b(["Chrome", "CriOS", "HeadlessChrome"]);
        }
        return a === "Firefox" && Kd() || a === "Safari" && Ld() || a === "Android Browser" && Xca() || a === "Silk" && Hd("Silk") ? (b = c[2]) && b[1] || "" : ""
    }
    function $ca(a) {
        if (Id() && a !== "Silk") {
            var b = Ed.brands.find(function(c) {
                return c.brand === a
            });
            if (!b || !b.version)
                return NaN;
            b = b.version.split(".")
        } else {
            b = Zca(a);
            if (b === "")
                return NaN;
            b = b.split(".")
        }
        return b.length === 0 ? NaN : Number(b[0])
    }
    ;function Nd() {
        return Cd ? !!Ed && !!Ed.platform : !1
    }
    function ada() {
        return Hd("iPhone") && !Hd("iPod") && !Hd("iPad")
    }
    function Sd() {
        return ada() || Hd("iPad") || Hd("iPod")
    }
    function bda() {
        return Nd() ? Ed.platform === "macOS" : Hd("Macintosh")
    }
    ;var Td = function(a) {
        Td[" "](a);
        return a
    };
    Td[" "] = function() {}
    ;
    var Ud = function(a, b) {
        try {
            return Td(a[b]),
            !0
        } catch (c) {}
        return !1
    }
      , cda = function(a, b, c, d) {
        d = d ? d(b) : b;
        return Object.prototype.hasOwnProperty.call(a, d) ? a[d] : a[d] = c(b)
    };
    var Vd = function() {
        return Na.navigator || null
    }, dda = Jd(), Wd = Vca(), Xd = Hd("Edge"), eda = Xd || Wd, Yd = Hd("Gecko") && !(qb(Dd(), "WebKit") && !Hd("Edge")) && !(Hd("Trident") || Hd("MSIE")) && !Hd("Edge"), Zd = qb(Dd(), "WebKit") && !Hd("Edge"), fda = Zd && Hd("Mobile"), $d = bda(), gda = Nd() ? Ed.platform === "Windows" : Hd("Windows"), hda = (Nd() ? Ed.platform === "Linux" : Hd("Linux")) || (Nd() ? Ed.platform === "Chrome OS" : Hd("CrOS")), ida = Nd() ? Ed.platform === "Android" : Hd("Android"), jda = ada(), kda = Hd("iPad"), lda = Hd("iPod"), mda = Sd(), nda = qb(Dd(), "KaiOS"), oda = function() {
        var a = Na.document;
        return a ? a.documentMode : void 0
    }, pda;
    a: {
        var qda = ""
          , rda = function() {
            var a = Dd();
            if (Yd)
                return /rv:([^\);]+)(\)|;)/.exec(a);
            if (Xd)
                return /Edge\/([\d\.]+)/.exec(a);
            if (Wd)
                return /\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);
            if (Zd)
                return /WebKit\/(\S+)/.exec(a);
            if (dda)
                return /(?:Version)[ \/]?(\S+)/.exec(a)
        }();
        rda && (qda = rda ? rda[1] : "");
        if (Wd) {
            var sda = oda();
            if (sda != null && sda > parseFloat(qda)) {
                pda = String(sda);
                break a
            }
        }
        pda = qda
    }
    var tda = pda, uda = {}, vda = function(a) {
        return cda(uda, a, function() {
            return rb(tda, a) >= 0
        })
    }, wda;
    if (Na.document && Wd) {
        var xda = oda();
        wda = xda ? xda : parseInt(tda, 10) || void 0
    } else
        wda = void 0;
    var yda = wda;
    var be = Kd()
      , zda = ada() || Hd("iPod")
      , Ada = Hd("iPad")
      , Bda = Xca()
      , ce = Md()
      , Cda = Ld() && !Sd();
    var Dda = {}
      , de = null
      , Eda = Yd || Zd || typeof Na.btoa == "function"
      , ee = function(a, b) {
        b === void 0 && (b = 0);
        Fda();
        b = Dda[b];
        for (var c = Array(Math.floor(a.length / 3)), d = b[64] || "", e = 0, h = 0; e < a.length - 2; e += 3) {
            var l = a[e]
              , m = a[e + 1]
              , p = a[e + 2]
              , q = b[l >> 2];
            l = b[(l & 3) << 4 | m >> 4];
            m = b[(m & 15) << 2 | p >> 6];
            p = b[p & 63];
            c[h++] = "" + q + l + m + p
        }
        q = 0;
        p = d;
        switch (a.length - e) {
        case 2:
            q = a[e + 1],
            p = b[(q & 15) << 2] || d;
        case 1:
            a = a[e],
            c[h] = "" + b[a >> 2] + b[(a & 3) << 4 | q >> 4] + p + d;
        }
        return c.join("")
    }
      , fe = function(a) {
        var b = [];
        Gda(a, function(c) {
            b.push(c)
        });
        return b
    }
      , ge = function(a) {
        var b = a.length
          , c = b * 3 / 4;
        c % 3 ? c = Math.floor(c) : pb("=.", a[b - 1]) && (c = pb("=.", a[b - 2]) ? c - 2 : c - 1);
        var d = new Uint8Array(c)
          , e = 0;
        Gda(a, function(h) {
            d[e++] = h
        });
        return e !== c ? d.subarray(0, e) : d
    }
      , Gda = function(a, b) {
        function c(p) {
            for (; d < a.length; ) {
                var q = a.charAt(d++)
                  , r = de[q];
                if (r != null)
                    return r;
                if (!nb(q))
                    throw Error("Unknown base64 encoding at char: " + q)
            }
            return p
        }
        Fda();
        for (var d = 0; ; ) {
            var e = c(-1)
              , h = c(0)
              , l = c(64)
              , m = c(64);
            if (m === 64 && e === -1)
                break;
            b(e << 2 | h >> 4);
            l != 64 && (b(h << 4 & 240 | l >> 2),
            m != 64 && b(l << 6 & 192 | m))
        }
    }
      , Fda = function() {
        if (!de) {
            de = {};
            for (var a = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""), b = ["+/=", "+/", "-_=", "-_.", "-_"], c = 0; c < 5; c++) {
                var d = a.concat(b[c].split(""));
                Dda[c] = d;
                for (var e = 0; e < d.length; e++) {
                    var h = d[e];
                    de[h] === void 0 && (de[h] = e)
                }
            }
        }
    };
    var Hda = typeof Uint8Array !== "undefined"
      , Ida = !Wd && typeof btoa === "function";
    function Jda(a) {
        if (!Ida)
            return ee(a);
        for (var b = "", c = 0, d = a.length - 10240; c < d; )
            b += String.fromCharCode.apply(null, a.subarray(c, c += 10240));
        b += String.fromCharCode.apply(null, c ? a.subarray(c) : a);
        return btoa(b)
    }
    var Kda = /[-_.]/g
      , Lda = {
        "-": "+",
        _: "/",
        ".": "="
    };
    function Mda(a) {
        return Lda[a] || ""
    }
    function Nda(a) {
        if (!Ida)
            return ge(a);
        Kda.test(a) && (a = a.replace(Kda, Mda));
        a = atob(a);
        for (var b = new Uint8Array(a.length), c = 0; c < a.length; c++)
            b[c] = a.charCodeAt(c);
        return b
    }
    function he(a) {
        return Hda && a != null && a instanceof Uint8Array
    }
    var ie = {};
    var Oda;
    function Pda(a) {
        if (a !== ie)
            throw Error("illegal external caller")
    }
    var je = function(a, b) {
        Pda(b);
        this.JSC$6388_value_ = a;
        if (a != null && a.length === 0)
            throw Error("ByteString should be constructed with non-empty values")
    }
      , ke = function() {
        return Oda || (Oda = new je(null,ie))
    };
    je.prototype.isEmpty = function() {
        return this.JSC$6388_value_ == null
    }
    ;
    je.prototype.sizeBytes = function() {
        var a = le(this);
        return a ? a.length : 0
    }
    ;
    var Qda = function(a) {
        a = a.JSC$6388_value_ || "";
        return typeof a === "string" ? a : new Uint8Array(a)
    }
      , le = function(a) {
        Pda(ie);
        var b = a.JSC$6388_value_;
        b = b == null || he(b) ? b : typeof b === "string" ? Nda(b) : null;
        return b == null ? b : a.JSC$6388_value_ = b
    };
    var Rda;
    function Sda() {
        var a = Error();
        fca(a, "incident");
        zd(a)
    }
    function me(a) {
        a = Error(a);
        fca(a, "warning");
        return a
    }
    ;function Tda() {
        return typeof BigInt === "function"
    }
    ;function ne(a) {
        return Array.prototype.slice.call(a)
    }
    ;var oe = typeof Symbol === "function" && typeof Symbol() === "symbol";
    function pe(a) {
        return typeof Symbol === "function" && typeof Symbol() === "symbol" ? Symbol() : a
    }
    var qe = pe()
      , Uda = pe("0di")
      , Vda = pe("2ex")
      , Wda = pe("0dg")
      , re = pe("1oa");
    var Xda = oe ? function(a, b) {
        a[qe] |= b
    }
    : function(a, b) {
        a.internalArrayState !== void 0 ? a.internalArrayState |= b : Object.defineProperties(a, {
            internalArrayState: {
                value: b,
                configurable: !0,
                writable: !0,
                enumerable: !1
            }
        })
    }
      , se = oe ? function(a, b) {
        a[qe] &= ~b
    }
    : function(a, b) {
        a.internalArrayState !== void 0 && (a.internalArrayState &= ~b)
    }
      , te = oe ? function(a) {
        return a[qe] | 0
    }
    : function(a) {
        return a.internalArrayState | 0
    }
      , ue = oe ? function(a) {
        return a[qe]
    }
    : function(a) {
        return a.internalArrayState
    }
      , ve = oe ? function(a, b) {
        a[qe] = b
    }
    : function(a, b) {
        a.internalArrayState !== void 0 ? a.internalArrayState = b : Object.defineProperties(a, {
            internalArrayState: {
                value: b,
                configurable: !0,
                writable: !0,
                enumerable: !1
            }
        })
    }
    ;
    function we(a) {
        Xda(a, 34);
        return a
    }
    function Yda(a) {
        Xda(a, 32);
        return a
    }
    function Zda(a, b) {
        ve(b, (a | 0) & -14591)
    }
    function $da(a, b) {
        ve(b, (a | 34) & -14557)
    }
    ;var xe = {}
      , aea = {};
    function bea(a) {
        return !(!a || typeof a !== "object" || a.mapPrototypeMarker !== aea)
    }
    function cea(a) {
        return a !== null && typeof a === "object" && !Array.isArray(a) && a.constructor === Object
    }
    function ye(a, b, c) {
        if (a != null)
            if (typeof a === "string")
                a = a ? new je(a,ie) : ke();
            else if (a.constructor !== je)
                if (he(a))
                    a = a.length ? new je(c ? a : new Uint8Array(a),ie) : ke();
                else {
                    if (!b)
                        throw Error();
                    a = void 0
                }
        return a
    }
    function ze(a, b, c) {
        if (!Array.isArray(a) || a.length)
            return !1;
        var d = te(a);
        if (d & 1)
            return !0;
        if (!(b && (Array.isArray(b) ? b.includes(c) : b.has(c))))
            return !1;
        ve(a, d | 1);
        return !0
    }
    var dea, eea = [];
    ve(eea, 55);
    dea = Object.freeze(eea);
    function Ae(a) {
        if (a & 2)
            throw Error()
    }
    var Ce = function(a, b, c) {
        this.idx_ = 0;
        this.arr_ = a;
        this.mapper = b;
        this.thisArg = c
    };
    Ce.prototype.next = function() {
        if (this.idx_ < this.arr_.length) {
            var a = this.arr_[this.idx_++];
            return {
                done: !1,
                value: this.mapper ? this.mapper.call(this.thisArg, a) : a
            }
        }
        return {
            done: !0,
            value: void 0
        }
    }
    ;
    Ce.prototype[Symbol.iterator] = function() {
        return new Ce(this.arr_,this.mapper,this.thisArg)
    }
    ;
    var De;
    function fea(a, b) {
        (b = De ? b[De] : void 0) && (a[De] = ne(b))
    }
    var gea, hea = Object.freeze({});
    Object.freeze({});
    var iea = Object.freeze({});
    var jea = typeof Uint8Array.prototype.slice === "function", Ee = 0, Fe = 0, kea;
    function lea(a) {
        var b = a >>> 0;
        Ee = b;
        Fe = (a - b) / 4294967296 >>> 0
    }
    function Ge(a) {
        if (a < 0) {
            lea(0 - a);
            var b = g(mea(Ee, Fe));
            a = b.next().value;
            b = b.next().value;
            Ee = a >>> 0;
            Fe = b >>> 0
        } else
            lea(a)
    }
    function He(a, b) {
        var c = b & 2147483648;
        c && (a = ~a + 1 >>> 0,
        b = ~b >>> 0,
        a == 0 && (b = b + 1 >>> 0));
        a = b * 4294967296 + (a >>> 0);
        return c ? -a : a
    }
    function Ie(a, b) {
        b >>>= 0;
        a >>>= 0;
        if (b <= 2097151)
            var c = "" + (4294967296 * b + a);
        else
            Tda() ? c = "" + (BigInt(b) << BigInt(32) | BigInt(a)) : (c = (a >>> 24 | b << 8) & 16777215,
            b = b >> 16 & 65535,
            a = (a & 16777215) + c * 6777216 + b * 6710656,
            c += b * 8147497,
            b *= 2,
            a >= 1E7 && (c += a / 1E7 >>> 0,
            a %= 1E7),
            c >= 1E7 && (b += c / 1E7 >>> 0,
            c %= 1E7),
            c = b + nea(c) + nea(a));
        return c
    }
    function nea(a) {
        a = String(a);
        return "0000000".slice(a.length) + a
    }
    function oea(a, b) {
        b & 2147483648 ? Tda() ? a = "" + (BigInt(b | 0) << BigInt(32) | BigInt(a >>> 0)) : (b = g(mea(a, b)),
        a = b.next().value,
        b = b.next().value,
        a = "-" + Ie(a, b)) : a = Ie(a, b);
        return a
    }
    function Je(a) {
        if (a.length < 16)
            Ge(Number(a));
        else if (Tda())
            a = BigInt(a),
            Ee = Number(a & BigInt(4294967295)) >>> 0,
            Fe = Number(a >> BigInt(32) & BigInt(4294967295));
        else {
            var b = +(a[0] === "-");
            Fe = Ee = 0;
            for (var c = a.length, d = 0 + b, e = (c - b) % 6 + b; e <= c; d = e,
            e += 6)
                d = Number(a.slice(d, e)),
                Fe *= 1E6,
                Ee = Ee * 1E6 + d,
                Ee >= 4294967296 && (Fe += Math.trunc(Ee / 4294967296),
                Fe >>>= 0,
                Ee >>>= 0);
            b && (b = g(mea(Ee, Fe)),
            a = b.next().value,
            b = b.next().value,
            Ee = a,
            Fe = b)
        }
    }
    function mea(a, b) {
        b = ~b;
        a ? a = ~a + 1 : b += 1;
        return [a, b]
    }
    ;function Ke(a) {
        if (a != null && typeof a !== "number")
            throw Error("Value of float/double field must be a number, found " + typeof a + ": " + a);
        return a
    }
    function pea(a) {
        if (a == null || typeof a === "number")
            return a;
        if (a === "NaN" || a === "Infinity" || a === "-Infinity")
            return Number(a)
    }
    function qea(a) {
        if (a != null && typeof a !== "boolean")
            throw Error("Expected boolean but got " + Xa(a) + ": " + a);
        return a
    }
    function rea(a) {
        if (a == null || typeof a === "boolean")
            return a;
        if (typeof a === "number")
            return !!a
    }
    var sea = /^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;
    function Le(a) {
        var b = typeof a;
        return b === "number" ? Number.isFinite(a) : b !== "string" ? !1 : sea.test(a)
    }
    function Me(a) {
        if (!Number.isFinite(a))
            throw me("enum");
        return a | 0
    }
    function Ne(a) {
        return a == null ? a : Number.isFinite(a) ? a | 0 : void 0
    }
    function tea(a) {
        if (typeof a !== "number")
            throw me("int32");
        if (!Number.isFinite(a))
            throw me("int32");
        return a | 0
    }
    function Oe(a) {
        return a == null ? a : tea(a)
    }
    function Pe(a) {
        if (a == null)
            return a;
        if (typeof a === "string") {
            if (!a)
                return;
            a = +a
        }
        if (typeof a === "number")
            return Number.isFinite(a) ? a | 0 : void 0
    }
    function uea(a) {
        if (a == null)
            return a;
        if (typeof a === "string") {
            if (!a)
                return;
            a = +a
        }
        if (typeof a === "number")
            return Number.isFinite(a) ? a >>> 0 : void 0
    }
    function vea(a, b) {
        b = !!b;
        if (!Le(a))
            throw me("int64");
        return typeof a === "string" ? Qe(a) : b ? wea(a) : Re(a)
    }
    function Se(a) {
        return a == null ? a : vea(a)
    }
    function xea(a) {
        return a[0] === "-" ? !1 : a.length < 20 ? !0 : a.length === 20 && Number(a.substring(0, 6)) < 184467
    }
    function yea(a) {
        return a[0] === "-" ? a.length < 20 ? !0 : a.length === 20 && Number(a.substring(0, 7)) > -922337 : a.length < 19 ? !0 : a.length === 19 && Number(a.substring(0, 6)) < 922337
    }
    function zea(a) {
        if (a < 0) {
            Ge(a);
            var b = Ie(Ee, Fe);
            a = Number(b);
            return Number.isSafeInteger(a) ? a : b
        }
        if (xea(String(a)))
            return a;
        Ge(a);
        return Fe * 4294967296 + (Ee >>> 0)
    }
    function Re(a) {
        a = Math.trunc(a);
        Number.isSafeInteger(a) || (Ge(a),
        a = He(Ee, Fe));
        return a
    }
    function Aea(a) {
        a = Math.trunc(a);
        return a >= 0 && Number.isSafeInteger(a) ? a : zea(a)
    }
    function wea(a) {
        a = Math.trunc(a);
        if (Number.isSafeInteger(a))
            a = String(a);
        else {
            var b = String(a);
            yea(b) ? a = b : (Ge(a),
            a = oea(Ee, Fe))
        }
        return a
    }
    function Qe(a) {
        var b = Math.trunc(Number(a));
        if (Number.isSafeInteger(b))
            return String(b);
        b = a.indexOf(".");
        b !== -1 && (a = a.substring(0, b));
        yea(a) || (Je(a),
        a = oea(Ee, Fe));
        return a
    }
    function Bea(a) {
        var b = Math.trunc(Number(a));
        if (Number.isSafeInteger(b) && b >= 0)
            return String(b);
        b = a.indexOf(".");
        b !== -1 && (a = a.substring(0, b));
        xea(a) || (Je(a),
        a = Ie(Ee, Fe));
        return a
    }
    function Cea(a, b) {
        b = b === void 0 ? !1 : b;
        if (a == null)
            return a;
        if (Le(a))
            return typeof a === "string" ? Qe(a) : b ? wea(a) : Re(a)
    }
    function Dea(a) {
        var b = !!b;
        if (!Le(a))
            throw me("uint64");
        typeof a === "string" ? a = Bea(a) : b ? (a = Math.trunc(a),
        a >= 0 && Number.isSafeInteger(a) ? a = String(a) : (b = String(a),
        xea(b) ? a = b : (Ge(a),
        a = Ie(Ee, Fe)))) : a = Aea(a);
        return a
    }
    function Eea(a) {
        if (a == null)
            return a;
        if (Le(a)) {
            if (typeof a === "string")
                return Bea(a);
            if (typeof a === "number")
                return Aea(a)
        }
    }
    function Te(a) {
        if (typeof a !== "string")
            throw Error();
        return a
    }
    function Ue(a) {
        if (a != null && typeof a !== "string")
            throw Error();
        return a
    }
    function Ve(a) {
        return a == null || typeof a === "string" ? a : void 0
    }
    function We(a, b, c, d) {
        if (a != null && typeof a === "object" && a.messagePrototypeMarker === xe)
            return a;
        if (!Array.isArray(a))
            return c ? d & 2 ? Fea(b) : new b : void 0;
        var e = c = te(a);
        e === 0 && (e |= d & 32);
        e |= d & 2;
        e !== c && ve(a, e);
        return new b(a)
    }
    function Fea(a) {
        var b = a[Uda];
        if (b)
            return b;
        b = new a;
        we(b.internalArray_);
        return a[Uda] = b
    }
    function Gea(a, b, c) {
        a = b ? tea(a) : Pe(a);
        return a == null ? c ? 0 : void 0 : a | 0
    }
    ;var Kea = function(a) {
        if (typeof Proxy !== "function")
            return a;
        var b = Hea(a);
        if (b)
            return b;
        b = new Proxy(a,{
            set: function(c, d, e) {
                Iea();
                c[d] = e;
                return !0
            }
        });
        Jea(a, b);
        return b
    };
    function Iea() {
        Sda()
    }
    var Lea = void 0
      , Mea = void 0
      , Hea = function(a) {
        var b;
        return (b = Lea) == null ? void 0 : b.get(a)
    }
      , Nea = function(a) {
        var b;
        return ((b = Mea) == null ? void 0 : b.get(a)) || a
    };
    function Jea(a, b) {
        (Lea || (Lea = new WeakMap)).set(a, b);
        (Mea || (Mea = new WeakMap)).set(b, a)
    }
    ;var Xe;
    function Ze(a, b) {
        Xe = b;
        a = new a(b);
        Xe = void 0;
        return a
    }
    var $e, Oea;
    function af(a) {
        switch (typeof a) {
        case "boolean":
            return $e || ($e = [0, void 0, !0]);
        case "number":
            return a > 0 ? void 0 : a === 0 ? Oea || (Oea = [0, void 0]) : [-a, void 0];
        case "string":
            return [0, a];
        case "object":
            return a;
        }
    }
    function bf(a, b, c) {
        a == null && (a = Xe);
        Xe = void 0;
        if (a == null) {
            var d = 96;
            c ? (a = [c],
            d |= 512) : a = [];
            b && (d = d & -16760833 | (b & 1023) << 14)
        } else {
            if (!Array.isArray(a))
                throw Error("narr");
            d = te(a);
            if (d & 2048)
                throw Error("farr");
            if (d & 64)
                return a;
            d |= 64;
            if (c && (d |= 512,
            c !== a[0]))
                throw Error("mid");
            a: {
                c = a;
                var e = c.length;
                if (e) {
                    var h = e - 1;
                    if (cea(c[h])) {
                        d |= 256;
                        b = h - (+!!(d & 512) - 1);
                        if (b >= 1024)
                            throw Error("pvtlmt");
                        d = d & -16760833 | (b & 1023) << 14;
                        break a
                    }
                }
                if (b) {
                    b = Math.max(b, e - (+!!(d & 512) - 1));
                    if (b > 1024)
                        throw Error("spvt");
                    d = d & -16760833 | (b & 1023) << 14
                }
            }
        }
        ve(a, d);
        return a
    }
    ;var Pea = {}
      , Qea = function() {
        try {
            var a = function() {
                return faa(Map, [], this.constructor)
            };
            k(a, Map);
            Td(new a);
            return !1
        } catch (b) {
            return !0
        }
    }()
      , cf = function() {
        this.JSC$6405_map_ = new Map
    };
    f = cf.prototype;
    f.get = function(a) {
        return this.JSC$6405_map_.get(a)
    }
    ;
    f.set = function(a, b) {
        this.JSC$6405_map_.set(a, b);
        this.size = this.JSC$6405_map_.size;
        return this
    }
    ;
    f.delete = function(a) {
        a = this.JSC$6405_map_.delete(a);
        this.size = this.JSC$6405_map_.size;
        return a
    }
    ;
    f.clear = function() {
        this.JSC$6405_map_.clear();
        this.size = this.JSC$6405_map_.size
    }
    ;
    f.has = function(a) {
        return this.JSC$6405_map_.has(a)
    }
    ;
    f.entries = function() {
        return this.JSC$6405_map_.entries()
    }
    ;
    f.keys = function() {
        return this.JSC$6405_map_.keys()
    }
    ;
    f.values = function() {
        return this.JSC$6405_map_.values()
    }
    ;
    f.forEach = function(a, b) {
        return this.JSC$6405_map_.forEach(a, b)
    }
    ;
    cf.prototype[Symbol.iterator] = function() {
        return this.entries()
    }
    ;
    var df = function() {
        if (Qea)
            return Object.setPrototypeOf(cf.prototype, Map.prototype),
            Object.defineProperties(cf.prototype, {
                size: {
                    value: 0,
                    configurable: !0,
                    enumerable: !0,
                    writable: !0
                }
            }),
            cf;
        var a = function() {
            return faa(Map, [], this.constructor)
        };
        k(a, Map);
        return a
    }();
    function Rea(a) {
        return a
    }
    var ef = function(a, b, c, d) {
        c = c === void 0 ? Rea : c;
        d = d === void 0 ? Rea : d;
        var e = df.call(this) || this;
        var h = te(a);
        h |= 64;
        ve(a, h);
        e.arrayState = h;
        e.valueCtor = b;
        e.keyToApi = c;
        e.valueToApi = e.valueCtor ? Sea : d;
        for (var l = 0; l < a.length; l++) {
            var m = a[l]
              , p = c(m[0], !1, !0)
              , q = m[1];
            b ? q === void 0 && (q = null) : q = d(m[1], !1, !0, void 0, void 0, h);
            df.prototype.set.call(e, p, q)
        }
        return e
    };
    k(ef, df);
    var Tea = function(a) {
        if (a.arrayState & 2)
            throw Error("Cannot mutate an immutable Map")
    }
      , Wea = function(a, b) {
        b = b === void 0 ? Uea : b;
        if (a.size !== 0)
            return Vea(a, b)
    }
      , Vea = function(a, b) {
        b = b === void 0 ? Uea : b;
        var c = [];
        a = df.prototype.entries.call(a);
        for (var d; !(d = a.next()).done; )
            d = d.value,
            d[0] = b(d[0]),
            d[1] = b(d[1]),
            c.push(d);
        return c
    };
    f = ef.prototype;
    f.clear = function() {
        Tea(this);
        df.prototype.clear.call(this)
    }
    ;
    f.delete = function(a) {
        Tea(this);
        return df.prototype.delete.call(this, this.keyToApi(a, !0, !1))
    }
    ;
    f.entries = function() {
        var a = Array.from(df.prototype.keys.call(this));
        return new Ce(a,Xea,this)
    }
    ;
    f.keys = function() {
        return df.prototype.keys.call(this)
    }
    ;
    f.values = function() {
        var a = Array.from(df.prototype.keys.call(this));
        return new Ce(a,ef.prototype.get,this)
    }
    ;
    f.forEach = function(a, b) {
        var c = this;
        df.prototype.forEach.call(this, function(d, e) {
            a.call(b, c.get(e), e, c)
        })
    }
    ;
    f.set = function(a, b) {
        Tea(this);
        a = this.keyToApi(a, !0, !1);
        return a == null ? this : b == null ? (df.prototype.delete.call(this, a),
        this) : df.prototype.set.call(this, a, this.valueToApi(b, !0, !0, this.valueCtor, !1, this.arrayState))
    }
    ;
    f.has = function(a) {
        return df.prototype.has.call(this, this.keyToApi(a, !1, !1))
    }
    ;
    f.get = function(a) {
        a = this.keyToApi(a, !1, !1);
        var b = df.prototype.get.call(this, a);
        if (b !== void 0) {
            var c = this.valueCtor;
            return c ? (c = this.valueToApi(b, !1, !0, c, this.callToMutableOnAccess, this.arrayState),
            c !== b && df.prototype.set.call(this, a, c),
            c) : b
        }
    }
    ;
    ef.prototype[Symbol.iterator] = function() {
        return this.entries()
    }
    ;
    ef.prototype.toJSON = void 0;
    ef.prototype.mapPrototypeMarker = aea;
    function Sea(a, b, c, d, e, h) {
        a = We(a, d, c, h);
        e && (a = ff(a));
        return a
    }
    function Uea(a) {
        return a
    }
    function Xea(a) {
        return [a, this.get(a)]
    }
    var Yea;
    function Zea() {
        return Yea || (Yea = new ef(we([]),void 0,void 0,void 0,Pea))
    }
    ;function $ea(a, b) {
        return afa(b)
    }
    function afa(a) {
        switch (typeof a) {
        case "number":
            return isFinite(a) ? a : String(a);
        case "boolean":
            return a ? 1 : 0;
        case "object":
            if (a)
                if (Array.isArray(a)) {
                    if (ze(a, void 0, 0))
                        return
                } else {
                    if (he(a))
                        return Jda(a);
                    if (a instanceof je) {
                        var b = a.JSC$6388_value_;
                        return b == null ? "" : typeof b === "string" ? b : a.JSC$6388_value_ = Jda(b)
                    }
                    if (a instanceof ef)
                        return Wea(a)
                }
        }
        return a
    }
    ;function bfa(a, b, c) {
        var d = ne(a)
          , e = d.length
          , h = b & 256 ? d[e - 1] : void 0;
        e += h ? -1 : 0;
        for (b = b & 512 ? 1 : 0; b < e; b++)
            d[b] = c(d[b]);
        if (h) {
            b = d[b] = {};
            for (var l in h)
                b[l] = c(h[l])
        }
        fea(d, a);
        return d
    }
    function gf(a, b, c, d, e) {
        if (a != null) {
            if (Array.isArray(a))
                a = ze(a, void 0, 0) ? void 0 : e && te(a) & 2 ? a : hf(a, b, c, d !== void 0, e);
            else if (cea(a)) {
                var h = {}, l;
                for (l in a)
                    h[l] = gf(a[l], b, c, d, e);
                a = h
            } else
                a = b(a, d);
            return a
        }
    }
    function hf(a, b, c, d, e) {
        var h = d || c ? te(a) : 0;
        d = d ? !!(h & 32) : void 0;
        for (var l = ne(a), m = 0; m < l.length; m++)
            l[m] = gf(l[m], b, c, d, e);
        c && (fea(l, a),
        c(h, l));
        return l
    }
    function cfa(a) {
        return gf(a, dfa, void 0, void 0, !1)
    }
    function dfa(a) {
        return a.messagePrototypeMarker === xe ? a.toJSON() : a instanceof je ? Qda(a) : he(a) ? new Uint8Array(a) : a instanceof ef ? Wea(a, cfa) : a
    }
    function efa(a) {
        return gf(a, ffa, void 0, void 0, !1)
    }
    function ffa(a) {
        return a.messagePrototypeMarker === xe ? a.toJSON() : a instanceof ef ? Wea(a, efa) : afa(a)
    }
    ;function gfa(a, b, c) {
        c = c === void 0 ? $da : c;
        if (a != null) {
            if (Hda && a instanceof Uint8Array)
                return b ? a : new Uint8Array(a);
            if (Array.isArray(a)) {
                var d = te(a);
                if (d & 2)
                    return a;
                b && (b = d === 0 || !!(d & 32) && !(d & 64 || !(d & 16)));
                return b ? (ve(a, (d | 34) & -12293),
                a) : hf(a, gfa, d & 4 ? $da : c, !0, !0)
            }
            a.messagePrototypeMarker === xe ? (c = a.internalArray_,
            d = ue(c),
            a = d & 2 ? a : Ze(a.constructor, jf(c, d, !0))) : a instanceof ef && !(a.arrayState & 2) && (c = we(Vea(a, gfa)),
            a = new ef(c,a.valueCtor,a.keyToApi,a.valueToApi));
            return a
        }
    }
    function jf(a, b, c) {
        var d = c || b & 2 ? $da : Zda
          , e = !!(b & 32);
        a = bfa(a, b, function(h) {
            return gfa(h, e, d)
        });
        Xda(a, 32 | (c ? 2 : 0));
        return a
    }
    function ff(a) {
        var b = a.internalArray_
          , c = ue(b);
        return c & 2 ? Ze(a.constructor, jf(b, c, !1)) : a
    }
    ;function hfa(a, b, c, d) {
        if (!(4 & b))
            return !0;
        if (c == null)
            return !1;
        !d && c === 0 && (4096 & b || 8192 & b) && (a.constructor[Wda] = (a.constructor[Wda] | 0) + 1) < 5 && Sda();
        return c === 0 ? !1 : !(c & b)
    }
    var lf = function(a, b) {
        a = a.internalArray_;
        return kf(a, ue(a), b)
    };
    function ifa(a, b, c, d) {
        b = d + (+!!(b & 512) - 1);
        if (!(b < 0 || b >= a.length || b >= c))
            return a[b]
    }
    var kf = function(a, b, c, d) {
        if (c === -1)
            return null;
        var e = b >> 14 & 1023 || 536870912;
        if (c >= e) {
            if (b & 256)
                return a[a.length - 1][c]
        } else {
            var h = a.length;
            if (d && b & 256 && (d = a[h - 1][c],
            d != null)) {
                if (ifa(a, b, e, c) && Vda != null) {
                    var l;
                    a = (l = Rda) != null ? l : Rda = {};
                    l = a[Vda] || 0;
                    l >= 4 || (a[Vda] = l + 1,
                    Sda())
                }
                return d
            }
            return ifa(a, b, e, c)
        }
    }
      , nf = function(a, b, c) {
        var d = a.internalArray_
          , e = ue(d);
        Ae(e);
        mf(d, e, b, c);
        return a
    };
    function mf(a, b, c, d, e) {
        var h = b >> 14 & 1023 || 536870912;
        if (c >= h || e && !Sca) {
            var l = b;
            if (b & 256)
                e = a[a.length - 1];
            else {
                if (d == null)
                    return l;
                e = a[h + (+!!(b & 512) - 1)] = {};
                l |= 256
            }
            e[c] = d;
            c < h && (a[c + (+!!(b & 512) - 1)] = void 0);
            l !== b && ve(a, l);
            return l
        }
        a[c + (+!!(b & 512) - 1)] = d;
        b & 256 && (a = a[a.length - 1],
        c in a && delete a[c]);
        return b
    }
    var pf = function(a, b, c) {
        return of(a, b, c, !1) !== void 0
    }
      , sf = function(a, b, c, d) {
        return of(a, b, qf(a, d, c)) !== void 0
    };
    function jfa(a, b, c, d, e) {
        var h = b & 2
          , l = kf(a, b, c, e);
        Array.isArray(l) || (l = dea);
        var m = !(d & 2);
        d = !(d & 1);
        var p = !!(b & 32)
          , q = te(l);
        q !== 0 || !p || h || m ? q & 1 || (q |= 1,
        ve(l, q)) : (q |= 33,
        ve(l, q));
        h ? (a = !1,
        q & 2 || (we(l),
        a = !!(4 & q)),
        (d || a) && Object.freeze(l)) : (h = !!(2 & q) || !!(2048 & q),
        d && h ? (l = ne(l),
        d = 1,
        p && !m && (d |= 32),
        ve(l, d),
        mf(a, b, c, l, e)) : m && q & 32 && !h && se(l, 32));
        return l
    }
    var lfa = function(a, b, c, d) {
        kfa(a, b, tf, d, c, !1, 1);
        return a
    }
      , uf = function(a, b) {
        a = a.internalArray_;
        var c = ue(a)
          , d = kf(a, c, b)
          , e = pea(d);
        e != null && e !== d && mf(a, c, b, e);
        return e
    }
      , vf = function(a, b) {
        return a === hea ? 2 : b ? 4 : Tca ? 5 : 2
    };
    function mfa(a, b, c, d, e, h) {
        var l = a.internalArray_
          , m = ue(l)
          , p = 2 & m ? 1 : d;
        h = !!h;
        d = nfa(l, m, b, e);
        var q = te(d);
        if (hfa(a, q, void 0, h)) {
            if (4 & q || Object.isFrozen(d))
                d = ne(d),
                q = wf(q, m),
                m = mf(l, m, b, d, e);
            for (var r = a = 0; a < d.length; a++) {
                var x = c(d[a]);
                x != null && (d[r++] = x)
            }
            r < a && (d.length = r);
            q = ofa(q, m);
            q = (q | 20) & -4097;
            q &= -8193;
            ve(d, q);
            2 & q && Object.freeze(d)
        }
        var z;
        p === 1 || p === 4 && 32 & q ? xf(q) || (h = q,
        q |= 2,
        q !== h && ve(d, q),
        Object.freeze(d)) : (c = p !== 5 ? !1 : !!(32 & q) || xf(q) || !!Hea(d),
        (p === 2 || c) && xf(q) && (d = ne(d),
        q = wf(q, m),
        q = zf(q, m, h),
        ve(d, q),
        m = mf(l, m, b, d, e)),
        xf(q) || (b = q,
        q = zf(q, m, h),
        q !== b && ve(d, q)),
        c && (z = Kea(d)));
        return z || d
    }
    function nfa(a, b, c, d) {
        a = kf(a, b, c, d);
        return Array.isArray(a) ? a : dea
    }
    function ofa(a, b) {
        a === 0 && (a = wf(a, b));
        return a | 1
    }
    function xf(a) {
        return !!(2 & a) && !!(4 & a) || !!(2048 & a)
    }
    var Af = function(a, b) {
        a = a.internalArray_;
        var c = ue(a)
          , d = kf(a, c, b)
          , e = ye(d, !0, !!(c & 34));
        e != null && e !== d && mf(a, c, b, e);
        return e == null ? ke() : e
    };
    function pfa(a, b) {
        a = a.internalArray_;
        var c = ue(a);
        a: {
            var d = kf(a, c, b)
              , e = c & 2
              , h = !1;
            if (d == null) {
                if (e) {
                    b = Zea();
                    break a
                }
                d = []
            } else if (d.constructor === ef) {
                if ((d.arrayState & 2) == 0 || e) {
                    b = d;
                    break a
                }
                d = Vea(d)
            } else
                Array.isArray(d) ? h = !!(te(d) & 2) : d = [];
            if (e) {
                if (!d.length) {
                    b = Zea();
                    break a
                }
                h || (h = !0,
                we(d))
            } else if (h) {
                h = !1;
                e = ne(d);
                for (d = 0; d < e.length; d++) {
                    var l = e[d] = ne(e[d]);
                    Array.isArray(l[1]) && (l[1] = we(l[1]))
                }
                d = e
            }
            h || (te(d) & 64 ? se(d, 32) : 32 & c && Yda(d));
            h = new ef(d,void 0,Gea,Gea);
            mf(a, c, b, h, !1);
            b = h
        }
        return b
    }
    function Bf(a, b, c, d) {
        var e = a.internalArray_
          , h = ue(e);
        Ae(h);
        if (c == null)
            return mf(e, h, b),
            a;
        c = Nea(c);
        var l = te(c)
          , m = l
          , p = !!(2 & l) || Object.isFrozen(c)
          , q = !p && (void 0 === iea || !1);
        if (hfa(a, l))
            for (l = 21,
            p && (c = ne(c),
            m = 0,
            l = wf(l, h),
            l = zf(l, h, !0)),
            p = 0; p < c.length; p++)
                c[p] = d(c[p]);
        q && (c = ne(c),
        m = 0,
        l = wf(l, h),
        l = zf(l, h, !0));
        l !== m && ve(c, l);
        mf(e, h, b, c);
        return a
    }
    function Cf(a, b, c, d) {
        var e = a.internalArray_
          , h = ue(e);
        Ae(h);
        mf(e, h, b, (d === "0" ? Number(c) === 0 : c === d) ? void 0 : c);
        return a
    }
    function Ef(a, b, c, d) {
        qfa(a.internalArray_, b, c, d);
        return a
    }
    function qfa(a, b, c, d) {
        var e = ue(a);
        Ae(e);
        a = jfa(a, e, b, 2);
        b = te(a);
        d = c(d, !!(4 & b) && !!(4096 & b));
        a.push(d)
    }
    function rfa(a) {
        return a
    }
    var Ff = function(a, b, c, d) {
        var e = a.internalArray_
          , h = ue(e);
        Ae(h);
        if (d == null) {
            var l = sfa(e);
            if (tfa(l, e, h, c) === b)
                l.set(c, 0);
            else
                return a
        } else
            h = ufa(e, h, c, b);
        mf(e, h, b, d);
        return a
    }
      , Gf = function(a, b, c, d) {
        var e = ue(a);
        e = ufa(a, e, c, b);
        mf(a, e, b, d)
    }
      , qf = function(a, b, c) {
        return Hf(a, b) === c ? c : -1
    }
      , Hf = function(a, b) {
        a = a.internalArray_;
        return tfa(sfa(a), a, ue(a), b)
    };
    function sfa(a) {
        if (oe) {
            var b;
            return (b = a[re]) != null ? b : a[re] = new Map
        }
        if (re in a)
            return a[re];
        b = new Map;
        Object.defineProperty(a, re, {
            value: b
        });
        return b
    }
    function ufa(a, b, c, d) {
        var e = sfa(a)
          , h = tfa(e, a, b, c);
        h !== d && (h && (b = mf(a, b, h)),
        e.set(c, d));
        return b
    }
    function tfa(a, b, c, d) {
        var e = a.get(d);
        if (e != null)
            return e;
        for (var h = e = 0; h < d.length; h++) {
            var l = d[h];
            kf(b, c, l) != null && (e !== 0 && (c = mf(b, c, e)),
            e = l)
        }
        a.set(d, e);
        return e
    }
    var wfa = function(a) {
        var b = vfa;
        a = a.internalArray_;
        var c = ue(a);
        Ae(c);
        var d = kf(a, c, 4);
        b = ff(We(d, b, !0, c));
        d !== b && mf(a, c, 4, b);
        return b
    }
      , xfa = function(a, b, c, d) {
        var e = ue(a), h = kf(a, e, c, d), l;
        if (h != null && h.messagePrototypeMarker === xe)
            return b = ff(h),
            b !== h && mf(a, e, c, b, d),
            b.internalArray_;
        if (Array.isArray(h)) {
            var m = te(h);
            m & 2 ? l = jf(h, m, !1) : l = h;
            l = bf(l, b[0], b[1])
        } else
            l = bf(void 0, b[0], b[1]);
        l !== h && mf(a, e, c, l, d);
        return l
    };
    function of(a, b, c, d) {
        a = a.internalArray_;
        var e = ue(a)
          , h = kf(a, e, c, d);
        b = We(h, b, !1, e);
        b !== h && b != null && mf(a, e, c, b, d);
        return b
    }
    var If = function(a, b, c, d) {
        d = d === void 0 ? !1 : d;
        b = of(a, b, c, d);
        if (b == null)
            return b;
        a = a.internalArray_;
        var e = ue(a);
        if (!(e & 2)) {
            var h = ff(b);
            h !== b && (b = h,
            mf(a, e, c, b, d))
        }
        return b
    };
    function yfa(a, b, c, d, e, h, l, m) {
        var p = !!(2 & b);
        e = p ? 1 : e;
        l = !!l;
        m && (m = !p);
        p = nfa(a, b, d, h);
        var q = te(p)
          , r = !!(4 & q);
        if (!r) {
            q = ofa(q, b);
            var x = p
              , z = b
              , C = !!(2 & q);
            C && (z |= 2);
            for (var E = !C, K = !0, N = 0, Q = 0; N < x.length; N++) {
                var V = We(x[N], c, !1, z);
                if (V instanceof c) {
                    if (!C) {
                        var ca = !!(te(V.internalArray_) & 2);
                        E && (E = !ca);
                        K && (K = ca)
                    }
                    x[Q++] = V
                }
            }
            Q < N && (x.length = Q);
            q |= 4;
            q = K ? q | 16 : q & -17;
            q = E ? q | 8 : q & -9;
            ve(x, q);
            C && Object.freeze(x)
        }
        if (m && !(8 & q || !p.length && (e === 1 || e === 4 && 32 & q))) {
            xf(q) && (p = ne(p),
            q = wf(q, b),
            b = mf(a, b, d, p, h));
            c = p;
            m = q;
            for (x = 0; x < c.length; x++)
                q = c[x],
                z = ff(q),
                q !== z && (c[x] = z);
            m |= 8;
            m = c.length ? m & -17 : m | 16;
            ve(c, m);
            q = m
        }
        var Z;
        e === 1 || e === 4 && 32 & q ? xf(q) || (b = q,
        q |= !p.length || 16 & q && (!r || 32 & q) ? 2 : 2048,
        q !== b && ve(p, q),
        Object.freeze(p)) : (r = e !== 5 ? !1 : !!(32 & q) || xf(q) || !!Hea(p),
        (e === 2 || r) && xf(q) && (p = ne(p),
        q = wf(q, b),
        q = zf(q, b, l),
        ve(p, q),
        b = mf(a, b, d, p, h)),
        xf(q) || (a = q,
        q = zf(q, b, l),
        q !== a && ve(p, q)),
        r && (Z = Kea(p)));
        return Z || p
    }
    var Jf = function(a, b, c, d) {
        a = a.internalArray_;
        var e = ue(a);
        return yfa(a, e, b, c, d, void 0, !1, !(2 & e))
    }
      , Lf = function(a, b, c) {
        c == null && (c = void 0);
        return nf(a, b, c)
    }
      , Mf = function(a, b, c, d) {
        d == null && (d = void 0);
        return Ff(a, b, c, d)
    }
      , Nf = function(a, b, c) {
        var d = a.internalArray_
          , e = ue(d);
        Ae(e);
        if (c == null)
            return mf(d, e, b),
            a;
        c = Nea(c);
        for (var h = te(c), l = h, m = !!(2 & h) || !!(2048 & h), p = m || Object.isFrozen(c), q = !p && (void 0 === iea || !1), r = !0, x = !0, z = 0; z < c.length; z++) {
            var C = c[z];
            m || (C = !!(te(C.internalArray_) & 2),
            r && (r = !C),
            x && (x = C))
        }
        m || (h |= 5,
        h = r ? h | 8 : h & -9,
        h = x ? h | 16 : h & -17);
        if (q || p && h !== l)
            c = ne(c),
            l = 0,
            h = wf(h, e),
            h = zf(h, e, !0);
        h !== l && ve(c, h);
        mf(d, e, b, c);
        return a
    };
    function wf(a, b) {
        a = (2 & b ? a | 2 : a & -3) | 32;
        return a &= -2049
    }
    function zf(a, b, c) {
        32 & b && c || (a &= -33);
        return a
    }
    function kfa(a, b, c, d, e, h, l) {
        a = a.internalArray_;
        var m = ue(a);
        Ae(m);
        b = yfa(a, m, c, b, 2, h, !0);
        c = d != null ? d : new c;
        if (l && (typeof e !== "number" || e < 0 || e > b.length))
            throw Error();
        e != void 0 ? b.splice(e, l, c) : b.push(c);
        te(c.internalArray_) & 2 ? se(b, 8) : se(b, 16)
    }
    var Of = function(a, b, c, d) {
        kfa(a, b, c, d);
        return a
    }
      , Pf = function(a, b) {
        a = lf(a, b);
        var c;
        a == null ? c = a : Le(a) ? typeof a === "number" ? c = Re(a) : c = Qe(a) : c = void 0;
        return c
    }
      , Qf = function(a, b) {
        a = lf(a, b);
        var c;
        a == null ? c = a : Le(a) ? typeof a === "number" ? c = Aea(a) : c = Bea(a) : c = void 0;
        return c
    };
    function Rf(a, b) {
        return a != null ? a : b
    }
    var Sf = function(a, b) {
        return rea(lf(a, b))
    }
      , Tf = function(a, b) {
        return Pe(lf(a, b))
    }
      , Uf = function(a, b) {
        return Ve(lf(a, b))
    }
      , Vf = function(a, b, c) {
        c = c === void 0 ? !1 : c;
        return Rf(Sf(a, b), c)
    }
      , Wf = function(a, b, c) {
        c = c === void 0 ? 0 : c;
        return Rf(Tf(a, b), c)
    }
      , Xf = function(a, b) {
        var c = c === void 0 ? 0 : c;
        return Rf(Pf(a, b), c)
    }
      , zfa = function(a) {
        var b = b === void 0 ? 0 : b;
        return Rf(Qf(a, 23), b)
    }
      , Yf = function(a, b) {
        var c = c === void 0 ? 0 : c;
        return Rf(uf(a, b), c)
    }
      , Zf = function(a, b) {
        var c = c === void 0 ? "" : c;
        return Rf(Uf(a, b), c)
    }
      , $f = function(a, b) {
        var c = 0;
        c = c === void 0 ? 0 : c;
        return Rf(Ne(lf(a, b)), c)
    }
      , ag = function(a, b, c, d, e) {
        return mfa(a, b, Ve, c, d, e)
    }
      , bg = function(a, b, c) {
        return Zf(a, qf(a, c, b))
    }
      , cg = function(a, b, c, d) {
        return If(a, b, qf(a, d, c))
    }
      , dg = function(a, b, c) {
        return nf(a, b, qea(c))
    }
      , fg = function(a, b, c) {
        return Cf(a, b, qea(c), !1)
    }
      , gg = function(a, b, c) {
        return nf(a, b, Oe(c))
    }
      , hg = function(a, b, c) {
        return nf(a, b, Se(c))
    }
      , ig = function(a, b, c) {
        return nf(a, b, Ue(c))
    }
      , jg = function(a, b, c) {
        return Cf(a, b, Ue(c), "")
    }
      , kg = function(a, b, c) {
        return nf(a, b, c == null ? c : Me(c))
    }
      , lg = function(a, b, c) {
        return Cf(a, b, c == null ? c : Me(c), 0)
    };
    function Afa(a, b) {
        return Error("Invalid wire type: " + a + " (at position " + b + ")")
    }
    function Bfa() {
        return Error("Failed to read varint, encoding is invalid.")
    }
    function Cfa(a, b) {
        return Error("Tried to read past the end of the data " + b + " > " + a)
    }
    ;function Dfa(a) {
        if (typeof a === "string")
            return {
                buffer: Nda(a),
                isImmutable: !1
            };
        if (Array.isArray(a))
            return {
                buffer: new Uint8Array(a),
                isImmutable: !1
            };
        if (a.constructor === Uint8Array)
            return {
                buffer: a,
                isImmutable: !1
            };
        if (a.constructor === ArrayBuffer)
            return {
                buffer: new Uint8Array(a),
                isImmutable: !1
            };
        if (a.constructor === je)
            return {
                buffer: le(a) || new Uint8Array(0),
                isImmutable: !0
            };
        if (a instanceof Uint8Array)
            return {
                buffer: new Uint8Array(a.buffer,a.byteOffset,a.byteLength),
                isImmutable: !1
            };
        throw Error("Type not convertible to a Uint8Array, expected a Uint8Array, an ArrayBuffer, a base64 encoded string, a ByteString or an Array of numbers");
    }
    ;var Efa = function(a, b) {
        this.bytes_ = null;
        this.bytesAreImmutable_ = !1;
        this.cursor_ = this.end_ = this.JSC$6414_start_ = 0;
        this.init(a, void 0, void 0, b)
    };
    f = Efa.prototype;
    f.init = function(a, b, c, d) {
        d = d === void 0 ? {} : d;
        this.aliasBytesFields = d.aliasBytesFields === void 0 ? !1 : d.aliasBytesFields;
        a && (a = Dfa(a),
        this.bytes_ = a.buffer,
        this.bytesAreImmutable_ = a.isImmutable,
        this.JSC$6414_start_ = b || 0,
        this.end_ = c !== void 0 ? this.JSC$6414_start_ + c : this.bytes_.length,
        this.cursor_ = this.JSC$6414_start_)
    }
    ;
    f.free = function() {
        this.clear();
        mg.length < 100 && mg.push(this)
    }
    ;
    f.clear = function() {
        this.bytes_ = null;
        this.bytesAreImmutable_ = !1;
        this.cursor_ = this.end_ = this.JSC$6414_start_ = 0;
        this.aliasBytesFields = !1
    }
    ;
    f.reset = function() {
        this.cursor_ = this.JSC$6414_start_
    }
    ;
    f.advance = function(a) {
        ng(this, this.cursor_ + a)
    }
    ;
    f.atEnd = function() {
        return this.cursor_ == this.end_
    }
    ;
    var og = function(a, b) {
        var c = 0
          , d = 0
          , e = 0
          , h = a.bytes_
          , l = a.cursor_;
        do {
            var m = h[l++];
            c |= (m & 127) << e;
            e += 7
        } while (e < 32 && m & 128);
        e > 32 && (d |= (m & 127) >> 4);
        for (e = 3; e < 32 && m & 128; e += 7)
            m = h[l++],
            d |= (m & 127) << e;
        ng(a, l);
        if (m < 128)
            return b(c >>> 0, d >>> 0);
        throw Bfa()
    }
      , ng = function(a, b) {
        a.cursor_ = b;
        if (b > a.end_)
            throw Cfa(a.end_, b)
    }
      , pg = function(a) {
        var b = a.bytes_
          , c = a.cursor_
          , d = b[c++]
          , e = d & 127;
        if (d & 128 && (d = b[c++],
        e |= (d & 127) << 7,
        d & 128 && (d = b[c++],
        e |= (d & 127) << 14,
        d & 128 && (d = b[c++],
        e |= (d & 127) << 21,
        d & 128 && (d = b[c++],
        e |= d << 28,
        d & 128 && b[c++] & 128 && b[c++] & 128 && b[c++] & 128 && b[c++] & 128 && b[c++] & 128)))))
            throw Bfa();
        ng(a, c);
        return e
    }
      , qg = function(a) {
        var b = a.bytes_
          , c = a.cursor_
          , d = b[c + 0]
          , e = b[c + 1]
          , h = b[c + 2];
        b = b[c + 3];
        a.advance(4);
        return (d << 0 | e << 8 | h << 16 | b << 24) >>> 0
    }
      , Ffa = function(a) {
        var b = qg(a);
        return qg(a) * 4294967296 + (b >>> 0)
    }
      , Gfa = function(a) {
        var b = qg(a)
          , c = qg(a);
        a = (c >> 31) * 2 + 1;
        var d = c >>> 20 & 2047;
        b = 4294967296 * (c & 1048575) + b;
        return d == 2047 ? b ? NaN : a * Infinity : d == 0 ? a * Math.pow(2, -1074) * b : a * Math.pow(2, d - 1075) * (b + 4503599627370496)
    }
      , Hfa = function(a) {
        for (var b = 0, c = a.cursor_, d = c + 10, e = a.bytes_; c < d; ) {
            var h = e[c++];
            b |= h;
            if ((h & 128) === 0)
                return ng(a, c),
                !!(b & 127)
        }
        throw Bfa()
    }
      , Ifa = function(a, b) {
        if (b < 0)
            throw Error("Tried to read a negative byte length: " + b);
        var c = a.cursor_
          , d = c + b;
        if (d > a.end_)
            throw Cfa(b, a.end_ - c);
        a.cursor_ = d;
        return c
    }
      , Jfa = function(a, b) {
        if (b == 0)
            return ke();
        var c = Ifa(a, b);
        a.aliasBytesFields && a.bytesAreImmutable_ ? c = a.bytes_.subarray(c, c + b) : (a = a.bytes_,
        b = c + b,
        c = c === b ? new Uint8Array(0) : jea ? a.slice(c, b) : new Uint8Array(a.subarray(c, b)));
        return c.length == 0 ? ke() : new je(c,ie)
    }
      , mg = [];
    var rg = function(a, b) {
        if (mg.length) {
            var c = mg.pop();
            c.init(a, void 0, void 0, b);
            a = c
        } else
            a = new Efa(a,b);
        this.decoder_ = a;
        this.fieldCursor_ = this.decoder_.cursor_;
        this.nextWireType_ = this.nextField_ = -1;
        Kfa(this, b)
    }
      , Kfa = function(a, b) {
        b = b === void 0 ? {} : b;
        a.discardUnknownFields = b.discardUnknownFields === void 0 ? !1 : b.discardUnknownFields
    };
    rg.prototype.free = function() {
        this.decoder_.clear();
        this.nextWireType_ = this.nextField_ = -1;
        sg.length < 100 && sg.push(this)
    }
    ;
    rg.prototype.reset = function() {
        this.decoder_.reset();
        this.fieldCursor_ = this.decoder_.cursor_;
        this.nextWireType_ = this.nextField_ = -1
    }
    ;
    rg.prototype.advance = function(a) {
        this.decoder_.advance(a)
    }
    ;
    var Lfa = function(a) {
        if (a.decoder_.atEnd())
            return !1;
        a.fieldCursor_ = a.decoder_.cursor_;
        var b = pg(a.decoder_) >>> 0
          , c = b >>> 3;
        b &= 7;
        if (!(b >= 0 && b <= 5))
            throw Afa(b, a.fieldCursor_);
        if (c < 1)
            throw Error("Invalid field number: " + c + " (at position " + a.fieldCursor_ + ")");
        a.nextField_ = c;
        a.nextWireType_ = b;
        return !0
    }
      , tg = function(a) {
        switch (a.nextWireType_) {
        case 0:
            a.nextWireType_ != 0 ? tg(a) : Hfa(a.decoder_);
            break;
        case 1:
            a.decoder_.advance(8);
            break;
        case 2:
            if (a.nextWireType_ != 2)
                tg(a);
            else {
                var b = pg(a.decoder_) >>> 0;
                a.decoder_.advance(b)
            }
            break;
        case 5:
            a.decoder_.advance(4);
            break;
        case 3:
            b = a.nextField_;
            do {
                if (!Lfa(a))
                    throw Error("Unmatched start-group tag: stream EOF");
                if (a.nextWireType_ == 4) {
                    if (a.nextField_ != b)
                        throw Error("Unmatched end-group tag");
                    break
                }
                tg(a)
            } while (1);
            break;
        default:
            throw Afa(a.nextWireType_, a.fieldCursor_);
        }
    }
      , ug = function(a, b, c) {
        var d = a.decoder_.end_
          , e = pg(a.decoder_) >>> 0
          , h = a.decoder_.cursor_ + e
          , l = h - d;
        l <= 0 && (a.decoder_.end_ = h,
        c(b, a, void 0, void 0, void 0),
        l = h - a.decoder_.cursor_);
        if (l)
            throw Error("Message parsing ended unexpectedly. Expected to read " + (e + " bytes, instead read " + (e - l) + " bytes, either the data ended unexpectedly or the message misreported its own length"));
        a.decoder_.cursor_ = h;
        a.decoder_.end_ = d
    }
      , Mfa = function(a) {
        var b = pg(a.decoder_) >>> 0;
        a = a.decoder_;
        var c = Ifa(a, b);
        a = a.bytes_;
        if (Ica) {
            var d = a, e;
            (e = Hca) || (e = Hca = new TextDecoder("utf-8",{
                fatal: !0
            }));
            b = c + b;
            d = c === 0 && b === d.length ? d : d.subarray(c, b);
            try {
                var h = e.decode(d)
            } catch (q) {
                if (yd === void 0) {
                    try {
                        e.decode(new Uint8Array([128]))
                    } catch (r) {}
                    try {
                        e.decode(new Uint8Array([97])),
                        yd = !0
                    } catch (r) {
                        yd = !1
                    }
                }
                !yd && (Hca = void 0);
                throw q
            }
        } else {
            h = c;
            b = h + b;
            c = [];
            for (var l = null, m, p; h < b; )
                m = a[h++],
                m < 128 ? c.push(m) : m < 224 ? h >= b ? xd() : (p = a[h++],
                m < 194 || (p & 192) !== 128 ? (h--,
                xd()) : c.push((m & 31) << 6 | p & 63)) : m < 240 ? h >= b - 1 ? xd() : (p = a[h++],
                (p & 192) !== 128 || m === 224 && p < 160 || m === 237 && p >= 160 || ((e = a[h++]) & 192) !== 128 ? (h--,
                xd()) : c.push((m & 15) << 12 | (p & 63) << 6 | e & 63)) : m <= 244 ? h >= b - 2 ? xd() : (p = a[h++],
                (p & 192) !== 128 || (m << 28) + (p - 144) >> 30 !== 0 || ((e = a[h++]) & 192) !== 128 || ((d = a[h++]) & 192) !== 128 ? (h--,
                xd()) : (m = (m & 7) << 18 | (p & 63) << 12 | (e & 63) << 6 | d & 63,
                m -= 65536,
                c.push((m >> 10 & 1023) + 55296, (m & 1023) + 56320))) : xd(),
                c.length >= 8192 && (l = Gca(l, c),
                c.length = 0);
            h = Gca(l, c)
        }
        return h
    }
      , Nfa = function(a) {
        var b = pg(a.decoder_) >>> 0;
        return Jfa(a.decoder_, b)
    }
      , sg = [];
    function Ofa(a) {
        return a
    }
    function Pfa(a) {
        return a
    }
    function Qfa(a, b, c, d) {
        return Rfa(a, b, c, d, Sfa, Tfa)
    }
    function Ufa(a, b, c, d) {
        return Rfa(a, b, c, d, Vfa, Wfa)
    }
    function Rfa(a, b, c, d, e, h) {
        if (!c.length && !d)
            return 0;
        for (var l = 0, m = 0, p = 0, q = 0, r = 0, x = c.length - 1; x >= 0; x--) {
            var z = c[x];
            d && x === c.length - 1 && z === d || (q++,
            z != null && p++)
        }
        if (d)
            for (var C in d)
                x = +C,
                isNaN(x) || (r += Xfa(x),
                m++,
                x > l && (l = x));
        q = e(q, p) + h(m, l, r);
        C = p;
        x = m;
        z = l;
        for (var E = r, K = c.length - 1; K >= 0; K--) {
            var N = c[K];
            if (!(N == null || d && K === c.length - 1 && N === d)) {
                N = K - b;
                var Q = e(N, C) + h(x, z, E);
                Q < q && (a = 1 + N,
                q = Q);
                x++;
                C--;
                E += Xfa(N);
                z = Math.max(z, N)
            }
        }
        b = e(0, 0) + h(x, z, E);
        b < q && (a = 0,
        q = b);
        if (d) {
            x = m;
            z = l;
            E = r;
            C = p;
            for (var V in d)
                d = +V,
                isNaN(d) || d >= 1024 || (x--,
                C++,
                E -= V.length,
                l = e(d, C) + h(x, z, E),
                l < q && (a = 1 + d,
                q = l))
        }
        return a
    }
    function Wfa(a, b, c) {
        return c + a * 3 + (a > 1 ? a - 1 : 0)
    }
    function Vfa(a, b) {
        return (a > 1 ? a - 1 : 0) + (a - b) * 4
    }
    function Tfa(a, b) {
        return a == 0 ? 0 : 9 * Math.max(1 << 32 - Math.clz32(a + a / 2 - 1), 4) <= b ? a == 0 ? 0 : a < 4 ? 100 + (a - 1) * 16 : a < 6 ? 148 + (a - 4) * 16 : a < 12 ? 244 + (a - 6) * 16 : a < 22 ? 436 + (a - 12) * 19 : a < 44 ? 820 + (a - 22) * 17 : 52 + 32 * a : 40 + 4 * b
    }
    function Sfa(a) {
        return 40 + 4 * a
    }
    function Xfa(a) {
        return a >= 100 ? a >= 1E4 ? Math.ceil(Math.log10(1 + a)) : a < 1E3 ? 3 : 4 : a < 10 ? 1 : 2
    } ;var vg, wg, Yfa, xg = function(a, b, c) {
        this.internalArray_ = bf(a, b, c)
    };
    xg.prototype.toJSON = function() {
        return yg(this)
    }
    ;
    xg.prototype.serialize = function(a) {
        try {
            return wg = !0,
            a && (vg = a === Pfa || a !== Ofa && a !== Qfa && a !== Ufa ? Pfa : a),
            JSON.stringify(yg(this), $ea)
        } finally {
            a && (vg = void 0),
            wg = !1
        }
    }
    ;
    var Zfa = function(a, b) {
        if (b == null || b == "")
            return new a;
        b = JSON.parse(b);
        if (!Array.isArray(b))
            throw Error("dnarr");
        return Ze(a, Yda(b))
    };
    f = xg.prototype;
    f.getExtension = function(a) {
        return a.ctor ? a.isRepeated ? a.getExtensionFn(this, a.ctor, 175237375, vf(void 0, !0), !0) : a.getExtensionFn(this, a.ctor, 175237375, !0) : a.isRepeated ? a.getExtensionFn(this, 175237375, vf(void 0, !0), !0) : a.getExtensionFn(this, 175237375, a.defaultValue, !0)
    }
    ;
    f.clone = function() {
        var a = this.internalArray_;
        return Ze(this.constructor, jf(a, ue(a), !1))
    }
    ;
    f.isImmutable = function() {
        return !!(te(this.internalArray_) & 2)
    }
    ;
    f.messagePrototypeMarker = xe;
    f.toString = function() {
        try {
            return wg = !0,
            yg(this).toString()
        } finally {
            wg = !1
        }
    }
    ;
    function yg(a) {
        var b = wg ? a.internalArray_ : Yfa ? hf(a.internalArray_, dfa, void 0, void 0, !1) : hf(a.internalArray_, ffa, void 0, void 0, !1);
        var c = !wg;
        var d = Oca ? void 0 : a.constructor.repeatedFields_;
        var e = ue(c ? a.internalArray_ : b);
        if (a = b.length) {
            var h = b[a - 1]
              , l = cea(h);
            l ? a-- : h = void 0;
            var m = +!!(e & 512) - 1, p = a - m, q = !!vg && Sca && !(e & 512), r;
            e = (r = vg) != null ? r : Pfa;
            e = q ? e(p, m, b, h) : p;
            r = (p = q && p !== e) ? Array.prototype.slice.call(b, 0, a) : b;
            if (l || p) {
                b: {
                    var x = r;
                    var z = h;
                    l = {};
                    q = !1;
                    if (p)
                        for (var C = Math.max(0, e + m); C < x.length; C++) {
                            var E = x[C]
                              , K = C - m;
                            E == null || ze(E, d, K) || bea(E) && E.size === 0 || (x[C] = void 0,
                            l[K] = E,
                            q = !0)
                        }
                    if (z)
                        for (var N in z)
                            if (C = +N,
                            isNaN(C))
                                l[N] = z[N];
                            else if (E = z[N],
                            Array.isArray(E) && (ze(E, d, +N) || bea(E) && E.size === 0) && (E = null),
                            E == null && (q = !0),
                            p && C < e) {
                                q = !0;
                                E = C + m;
                                for (K = x.length; K <= E; K++)
                                    x.push(void 0);
                                x[E] = z[C]
                            } else
                                E != null && (l[N] = E);
                    if (q) {
                        for (var Q in l) {
                            z = l;
                            break b
                        }
                        z = null
                    }
                }
                x = z == null ? h != null : z !== h
            }
            p && (a = r.length);
            for (var V; a > 0; a--) {
                Q = a - 1;
                N = r[Q];
                Q -= m;
                if (!(N == null || ze(N, d, Q) || bea(N) && N.size === 0))
                    break;
                V = !0
            }
            if (r !== b || x || V) {
                if (!p && !c)
                    r = Array.prototype.slice.call(r, 0, a);
                else if (V || x || z)
                    r.length = a;
                z && r.push(z)
            }
            b = r
        }
        return b
    }
    ;var $fa = function(a, b) {
        this.JSC$6429_lo = a >>> 0;
        this.JSC$6429_hi = b >>> 0
    }, bga = function(a) {
        if (!a)
            return aga || (aga = new $fa(0,0));
        if (!/^\d+$/.test(a))
            return null;
        Je(a);
        return new $fa(Ee,Fe)
    }, aga, cga = function(a, b) {
        this.JSC$6431_lo = a >>> 0;
        this.JSC$6431_hi = b >>> 0
    }, ega = function(a) {
        if (!a)
            return dga || (dga = new cga(0,0));
        if (!/^-?\d+$/.test(a))
            return null;
        Je(a);
        return new cga(Ee,Fe)
    }, dga;
    var fga = function() {
        this.JSC$6433_buffer_ = []
    };
    fga.prototype.length = function() {
        return this.JSC$6433_buffer_.length
    }
    ;
    fga.prototype.end = function() {
        var a = this.JSC$6433_buffer_;
        this.JSC$6433_buffer_ = [];
        return a
    }
    ;
    var gga = function(a, b, c) {
        for (; c > 0 || b > 127; )
            a.JSC$6433_buffer_.push(b & 127 | 128),
            b = (b >>> 7 | c << 25) >>> 0,
            c >>>= 7;
        a.JSC$6433_buffer_.push(b)
    }
      , zg = function(a, b) {
        for (; b > 127; )
            a.JSC$6433_buffer_.push(b & 127 | 128),
            b >>>= 7;
        a.JSC$6433_buffer_.push(b)
    }
      , hga = function(a, b) {
        if (b >= 0)
            zg(a, b);
        else {
            for (var c = 0; c < 9; c++)
                a.JSC$6433_buffer_.push(b & 127 | 128),
                b >>= 7;
            a.JSC$6433_buffer_.push(1)
        }
    }
      , Ag = function(a, b) {
        a.JSC$6433_buffer_.push(b >>> 0 & 255);
        a.JSC$6433_buffer_.push(b >>> 8 & 255);
        a.JSC$6433_buffer_.push(b >>> 16 & 255);
        a.JSC$6433_buffer_.push(b >>> 24 & 255)
    };
    var iga = function() {
        this.blocks_ = [];
        this.totalLength_ = 0;
        this.encoder_ = new fga
    }
      , Bg = function(a, b) {
        b.length !== 0 && (a.blocks_.push(b),
        a.totalLength_ += b.length)
    }
      , Cg = function(a, b, c) {
        zg(a.encoder_, b * 8 + c)
    }
      , jga = function(a, b, c) {
        c != null && (typeof c === "string" && bga(c),
        Cg(a, b, 1),
        typeof c === "number" ? (a = a.encoder_,
        lea(c),
        Ag(a, Ee),
        Ag(a, Fe)) : (c = bga(c),
        a = a.encoder_,
        b = c.JSC$6429_hi,
        Ag(a, c.JSC$6429_lo),
        Ag(a, b)))
    }
      , kga = function(a, b, c) {
        Cg(a, b, 2);
        zg(a.encoder_, c.length);
        Bg(a, a.encoder_.end());
        Bg(a, c)
    };
    var Dg = function(a, b, c, d) {
        this.$$binaryReaderFn = a;
        this.$$binaryWriterFn = b;
        this.$$isRepeated = c;
        this.$$isMsg = d
    };
    function lga(a) {
        return Array.isArray(a) ? a[0]instanceof Dg ? a : [mga, a] : [a, void 0]
    }
    function nga(a, b, c) {
        if (Array.isArray(b)) {
            var d = te(b);
            if (d & 4)
                return b;
            for (var e = 0, h = 0; e < b.length; e++) {
                var l = a(b[e]);
                l != null && (b[h++] = l)
            }
            h < e && (b.length = h);
            c && (ve(b, (d | 5) & -12289),
            d & 2 && Object.freeze(b));
            return b
        }
    }
    var oga = Symbol();
    function pga(a) {
        var b = a[oga];
        if (!b) {
            var c = qga(a)
              , d = rga(a)
              , e = d.deserializeBinaryMessageSet;
            b = e ? function(h, l) {
                return e(h, l, d)
            }
            : function(h, l) {
                for (; Lfa(l) && l.nextWireType_ != 4; ) {
                    var m = l.nextField_
                      , p = d[m];
                    if (!p) {
                        var q = d.extensions;
                        q && (q = q[m]) && (p = d[m] = sga(q))
                    }
                    p && p(l, h, m) || (p = l,
                    m = p.fieldCursor_,
                    tg(p),
                    p.discardUnknownFields ? p = void 0 : (q = p.decoder_.cursor_ - m,
                    p.decoder_.cursor_ = m,
                    p = Jfa(p.decoder_, q)),
                    m = h,
                    p && (De || (De = Symbol()),
                    (q = m[De]) ? q.push(p) : m[De] = [p]))
                }
                c === tga || c === Fg || c.onlySubmessages || (h[gea || (gea = Symbol())] = c)
            }
            ;
            a[oga] = b
        }
        return b
    }
    function sga(a) {
        a = lga(a);
        var b = a[0].$$binaryReaderFn;
        if (a = a[1]) {
            var c = pga(a)
              , d = rga(a).messageMetadata;
            return function(e, h, l) {
                return b(e, h, l, d, c)
            }
        }
        return b
    }
    var uga = function() {}, tga, Fg, Gg = Symbol();
    function vga(a, b, c) {
        var d = c[1];
        if (d) {
            var e = d[Gg];
            var h = e ? e.messageMetadata : af(d[0]);
            a[b] = e != null ? e : d
        }
        h && h === $e ? (a.mapFields || (a.mapFields = new Set)).add(b) : c[0] && (a.repeatedFields || (a.repeatedFields = new Set)).add(b)
    }
    function wga(a, b) {
        return [a.$$isRepeated, !b || b[0] > 0 ? void 0 : b]
    }
    function qga(a) {
        var b = a[Gg];
        if (b)
            return b;
        b = xga(a, a[Gg] = new uga, wga, wga, vga);
        if (!b.extensions && !b.repeatedFields && !b.mapFields) {
            var c = !0, d;
            for (d in b)
                isNaN(d) || (c = !1);
            c ? (af(a[0]) === $e ? Fg ? b = Fg : (b = new uga,
            b.messageMetadata = af(!0),
            b = Fg = b) : b = tga || (tga = new uga),
            b = a[Gg] = b) : b.onlySubmessages = !0
        }
        return b
    }
    function yga(a, b, c) {
        a[b] = c
    }
    function xga(a, b, c, d, e) {
        e = e === void 0 ? yga : e;
        b.messageMetadata = af(a[0]);
        var h = 0
          , l = a[++h];
        l && l.constructor === Object && (b.extensions = l,
        l = a[++h],
        typeof l === "function" && (b.deserializeBinaryMessageSet = l,
        b.makeMessageSetExtensionWriterFn = a[++h],
        l = a[++h]));
        for (var m = {}; Array.isArray(l) && typeof l[0] === "number" && l[0] > 0; ) {
            for (var p = 0; p < l.length; p++)
                m[l[p]] = l;
            l = a[++h]
        }
        for (p = 1; l !== void 0; ) {
            typeof l === "number" && (p += l,
            l = a[++h]);
            var q = void 0;
            if (l instanceof Dg)
                var r = l;
            else
                r = zga,
                h--;
            if (r.$$isMsg) {
                l = a[++h];
                q = a;
                var x = h;
                typeof l == "function" && (l = l(),
                q[x] = l);
                q = l
            }
            l = a[++h];
            x = p + 1;
            typeof l === "number" && l < 0 && (x -= l,
            l = a[++h]);
            for (; p < x; p++) {
                var z = m[p];
                e(b, p, q ? d(r, q, z) : c(r, z))
            }
        }
        return b
    }
    var Aga = Symbol();
    function Bga(a) {
        var b = a[Aga];
        if (!b) {
            var c = Hg(a);
            b = function(d, e) {
                return Cga(d, e, c)
            }
            ;
            a[Aga] = b
        }
        return b
    }
    var Dga = Symbol();
    function Ega(a) {
        return a.$$binaryWriterFn
    }
    function Fga(a, b) {
        var c, d, e = a.$$binaryWriterFn;
        return function(h, l, m) {
            return e(h, l, m, d || (d = Hg(b).messageMetadata), c || (c = Bga(b)))
        }
    }
    function Hg(a) {
        var b = a[Dga];
        if (b)
            return b;
        b = xga(a, a[Dga] = {}, Ega, Fga);
        Gga(a);
        return b
    }
    var Hga = Symbol();
    function Iga(a, b) {
        var c = a.$$binaryReaderFn;
        return b ? function(d, e, h) {
            return c(d, e, h, b)
        }
        : c
    }
    function Jga(a, b, c) {
        var d = a.$$binaryReaderFn, e, h;
        return function(l, m, p) {
            return d(l, m, p, h || (h = rga(b).messageMetadata), e || (e = pga(b)), c)
        }
    }
    function rga(a) {
        var b = a[Hga];
        if (b)
            return b;
        qga(a);
        b = xga(a, a[Hga] = {}, Iga, Jga);
        Gga(a);
        return b
    }
    function Gga(a) {
        Hga in a && Gg in a && Dga in a && (a.length = 0)
    }
    function Kga(a, b) {
        var c = a[b];
        if (c)
            return c;
        if (c = a.extensions)
            if (c = c[b]) {
                c = lga(c);
                var d = c[0].$$binaryWriterFn;
                if (c = c[1]) {
                    var e = Bga(c)
                      , h = Hg(c).messageMetadata;
                    c = (c = a.makeMessageSetExtensionWriterFn) ? c(h, e) : function(l, m, p) {
                        return d(l, m, p, h, e)
                    }
                } else
                    c = d;
                return a[b] = c
            }
    }
    function Cga(a, b, c) {
        for (var d = ue(a), e = +!!(d & 512) - 1, h = a.length, l = h + (d & 256 ? -1 : 0), m = d & 512 ? 1 : 0; m < l; m++) {
            var p = a[m];
            if (p != null) {
                var q = m - e
                  , r = Kga(c, q);
                r && r(b, p, q)
            }
        }
        if (d & 256) {
            d = a[h - 1];
            for (var x in d)
                e = +x,
                Number.isNaN(e) || (h = d[x],
                h != null && (l = Kga(c, e)) && l(b, h, e))
        }
        if (a = De ? a[De] : void 0)
            for (Bg(b, b.encoder_.end()),
            c = 0; c < a.length; c++)
                Bg(b, le(a[c]) || new Uint8Array(0))
    }
    function Ig(a, b) {
        return new Dg(a,b,!1,!1)
    }
    function Jg(a, b, c) {
        mf(a, ue(a), b, c)
    }
    function Lga(a, b, c) {
        b = pea(b);
        b != null && (Cg(a, c, 1),
        a = a.encoder_,
        c = kea || (kea = new DataView(new ArrayBuffer(8))),
        c.setFloat64(0, +b, !0),
        Ee = c.getUint32(0, !0),
        Fe = c.getUint32(4, !0),
        Ag(a, Ee),
        Ag(a, Fe))
    }
    function Kg(a, b, c) {
        a: if (b != null) {
            if (Le(b)) {
                if (typeof b === "string") {
                    b = Qe(b);
                    break a
                }
                if (typeof b === "number") {
                    b = Re(b);
                    break a
                }
            }
            b = void 0
        }
        b != null && (typeof b === "string" && ega(b),
        b != null && (Cg(a, c, 0),
        typeof b === "number" ? (a = a.encoder_,
        Ge(b),
        gga(a, Ee, Fe)) : (c = ega(b),
        gga(a.encoder_, c.JSC$6431_lo, c.JSC$6431_hi))))
    }
    function Mga(a, b, c) {
        b = Pe(b);
        b != null && b != null && (Cg(a, c, 0),
        hga(a.encoder_, b))
    }
    function Nga(a, b, c) {
        jga(a, c, Eea(b))
    }
    function Oga(a, b, c) {
        b = rea(b);
        b != null && (Cg(a, c, 0),
        a.encoder_.JSC$6433_buffer_.push(b ? 1 : 0))
    }
    function Pga(a, b, c) {
        b = Ve(b);
        b != null && kga(a, c, Mca(b))
    }
    function Lg(a, b, c, d, e) {
        b = b instanceof xg ? b.internalArray_ : Array.isArray(b) ? bf(b, d[0], d[1]) : void 0;
        if (b != null) {
            Cg(a, c, 2);
            c = a.encoder_.end();
            Bg(a, c);
            c.push(a.totalLength_);
            e(b, a);
            e = c.pop();
            for (e = a.totalLength_ + a.encoder_.length() - e; e > 127; )
                c.push(e & 127 | 128),
                e >>>= 7,
                a.totalLength_++;
            c.push(e);
            a.totalLength_++
        }
    }
    function Qga(a, b, c) {
        b = b == null || typeof b == "string" || he(b) || b instanceof je ? b : void 0;
        b != null && kga(a, c, Dfa(b).buffer)
    }
    function Rga(a, b, c) {
        b = Pe(b);
        b != null && (b = parseInt(b, 10),
        Cg(a, c, 0),
        hga(a.encoder_, b))
    }
    var Sga = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 1)
            return !1;
        Jg(b, c, Gfa(a.decoder_));
        return !0
    }, Lga), Tga = Ig(function(a, b, c, d) {
        if (a.nextWireType_ !== 1)
            return !1;
        Gf(b, c, d, Gfa(a.decoder_));
        return !0
    }, Lga), Uga = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 0)
            return !1;
        Jg(b, c, og(a.decoder_, oea));
        return !0
    }, Kg), Mg = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 0)
            return !1;
        Jg(b, c, og(a.decoder_, He));
        return !0
    }, Kg), Vga = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 0)
            return !1;
        a = og(a.decoder_, He);
        Jg(b, c, a === 0 ? void 0 : a);
        return !0
    }, Kg), Wga = Ig(function(a, b, c, d) {
        if (a.nextWireType_ !== 0)
            return !1;
        Gf(b, c, d, og(a.decoder_, He));
        return !0
    }, Kg), Ng = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 0)
            return !1;
        Jg(b, c, pg(a.decoder_));
        return !0
    }, Mga), Xga = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 0)
            return !1;
        a = pg(a.decoder_);
        Jg(b, c, a === 0 ? void 0 : a);
        return !0
    }, Mga), Yga = Ig(function(a, b, c, d) {
        if (a.nextWireType_ !== 0)
            return !1;
        Gf(b, c, d, pg(a.decoder_));
        return !0
    }, Mga), Zga = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 1)
            return !1;
        var d = a.decoder_;
        a = qg(d);
        d = qg(d);
        a = Ie(a, d);
        Jg(b, c, a);
        return !0
    }, Nga), $ga = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 1)
            return !1;
        Jg(b, c, Ffa(a.decoder_));
        return !0
    }, Nga), aha;
    aha = new Dg(function(a, b, c) {
        if (a.nextWireType_ !== 1 && a.nextWireType_ !== 2)
            return !1;
        b = jfa(b, ue(b), c, 2, !1);
        if (a.nextWireType_ == 2)
            for (c = pg(a.decoder_) >>> 0,
            c = a.decoder_.cursor_ + c; a.decoder_.cursor_ < c; )
                b.push(Ffa(a.decoder_));
        else
            b.push(Ffa(a.decoder_));
        return !0
    }
    ,function(a, b, c) {
        b = nga(Eea, b, !1);
        if (b != null)
            for (var d = 0; d < b.length; d++)
                jga(a, c, b[d])
    }
    ,!0,!1);
    var bha = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 5)
            return !1;
        Jg(b, c, qg(a.decoder_));
        return !0
    }, function(a, b, c) {
        b = uea(b);
        b != null && (Cg(a, c, 5),
        Ag(a.encoder_, b))
    }), Og = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 0)
            return !1;
        Jg(b, c, Hfa(a.decoder_));
        return !0
    }, Oga), cha = Ig(function(a, b, c, d) {
        if (a.nextWireType_ !== 0)
            return !1;
        Gf(b, c, d, Hfa(a.decoder_));
        return !0
    }, Oga), Pg = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 2)
            return !1;
        Jg(b, c, Mfa(a));
        return !0
    }, Pga), dha;
    dha = new Dg(function(a, b, c) {
        if (a.nextWireType_ !== 2)
            return !1;
        a = Mfa(a);
        qfa(b, c, rfa, a);
        return !0
    }
    ,function(a, b, c) {
        b = nga(Ve, b, !0);
        if (b != null)
            for (var d = 0; d < b.length; d++) {
                var e = a
                  , h = c
                  , l = b[d];
                l != null && kga(e, h, Mca(l))
            }
    }
    ,!0,!1);
    var eha = Ig(function(a, b, c, d) {
        if (a.nextWireType_ !== 2)
            return !1;
        Gf(b, c, d, Mfa(a));
        return !0
    }, Pga), mga = new Dg(function(a, b, c, d, e) {
        if (a.nextWireType_ !== 2)
            return !1;
        ug(a, xfa(b, d, c, !0), e);
        return !0
    }
    ,Lg,!1,!0), zga = new Dg(function(a, b, c, d, e) {
        if (a.nextWireType_ !== 2)
            return !1;
        ug(a, xfa(b, d, c), e);
        return !0
    }
    ,Lg,!1,!0), Qg;
    Qg = new Dg(function(a, b, c, d, e) {
        if (a.nextWireType_ !== 2)
            return !1;
        d = bf(void 0, d[0], d[1]);
        var h = ue(b);
        Ae(h);
        var l = jfa(b, h, c, 3);
        h = ue(b);
        te(l) & 4 && (l = ne(l),
        ve(l, (te(l) | 1) & -2079),
        mf(b, h, c, l));
        l.push(d);
        ug(a, d, e);
        return !0
    }
    ,function(a, b, c, d, e) {
        if (Array.isArray(b))
            for (var h = 0; h < b.length; h++)
                Lg(a, b[h], c, d, e)
    }
    ,!0,!0);
    var Rg = new Dg(function(a, b, c, d, e, h) {
        if (a.nextWireType_ !== 2)
            return !1;
        ufa(b, ue(b), h, c);
        b = xfa(b, d, c);
        ug(a, b, e);
        return !0
    }
    ,Lg,!1,!0)
      , fha = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 2)
            return !1;
        Jg(b, c, Nfa(a));
        return !0
    }, Qga)
      , gha = Ig(function(a, b, c, d) {
        if (a.nextWireType_ !== 2)
            return !1;
        Gf(b, c, d, Nfa(a));
        return !0
    }, Qga)
      , hha = Ig(function(a, b, c, d) {
        if (a.nextWireType_ !== 0)
            return !1;
        Gf(b, c, d, pg(a.decoder_) >>> 0);
        return !0
    }, function(a, b, c) {
        b = uea(b);
        b != null && b != null && (Cg(a, c, 0),
        zg(a.encoder_, b))
    })
      , Sg = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 0)
            return !1;
        Jg(b, c, pg(a.decoder_));
        return !0
    }, Rga)
      , iha = Ig(function(a, b, c) {
        if (a.nextWireType_ !== 0)
            return !1;
        a = pg(a.decoder_);
        Jg(b, c, a === 0 ? void 0 : a);
        return !0
    }, Rga)
      , jha = Ig(function(a, b, c, d) {
        if (a.nextWireType_ !== 0)
            return !1;
        Gf(b, c, d, pg(a.decoder_));
        return !0
    }, Rga);
    function Tg(a) {
        a.isGuard_doNotManuallySetPrettyPlease = !0;
        return a
    }
    var kha = Tg(function(a) {
        return a !== null && a !== void 0
    });
    function lha(a) {
        return a == null ? a : Qda(a)
    }
    function Ug(a, b) {
        return function(c, d) {
            if (sg.length) {
                var e = sg.pop();
                Kfa(e, d);
                e.decoder_.init(c, void 0, void 0, d);
                c = e
            } else
                c = new rg(c,d);
            try {
                var h = new a
                  , l = h.internalArray_;
                pga(b)(l, c);
                var m = h
            } finally {
                c.free()
            }
            return m
        }
    }
    function Vg(a) {
        return function() {
            var b = new iga;
            Cga(this.internalArray_, b, Hg(a));
            Bg(b, b.encoder_.end());
            for (var c = new Uint8Array(b.totalLength_), d = b.blocks_, e = d.length, h = 0, l = 0; l < e; l++) {
                var m = d[l];
                c.set(m, h);
                h += m.length
            }
            b.blocks_ = [c];
            return c
        }
    }
    function mha(a) {
        return Tg(function(b) {
            return b instanceof a && !(te(b.internalArray_) & 2)
        })
    }
    function Wg(a) {
        return function(b) {
            return Zfa(a, b)
        }
    }
    ;var Xg = window;
    xb("csi.gstatic.com");
    xb("googleads.g.doubleclick.net");
    xb("partner.googleadservices.com");
    xb("pubads.g.doubleclick.net");
    xb("securepubads.g.doubleclick.net");
    xb("tpc.googlesyndication.com");
    var Yg = function() {}
      , fc = function(a) {
        return a
    }
      , nha = function(a) {
        var b = b || 0;
        return function() {
            return a.apply(this, Array.prototype.slice.call(arguments, 0, b))
        }
    }
      , Zg = function(a) {
        var b = !1, c;
        return function() {
            b || (c = a(),
            b = !0);
            return c
        }
    }
      , $g = function(a, b) {
        var c = 0;
        return function(d) {
            Na.clearTimeout(c);
            var e = arguments;
            c = Na.setTimeout(function() {
                a.apply(void 0, e)
            }, b)
        }
    };
    try {
        new self.OffscreenCanvas(0,0).getContext("2d")
    } catch (a) {}
    ;function ah(a) {
        return new rba(a[0].toLowerCase())
    }
    ;function oha(a) {
        var b = b === void 0 ? {} : b;
        if (a instanceof vc)
            return a;
        a = String(a).replace(/&/g, "&amp;").replace(/</g, "&lt;").replace(/>/g, "&gt;").replace(/"/g, "&quot;").replace(/'/g, "&apos;");
        b.preserveSpaces && (a = a.replace(/(^|[\r\n\t ]) /g, "$1&#160;"));
        b.preserveNewlines && (a = a.replace(/(\r\n|\n|\r)/g, "<br>"));
        b.preserveTabs && (a = a.replace(/(\t+)/g, "<span style=\"white-space:pre\">$1</span>"));
        return xc(a)
    }
    ;function pha(a, b) {
        var c = b.createRange();
        c.selectNode(b.body);
        a = xc(a);
        return c.createContextualFragment(wc(a))
    }
    ;function qha(a) {
        a = a.nodeName;
        return typeof a === "string" ? a : "FORM"
    }
    function rha(a) {
        a = a.nodeType;
        return a === 1 || typeof a !== "number"
    }
    ;function sha(a) {
        try {
            return new URL(a,window.document.baseURI)
        } catch (b) {
            return new URL("about:invalid")
        }
    }
    ;var bh = function(a, b, c, d) {
        this.allowedElements = a;
        this.elementPolicies = b;
        this.allowedGlobalAttributes = c;
        this.globalAttributePolicies = d
    };
    var tha = "ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ")
      , uha = [["A", new Map([["href", {
        policyAction: 2
    }]])], ["AREA", new Map([["href", {
        policyAction: 2
    }]])], ["LINK", new Map([["href", {
        policyAction: 5,
        conditions: new Map([["rel", new Set("alternate author bookmark canonical cite help icon license next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" "))]])
    }]])], ["SOURCE", new Map([["src", {
        policyAction: 5
    }], ["srcset", {
        policyAction: 6
    }]])], ["IMG", new Map([["src", {
        policyAction: 5
    }], ["srcset", {
        policyAction: 6
    }]])], ["VIDEO", new Map([["src", {
        policyAction: 5
    }]])], ["AUDIO", new Map([["src", {
        policyAction: 5
    }]])]]
      , vha = "title aria-atomic aria-autocomplete aria-busy aria-checked aria-current aria-disabled aria-dropeffect aria-expanded aria-haspopup aria-hidden aria-invalid aria-label aria-level aria-live aria-multiline aria-multiselectable aria-orientation aria-posinset aria-pressed aria-readonly aria-relevant aria-required aria-selected aria-setsize aria-sort aria-valuemax aria-valuemin aria-valuenow aria-valuetext alt align autocapitalize autocomplete autocorrect autofocus autoplay bgcolor border cellpadding cellspacing checked color cols colspan controls datetime disabled download draggable enctype face formenctype frameborder height hreflang hidden ismap label lang loop max maxlength media minlength min multiple muted nonce open placeholder preload rel required reversed role rows rowspan selected shape size sizes slot span spellcheck start step summary translate type valign value width wrap itemscope itemtype itemid itemprop itemref".split(" ")
      , wha = [["dir", {
        policyAction: 3,
        conditions: sb(function() {
            return new Map([["dir", new Set(["auto", "ltr", "rtl"])]])
        })
    }], ["async", {
        policyAction: 3,
        conditions: sb(function() {
            return new Map([["async", new Set(["async"])]])
        })
    }], ["cite", {
        policyAction: 2
    }], ["loading", {
        policyAction: 3,
        conditions: sb(function() {
            return new Map([["loading", new Set(["eager", "lazy"])]])
        })
    }], ["poster", {
        policyAction: 2
    }], ["target", {
        policyAction: 3,
        conditions: sb(function() {
            return new Map([["target", new Set(["_self", "_blank"])]])
        })
    }]]
      , xha = new bh(new Set(tha),new Map(uha),new Set(vha),new Map(wha))
      , yha = new bh(new Set(tha.concat(["BUTTON", "INPUT"])),new Map(uha),new Set(sb(function() {
        return vha.concat(["class", "id", "name"])
    })),new Map(sb(function() {
        return wha.concat([["style", {
            policyAction: 1
        }]])
    })));
    var zha = function(a, b, c, d) {
        this.JSC$6466_sanitizerTable = a;
        this.styleElementSanitizer = b;
        this.styleAttributeSanitizer = c;
        this.JSC$6466_resourceUrlPolicy = d;
        this.changes = []
    }
      , Bha = function(a, b) {
        var c = document.implementation.createHTMLDocument("");
        a = Aha(a, b, c);
        c = c.body;
        c.appendChild(a);
        c = new XMLSerializer().serializeToString(c);
        c = c.slice(c.indexOf(">") + 1, c.lastIndexOf("</"));
        return xc(c)
    }
      , Aha = function(a, b, c) {
        b = pha(b, c);
        b = document.createTreeWalker(b, 5, function(m) {
            if (m.nodeType === 3)
                m = 1;
            else if (rha(m)) {
                if (m = qha(m),
                m === null)
                    m = 2;
                else {
                    var p = a.JSC$6466_sanitizerTable;
                    m = m !== "FORM" && (p.allowedElements.has(m) || p.elementPolicies.has(m)) ? 1 : 2
                }
            } else
                m = 2;
            return m
        });
        for (var d = b.nextNode(), e = c.createDocumentFragment(), h = e; d !== null; ) {
            var l = void 0;
            if (d.nodeType === 3)
                a.styleElementSanitizer && h.nodeName === "STYLE" ? (d = a.styleElementSanitizer(d.data),
                l = a.createTextNode(d)) : l = a.createTextNode(d.data);
            else if (rha(d))
                l = Cha(a, d, c);
            else
                throw Error("");
            h.appendChild(l);
            if (d = b.firstChild())
                h = l;
            else
                for (; !(d = b.nextSibling()) && (d = b.parentNode()); )
                    h = h.parentNode
        }
        return e
    };
    zha.prototype.createTextNode = function(a) {
        return document.createTextNode(a)
    }
    ;
    var Cha = function(a, b, c) {
        var d = qha(b);
        c = c.createElement(d);
        b = b.attributes;
        for (var e = g(b), h = e.next(); !h.done; h = e.next()) {
            var l = h.value;
            h = l.name;
            l = l.value;
            var m = a.JSC$6466_sanitizerTable;
            var p = m.elementPolicies.get(d);
            m = (p == null ? 0 : p.has(h)) ? p.get(h) : m.allowedGlobalAttributes.has(h) ? {
                policyAction: 1
            } : (m = m.globalAttributePolicies.get(h)) ? m : {
                policyAction: 0
            };
            a: {
                if (p = m.conditions) {
                    p = g(p);
                    for (var q = p.next(); !q.done; q = p.next()) {
                        var r = g(q.value);
                        q = r.next().value;
                        r = r.next().value;
                        var x = void 0;
                        if ((q = (x = b.getNamedItem(q)) == null ? void 0 : x.value) && !r.has(q)) {
                            p = !1;
                            break a
                        }
                    }
                }
                p = !0
            }
            if (p)
                switch (m.policyAction) {
                case 1:
                    ch(c, h, l);
                    break;
                case 2:
                    m = oba(l);
                    l = m !== void 0 && pba.indexOf(m.toLowerCase()) !== -1 ? l : "about:invalid#zClosurez";
                    ch(c, h, l);
                    break;
                case 3:
                    ch(c, h, l.toLowerCase());
                    break;
                case 4:
                    a.styleAttributeSanitizer ? (l = a.styleAttributeSanitizer(l),
                    ch(c, h, l)) : ch(c, h, l);
                    break;
                case 5:
                    a.JSC$6466_resourceUrlPolicy ? (m = {
                        type: 2,
                        attributeName: h,
                        elementName: d
                    },
                    l = sha(l),
                    (l = a.JSC$6466_resourceUrlPolicy(l, m)) && ch(c, h, l.toString())) : ch(c, h, l);
                    break;
                case 6:
                    if (a.JSC$6466_resourceUrlPolicy) {
                        m = {
                            type: 2,
                            attributeName: h,
                            elementName: d
                        };
                        p = [];
                        l = g(l.split(","));
                        for (q = l.next(); !q.done; q = l.next())
                            r = g(q.value.trim().split(/\s+/, 2)),
                            q = r.next().value,
                            r = r.next().value,
                            p.push({
                                url: q,
                                descriptor: r
                            });
                        l = {
                            parts: []
                        };
                        p = g(p);
                        for (q = p.next(); !q.done; q = p.next())
                            q = q.value,
                            r = sha(q.url),
                            (r = a.JSC$6466_resourceUrlPolicy(r, m)) && l.parts.push({
                                url: r.toString(),
                                descriptor: q.descriptor
                            });
                        ch(c, h, Dha(l))
                    } else
                        ch(c, h, l);
                }
        }
        return c
    };
    function ch(a, b, c) {
        a.setAttribute(b, c)
    }
    function Dha(a) {
        return a.parts.map(function(b) {
            var c = b.descriptor;
            return "" + b.url + (c ? " " + c : "")
        }).join(" , ")
    }
    var Eha = sb(function() {
        return new zha(yha)
    });
    var Fha = function() {
        this.calledBuild = !1;
        this.JSC$6479_sanitizerTable = xha
    };
    Fha.prototype.build = function() {
        if (this.calledBuild)
            throw Error("this sanitizer has already called build");
        this.calledBuild = !0;
        return new zha(this.JSC$6479_sanitizerTable,void 0,void 0,this.JSC$6479_resourceUrlPolicy)
    }
    ;
    function Gha(a) {
        var b = a.split(/\?|#/)
          , c = /\?/.test(a) ? "?" + b[1] : "";
        return {
            path: b[0],
            params: c,
            hash: /#/.test(a) ? "#" + (c ? b[2] : b[1]) : ""
        }
    }
    function fh(a) {
        var b = Fa.apply(1, arguments);
        if (b.length === 0)
            return Db(a[0]);
        for (var c = a[0], d = 0; d < b.length; d++)
            c += encodeURIComponent(b[d]) + a[d + 1];
        return Db(c)
    }
    function gh(a, b) {
        a = Gha(Ab(a).toString());
        var c = a.params
          , d = c.length ? "&" : "?";
        b.forEach(function(e, h) {
            e = e instanceof Array ? e : [e];
            for (var l = 0; l < e.length; l++) {
                var m = e[l];
                m !== null && m !== void 0 && (c += d + encodeURIComponent(h) + "=" + encodeURIComponent(String(m)),
                d = "&")
            }
        });
        return Db(a.path + c + a.hash)
    }
    ;function hh(a) {
        for (var b = Fa.apply(1, arguments), c = a[0], d = 0; d < a.length - 1; d++)
            c += String(b[d]) + a[d + 1];
        if (/[<>]/.test(c))
            throw Error("Forbidden characters in style string: " + c);
        return tc(c)
    }
    ;var Hha = Zg(function() {
        var a = document.createElement("div")
          , b = document.createElement("div");
        b.appendChild(document.createElement("div"));
        a.appendChild(b);
        b = a.firstChild.firstChild;
        a.innerHTML = wc(Yba);
        return !b.parentElement
    })
      , Iha = function(a) {
        if (Hha())
            for (; a.lastChild; )
                a.removeChild(a.lastChild);
        a.innerHTML = wc(Yba)
    }
      , Kha = function(a, b) {
        a: {
            var c = (a.ownerDocument && a.ownerDocument.defaultView || Na).document;
            if (c.querySelector && (c = c.querySelector("script[nonce]")) && (c = c.nonce || c.getAttribute("nonce")) && Jha.test(c))
                break a;
            c = ""
        }
        c && a.setAttribute("nonce", c);
        a.src = Ab(b)
    }
      , Lha = function(a, b, c, d) {
        a = ih(a);
        b = b || Na;
        c = c instanceof tb ? vb(c) : c || "";
        return d !== void 0 ? b.open(a, c, d) : b.open(a, c)
    }
      , Jha = /^[\w+/_-]+[=]{0,2}$/
      , ih = function(a) {
        a = Ub(a);
        return a === void 0 ? Hb.toString() : a
    };
    var jh = function(a, b, c) {
        return Math.min(Math.max(a, b), c)
    }
      , kh = function(a, b, c) {
        return a + c * (b - a)
    }
      , Mha = function(a, b, c) {
        return Math.abs(a - b) <= (c || 1E-6)
    };
    var lh = function(a, b) {
        this.x = a !== void 0 ? a : 0;
        this.y = b !== void 0 ? b : 0
    };
    f = lh.prototype;
    f.clone = function() {
        return new lh(this.x,this.y)
    }
    ;
    f.equals = function(a) {
        return a instanceof lh && (this == a ? !0 : this && a ? this.x == a.x && this.y == a.y : !1)
    }
    ;
    f.ceil = function() {
        this.x = Math.ceil(this.x);
        this.y = Math.ceil(this.y);
        return this
    }
    ;
    f.floor = function() {
        this.x = Math.floor(this.x);
        this.y = Math.floor(this.y);
        return this
    }
    ;
    f.round = function() {
        this.x = Math.round(this.x);
        this.y = Math.round(this.y);
        return this
    }
    ;
    f.translate = function(a, b) {
        a instanceof lh ? (this.x += a.x,
        this.y += a.y) : (this.x += Number(a),
        typeof b === "number" && (this.y += b));
        return this
    }
    ;
    f.scale = function(a, b) {
        this.x *= a;
        this.y *= typeof b === "number" ? b : a;
        return this
    }
    ;
    var mh = function(a, b) {
        this.width = a;
        this.height = b
    }
      , Nha = function(a, b) {
        return a == b ? !0 : a && b ? a.width == b.width && a.height == b.height : !1
    };
    f = mh.prototype;
    f.clone = function() {
        return new mh(this.width,this.height)
    }
    ;
    f.area = function() {
        return this.width * this.height
    }
    ;
    f.aspectRatio = function() {
        return this.width / this.height
    }
    ;
    f.isEmpty = function() {
        return !this.area()
    }
    ;
    f.ceil = function() {
        this.width = Math.ceil(this.width);
        this.height = Math.ceil(this.height);
        return this
    }
    ;
    f.floor = function() {
        this.width = Math.floor(this.width);
        this.height = Math.floor(this.height);
        return this
    }
    ;
    f.round = function() {
        this.width = Math.round(this.width);
        this.height = Math.round(this.height);
        return this
    }
    ;
    f.scale = function(a, b) {
        this.width *= a;
        this.height *= typeof b === "number" ? b : a;
        return this
    }
    ;
    var ph = function(a) {
        return a ? new nh(oh(a)) : Faa || (Faa = new nh)
    }
      , qh = function(a, b) {
        return typeof b === "string" ? a.getElementById(b) : b
    }
      , rh = function(a, b) {
        return (b || document).getElementsByTagName(String(a))
    }
      , Pha = function(a) {
        return Oha("yt-formatted-string", "paper-input-input", a)
    }
      , uh = function(a, b, c, d) {
        a = d || a;
        b = b && b != "*" ? String(b).toUpperCase() : "";
        if (a.querySelectorAll && a.querySelector && (b || c))
            return a.querySelectorAll(b + (c ? "." + c : ""));
        if (c && a.getElementsByClassName) {
            a = a.getElementsByClassName(c);
            if (b) {
                d = {};
                for (var e = 0, h = 0, l; l = a[h]; h++)
                    b == l.nodeName && (d[e++] = l);
                d.length = e;
                return d
            }
            return a
        }
        a = a.getElementsByTagName(b || "*");
        if (c) {
            d = {};
            for (h = e = 0; l = a[h]; h++)
                b = l.className,
                typeof b.split == "function" && hc(b.split(/\s+/), c) && (d[e++] = l);
            d.length = e;
            return d
        }
        return a
    }
      , Oha = function(a, b, c) {
        var d = document
          , e = c || d
          , h = a && a != "*" ? String(a).toUpperCase() : "";
        return e.querySelectorAll && e.querySelector && (h || b) ? e.querySelector(h + (b ? "." + b : "")) : uh(d, a, b, c)[0] || null
    }
      , Rha = function(a, b) {
        pc.forEach(b, function(c, d) {
            d == "style" ? a.style.cssText = c : d == "class" ? a.className = c : d == "for" ? a.htmlFor = c : Qha.hasOwnProperty(d) ? a.setAttribute(Qha[d], c) : lb(d, "aria-") || lb(d, "data-") ? a.setAttribute(d, c) : a[d] = c
        })
    }
      , Qha = {
        cellpadding: "cellPadding",
        cellspacing: "cellSpacing",
        colspan: "colSpan",
        frameborder: "frameBorder",
        height: "height",
        maxlength: "maxLength",
        nonce: "nonce",
        role: "role",
        rowspan: "rowSpan",
        type: "type",
        usemap: "useMap",
        valign: "vAlign",
        width: "width"
    }
      , vh = function(a) {
        a = (a || window).document;
        a = a.compatMode == "CSS1Compat" ? a.documentElement : a.body;
        return new mh(a.clientWidth,a.clientHeight)
    }
      , xh = function(a) {
        var b = wh(a);
        a = a.parentWindow || a.defaultView;
        return new lh(a.pageXOffset || b.scrollLeft,a.pageYOffset || b.scrollTop)
    }
      , wh = function(a) {
        return a.scrollingElement ? a.scrollingElement : Zd || a.compatMode != "CSS1Compat" ? a.body || a.documentElement : a.documentElement
    }
      , yh = function(a) {
        return a ? a.parentWindow || a.defaultView : window
    }
      , zh = function(a, b, c) {
        return Sha(document, arguments)
    }
      , Sha = function(a, b) {
        var c = b[1]
          , d = Tha(a, String(b[0]));
        c && (typeof c === "string" ? d.className = c : Array.isArray(c) ? d.className = c.join(" ") : Rha(d, c));
        b.length > 2 && Uha(a, d, b, 2);
        return d
    }
      , Uha = function(a, b, c, d) {
        function e(m) {
            m && b.appendChild(typeof m === "string" ? a.createTextNode(m) : m)
        }
        for (; d < c.length; d++) {
            var h = c[d];
            if (!Ya(h) || $a(h) && h.nodeType > 0)
                e(h);
            else {
                a: {
                    if (h && typeof h.length == "number") {
                        if ($a(h)) {
                            var l = typeof h.item == "function" || typeof h.item == "string";
                            break a
                        }
                        if (typeof h === "function") {
                            l = typeof h.item == "function";
                            break a
                        }
                    }
                    l = !1
                }
                Zb(l ? lc(h) : h, e)
            }
        }
    }
      , Bh = function(a) {
        return Tha(document, a)
    }
      , Tha = function(a, b) {
        b = String(b);
        a.contentType === "application/xhtml+xml" && (b = b.toLowerCase());
        return a.createElement(b)
    }
      , Ch = function() {
        return document.createTextNode("\n")
    }
      , Dh = function(a) {
        if (a.nodeType != 1)
            return !1;
        switch (a.tagName) {
        case "APPLET":
        case "AREA":
        case "BASE":
        case "BR":
        case "COL":
        case "COMMAND":
        case "EMBED":
        case "FRAME":
        case "HR":
        case "IMG":
        case "INPUT":
        case "IFRAME":
        case "ISINDEX":
        case "KEYGEN":
        case "LINK":
        case "NOFRAMES":
        case "NOSCRIPT":
        case "META":
        case "OBJECT":
        case "PARAM":
        case "SCRIPT":
        case "SOURCE":
        case "STYLE":
        case "TRACK":
        case "WBR":
            return !1;
        }
        return !0
    }
      , Vha = function(a, b) {
        Uha(oh(a), a, arguments, 1)
    }
      , Eh = function(a) {
        for (var b; b = a.firstChild; )
            a.removeChild(b)
    }
      , Fh = function(a, b) {
        b.parentNode && b.parentNode.insertBefore(a, b)
    }
      , Gh = function(a, b) {
        b.parentNode && b.parentNode.insertBefore(a, b.nextSibling)
    }
      , Hh = function(a, b) {
        a.insertBefore(b, a.childNodes[0] || null)
    }
      , Ih = function(a) {
        return a && a.parentNode ? a.parentNode.removeChild(a) : null
    }
      , Wha = function(a, b) {
        var c = b.parentNode;
        c && c.replaceChild(a, b)
    }
      , Xha = function(a) {
        var b, c = a.parentNode;
        if (c && c.nodeType != 11)
            if (a.removeNode)
                a.removeNode(!1);
            else {
                for (; b = a.firstChild; )
                    c.insertBefore(b, a);
                Ih(a)
            }
    }
      , Jh = function(a) {
        return a.children != void 0 ? a.children : Array.prototype.filter.call(a.childNodes, function(b) {
            return b.nodeType == 1
        })
    }
      , Zha = function(a) {
        return a.nextElementSibling !== void 0 ? a.nextElementSibling : Yha(a.nextSibling, !0)
    }
      , $ha = function(a) {
        return a.previousElementSibling !== void 0 ? a.previousElementSibling : Yha(a.previousSibling, !1)
    }
      , Yha = function(a, b) {
        for (; a && a.nodeType != 1; )
            a = b ? a.nextSibling : a.previousSibling;
        return a
    }
      , Kh = function(a) {
        return $a(a) && a.nodeType == 1
    }
      , aia = function(a) {
        var b;
        if (b = a.parentElement)
            return b;
        b = a.parentNode;
        return Kh(b) ? b : null
    }
      , Lh = function(a, b) {
        if (!a || !b)
            return !1;
        if (a.contains && b.nodeType == 1)
            return a == b || a.contains(b);
        if (typeof a.compareDocumentPosition != "undefined")
            return a == b || !!(a.compareDocumentPosition(b) & 16);
        for (; b && a != b; )
            b = b.parentNode;
        return b == a
    }
      , dia = function(a, b) {
        if (a == b)
            return 0;
        if (a.compareDocumentPosition)
            return a.compareDocumentPosition(b) & 2 ? 1 : -1;
        if ("sourceIndex"in a || a.parentNode && "sourceIndex"in a.parentNode) {
            var c = a.nodeType == 1
              , d = b.nodeType == 1;
            if (c && d)
                return a.sourceIndex - b.sourceIndex;
            var e = a.parentNode
              , h = b.parentNode;
            return e == h ? bia(a, b) : !c && Lh(e, b) ? -1 * cia(a, b) : !d && Lh(h, a) ? cia(b, a) : (c ? a.sourceIndex : e.sourceIndex) - (d ? b.sourceIndex : h.sourceIndex)
        }
        d = oh(a);
        c = d.createRange();
        c.selectNode(a);
        c.collapse(!0);
        a = d.createRange();
        a.selectNode(b);
        a.collapse(!0);
        return c.compareBoundaryPoints(Na.Range.START_TO_END, a)
    }
      , cia = function(a, b) {
        var c = a.parentNode;
        if (c == b)
            return -1;
        for (; b.parentNode != c; )
            b = b.parentNode;
        return bia(b, a)
    }
      , bia = function(a, b) {
        for (; b = b.previousSibling; )
            if (b == a)
                return -1;
        return 1
    }
      , eia = function(a) {
        var b, c = arguments.length;
        if (!c)
            return null;
        if (c == 1)
            return arguments[0];
        var d = []
          , e = Infinity;
        for (b = 0; b < c; b++) {
            for (var h = [], l = arguments[b]; l; )
                h.unshift(l),
                l = l.parentNode;
            d.push(h);
            e = Math.min(e, h.length)
        }
        h = null;
        for (b = 0; b < e; b++) {
            l = d[0][b];
            for (var m = 1; m < c; m++)
                if (l != d[m][b])
                    return h;
            h = l
        }
        return h
    }
      , oh = function(a) {
        return a.nodeType == 9 ? a : a.ownerDocument || a.document
    }
      , Mh = function(a) {
        return a.contentDocument || a.contentWindow.document
    }
      , Nh = function(a, b) {
        if ("textContent"in a)
            a.textContent = b;
        else if (a.nodeType == 3)
            a.data = String(b);
        else if (a.firstChild && a.firstChild.nodeType == 3) {
            for (; a.lastChild != a.firstChild; )
                a.removeChild(a.lastChild);
            a.firstChild.data = String(b)
        } else
            Eh(a),
            a.appendChild(oh(a).createTextNode(String(b)))
    }
      , fia = {
        SCRIPT: 1,
        STYLE: 1,
        HEAD: 1,
        IFRAME: 1,
        OBJECT: 1
    }
      , gia = {
        IMG: " ",
        BR: "\n"
    }
      , hia = function(a) {
        a = a.tabIndex;
        return typeof a === "number" && a >= 0 && a < 32768
    }
      , jia = function(a) {
        var b = [];
        iia(a, b, !0);
        a = b.join("");
        a = a.replace(/ \xAD /g, " ").replace(/\xAD/g, "");
        a = a.replace(/\u200B/g, "");
        a = a.replace(/ +/g, " ");
        a != " " && (a = a.replace(/^\s*/, ""));
        return a
    }
      , kia = function(a) {
        var b = [];
        iia(a, b, !1);
        return b.join("")
    }
      , iia = function(a, b, c) {
        if (!(a.nodeName in fia))
            if (a.nodeType == 3)
                c ? b.push(String(a.nodeValue).replace(/(\r\n|\r|\n)/g, "")) : b.push(a.nodeValue);
            else if (a.nodeName in gia)
                b.push(gia[a.nodeName]);
            else
                for (a = a.firstChild; a; )
                    iia(a, b, c),
                    a = a.nextSibling
    }
      , Ph = function(a, b, c) {
        if (!b && !c)
            return null;
        var d = b ? String(b).toUpperCase() : null;
        return Oh(a, function(e) {
            return (!d || e.nodeName == d) && (!c || typeof e.className === "string" && hc(e.className.split(/\s+/), c))
        }, !0)
    }
      , Oh = function(a, b, c) {
        a && !c && (a = a.parentNode);
        for (c = 0; a; ) {
            if (b(a))
                return a;
            a = a.parentNode;
            c++
        }
        return null
    }
      , nh = function(a) {
        this.JSC$6495_document_ = a || Na.document || document
    };
    f = nh.prototype;
    f.getElement = function(a) {
        return qh(this.JSC$6495_document_, a)
    }
    ;
    f.$ = nh.prototype.getElement;
    f.getElementsByTagName = function(a, b) {
        return (b || this.JSC$6495_document_).getElementsByTagName(String(a))
    }
    ;
    f.getElementsByTagNameAndClass = function(a, b, c) {
        return uh(this.JSC$6495_document_, a, b, c)
    }
    ;
    f.$$ = nh.prototype.getElementsByTagNameAndClass;
    f.setProperties = Rha;
    f.JSC$6497_createDom = function(a, b, c) {
        return Sha(this.JSC$6495_document_, arguments)
    }
    ;
    f.createElement = function(a) {
        return Tha(this.JSC$6495_document_, a)
    }
    ;
    f.createTextNode = function(a) {
        return this.JSC$6495_document_.createTextNode(String(a))
    }
    ;
    var Qh = function(a) {
        a = a.JSC$6495_document_;
        return a.parentWindow || a.defaultView
    };
    f = nh.prototype;
    f.appendChild = function(a, b) {
        a.appendChild(b)
    }
    ;
    f.append = Vha;
    f.canHaveChildren = Dh;
    f.removeNode = Ih;
    f.getChildren = Jh;
    f.contains = Lh;
    var mia = function() {
        return Cd && Ed ? Ed.mobile : !lia() && (Hd("iPod") || Hd("iPhone") || Hd("Android") || Hd("IEMobile"))
    }
      , lia = function() {
        return Cd && Ed ? !Ed.mobile && (Hd("iPad") || Hd("Android") || Hd("Silk")) : Hd("iPad") || Hd("Android") && !Hd("Mobile") || Hd("Silk")
    };
    var Rh = function(a) {
        try {
            return !!a && a.location.href != null && Ud(a, "foo")
        } catch (b) {
            return !1
        }
    }
      , oia = function(a) {
        var b = nia;
        if (b)
            for (var c in b)
                Object.prototype.hasOwnProperty.call(b, c) && a(b[c], c, b)
    }
      , pia = function() {
        var a = [];
        oia(function(b) {
            a.push(b)
        });
        return a
    }
      , nia = {
        ALLOW_FORMS: "allow-forms",
        ALLOW_MODALS: "allow-modals",
        ALLOW_ORIENTATION_LOCK: "allow-orientation-lock",
        ALLOW_POINTER_LOCK: "allow-pointer-lock",
        ALLOW_POPUPS: "allow-popups",
        ALLOW_POPUPS_TO_ESCAPE_SANDBOX: "allow-popups-to-escape-sandbox",
        ALLOW_PRESENTATION: "allow-presentation",
        ALLOW_SAME_ORIGIN: "allow-same-origin",
        ALLOW_SCRIPTS: "allow-scripts",
        ALLOW_TOP_NAVIGATION: "allow-top-navigation",
        ALLOW_TOP_NAVIGATION_BY_USER_ACTIVATION: "allow-top-navigation-by-user-activation"
    }
      , qia = Zg(function() {
        return pia()
    })
      , sia = function() {
        var a = ria("IFRAME")
          , b = {};
        Zb(qia(), function(c) {
            a.sandbox && a.sandbox.supports && a.sandbox.supports(c) && (b[c] = !0)
        });
        return b
    }
      , ria = function(a, b) {
        b = b === void 0 ? document : b;
        return b.createElement(String(a).toLowerCase())
    };
    var Sh = function(a, b, c, d) {
        this.top = a;
        this.right = b;
        this.bottom = c;
        this.left = d
    };
    f = Sh.prototype;
    f.getWidth = function() {
        return this.right - this.left
    }
    ;
    f.getHeight = function() {
        return this.bottom - this.top
    }
    ;
    f.clone = function() {
        return new Sh(this.top,this.right,this.bottom,this.left)
    }
    ;
    f.contains = function(a) {
        return this && a ? a instanceof Sh ? a.left >= this.left && a.right <= this.right && a.top >= this.top && a.bottom <= this.bottom : a.x >= this.left && a.x <= this.right && a.y >= this.top && a.y <= this.bottom : !1
    }
    ;
    f.expand = function(a, b, c, d) {
        $a(a) ? (this.top -= a.top,
        this.right += a.right,
        this.bottom += a.bottom,
        this.left -= a.left) : (this.top -= a,
        this.right += Number(b),
        this.bottom += Number(c),
        this.left -= Number(d));
        return this
    }
    ;
    f.ceil = function() {
        this.top = Math.ceil(this.top);
        this.right = Math.ceil(this.right);
        this.bottom = Math.ceil(this.bottom);
        this.left = Math.ceil(this.left);
        return this
    }
    ;
    f.floor = function() {
        this.top = Math.floor(this.top);
        this.right = Math.floor(this.right);
        this.bottom = Math.floor(this.bottom);
        this.left = Math.floor(this.left);
        return this
    }
    ;
    f.round = function() {
        this.top = Math.round(this.top);
        this.right = Math.round(this.right);
        this.bottom = Math.round(this.bottom);
        this.left = Math.round(this.left);
        return this
    }
    ;
    f.translate = function(a, b) {
        a instanceof lh ? (this.left += a.x,
        this.right += a.x,
        this.top += a.y,
        this.bottom += a.y) : (this.left += a,
        this.right += a,
        typeof b === "number" && (this.top += b,
        this.bottom += b));
        return this
    }
    ;
    f.scale = function(a, b) {
        b = typeof b === "number" ? b : a;
        this.left *= a;
        this.right *= a;
        this.top *= b;
        this.bottom *= b;
        return this
    }
    ;
    var Th = function(a, b, c, d) {
        this.left = a;
        this.top = b;
        this.width = c;
        this.height = d
    };
    f = Th.prototype;
    f.clone = function() {
        return new Th(this.left,this.top,this.width,this.height)
    }
    ;
    f.boundingRect = function(a) {
        var b = Math.max(this.left + this.width, a.left + a.width)
          , c = Math.max(this.top + this.height, a.top + a.height);
        this.left = Math.min(this.left, a.left);
        this.top = Math.min(this.top, a.top);
        this.width = b - this.left;
        this.height = c - this.top
    }
    ;
    f.contains = function(a) {
        return a instanceof lh ? a.x >= this.left && a.x <= this.left + this.width && a.y >= this.top && a.y <= this.top + this.height : this.left <= a.left && this.left + this.width >= a.left + a.width && this.top <= a.top && this.top + this.height >= a.top + a.height
    }
    ;
    f.distance = function(a) {
        var b = a.x < this.left ? this.left - a.x : Math.max(a.x - (this.left + this.width), 0);
        a = a.y < this.top ? this.top - a.y : Math.max(a.y - (this.top + this.height), 0);
        return Math.sqrt(b * b + a * a)
    }
    ;
    f.getSize = function() {
        return new mh(this.width,this.height)
    }
    ;
    f.ceil = function() {
        this.left = Math.ceil(this.left);
        this.top = Math.ceil(this.top);
        this.width = Math.ceil(this.width);
        this.height = Math.ceil(this.height);
        return this
    }
    ;
    f.floor = function() {
        this.left = Math.floor(this.left);
        this.top = Math.floor(this.top);
        this.width = Math.floor(this.width);
        this.height = Math.floor(this.height);
        return this
    }
    ;
    f.round = function() {
        this.left = Math.round(this.left);
        this.top = Math.round(this.top);
        this.width = Math.round(this.width);
        this.height = Math.round(this.height);
        return this
    }
    ;
    f.translate = function(a, b) {
        a instanceof lh ? (this.left += a.x,
        this.top += a.y) : (this.left += a,
        typeof b === "number" && (this.top += b));
        return this
    }
    ;
    f.scale = function(a, b) {
        b = typeof b === "number" ? b : a;
        this.left *= a;
        this.width *= a;
        this.top *= b;
        this.height *= b;
        return this
    }
    ;
    var Wh = function(a, b, c) {
        if (typeof b === "string")
            (b = tia(a, b)) && (a.style[b] = c);
        else
            for (var d in b) {
                c = a;
                var e = b[d]
                  , h = tia(c, d);
                h && (c.style[h] = e)
            }
    }
      , uia = {}
      , tia = function(a, b) {
        var c = uia[b];
        if (!c) {
            var d = cd(b);
            c = d;
            a.style[d] === void 0 && (d = (Zd ? "Webkit" : Yd ? "Moz" : Wd ? "ms" : null) + oca(d),
            a.style[d] !== void 0 && (c = d));
            uia[b] = c
        }
        return c
    }
      , Xh = function(a, b) {
        var c = oh(a);
        return c.defaultView && c.defaultView.getComputedStyle && (a = c.defaultView.getComputedStyle(a, null)) ? a[b] || a.getPropertyValue(b) || "" : ""
    }
      , Yh = function(a, b) {
        return Xh(a, b) || (a.currentStyle ? a.currentStyle[b] : null) || a.style && a.style[b]
    }
      , $h = function(a, b, c) {
        if (b instanceof lh) {
            var d = b.x;
            b = b.y
        } else
            d = b,
            b = c;
        a.style.left = Zh(d, !1);
        a.style.top = Zh(b, !1)
    }
      , via = function(a) {
        try {
            return a.getBoundingClientRect()
        } catch (b) {
            return {
                left: 0,
                top: 0,
                right: 0,
                bottom: 0
            }
        }
    }
      , ai = function(a) {
        var b = oh(a)
          , c = new lh(0,0);
        if (a == (b ? oh(b) : document).documentElement)
            return c;
        a = via(a);
        b = xh(ph(b).JSC$6495_document_);
        c.x = a.left + b.x;
        c.y = a.top + b.y;
        return c
    }
      , bi = function(a, b, c) {
        if (b instanceof mh)
            c = b.height,
            b = b.width;
        else if (c == void 0)
            throw Error("missing height argument");
        a.style.width = Zh(b, !0);
        a.style.height = Zh(c, !0)
    }
      , Zh = function(a, b) {
        typeof a == "number" && (a = (b ? Math.round(a) : a) + "px");
        return a
    }
      , ci = function(a) {
        var b = wia;
        if (Yh(a, "display") != "none")
            return b(a);
        var c = a.style
          , d = c.display
          , e = c.visibility
          , h = c.position;
        c.visibility = "hidden";
        c.position = "absolute";
        c.display = "inline";
        a = b(a);
        c.display = d;
        c.position = h;
        c.visibility = e;
        return a
    }
      , wia = function(a) {
        var b = a.offsetWidth
          , c = a.offsetHeight
          , d = Zd && !b && !c;
        return (b === void 0 || d) && a.getBoundingClientRect ? (a = via(a),
        new mh(a.right - a.left,a.bottom - a.top)) : new mh(b,c)
    }
      , di = function(a) {
        var b = ai(a);
        a = ci(a);
        return new Th(b.x,b.y,a.width,a.height)
    }
      , xia = function(a, b) {
        a = a.style;
        "opacity"in a ? a.opacity = b : "MozOpacity"in a ? a.MozOpacity = b : "filter"in a && (a.filter = b === "" ? "" : "alpha(opacity=" + Number(b) * 100 + ")")
    }
      , ei = function(a, b) {
        a.style.display = b ? "" : "none"
    }
      , fi = function(a) {
        return "rtl" == Yh(a, "direction")
    }
      , yia = function(a) {
        var b = Xh(a, "marginLeft")
          , c = Xh(a, "marginRight")
          , d = Xh(a, "marginTop");
        a = Xh(a, "marginBottom");
        return new Sh(parseFloat(d),parseFloat(c),parseFloat(a),parseFloat(b))
    }
      , zia = function(a) {
        var b = Xh(a, "borderLeftWidth")
          , c = Xh(a, "borderRightWidth")
          , d = Xh(a, "borderTopWidth");
        a = Xh(a, "borderBottomWidth");
        return new Sh(parseFloat(d),parseFloat(c),parseFloat(a),parseFloat(b))
    }
      , Aia = function(a) {
        var b = Bh("DIV");
        a && (b.className = a);
        b.style.cssText = "overflow:auto;position:absolute;top:0;width:100px;height:100px";
        a = Bh("DIV");
        bi(a, "200px", "200px");
        b.appendChild(a);
        document.body.appendChild(b);
        a = b.offsetWidth - b.clientWidth;
        Ih(b);
        return a
    };
    var Bia = new Date().getTime();
    var Cia = function(a) {
        this.internalArray_ = bf(a)
    };
    k(Cia, xg);
    Cia.repeatedFields_ = [2];
    var ii = function(a) {
        this.internalArray_ = bf(a)
    };
    k(ii, xg);
    ii.prototype.getSeconds = function() {
        return Xf(this, 1)
    }
    ;
    ii.prototype.setSeconds = function(a) {
        return Cf(this, 1, Se(a), "0")
    }
    ;
    var Dia = [0, Vga, Xga];
    var ji = function(a) {
        this.internalArray_ = bf(a)
    };
    k(ji, xg);
    ji.prototype.getSeconds = function() {
        return Xf(this, 1)
    }
    ;
    ji.prototype.setSeconds = function(a) {
        return Cf(this, 1, Se(a), "0")
    }
    ;
    var Eia = function(a) {
        var b = Number;
        var c = c === void 0 ? "0" : c;
        c = Rf(Cea(lf(a, 1), !0), c);
        b = b(c);
        a = Wf(a, 2);
        return new Date(b * 1E3 + a / 1E6)
    };
    var Fia = [0, Vga, Xga];
    var Gia = function(a) {
        if (!a)
            return "";
        if (/^about:(?:blank|srcdoc)$/.test(a))
            return window.origin || "";
        a.indexOf("blob:") === 0 && (a = a.substring(5));
        a = a.split("#")[0].split("?")[0];
        a = a.toLowerCase();
        a.indexOf("//") == 0 && (a = window.location.protocol + a);
        /^[\w\-]*:\/\//.test(a) || (a = window.location.href);
        var b = a.substring(a.indexOf("://") + 3)
          , c = b.indexOf("/");
        c != -1 && (b = b.substring(0, c));
        c = a.substring(0, a.indexOf("://"));
        if (!c)
            throw Error("URI is missing protocol: " + a);
        if (c !== "http" && c !== "https" && c !== "chrome-extension" && c !== "moz-extension" && c !== "file" && c !== "android-app" && c !== "chrome-search" && c !== "chrome-untrusted" && c !== "chrome" && c !== "app" && c !== "devtools")
            throw Error("Invalid URI scheme in origin: " + c);
        a = "";
        var d = b.indexOf(":");
        if (d != -1) {
            var e = b.substring(d + 1);
            b = b.substring(0, d);
            if (c === "http" && e !== "80" || c === "https" && e !== "443")
                a = ":" + e
        }
        return c + "://" + b + a
    };
    function Hia() {
        function a() {
            e[0] = 1732584193;
            e[1] = 4023233417;
            e[2] = 2562383102;
            e[3] = 271733878;
            e[4] = 3285377520;
            r = q = 0
        }
        function b(x) {
            for (var z = l, C = 0; C < 64; C += 4)
                z[C / 4] = x[C] << 24 | x[C + 1] << 16 | x[C + 2] << 8 | x[C + 3];
            for (C = 16; C < 80; C++)
                x = z[C - 3] ^ z[C - 8] ^ z[C - 14] ^ z[C - 16],
                z[C] = (x << 1 | x >>> 31) & 4294967295;
            x = e[0];
            var E = e[1]
              , K = e[2]
              , N = e[3]
              , Q = e[4];
            for (C = 0; C < 80; C++) {
                if (C < 40) {
                    if (C < 20) {
                        var V = N ^ E & (K ^ N);
                        var ca = 1518500249
                    } else
                        V = E ^ K ^ N,
                        ca = 1859775393;
                } else
                    C < 60 ? (V = E & K | N & (E | K),
                    ca = 2400959708) : (V = E ^ K ^ N,
                    ca = 3395469782);
                V = ((x << 5 | x >>> 27) & 4294967295) + V + Q + ca + z[C] & 4294967295;
                Q = N;
                N = K;
                K = (E << 30 | E >>> 2) & 4294967295;
                E = x;
                x = V
            }
            e[0] = e[0] + x & 4294967295;
            e[1] = e[1] + E & 4294967295;
            e[2] = e[2] + K & 4294967295;
            e[3] = e[3] + N & 4294967295;
            e[4] = e[4] + Q & 4294967295
        }
        function c(x, z) {
            if (typeof x === "string") {
                x = unescape(encodeURIComponent(x));
                for (var C = [], E = 0, K = x.length; E < K; ++E)
                    C.push(x.charCodeAt(E));
                x = C
            }
            z || (z = x.length);
            C = 0;
            if (q == 0)
                for (; C + 64 < z; )
                    b(x.slice(C, C + 64)),
                    C += 64,
                    r += 64;
            for (; C < z; )
                if (h[q++] = x[C++],
                r++,
                q == 64)
                    for (q = 0,
                    b(h); C + 64 < z; )
                        b(x.slice(C, C + 64)),
                        C += 64,
                        r += 64
        }
        function d() {
            var x = []
              , z = r * 8;
            q < 56 ? c(m, 56 - q) : c(m, 64 - (q - 56));
            for (var C = 63; C >= 56; C--)
                h[C] = z & 255,
                z >>>= 8;
            b(h);
            for (C = z = 0; C < 5; C++)
                for (var E = 24; E >= 0; E -= 8)
                    x[z++] = e[C] >> E & 255;
            return x
        }
        for (var e = [], h = [], l = [], m = [128], p = 1; p < 64; ++p)
            m[p] = 0;
        var q, r;
        a();
        return {
            reset: a,
            update: c,
            digest: d,
            digestString: function() {
                for (var x = d(), z = "", C = 0; C < x.length; C++)
                    z += "0123456789ABCDEF".charAt(Math.floor(x[C] / 16)) + "0123456789ABCDEF".charAt(x[C] % 16);
                return z
            }
        }
    }
    ;var Jia = function(a, b, c) {
        var d = String(Na.location.href);
        return d && a && b ? [b, Iia(Gia(d), a, c || null)].join(" ") : null
    }
      , Iia = function(a, b, c) {
        var d = []
          , e = [];
        if ((Array.isArray(c) ? 2 : 1) == 1)
            return e = [b, a],
            Zb(d, function(m) {
                e.push(m)
            }),
            Kia(e.join(" "));
        var h = []
          , l = [];
        Zb(c, function(m) {
            l.push(m.key);
            h.push(m.value)
        });
        c = Math.floor(new Date().getTime() / 1E3);
        e = h.length == 0 ? [c, b, a] : [h.join(":"), c, b, a];
        Zb(d, function(m) {
            e.push(m)
        });
        a = Kia(e.join(" "));
        a = [c, a];
        l.length == 0 || a.push(l.join(""));
        return a.join("_")
    }
      , Kia = function(a) {
        var b = Hia();
        b.update(a);
        return b.digestString().toLowerCase()
    };
    var Lia = {};
    var ki = function(a) {
        this.JSC$6517_document_ = a || {
            cookie: ""
        }
    };
    f = ki.prototype;
    f.isEnabled = function() {
        if (!Na.navigator.cookieEnabled)
            return !1;
        if (!this.isEmpty())
            return !0;
        this.set("TESTCOOKIESENABLED", "1", {
            maxAge: 60
        });
        if (this.get("TESTCOOKIESENABLED") !== "1")
            return !1;
        this.remove("TESTCOOKIESENABLED");
        return !0
    }
    ;
    f.set = function(a, b, c) {
        var d = !1;
        if (typeof c === "object") {
            var e = c.sameSite;
            d = c.secure || !1;
            var h = c.domain || void 0;
            var l = c.path || void 0;
            var m = c.maxAge
        }
        if (/[;=\s]/.test(a))
            throw Error("Invalid cookie name \"" + a + "\"");
        if (/[;\r\n]/.test(b))
            throw Error("Invalid cookie value \"" + b + "\"");
        m === void 0 && (m = -1);
        c = h ? ";domain=" + h : "";
        l = l ? ";path=" + l : "";
        d = d ? ";secure" : "";
        m = m < 0 ? "" : m == 0 ? ";expires=" + new Date(1970,1,1).toUTCString() : ";expires=" + new Date(Date.now() + m * 1E3).toUTCString();
        this.JSC$6517_document_.cookie = a + "=" + b + c + l + m + d + (e != null ? ";samesite=" + e : "")
    }
    ;
    f.get = function(a, b) {
        for (var c = a + "=", d = (this.JSC$6517_document_.cookie || "").split(";"), e = 0, h; e < d.length; e++) {
            h = ob(d[e]);
            if (h.lastIndexOf(c, 0) == 0)
                return h.slice(c.length);
            if (h == a)
                return ""
        }
        return b
    }
    ;
    f.remove = function(a, b, c) {
        var d = this.containsKey(a);
        this.set(a, "", {
            maxAge: 0,
            path: b,
            domain: c
        });
        return d
    }
    ;
    f.getKeys = function() {
        return li(this).keys
    }
    ;
    f.getValues = function() {
        return li(this).values
    }
    ;
    f.isEmpty = function() {
        return !this.JSC$6517_document_.cookie
    }
    ;
    f.getCount = function() {
        return this.JSC$6517_document_.cookie ? (this.JSC$6517_document_.cookie || "").split(";").length : 0
    }
    ;
    f.containsKey = function(a) {
        return this.get(a) !== void 0
    }
    ;
    f.containsValue = function(a) {
        for (var b = li(this).values, c = 0; c < b.length; c++)
            if (b[c] == a)
                return !0;
        return !1
    }
    ;
    f.clear = function() {
        for (var a = li(this).keys, b = a.length - 1; b >= 0; b--)
            this.remove(a[b])
    }
    ;
    var li = function(a) {
        a = (a.JSC$6517_document_.cookie || "").split(";");
        for (var b = [], c = [], d, e, h = 0; h < a.length; h++)
            e = ob(a[h]),
            d = e.indexOf("="),
            d == -1 ? (b.push(""),
            c.push(e)) : (b.push(e.substring(0, d)),
            c.push(e.substring(d + 1)));
        return {
            keys: b,
            values: c
        }
    }
      , mi = new ki(typeof document == "undefined" ? null : document);
    var Mia = function(a) {
        return !!Lia.FPA_SAMESITE_PHASE2_MOD || !(a === void 0 || !a)
    }
      , Nia = function(a) {
        a = a === void 0 ? !1 : a;
        var b = Na.__SAPISID || Na.__APISID || Na.__3PSAPISID || Na.__OVERRIDE_SID;
        Mia(a) && (b = b || Na.__1PSAPISID);
        if (b)
            return !0;
        if (typeof document !== "undefined") {
            var c = new ki(document);
            b = c.get("SAPISID") || c.get("APISID") || c.get("__Secure-3PAPISID");
            Mia(a) && (b = b || c.get("__Secure-1PAPISID"))
        }
        return !!b
    }
      , Oia = function(a, b, c, d) {
        (a = Na[a]) || typeof document === "undefined" || (a = new ki(document).get(b));
        return a ? Jia(a, c, d) : null
    }
      , Pia = function(a, b) {
        b = b === void 0 ? !1 : b;
        var c = Gia(String(Na.location.href))
          , d = [];
        if (Nia(b)) {
            c = c.indexOf("https:") == 0 || c.indexOf("chrome-extension:") == 0 || c.indexOf("chrome-untrusted://new-tab-page") == 0 || c.indexOf("moz-extension:") == 0;
            var e = c ? Na.__SAPISID : Na.__APISID;
            e || typeof document === "undefined" || (e = new ki(document),
            e = e.get(c ? "SAPISID" : "APISID") || e.get("__Secure-3PAPISID"));
            (e = e ? Jia(e, c ? "SAPISIDHASH" : "APISIDHASH", a) : null) && d.push(e);
            c && Mia(b) && ((b = Oia("__1PSAPISID", "__Secure-1PAPISID", "SAPISID1PHASH", a)) && d.push(b),
            (a = Oia("__3PSAPISID", "__Secure-3PAPISID", "SAPISID3PHASH", a)) && d.push(a))
        }
        return d.length == 0 ? null : d.join(" ")
    };
    function ni(a) {
        a && typeof a.dispose == "function" && a.dispose()
    }
    ;function oi(a) {
        for (var b = 0, c = arguments.length; b < c; ++b) {
            var d = arguments[b];
            Ya(d) ? oi.apply(null, d) : ni(d)
        }
    }
    ;var pi = function() {
        this.JSC$6527_disposed_ = this.JSC$6527_disposed_;
        this.onDisposeCallbacks_ = this.onDisposeCallbacks_
    };
    pi.prototype.JSC$6527_disposed_ = !1;
    pi.prototype.isDisposed = function() {
        return this.JSC$6527_disposed_
    }
    ;
    pi.prototype.dispose = function() {
        this.JSC$6527_disposed_ || (this.JSC$6527_disposed_ = !0,
        this.disposeInternal())
    }
    ;
    pi.prototype[Symbol.dispose] = function() {
        this.dispose()
    }
    ;
    var ri = function(a, b) {
        a.addOnDisposeCallback(cb(ni, b))
    };
    pi.prototype.addOnDisposeCallback = function(a, b) {
        this.JSC$6527_disposed_ ? b !== void 0 ? a.call(b) : a() : (this.onDisposeCallbacks_ || (this.onDisposeCallbacks_ = []),
        this.onDisposeCallbacks_.push(b !== void 0 ? bb(a, b) : a))
    }
    ;
    pi.prototype.disposeInternal = function() {
        if (this.onDisposeCallbacks_)
            for (; this.onDisposeCallbacks_.length; )
                this.onDisposeCallbacks_.shift()()
    }
    ;
    var si = function(a) {
        this.id = a
    };
    si.prototype.toString = function() {
        return this.id
    }
    ;
    var ti = function(a, b) {
        this.type = a instanceof si ? String(a) : a;
        this.currentTarget = this.target = b;
        this.defaultPrevented = this.propagationStopped_ = !1
    };
    ti.prototype.stopPropagation = function() {
        this.propagationStopped_ = !0
    }
    ;
    ti.prototype.preventDefault = function() {
        this.defaultPrevented = !0
    }
    ;
    var Qia = function() {
        if (!Na.addEventListener || !Object.defineProperty)
            return !1;
        var a = !1
          , b = Object.defineProperty({}, "passive", {
            get: function() {
                a = !0
            }
        });
        try {
            var c = function() {};
            Na.addEventListener("test", c, b);
            Na.removeEventListener("test", c, b)
        } catch (d) {}
        return a
    }();
    var ui = function(a, b) {
        ti.call(this, a ? a.type : "");
        this.relatedTarget = this.currentTarget = this.target = null;
        this.button = this.screenY = this.screenX = this.clientY = this.clientX = this.offsetY = this.offsetX = 0;
        this.key = "";
        this.charCode = this.keyCode = 0;
        this.metaKey = this.shiftKey = this.altKey = this.ctrlKey = !1;
        this.state = null;
        this.pointerId = 0;
        this.pointerType = "";
        this.timeStamp = 0;
        this.event_ = null;
        a && this.init(a, b)
    };
    fb(ui, ti);
    var Ria = {
        2: "touch",
        3: "pen",
        4: "mouse"
    };
    ui.prototype.init = function(a, b) {
        var c = this.type = a.type
          , d = a.changedTouches && a.changedTouches.length ? a.changedTouches[0] : null;
        this.target = a.target || a.srcElement;
        this.currentTarget = b;
        (b = a.relatedTarget) ? Yd && (Ud(b, "nodeName") || (b = null)) : c == "mouseover" ? b = a.fromElement : c == "mouseout" && (b = a.toElement);
        this.relatedTarget = b;
        d ? (this.clientX = d.clientX !== void 0 ? d.clientX : d.pageX,
        this.clientY = d.clientY !== void 0 ? d.clientY : d.pageY,
        this.screenX = d.screenX || 0,
        this.screenY = d.screenY || 0) : (this.offsetX = Zd || a.offsetX !== void 0 ? a.offsetX : a.layerX,
        this.offsetY = Zd || a.offsetY !== void 0 ? a.offsetY : a.layerY,
        this.clientX = a.clientX !== void 0 ? a.clientX : a.pageX,
        this.clientY = a.clientY !== void 0 ? a.clientY : a.pageY,
        this.screenX = a.screenX || 0,
        this.screenY = a.screenY || 0);
        this.button = a.button;
        this.keyCode = a.keyCode || 0;
        this.key = a.key || "";
        this.charCode = a.charCode || (c == "keypress" ? a.keyCode : 0);
        this.ctrlKey = a.ctrlKey;
        this.altKey = a.altKey;
        this.shiftKey = a.shiftKey;
        this.metaKey = a.metaKey;
        this.pointerId = a.pointerId || 0;
        this.pointerType = typeof a.pointerType === "string" ? a.pointerType : Ria[a.pointerType] || "";
        this.state = a.state;
        this.timeStamp = a.timeStamp;
        this.event_ = a;
        a.defaultPrevented && ui.superClass_.preventDefault.call(this)
    }
    ;
    ui.prototype.stopPropagation = function() {
        ui.superClass_.stopPropagation.call(this);
        this.event_.stopPropagation ? this.event_.stopPropagation() : this.event_.cancelBubble = !0
    }
    ;
    ui.prototype.preventDefault = function() {
        ui.superClass_.preventDefault.call(this);
        var a = this.event_;
        a.preventDefault ? a.preventDefault() : a.returnValue = !1
    }
    ;
    var Sia = "closure_listenable_" + (Math.random() * 1E6 | 0)
      , vi = function(a) {
        return !(!a || !a[Sia])
    };
    var Tia = 0;
    var Uia = function(a, b, c, d, e) {
        this.listener = a;
        this.proxy = null;
        this.src = b;
        this.type = c;
        this.capture = !!d;
        this.handler = e;
        this.key = ++Tia;
        this.removed = this.callOnce = !1
    }
      , Via = function(a) {
        a.removed = !0;
        a.listener = null;
        a.proxy = null;
        a.src = null;
        a.handler = null
    };
    var wi = function(a) {
        this.src = a;
        this.listeners = {};
        this.typeCount_ = 0
    };
    wi.prototype.add = function(a, b, c, d, e) {
        var h = a.toString();
        a = this.listeners[h];
        a || (a = this.listeners[h] = [],
        this.typeCount_++);
        var l = Wia(a, b, d, e);
        l > -1 ? (b = a[l],
        c || (b.callOnce = !1)) : (b = new Uia(b,this.src,h,!!d,e),
        b.callOnce = c,
        a.push(b));
        return b
    }
    ;
    wi.prototype.remove = function(a, b, c, d) {
        a = a.toString();
        if (!(a in this.listeners))
            return !1;
        var e = this.listeners[a];
        b = Wia(e, b, c, d);
        return b > -1 ? (Via(e[b]),
        jc(e, b),
        e.length == 0 && (delete this.listeners[a],
        this.typeCount_--),
        !0) : !1
    }
    ;
    var Xia = function(a, b) {
        var c = b.type;
        if (!(c in a.listeners))
            return !1;
        var d = ic(a.listeners[c], b);
        d && (Via(b),
        a.listeners[c].length == 0 && (delete a.listeners[c],
        a.typeCount_--));
        return d
    };
    wi.prototype.removeAll = function(a) {
        a = a && a.toString();
        var b = 0, c;
        for (c in this.listeners)
            if (!a || c == a) {
                for (var d = this.listeners[c], e = 0; e < d.length; e++)
                    ++b,
                    Via(d[e]);
                delete this.listeners[c];
                this.typeCount_--
            }
        return b
    }
    ;
    wi.prototype.getListener = function(a, b, c, d) {
        a = this.listeners[a.toString()];
        var e = -1;
        a && (e = Wia(a, b, c, d));
        return e > -1 ? a[e] : null
    }
    ;
    wi.prototype.hasListener = function(a, b) {
        var c = a !== void 0
          , d = c ? a.toString() : ""
          , e = b !== void 0;
        return pc.some(this.listeners, function(h) {
            for (var l = 0; l < h.length; ++l)
                if (!(c && h[l].type != d || e && h[l].capture != b))
                    return !0;
            return !1
        })
    }
    ;
    var Wia = function(a, b, c, d) {
        for (var e = 0; e < a.length; ++e) {
            var h = a[e];
            if (!h.removed && h.listener == b && h.capture == !!c && h.handler == d)
                return e
        }
        return -1
    };
    var Yia = "closure_lm_" + (Math.random() * 1E6 | 0)
      , Zia = {}
      , $ia = 0
      , yi = function(a, b, c, d, e) {
        if (d && d.once)
            return xi(a, b, c, d, e);
        if (Array.isArray(b)) {
            for (var h = 0; h < b.length; h++)
                yi(a, b[h], c, d, e);
            return null
        }
        c = aja(c);
        return vi(a) ? a.listen(b, c, $a(d) ? !!d.capture : !!d, e) : bja(a, b, c, !1, d, e)
    }
      , bja = function(a, b, c, d, e, h) {
        if (!b)
            throw Error("Invalid event type");
        var l = $a(e) ? !!e.capture : !!e
          , m = zi(a);
        m || (a[Yia] = m = new wi(a));
        c = m.add(b, c, d, l, h);
        if (c.proxy)
            return c;
        d = cja();
        c.proxy = d;
        d.src = a;
        d.listener = c;
        if (a.addEventListener)
            Qia || (e = l),
            e === void 0 && (e = !1),
            a.addEventListener(b.toString(), d, e);
        else if (a.attachEvent)
            a.attachEvent(dja(b.toString()), d);
        else if (a.addListener && a.removeListener)
            a.addListener(d);
        else
            throw Error("addEventListener and attachEvent are unavailable.");
        $ia++;
        return c
    }
      , cja = function() {
        var a = eja
          , b = function(c) {
            return a.call(b.src, b.listener, c)
        };
        return b
    }
      , xi = function(a, b, c, d, e) {
        if (Array.isArray(b)) {
            for (var h = 0; h < b.length; h++)
                xi(a, b[h], c, d, e);
            return null
        }
        c = aja(c);
        return vi(a) ? a.listenOnce(b, c, $a(d) ? !!d.capture : !!d, e) : bja(a, b, c, !0, d, e)
    }
      , Ai = function(a, b, c, d, e) {
        if (Array.isArray(b))
            for (var h = 0; h < b.length; h++)
                Ai(a, b[h], c, d, e);
        else
            d = $a(d) ? !!d.capture : !!d,
            c = aja(c),
            vi(a) ? a.unlisten(b, c, d, e) : a && (a = zi(a)) && (b = a.getListener(b, c, d, e)) && Bi(b)
    }
      , Bi = function(a) {
        if (typeof a === "number" || !a || a.removed)
            return !1;
        var b = a.src;
        if (vi(b))
            return Xia(b.eventTargetListeners_, a);
        var c = a.type
          , d = a.proxy;
        b.removeEventListener ? b.removeEventListener(c, d, a.capture) : b.detachEvent ? b.detachEvent(dja(c), d) : b.addListener && b.removeListener && b.removeListener(d);
        $ia--;
        (c = zi(b)) ? (Xia(c, a),
        c.typeCount_ == 0 && (c.src = null,
        b[Yia] = null)) : Via(a);
        return !0
    }
      , fja = function(a, b, c, d, e) {
        c = aja(c);
        d = !!d;
        return vi(a) ? a.getListener(b, c, d, e) : a ? (a = zi(a)) ? a.getListener(b, c, d, e) : null : null
    }
      , dja = function(a) {
        return a in Zia ? Zia[a] : Zia[a] = "on" + a
    }
      , eja = function(a, b) {
        if (a.removed)
            a = !0;
        else {
            b = new ui(b,this);
            var c = a.listener
              , d = a.handler || a.src;
            a.callOnce && Bi(a);
            a = c.call(d, b)
        }
        return a
    }
      , zi = function(a) {
        a = a[Yia];
        return a instanceof wi ? a : null
    }
      , gja = "__closure_events_fn_" + (Math.random() * 1E9 >>> 0)
      , aja = function(a) {
        if (typeof a === "function")
            return a;
        a[gja] || (a[gja] = function(b) {
            return a.handleEvent(b)
        }
        );
        return a[gja]
    };
    var Ci = function() {
        pi.call(this);
        this.eventTargetListeners_ = new wi(this);
        this.actualEventTarget_ = this;
        this.parentEventTarget_ = null
    };
    fb(Ci, pi);
    Ci.prototype[Sia] = !0;
    f = Ci.prototype;
    f.setParentEventTarget = function(a) {
        this.parentEventTarget_ = a
    }
    ;
    f.addEventListener = function(a, b, c, d) {
        yi(this, a, b, c, d)
    }
    ;
    f.removeEventListener = function(a, b, c, d) {
        Ai(this, a, b, c, d)
    }
    ;
    f.dispatchEvent = function(a) {
        var b, c = this.parentEventTarget_;
        if (c)
            for (b = []; c; c = c.parentEventTarget_)
                b.push(c);
        c = this.actualEventTarget_;
        var d = a.type || a;
        if (typeof a === "string")
            a = new ti(a,c);
        else if (a instanceof ti)
            a.target = a.target || c;
        else {
            var e = a;
            a = new ti(d,c);
            pc.extend(a, e)
        }
        e = !0;
        if (b)
            for (var h = b.length - 1; !a.propagationStopped_ && h >= 0; h--) {
                var l = a.currentTarget = b[h];
                e = hja(l, d, !0, a) && e
            }
        a.propagationStopped_ || (l = a.currentTarget = c,
        e = hja(l, d, !0, a) && e,
        a.propagationStopped_ || (e = hja(l, d, !1, a) && e));
        if (b)
            for (h = 0; !a.propagationStopped_ && h < b.length; h++)
                l = a.currentTarget = b[h],
                e = hja(l, d, !1, a) && e;
        return e
    }
    ;
    f.disposeInternal = function() {
        Ci.superClass_.disposeInternal.call(this);
        this.removeAllListeners();
        this.parentEventTarget_ = null
    }
    ;
    f.listen = function(a, b, c, d) {
        return this.eventTargetListeners_.add(String(a), b, !1, c, d)
    }
    ;
    f.listenOnce = function(a, b, c, d) {
        return this.eventTargetListeners_.add(String(a), b, !0, c, d)
    }
    ;
    f.unlisten = function(a, b, c, d) {
        return this.eventTargetListeners_.remove(String(a), b, c, d)
    }
    ;
    f.removeAllListeners = function(a) {
        return this.eventTargetListeners_ ? this.eventTargetListeners_.removeAll(a) : 0
    }
    ;
    var hja = function(a, b, c, d) {
        b = a.eventTargetListeners_.listeners[String(b)];
        if (!b)
            return !0;
        b = b.concat();
        for (var e = !0, h = 0; h < b.length; ++h) {
            var l = b[h];
            if (l && !l.removed && l.capture == c) {
                var m = l.listener
                  , p = l.handler || l.src;
                l.callOnce && Xia(a.eventTargetListeners_, l);
                e = m.call(p, d) !== !1 && e
            }
        }
        return e && !d.defaultPrevented
    };
    Ci.prototype.getListener = function(a, b, c, d) {
        return this.eventTargetListeners_.getListener(String(a), b, c, d)
    }
    ;
    Ci.prototype.hasListener = function(a, b) {
        return this.eventTargetListeners_.hasListener(a !== void 0 ? String(a) : void 0, b)
    }
    ;
    var Di = function(a) {
        Ci.call(this);
        var b = this;
        this.pollingJob = this.abortTimeoutKey = 0;
        this.jobManager = a != null ? a : {
            addLowPriorityJob: function(e, h) {
                return setTimeout(e, h)
            },
            cancelJob: function(e) {
                clearTimeout(e)
            }
        };
        var c, d;
        this.isOnline = (d = (c = window.navigator) == null ? void 0 : c.onLine) != null ? d : !0;
        this.onNavigatorChange = function() {
            return t(function(e) {
                return n(e, ija(b), 0)
            })
        }
        ;
        window.addEventListener("offline", this.onNavigatorChange);
        window.addEventListener("online", this.onNavigatorChange);
        this.pollingJob || jja(this)
    };
    k(Di, Ci);
    var kja = function() {
        var a = Ei;
        Di.instance || (Di.instance = new Di(a));
        return Di.instance
    };
    Di.prototype.dispose = function() {
        window.removeEventListener("offline", this.onNavigatorChange);
        window.removeEventListener("online", this.onNavigatorChange);
        this.jobManager.cancelJob(this.pollingJob);
        delete Di.instance
    }
    ;
    Di.prototype.isNetworkAvailable = function() {
        return this.isOnline
    }
    ;
    var jja = function(a) {
        a.pollingJob = a.jobManager.addLowPriorityJob(function() {
            var b;
            return t(function(c) {
                if (c.nextAddress == 1)
                    return a.isOnline ? ((b = window.navigator) == null ? 0 : b.onLine) ? c.jumpTo(3) : n(c, ija(a), 3) : n(c, ija(a), 3);
                jja(a);
                ta(c)
            })
        }, 3E4)
    }
      , ija = function(a, b) {
        return a.networkRequestPromise ? a.networkRequestPromise : a.networkRequestPromise = new Promise(function(c) {
            var d, e, h, l;
            return t(function(m) {
                switch (m.nextAddress) {
                case 1:
                    return d = window.AbortController ? new window.AbortController : void 0,
                    h = (e = d) == null ? void 0 : e.signal,
                    l = !1,
                    va(m, 2, 3),
                    d && (a.abortTimeoutKey = a.jobManager.addLowPriorityJob(function() {
                        d.abort()
                    }, b || 2E4)),
                    n(m, fetch("/generate_204", {
                        method: "HEAD",
                        signal: h
                    }), 5);
                case 5:
                    l = !0;
                case 3:
                    Aa(m);
                    a.networkRequestPromise = void 0;
                    a.abortTimeoutKey && (a.jobManager.cancelJob(a.abortTimeoutKey),
                    a.abortTimeoutKey = 0);
                    l !== a.isOnline && (a.isOnline = l,
                    a.isOnline ? a.dispatchEvent("networkstatus-online") : a.dispatchEvent("networkstatus-offline"));
                    c(l);
                    Ca(m, 0);
                    break;
                case 2:
                    za(m),
                    l = !1,
                    m.jumpTo(3);
                }
            })
        }
        )
    };
    var lja = function() {
        this.data = [];
        this.cachedPackedInt52 = -1
    };
    lja.prototype.set = function(a, b) {
        b = b === void 0 ? !0 : b;
        0 <= a && a < 52 && Number.isInteger(a) && this.data[a] !== b && (this.data[a] = b,
        this.cachedPackedInt52 = -1)
    }
    ;
    lja.prototype.get = function(a) {
        return !!this.data[a]
    }
    ;
    var mja = function(a) {
        a.cachedPackedInt52 === -1 && (a.cachedPackedInt52 = a.data.reduce(function(b, c, d) {
            return b + (c ? Math.pow(2, d) : 0)
        }, 0));
        return a.cachedPackedInt52
    };
    var nja = function(a, b, c) {
        a && b !== null && b != b.top && (b = b.top);
        try {
            return (c === void 0 ? 0 : c) ? new mh(b.innerWidth,b.innerHeight).round() : vh(b).round()
        } catch (d) {
            return new mh(-12245933,-12245933)
        }
    };
    var oja = function(a) {
        return a.prerendering ? 3 : {
            visible: 1,
            hidden: 2,
            prerender: 3,
            preview: 4,
            unloaded: 5
        }[a.visibilityState || a.webkitVisibilityState || a.mozVisibilityState || ""] || 0
    };
    var pja = function(a, b) {
        this.create_ = a;
        this.reset_ = b;
        this.occupants_ = 0;
        this.head_ = null
    };
    pja.prototype.get = function() {
        if (this.occupants_ > 0) {
            this.occupants_--;
            var a = this.head_;
            this.head_ = a.next;
            a.next = null
        } else
            a = this.create_();
        return a
    }
    ;
    pja.prototype.put = function(a) {
        this.reset_(a);
        this.occupants_ < 100 && (this.occupants_++,
        a.next = this.head_,
        this.head_ = a)
    }
    ;
    var qja, Ija = function() {
        var a = Na.MessageChannel;
        typeof a === "undefined" && typeof window !== "undefined" && window.postMessage && window.addEventListener && !Hd("Presto") && (a = function() {
            var e = Bh("IFRAME");
            e.style.display = "none";
            document.documentElement.appendChild(e);
            var h = e.contentWindow;
            e = h.document;
            e.open();
            e.close();
            var l = "callImmediate" + Math.random()
              , m = h.location.protocol == "file:" ? "*" : h.location.protocol + "//" + h.location.host;
            e = bb(function(p) {
                if ((m == "*" || p.origin == m) && p.data == l)
                    this.port1.onmessage()
            }, this);
            h.addEventListener("message", e, !1);
            this.port1 = {};
            this.port2 = {
                postMessage: function() {
                    h.postMessage(l, m)
                }
            }
        }
        );
        if (typeof a !== "undefined") {
            var b = new a
              , c = {}
              , d = c;
            b.port1.onmessage = function() {
                if (c.next !== void 0) {
                    c = c.next;
                    var e = c.cb;
                    c.cb = null;
                    e()
                }
            }
            ;
            return function(e) {
                d.next = {
                    cb: e
                };
                d = d.next;
                b.port2.postMessage(0)
            }
        }
        return function(e) {
            Na.setTimeout(e, 0)
        }
    }, Jja = fc;
    var Kja = function() {
        this.workTail_ = this.workHead_ = null
    };
    Kja.prototype.add = function(a, b) {
        var c = Lja.get();
        c.set(a, b);
        this.workTail_ ? this.workTail_.next = c : this.workHead_ = c;
        this.workTail_ = c
    }
    ;
    Kja.prototype.remove = function() {
        var a = null;
        this.workHead_ && (a = this.workHead_,
        this.workHead_ = this.workHead_.next,
        this.workHead_ || (this.workTail_ = null),
        a.next = null);
        return a
    }
    ;
    var Lja = new pja(function() {
        return new Mja
    }
    ,function(a) {
        return a.reset()
    }
    )
      , Mja = function() {
        this.next = this.scope = this.fn = null
    };
    Mja.prototype.set = function(a, b) {
        this.fn = a;
        this.scope = b;
        this.next = null
    }
    ;
    Mja.prototype.reset = function() {
        this.next = this.scope = this.fn = null
    }
    ;
    var Nja, Oja = !1, Pja = new Kja, Fi = function(a, b) {
        Nja || Qja();
        Oja || (Nja(),
        Oja = !0);
        Pja.add(a, b)
    }, Qja = function() {
        if (Na.Promise && Na.Promise.resolve) {
            var a = Na.Promise.resolve(void 0);
            Nja = function() {
                a.then(Rja)
            }
        } else
            Nja = function() {
                var b = Rja;
                b = Jja(b);
                typeof Na.setImmediate !== "function" || Na.Window && Na.Window.prototype && Na.Window.prototype.setImmediate == Na.setImmediate ? (qja || (qja = Ija()),
                qja(b)) : Na.setImmediate(b)
            }
    }, Rja = function() {
        for (var a; a = Pja.remove(); ) {
            try {
                a.fn.call(a.scope)
            } catch (b) {
                zd(b)
            }
            Lja.put(a)
        }
        Oja = !1
    };
    var Sja = function() {
        this.blockSize = -1
    };
    var Gi = function() {
        this.blockSize = -1;
        this.blockSize = 64;
        this.chain_ = [];
        this.buf_ = [];
        this.W_ = [];
        this.pad_ = [];
        this.pad_[0] = 128;
        for (var a = 1; a < this.blockSize; ++a)
            this.pad_[a] = 0;
        this.total_ = this.inbuf_ = 0;
        this.reset()
    };
    fb(Gi, Sja);
    Gi.prototype.reset = function() {
        this.chain_[0] = 1732584193;
        this.chain_[1] = 4023233417;
        this.chain_[2] = 2562383102;
        this.chain_[3] = 271733878;
        this.chain_[4] = 3285377520;
        this.total_ = this.inbuf_ = 0
    }
    ;
    var Tja = function(a, b, c) {
        c || (c = 0);
        var d = a.W_;
        if (typeof b === "string")
            for (var e = 0; e < 16; e++)
                d[e] = b.charCodeAt(c) << 24 | b.charCodeAt(c + 1) << 16 | b.charCodeAt(c + 2) << 8 | b.charCodeAt(c + 3),
                c += 4;
        else
            for (e = 0; e < 16; e++)
                d[e] = b[c] << 24 | b[c + 1] << 16 | b[c + 2] << 8 | b[c + 3],
                c += 4;
        for (e = 16; e < 80; e++) {
            var h = d[e - 3] ^ d[e - 8] ^ d[e - 14] ^ d[e - 16];
            d[e] = (h << 1 | h >>> 31) & 4294967295
        }
        b = a.chain_[0];
        c = a.chain_[1];
        var l = a.chain_[2]
          , m = a.chain_[3]
          , p = a.chain_[4];
        for (e = 0; e < 80; e++) {
            if (e < 40) {
                if (e < 20) {
                    h = m ^ c & (l ^ m);
                    var q = 1518500249
                } else
                    h = c ^ l ^ m,
                    q = 1859775393;
            } else
                e < 60 ? (h = c & l | m & (c | l),
                q = 2400959708) : (h = c ^ l ^ m,
                q = 3395469782);
            h = (b << 5 | b >>> 27) + h + p + q + d[e] & 4294967295;
            p = m;
            m = l;
            l = (c << 30 | c >>> 2) & 4294967295;
            c = b;
            b = h
        }
        a.chain_[0] = a.chain_[0] + b & 4294967295;
        a.chain_[1] = a.chain_[1] + c & 4294967295;
        a.chain_[2] = a.chain_[2] + l & 4294967295;
        a.chain_[3] = a.chain_[3] + m & 4294967295;
        a.chain_[4] = a.chain_[4] + p & 4294967295
    };
    Gi.prototype.update = function(a, b) {
        if (a != null) {
            b === void 0 && (b = a.length);
            for (var c = b - this.blockSize, d = 0, e = this.buf_, h = this.inbuf_; d < b; ) {
                if (h == 0)
                    for (; d <= c; )
                        Tja(this, a, d),
                        d += this.blockSize;
                if (typeof a === "string")
                    for (; d < b; ) {
                        if (e[h] = a.charCodeAt(d),
                        ++h,
                        ++d,
                        h == this.blockSize) {
                            Tja(this, e);
                            h = 0;
                            break
                        }
                    }
                else
                    for (; d < b; )
                        if (e[h] = a[d],
                        ++h,
                        ++d,
                        h == this.blockSize) {
                            Tja(this, e);
                            h = 0;
                            break
                        }
            }
            this.inbuf_ = h;
            this.total_ += b
        }
    }
    ;
    Gi.prototype.digest = function() {
        var a = []
          , b = this.total_ * 8;
        this.inbuf_ < 56 ? this.update(this.pad_, 56 - this.inbuf_) : this.update(this.pad_, this.blockSize - (this.inbuf_ - 56));
        for (var c = this.blockSize - 1; c >= 56; c--)
            this.buf_[c] = b & 255,
            b /= 256;
        Tja(this, this.buf_);
        for (c = b = 0; c < 5; c++)
            for (var d = 24; d >= 0; d -= 8)
                a[b] = this.chain_[c] >> d & 255,
                ++b;
        return a
    }
    ;
    var Uja = function(a) {
        return typeof a.className == "string" ? a.className : a.getAttribute && a.getAttribute("class") || ""
    }
      , Vja = function(a) {
        return a.classList ? a.classList : Uja(a).match(/\S+/g) || []
    }
      , Hi = function(a, b) {
        typeof a.className == "string" ? a.className = b : a.setAttribute && a.setAttribute("class", b)
    }
      , Ii = function(a, b) {
        return a.classList ? a.classList.contains(b) : hc(Vja(a), b)
    }
      , Ki = function(a, b) {
        if (a.classList)
            a.classList.add(b);
        else if (!Ii(a, b)) {
            var c = Uja(a);
            Hi(a, c + (c.length > 0 ? " " + b : b))
        }
    }
      , Li = function(a, b) {
        if (a.classList)
            Array.prototype.forEach.call(b, function(e) {
                Ki(a, e)
            });
        else {
            var c = {};
            Array.prototype.forEach.call(Vja(a), function(e) {
                c[e] = !0
            });
            Array.prototype.forEach.call(b, function(e) {
                c[e] = !0
            });
            b = "";
            for (var d in c)
                b += b.length > 0 ? " " + d : d;
            Hi(a, b)
        }
    }
      , Mi = function(a, b) {
        a.classList ? a.classList.remove(b) : Ii(a, b) && Hi(a, Array.prototype.filter.call(Vja(a), function(c) {
            return c != b
        }).join(" "))
    }
      , Wja = function(a, b) {
        a.classList ? Array.prototype.forEach.call(b, function(c) {
            Mi(a, c)
        }) : Hi(a, Array.prototype.filter.call(Vja(a), function(c) {
            return !hc(b, c)
        }).join(" "))
    };
    var Ni = function() {};
    Ni.prototype.next = function() {
        return Oi
    }
    ;
    var Oi = {
        done: !0,
        value: void 0
    }
      , Pi = function(a) {
        return {
            value: a,
            done: !1
        }
    };
    Ni.prototype.__iterator__ = function() {
        return this
    }
    ;
    var Xja = function(a) {
        if (a instanceof Ni)
            return a;
        if (typeof a.__iterator__ == "function")
            return a.__iterator__(!1);
        if (Ya(a)) {
            var b = 0
              , c = new Ni;
            c.next = function() {
                for (; ; ) {
                    if (b >= a.length)
                        return Oi;
                    if (b in a)
                        return Pi(a[b++]);
                    b++
                }
            }
            ;
            return c
        }
        throw Error("Not implemented")
    }
      , Yja = function(a, b, c) {
        if (Ya(a))
            Zb(a, b, c);
        else
            for (a = Xja(a); ; ) {
                var d = a.next();
                if (d.done)
                    break;
                b.call(c, d.value, void 0, a)
            }
    };
    var Zja = function(a) {
        if (a instanceof Qi || a instanceof Ri || a instanceof Si)
            return a;
        if (typeof a.next == "function")
            return new Qi(function() {
                return a
            }
            );
        if (typeof a[Symbol.iterator] == "function")
            return new Qi(function() {
                return a[Symbol.iterator]()
            }
            );
        if (typeof a.__iterator__ == "function")
            return new Qi(function() {
                return a.__iterator__()
            }
            );
        throw Error("Not an iterator or iterable.")
    }
      , Qi = function(a) {
        this.func_ = a
    };
    Qi.prototype.__iterator__ = function() {
        return new Ri(this.func_())
    }
    ;
    Qi.prototype[Symbol.iterator] = function() {
        return new Si(this.func_())
    }
    ;
    Qi.prototype.toEs6 = function() {
        return new Si(this.func_())
    }
    ;
    var Ri = function(a) {
        this.JSC$6599_iter_ = a
    };
    k(Ri, Ni);
    Ri.prototype.next = function() {
        return this.JSC$6599_iter_.next()
    }
    ;
    Ri.prototype[Symbol.iterator] = function() {
        return new Si(this.JSC$6599_iter_)
    }
    ;
    Ri.prototype.toEs6 = function() {
        return new Si(this.JSC$6599_iter_)
    }
    ;
    var Si = function(a) {
        Qi.call(this, function() {
            return a
        });
        this.JSC$6602_iter_ = a
    };
    k(Si, Qi);
    Si.prototype.next = function() {
        return this.JSC$6602_iter_.next()
    }
    ;
    var $ja = function(a) {
        try {
            return Na.JSON.parse(a)
        } catch (b) {}
        a = String(a);
        if (/^\s*$/.test(a) ? 0 : /^[\],:{}\s\u2028\u2029]*$/.test(a.replace(/\\["\\\/bfnrtu]/g, "@").replace(/(?:"[^"\\\n\r\u2028\u2029\x00-\x08\x0a-\x1f]*"|true|false|null|-?\d+(?:\.\d*)?(?:[eE][+\-]?\d+)?)[\s\u2028\u2029]*(?=:|,|]|}|$)/g, "]").replace(/(?:^|:|,)(?:[\s\u2028\u2029]*\[)+/g, "")))
            try {
                return eval("(" + a + ")")
            } catch (b) {}
        throw Error("Invalid JSON string: " + a)
    }
      , Ti = function(a) {
        return new aka().serialize(a)
    }
      , aka = function() {};
    aka.prototype.serialize = function(a) {
        var b = [];
        bka(this, a, b);
        return b.join("")
    }
    ;
    var bka = function(a, b, c) {
        if (b == null)
            c.push("null");
        else {
            if (typeof b == "object") {
                if (Array.isArray(b)) {
                    var d = b;
                    b = d.length;
                    c.push("[");
                    for (var e = "", h = 0; h < b; h++)
                    k(eY, I);
    eY.prototype.onDataChanged = function() {
        this.data && (this.isCollapsed = !this.data.startExpanded)
    }
    ;
    eY.prototype.onExpandCollapse = function() {
        this.isCollapsed = !this.isCollapsed
    }
    ;
    eY.prototype.updateExpandCollapseButton = function() {
        if (this.isCollapsed) {
            var a;
            this.expandCollapseButton = A((a = this.data) == null ? void 0 : a.expandButton, Uu)
        } else {
            var b;
            this.expandCollapseButton = A((b = this.data) == null ? void 0 : b.collapseButton, Uu)
        }
    }
    ;
    var fY = eY;
    fY.prototype.updateExpandCollapseButton = fY.prototype.updateExpandCollapseButton;
    fY.prototype.onDataChanged = fY.prototype.onDataChanged;
    u([J(X.YtRendererBehavior), v("design:type", Object)], fY.prototype, "ytRendererBehavior", void 0);
    u([P(), v("design:type", Object)], fY.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], fY.prototype, "isCollapsed", void 0);
    u([P(), v("design:type", Object)], fY.prototype, "expandCollapseButton", void 0);
    u([Wy("data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], fY.prototype, "onDataChanged", null);
    u([Wy("data", "isCollapsed"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], fY.prototype, "updateExpandCollapseButton", null);
    fY = u([R({
        disableElementRegistration: !0,
        is: "ytd-sponsorships-expandable-perks-renderer"
    })], fY);
    U(fY, "ytd-sponsorships-expandable-perks-renderer", function() {
        if (Zjc !== void 0)
            return Zjc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div class=\"badged-title style-scope ytd-sponsorships-expandable-perks-renderer\">\n  <yt-img-shadow thumbnail=\"[[data.badge]]\" class=\"style-scope ytd-sponsorships-expandable-perks-renderer\"></yt-img-shadow>\n  <yt-formatted-string text=\"[[data.title]]\" class=\"style-scope ytd-sponsorships-expandable-perks-renderer\"></yt-formatted-string>\n</div>\n<yt-formatted-string class=\"subtitle style-scope ytd-sponsorships-expandable-perks-renderer\" text=\"[[data.subtitle]]\"></yt-formatted-string>\n<hr class=\"style-scope ytd-sponsorships-expandable-perks-renderer\">\n<yt-formatted-string class=\"expandable-heading style-scope ytd-sponsorships-expandable-perks-renderer\" text=\"[[data.expandableHeader]]\"></yt-formatted-string>\n<ytd-button-renderer class=\"end-button style-scope ytd-sponsorships-expandable-perks-renderer\" data=\"[[data.endButton.buttonRenderer]]\"></ytd-button-renderer>\n<ytd-button-renderer class=\"bottom-button style-scope ytd-sponsorships-expandable-perks-renderer\" data=\"[[data.bottomButton.buttonRenderer]]\"></ytd-button-renderer>\n<ytd-button-renderer class=\"expand-collapse-button style-scope ytd-sponsorships-expandable-perks-renderer\" data=\"[[expandCollapseButton]]\" noink=\"\" on-click=\"onExpandCollapse\"></ytd-button-renderer>\n\n<div class=\"expandable-content style-scope ytd-sponsorships-expandable-perks-renderer\">\n  <template is=\"dom-repeat\" items=\"[[data.expandableItems]]\" as=\"item\" class=\"style-scope ytd-sponsorships-expandable-perks-renderer\">\n    <ytd-sponsorships-perk-renderer data=\"[[item.sponsorshipsPerkRenderer]]\" class=\"style-scope ytd-sponsorships-expandable-perks-renderer\"></ytd-sponsorships-perk-renderer>\n  </template>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Zjc = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j022") ? 1 : 2
    });
    var fkc;
    var gkc = function() {
        return I.apply(this, arguments) || this
    };
    k(gkc, I);
    gkc.prototype.handleAction = function() {
        this.data && this.data.command && this.ytComponentBehavior.resolveCommand(this.data.command)
    }
    ;
    var hY = gkc;
    u([J(JA.YtComponentBehavior), v("design:type", Object)], hY.prototype, "ytComponentBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], hY.prototype, "ytRendererBehavior", void 0);
    u([P(), v("design:type", Object)], hY.prototype, "data", void 0);
    hY = u([R({
        disableElementRegistration: !0,
        is: "ytd-sponsorships-actionable-message-renderer"
    })], hY);
    U(hY, "ytd-sponsorships-actionable-message-renderer", function() {
        if (fkc !== void 0)
            return fkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><button on-click=\"handleAction\" class=\"style-scope ytd-sponsorships-actionable-message-renderer\">\n  <yt-img-shadow id=\"icon\" height=\"24\" thumbnail=\"[[data.icon]]\" width=\"24\" class=\"style-scope ytd-sponsorships-actionable-message-renderer\"></yt-img-shadow>\n  <yt-formatted-string id=\"title\" text=\"[[data.title]]\" class=\"style-scope ytd-sponsorships-actionable-message-renderer\"></yt-formatted-string>\n</button>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return fkc = a
    }, {
        mode: 1
    });
    var hkc;
    var ikc = function() {
        return I.apply(this, arguments) || this
    };
    k(ikc, I);
    f = ikc.prototype;
    f.configureRendererStamper = function() {
        return {
            "data.expandableItems": {
                id: "content-container",
                mapping: {
                    sponsorshipsPerksRenderer: {
                        component: "ytd-sponsorships-perks-renderer"
                    },
                    sponsorshipsTierRenderer: {
                        component: "ytd-sponsorships-tier-renderer"
                    }
                }
            }
        }
    }
    ;
    f.getExpansionIcon = function(a) {
        return a ? "yt-icons:arrow_drop_up" : "yt-icons:arrow_drop_down"
    }
    ;
    f.onToggleExpand = function() {
        this.data.expandableItems && this.set("expanded", !this.get("expanded"))
    }
    ;
    f.computeMessageContainerStyle = function(a) {
        var b = a.expandableItems ? " style-clickable" : "";
        return a.messageContainerStyle ? a.messageContainerStyle.split("MESSAGE_CONTAINER_")[1].replace(/_/g, "-").toLowerCase() + b : "style-unspecified" + b
    }
    ;
    f.isSinglePerk = function(a) {
        return !!a.messageContainerStyle && (a.messageContainerStyle === "MESSAGE_CONTAINER_STYLE_SINGLE_PERK" || a.messageContainerStyle === "MESSAGE_CONTAINER_STYLE_SINGLE_PERK_FIRST")
    }
    ;
    f.onExpandedChanged = function() {
        var a = this;
        if (this.expanded)
            for (var b = g(this.hostElement.querySelectorAll("yt-img-shadow")), c = b.next(); !c.done; c = b.next())
                c.value.onShow();
        ht(this, function() {
            zv(a.hostElement, "yt-refit")
        })
    }
    ;
    f.onDataChanged = function() {
        this.get("data.startExpanded") && (this.expanded = !0)
    }
    ;
    var iY = ikc;
    iY.prototype.onDataChanged = iY.prototype.onDataChanged;
    iY.prototype.onExpandedChanged = iY.prototype.onExpandedChanged;
    u([J(X.YtRendererBehavior), v("design:type", Object)], iY.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], iY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], iY.prototype, "data", void 0);
    u([P({
        value: !1
    }), v("design:type", Boolean)], iY.prototype, "expanded", void 0);
    u([O("expanded"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], iY.prototype, "onExpandedChanged", null);
    u([O("data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], iY.prototype, "onDataChanged", null);
    iY = u([R({
        disableElementRegistration: !0,
        is: "ytd-sponsorships-expandable-message-renderer"
    })], iY);
    U(iY, "ytd-sponsorships-expandable-message-renderer", function() {
        if (hkc !== void 0)
            return hkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div class$=\"[[computeMessageContainerStyle(data)]] style-scope ytd-sponsorships-expandable-message-renderer\" class=\"style-scope ytd-sponsorships-expandable-message-renderer\">\n  <button id=\"message-container\" on-tap=\"onToggleExpand\" class=\"style-scope ytd-sponsorships-expandable-message-renderer\">\n    <template is=\"dom-if\" if=\"[[isSinglePerk(data)]]\" class=\"style-scope ytd-sponsorships-expandable-message-renderer\">\n      <yt-icon id=\"check-icon\" icon=\"yt-icons:check\" class=\"style-scope ytd-sponsorships-expandable-message-renderer\"></yt-icon>\n    </template>\n    <yt-formatted-string class=\"text style-scope ytd-sponsorships-expandable-message-renderer\" text=\"[[data.text]]\"></yt-formatted-string>\n    <template is=\"dom-if\" if=\"[[data.expandableItems]]\" class=\"style-scope ytd-sponsorships-expandable-message-renderer\">\n      <yt-icon id=\"expand-icon\" icon=\"[[getExpansionIcon(expanded)]]\" class=\"style-scope ytd-sponsorships-expandable-message-renderer\"></yt-icon>\n    </template>\n  </button>\n  <div id=\"content-container\" hidden=\"[[!expanded]]\" class=\"style-scope ytd-sponsorships-expandable-message-renderer\"></div>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return hkc = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j022") ? 1 : 2
    });
    var jkc;
    var kkc = function() {
        return I.apply(this, arguments) || this
    };
    k(kkc, I);
    kkc.prototype.configureRendererStamper = function() {
        return {
            "data.endButton": {
                id: "end-button",
                mapping: {
                    buttonRenderer: {
                        component: "ytd-button-renderer"
                    }
                }
            },
            "data.bottomButton": {
                id: "bottom-button",
                mapping: {
                    buttonRenderer: {
                        component: "ytd-button-renderer"
                    }
                }
            }
        }
    }
    ;
    kkc.prototype.onDataChanged = function() {
        this.get("data.endButton.buttonRenderer.text") && this.get("data.endButton.buttonRenderer.icon") && (A(this.data.endButton, Uu).iconPosition = "BUTTON_ICON_POSITION_TYPE_RIGHT_OF_TEXT")
    }
    ;
    var jY = kkc;
    jY.prototype.onDataChanged = jY.prototype.onDataChanged;
    u([J(X.YtRendererBehavior), v("design:type", Object)], jY.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], jY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], jY.prototype, "data", void 0);
    u([O("data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], jY.prototype, "onDataChanged", null);
    jY = u([R({
        disableElementRegistration: !0,
        is: "ytd-sponsorships-heading-renderer"
    })], jY);
    U(jY, "ytd-sponsorships-heading-renderer", function() {
        if (jkc !== void 0)
            return jkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"content\" class=\"style-scope ytd-sponsorships-heading-renderer\">\n  <yt-formatted-string id=\"title\" text=\"[[data.title]]\" class=\"style-scope ytd-sponsorships-heading-renderer\"></yt-formatted-string>\n  <div id=\"subtitle-content\" hidden=\"[[!data.subtitle]]\" class=\"style-scope ytd-sponsorships-heading-renderer\">\n    <yt-img-shadow id=\"subtitle-icon\" hidden=\"[[!data.subtitleIcon]]\" thumbnail=\"[[data.subtitleIcon]]\" class=\"style-scope ytd-sponsorships-heading-renderer\">\n    </yt-img-shadow>\n    <yt-formatted-string id=\"subtitle\" text=\"[[data.subtitle]]\" class=\"style-scope ytd-sponsorships-heading-renderer\"></yt-formatted-string>\n  </div>\n  <div id=\"bottom-button\" class=\"style-scope ytd-sponsorships-heading-renderer\"></div>\n</div>\n<div id=\"end-button\" class=\"style-scope ytd-sponsorships-heading-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return jkc = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j022") ? 1 : 2
    });
    var lkc;
    var mkc = function() {
        return I.apply(this, arguments) || this
    };
    k(mkc, I);
    var kY = mkc;
    u([P(), v("design:type", Object)], kY.prototype, "data", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], kY.prototype, "ytRendererBehavior", void 0);
    kY = u([R({
        disableElementRegistration: !0,
        is: "ytd-sponsorships-links-renderer"
    })], kY);
    U(kY, "ytd-sponsorships-links-renderer", function() {
        if (lkc !== void 0)
            return lkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><template is=\"dom-repeat\" items=\"[[data.links]]\" class=\"style-scope ytd-sponsorships-links-renderer\">\n  <yt-formatted-string class=\"link style-scope ytd-sponsorships-links-renderer\" link-inherit-color=\"\" text=\"[[item]]\">\n</yt-formatted-string></template>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return lkc = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j022") ? 1 : 2
    });
    var nkc;
    var okc = function() {
        return I.apply(this, arguments) || this
    };
    k(okc, I);
    f = okc.prototype;
    f.onDataChanged = function() {
        if (this.data && this.data.expandableItems) {
            var a;
            (a = T(this.hostElement).querySelector("tp-yt-paper-button")) == null || a.setAttribute("role", "button")
        } else {
            var b;
            (b = T(this.hostElement).querySelector("tp-yt-paper-button")) == null || b.removeAttribute("role")
        }
    }
    ;
    f.onToggleExpand = function() {
        this.data && this.data.expandableItems && this.set("expanded", !this.get("expanded"))
    }
    ;
    f.getExpansionIcon = function(a) {
        return a ? "yt-icons:arrow_drop_up" : "yt-icons:arrow_drop_down"
    }
    ;
    f.getTileClasses = function(a) {
        return a ? "tile expandable-tile" : "tile"
    }
    ;
    f.getButtonDisabled = function(a) {
        return a ? void 0 : ""
    }
    ;
    var lY = okc;
    lY.prototype.onDataChanged = lY.prototype.onDataChanged;
    u([J(X.YtRendererBehavior), v("design:type", Object)], lY.prototype, "ytRendererBehavior", void 0);
    u([P(), v("design:type", Object)], lY.prototype, "data", void 0);
    u([P({
        value: !1
    }), v("design:type", Boolean)], lY.prototype, "expanded", void 0);
    u([O("data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], lY.prototype, "onDataChanged", null);
    lY = u([R({
        disableElementRegistration: !0,
        is: "ytd-sponsorships-list-tile-renderer"
    })], lY);
    U(lY, "ytd-sponsorships-list-tile-renderer", function() {
        if (nkc !== void 0)
            return nkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><tp-yt-paper-button id=\"tile\" class=\"tile style-scope ytd-sponsorships-list-tile-renderer\" class$=\"[[getTileClasses(data.expandableItems)]]\" disabled$=\"[[getButtonDisabled(data.expandableItems)]]\" noink=\"\" on-tap=\"onToggleExpand\">\n  <yt-img-shadow class=\"icon style-scope ytd-sponsorships-list-tile-renderer\" thumbnail=\"[[data.icon]]\"></yt-img-shadow>\n  <div class=\"titles style-scope ytd-sponsorships-list-tile-renderer\">\n    <yt-formatted-string class=\"title style-scope ytd-sponsorships-list-tile-renderer\" text=\"[[data.title]]\"></yt-formatted-string>\n    <yt-formatted-string class=\"subtitle style-scope ytd-sponsorships-list-tile-renderer\" text=\"[[data.subtitle]]\"></yt-formatted-string>\n    <yt-formatted-string class=\"detail style-scope ytd-sponsorships-list-tile-renderer\" text=\"[[data.detail]]\"></yt-formatted-string>\n  </div>\n  <template is=\"dom-if\" if=\"[[data.expandableItems]]\" class=\"style-scope ytd-sponsorships-list-tile-renderer\">\n    <yt-icon class=\"expand-icon style-scope ytd-sponsorships-list-tile-renderer\" icon=\"[[getExpansionIcon(expanded)]]\"></yt-icon>\n  </template>\n</tp-yt-paper-button>\n\n<template is=\"dom-if\" if=\"[[expanded]]\" class=\"style-scope ytd-sponsorships-list-tile-renderer\">\n  <div class=\"tiles-container style-scope ytd-sponsorships-list-tile-renderer\">\n    <template is=\"dom-repeat\" items=\"[[data.expandableItems]]\" class=\"style-scope ytd-sponsorships-list-tile-renderer\">\n      <template is=\"dom-if\" if=\"[[item.sponsorshipsLoyaltyBadgesRenderer]]\" class=\"style-scope ytd-sponsorships-list-tile-renderer\">\n        <ytd-sponsorships-loyalty-badges-renderer class=\"sponsorships-loyalty-badges-renderer style-scope ytd-sponsorships-list-tile-renderer\" data=\"[[item.sponsorshipsLoyaltyBadgesRenderer]]\"></ytd-sponsorships-loyalty-badges-renderer>\n      </template>\n      <template is=\"dom-if\" if=\"[[item.sponsorshipsListTileRenderer]]\" class=\"style-scope ytd-sponsorships-list-tile-renderer\">\n        <div class=\"tile style-scope ytd-sponsorships-list-tile-renderer\">\n          <yt-img-shadow class=\"icon style-scope ytd-sponsorships-list-tile-renderer\" thumbnail=\"[[item.sponsorshipsListTileRenderer.icon]]\">\n          </yt-img-shadow>\n          <div class=\"titles style-scope ytd-sponsorships-list-tile-renderer\">\n            <yt-formatted-string class=\"title style-scope ytd-sponsorships-list-tile-renderer\" text=\"[[item.sponsorshipsListTileRenderer.title]]\">\n            </yt-formatted-string>\n            <yt-formatted-string class=\"subtitle style-scope ytd-sponsorships-list-tile-renderer\" text=\"[[item.sponsorshipsListTileRenderer.subtitle]]\">\n            </yt-formatted-string>\n          </div>\n        </div>\n      </template>\n    </template>\n  </div>\n</template>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return nkc = a
    }, {
        mode: 1
    });
    var pkc;
    var qkc;
    var rkc = function() {
        return I.apply(this, arguments) || this
    };
    k(rkc, I);
    rkc.prototype.configureRendererStamper = function() {
        return {
            "data.redeemButton": {
                id: "redeem-button",
                mapping: {
                    buttonRenderer: {
                        component: "yt-button-renderer"
                    }
                }
            }
        }
    }
    ;
    var mY = rkc;
    u([J(X.YtRendererBehavior), v("design:type", Object)], mY.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], mY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], mY.prototype, "data", void 0);
    mY = u([R({
        disableElementRegistration: !0,
        is: "ytd-sponsorships-promotion-renderer"
    })], mY);
    U(mY, "ytd-sponsorships-promotion-renderer", function() {
        if (qkc !== void 0)
            return qkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"content\" class=\"style-scope ytd-sponsorships-promotion-renderer\">\n  <div id=\"above-button\" class=\"style-scope ytd-sponsorships-promotion-renderer\">\n    <yt-formatted-string class=\"above-redeem-button-text style-scope ytd-sponsorships-promotion-renderer\" text=\"[[data.aboveRedeemButtonText]]\"></yt-formatted-string>\n    <ytd-badge-supported-renderer top-standalone-badge=\"[[data.badge]]\" class=\"style-scope ytd-sponsorships-promotion-renderer\">\n    </ytd-badge-supported-renderer>\n  </div>\n  <div id=\"redeem-button\" class=\"style-scope ytd-sponsorships-promotion-renderer\"></div>\n  <yt-formatted-string class=\"redeem-disclaimer style-scope ytd-sponsorships-promotion-renderer\" split-lines=\"true\" text=\"[[data.redeemDisclaimer]]\"></yt-formatted-string>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return qkc = a
    }, {
        mode: 1
    });
    var skc;
    var tkc = function() {
        return I.apply(this, arguments) || this
    };
    k(tkc, I);
    tkc.prototype.configureRendererStamper = function() {
        return {
            "data.button": {
                id: "purchase-button",
                mapping: {
                    buttonRenderer: {
                        component: "yt-button-renderer"
                    }
                }
            }
        }
    }
    ;
    var nY = tkc;
    u([J(X.YtRendererBehavior), v("design:type", Object)], nY.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], nY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], nY.prototype, "data", void 0);
    nY = u([R({
        disableElementRegistration: !0,
        is: "ytd-sponsorships-purchase-option-renderer"
    })], nY);
    U(nY, "ytd-sponsorships-purchase-option-renderer", function() {
        if (skc !== void 0)
            return skc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"content\" class=\"style-scope ytd-sponsorships-purchase-option-renderer\">\n  <div id=\"purchase-info\" class=\"style-scope ytd-sponsorships-purchase-option-renderer\">\n    <div id=\"header\" class=\"style-scope ytd-sponsorships-purchase-option-renderer\">\n      <yt-formatted-string class=\"purchase-text style-scope ytd-sponsorships-purchase-option-renderer\" text=\"[[data.text]]\"></yt-formatted-string>\n      <ytd-badge-supported-renderer top-standalone-badge=\"[[data.badge]]\" class=\"style-scope ytd-sponsorships-purchase-option-renderer\">\n      </ytd-badge-supported-renderer>\n    </div>\n    <yt-formatted-string class=\"disclaimer style-scope ytd-sponsorships-purchase-option-renderer\" split-lines=\"true\" text=\"[[data.disclaimer]]\"></yt-formatted-string>\n  </div>\n  <div id=\"purchase-button\" class=\"style-scope ytd-sponsorships-purchase-option-renderer\"></div>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return skc = a
    }, {
        mode: 1
    });
    var ukc;
    var vkc;
    var wkc = function() {
        return I.apply(this, arguments) || this
    };
    k(wkc, I);
    var xkc = wkc;
    u([P(), v("design:type", Object)], xkc.prototype, "data", void 0);
    xkc = u([R({
        disableElementRegistration: !0,
        is: "ytd-ypc-offer-promo-renderer"
    })], xkc);
    U(xkc, "ytd-ypc-offer-promo-renderer", function() {
        if (vkc !== void 0)
            return vkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"content\" class=\"style-scope ytd-ypc-offer-promo-renderer\">\n  <yt-icon id=\"icon\" icon=\"[[data.icon.iconType]]\" class=\"style-scope ytd-ypc-offer-promo-renderer\"></yt-icon>\n  <div id=\"benefit-info\" class=\"style-scope ytd-ypc-offer-promo-renderer\">\n    <div id=\"header\" class=\"style-scope ytd-ypc-offer-promo-renderer\">\n      <yt-formatted-string class=\"title style-scope ytd-ypc-offer-promo-renderer\" text=\"[[data.title]]\">\n      </yt-formatted-string>\n    </div>\n    <div id=\"badge-section\" class=\"style-scope ytd-ypc-offer-promo-renderer\">\n      <ytd-badge-supported-renderer id=\"badge\" top-standalone-badge=\"[[data.badge]]\" class=\"style-scope ytd-ypc-offer-promo-renderer\">\n        </ytd-badge-supported-renderer>\n    <yt-formatted-string class=\"subtitle style-scope ytd-ypc-offer-promo-renderer\" text=\"[[data.subtitle]]\">\n    </yt-formatted-string>\n    </div>\n  </div>\n</div>");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return vkc = a
    }, {
        mode: 1
    });
    var ykc = function() {
        return I.apply(this, arguments) || this
    };
    k(ykc, I);
    f = ykc.prototype;
    f.configureRendererStamper = function() {
        return {
            "data.purchaseButton": {
                id: "purchase-button",
                mapping: {
                    buttonRenderer: {
                        component: "yt-button-renderer"
                    }
                }
            },
            "data.expandableMessage": {
                id: "expandable-message",
                mapping: {
                    sponsorshipsExpandableMessageRenderer: {
                        component: "ytd-sponsorships-expandable-message-renderer"
                    }
                }
            },
            "data.purchaseOption": {
                id: "purchase-option",
                mapping: {
                    sponsorshipsPurchaseOptionRenderer: {
                        component: "ytd-sponsorships-purchase-option-renderer"
                    }
                }
            },
            "data.alternativePurchaseOption": {
                id: "alternative-purchase-option",
                mapping: {
                    sponsorshipsPurchaseOptionRenderer: {
                        component: "ytd-sponsorships-purchase-option-renderer"
                    }
                }
            },
            "data.offerPromoCard": {
                id: "offer-promo",
                mapping: {
                    ypcOfferPromoRenderer: {
                        component: "ytd-ypc-offer-promo-renderer"
                    }
                }
            }
        }
    }
    ;
    f.expansionCTA = function(a, b) {
        return a && (b ? a.collapseCallToAction : a.expansionCallToAction)
    }
    ;
    f.getExpansionIcon = function(a) {
        return a ? "arrow_drop_up" : "arrow_drop_down"
    }
    ;
    f.expansionCallToActionTap = function() {
        var a = this;
        this.expanded = !this.expanded;
        ht(this, function() {
            zv(a.hostElement, "yt-refit")
        })
    }
    ;
    f.onDataChanged = function() {
        this.expanded = !this.get("data.expansionCallToAction");
        this.purchaseButtonClicked = !1;
        var a, b = (a = this.data) == null ? void 0 : a.onVisible;
        b && this.ytComponentBehavior.resolveCommand(b)
    }
    ;
    f.computeDisplayTitle = function(a) {
        return !(!a || this.titledisplaystatus !== "show")
    }
    ;
    f.computeDisplaySeparator = function() {
        return !1
    }
    ;
    f.onPurchaseButtonTap = function() {
        this.purchaseButtonClicked = !0
    }
    ;
    var oY = ykc;
    oY.prototype.onDataChanged = oY.prototype.onDataChanged;
    u([J(X.YtRendererBehavior), v("design:type", Object)], oY.prototype, "ytRendererBehavior", void 0);
    u([J(JA.YtComponentBehavior), v("design:type", Object)], oY.prototype, "ytComponentBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], oY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], oY.prototype, "data", void 0);
    u([P({
        value: !1
    }), v("design:type", Boolean)], oY.prototype, "expanded", void 0);
    u([P({
        value: !1
    }), v("design:type", Boolean)], oY.prototype, "purchaseButtonClicked", void 0);
    u([P({
        reflectToAttribute: !0,
        value: "show"
    }), v("design:type", String)], oY.prototype, "titledisplaystatus", void 0);
    u([P({
        computed: "computeDisplayTitle(data.title)"
    }), v("design:type", Boolean)], oY.prototype, "displayTitle", void 0);
    u([P({
        computed: "computeDisplaySeparator(data)"
    }), v("design:type", Boolean)], oY.prototype, "displaySeparator", void 0);
    u([Wy("data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], oY.prototype, "onDataChanged", null);
    oY = u([R({
        disableElementRegistration: !0,
        is: "ytd-sponsorships-tier-renderer"
    })], oY);
    U(oY, "ytd-sponsorships-tier-renderer", function() {
        if (ukc !== void 0)
            return ukc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady-->\n<div id=\"title\" hidden=\"[[!displayTitle]]\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n  <yt-formatted-string text=\"[[data.title]]\" class=\"style-scope ytd-sponsorships-tier-renderer\"></yt-formatted-string>\n</div>\n<div id=\"offer-promo\" hidden=\"[[!data.offerPromoCard]]\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n</div>\n<div id=\"purchase-with-options\" hidden=\"[[!data.purchaseOption]]\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n  <div id=\"purchase-option\" class=\"style-scope ytd-sponsorships-tier-renderer\"></div>\n  <div class=\"separator style-scope ytd-sponsorships-tier-renderer\" hidden=\"[[!data.alternativePurchaseOption]]\"></div>\n  <div id=\"alternative-purchase-option\" class=\"style-scope ytd-sponsorships-tier-renderer\"></div>\n</div>\n<div id=\"default-purchase-view\" hidden=\"[[data.purchaseOption]]\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n  <div id=\"above-purchase-button\" hidden=\"[[!data.abovePurchaseButtonText]]\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n    <yt-formatted-string id=\"above-purchase-button-text\" text=\"[[data.abovePurchaseButtonText]]\" class=\"style-scope ytd-sponsorships-tier-renderer\"></yt-formatted-string>\n    <yt-formatted-string id=\"above-purchase-button-text-subtitle\" class=\"subtitle style-scope ytd-sponsorships-tier-renderer\" text=\"[[data.abovePurchaseButtonTextSubtitle]]\"></yt-formatted-string>\n  </div>\n  <div id=\"premium-freebie-promo\" class=\"style-scope ytd-sponsorships-tier-renderer\"></div>\n  <div class=\"separator style-scope ytd-sponsorships-tier-renderer\" hidden=\"[[!displaySeparator]]\"></div>\n  <div id=\"header\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n    <div id=\"purchase-button\" on-tap=\"onPurchaseButtonTap\" class=\"style-scope ytd-sponsorships-tier-renderer\"></div>\n    \n    <yt-formatted-string id=\"purchase-text\" force-default-style=\"\" hidden=\"[[!data.purchaseText]]\" text=\"[[data.purchaseText]]\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n    </yt-formatted-string>\n    <yt-formatted-string class=\"disclaimer style-scope ytd-sponsorships-tier-renderer\" split-lines=\"true\" text=\"[[data.disclaimer]]\">\n    </yt-formatted-string>\n  </div>\n</div>\n<div class=\"separator style-scope ytd-sponsorships-tier-renderer\" hidden=\"[[!displaySeparator]]\"></div>\n<div id=\"expandable-message\" class=\"style-scope ytd-sponsorships-tier-renderer\"></div>\n<div id=\"content\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n  <div id=\"perks_section\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n    <ytd-sponsorships-perks-renderer id=\"perks\" data=\"[[data.perks.sponsorshipsPerksRenderer]]\" expanded=\"[[expanded]]\" class=\"style-scope ytd-sponsorships-tier-renderer\"></ytd-sponsorships-perks-renderer>\n  </div>\n  <button id=\"expansion_call_to_action\" on-tap=\"expansionCallToActionTap\" hidden=\"[[!data.expansionCallToAction]]\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n    <yt-formatted-string text=\"[[expansionCTA(data, expanded)]]\" class=\"style-scope ytd-sponsorships-tier-renderer\"></yt-formatted-string>\n    <yt-icon class=\"expand-icon style-scope ytd-sponsorships-tier-renderer\" icon=\"[[getExpansionIcon(expanded)]]\"></yt-icon>\n  </button>\n</div>\n<div id=\"footer\" class=\"style-scope ytd-sponsorships-tier-renderer\">\n  <yt-formatted-string id=\"bottom-disclaimer\" class=\"disclaimer style-scope ytd-sponsorships-tier-renderer\" split-lines=\"true\" text=\"[[data.bottomDisclaimer]]\">\n  </yt-formatted-string>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return ukc = a
    }, {
        mode: 2
    });
    var zkc = function() {
        return I.apply(this, arguments) || this
    };
    k(zkc, I);
    zkc.prototype.configureRendererStamper = function() {
        return {
            "data.content": {
                id: "content",
                mapping: {
                    sponsorshipsTierRenderer: {
                        component: "ytd-sponsorships-tier-renderer"
                    },
                    sponsorshipsHeadingRenderer: {
                        component: "ytd-sponsorships-heading-renderer"
                    },
                    sponsorshipsListTileRenderer: {
                        component: "ytd-sponsorships-list-tile-renderer"
                    },
                    sponsorshipsExpandableMessageRenderer: {
                        component: "ytd-sponsorships-expandable-message-renderer"
                    }
                }
            },
            "data.sidebar": {
                id: "sidebar",
                mapping: {
                    sponsorshipsHeadingRenderer: {
                        component: "ytd-sponsorships-heading-renderer"
                    },
                    sponsorshipsActionableMessageRenderer: {
                        component: "ytd-sponsorships-actionable-message-renderer"
                    },
                    sponsorshipsLinksRenderer: {
                        component: "ytd-sponsorships-links-renderer"
                    },
                    sponsorshipsListTileRenderer: {
                        component: "ytd-sponsorships-list-tile-renderer"
                    }
                }
            },
            "data.alert": {
                id: "alert-renderer",
                mapping: {
                    sponsorshipsAlertRenderer: {
                        component: "ytd-sponsorships-alert-renderer"
                    }
                }
            }
        }
    }
    ;
    var pY = zkc;
    u([J(X.YtRendererBehavior), v("design:type", Object)], pY.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], pY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], pY.prototype, "data", void 0);
    pY = u([R({
        disableElementRegistration: !0,
        is: "ytd-sponsorships-management-renderer"
    })], pY);
    U(pY, "ytd-sponsorships-management-renderer", function() {
        if (pkc !== void 0)
            return pkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"alert-renderer\" class=\"style-scope ytd-sponsorships-management-renderer\"></div>\n<div id=\"main-section\" class=\"style-scope ytd-sponsorships-management-renderer\">\n  <div id=\"content\" class=\"style-scope ytd-sponsorships-management-renderer\"></div>\n  <div id=\"sidebar\" class=\"style-scope ytd-sponsorships-management-renderer\"></div>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return pkc = a
    }, {
        mode: 1
    });
    var Akc;
    var Bkc = function() {
        return I.apply(this, arguments) || this
    };
    k(Bkc, I);
    var qY = Bkc;
    u([J(X.YtRendererBehavior), v("design:type", Object)], qY.prototype, "ytRendererBehavior", void 0);
    u([P(), v("design:type", Object)], qY.prototype, "data", void 0);
    qY = u([R({
        disableElementRegistration: !0,
        is: "ytd-open-in-native-app-view-model"
    })], qY);
    U(qY, "ytd-open-in-native-app-view-model", function() {
        if (Akc !== void 0)
            return Akc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><yt-attributed-string id=\"title\" data=\"[[data.title]]\" class=\"style-scope ytd-open-in-native-app-view-model\">\n</yt-attributed-string>\n<yt-image id=\"image\" data=\"[[data.image]]\" ftl-eligible=\"\" height=\"162\" width=\"200\" class=\"style-scope ytd-open-in-native-app-view-model\">\n</yt-image>\n<yt-attributed-string id=\"text\" data=\"[[data.detailsText]]\" class=\"style-scope ytd-open-in-native-app-view-model\">\n</yt-attributed-string>\n<yt-attributed-string id=\"link\" data=\"[[data.learnMoreLink]]\" force-default-style=\"\" class=\"style-scope ytd-open-in-native-app-view-model\">\n</yt-attributed-string>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Akc = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j028") ? 1 : 2
    });
    function rY(a, b) {
        if (typeof a !== "object")
            return null;
        a = g(Object.entries(a));
        for (var c = a.next(); !c.done; c = a.next()) {
            var d = g(c.value);
            c = d.next().value;
            d = d.next().value;
            if (c === b)
                return c;
            if (d = rY(d, b))
                return c + "." + d
        }
        return null
    }
    function sY(a) {
        var b = a.content;
        return (a = a.styleRuns) && b ? {
            runs: a.map(function(c) {
                var d = {
                    text: b.slice(c.startIndex, c.startIndex + c.length)
                };
                c.fontColor && (d.textColor = c.fontColor);
                return d
            })
        } : {
            simpleText: b
        }
    }
    ;var Ckc;
    var Dkc;
    var Ekc = function() {
        return I.apply(this, arguments) || this
    };
    k(Ekc, I);
    Ekc.prototype.configureRendererStamper = function() {
        return {
            "data.summaryText": {
                id: "summary-text",
                mapping: {
                    cardItemTextRenderer: "yt-card-item-text-renderer",
                    cardItemTextWithButtonRenderer: {
                        component: "yt-card-item-text-with-button-renderer",
                        params: {
                            iconSize: 18
                        }
                    }
                }
            },
            "data.additionalMetadataText": {
                id: "additional-metadata-text",
                mapping: {
                    cardItemTextRenderer: "yt-card-item-text-renderer"
                }
            },
            "data.price": {
                id: "price",
                mapping: {
                    cardItemTextRenderer: "yt-card-item-text-renderer"
                }
            }
        }
    }
    ;
    var tY = Ekc;
    u([J(X.YtRendererBehavior), v("design:type", Object)], tY.prototype, "ytRendererBehavior", void 0);
    u([J(JA.YtComponentBehavior), v("design:type", Object)], tY.prototype, "ytComponentBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], tY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], tY.prototype, "data", void 0);
    tY = u([R({
        disableElementRegistration: !0,
        is: "ytd-commerce-cart-summary-line-item-renderer"
    })], tY);
    U(tY, "ytd-commerce-cart-summary-line-item-renderer", function() {
        if (Dkc !== void 0)
            return Dkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"summary-content\" class=\"style-scope ytd-commerce-cart-summary-line-item-renderer\">\n  <div id=\"summary-text\" class=\"style-scope ytd-commerce-cart-summary-line-item-renderer\"></div>\n  <div id=\"additional-metadata-text\" class=\"style-scope ytd-commerce-cart-summary-line-item-renderer\"></div>\n</div>\n<div id=\"price\" class=\"style-scope ytd-commerce-cart-summary-line-item-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Dkc = a
    }, {
        mode: 1
    });
    YB("cardItemSection", "commerceCartCheckoutButtonRenderer", {
        component: "ytd-commerce-cart-checkout-button-renderer",
        noInjection: !0,
        properties: {
            compact: "[[compact]]"
        }
    });
    var Fkc = function() {
        var a = I.apply(this, arguments) || this;
        a.hidden = !1;
        return a
    };
    k(Fkc, I);
    f = Fkc.prototype;
    f.configureRendererStamper = function() {
        return {
            "data.estimatedTotalLineItem": {
                id: "estimated-total-line-item",
                mapping: {
                    commerceCartSummaryLineItemRenderer: "ytd-commerce-cart-summary-line-item-renderer"
                }
            },
            "data.checkoutButton": {
                id: "checkout-button",
                mapping: {
                    buttonRenderer: {
                        component: "yt-button-renderer"
                    }
                }
            },
            "data.cartButton": {
                id: "cart-button",
                mapping: {
                    buttonRenderer: {
                        component: "yt-button-renderer"
                    }
                }
            }
        }
    }
    ;
    f.entityChanged = function() {
        this.commerceCartCheckoutButtonEntity && (this.updateCheckoutButton(),
        this.updateIsHidden(),
        this.updateSummary())
    }
    ;
    f.updateSummary = function() {
        var a = this.commerceCartCheckoutButtonEntity, b;
        if (((b = this.data) == null ? 0 : b.cartButton) && a.checkoutSummaryText) {
            var c, d = rY((c = this.data) == null ? void 0 : c.estimatedTotalLineItem, "summaryText");
            this.set("data.estimatedTotalLineItem." + d + ".cardItemTextRenderer.text", sY(a.checkoutSummaryText));
            if (a.checkoutDetailText) {
                var e;
                c = rY((e = this.data) == null ? void 0 : e.estimatedTotalLineItem, "price");
                this.set("data.estimatedTotalLineItem." + c + ".cardItemTextRenderer.text", sY(a.checkoutDetailText))
            }
            if (a.checkoutAdditionalMetadataText) {
                var h;
                e = rY((h = this.data) == null ? void 0 : h.estimatedTotalLineItem, "additionalMetadataText");
                this.set("data.estimatedTotalLineItem." + e + ".cardItemTextRenderer.text", sY(a.checkoutAdditionalMetadataText))
            }
        } else
            a.estimatedTotalPrice && (h = rY((d = this.data) == null ? void 0 : d.estimatedTotalLineItem, "price"),
            this.set("data.estimatedTotalLineItem." + h + ".cardItemTextRenderer.text", sY(a.estimatedTotalPrice)))
    }
    ;
    f.updateIsHidden = function() {
        var a, b = (a = this.commerceCartCheckoutButtonEntity) == null ? void 0 : a.isHidden;
        b !== void 0 && (this.hidden = b)
    }
    ;
    f.updateCheckoutButton = function() {
        var a, b = (a = this.commerceCartCheckoutButtonEntity) == null ? void 0 : a.isDisabled;
        b !== void 0 && this.set("data.checkoutButton.buttonRenderer.isDisabled", b);
        var c;
        a = (c = this.commerceCartCheckoutButtonEntity.checkoutButtonCommand) == null ? void 0 : c.innertubeCommand;
        a !== void 0 && this.set("data.checkoutButton.buttonRenderer.command", a);
        var d;
        c = (d = this.commerceCartCheckoutButtonEntity) == null ? void 0 : d.checkoutButtonText;
        c !== void 0 && this.set("data.checkoutButton.buttonRenderer.text", {
            simpleText: c
        })
    }
    ;
    var uY = Fkc;
    uY.prototype.entityChanged = uY.prototype.entityChanged;
    u([J(Xz), v("design:type", Object)], uY.prototype, "ytdReduxBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], uY.prototype, "ytRendererBehavior", void 0);
    u([J(JA.YtComponentBehavior), v("design:type", Object)], uY.prototype, "ytComponentBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], uY.prototype, "ytRendererstamperBehavior", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], uY.prototype, "fullWidth", void 0);
    u([P(), v("design:type", Object)], uY.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], uY.prototype, "compact", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], uY.prototype, "hidden", void 0);
    u([P({
        selectorArgs: ["data.commerceCartCheckoutButtonEntityKey"],
        selector: qhb
    }), v("design:type", Object)], uY.prototype, "commerceCartCheckoutButtonEntity", void 0);
    u([O("commerceCartCheckoutButtonEntity", "data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], uY.prototype, "entityChanged", null);
    uY = u([R({
        disableElementRegistration: !0,
        is: "ytd-commerce-cart-checkout-button-renderer"
    })], uY);
    U(uY, "ytd-commerce-cart-checkout-button-renderer", function() {
        if (Ckc !== void 0)
            return Ckc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"estimated-total-line-item\" class=\"style-scope ytd-commerce-cart-checkout-button-renderer\"></div>\n<div id=\"checkout-button\" class=\"style-scope ytd-commerce-cart-checkout-button-renderer\"></div>\n<div id=\"cart-button\" class=\"style-scope ytd-commerce-cart-checkout-button-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Ckc = a
    }, {
        mode: 2
    });
    var Gkc;
    YB("cardItemSection", "commerceCartHeaderRenderer", {
        component: "ytd-commerce-cart-header-renderer",
        noInjection: !0
    });
    var Hkc = function() {
        var a = I.apply(this, arguments) || this;
        a.hidden = !1;
        return a
    };
    k(Hkc, I);
    f = Hkc.prototype;
    f.configureRendererStamper = function() {
        return {
            "data.item": {
                id: "item",
                mapping: {
                    cardItemRenderer: "yt-card-item-renderer"
                }
            }
        }
    }
    ;
    f.entityChanged = function() {
        this.commerceCartHeaderEntity && (this.updateIsHidden(),
        this.updateSummaryText(),
        this.updateCheckoutButton(),
        this.updateTitle())
    }
    ;
    f.updateIsHidden = function() {
        if (this.compact)
            this.hidden = !1;
        else {
            var a, b = (a = this.commerceCartHeaderEntity) == null ? void 0 : a.isHidden;
            b !== void 0 && (this.hidden = b)
        }
    }
    ;
    f.updateTitle = function() {
        var a = this.commerceCartHeaderEntity.isDisabled, b, c, d = (c = A((b = this.data) == null ? void 0 : b.item, BTb)) == null ? void 0 : c.headingRenderer;
        d && (b = rY(d, "textRenderers"),
        this.set("data.item.cardItemRenderer.headingRenderer." + b + ".0.cardItemTextRenderer.textColor", a ? "CARD_ITEM_COLOR_TEXT_DISABLED" : "CARD_ITEM_COLOR_TEXT_PRIMARY"))
    }
    ;
    f.updateSummaryText = function() {
        var a = this.commerceCartHeaderEntity;
        if (this.compact) {
            var b, c, d = (c = A((b = this.data) == null ? void 0 : b.item, BTb)) == null ? void 0 : c.headingRenderer;
            d && (b = rY(d, "textRenderers"),
            this.set("data.item.cardItemRenderer.headingRenderer." + b + ".1.cardItemTextRenderer.text", a.shortHeaderSummaryText ? sY(a.shortHeaderSummaryText) : a.headerSummaryText ? sY(a.headerSummaryText) : ""))
        } else {
            var e;
            if (b = (e = A((d = this.data) == null ? void 0 : d.item, BTb)) == null ? void 0 : e.additionalInfoRenderer)
                b = rY(b, "cardItemTextRenderer"),
                this.set("data.item.cardItemRenderer.additionalInfoRenderer." + b + ".text", a.headerSummaryText ? sY(a.headerSummaryText) : "")
        }
    }
    ;
    f.updateCheckoutButton = function() {
        var a = this.commerceCartHeaderEntity, b, c, d = (c = A((b = this.data) == null ? void 0 : b.item, BTb)) == null ? void 0 : c.additionalInfoRenderer;
        b = rY(d, "buttonRenderer");
        var e;
        c = (e = this.commerceCartHeaderEntity) == null ? void 0 : e.isButtonDisabled;
        var h;
        e = (h = this.commerceCartHeaderEntity) == null ? void 0 : h.isButtonHidden;
        c !== void 0 && this.set("data.item.cardItemRenderer.additionalInfoRenderer." + b + ".buttonRenderer.isDisabled", c);
        e !== void 0 && this.set("data.item.cardItemRenderer.additionalInfoRenderer.isHidden", e);
        var l;
        a = (l = a.checkoutButtonCommand) == null ? void 0 : l.innertubeCommand;
        a !== void 0 && this.set("data.item.cardItemRenderer.additionalInfoRenderer." + b + ".buttonRenderer.command", a)
    }
    ;
    var vY = Hkc;
    vY.prototype.entityChanged = vY.prototype.entityChanged;
    u([J(Xz), v("design:type", Object)], vY.prototype, "ytdReduxBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], vY.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], vY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], vY.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], vY.prototype, "compact", void 0);
    u([P({
        selectorArgs: ["data.commerceCartHeaderEntityKey"],
        selector: function(a, b) {
            return iw(a.entities, "commerceCartHeaderEntity", b)
        }
    }), v("design:type", Object)], vY.prototype, "commerceCartHeaderEntity", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], vY.prototype, "hidden", void 0);
    u([O("commerceCartHeaderEntity", "data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], vY.prototype, "entityChanged", null);
    vY = u([R({
        disableElementRegistration: !0,
        is: "ytd-commerce-cart-header-renderer"
    })], vY);
    U(vY, "ytd-commerce-cart-header-renderer", function() {
        if (Gkc !== void 0)
            return Gkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"item\" class=\"style-scope ytd-commerce-cart-header-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Gkc = a
    }, {
        mode: 1
    });
    var Ikc;
    var wY = function() {
        var a = I.apply(this, arguments) || this;
        a.hidden = !1;
        return a
    };
    k(wY, I);
    wY.prototype.onSelect = function() {
        this.data && this.data.onSelectCommand && Hv(this.hostElement, [this.data.onSelectCommand])
    }
    ;
    wY.prototype.computeHidden = function(a) {
        return !!a
    }
    ;
    da.Object.defineProperties(wY.prototype, {
        label: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return this.ytRendererBehavior.getSimpleString(this.data.label)
            }
        },
        value: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                if (this.data && (typeof this.data.stringValue === "string" || typeof this.data.int32Value === "number"))
                    return this.data.stringValue ? this.data.stringValue : this.data.int32Value
            }
        }
    });
    var xY = wY;
    u([J(X.YtRendererBehavior), v("design:type", Object)], xY.prototype, "ytRendererBehavior", void 0);
    u([P(), v("design:type", Object)], xY.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0,
        computed: "computeHidden(data.isHidden)"
    }), v("design:type", Object)], xY.prototype, "hidden", void 0);
    u([L("data.label"), v("design:type", String), v("design:paramtypes", [])], xY.prototype, "label", null);
    u([L("data"), v("design:type", Object), v("design:paramtypes", [])], xY.prototype, "value", null);
    xY = u([R({
        is: "ytd-dropdown-item-renderer",
        disableElementRegistration: !0
    })], xY);
    U(xY, "ytd-dropdown-item-renderer", function() {
        if (Ikc !== void 0)
            return Ikc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><tp-yt-paper-item id=\"item\" aria-label$=\"[[data.accessibility.label]]\" on-tap=\"onSelect\" class=\"style-scope ytd-dropdown-item-renderer\">\n  <yt-formatted-string id=\"label\" text=\"[[data.label]]\" class=\"style-scope ytd-dropdown-item-renderer\">\n  </yt-formatted-string>\n</tp-yt-paper-item>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Ikc = a
    }, {
        mode: 1
    });
    var Jkc;
    var Kkc;
    var Lkc = function() {
        return I.apply(this, arguments) || this
    };
    k(Lkc, I);
    var yY = Lkc;
    u([J(X.YtRendererBehavior), v("design:type", Object)], yY.prototype, "ytRendererBehavior", void 0);
    u([P(), v("design:type", Object)], yY.prototype, "data", void 0);
    u([P({
        computed: "getSimpleString(data.label)"
    }), v("design:type", String)], yY.prototype, "label", void 0);
    yY = u([R({
        is: "ytd-navigation-dropdown-item-renderer",
        disableElementRegistration: !0
    })], yY);
    U(yY, "ytd-navigation-dropdown-item-renderer", function() {
        if (Kkc !== void 0)
            return Kkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady-->  <a class=\"yt-simple-endpoint style-scope ytd-navigation-dropdown-item-renderer\" href$=\"[[computeHref_(data.endpoint)]]\" data=\"[[data.endpoint]]\" aria-label$=\"[[data.accessibility.accessibilityData.label]]\">\n  <tp-yt-paper-item id=\"item\" class=\"style-scope ytd-navigation-dropdown-item-renderer\">\n    <yt-formatted-string id=\"label\" text=\"[[data.label]]\" class=\"style-scope ytd-navigation-dropdown-item-renderer\"></yt-formatted-string>\n  </tp-yt-paper-item>\n</a>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Kkc = a
    }, {
        mode: 1
    });
    var Mkc = function() {
        var a = I.apply(this, arguments) || this;
        a.disabled = !1;
        a.value = "";
        a.noLabelFloat = !1;
        a.noUnderline = !1;
        a.usePrimaryColor = !1;
        a.hasBackground = !1;
        a.verticalAlign = "top";
        a.autosize = !1;
        a.minAutosizeWidth = 100;
        a.enableRefreshWeb = y("enable_cairo_refresh_web");
        a.autosizeFont = "14px Roboto";
        return a
    };
    k(Mkc, I);
    f = Mkc.prototype;
    f.configureRendererStamper = function() {
        return {
            "data.entries": {
                id: "entries",
                mapping: {
                    dropdownItemRenderer: "ytd-dropdown-item-renderer",
                    privacyDropdownItemRenderer: "ytd-privacy-dropdown-item-renderer",
                    navigationDropdownItemRenderer: "ytd-navigation-dropdown-item-renderer"
                }
            }
        }
    }
    ;
    f.open = function() {
        this.inputEl.open()
    }
    ;
    f.reset = function() {
        this.entries.selected = -1;
        this.entries.forceSynchronousItemUpdate();
        this.entries.select(this.getSelectedItem())
    }
    ;
    f.dataChanged = function() {
        this.reset()
    }
    ;
    f.valueChangedForBinding = function() {
        this.hostElement.dispatchEvent(new RN("value-changed",this.value))
    }
    ;
    f.stopPropagation = function(a) {
        a.stopPropagation()
    }
    ;
    f.autoSizeLabel = function() {
        if (this.autosizeFont && this.autosize) {
            this.canvas || (this.canvas = document.createElement("canvas"));
            var a = this.canvas.getContext("2d");
            a && (a.font = this.autosizeFont,
            this.inputEl.style.width = Math.max(this.minAutosizeWidth, Number(a.measureText(this.inputEl.value).width) + 24) + "px")
        }
    }
    ;
    f.getSelectedItem = function() {
        if (!this.data || !this.data.entries)
            return null;
        for (var a = 0, b = this.data.entries.length; a < b; a++) {
            var c = this.data.entries[a], d;
            for (d in c)
                if (c.hasOwnProperty(d)) {
                    var e = c[d];
                    if ("isSelected"in e && e.isSelected)
                        return "stringValue"in e ? e.stringValue || "" : "int32Value"in e ? e.int32Value || 0 : 0
                }
        }
        return null
    }
    ;
    f.updateValueFromBinding = function(a) {
        this.value = a.detail.value
    }
    ;
    da.Object.defineProperties(Mkc.prototype, {
        label: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                if (!this.data || !this.data.entries)
                    return null;
                if (this.data.label)
                    return this.data.label;
                for (var a = 0, b = this.data.entries.length; a < b; a++) {
                    var c = this.data.entries[a], d;
                    for (d in c)
                        if (c.hasOwnProperty(d)) {
                            var e = c[d];
                            if ("isSelected"in e && e.isSelected && "label"in e)
                                return this.ytRendererBehavior.getSimpleString(e.label)
                        }
                }
                return null
            }
        }
    });
    var zY = Mkc;
    zY.prototype.autoSizeLabel = zY.prototype.autoSizeLabel;
    zY.prototype.stopPropagation = zY.prototype.stopPropagation;
    zY.prototype.valueChangedForBinding = zY.prototype.valueChangedForBinding;
    zY.prototype.dataChanged = zY.prototype.dataChanged;
    u([J(X.YtRendererBehavior), v("design:type", Object)], zY.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], zY.prototype, "ytRendererStamperBehavior", void 0);
    u([P(), v("design:type", Object)], zY.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], zY.prototype, "disabled", void 0);
    u([P(), v("design:type", Object)], zY.prototype, "value", void 0);
    u([P(), v("design:type", Object)], zY.prototype, "noLabelFloat", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], zY.prototype, "noUnderline", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", String)], zY.prototype, "theme", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], zY.prototype, "usePrimaryColor", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], zY.prototype, "hasBackground", void 0);
    u([P(), v("design:type", Object)], zY.prototype, "verticalAlign", void 0);
    u([P(), v("design:type", Object)], zY.prototype, "autosize", void 0);
    u([P(), v("design:type", Object)], zY.prototype, "minAutosizeWidth", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], zY.prototype, "enableRefreshWeb", void 0);
    u([P(), v("design:type", Object)], zY.prototype, "autosizeFont", void 0);
    u([Ty("#entries"), v("design:type", Object)], zY.prototype, "entries", void 0);
    u([Ty("#input"), v("design:type", Object)], zY.prototype, "inputEl", void 0);
    u([Wy("data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], zY.prototype, "dataChanged", null);
    u([Wy("value"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], zY.prototype, "valueChangedForBinding", null);
    u([M("iron-overlay-opened"), M("iron-overlay-closed"), v("design:type", Function), v("design:paramtypes", [CustomEvent]), v("design:returntype")], zY.prototype, "stopPropagation", null);
    u([M("iron-select"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], zY.prototype, "autoSizeLabel", null);
    u([L("data"), v("design:type", Object), v("design:paramtypes", [])], zY.prototype, "label", null);
    zY = u([R({
        disableElementRegistration: !0,
        is: "ytd-dropdown-renderer"
    })], zY);
    U(zY, "ytd-dropdown-renderer", function() {
        if (Jkc !== void 0)
            return Jkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><tp-yt-paper-dropdown-menu-light id=\"input\" aria-label$=\"[[label]]\" disabled=\"[[disabled]]\" horizontal-align=\"left\" label=\"[[label]]\" no-label-float=\"[[noLabelFloat]]\" vertical-align=\"[[verticalAlign]]\" class=\"style-scope ytd-dropdown-renderer\">\n  <tp-yt-paper-listbox id=\"entries\" class=\"dropdown-content style-scope ytd-dropdown-renderer\" slot=\"dropdown-content\" attr-for-selected=\"value\" selected=\"[[value]]\" on-selected-changed=\"updateValueFromBinding\">\n  </tp-yt-paper-listbox>\n</tp-yt-paper-dropdown-menu-light>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Jkc = a
    }, {
        mode: 1
    });
    var Nkc;
    var Okc = $g(function(a, b) {
        var c;
        return (c = a.onChangeCallback) == null ? void 0 : c.call(a, b)
    }, 1E3)
      , Pkc = Nz(function(a) {
        var b = a.data;
        var c = a.iconMinus;
        var d = a.iconPlus;
        var e = function() {
            return b().disabled ? b().disabled : !1
        };
        a = g(fq(0));
        var h = a.next().value
          , l = a.next().value;
        a = {};
        a = (a["yt-spec-quantity-incrementer-shape"] = !0,
        a);
        var m = Mr(function() {
            if (h() === 1) {
                var q, r;
                (r = (q = b()).onRemoveCommand) == null || r.call(q)
            }
            q = h() > b().maxValue ? b().maxValue : h() - 1;
            l(q);
            Okc(b(), q)
        })
          , p = Mr(function() {
            if (h() !== b().maxValue) {
                var q = h() + 1;
                l(q);
                Okc(b(), q)
            }
        });
        vr(function() {
            l(b().value)
        });
        return F("quantity-incrementer-shape", null, F("div", {
            class: lC(a)
        }, F("button", {
            class: "yt-spec-quantity-incrementer-shape__button",
            disabled: function() {
                return h() === (b().onRemoveCommand ? 0 : 1) || e()
            },
            "aria-label": function() {
                return h() !== 1 ? b().minusLabel : b().minimumReachedLabel
            },
            "on:click": m
        }, F($p, null, function() {
            rC({
                circular: !0
            })
        }), F("div", {
            class: "yt-spec-quantity-incrementer-shape__iconWrapper"
        }, F("div", {
            class: function() {
                var q = {};
                q = (q["yt-spec-quantity-incrementer-shape__icon"] = !0,
                q["yt-spec-quantity-incrementer-shape__icon--disabled"] = e() || h() === (b().onRemoveCommand ? 0 : 1),
                q);
                return lC(q)
            }
        }, F($p, null, function() {
            c()
        })))), F("div", {
            class: function() {
                var q = {};
                q = (q["yt-spec-quantity-incrementer-shape__text"] = !0,
                q["yt-spec-quantity-incrementer-shape__text--invalid"] = h() > b().maxValue,
                q["yt-spec-quantity-incrementer-shape__text--text-disabled"] = e(),
                q);
                return lC(q)
            }
        }, h), F("button", {
            class: "yt-spec-quantity-incrementer-shape__button",
            disabled: function() {
                return h() >= b().maxValue || e()
            },
            "aria-label": function() {
                return h() !== b().maxValue ? b().plusLabel : b().maximumReachedLabel
            },
            "on:click": p
        }, F($p, null, function() {
            rC({
                circular: !0
            })
        }), F("div", {
            class: "yt-spec-quantity-incrementer-shape__iconWrapper"
        }, F("div", {
            class: function() {
                var q = {};
                q = (q["yt-spec-quantity-incrementer-shape__icon"] = !0,
                q["yt-spec-quantity-incrementer-shape__icon--disabled"] = h() >= b().maxValue || e(),
                q);
                return lC(q)
            }
        }, F($p, null, function() {
            d()
        }))))))
    });
    Pkc.idomCompat = !0;
    function Qkc(a, b, c, d, e) {
        e && (a.quantity = e);
        if (!a.quantity || !a.maxQuantity)
            return {};
        e = a.minusButton;
        var h = a.plusButton, l, m, p, q;
        return {
            value: a.quantity,
            maxValue: a.maxQuantity,
            onChangeCallback: function(r) {
                b(a, r)
            },
            minusLabel: (l = A(e, HTb)) == null ? void 0 : l.label,
            minimumReachedLabel: (m = A(e, HTb)) == null ? void 0 : m.limitReachedLabel,
            plusLabel: (p = A(h, HTb)) == null ? void 0 : p.label,
            maximumReachedLabel: (q = A(h, HTb)) == null ? void 0 : q.limitReachedLabel,
            disabled: c,
            onRemoveCommand: d
        }
    }
    ;function Rkc(a, b) {
        var c = a.quantityIncrementerEntityKey;
        if (c) {
            var d = {};
            d.quantity = b;
            Wz(bw("quantityIncrementerEntity", c, d));
            a.onChangeCommand && HB(a.onChangeCommand)
        }
    }
    function Skc() {
        sm().resolve(wB)("BAR_HORIZONTAL", {
            className: lC("yt-spec-quantity-incrementer-view-model", "yt-spec-quantity-incrementer-view-model__quantity-incrementer-minus-icon")
        })
    }
    function Tkc() {
        sm().resolve(wB)("ADD", {
            className: lC("yt-spec-quantity-incrementer-view-model", "yt-spec-quantity-incrementer-view-model__quantity-incrementer-plus-icon")
        })
    }
    var Ukc = sC(function(a) {
        function b() {
            c.onRemoveCommand && HB(c.onRemoveCommand)
        }
        var c = a.data;
        var d, e = WC(Rob, (d = c.quantityIncrementerEntityKey) != null ? d : ""), h = kIa(function() {
            var m;
            return e() ? !((m = e()) == null || !m.disabled) : !1
        }), l = kIa(function() {
            var m;
            return e() ? (m = e()) == null ? void 0 : m.quantity : c.quantity
        });
        return F("yt-quantity-incrementer-view-model", null, F(Pkc, {
            data: function() {
                return Qkc(c, Rkc, h(), b, l())
            },
            iconMinus: Skc,
            iconPlus: Tkc
        }))
    });
    iB(Ukc, "yt-quantity-incrementer-view-model", {
        props: {
            data: gB
        }
    });
    var AY = function() {
        var a = I.apply(this, arguments) || this;
        a.compact = !1;
        a.hasQuantityIncrementer = !1;
        a.enableRefreshWeb = y("enable_cairo_refresh_web");
        return a
    };
    k(AY, I);
    AY.prototype.configureRendererStamper = function() {
        return {
            "data.picker": {
                id: "picker",
                mapping: {
                    quantityIncrementerViewModel: "yt-quantity-incrementer-view-model",
                    dropdownRenderer: {
                        component: "ytd-dropdown-renderer",
                        params: {
                            autosize: !0,
                            minAutosizeWidth: 0,
                            noUnderline: !0,
                            noLabelFloat: !0,
                            usePrimaryColor: !0
                        }
                    }
                }
            },
            "data.price": {
                id: "price",
                mapping: {
                    cardItemTextRenderer: "yt-card-item-text-renderer"
                }
            }
        }
    }
    ;
    AY.prototype.computeHasQuantityIncrementer = function() {
        var a;
        return !!A((a = this.data) == null ? void 0 : a.picker, ITb)
    }
    ;
    AY.prototype.onLabelClick = function() {
        var a;
        (a = this.dropdownEl) == null || a.open()
    }
    ;
    var BY = AY;
    u([Ty("ytd-dropdown-renderer"), v("design:type", Object)], BY.prototype, "dropdownEl", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], BY.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], BY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], BY.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", String)], BY.prototype, "quantityColor", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], BY.prototype, "compact", void 0);
    u([P({
        reflectToAttribute: !0,
        computed: "computeHasQuantityIncrementer(data)"
    }), v("design:type", Object)], BY.prototype, "hasQuantityIncrementer", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], BY.prototype, "enableRefreshWeb", void 0);
    BY = u([R({
        disableElementRegistration: !0,
        is: "ytd-commerce-cart-item-quantity-picker-renderer"
    })], BY);
    U(BY, "ytd-commerce-cart-item-quantity-picker-renderer", function() {
        if (Nkc !== void 0)
            return Nkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"picker-label\" on-click=\"onLabelClick\" class=\"style-scope ytd-commerce-cart-item-quantity-picker-renderer\">[[getSimpleString(data.pickerLabel)]]</div>\n<div id=\"picker\" class=\"style-scope ytd-commerce-cart-item-quantity-picker-renderer\"></div>\n<div id=\"price\" class=\"style-scope ytd-commerce-cart-item-quantity-picker-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Nkc = a
    }, {
        mode: 1
    });
    var Vkc;
    var Wkc;
    var CY = function() {
        return I.apply(this, arguments) || this
    };
    k(CY, I);
    CY.prototype.configureRendererStamper = function() {
        return {
            "data.actionButton": {
                id: "action-button",
                mapping: {
                    buttonRenderer: "yt-button-renderer"
                }
            }
        }
    }
    ;
    CY.prototype.entityChanged = function() {
        this.disabledCartItemEntity && (this.updateTitle(),
        this.updateButton())
    }
    ;
    CY.prototype.updateTitle = function() {
        var a = this.disabledCartItemEntity;
        a.disableActionName && this.set("data.title", sY(a.disableActionName))
    }
    ;
    CY.prototype.updateButton = function() {
        var a, b = (a = this.disabledCartItemEntity.undoCommand) == null ? void 0 : a.innertubeCommand;
        b !== void 0 && (this.set("data.actionButton.buttonRenderer.command", b),
        this.set("data.actionButton.buttonRenderer.isDisabled", !1))
    }
    ;
    var DY = CY;
    DY.prototype.entityChanged = DY.prototype.entityChanged;
    u([J(Xz), v("design:type", Object)], DY.prototype, "ytdReduxBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], DY.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], DY.prototype, "ytRendererstamperBehavior", void 0);
    u([P({
        selectorArgs: ["data.disabledCartItemEntityKey"],
        selector: function(a, b) {
            return iw(a.entities, "disabledCartItemEntity", b)
        }
    }), v("design:type", Object)], DY.prototype, "disabledCartItemEntity", void 0);
    u([P(), v("design:type", Object)], DY.prototype, "data", void 0);
    u([O("disabledCartItemEntity", "data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], DY.prototype, "entityChanged", null);
    DY = u([R({
        disableElementRegistration: !0,
        is: "ytd-disabled-cart-item-renderer"
    })], DY);
    U(DY, "ytd-disabled-cart-item-renderer", function() {
        if (Wkc !== void 0)
            return Wkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"text-container\" class=\"style-scope ytd-disabled-cart-item-renderer\">\n  <yt-formatted-string id=\"title\" text=\"[[data.title]]\" class=\"style-scope ytd-disabled-cart-item-renderer\"></yt-formatted-string>\n  <yt-formatted-string id=\"description\" text=\"[[data.description]]\" class=\"style-scope ytd-disabled-cart-item-renderer\"></yt-formatted-string>\n</div>\n<div id=\"action-button\" class=\"style-scope ytd-disabled-cart-item-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Wkc = a
    }, {
        mode: 1
    });
    YB("cardItemSection", "commerceCartItemRenderer", {
        component: "ytd-commerce-cart-item-renderer",
        noInjection: !0,
        properties: {
            compact: "[[compact]]"
        }
    });
    var Xkc = function() {
        var a = I.apply(this, arguments) || this;
        a.compact = !1;
        a.hidden = !1;
        a.errorHidden = !1;
        a.noOnTap = !1;
        return a
    };
    k(Xkc, I);
    f = Xkc.prototype;
    f.configureRendererStamper = function() {
        return {
            "data.title": {
                id: "title",
                mapping: {
                    cardItemTextRenderer: "yt-card-item-text-renderer"
                }
            },
            "data.textMetadata": {
                id: "text-metadata",
                mapping: {
                    cardItemTextRenderer: "yt-card-item-text-renderer"
                }
            },
            "data.merchantUpdateText": {
                id: "merchant-update-text",
                mapping: {
                    cardItemTextRenderer: "yt-card-item-text-renderer"
                }
            },
            "data.cartItemNotification": {
                id: "cart-item-notification",
                mapping: {
                    cardItemTextWithImageRenderer: "yt-card-item-text-with-image-renderer"
                }
            },
            "data.cardItemActions": {
                id: "cart-item-actions",
                mapping: {
                    buttonRenderer: {
                        component: "yt-button-renderer",
                        properties: {
                            disableTextTransform: "[[compact]]"
                        }
                    }
                },
                events: !0
            },
            "data.quantityPicker": {
                id: "quantity-picker",
                mapping: {
                    commerceCartItemQuantityPickerRenderer: {
                        component: "ytd-commerce-cart-item-quantity-picker-renderer",
                        properties: {
                            compact: "[[compact]]",
                            quantityColor: "[[commerceCartItemEntity.quantityColor]]"
                        }
                    }
                }
            },
            "data.disabledCartItem": {
                id: "disabled-cart-item",
                mapping: {
                    disabledCartItemRenderer: "ytd-disabled-cart-item-renderer"
                }
            }
        }
    }
    ;
    f.entityChanged = function() {
        this.commerceCartItemEntity && (this.updateQuantity(),
        this.updateIsHidden(),
        this.updateHideErrorMessage())
    }
    ;
    f.onYtRendererstamperFinished = function() {
        if (this.firstButtonElement) {
            var a = this.firstButtonElement;
            a.alignByText = !0;
            a.iconAlignByText = !0
        }
    }
    ;
    f.computeNoOnTap = function(a) {
        return !a
    }
    ;
    f.updateQuantityColor = function() {
        if (this.pickerElement) {
            var a, b = (a = this.commerceCartItemEntity) == null ? void 0 : a.quantityColor;
            this.pickerElement.quantityColor = b
        }
    }
    ;
    f.updateTotalPriceColor = function() {
        var a, b = (a = this.commerceCartItemEntity) == null ? void 0 : a.totalPriceColor;
        if (b) {
            var c;
            a = A((c = this.data) == null ? void 0 : c.quantityPicker, DTb);
            if (c = A(a == null ? void 0 : a.price, CTb))
                c.textColor = b
        }
    }
    ;
    f.updateIsHidden = function() {
        if (this.compact)
            this.hidden = !1;
        else {
            var a, b = (a = this.commerceCartItemEntity) == null ? void 0 : a.isHidden;
            b !== void 0 && (this.hidden = b)
        }
    }
    ;
    f.updateHideErrorMessage = function() {
        var a, b = (a = this.commerceCartItemEntity) == null ? void 0 : a.hideErrorMessage;
        b !== void 0 && (this.errorHidden = b)
    }
    ;
    f.updateQuantity = function() {
        var a = this, b, c = (b = this.commerceCartItemEntity) == null ? void 0 : b.quantity, d;
        b = (d = this.commerceCartItemEntity) == null ? void 0 : d.totalPrice;
        if (c) {
            this.updateTotalPriceColor();
            this.updateQuantityColor();
            var e;
            d = A((e = this.data) == null ? void 0 : e.quantityPicker, DTb);
            if (e = A(d == null ? void 0 : d.price, CTb))
                e.text = b ? {
                    simpleText: b.content
                } : void 0;
            if (b = A(d == null ? void 0 : d.picker, ITb))
                b.quantity = c;
            var h;
            if (e = (h = A(d == null ? void 0 : d.picker, KSb)) == null ? void 0 : h.entries) {
                h = !1;
                b = void 0;
                e = g(e);
                for (d = e.next(); !d.done; d = e.next())
                    d = d.value,
                    d.dropdownItemRenderer && (b || (b = d.dropdownItemRenderer),
                    d.dropdownItemRenderer.isSelected = !1,
                    c === d.dropdownItemRenderer.int32Value && (h = !0,
                    d.dropdownItemRenderer.isSelected = !0));
                !h && b && (b.isSelected = !0)
            }
            ht(this, function() {
                var l;
                a.set("data.quantityPicker", pc.unsafeClone((l = a.data) == null ? void 0 : l.quantityPicker))
            })
        }
    }
    ;
    var EY = Xkc;
    EY.prototype.onYtRendererstamperFinished = EY.prototype.onYtRendererstamperFinished;
    EY.prototype.entityChanged = EY.prototype.entityChanged;
    u([P(), v("design:type", Object)], EY.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], EY.prototype, "compact", void 0);
    u([J(Xz), v("design:type", Object)], EY.prototype, "ytdReduxBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], EY.prototype, "ytRendererBehavior", void 0);
    u([J(JA.YtComponentBehavior), v("design:type", Object)], EY.prototype, "ytComponentBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], EY.prototype, "ytRendererstamperBehavior", void 0);
    u([P({
        selectorArgs: ["data.commerceCartItemEntityKey"],
        selector: function(a, b) {
            return iw(a.entities, "commerceCartItemEntity", b)
        }
    }), v("design:type", Object)], EY.prototype, "commerceCartItemEntity", void 0);
    u([P(), v("design:type", Object)], EY.prototype, "quantityPicker", void 0);
    u([P(), v("design:type", Object)], EY.prototype, "compactQuantityPicker", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], EY.prototype, "hidden", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], EY.prototype, "errorHidden", void 0);
    u([P({
        reflectToAttribute: !0,
        computed: "computeNoOnTap(data.onTap)"
    }), v("design:type", Object)], EY.prototype, "noOnTap", void 0);
    u([Ty("ytd-commerce-cart-item-quantity-picker-renderer"), v("design:type", Object)], EY.prototype, "pickerElement", void 0);
    u([Ty("yt-button-renderer"), v("design:type", Element)], EY.prototype, "firstButtonElement", void 0);
    u([O("commerceCartItemEntity", "data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], EY.prototype, "entityChanged", null);
    u([M("yt-rendererstamper-finished"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], EY.prototype, "onYtRendererstamperFinished", null);
    EY = u([R({
        disableElementRegistration: !0,
        is: "ytd-commerce-cart-item-renderer"
    })], EY);
    U(EY, "ytd-commerce-cart-item-renderer", function() {
        if (Vkc !== void 0)
            return Vkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"container\" hidden=\"[[commerceCartItemEntity.isDisabled]]\" class=\"style-scope ytd-commerce-cart-item-renderer\">\n  <a id=\"img-container\" class=\"yt-simple-endpoint style-scope ytd-commerce-cart-item-renderer\" href$=\"[[computeHref_(data.onTap)]]\" data=\"[[data.onTap]]\" tabindex=\"-1\">\n    <yt-img-shadow id=\"image\" object-fit=\"CONTAIN\" thumbnail=\"[[data.cartItemImage]]\" width=\"200\" class=\"style-scope ytd-commerce-cart-item-renderer\">\n    </yt-img-shadow>\n  </a>\n  <div id=\"content\" class=\"style-scope ytd-commerce-cart-item-renderer\">\n    <div id=\"item\" class=\"style-scope ytd-commerce-cart-item-renderer\">\n      <div id=\"info\" class=\"style-scope ytd-commerce-cart-item-renderer\">\n        <div id=\"cart-item-notification\" class=\"style-scope ytd-commerce-cart-item-renderer\"></div>\n        <h3 class=\"style-scope ytd-commerce-cart-item-renderer\">\n            <a class=\"yt-simple-endpoint style-scope ytd-commerce-cart-item-renderer\" href$=\"[[computeHref_(data.onTap)]]\" data=\"[[data.onTap]]\">\n              <div id=\"title\" class=\"style-scope ytd-commerce-cart-item-renderer\"></div>\n            </a>\n        </h3>\n        <div id=\"text-metadata\" class=\"style-scope ytd-commerce-cart-item-renderer\"></div>\n        <div id=\"merchant-update-text\" class=\"style-scope ytd-commerce-cart-item-renderer\"></div>\n      </div>\n      <div id=\"quantity-picker\" class=\"style-scope ytd-commerce-cart-item-renderer\"></div>\n    </div>\n    <div id=\"actions\" class=\"style-scope ytd-commerce-cart-item-renderer\">\n      <div id=\"cart-item-actions\" class=\"style-scope ytd-commerce-cart-item-renderer\"></div>\n    </div>\n  </div>\n</div>\n<div id=\"disabled-cart-item\" hidden=\"[[!commerceCartItemEntity.isDisabled]]\" class=\"style-scope ytd-commerce-cart-item-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Vkc = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j028") ? 1 : 2
    });
    var Ykc;
    var Zkc;
    var FY = function() {
        return I.apply(this, arguments) || this
    };
    k(FY, I);
    FY.prototype.configureRendererStamper = function() {
        return {
            "data.summaryLineItems": {
                id: "summary-line-items",
                mapping: {
                    commerceCartSummaryLineItemRenderer: "ytd-commerce-cart-summary-line-item-renderer"
                }
            },
            "data.checkoutButton": {
                id: "checkout-button",
                mapping: {
                    commerceCartCheckoutButtonRenderer: {
                        component: "ytd-commerce-cart-checkout-button-renderer",
                        params: {
                            fullWidth: !0
                        }
                    }
                }
            }
        }
    }
    ;
    FY.prototype.entityChanged = function() {
        this.commerceCartCheckoutButtonEntity && (this.updateCheckoutLineItems(),
        this.updateIsHidden())
    }
    ;
    FY.prototype.updateCheckoutLineItems = function() {
        var a, b = (a = this.commerceCartCheckoutButtonEntity) == null ? void 0 : a.checkoutLineItems;
        b && (a = b.map(function(c) {
            a: {
                var d = c.price
                  , e = c.description;
                switch (c.style) {
                case "COMMERCE_CHECKOUT_LINE_ITEM_STYLE_MERCHANT":
                    c = {
                        commerceCartSummaryLineItemRenderer: {
                            summaryText: {
                                cardItemTextRenderer: {
                                    text: sY(e),
                                    style: "CARD_ITEM_TEXT_STYLE_BODY_2A",
                                    textColor: "CARD_ITEM_COLOR_TEXT_SECONDARY",
                                    containerMargin: {
                                        top: "CARD_ITEM_UX_SPACE_2",
                                        right: "CARD_ITEM_UX_SPACE_0",
                                        bottom: "CARD_ITEM_UX_SPACE_2",
                                        left: "CARD_ITEM_UX_SPACE_4"
                                    }
                                }
                            },
                            price: {
                                cardItemTextRenderer: {
                                    text: sY(d),
                                    style: "CARD_ITEM_TEXT_STYLE_BODY_2A",
                                    textColor: "CARD_ITEM_COLOR_TEXT_SECONDARY",
                                    containerMargin: {
                                        top: "CARD_ITEM_UX_SPACE_0",
                                        right: "CARD_ITEM_UX_SPACE_0",
                                        bottom: "CARD_ITEM_UX_SPACE_0",
                                        left: "CARD_ITEM_UX_SPACE_0"
                                    }
                                }
                            }
                        }
                    };
                    break a;
                default:
                    c = {
                        commerceCartSummaryLineItemRenderer: {
                            summaryText: {
                                cardItemTextRenderer: {
                                    text: sY(e),
                                    style: "CARD_ITEM_TEXT_STYLE_BODY_2A",
                                    textColor: "CARD_ITEM_COLOR_TEXT_PRIMARY",
                                    containerMargin: {
                                        top: "CARD_ITEM_UX_SPACE_2",
                                        right: "CARD_ITEM_UX_SPACE_0",
                                        bottom: "CARD_ITEM_UX_SPACE_2",
                                        left: "CARD_ITEM_UX_SPACE_0"
                                    }
                                }
                            },
                            price: {
                                cardItemTextRenderer: {
                                    text: sY(d),
                                    style: "CARD_ITEM_TEXT_STYLE_BODY_2A",
                                    textColor: "CARD_ITEM_COLOR_TEXT_PRIMARY",
                                    containerMargin: {
                                        top: "CARD_ITEM_UX_SPACE_0",
                                        right: "CARD_ITEM_UX_SPACE_0",
                                        bottom: "CARD_ITEM_UX_SPACE_0",
                                        left: "CARD_ITEM_UX_SPACE_0"
                                    }
                                }
                            }
                        }
                    };
                }
            }
            return c
        }),
        this.set("data.summaryLineItems", a))
    }
    ;
    FY.prototype.updateIsHidden = function() {
        var a, b = (a = this.commerceCartCheckoutButtonEntity) == null ? void 0 : a.isHidden;
        b !== void 0 && (this.hostElement.hidden = b)
    }
    ;
    var GY = FY;
    GY.prototype.entityChanged = GY.prototype.entityChanged;
    u([J(Xz), v("design:type", Object)], GY.prototype, "ytdReduxBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], GY.prototype, "ytRendererBehavior", void 0);
    u([J(JA.YtComponentBehavior), v("design:type", Object)], GY.prototype, "ytComponentBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], GY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], GY.prototype, "data", void 0);
    u([P({
        selectorArgs: ["data.commerceCartCheckoutButtonEntityKey"],
        selector: qhb
    }), v("design:type", Object)], GY.prototype, "commerceCartCheckoutButtonEntity", void 0);
    u([O("commerceCartCheckoutButtonEntity", "data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], GY.prototype, "entityChanged", null);
    GY = u([R({
        disableElementRegistration: !0,
        is: "ytd-commerce-cart-summary-renderer"
    })], GY);
    U(GY, "ytd-commerce-cart-summary-renderer", function() {
        if (Zkc !== void 0)
            return Zkc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"title\" class=\"style-scope ytd-commerce-cart-summary-renderer\">[[getSimpleString(data.title)]]</div>\n<div id=\"summary-line-items\" class=\"style-scope ytd-commerce-cart-summary-renderer\"></div>\n<div id=\"checkout-button\" class=\"style-scope ytd-commerce-cart-summary-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Zkc = a
    }, {
        mode: 1
    });
    var HY = function() {
        return I.apply(this, arguments) || this
    };
    k(HY, I);
    HY.prototype.configureRendererStamper = function() {
        return {
            "data.items": {
                id: "items",
                mapping: {
                    cardItemContainerRenderer: {
                        component: "yt-card-item-container-renderer",
                        params: {
                            compact: !1
                        }
                    },
                    commerceCartCheckoutButtonRenderer: "ytd-commerce-cart-checkout-button-renderer",
                    commerceCartHeaderRenderer: "ytd-commerce-cart-header-renderer",
                    cardItemRenderer: "yt-card-item-renderer"
                }
            },
            "data.cartSummary": {
                id: "cart-summary",
                mapping: {
                    commerceCartSummaryRenderer: "ytd-commerce-cart-summary-renderer"
                }
            }
        }
    }
    ;
    HY.prototype.notificationEntityChanged = function() {
        this.commerceCartExpandableNotificationEntity && this.updateNotification()
    }
    ;
    HY.prototype.computeLoadingHidden = function() {
        var a;
        return !((a = this.commerceCartPageStateEntity) == null ? 0 : a.cartActionInProgress)
    }
    ;
    HY.prototype.updateNotification = function() {
        var a, b = (a = this.get("commerceCartExpandableNotificationEntity")) == null ? void 0 : a.summaryText;
        b && this.set("data.cartNotification", sY(b))
    }
    ;
    var IY = HY;
    IY.prototype.notificationEntityChanged = IY.prototype.notificationEntityChanged;
    u([J(Xz), v("design:type", Object)], IY.prototype, "ytdReduxBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], IY.prototype, "ytRendererBehavior", void 0);
    u([J(JA.YtComponentBehavior), v("design:type", Object)], IY.prototype, "ytComponentBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], IY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], IY.prototype, "data", void 0);
    u([P({
        selectorArgs: ["data.commerceCartExpandableNotificationEntityKey"],
        selector: function(a, b) {
            return iw(a.entities, "commerceCartExpandableNotificationEntity", b)
        }
    }), v("design:type", Object)], IY.prototype, "commerceCartExpandableNotificationEntity", void 0);
    u([P({
        selectorArgs: ["data.commerceCartPageStateEntityKey"],
        selector: function(a, b) {
            return iw(a.entities, "commerceCartPageStateEntity", b)
        }
    }), v("design:type", Object)], IY.prototype, "commerceCartPageStateEntity", void 0);
    u([P({
        reflectToAttribute: !0,
        value: y("web_background_colors_update")
    }), v("design:type", Boolean)], IY.prototype, "backgroundRefresh", void 0);
    u([Ty("#spinner"), v("design:type", HTMLElement)], IY.prototype, "spinner", void 0);
    u([O("commerceCartExpandableNotificationEntity", "data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], IY.prototype, "notificationEntityChanged", null);
    IY = u([R({
        disableElementRegistration: !0,
        is: "ytd-commerce-cart-renderer"
    })], IY);
    U(IY, "ytd-commerce-cart-renderer", function() {
        if (Ykc !== void 0)
            return Ykc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"title-container\" class=\"style-scope ytd-commerce-cart-renderer\">\n  <div id=\"title\" class=\"style-scope ytd-commerce-cart-renderer\">[[getSimpleString(data.title)]]</div>\n  <div id=\"notification\" class=\"style-scope ytd-commerce-cart-renderer\">[[getSimpleString(data.cartNotification)]]</div>\n</div>\n<div id=\"body\" class=\"style-scope ytd-commerce-cart-renderer\">\n  <div id=\"primary-column\" class=\"style-scope ytd-commerce-cart-renderer\">\n    <div id=\"items\" class=\"style-scope ytd-commerce-cart-renderer\"></div>\n  </div>\n  <div id=\"secondary-column\" class=\"style-scope ytd-commerce-cart-renderer\">\n    <div id=\"cart-summary\" class=\"style-scope ytd-commerce-cart-renderer\"></div>\n  </div>\n</div>\n<div id=\"loading-overlay\" hidden=\"[[computeLoadingHidden(data, commerceCartPageStateEntity)]]\" class=\"style-scope ytd-commerce-cart-renderer\">\n  <div id=\"positioning-container\" class=\"style-scope ytd-commerce-cart-renderer\">\n    <tp-yt-paper-spinner-lite id=\"spinner\" active=\"[[commerceCartPageStateEntity.cartActionInProgress]]\" class=\"style-scope ytd-commerce-cart-renderer\">\n    </tp-yt-paper-spinner-lite>\n  </div>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Ykc = a
    }, {
        mode: 1
    });
    var $kc;
    var alc = function() {
        var a = I.apply(this, arguments) || this;
        a.active = !0;
        return a
    };
    k(alc, I);
    alc.prototype.renderIdom = function() {
        if (this.data) {
            var a = this.data
              , b = {};
            y("enable_mini_app_wiz_migration") ? jB(zvb)({
                data: a
            }) : aB(OE, {
                data: a,
                config: b
            })
        }
    }
    ;
    var JY = alc;
    u([J(bB), v("design:type", Object)], JY.prototype, "ytIdomTemplatingBehavior", void 0);
    u([P(), v("design:type", Object)], JY.prototype, "data", void 0);
    u([P(), v("design:type", Object)], JY.prototype, "active", void 0);
    JY = u([cz({
        disableElementRegistration: !0,
        is: "ytd-mini-app-container-view-model",
        isInjectionRoot: !0
    })], JY);
    U(JY, "ytd-mini-app-container-view-model", function() {
        if ($kc !== void 0)
            return $kc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady-->");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return $kc = a
    }, {
        mode: 2
    });
    var blc;
    var clc = function() {
        var a = I.apply(this, arguments) || this;
        a.actionMap = {
            "yt-add-backstage-comment-action": "addBackstageCommentAction",
            "yt-add-backstage-post-action": "addBackstagePostAction",
            "yt-add-backstage-reply-action": "addBackstageReplyAction",
            "yt-ban-author-action": "banAuthorAction",
            "yt-hide-reported-comment-action": "hideReportedCommentAction",
            "yt-remove-comment-action": "removeCommentAction",
            "yt-replace-backstage-comment-action": "replaceBackstageCommentAction",
            "yt-replace-backstage-post-action": "replaceBackstagePostAction",
            "yt-replace-backstage-reply-action": "replaceBackstageReplyAction"
        };
        return a
    };
    k(clc, I);
    f = clc.prototype;
    f.addBackstagePostAction = function(a) {
        this.get("header.commentsHeaderRenderer.shouldShowBackstagePostOptimistically", this.data) && (a = this.get("addBackstagePostAction.renderer.backstagePostThreadRenderer", a)) && (this.get("header.commentsHeaderRenderer.zeroStateMessage.backstageZeroStateRenderer", this.data) && this.set("data.header.commentsHeaderRenderer.zeroStateMessage", {}),
        this.get("header.commentsHeaderRenderer.schedulingZeroStateMessage.postSchedulingZeroStateRenderer", this.data) && this.set("data.header.commentsHeaderRenderer.schedulingZeroStateMessage", {}),
        this.get("data.contents") ? this.splice("data.contents", 0, 0, {
            backstagePostThreadRenderer: a
        }) : this.set("data.contents", [{
            backstagePostThreadRenderer: a
        }]))
    }
    ;
    f.addBackstageCommentAction = function(a) {
        var b = this.get("addBackstageCommentAction.parentId", a);
        a = this.get("addBackstageCommentAction.renderer.commentThreadRenderer", a);
        if (b && a) {
            b = this.postIdToIndices(b);
            for (var c = 0; c < b.length; c++) {
                var d = b[c];
                if (d < 0)
                    break;
                d = "data.contents." + d + ".backstagePostThreadRenderer.comments";
                this.get(d) && (this.get(d + ".backstageCommentsRenderer.contents") && this.push(d + ".backstageCommentsRenderer.contents", {
                    commentThreadRenderer: a
                }),
                this.get(d + ".backstageCommentsRenderer.teaserContents") ? this.push(d + ".backstageCommentsRenderer.teaserContents", {
                    commentThreadRenderer: a
                }) : this.set(d + ".backstageCommentsRenderer.teaserContents", [{
                    commentThreadRenderer: a
                }]))
            }
        }
    }
    ;
    f.addBackstageReplyAction = function(a) {
        var b = this.get("addBackstageReplyAction.parentId", a);
        a = this.get("addBackstageReplyAction.renderer.commentRenderer", a);
        b && a && this.setCreatorReply(b, a)
    }
    ;
    f.banAuthorAction = function(a) {
        var b = this.get("banAuthorAction.commentId", a);
        b && (a = this.get("banAuthorAction.parentCommentId", a) || this.getParentPostId(b),
        this.removeFromStream(b, a))
    }
    ;
    f.hideReportedCommentAction = function(a) {
        var b = this.get("hideReportedCommentAction.commentId", a);
        b && ((a = this.get("hideReportedCommentAction.parentCommentId", a)) || (a = this.getParentPostId(b)),
        this.removeFromStream(b, a))
    }
    ;
    f.replaceBackstageCommentAction = function(a) {
        var b = this.get("replaceBackstageCommentAction.commentId", a)
          , c = this.get("replaceBackstageCommentAction.parentId", a);
        a = this.get("replaceBackstageCommentAction.renderer.commentThreadRenderer", a);
        if (b && c && a) {
            c = this.postIdToIndices(c);
            for (var d = 0; d < c.length; d++) {
                var e = c[d];
                if (e < 0)
                    break;
                var h = this.commentIdToIndex(b, e, !1);
                if (h >= 0) {
                    var l = this.get("data.contents." + e + ".backstagePostThreadRenderer.comments.backstageCommentsRenderer.contents." + h + ".commentThreadRenderer.replies.commentRepliesRenderer");
                    l && (a.replies = {
                        commentRepliesRenderer: l
                    });
                    this.splice("data.contents." + e + ".backstagePostThreadRenderer.comments.backstageCommentsRenderer.contents", h, 1, {
                        commentThreadRenderer: a
                    })
                }
                h = this.commentIdToIndex(b, e, !0);
                if (h >= 0) {
                    if (l = this.get("data.contents." + e + ".backstagePostThreadRenderer.comments.backstageCommentsRenderer.teaserContents." + (h + ".commentThreadRenderer.replies.commentRepliesRenderer")))
                        a.replies = {
                            commentRepliesRenderer: l
                        };
                    this.splice("data.contents." + e + ".backstagePostThreadRenderer.comments.backstageCommentsRenderer.teaserContents", h, 1, {
                        commentThreadRenderer: a
                    })
                }
            }
        }
    }
    ;
    f.replaceBackstagePostAction = function(a) {
        var b = this.get("replaceBackstagePostAction.itemId", a);
        if (b) {
            b = this.postIdToIndices(b);
            for (var c = 0; c < b.length; c++) {
                var d = b[c];
                if (d < 0)
                    break;
                var e = this.getPostRendererType(d)
                  , h = this.get("replaceBackstagePostAction.renderer." + e, a);
                if (!h && e !== "sharedPostRenderer")
                    break;
                var l = !1;
                h || (l = !0,
                h = this.get("replaceBackstagePostAction.renderer.backstagePostRenderer", a));
                if (!h)
                    break;
                var m = {};
                l ? (DB(m, mPb, h),
                this.set("data.contents." + d + ".backstagePostThreadRenderer.post.sharedPostRenderer.originalPost", m)) : (DB(m, new w(e), h),
                this.set("data.contents." + d + ".backstagePostThreadRenderer.post", m))
            }
        }
    }
    ;
    f.replaceBackstageReplyAction = function(a) {
        var b = this.get("replaceBackstageReplyAction.replyId", a)
          , c = this.get("replaceBackstageReplyAction.parentId", a);
        a = this.get("replaceBackstageReplyAction.renderer.commentRenderer", a);
        b && a && c && this.setCreatorReply(c, a)
    }
    ;
    f.removeCommentAction = function(a) {
        var b = this.get("removeCommentAction.commentId", a);
        if (b) {
            var c = this.get("removeCommentAction.parentCommentId", a);
            c && this.get("removeCommentAction.isCreatorReply", a) ? this.setCreatorReply(c, void 0) : (c || (c = this.getParentPostId(b)),
            this.removeFromStream(b, c))
        }
    }
    ;
    f.setCreatorReply = function(a, b) {
        var c = this.getParentPostId(a);
        if (c) {
            c = this.postIdToIndices(c);
            for (var d = 0; d < c.length; d++) {
                var e = c[d];
                if (e < 0)
                    break;
                var h = this.commentIdToIndex(a, e, !1);
                if (h >= 0) {
                    var l = "data.contents." + e + ".backstagePostThreadRenderer.comments.backstageCommentsRenderer.contents." + h;
                    h = l + ".commentThreadRenderer.comment.commentRenderer.containsCreatorReply";
                    l += ".commentThreadRenderer.replies";
                    b == void 0 ? (this.set(l, {}),
                    this.set(h, !1)) : (this.set(l, {
                        commentRepliesRenderer: {
                            teaserContents: [{
                                commentRenderer: b
                            }]
                        }
                    }),
                    this.set(l + ".commentRepliesRenderer.teaserContents.0.commentRenderer.isCreatorReply", !0),
                    this.set(h, !0))
                }
                h = this.commentIdToIndex(a, e, !0);
                h >= 0 && (h = "data.contents." + e + ".backstagePostThreadRenderer.comments.backstageCommentsRenderer.teaserContents." + h,
                e = h + ".commentThreadRenderer.comment.commentRenderer.containsCreatorReply",
                h += ".commentThreadRenderer.replies",
                b == void 0 ? (this.set(h, {}),
                this.set(e, !1)) : (this.set(h, {
                    commentRepliesRenderer: {
                        teaserContents: [{
                            commentRenderer: b
                        }]
                    }
                }),
                this.set(e, !0)))
            }
        }
    }
    ;
    f.removeFromStream = function(a, b) {
        if (b) {
            b = this.postIdToIndices(b);
            for (var c = 0; c < b.length; c++) {
                var d = b[c];
                if (d < 0)
                    break;
                var e = this.commentIdToIndex(a, d, !1);
                e >= 0 && this.splice("data.contents." + d + ".backstagePostThreadRenderer.comments.backstageCommentsRenderer.contents", e, 1);
                e = this.commentIdToIndex(a, d, !0);
                e >= 0 && this.splice("data.contents." + d + ".backstagePostThreadRenderer.comments.backstageCommentsRenderer.teaserContents", e, 1);
                d = "data.contents." + d + ".backstagePostThreadRenderer.post.backstagePostRenderer";
                e = d + ".backstageAttachment.pollRenderer.votedCommentId";
                this.get(e) === a && (this.set(e, null),
                this.set(d + ".backstageAttachment.pollRenderer.commentDelete", null))
            }
        } else
            for (b = this.postIdToIndices(a).reverse(),
            c = 0; c < b.length; c++) {
                d = b[c];
                if (d < 0)
                    break;
                e = this.getPostRendererType(d);
                var h = this.get("backstagePostThreadRenderer.post." + e, this.data.contents[d]);
                h.postId === a ? this.splice("data.contents", d, 1) : e === "sharedPostRenderer" && this.set("data.contents." + d + ".backstagePostThreadRenderer.post.sharedPostRenderer.originalPost", null);
                h.scheduledPublishTimeSec && Dv(this.hostElement, "yt-update-posts-total-count-action", [{
                    updatePostsTotalCountAction: {
                        updateType: "UPDATE_POSTS_TOTAL_COUNT_TYPE_REMOVE",
                        number: 1
                    }
                }])
            }
    }
    ;
    f.postIdToIndices = function(a) {
        for (var b = [], c = 0; c < this.data.contents.length; c++) {
            var d = this.getPostRendererType(c);
            this.get("backstagePostThreadRenderer.post." + d + ".postId", this.data.contents[c]) === a && b.push(c);
            if (d === "sharedPostRenderer") {
                var e = this.get("backstagePostThreadRenderer.post." + d + ".originalPost.backstagePostRenderer.postId", this.data.contents[c]);
                d = this.get("backstagePostThreadRenderer.post." + d + ".originalPost.postRenderer.postId", this.data.contents[c]);
                e !== a && d !== a || b.push(c)
            }
        }
        return b
    }
    ;
    f.commentIdToIndex = function(a, b, c) {
        if (b < 0)
            return -1;
        var d, e, h, l, m = A((d = this.data) == null ? void 0 : (e = d.contents) == null ? void 0 : (h = e[b]) == null ? void 0 : (l = h.backstagePostThreadRenderer) == null ? void 0 : l.comments, kPb);
        return (b = c ? m == null ? void 0 : m.teaserContents : m == null ? void 0 : m.contents) && b.length ? b.findIndex(function(p) {
            return A(p, zPb).comment.commentRenderer.commentId === a
        }) : -1
    }
    ;
    f.getParentPostId = function(a) {
        a = a.split(".");
        if (a[1])
            return a[0]
    }
    ;
    f.getPostRendererType = function(a) {
        return this.get("backstagePostThreadRenderer.post.sharedPostRenderer", this.data.contents[a]) ? "sharedPostRenderer" : "backstagePostRenderer"
    }
    ;
    var KY = clc;
    u([J(X.YtRendererBehavior), v("design:type", Object)], KY.prototype, "ytRendererBehavior", void 0);
    u([J(EA.YtActionHandlerBehavior), v("design:type", Object)], KY.prototype, "ytActionHandlerBehavior", void 0);
    u([P(), v("design:type", Object)], KY.prototype, "data", void 0);
    KY = u([R({
        disableElementRegistration: !0,
        is: "ytd-backstage-items"
    })], KY);
    U(KY, "ytd-backstage-items", function() {
        if (blc !== void 0)
            return blc;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><ytd-item-section-renderer data=\"[[data]]\" class=\"style-scope ytd-backstage-items\"></ytd-item-section-renderer>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return blc = a
    }, {
        mode: 1
    });
    var dlc;
    function LY(a) {
        return y("kevlar_comments_clone_data_killswitch") ? a : pc.unsafeClone(a)
    }
    ot({
        is: "ytd-comments",
        _template: function() {
            if (dlc !== void 0)
                return dlc;
            var a = document.createElement("template");
            G(a, "<!--css-build:shady--><!--css-build:shady--><tp-yt-paper-spinner-lite active=\"[[canShowDefaultSpinner_]]\" class=\"style-scope ytd-comments\"></tp-yt-paper-spinner-lite>\n<ytd-item-section-renderer id=\"sections\" can-schedule-jobs=\"[[canScheduleJobs]]\" comments-hide-panel-button=\"[[hidePanelButton]]\" continuation-disable-prescan-visibility=\"[[disablePrescanVisibility]]\" data=\"{{data}}\" engagement-panel=\"[[engagementPanel]]\" initial-count=\"2\" is-watch-grid=\"[[isWatchGrid]]\" class=\"style-scope ytd-comments\">\n</ytd-item-section-renderer>\n");
            a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
            return dlc = a
        },
        behaviors: [V$a.YtHostElementBehavior, hQ.YtPlayerListenerBehavior, X.YtRendererBehavior, EA.YtActionHandlerBehavior],
        properties: {
            data: {
                type: Object,
                observer: "dataChanged_"
            },
            isBackstage: {
                type: Boolean,
                computed: "computeIsBackstage_(data.header.commentsHeaderRenderer.isBackstageContent)",
                reflectToAttribute: !0
            },
            disablePrescanVisibility: {
                type: Boolean,
                value: !0
            },
            canScheduleJobs: {
                type: Boolean,
                value: !0
            },
            canShowDefaultSpinner_: {
                type: Boolean,
                computed: "computeCanShowDefaultSpinner_(data, canScheduleJobs)"
            },
            engagementPanel: {
                type: Boolean,
                reflectToAttribute: !0
            },
            hidePanelButton: {
                type: Boolean,
                value: !1
            },
            isWatchGrid: {
                type: Boolean,
                value: !1
            }
        },
        actionMap: {
            "yt-ban-author-action": "banAuthorAction_",
            "yt-create-comment-action": "createCommentAction_",
            "yt-create-comment-reply-action": "createCommentReplyAction_",
            "yt-hide-reported-comment-action": "hideReportedCommentAction_",
            "yt-pin-comment-action": "pinCommentAction_",
            "yt-reload-comments-command": "reloadComments_",
            "yt-remove-comment-action": "removeCommentAction_",
            "yt-unpin-comment-action": "unpinCommentAction_",
            "yt-update-comment-action": "updateCommentAction_",
            "yt-update-comment-reply-action": "updateCommentReplyAction_"
        },
        listeners: {
            "yt-retrieve-location": "onRetrieveLocation_"
        },
        observers: ["contentsChanged_(data.contents.*)", "headerChanged_(data.header)"],
        created: function() {
            var a = this;
            this.RenderingPriority = {
                RENDERING_PRIORITY_UNKNOWN: 0,
                RENDERING_PRIORITY_PINNED_COMMENT: 10,
                RENDERING_PRIORITY_LINKED_COMMENT: 20,
                RENDERING_PRIORITY_REALTIME_COMMENT: 30,
                RENDERING_PRIORITY_COMMUNITY_GUIDELINES_BELOW_HEADER: 80,
                RENDERING_PRIORITY_COMMENT_HEADER: 100
            };
            this.initCommentsCsi_();
            this.player = null;
            this.JSC$15646_PLAYER_EVENTS_ = new Map;
            this.JSC$15646_PLAYER_EVENTS_.set("onVideoProgress", function() {
                a.onVideoProgress_()
            })
        },
        attached: function() {
            this.maybeGetAndSetPlayer_()
        },
        maybeGetAndSetPlayer_: function() {
            var a = this
              , b = xA(this);
            b && b.getPlayerPromise().then(function(c) {
                a.playerApiReady_(c)
            })
        },
        playerApiReady_: function(a) {
            this.setPlayer_(a)
        },
        setPlayer_: function(a) {
            this.player_ && this.unlistenFromPlayerEvents(this.player_, this.JSC$15646_PLAYER_EVENTS_);
            (this.player_ = a) && this.listenToPlayerEvents(a, this.JSC$15646_PLAYER_EVENTS_)
        },
        detached: function() {
            this.setPlayer_(null)
        },
        onVideoProgress_: function() {
            var a = this
              , b = ok("prefetch_comments_ms_after_video");
            b > 0 && setTimeout(function() {
                return a.loadComments()
            }, b);
            y("prefetch_comments_idle_job") && Lk(Ei, function() {
                return a.loadComments()
            });
            this.setPlayer_(null)
        },
        dataChanged_: function() {
            this.player_ || this.maybeGetAndSetPlayer_()
        },
        contentsChanged_: function(a) {
            a && a.value && a.path === "data.contents" && this.tickForCommentsTimer_("cml")
        },
        headerChanged_: function(a) {
            a && this.tickForCommentsTimer_("cmhl")
        },
        initCommentsCsi_: function() {
            Kq("wn_comments");
            var a = nq();
            a && Jq({
                clientScreenNonce: a
            }, "wn_comments");
            this.tickForCommentsTimer_("cmi")
        },
        createCommentAction_: function(a) {
            a = LY(a);
            var b, c, d;
            if (a = (b = a) == null ? void 0 : (c = b.createCommentAction) == null ? void 0 : (d = c.contents) == null ? void 0 : d.commentThreadRenderer) {
                var e, h, l, m, p, q;
                !this.isBackstage && ((e = this.data) == null ? 0 : (h = e.header) == null ? 0 : (l = h.commentsHeaderRenderer) == null ? 0 : (m = l.createRenderer) == null ? 0 : (p = m.commentSimpleboxRenderer) == null ? 0 : (q = p.zeroStep) == null ? 0 : q.zeroStepChannelCreationRenderer) && this.set("data.header.commentsHeaderRenderer.createRenderer.commentSimpleboxRenderer.zeroStep", {});
                var r, x, z, C;
                this.isBackstage && ((r = this.data) == null ? 0 : (x = r.header) == null ? 0 : (z = x.commentsHeaderRenderer) == null ? 0 : (C = z.zeroStateMessage) == null ? 0 : C.backstageZeroStateRenderer) && this.set("data.header.commentsHeaderRenderer.zeroStateMessage", {});
                this.insert_(a)
            }
        },
        doReplyInsert_: function(a, b, c, d) {
            d ? this.splice(a, d, 0, b) : this.push(a, b)
        },
        getRepliesPath_: function(a) {
            return "data.contents." + a + ".commentThreadRenderer.replies"
        },
        getRepliesContentsPath_: function(a, b) {
            a = this.getRepliesPath_(a);
            return b ? a + ".commentRepliesRenderer.teaserContents" : a + ".commentRepliesRenderer.contents"
        },
        createCommentReplyAction_: function(a) {
            a = LY(a);
            var b, c, d = (b = a) == null ? void 0 : (c = b.createCommentReplyAction) == null ? void 0 : c.parentCommentId, e, h;
            if (b = (e = a) == null ? void 0 : (h = e.createCommentReplyAction) == null ? void 0 : h.contents)
                if (d = this.commentIdToIndex_(d),
                !(d < 0))
                    if (e = this.getRepliesPath_(d),
                    this.get(e)) {
                        var l, m;
                        a = (l = a) == null ? void 0 : (m = l.createCommentReplyAction) == null ? void 0 : m.replyToCommentId;
                        l = this.getRepliesContentsPath_(d, !1);
                        this.get(l) && (m = this.get(l).length,
                        e = l + "." + (m - 1) + ".continuationItemRenderer",
                        this.get(e + ".button") ? (e = this.replyIdToIndex_(a, d, !1),
                        this.doReplyInsert_(l, b, e, m - 1)) : this.get(e) || (m = this.replyIdToIndex_(a, d, !1),
                        this.doReplyInsert_(l, b, m, null)));
                        l = this.getRepliesContentsPath_(d, !0);
                        this.get(l) ? (d = this.replyIdToIndex_(a, d, !0),
                        (!a || d >= 0) && this.doReplyInsert_(l, b, d, null)) : this.set(l, [b])
                    } else
                        this.set(e, {
                            commentRepliesRenderer: {
                                teaserContents: [b]
                            }
                        })
        },
        hideReportedCommentAction_: function(a) {
            var b, c = a == null ? void 0 : (b = a.hideReportedCommentAction) == null ? void 0 : b.commentId;
            if (c) {
                var d;
                a = a == null ? void 0 : (d = a.hideReportedCommentAction) == null ? void 0 : d.parentCommentId;
                c = c.replace("#", ".");
                a || (a = this.getParentCommentId_(c));
                this.remove_(c, a)
            }
        },
        getParentCommentId_: function(a) {
            a = a.split(".");
            if (a[1])
                return a[0]
        },
        removeCommentAction_: function(a) {
            var b, c = a == null ? void 0 : (b = a.removeCommentAction) == null ? void 0 : b.commentId;
            if (c) {
                var d;
                a = a == null ? void 0 : (d = a.removeCommentAction) == null ? void 0 : d.parentCommentId;
                c = c.replace("#", ".");
                a || (a = this.getParentCommentId_(c));
                this.remove_(c, a)
            }
        },
        pinCommentAction_: function(a) {
            a = LY(a);
            var b, c, d = (b = a) == null ? void 0 : (c = b.pinCommentAction) == null ? void 0 : c.commentId;
            d && (a = this.get("pinCommentAction.actionResult.update.commentThreadRenderer", a)) && (this.remove_(d),
            this.insert_(a, !0))
        },
        unpinCommentAction_: function(a) {
            a = LY(a);
            var b, c, d = (b = a) == null ? void 0 : (c = b.unpinCommentAction) == null ? void 0 : c.commentId;
            if (d) {
                var e, h, l;
                if (a = (e = a.unpinCommentAction) == null ? void 0 : (h = e.actionResult) == null ? void 0 : (l = h.update) == null ? void 0 : l.commentThreadRenderer)
                    this.remove_(d),
                    this.insert_(a)
            }
        },
        updateCommentAction_: function(a) {
            a = LY(a);
            var b, c, d = (b = a) == null ? void 0 : (c = b.updateCommentAction) == null ? void 0 : c.commentId, e, h;
            a = (e = a) == null ? void 0 : (h = e.updateCommentAction) == null ? void 0 : h.contents;
            d && a && this.update_(d, a)
        },
        updateCommentReplyAction_: function(a) {
            a = LY(a);
            var b, c, d = (b = a) == null ? void 0 : (c = b.updateCommentReplyAction) == null ? void 0 : c.commentId, e, h;
            a = (e = a) == null ? void 0 : (h = e.updateCommentReplyAction) == null ? void 0 : h.contents;
            d && a && (d = d.replace("#", "."),
            e = this.getParentCommentId_(d),
            this.update_(d, a, e))
        },
        banAuthorAction_: function(a) {
            var b, c = a == null ? void 0 : (b = a.banAuthorAction) == null ? void 0 : b.commentId;
            if (c) {
                var d;
                a = a == null ? void 0 : (d = a.banAuthorAction) == null ? void 0 : d.parentCommentId;
                c = c.replace("#", ".");
                a || (a = this.getParentCommentId_(c));
                this.remove_(c, a)
            }
        },
        commentIdToIndex_: function(a) {
            var b;
            return a && (b = this.data) != null && b.contents ? this.data.contents.findIndex(function(c) {
                var d, e, h, l, m;
                return a === ((c == null ? void 0 : (d = c.commentThreadRenderer) == null ? void 0 : (e = d.comment) == null ? void 0 : (h = e.commentRenderer) == null ? void 0 : h.commentId) || (c == null ? void 0 : (l = c.commentThreadRenderer) == null ? void 0 : l.commentViewModel) && ((m = A(c.commentThreadRenderer.commentViewModel, BPb)) == null ? void 0 : m.commentId))
            }) : -1
        },
        insert_: function(a, b) {
            var c, d;
            if ((c = this.data) == null ? 0 : (d = c.contents) == null ? 0 : d.some(function(h) {
                return !(h == null || !h.commentThreadRenderer)
            }))
                for (c = 0,
                d = this.data.contents.length; c < d; c++) {
                    var e = this.data.contents[c].commentThreadRenderer;
                    if (this.RenderingPriority[a.renderingPriority] >= this.RenderingPriority[e.renderingPriority]) {
                        b && this.RenderingPriority[a.renderingPriority] == this.RenderingPriority[e.renderingPriority] ? this.splice("data.contents", c, 1, {
                            commentThreadRenderer: a
                        }) : this.splice("data.contents", c, 0, {
                            commentThreadRenderer: a
                        });
                        break
                    }
                }
            else
                this.set("data.contents", [{
                    commentThreadRenderer: a
                }])
        },
        doReplyRemove_: function(a, b, c) {
            a = this.replyIdToIndex_(a, b, c);
            a < 0 || (b = this.getRepliesContentsPath_(b, c),
            this.splice(b, a, 1))
        },
        remove_: function(a, b) {
            b = this.commentIdToIndex_(b);
            b < 0 ? (b = this.commentIdToIndex_(a),
            b < 0 || this.splice("data.contents", b, 1)) : (this.doReplyRemove_(a, b, !1),
            this.doReplyRemove_(a, b, !0),
            b = "data.contents." + b + ".commentThreadRenderer.comment.commentRenderer",
            this.get(b + ".backstageAttachment.pollRenderer.votedCommentId") == a && (this.set(b + ".backstageAttachment.pollRenderer.votedCommentId", null),
            this.set(b + ".backstageAttachment.pollRenderer.commentDelete", null)))
        },
        replyIdToIndex_: function(a, b, c) {
            if (b < 0)
                return -1;
            b = this.getRepliesContentsPath_(b, c);
            b = this.get(b);
            if (!b || !b.length)
                return -1;
            c = 0;
            for (var d = b.length; c < d; c++) {
                var e = void 0
                  , h = void 0
                  , l = void 0
                  , m = void 0;
                if ((((e = b[c]) == null ? void 0 : (h = e.commentRenderer) == null ? void 0 : h.commentId) || ((l = b[c]) == null ? void 0 : (m = l.commentViewModel) == null ? void 0 : m.commentId)) === a)
                    return c
            }
            return -1
        },
        doReplyUpdate_: function(a, b, c, d) {
            a = this.replyIdToIndex_(a, b, d);
            if (!(a < 0)) {
                b = this.getRepliesContentsPath_(b, d);
                if (d = this.get(b + "." + a + ".commentRenderer.creatorReply"))
                    c.commentRenderer.creatorReply = d;
                this.splice(b, a, 1, c)
            }
        },
        update_: function(a, b, c) {
            var d = this.commentIdToIndex_(c);
            !c || d < 0 ? (d = this.commentIdToIndex_(a),
            d < 0 || this.set("data.contents." + d + ".commentThreadRenderer.comment", b)) : (this.doReplyUpdate_(a, d, b, !1),
            this.doReplyUpdate_(a, d, b, !0))
        },
        computeIsBackstage_: function(a) {
            return !!a
        },
        computeCanShowDefaultSpinner_: function(a, b) {
            return b ? (b = sm().resolve(rm(bx))) && b.isOnWatch && b.isOnWatch() ? !(a && (a.contents || a.header || a.continuations)) : !1 : !1
        },
        onRetrieveLocation_: function(a, b) {
            b && b.hasComments && this.tickForCommentsTimer_("lss")
        },
        tickForCommentsTimer_: function(a) {
            Mq(a, void 0, "wn_comments")
        },
        reloadComments_: function(a) {
            a && a.reloadCommentsCommand && a.reloadCommentsCommand.command && a.reloadCommentsCommand.command.continuationCommand && Hv(this, [a.reloadCommentsCommand.command])
        },
        loadComments: function() {
            ok("prefetch_comments_ms_after_video") || y("prefetch_comments_idle_job") ? this.$.sections.triggerInitialContinuations() : this.$.sections.triggerContinuations()
        }
    });
    var elc;
    var flc;
    var glc = function() {
        return I.apply(this, arguments) || this
    };
    k(glc, I);
    glc.prototype.configureRendererStamper = function() {
        return {
            "data.imageRenderer": {
                id: "image-renderer",
                mapping: {
                    themedImageRenderer: {
                        component: "yt-themed-image-renderer",
                        params: {
                            fit: !0
                        }
                    }
                }
            }
        }
    }
    ;
    glc.prototype.onBackIconTap_ = function() {
        window.history.back()
    }
    ;
    var MY = glc;
    u([J(X.YtRendererBehavior), v("design:type", Object)], MY.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], MY.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], MY.prototype, "data", void 0);
    MY = u([cz({
        is: "yt-header-with-back-renderer",
        disableElementRegistration: !0
    })], MY);
    U(MY, "yt-header-with-back-renderer", function() {
        if (flc === void 0) {
            var a = document.createElement("template");
            G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"header-wrapper\" class=\"style-scope yt-header-with-back-renderer\">\n  <yt-icon-button id=\"back-button\" label=\"Back\" on-tap=\"onBackIconTap_\" class=\"style-scope yt-header-with-back-renderer\">\n    <yt-icon icon=\"yt-icons:arrow-back\" class=\"style-scope yt-header-with-back-renderer\"></yt-icon>\n  </yt-icon-button>\n  <div id=\"image-renderer\" hidden=\"[[!data.imageRenderer]]\" class=\"style-scope yt-header-with-back-renderer\"></div>\n  <div id=\"header-container\" class=\"style-scope yt-header-with-back-renderer\">\n    <yt-formatted-string id=\"header-title\" text=\"[[data.title]]\" class=\"style-scope yt-header-with-back-renderer\"></yt-formatted-string>\n    <yt-formatted-string id=\"header-subtitle\" text=\"[[data.subtitle]]\" class=\"style-scope yt-header-with-back-renderer\"></yt-formatted-string>\n  </div>\n</div>\n");
            a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
            var b = a.content
              , c = b.insertBefore;
            elc === void 0 && (elc = document.createElement("template"));
            var d = elc;
            c.call(b, d.content.cloneNode(!0), a.content.firstChild);
            flc = a
        }
        a = flc;
        return a
    }, {
        mode: 2
    });
    var hlc;
    var ilc;
    var jlc = function() {
        var a = I.apply(this, arguments) || this;
        a.actionMap = {
            "yt-dark-mode-toggled-action": "onDarkModeToggledAction"
        };
        return a
    };
    k(jlc, I);
    f = jlc.prototype;
    f.attached = function() {
        this.isDarkTheme = !!document.documentElement.hasAttribute("dark")
    }
    ;
    f.onDarkModeToggledAction = function(a) {
        a !== this.isDarkTheme && (this.isDarkTheme = a,
        this.setUrl())
    }
    ;
    f.dataChanged = function() {
        var a = this;
        if (this.data) {
            var b = this.setUrl();
            b && Mm({
                destination: window,
                iframe: this.iframe,
                origin: hd(b.toString()),
                channelName: "yt-iframe",
                onMessage: function(c) {
                    (c = a.getCommunicationCommand(c.data)) && a.ytComponentBehavior.resolveCommand(c)
                },
                onEstablished: function() {}
            })
        }
    }
    ;
    f.setUrl = function() {
        if (this.data && this.data.iframeUrl) {
            var a = Sj(this.isDarkTheme && this.data.darkThemeIframeUrl ? this.data.darkThemeIframeUrl : this.data.iframeUrl);
            if (a)
                return Dc(this.iframe, a),
                a
        }
    }
    ;
    f.getCommunicationCommand = functirn how To read iT on(a) {
        var b;
        if ((b = this.data) != null && b.onCommunicationCommandsMap) {
            b = this.data.onCommunicationCommandsMap.find(function(e) {
                return e.key === a
            });



            AS I PUT THIS OUT HERE, I JUST want to say screw all the haters that dont understand why i do this, LEarn how to read it instead off hating on me, and to all the fucksticks in the kenyon mn trailer park, i hope you little punks rot in hell for trying to fuck with me knowing im trying to raise a family, karma will bite you bitches in the ass, and while it happens im going to grab some popcorn sit back and watch like im watching a movie, yours truly brady lee fischer, heres my address just in case you want to try to be on some bullshit*************901 REDWING AVE, Trailer 16,Kenyon mn, 55946********** waant my phone number also ???

            BEFORE i FORGET   SUPPORT 81 4L

                reflectToAttribute: !0
    }), v("design:type", Boolean)], ZV.prototype, "selected", void 0);
    u([O("data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], ZV.prototype, "dataChanged", null);
    u([O("selected"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], ZV.prototype, "selectionChanged", null);
    u([M("tap"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], ZV.prototype, "onTap", null);
    u([M("focus"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], ZV.prototype, "onFocus", null);
    ZV = u([cz({
        is: "yt-chip-cloud-chip-renderer",
        disableElementRegistration: !0
    })], ZV);
    U(ZV, "yt-chip-cloud-chip-renderer", function() {
        if (qec === void 0) {
            var a = document.createElement("template");
            G(a, "<!--css-build:shady--><!--css-build:shady--><yt-formatted-string id=\"text\" ellipsis-truncate=\"\" text=\"[[data.text]]\" class=\"style-scope yt-chip-cloud-chip-renderer\">\n</yt-formatted-string>\n");
            a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
            var b = a.content
              , c = b.insertBefore;
            pec === void 0 && (pec = document.createElement("template"));
            var d = pec;
            c.call(b, d.content.cloneNode(!0), a.content.firstChild);
            qec = a
        }
        a = qec;
        return a
    }, {
        mode: 2
    });
    var sec = function() {
        var a = I.apply(this, arguments) || this;
        a.isDarkTheme = !1;
        a.notSticky = !1;
        a.transparentBackground = !1;
        a.shouldHide = !1;
        a.disableSticky = !1;
        a.fluidWidth = !1;
        a.isClipList = !1;
        a.isWatchPage = !1;
        a.toolbarHeight = 0;
        a.actionMap = {
            "yt-chip-cloud-chip-select-action": "handleChipCloudChipSelectAction",
            "yt-chip-cloud-chip-deselect-action": "handleChipCloudChipDeselectAction",
            "yt-dark-mode-toggled-action": "onDarkModeToggledAction"
        };
        return a
    };
    k(sec, I);
    f = sec.prototype;
    f.configureRendererStamper = function() {
        return {
            "data.contents": {
                id: "chips",
                mapping: {
                    chipCloudChipRenderer: {
                        component: "yt-chip-cloud-chip-renderer",
                        properties: {
                            disableDeselectEvent: "[[isDisableDeselectEvent]]"
                        }
                    }
                }
            },
            sortFilterHeaderRendererData: {
                id: "filter",
                mapping: {
                    sortFilterHeaderRenderer: {
                        component: "ytd-sort-filter-header-renderer",
                        properties: {
                            isClipList: "[[isClipList]]"
                        }
                    }
                }
            },
            "data.previousButton": {
                id: "left-arrow-button",
                mapping: {
                    buttonRenderer: {
                        component: "ytd-button-renderer",
                        properties: {
                            "on-tap": "[[boundPrevClick]]"
                        },
                        params: {
                            iconSize: 16
                        }
                    }
                }
            },
            "data.nextButton": {
                id: "right-arrow-button",
                mapping: {
                    buttonRenderer: {
                        component: "ytd-button-renderer",
                        properties: {
                            "on-tap": "[[boundNextClick]]"
                        },
                        params: {
                            iconSize: 16
                        }
                    }
                }
            }
        }
    }
    ;
    f.attached = function() {
        var a = this;
        document.addEventListener("scroll", MA(this, this.updateChipBarWidthAndTop));
        this.isDarkTheme = document.documentElement.hasAttribute("dark");
        var b;
        this.toolbarHeight = ((b = document.querySelector("ytd-masthead")) == null ? void 0 : b.clientHeight) || 0;
        window.IntersectionObserver && (this.intersectionObserver = new IntersectionObserver(function(c) {
            a.handleIntersect(c)
        }
        ,{
            rootMargin: "-" + (this.toolbarHeight + 1) + "px 0px 0px 0px",
            threshold: [1]
        }),
        this.intersectionObserver.observe(this.hostElement));
        window.ResizeObserver && (this.resizeObserver = new ResizeObserver(function() {
            a.updateChipBarWidthAndTop()
        }
        ),
        this.resizeObserver.observe(this.hostElement))
    }
    ;
    f.detached = function() {
        var a;
        (a = this.intersectionObserver) == null || a.disconnect();
        var b;
        (b = this.resizeObserver) == null || b.disconnect();
        document.removeEventListener("scroll", MA(this, this.updateChipBarWidthAndTop))
    }
    ;
    f.dataChanged = function() {
        var a = this;
        this.updating = !0;
        var b = this.findSelectedChipIndex();
        this.selectedIndex !== b && (this.selectedIndex = -1);
        ht(this, function() {
            a.selectedIndex = b;
            a.updating = !1;
            a.ytScrollableChipCloudBehavior.reset()
        })
    }
    ;
    f.findSelectedChipIndex = function() {
        var a;
        if ((a = this.data) == null || !a.contents)
            return 0;
        a = this.data.contents;
        for (var b = 0; b < a.length; b++) {
            var c = void 0;
            if ((c = A(a[b], JSb)) == null ? 0 : c.isSelected)
                return b
        }
        return 0
    }
    ;
    f.computeStyle = function(a) {
        return a
    }
    ;
    f.handleChipCloudChipSelectAction = function(a) {
        a = this.JSC$15061_chipsSelector.indexOf(a);
        a > -1 && this.JSC$15061_chipsSelector.selectIndex(a)
    }
    ;
    f.handleChipCloudChipDeselectAction = function() {
        if (y("kevlar_chips_check_index_zero_killswitch") || ![0, -1].includes(this.selectedIndex)) {
            var a, b, c, d = (c = A((a = this.data) == null ? void 0 : (b = a.contents) == null ? void 0 : b[0], JSb)) == null ? void 0 : c.navigationEndpoint;
            d && Dv(this.hostElement, "yt-browse-section-list-reload-endpoint", [d]);
            this.JSC$15061_chipsSelector.selectIndex(0);
            this.ytScrollableChipCloudBehavior.reset()
        }
    }
    ;
    f.onGuideIsExpandedChanged = function() {
        var a = this.ytScrollableChipCloudBehavior;
        ht(a, a.setContainerWidthDiff);
        XV(this.ytScrollableChipCloudBehavior)
    }
    ;
    f.onResize = function() {
        var a = this.ytScrollableChipCloudBehavior;
        ht(a, a.setContainerWidthDiff);
        XV(this.ytScrollableChipCloudBehavior)
    }
    ;
    f.onDarkModeToggledAction = function(a) {
        this.isDarkTheme = a
    }
    ;
    f.updateChipBarWidthAndTop = function() {
        this.updateDimensions();
        this.notSticky = this.isChannelPageGrid || this.disableSticky || this.hostElement.getBoundingClientRect().y > this.toolbarHeight
    }
    ;
    f.handleIntersect = function(a) {
        y("disable_chips_intersection_observer") || (this.notSticky = this.isChannelPageGrid || this.disableSticky || a[0].intersectionRatio === 1)
    }
    ;
    f.updateDimensions = function() {
        var a = this.ytRendererBehavior.parentComponent;
        if (a) {
            var b, c = (b = a.headerElement) != null ? b : a;
            tz(this.hostElement, {
                "--ytd-rich-grid-chips-bar-width": c.clientWidth + "px",
                "--ytd-rich-grid-chips-bar-top": this.toolbarHeight + "px"
            })
        }
    }
    ;
    f.updateSelectedIndexFromBinding = function(a) {
        this.selectedIndex = a.detail.value
    }
    ;
    da.Object.defineProperties(sec.prototype, {
        isChannelPageGrid: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return this.componentStyle === "FEED_FILTER_CHIP_BAR_STYLE_TYPE_CHANNEL_PAGE_GRID"
            }
        },
        isHashtagLandingPage: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return this.componentStyle === "FEED_FILTER_CHIP_BAR_STYLE_TYPE_HASHTAG_LANDING_PAGE"
            }
        },
        isDisableDeselectEvent: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return this.isChannelPageGrid || this.isHashtagLandingPage
            }
        },
        sortFilterHeaderRendererData: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                var a, b, c = (a = this.data) == null ? void 0 : (b = a.contents) == null ? void 0 : b.find(function(d) {
                    return A(d, NSb)
                });
                return {
                    sortFilterHeaderRenderer: A(c, NSb)
                }
            }
        },
        frostedGlass: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return y("web_frosted_glass") && this.componentStyle === "FEED_FILTER_CHIP_BAR_STYLE_TYPE_DEFAULT"
            }
        }
    });
    var $V = sec;
    $V.prototype.updateChipBarWidthAndTop = $V.prototype.updateChipBarWidthAndTop;
    $V.prototype.onResize = $V.prototype.onResize;
    $V.prototype.onGuideIsExpandedChanged = $V.prototype.onGuideIsExpandedChanged;
    $V.prototype.dataChanged = $V.prototype.dataChanged;
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], $V.prototype, "ytRendererstamperBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], $V.prototype, "ytRendererBehavior", void 0);
    u([J(EA.YtActionHandlerBehavior), v("design:type", Object)], $V.prototype, "actionHandlerBehavior", void 0);
    u([J(Vt), v("design:type", Object)], $V.prototype, "ironResizableBehavior", void 0);
    u([J(), v("design:type", YV)], $V.prototype, "ytScrollableChipCloudBehavior", void 0);
    u([J(Xz), v("design:type", Object)], $V.prototype, "ytdReduxBehavior", void 0);
    u([P(), v("design:type", Object)], $V.prototype, "data", void 0);
    u([P({
        value: 0
    }), v("design:type", Number)], $V.prototype, "selectedIndex", void 0);
    u([P({
        value: 320
    }), v("design:type", Number)], $V.prototype, "scrollDistance", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], $V.prototype, "isDarkTheme", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], $V.prototype, "notSticky", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], $V.prototype, "transparentBackground", void 0);
    u([P({
        reflectToAttribute: !0,
        computed: "computeStyle(data.styleType)"
    }), v("design:type", String)], $V.prototype, "componentStyle", void 0);
    u([P({
        selector: Hfb
    }), v("design:type", Boolean)], $V.prototype, "guideIsExpanded", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], $V.prototype, "shouldHide", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], $V.prototype, "disableSticky", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], $V.prototype, "fluidWidth", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], $V.prototype, "isClipList", void 0);
    u([P(), v("design:type", Object)], $V.prototype, "isWatchPage", void 0);
    u([Ty("#chips"), v("design:type", Object)], $V.prototype, "JSC$15061_chipsSelector", void 0);
    u([P({
        value: !1,
        reflectToAttribute: !0
    }), v("design:type", Boolean)], $V.prototype, "updating", void 0);
    u([Wy("data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $V.prototype, "dataChanged", null);
    u([O("guideIsExpanded"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $V.prototype, "onGuideIsExpandedChanged", null);
    u([M("iron-resize"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $V.prototype, "onResize", null);
    u([Wy("isChannelPageGrid", "disableSticky", "data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $V.prototype, "updateChipBarWidthAndTop", null);
    u([L("componentStyle"), v("design:type", Boolean), v("design:paramtypes", [])], $V.prototype, "isChannelPageGrid", null);
    u([L("componentStyle"), v("design:type", Boolean), v("design:paramtypes", [])], $V.prototype, "isHashtagLandingPage", null);
    u([L("componentStyle"), v("design:type", Boolean), v("design:paramtypes", [])], $V.prototype, "isDisableDeselectEvent", null);
    u([L("data"), v("design:type", Object), v("design:paramtypes", [])], $V.prototype, "sortFilterHeaderRendererData", null);
    u([P({
        reflectToAttribute: !0
    }), L("componentStyle"), v("design:type", Boolean), v("design:paramtypes", [])], $V.prototype, "frostedGlass", null);
    $V = u([R({
        is: "ytd-feed-filter-chip-bar-renderer",
        disableElementRegistration: !0
    })], $V);
    U($V, "ytd-feed-filter-chip-bar-renderer", function() {
        if (oec !== void 0)
            return oec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"chips-wrapper\" class=\"style-scope ytd-feed-filter-chip-bar-renderer\">\n  <div id=\"chips-content\" class=\"style-scope ytd-feed-filter-chip-bar-renderer\">\n    <div id=\"left-arrow\" class=\"style-scope ytd-feed-filter-chip-bar-renderer\">\n      <div id=\"left-arrow-button\" class=\"style-scope ytd-feed-filter-chip-bar-renderer\"></div>\n    </div>\n    <div id=\"filter\" class=\"style-scope ytd-feed-filter-chip-bar-renderer\"></div>\n    <div id=\"scroll-container\" class=\"style-scope ytd-feed-filter-chip-bar-renderer\">\n      <iron-selector id=\"chips\" activate-event=\"\" role=\"tablist\" selected=\"[[selectedIndex]]\" selected-attribute=\"selected\" on-selected-changed=\"updateSelectedIndexFromBinding\" class=\"style-scope ytd-feed-filter-chip-bar-renderer\">\n      </iron-selector>\n    </div>\n    <div id=\"right-arrow\" class=\"style-scope ytd-feed-filter-chip-bar-renderer\">\n      <div id=\"right-arrow-button\" class=\"style-scope ytd-feed-filter-chip-bar-renderer\"></div>\n    </div>\n  </div>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return oec = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j022") ? 1 : 2
    });
    var tec;
    var uec = [10, 12, 14, 16, 18, 20, 24, 28, 32, 36]
      , vec = [20, 22, 24, 26, 28, 32, 36, 40, 48, 56, 64, 72, 84, 96, 120]
      , wec = function() {
        var a = I.apply(this, arguments) || this;
        a.fontFamily = "PROMO_FONT_FAMILY_YOUTUBE_SANS_BOLD";
        a.hideOverflow = !1;
        a.useRoboto = !1;
        a.fontClass = "";
        a.overflown = !1;
        a.actionMap = {
            "yt-window-resized": "resize"
        };
        return a
    };
    k(wec, I);
    f = wec.prototype;
    f.attached = function() {
        var a = this;
        switch (this.fontFamily) {
        case "PROMO_FONT_FAMILY_ROBOTO_BOLD":
            this.useRoboto = !0;
            this.fontWeight = 700;
            break;
        case "PROMO_FONT_FAMILY_YOUTUBE_SANS_BOLD":
            this.useRoboto = !1;
            this.fontWeight = 700;
            break;
        case "PROMO_FONT_FAMILY_YOUTUBE_SANS_MEDIUM":
            this.useRoboto = !1;
            this.fontWeight = 500;
            break;
        case "PROMO_FONT_FAMILY_YOUTUBE_SANS_SEMIBOLD":
            this.useRoboto = !1;
            this.fontWeight = 600;
            break;
        case "PROMO_FONT_FAMILY_YOUTUBE_SANS_LIGHT":
            this.useRoboto = !1;
            this.fontWeight = 400;
            break;
        default:
            this.useRoboto = !1,
            this.fontWeight = 700;
        }
        this.setParentConstraints();
        ht(this, function() {
            a.resize()
        });
        if (!Wd) {
            var b, c, d;
            (b = document) == null || (c = b.fonts) == null || (d = c.ready) == null || d.then(function() {
                a.resize()
            })
        }
    }
    ;
    f.dataChanged = function() {
        this.resize()
    }
    ;
    f.guideIsExpandedChanged = function() {
        this.resize()
    }
    ;
    f.resize = function() {
        if (this.textNode.offsetWidth || this.textNode.offsetWidth) {
            this.overflown && (this.overflown = !1,
            this.textNode.classList.remove("overflown"));
            this.textNode.style.visibility = "hidden";
            var a = this.getMaxNumLines()
              , b = this.getMinFont()
              , c = this.getMaxFont()
              , d = this.useRoboto ? uec : vec;
            for (d = d.filter(function(h) {
                return h <= c && h >= b
            }); d.length > 1; ) {
                var e = Math.floor(d.length / 2);
                this.updateFontSize(d[e]);
                if (this.textNode.offsetWidth <= this.getMaxWidth() && this.textNode.offsetHeight <= this.getMaxHeight() && this.textNode.getClientRects().length <= a)
                    d = d.slice(e, d.length);
                else if (this.textNode.offsetWidth > this.getMaxWidth() || this.textNode.offsetHeight > this.getMaxHeight() || this.textNode.getClientRects().length > a)
                    d = d.slice(0, e);
                else
                    break
            }
            this.updateFontSize(d[d.length - 1]);
            this.textNode.style.visibility = "inherit";
            this.handleOverflow(a)
        }
    }
    ;
    f.handleOverflow = function(a) {
        this.hideOverflow && this.maxLines && this.textNode.getClientRects().length > a && (this.overflown = !0,
        this.textNode.classList.add("overflown"),
        this.textNode.style.setProperty("-webkit-line-clamp", a.toString()))
    }
    ;
    f.updateFontSize = function(a) {
        this.fontClass && this.textNode.classList.remove(this.fontClass);
        this.fontClass = (this.useRoboto ? "roboto-" : "yt-sans-") + a;
        this.textNode.classList.add(this.fontClass)
    }
    ;
    f.getMaxFont = function() {
        var a = this.useRoboto ? uec : vec;
        a = a[a.length - 1];
        return this.maxFontSize && this.maxFontSize <= a ? this.maxFontSize : a
    }
    ;
    f.getMinFont = function() {
        var a = (this.useRoboto ? uec : vec)[0];
        return this.minFontSize && this.minFontSize >= a ? this.minFontSize : a
    }
    ;
    f.getMaxWidth = function() {
        return this.maxWidth ? this.maxWidth : this.containerNode.offsetWidth
    }
    ;
    f.getMaxHeight = function() {
        return this.maxHeight ? this.maxHeight : this.containerNode.offsetHeight
    }
    ;
    f.getMaxNumLines = function() {
        return this.maxLines && this.text ? this.maxLines + Zw(this.text).split("\n").length - 1 : Infinity
    }
    ;
    f.setParentConstraints = function() {
        this.maxWidth && (this.containerNode.style.maxWidth = this.maxWidth + "px");
        this.maxHeight && (this.containerNode.style.maxHeight = this.maxHeight + "px");
        if (this.fontWeight) {
            if (this.useRoboto && this.fontWeight !== 400 && this.fontWeight !== 500)
                throw Error(this.fontWeight + " is not an approved Roboto font weight.");
            this.textNode.style.fontWeight = this.fontWeight.toString()
        }
    }
    ;
    var aW = wec;
    aW.prototype.guideIsExpandedChanged = aW.prototype.guideIsExpandedChanged;
    aW.prototype.dataChanged = aW.prototype.dataChanged;
    u([J(X.YtRendererBehavior), v("design:type", Object)], aW.prototype, "ytRendererBehavior", void 0);
    u([J(Xz), v("design:type", Object)], aW.prototype, "ytdReduxBehavior", void 0);
    u([J(EA.YtActionHandlerBehavior), v("design:type", Object)], aW.prototype, "actionHandlerBehavior", void 0);
    u([P(), v("design:type", Object)], aW.prototype, "text", void 0);
    u([P(), v("design:type", String)], aW.prototype, "fontFamily", void 0);
    u([P(), v("design:type", Number)], aW.prototype, "maxWidth", void 0);
    u([P(), v("design:type", Number)], aW.prototype, "maxHeight", void 0);
    u([P(), v("design:type", Number)], aW.prototype, "maxFontSize", void 0);
    u([P(), v("design:type", Number)], aW.prototype, "minFontSize", void 0);
    u([P(), v("design:type", Number)], aW.prototype, "maxLines", void 0);
    u([P(), v("design:type", Object)], aW.prototype, "hideOverflow", void 0);
    u([P({
        selector: Hfb
    }), v("design:type", Boolean)], aW.prototype, "guideIsExpanded", void 0);
    u([Ty("#container"), v("design:type", HTMLElement)], aW.prototype, "containerNode", void 0);
    u([Ty("#text"), v("design:type", HTMLElement)], aW.prototype, "textNode", void 0);
    u([Wy("text"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], aW.prototype, "dataChanged", null);
    u([Wy("guideIsExpanded"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], aW.prototype, "guideIsExpandedChanged", null);
    aW = u([R({
        disableElementRegistration: !0,
        is: "yt-dynamic-sizing-formatted-string"
    })], aW);
    U(aW, "yt-dynamic-sizing-formatted-string", function() {
        if (tec !== void 0)
            return tec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"container\" class=\"dynamic-text-container style-scope yt-dynamic-sizing-formatted-string\">\n  <yt-formatted-string id=\"text\" disable-attributed-string=\"\" text=\"[[text]]\" class=\"style-scope yt-dynamic-sizing-formatted-string\"></yt-formatted-string>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return tec = a
    }, {
        mode: 1
    });
    var xec;
    var yec = ja(["color:", ";"])
      , zec = ja(["color:", ";"])
      , Aec = ja("color: ;--yt-endpoint-color: ;--yt-endpoint-hover-color: ;--yt-endpoint-visited-color: ;--yt-formatted-string-bold-font-weight: ;".split(" "))
      , Bec = ja(["color:", ";"])
      , Cec = ja(["--yt-button-color:", ";background-color:", ";"])
      , Dec = function() {
        var a = I.apply(this, arguments) || this;
        a.tileLottieAnimationRef = {};
        a.backgroundLottieAnimationRef = {};
        a.isOnHoverBehaviorForLottieEnabled = !0;
        a.useBiggerShowcaseImage = y("enable_desktop_search_bigger_thumbs");
        a.actionMap = {
            "ytd-update-elements-per-row-action": "onUpdateElementsPerRowAction",
            "yt-dark-mode-toggled-action": "onDarkModeToggledAction",
            "yt-open-video-preview-action": "pauseLottie"
        };
        return a
    };
    k(Dec, I);
    f = Dec.prototype;
    f.attached = function() {
        this.requestElementsPerRow();
        this.isDarkTheme = !!document.documentElement.hasAttribute("dark");
        this.data && (this.currentColorData = this.isDarkTheme ? this.data.darkColorData : this.data.lightColorData)
    }
    ;
    f.configureRendererStamper = function() {
        return {
            primaryButton: {
                id: "primary-button",
                mapping: {
                    buttonRenderer: "ytd-button-renderer",
                    toggleButtonRenderer: "ytd-toggle-button-renderer"
                },
                reuseComponents: !0
            },
            secondaryButton: {
                id: "secondary-button",
                mapping: {
                    buttonRenderer: "ytd-button-renderer",
                    toggleButtonRenderer: "ytd-toggle-button-renderer"
                },
                reuseComponents: !0
            },
            "data.dismissButton": {
                id: "dismiss-button",
                mapping: {
                    buttonRenderer: "ytd-button-renderer"
                }
            },
            dismissedRenderer: {
                id: "dismissed",
                mapping: {
                    notificationTextRenderer: "ytd-notification-text-renderer",
                    notificationMultiActionRenderer: "ytd-notification-multi-action-renderer"
                }
            }
        }
    }
    ;
    f.dataChanged = function() {
        if (this.data) {
            this.requestElementsPerRow();
            this.updateButtonPalette();
            var a = this.hasStaticTile(this.data) || this.hasTileLottie(this.data);
            a !== this.hasTile && this.set("hasTile", a);
            a = this.hasLogo(this.data) || !!this.data.badgeText;
            a !== this.hasMetadata && this.set("hasMetadata", a);
            this.currentColorData = this.isDarkTheme ? this.data.darkColorData : this.data.lightColorData;
            this.maybeInitializeTileLottie();
            this.maybeInitializeBackgroundLottie()
        }
    }
    ;
    f.themeChanged = function() {
        this.data && (this.set("currentColorData", this.isDarkTheme ? this.data.darkColorData : this.data.lightColorData),
        this.maybeInitializeTileLottie(),
        this.maybeInitializeBackgroundLottie())
    }
    ;
    f.currentColorChanged = function() {
        this.updateButtonPalette()
    }
    ;
    f.computeBackgroundStyle = function(a) {
        if (a && this.data) {
            var b = [];
            if (this.data.lightBackgroundImage && this.data.darkBackgroundImage) {
                var c = tB((this.isDarkTheme ? this.data.darkBackgroundImage : this.data.lightBackgroundImage).thumbnails);
                c && b.push("background-image: url(\"" + c + "\");")
            }
            var d;
            ((d = a.basicColorData) == null ? void 0 : d.backgroundColor) !== void 0 && b.push("background-color: " + iy(a.basicColorData.backgroundColor) + ";");
            return tc(b.join(""))
        }
    }
    ;
    f.onDarkModeToggledAction = function(a) {
        a !== this.isDarkTheme && this.set("isDarkTheme", a)
    }
    ;
    f.getCurrentLogo = function(a, b) {
        if (a)
            return b ? a.darkLogoImage : a.lightLogoImage
    }
    ;
    f.getCurrentStaticTileImage = function(a, b) {
        if (this.hasStaticTile(a))
            return a.darkTileImage ? b ? a.darkTileImage : a.tileImage : a.tileImage
    }
    ;
    f.computeTitleStyle = function(a) {
        if (this.data && this.data.title && a && a.basicColorData && a.basicColorData.foregroundTitleColor !== void 0)
            return hh(yec, hy(a.basicColorData.foregroundTitleColor))
    }
    ;
    f.computeSubtitleStyle = function(a) {
        if (this.data && this.data.subtitle && a && a.basicColorData && a.basicColorData.foregroundBodyColor !== void 0)
            return hh(zec, hy(a.basicColorData.foregroundBodyColor))
    }
    ;
    f.computeSupplementalStyle = function(a) {
        if (this.data && this.data.supplementalText && a && a.supplementalTextColor !== void 0)
            return a = hy(a.supplementalTextColor),
            hh(Aec, a, a, a, a, "700")
    }
    ;
    f.computeBadgeStyle = function(a) {
        if (this.data && this.data.badgeText && a && a.basicColorData && a.basicColorData.foregroundActivatedColor !== void 0)
            return hh(Bec, hy(a.basicColorData.foregroundActivatedColor))
    }
    ;
    f.computeDismissIconStyle = function(a) {
        var b, c;
        if ((a == null ? 0 : (b = a.dismissButtonColorData) == null ? 0 : b.foregroundTitleColor) && (a == null ? 0 : (c = a.dismissButtonColorData) == null ? 0 : c.backgroundColor))
            return hh(Cec, iy(a.dismissButtonColorData.foregroundTitleColor), iy(a.dismissButtonColorData.backgroundColor))
    }
    ;
    f.computeBannerStyle = function(a) {
        return a ? a.toLowerCase().replace(/_/g, "-") : ""
    }
    ;
    f.computeLocation = function(a) {
        switch (a == null ? void 0 : a.location) {
        case "LOCATION_CONTEXT_SEARCH_PAGE":
            return "search";
        case "LOCATION_CONTEXT_SLOT_ZERO_HOME":
            return "slot-zero-home";
        }
    }
    ;
    f.shouldShowTileSection = function(a, b, c) {
        return !this.shouldExpandLogo(a, b, c) && b
    }
    ;
    f.shouldShowExpandedLogoSection = function(a, b, c) {
        return this.shouldExpandLogo(a, b, c) && a !== void 0 && this.hasLogo(a)
    }
    ;
    f.shouldExpandLogo = function(a, b, c) {
        return a && b ? !1 : c >= 2
    }
    ;
    f.hasStaticTile = function(a) {
        return !(a == null || !a.tileImage)
    }
    ;
    f.hasTileLottie = function(a) {
        var b;
        return !!(a == null ? 0 : (b = a.tileLottie) == null ? 0 : b.url)
    }
    ;
    f.hasLogo = function(a) {
        return this.getCurrentLogo(a, this.isDarkTheme) !== void 0
    }
    ;
    f.getLogoHeight = function(a) {
        return this.logoWithPadding(a) ? "26" : "20"
    }
    ;
    f.getExpandedLogoHeight = function(a) {
        return this.logoWithPadding(a) ? "31" : "24"
    }
    ;
    f.getLogoImageId = function(a) {
        return this.logoWithPadding(a) ? "logo-image-with-padding" : "logo-image"
    }
    ;
    f.hasBackgroundLottie = function(a) {
        var b;
        return !!(a == null ? 0 : (b = a.backgroundLottie) == null ? 0 : b.url)
    }
    ;
    f.maybePlayLottie = function() {
        if (this.isOnHoverBehaviorForLottieEnabled) {
            var a, b;
            (a = this.tileLottieAnimationRef) == null || (b = a.lottieEl) == null || b.play();
            var c, d;
            (c = this.backgroundLottieAnimationRef) == null || (d = c.lottieEl) == null || d.play()
        }
    }
    ;
    f.maybePauseLottie = function() {
        if (this.isOnHoverBehaviorForLottieEnabled) {
            var a, b;
            (a = this.tileLottieAnimationRef) == null || (b = a.lottieEl) == null || b.pause();
            var c, d;
            (c = this.backgroundLottieAnimationRef) == null || (d = c.lottieEl) == null || d.pause()
        }
    }
    ;
    f.pauseLottie = function() {
        var a, b;
        (a = this.tileLottieAnimationRef) == null || (b = a.lottieEl) == null || b.pause();
        var c, d;
        (c = this.backgroundLottieAnimationRef) == null || (d = c.lottieEl) == null || d.pause();
        this.isOnHoverBehaviorForLottieEnabled || (this.isOnHoverBehaviorForLottieEnabled = !0)
    }
    ;
    f.performPrimaryButtonAction = function() {
        var a, b, c;
        ((a = this.data) == null ? 0 : (b = a.primaryButton) == null ? 0 : (c = b.buttonRenderer) == null ? 0 : c.command) && this.ytComponentBehavior.resolveCommand(this.data.primaryButton.buttonRenderer.command)
    }
    ;
    f.requestElementsPerRow = function() {
        zv(this.hostElement, "yt-request-elements-per-row")
    }
    ;
    f.updateButtonPalette = function() {
        if (this.data && this.currentColorData) {
            var a;
            ((a = this.data.dismissButton) == null ? 0 : a.buttonRenderer) && this.currentColorData.dismissButtonColorData && (this.data.dismissButton.buttonRenderer.colorData = {
                basicColorPaletteData: this.currentColorData.dismissButtonColorData
            },
            this.data.dismissButton.buttonRenderer.style = void 0,
            this.set("dismissButton", {
                buttonRenderer: Object.assign({}, this.data.dismissButton.buttonRenderer)
            }));
            var b;
            if ((b = this.data.primaryButton) == null ? 0 : b.buttonRenderer)
                this.currentColorData.primaryButtonColorData ? (this.data.primaryButton.buttonRenderer.colorData = {
                    basicColorPaletteData: this.currentColorData.primaryButtonColorData
                },
                this.data.primaryButton.buttonRenderer.style = void 0) : this.currentColorData.primaryButtonStyleType && (this.data.primaryButton.buttonRenderer.style = this.currentColorData.primaryButtonStyleType,
                this.data.primaryButton.buttonRenderer.colorData = void 0),
                this.set("primaryButton", {
                    buttonRenderer: Object.assign({}, this.data.primaryButton.buttonRenderer)
                });
            var c;
            if ((c = this.data.secondaryButton) == null ? 0 : c.buttonRenderer)
                this.currentColorData.secondaryButtonColorData ? (this.data.secondaryButton.buttonRenderer.colorData = {
                    basicColorPaletteData: this.currentColorData.secondaryButtonColorData
                },
                this.data.secondaryButton.buttonRenderer.style = void 0) : this.currentColorData.secondaryButtonStyleType && (this.data.secondaryButton.buttonRenderer.style = this.currentColorData.secondaryButtonStyleType,
                this.data.secondaryButton.buttonRenderer.colorData = void 0),
                this.set("secondaryButton", {
                    buttonRenderer: Object.assign({}, this.data.secondaryButton.buttonRenderer)
                });
            var d;
            ((d = this.data.primaryButton) == null ? 0 : d.toggleButtonRenderer) && this.set("primaryButton", {
                toggleButtonRenderer: Object.assign({}, this.data.primaryButton.toggleButtonRenderer)
            });
            var e;
            ((e = this.data.secondaryButton) == null ? 0 : e.toggleButtonRenderer) && this.set("secondaryButton", {
                toggleButtonRenderer: Object.assign({}, this.data.secondaryButton.toggleButtonRenderer)
            })
        }
    }
    ;
    f.maybeInitializeTileLottie = function() {
        if (this.hasTileLottie(this.data)) {
            var a = this.getTileLottieDataBasedOnTheme(), b, c;
            if (a.url !== ((b = this.tileLottiePlayerProps) == null ? void 0 : (c = b.animationConfig) == null ? void 0 : c.path)) {
                var d, e;
                (d = this.tileLottieAnimationRef) == null || (e = d.lottieEl) == null || e.destroy();
                var h;
                this.isOnHoverBehaviorForLottieEnabled = !((h = a.settings) == null ? 0 : h.autoplay);
                var l, m;
                this.tileLottiePlayerProps = {
                    animationRef: this.tileLottieAnimationRef,
                    animationConfig: {
                        name: this.isDarkTheme ? "STATEMENT_BANNER_TILE_LOTTIE_DARK" : "STATEMENT_BANNER_TILE_LOTTIE_LIGHT",
                        autoplay: (m = (l = a.settings) == null ? void 0 : l.autoplay) != null ? m : !1,
                        loop: this.getLottieLoopValue(a.settings),
                        renderer: "svg",
                        rendererSettings: {
                            viewBoxOnly: !1,
                            preserveAspectRatio: "xMidYMid slice"
                        }
                    },
                    listeners: {
                        complete: this.onLottieComplete.bind(this)
                    }
                };
                typeof a.url === "string" ? this.tileLottiePlayerProps.animationConfig.path = a.url : this.tileLottiePlayerProps.animationConfig.animationData = a.url
            }
        }
    }
    ;
    f.maybeInitializeBackgroundLottie = function() {
        if (this.hasBackgroundLottie(this.data)) {
            var a = this.getBackgroundLottieDataBasedOnTheme(), b, c;
            if (a.url !== ((b = this.backgroundLottiePlayerProps) == null ? void 0 : (c = b.animationConfig) == null ? void 0 : c.path)) {
                var d, e;
                (d = this.backgroundLottieAnimationRef) == null || (e = d.lottieEl) == null || e.destroy();
                var h;
                this.isOnHoverBehaviorForLottieEnabled = !((h = a.settings) == null ? 0 : h.autoplay);
                var l, m;
                this.backgroundLottiePlayerProps = {
                    animationRef: this.backgroundLottieAnimationRef,
                    animationConfig: {
                        name: this.isDarkTheme ? "STATEMENT_BANNER_BACKGROUND_LOTTIE_DARK" : "STATEMENT_BANNER_BACKGROUND_LOTTIE_LIGHT",
                        autoplay: (m = (l = a.settings) == null ? void 0 : l.autoplay) != null ? m : !1,
                        loop: this.getLottieLoopValue(a.settings),
                        renderer: "svg",
                        rendererSettings: {
                            viewBoxOnly: !1,
                            preserveAspectRatio: "xMidYMid slice"
                        }
                    },
                    listeners: {
                        complete: this.onLottieComplete.bind(this)
                    }
                };
                typeof a.url === "string" ? this.backgroundLottiePlayerProps.animationConfig.path = a.url : this.backgroundLottiePlayerProps.animationConfig.animationData = a.url
            }
        }
    }
    ;
    f.onLottieComplete = function() {
        if (!this.isOnHoverBehaviorForLottieEnabled) {
            var a;
            ((a = this.tileLottieAnimationRef) == null ? void 0 : a.lottieEl) !== void 0 && (this.tileLottieAnimationRef.lottieEl.loop = !0);
            var b;
            ((b = this.backgroundLottieAnimationRef) == null ? void 0 : b.lottieEl) !== void 0 && (this.backgroundLottieAnimationRef.lottieEl.loop = !0);
            this.isOnHoverBehaviorForLottieEnabled = !0
        }
    }
    ;
    f.getTileLottieDataBasedOnTheme = function() {
        var a;
        if (this.isDarkTheme && ((a = this.data) == null ? 0 : a.darkThemeTileLottie))
            return this.data.darkThemeTileLottie;
        var b;
        return ((b = this.data) == null ? 0 : b.tileLottie) ? this.data.tileLottie : {}
    }
    ;
    f.getBackgroundLottieDataBasedOnTheme = function() {
        var a;
        if (this.isDarkTheme && ((a = this.data) == null ? 0 : a.darkThemeBackgroundLottie))
            return this.data.darkThemeBackgroundLottie;
        var b;
        return ((b = this.data) == null ? 0 : b.backgroundLottie) ? this.data.backgroundLottie : {}
    }
    ;
    f.onUpdateElementsPerRowAction = function(a) {
        a && this.elementsPerRow !== a && (this.elementsPerRow = a)
    }
    ;
    f.getLottieLoopValue = function(a) {
        return a ? a.loop !== void 0 ? a.loop : a.loopCount ? a.loopCount - 1 : !0 : !0
    }
    ;
    f.logoWithPadding = function(a) {
        var b, c, d;
        return (a = (b = this.getCurrentLogo(a, this.isDarkTheme)) == null ? void 0 : (c = b.thumbnails) == null ? void 0 : (d = c[0]) == null ? void 0 : d.height) && a % 31 === 0 ? !0 : !1
    }
    ;
    var bW = Dec;
    bW.prototype.currentColorChanged = bW.prototype.currentColorChanged;
    bW.prototype.themeChanged = bW.prototype.themeChanged;
    bW.prototype.dataChanged = bW.prototype.dataChanged;
    u([J(X.YtRendererBehavior), v("design:type", Object)], bW.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], bW.prototype, "ytRendererstamperBehavior", void 0);
    u([J(Zz), v("design:type", Object)], bW.prototype, "ytdDismissibleItemBehavior", void 0);
    u([J(EA.YtActionHandlerBehavior), v("design:type", Object)], bW.prototype, "actionHandlerBehavior", void 0);
    u([J(JA.YtComponentBehavior), v("design:type", Object)], bW.prototype, "ytComponentBehavior", void 0);
    u([P(), v("design:type", Object)], bW.prototype, "data", void 0);
    u([P(), v("design:type", Object)], bW.prototype, "primaryButton", void 0);
    u([P(), v("design:type", Object)], bW.prototype, "secondaryButton", void 0);
    u([P({
        reflectToAttribute: !0,
        value: 3
    }), v("design:type", Number)], bW.prototype, "elementsPerRow", void 0);
    u([P({
        reflectToAttribute: !0,
        value: !1
    }), v("design:type", Boolean)], bW.prototype, "isDarkTheme", void 0);
    u([P({
        reflectToAttribute: !0,
        value: !1
    }), v("design:type", Boolean)], bW.prototype, "hasTile", void 0);
    u([P({
        reflectToAttribute: !0,
        value: !1
    }), v("design:type", Boolean)], bW.prototype, "hasMetadata", void 0);
    u([P(), v("design:type", Object)], bW.prototype, "currentColorData", void 0);
    u([P({
        reflectToAttribute: !0,
        computed: "computeBannerStyle(data.style)"
    }), v("design:type", String)], bW.prototype, "bannerStyle", void 0);
    u([P({
        reflectToAttribute: !0,
        computed: "computeLocation(data.shelfContext)"
    }), v("design:type", String)], bW.prototype, "location", void 0);
    u([P(), v("design:type", Object)], bW.prototype, "tileLottiePlayerProps", void 0);
    u([P(), v("design:type", Object)], bW.prototype, "tileLottieAnimationRef", void 0);
    u([P(), v("design:type", Object)], bW.prototype, "backgroundLottiePlayerProps", void 0);
    u([P(), v("design:type", Object)], bW.prototype, "backgroundLottieAnimationRef", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], bW.prototype, "useBiggerShowcaseImage", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], bW.prototype, "isHideEnclosingAction", void 0);
    u([Wy("data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], bW.prototype, "dataChanged", null);
    u([Wy("isDarkTheme"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], bW.prototype, "themeChanged", null);
    u([Wy("currentColorData"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], bW.prototype, "currentColorChanged", null);
    bW = u([R({
        is: "ytd-statement-banner-renderer",
        disableElementRegistration: !0
    })], bW);
    U(bW, "ytd-statement-banner-renderer", function() {
        if (xec !== void 0)
            return xec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"dismissible\" on-mouseleave=\"maybePauseLottie\" on-mouseover=\"maybePlayLottie\" class=\"style-scope ytd-statement-banner-renderer\">\n  <div id=\"background-content\" style$=\"[[computeBackgroundStyle(currentColorData)]]\" class=\"style-scope ytd-statement-banner-renderer\">\n    <ytd-lottie-player id=\"background-lottie\" data=\"[[backgroundLottiePlayerProps]]\" hidden=\"[[!hasBackgroundLottie(data)]]\" class=\"style-scope ytd-statement-banner-renderer\">\n  </ytd-lottie-player></div>\n  <div id=\"foreground-content\" class=\"style-scope ytd-statement-banner-renderer\">\n    <div class=\"showcase-image style-scope ytd-statement-banner-renderer\" hidden=\"[[!shouldShowTileSection(data, hasTile, elementsPerRow)]]\">\n      <div hidden=\"[[!hasTile]]\" id=\"tile-container\" on-click=\"performPrimaryButtonAction\" class=\"style-scope ytd-statement-banner-renderer\">\n        <yt-img-shadow id=\"tile-image\" hidden=\"[[!hasStaticTile(data)]]\" object-fit=\"CONTAIN\" thumbnail=\"[[getCurrentStaticTileImage(data, isDarkTheme)]]\" class=\"style-scope ytd-statement-banner-renderer\">\n        </yt-img-shadow>\n        <ytd-lottie-player id=\"tile-lottie\" data=\"[[tileLottiePlayerProps]]\" hidden=\"[[!hasTileLottie(data)]]\" class=\"style-scope ytd-statement-banner-renderer\">\n      </ytd-lottie-player></div>\n    </div>\n    <div class=\"showcase-image style-scope ytd-statement-banner-renderer\" hidden=\"[[!shouldShowExpandedLogoSection(data, hasTile, elementsPerRow)]]\" id=\"logo-container\">\n      <div id=\"logo-wrapper\" class=\"style-scope ytd-statement-banner-renderer\">\n        <yt-img-shadow id=\"logo-image\" height=\"[[getExpandedLogoHeight(data)]]\" thumbnail=\"[[getCurrentLogo(data, isDarkTheme)]]\" class=\"style-scope ytd-statement-banner-renderer\">\n        </yt-img-shadow>\n      </div>\n    </div>\n    <div id=\"details-container\" class=\"style-scope ytd-statement-banner-renderer\">\n      <div id=\"text-container\" class=\"style-scope ytd-statement-banner-renderer\">\n        <div id=\"metadata-container\" hidden=\"[[!hasMetadata]]\" class=\"style-scope ytd-statement-banner-renderer\">\n          <yt-img-shadow dimension=\"height\" height$=\"[[getLogoHeight(data)]]\" hidden=\"[[shouldExpandLogo(data, hasTile, elementsPerRow)]]\" id$=\"[[getLogoImageId(data)]]\" thumbnail=\"[[getCurrentLogo(data, isDarkTheme)]]\" class=\"style-scope ytd-statement-banner-renderer\">\n          </yt-img-shadow>\n          <div id=\"badge-container\" style$=\"[[computeBadgeStyle(currentColorData)]]\" class=\"style-scope ytd-statement-banner-renderer\">\n            <yt-formatted-string id=\"badge\" text=\"[[data.badgeText]]\" class=\"style-scope ytd-statement-banner-renderer\"></yt-formatted-string>\n          </div>\n        </div>\n        <div id=\"dynamic-title\" style$=\"[[computeTitleStyle(currentColorData)]]\" on-click=\"performPrimaryButtonAction\" class=\"style-scope ytd-statement-banner-renderer\">\n          <yt-dynamic-sizing-formatted-string font-family=\"[[data.titleFontFamily]]\" max-font-size=\"36\" max-height=\"110\" max-lines=\"2\" min-font-size=\"20\" text=\"[[data.title]]\" class=\"style-scope ytd-statement-banner-renderer\">\n          </yt-dynamic-sizing-formatted-string>\n        </div>\n        <div id=\"subtitle-container\" style$=\"[[computeSubtitleStyle(currentColorData)]]\" class=\"style-scope ytd-statement-banner-renderer\">\n          <yt-formatted-string id=\"subtitle\" text=\"[[data.subtitle]]\" class=\"style-scope ytd-statement-banner-renderer\"></yt-formatted-string>\n        </div>\n        <div id=\"supplemental-text-container\" hidden=\"[[!data.supplementalText]]\" style$=\"[[computeSupplementalStyle(currentColorData)]]\" class=\"style-scope ytd-statement-banner-renderer\">\n          <yt-formatted-string id=\"supplemental-text\" text=\"[[data.supplementalText]]\" class=\"style-scope ytd-statement-banner-renderer\">\n          </yt-formatted-string>\n        </div>\n      </div>\n      <div id=\"button-container\" class=\"style-scope ytd-statement-banner-renderer\">\n        <div id=\"button-wrapper\" class=\"style-scope ytd-statement-banner-renderer\">\n          <div id=\"primary-button\" class=\"style-scope ytd-statement-banner-renderer\"></div>\n          <div id=\"secondary-button\" class=\"style-scope ytd-statement-banner-renderer\"></div>\n        </div>\n      </div>\n    </div>\n    <div id=\"dismiss-button\" style$=\"[[computeDismissIconStyle(currentColorData, elementsPerRow)]]\" class=\"style-scope ytd-statement-banner-renderer\"></div>\n  </div>\n</div>\n<div id=\"dismissed\" class=\"style-scope ytd-statement-banner-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return xec = a
    }, {
        mode: 1
    });
    var Eec;
    YB("itemSectionRenderer", "aboutChannelRenderer", "ytd-about-channel-renderer");
    var Fec = function() {
        var a = I.apply(this, arguments) || this;
        a.businessEmailDisplayState = "HIDE_SECTION";
        return a
    };
    k(Fec, I);
    f = Fec.prototype;
    f.refit = function() {
        var a = this;
        Ez(function() {
            Ev(a.hostElement, "yt-refit-popups-action")
        });
        ht(this, function() {
            Ev(a.hostElement, "yt-refit-popups-action")
        })
    }
    ;
    f.onBusinessEmailClick = function() {
        this.metadata.bypassBusinessEmailCaptcha ? this.businessEmailDisplayState = "BUSINESS_EMAIL" : (mv("https://www.google.com/recaptcha/api.js?trustedtypes=true"),
        this.businessEmailDisplayState = "CAPTCHA")
    }
    ;
    f.businessEmailMetadataChanged = function() {
        this.revealButton || this.businessEmail || this.metadata.signInForBusinessEmail ? this.metadata.signInForBusinessEmail ? this.businessEmailDisplayState = "SIGN_IN_REQUIRED" : this.businessEmailErrorMessage ? this.businessEmailDisplayState = "ERROR_MESSAGE" : (this.businessEmailDisplayState = "REVEAL_BUTTON",
        this.metadata.businessEmail && (this.businessEmail = this.metadata.businessEmail)) : this.businessEmailDisplayState = "HIDE_SECTION"
    }
    ;
    f.detached = function() {
        this.businessEmailErrorMessage = this.businessEmail = void 0;
        this.businessEmailDisplayState = "HIDE_SECTION"
    }
    ;
    f.configureRendererStamper = function() {
        return {
            "data.flaggingButton": {
                id: "flagging-button",
                mapping: {
                    buttonRenderer: "ytd-button-renderer"
                }
            },
            "data.shareChannel": {
                id: "share-channel",
                mapping: {
                    buttonRenderer: "ytd-button-renderer"
                }
            },
            "data.dismissButton": {
                id: "dismiss-button",
                mapping: {
                    buttonRenderer: {
                        component: "ytd-button-renderer",
                        attributes: {
                            "dialog-dismiss": !0
                        }
                    }
                }
            },
            "metadata.links": {
                id: "link-list-container",
                mapping: {
                    channelExternalLinkViewModel: "yt-channel-external-link-view-model"
                }
            }
        }
    }
    ;
    f.computeEmailHref = function(a) {
        return "mailto:" + a
    }
    ;
    f.computeSafeUrl = function(a) {
        if (a)
            return Ob(a)
    }
    ;
    f.linkEndpoint = function(a) {
        return A(a.onTap, Ku)
    }
    ;
    f.linkEndpointToHref = function(a) {
        return this.ytComponentBehavior.computeHref_(this.linkEndpoint(a))
    }
    ;
    f.onYtServiceRequestCompleted = function(a) {
        var b;
        if ((b = a.detail.data) == null ? 0 : b.businessEmail)
            this.businessEmail = a.detail.data.businessEmail,
            this.businessEmailDisplayState = "BUSINESS_EMAIL";
        else {
            var c;
            if ((c = a.detail.data) == null ? 0 : c.errorMessage)
                this.businessEmailErrorMessage = a.detail.data.errorMessage,
                this.businessEmailDisplayState = "ERROR_MESSAGE"
        }
    }
    ;
    f.onBusinessEmailCaptchaSubmit = function() {
        if (this.metadata.channelId && this.metadata.onBusinessEmailRevealClickCommand) {
            var a = this.JSC$15081_captchaTextarea.value;
            if (a) {
                a = {
                    recaptcha_response_token: a,
                    channel_id: this.metadata.channelId
                };
                var b = A(this.metadata.onBusinessEmailRevealClickCommand, Ku);
                b && this.ytComponentBehavior.resolveCommand(b, {
                    form: a
                })
            }
        }
    }
    ;
    f.recaptchaSiteKey = function() {
        return "6Lf39AMTAAAAALPbLZdcrWDa8Ygmgk_fmGmrlRog"
    }
    ;
    da.Object.defineProperties(Fec.prototype, {
        metadata: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                var a;
                return A((a = this.data) == null ? void 0 : a.metadata, tPb)
            }
        },
        revealButton: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return A(this.metadata.businessEmailRevealButton, cv)
            }
        },
        channelDisplayUrl: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                if (this.metadata.displayCanonicalChannelUrl)
                    return this.metadata.displayCanonicalChannelUrl;
                if (this.metadata.canonicalChannelUrl) {
                    var a = new URL(this.metadata.canonicalChannelUrl);
                    return a.host + a.pathname
                }
            }
        },
        formattedDescription: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return this.metadata.description ? {
                    simpleText: this.metadata.description
                } : void 0
            }
        },
        shouldRendereVerifiedPhoneStatus: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return this.metadata.phoneVerifiedLabel !== "" && this.learnMoreCommand !== void 0
            }
        },
        learnMoreCommand: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return A(this.metadata.learnMoreOnTap, Ku)
            }
        }
    });
    var cW = Fec;
    cW.prototype.onYtServiceRequestCompleted = cW.prototype.onYtServiceRequestCompleted;
    cW.prototype.businessEmailMetadataChanged = cW.prototype.businessEmailMetadataChanged;
    cW.prototype.refit = cW.prototype.refit;
    u([J(JA.YtComponentBehavior), v("design:type", Object)], cW.prototype, "ytComponentBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], cW.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], cW.prototype, "ytRendererstamperBehavior", void 0);
    u([Ty("#g-recaptcha-response"), v("design:type", HTMLTextAreaElement)], cW.prototype, "JSC$15081_captchaTextarea", void 0);
    u([P(), v("design:type", Object)], cW.prototype, "data", void 0);
    u([L("data"), v("design:type", Object), v("design:paramtypes", [])], cW.prototype, "metadata", null);
    u([L("metadata"), v("design:type", Object), v("design:paramtypes", [])], cW.prototype, "revealButton", null);
    u([L("metadata"), v("design:type", Object), v("design:paramtypes", [])], cW.prototype, "channelDisplayUrl", null);
    u([Wy("metadata"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], cW.prototype, "refit", null);
    u([L("metadata"), v("design:type", Object), v("design:paramtypes", [])], cW.prototype, "formattedDescription", null);
    u([L("metadata", "learnMoreCommand"), v("design:type", Boolean), v("design:paramtypes", [])], cW.prototype, "shouldRendereVerifiedPhoneStatus", null);
    u([L("metadata"), v("design:type", Object), v("design:paramtypes", [])], cW.prototype, "learnMoreCommand", null);
    u([P(), v("design:type", String)], cW.prototype, "businessEmailDisplayState", void 0);
    u([P(), v("design:type", String)], cW.prototype, "businessEmail", void 0);
    u([P(), v("design:type", String)], cW.prototype, "businessEmailErrorMessage", void 0);
    u([Wy("metadata"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], cW.prototype, "businessEmailMetadataChanged", null);
    u([M("yt-service-request-completed"), v("design:type", Function), v("design:paramtypes", [CustomEvent]), v("design:returntype")], cW.prototype, "onYtServiceRequestCompleted", null);
    cW = u([R({
        is: "ytd-about-channel-renderer",
        disableElementRegistration: !0
    })], cW);
    U(cW, "ytd-about-channel-renderer", function() {
        if (Eec !== void 0)
            return Eec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"about-container\" class=\"style-scope ytd-about-channel-renderer\">\n  <div id=\"header-row\" hidden=\"[[!metadata.aboutPanelTitle]]\" class=\"style-scope ytd-about-channel-renderer\">\n    <h1 class=\"style-scope ytd-about-channel-renderer\">[[metadata.aboutPanelTitle]]</h1>\n    <div id=\"dismiss-button\" class=\"style-scope ytd-about-channel-renderer\"></div>\n  </div>\n\n  <yt-attributed-string id=\"description-container\" class=\"about-section style-scope ytd-about-channel-renderer\" data=\"[[formattedDescription]]\" hidden=\"[[!formattedDescription]]\" split-lines=\"\" userinput=\"true\">\n  </yt-attributed-string>\n\n  <div id=\"bio-container\" class=\"about-section style-scope ytd-about-channel-renderer\" hidden=\"[[!metadata.formattedBio]]\">\n    <h2 class=\"subheadline style-scope ytd-about-channel-renderer\">[[metadata.artistBioLabel]]</h2>\n    <yt-attributed-string id=\"bio-container\" class=\"about-section style-scope ytd-about-channel-renderer\" data=\"[[metadata.artistBio]]\" hidden=\"[[!metadata.artistBio]]\" split-lines=\"\" userinput=\"true\">\n    </yt-attributed-string>\n    <p class=\"style-scope ytd-about-channel-renderer\">[[metadata.artistBio]]</p>\n  </div>\n\n  <div id=\"links-section\" hidden=\"[[!metadata.links]]\" class=\"style-scope ytd-about-channel-renderer\">\n    <yt-attributed-string class=\"subheadline style-scope ytd-about-channel-renderer\" data=\"[[metadata.customLinksLabel]]\">\n    </yt-attributed-string>\n    <div id=\"link-list-container\" class=\"style-scope ytd-about-channel-renderer\">\n    </div>\n  </div>\n  <div id=\"custom-links-section\" hidden=\"[[!metadata.customLinks]]\" class=\"style-scope ytd-about-channel-renderer\">\n    <yt-attributed-string class=\"subheadline style-scope ytd-about-channel-renderer\" data=\"[[metadata.customLinksLabel]]\">\n    </yt-attributed-string>\n    <table id=\"links-container\" class=\"about-section style-scope ytd-about-channel-renderer\">\n      <template is=\"dom-repeat\" items=\"[[metadata.customLinks]]\" as=\"link\" class=\"style-scope ytd-about-channel-renderer\">\n        <tr hidden=\"[[!linkEndpointToHref(link)]]\" class=\"style-scope ytd-about-channel-renderer\">\n          <td class=\"image-container style-scope ytd-about-channel-renderer\">\n            <yt-image data=\"[[link.favicon]]\" width=\"32\" class=\"style-scope ytd-about-channel-renderer\"></yt-image>\n          </td>\n          <td class=\"href-container style-scope ytd-about-channel-renderer\">\n            <a class=\"yt-simple-endpoint style-scope ytd-about-channel-renderer\" href$=\"[[linkEndpointToHref(link)]]\" data=\"[[linkEndpoint(link)]]\">[[link.label]]</a>\n          </td>\n        </tr>\n      </template>\n    </table>\n  </div>\n\n  <div id=\"additional-info-container\" class=\"about-section style-scope ytd-about-channel-renderer\">\n    <yt-attributed-string class=\"subheadline style-scope ytd-about-channel-renderer\" data=\"[[metadata.additionalInfoLabel]]\"></yt-attributed-string>\n    <table class=\"style-scope ytd-about-channel-renderer\">\n      <tbody class=\"style-scope ytd-about-channel-renderer\"><tr class=\"description-item style-scope ytd-about-channel-renderer\" hidden=\"[[equals(businessEmailDisplayState, 'HIDE_SECTION')]]\">\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <yt-icon icon=\"mail\" class=\"style-scope ytd-about-channel-renderer\"></yt-icon>\n        </td>\n\n        <td hidden=\"[[!equals(businessEmailDisplayState, 'SIGN_IN_REQUIRED')]]\" class=\"style-scope ytd-about-channel-renderer\">\n          <yt-attributed-string data=\"[[metadata.signInForBusinessEmail]]\" class=\"style-scope ytd-about-channel-renderer\"></yt-attributed-string>\n        </td>\n\n        <td id=\"view-email-button-container\" hidden=\"[[!equals(businessEmailDisplayState, 'REVEAL_BUTTON')]]\" class=\"style-scope ytd-about-channel-renderer\">\n          <yt-button-view-model class=\"button style-scope ytd-about-channel-renderer\" data=\"[[revealButton]]\" on-click=\"onBusinessEmailClick\">\n          </yt-button-view-model>\n        </td>\n\n        <td hidden=\"[[!equals(businessEmailDisplayState, 'CAPTCHA')]]\" class=\"style-scope ytd-about-channel-renderer\">\n          \n          <div id=\"recaptcha\" class=\"g-recaptcha style-scope ytd-about-channel-renderer\" data-sitekey$=\"[[recaptchaSiteKey()]]\"></div>\n          <button id=\"submit-btn\" class=\"yt-uix-button yt-uix-button-size-default yt-uix-button-primary style-scope ytd-about-channel-renderer\" on-click=\"onBusinessEmailCaptchaSubmit\">\n            <span class=\"yt-uix-button-content style-scope ytd-about-channel-renderer\">[[metadata.businessEmailSubmitCaptchaLabel]] </span>\n          </button>\n        </td>\n        <td hidden=\"[[!equals(businessEmailDisplayState, 'ERROR_MESSAGE')]]\" class=\"style-scope ytd-about-channel-renderer\">\n          [[businessEmailErrorMessage]]\n        </td>\n\n        <td hidden=\"[[!equals(businessEmailDisplayState, 'BUSINESS_EMAIL')]]\" class=\"style-scope ytd-about-channel-renderer\">\n          <a id=\"email\" class=\"yt-simple-endpoint style-scope ytd-about-channel-renderer\" href$=\"[[computeEmailHref(businessEmail)]]\" target=\"_blank\">[[businessEmail]]</a>\n        </td>\n      </tr>\n\n      <tr class=\"description-item style-scope ytd-about-channel-renderer\" hidden=\"[[!shouldRendereVerifiedPhoneStatus]]\">\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <yt-icon icon=\"phone\" class=\"style-scope ytd-about-channel-renderer\"></yt-icon>\n        </td>\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <span class=\"style-scope ytd-about-channel-renderer\">[[metadata.phoneVerifiedLabel]]</span>\n          <a class=\"yt-simple-endpoint phone-status-info style-scope ytd-about-channel-renderer\" href$=\"[[computeHref_(learnMoreCommand)]]\" target=\"_blank\">\n            <yt-icon icon=\"info\" class=\"style-scope ytd-about-channel-renderer\"></yt-icon>\n          </a>\n        </td>\n      </tr>\n\n      <tr class=\"description-item style-scope ytd-about-channel-renderer\" hidden=\"[[!channelDisplayUrl]]\">\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <yt-icon icon=\"language\" class=\"style-scope ytd-about-channel-renderer\"></yt-icon>\n        </td>\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <a class=\"yt-simple-endpoint style-scope ytd-about-channel-renderer\" href$=\"[[metadata.canonicalChannelUrl]]\">[[channelDisplayUrl]]</a>\n        </td>\n      </tr>\n\n      <tr class=\"description-item style-scope ytd-about-channel-renderer\" hidden=\"[[!metadata.subscriberCountText]]\">\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <yt-icon icon=\"person_radar\" class=\"style-scope ytd-about-channel-renderer\"></yt-icon>\n        </td>\n        <td class=\"style-scope ytd-about-channel-renderer\">[[metadata.subscriberCountText]]</td>\n      </tr>\n      <tr class=\"description-item style-scope ytd-about-channel-renderer\" hidden=\"[[!metadata.videoCountText]]\">\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <yt-icon hidden=\"[[!metadata.videoCountText]]\" icon=\"my_videos\" class=\"style-scope ytd-about-channel-renderer\"></yt-icon>\n        </td>\n        <td class=\"style-scope ytd-about-channel-renderer\">[[metadata.videoCountText]]</td>\n      </tr>\n      <tr class=\"description-item style-scope ytd-about-channel-renderer\" hidden=\"[[!metadata.viewCountText]]\">\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <yt-icon hidden=\"[[!metadata.viewCountText]]\" icon=\"trending_up\" class=\"style-scope ytd-about-channel-renderer\"></yt-icon>\n        </td>\n        <td class=\"style-scope ytd-about-channel-renderer\">[[metadata.viewCountText]]</td>\n      </tr>\n      <tr class=\"description-item style-scope ytd-about-channel-renderer\" hidden=\"[[!metadata.joinedDateText]]\">\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <yt-icon hidden=\"[[!metadata.joinedDateText]]\" icon=\"info_outline\" class=\"style-scope ytd-about-channel-renderer\"></yt-icon>\n        </td>\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <yt-attributed-string data=\"[[metadata.joinedDateText]]\" class=\"style-scope ytd-about-channel-renderer\"></yt-attributed-string>\n        </td>\n      </tr>\n      <tr class=\"description-item style-scope ytd-about-channel-renderer\" hidden=\"[[!metadata.country]]\">\n        <td class=\"style-scope ytd-about-channel-renderer\">\n          <yt-icon hidden=\"[[!metadata.country]]\" icon=\"privacy_public\" class=\"style-scope ytd-about-channel-renderer\"></yt-icon>\n        </td>\n        <td class=\"style-scope ytd-about-channel-renderer\">[[metadata.country]]</td>\n      </tr>\n    </tbody></table>\n  </div>\n\n  <div id=\"button-container\" class=\"style-scope ytd-about-channel-renderer\">\n    <div id=\"share-channel\" class=\"button style-scope ytd-about-channel-renderer\"></div>\n    <div id=\"flagging-button\" class=\"button style-scope ytd-about-channel-renderer\"></div>\n  </div>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Eec = a
    }, {
        mode: 1
    });
    var Gec;
    var Hec = function() {
        var a = I.apply(this, arguments) || this;
        a.useModernCollectionsV2 = y("web_modern_collections_v2");
        return a
    };
    k(Hec, I);
    Hec.prototype.configureRendererStamper = function() {
        return {
            "data.menu": {
                id: "menu",
                mapping: {
                    menuRenderer: {
                        component: "ytd-menu-renderer"
                    }
                }
            },
            dismissedRenderer: {
                id: "dismissed",
                mapping: {
                    notificationTextRenderer: "ytd-notification-text-renderer"
                }
            }
        }
    }
    ;
    var dW = Hec;
    u([J(X.YtRendererBehavior), v("design:type", Object)], dW.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], dW.prototype, "ytRendererstamperBehavior", void 0);
    u([J(Zz), v("design:type", Object)], dW.prototype, "ytdDismissibleItemBehavior", void 0);
    u([P({
        reflectToAttribute: !0,
        value: function() {
            return y("kevlar_watch_feed_big_thumbs")
        }
    }), v("design:type", Boolean)], dW.prototype, "watchFeedBigThumbs", void 0);
    u([P({
        reflectToAttribute: !0,
        value: function() {
            return y("kevlar_watch_feed_big_thumbs") ? "9999" : "168"
        }
    }), v("design:type", String)], dW.prototype, "thumbnailWidth", void 0);
    u([P({
        reflectToAttribute: !0,
        value: function() {
            return y("kevlar_watch_feed_big_thumbs") ? "" : "94"
        }
    }), v("design:type", String)], dW.prototype, "customThumbnailSize", void 0);
    u([P(), v("design:type", Object)], dW.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], dW.prototype, "useModernCollectionsV2", void 0);
    dW = u([R({
        is: "ytd-compact-playlist-renderer",
        disableElementRegistration: !0
    })], dW);
    U(dW, "ytd-compact-playlist-renderer", function() {
        if (Gec !== void 0)
            return Gec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"dismissible\" class=\"style-scope ytd-compact-playlist-renderer\">\n  <ytd-playlist-thumbnail custom-thumbnail-size=\"[[customThumbnailSize]]\" data=\"[[data]]\" height=\"94\" watch-feed-thumbnail=\"[[watchFeedBigThumbs]]\" width=\"[[thumbnailWidth]]\" class=\"style-scope ytd-compact-playlist-renderer\">\n  </ytd-playlist-thumbnail>\n  <div class=\"details style-scope ytd-compact-playlist-renderer\">\n    <div class=\"metadata style-scope ytd-compact-playlist-renderer\">\n      <a id=\"title\" class=\"yt-simple-endpoint style-scope ytd-compact-playlist-renderer\" href$=\"[[computeHref_(data.navigationEndpoint)]]\" data=\"[[data.navigationEndpoint]]\">\n        <h3 class=\"style-scope ytd-compact-playlist-renderer\">\n          <ytd-badge-supported-renderer top-standalone-badge=\"[[data.topStandaloneBadge]]\" class=\"style-scope ytd-compact-playlist-renderer\">\n          </ytd-badge-supported-renderer>\n          <span id=\"video-title\" title$=\"[[getSimpleString(data.title)]]\" aria-label$=\"[[data.title.accessibility.accessibilityData.label]]\" class=\"style-scope ytd-compact-playlist-renderer\">\n            [[getSimpleString(data.title)]]\n          </span>\n        </h3>\n        <div class=\"secondary-metadata style-scope ytd-compact-playlist-renderer\">\n          <ytd-video-meta-block class=\"compact style-scope ytd-compact-playlist-renderer\" data=\"[[data]]\" no-endpoints=\"\" watch-feed-big-thumbs=\"[[watchFeedBigThumbs]]\">\n          </ytd-video-meta-block>\n          <ytd-badge-supported-renderer id=\"badges\" badges=\"[[data.badges]]\" disable-upgrade$=\"[[!data.badges]]\" hidden=\"[[!data.badges]]\" class=\"style-scope ytd-compact-playlist-renderer\">\n          </ytd-badge-supported-renderer>\n        </div>\n      </a>\n    </div>\n    <div id=\"menu\" class=\"style-scope ytd-compact-playlist-renderer\"></div>\n  </div>\n</div>\n<div id=\"dismissed\" class=\"style-scope ytd-compact-playlist-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Gec = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j033") ? 1 : 2
    });
    var Iec;
    var eW = function() {
        var a = I.apply(this, arguments) || this;
        a.collections = y("web_modern_collections_v2");
        return a
    };
    k(eW, I);
    eW.prototype.configureRendererStamper = function() {
        return {
            "data.menu": {
                id: "menu",
                mapping: {
                    menuRenderer: {
                        component: "ytd-menu-renderer"
                    }
                }
            },
            dismissedRenderer: {
                id: "dismissed",
                mapping: {
                    notificationTextRenderer: "ytd-notification-text-renderer"
                }
            }
        }
    }
    ;
    eW.prototype.attached = function() {
        this.hostElement.classList.add("use-ellipsis")
    }
    ;
    eW.prototype.onYtNavigate = function(a, b) {
        var c = this;
        if (b.endpoint === this.data.navigationEndpoint && this.get("endpoint.watchEndpoint.continuePlayback", b)) {
            var d = this.get("watchEndpoint.videoId", b.endpoint)
              , e = Ev(this.hostElement, "yt-get-current-video-id-action")[0];
            y("kevlar_mix_handle_first_endpoint_different") && d && e && d !== e || (a.stopPropagation(),
            zA().getPlayerPromise().then(function(h) {
                if (h.getPlayerState() === 0 && c.data.secondaryNavigationEndpoint)
                    var l = c.data.secondaryNavigationEndpoint;
                else {
                    l = Object.assign({}, b.endpoint);
                    var m = A(l.commandMetadata, pq);
                    m && (h = Math.floor(h.getCurrentTime()),
                    m.url = pd(m.url, {
                        t: h
                    }),
                    !y("kevlar_add_start_time_to_mix_endpoint_killswitch") && (m = A(l, qq))) && (m.startTimeSeconds = h)
                }
                zv(c.hostElement, "yt-navigate", {
                    endpoint: l
                })
            }))
        }
    }
    ;
    da.Object.defineProperties(eW.prototype, {
        collectionStack: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                var a, b, c, d, e, h;
                return {
                    thumbnailSize: "medium",
                    doubleStack: !1,
                    sampledThumbnailColor: (a = this.data) == null ? void 0 : (b = a.thumbnail) == null ? void 0 : b.sampledThumbnailColor,
                    vibrantColorPalette: (c = this.data) == null ? void 0 : (d = c.thumbnail) == null ? void 0 : d.vibrantColorPalette,
                    darkColorPalette: (e = this.data) == null ? void 0 : (h = e.thumbnail) == null ? void 0 : h.darkColorPalette,
                    experimentEnabled: this.collections
                }
            }
        }
    });
    var fW = eW;
    fW.prototype.onYtNavigate = fW.prototype.onYtNavigate;
    u([J(X.YtRendererBehavior), v("design:type", Object)], fW.prototype, "ytRendererBehavior", void 0);
    u([J(KA.YtEndpointBehavior), v("design:type", Object)], fW.prototype, "ytEndpointBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], fW.prototype, "ytRendererstamperBehavior", void 0);
    u([J(Zz), v("design:type", Object)], fW.prototype, "ytdDismissibleItemBehavior", void 0);
    u([J(eA), v("design:type", Object)], fW.prototype, "ytdLockupBehavior", void 0);
    u([P({
        reflectToAttribute: !0,
        value: function() {
            return y("kevlar_watch_feed_big_thumbs")
        }
    }), v("design:type", Boolean)], fW.prototype, "watchFeedBigThumbs", void 0);
    u([P({
        reflectToAttribute: !0,
        value: function() {
            return y("kevlar_watch_feed_big_thumbs") ? "9999" : "168"
        }
    }), v("design:type", String)], fW.prototype, "thumbnailWidth", void 0);
    u([P(), v("design:type", Object)], fW.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], fW.prototype, "collections", void 0);
    u([L("data", "collections"), v("design:type", Object), v("design:paramtypes", [])], fW.prototype, "collectionStack", null);
    u([M("yt-navigate"), v("design:type", Function), v("design:paramtypes", [CustomEvent, Object]), v("design:returntype")], fW.prototype, "onYtNavigate", null);
    fW = u([R({
        is: "ytd-compact-radio-renderer",
        disableElementRegistration: !0
    })], fW);
    U(fW, "ytd-compact-radio-renderer", function() {
        if (Iec !== void 0)
            return Iec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"dismissible\" class=\"style-scope ytd-compact-radio-renderer\">\n  <div class=\"modern-collection-parent style-scope ytd-compact-radio-renderer\">\n    <yt-collections-stack data=\"[[collectionStack]]\" class=\"style-scope ytd-compact-radio-renderer\"></yt-collections-stack>\n    <ytd-thumbnail data=\"[[data]]\" height=\"94\" hovered=\"[[lockupIsHovered]]\" use-hovered-property=\"\" watch-feed-thumbnail=\"[[watchFeedBigThumbs]]\" width=\"[[thumbnailWidth]]\" class=\"style-scope ytd-compact-radio-renderer\">\n    </ytd-thumbnail>\n  </div>\n  <div class=\"details style-scope ytd-compact-radio-renderer\">\n    <div class=\"metadata style-scope ytd-compact-radio-renderer\">\n      <a id=\"title\" class=\"yt-simple-endpoint style-scope ytd-compact-radio-renderer\" href$=\"[[computeHref_(data.navigationEndpoint)]]\" data=\"[[data.navigationEndpoint]]\">\n        <h3 class=\"style-scope ytd-compact-radio-renderer\">\n          <ytd-badge-supported-renderer top-standalone-badge=\"[[data.topStandaloneBadge]]\" class=\"style-scope ytd-compact-radio-renderer\">\n          </ytd-badge-supported-renderer>\n          <span id=\"video-title\" title$=\"[[getSimpleString(data.title)]]\" aria-label$=\"[[data.title.accessibility.accessibilityData.label]]\" class=\"style-scope ytd-compact-radio-renderer\">\n            [[getSimpleString(data.title)]]\n          </span>\n        </h3>\n        <ytd-video-meta-block class=\"compact style-scope ytd-compact-radio-renderer\" data=\"[[data]]\" no-endpoints=\"\" radio-meta=\"\">\n        </ytd-video-meta-block>\n      </a>\n    </div>\n    <div id=\"menu\" class=\"style-scope ytd-compact-radio-renderer\"></div>\n  </div>\n</div>\n<div id=\"dismissed\" class=\"style-scope ytd-compact-radio-renderer\"></div>\n<yt-interaction id=\"interaction\" class=\"extended style-scope ytd-compact-radio-renderer\"></yt-interaction>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Iec = a
    }, {
        mode: 1
    });
    var Jec;
    var Kec = function() {
        return I.apply(this, arguments) || this
    };
    k(Kec, I);
    Kec.prototype.configureRendererStamper = function() {
        return {
            "data.button": {
                id: "action-button",
                mapping: {
                    buttonRenderer: {
                        component: "ytd-button-renderer",
                        params: {
                            alignByText: !1
                        }
                    }
                }
            }
        }
    }
    ;
    Kec.prototype.computeRendererStyle = function(a) {
        return a.style ? a.style.split("STYLE_")[1].replace(/_/g, "-").toLowerCase() : ""
    }
    ;
    var gW = Kec;
    u([P(), v("design:type", Object)], gW.prototype, "data", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], gW.prototype, "ytRendererstamperBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], gW.prototype, "rendererBehavior", void 0);
    u([P({
        computed: "computeRendererStyle(data)",
        reflectToAttribute: !0
    }), v("design:type", String)], gW.prototype, "rendererStyle", void 0);
    gW = u([R({
        is: "ytd-compact-text-promo-renderer",
        disableElementRegistration: !0
    })], gW);
    U(gW, "ytd-compact-text-promo-renderer", function() {
        if (Jec !== void 0)
            return Jec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><ytd-badge-supported-renderer id=\"featured-badge\" disable-upgrade$=\"[[!data.badge]]\" hidden=\"[[!data.badge]]\" top-standalone-badge=\"[[data.badge]]\" class=\"style-scope ytd-compact-text-promo-renderer\">\n</ytd-badge-supported-renderer>\n<yt-formatted-string class=\"title style-scope ytd-compact-text-promo-renderer\" text=\"[[data.title]]\">\n</yt-formatted-string>\n<yt-formatted-string class=\"subtitle style-scope ytd-compact-text-promo-renderer\" force-default-style=\"\" text=\"[[data.subTitle]]\">\n</yt-formatted-string>\n<div id=\"action-button\" class=\"style-scope ytd-compact-text-promo-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Jec = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j033") ? 1 : 2
    });
    var Lec;
    YB("itemSectionRenderer", "counterfactualRenderer", "ytd-counterfactual-renderer");
    var Mec = function() {
        return I.apply(this, arguments) || this
    };
    k(Mec, I);
    var hW = Mec;
    u([J(X.YtRendererBehavior), v("design:type", Object)], hW.prototype, "ytRendererBehavior", void 0);
    u([P(), v("design:type", Object)], hW.prototype, "data", void 0);
    hW = u([R({
        is: "ytd-counterfactual-renderer",
        disableElementRegistration: !0
    })], hW);
    U(hW, "ytd-counterfactual-renderer", function() {
        if (Lec !== void 0)
            return Lec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady-->");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Lec = a
    }, {
        mode: 1
    });
    var Nec;
    YB("sharingItemSection", "itemSectionHeaderRenderer", "ytd-item-section-header-renderer");
    var Oec = function() {
        var a = I.apply(this, arguments) || this;
        a.modernTypography = y("web_modern_typography");
        return a
    };
    k(Oec, I);
    Oec.prototype.configureRendererStamper = function() {
        return {
            "data.buttons": {
                id: "buttons",
                mapping: {
                    buttonRenderer: "ytd-button-renderer"
                }
            }
        }
    }
    ;
    Oec.prototype.computeStyle = function(a) {
        return a ? a : ""
    }
    ;
    var iW = Oec;
    u([J(X.YtRendererBehavior), v("design:type", Object)], iW.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], iW.prototype, "ytRendererstamperBehavior", void 0);
    u([P(), v("design:type", Object)], iW.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0,
        computed: "computeStyle(data.titleStyle)"
    }), v("design:type", String)], iW.prototype, "titleStyle", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], iW.prototype, "modernTypography", void 0);
    iW = u([R({
        is: "ytd-item-section-header-renderer",
        disableElementRegistration: !0
    })], iW);
    U(iW, "ytd-item-section-header-renderer", function() {
        if (Nec !== void 0)
            return Nec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"header\" class=\"style-scope ytd-item-section-header-renderer\">\n  <div id=\"title\" class=\"style-scope ytd-item-section-header-renderer\">[[getSimpleString(data.title)]]</div>\n  <yt-formatted-string id=\"subtitle\" text=\"[[data.subtitle]]\" class=\"style-scope ytd-item-section-header-renderer\"></yt-formatted-string>\n</div>\n<div id=\"buttons\" class=\"style-scope ytd-item-section-header-renderer\"></div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Nec = a
    }, {
        mode: 1
    });
    var Pec;
    var Qec;
    var Rec = function() {
        return I.apply(this, arguments) || this
    };
    k(Rec, I);
    var jW = Rec;
    u([P(), v("design:type", Object)], jW.prototype, "data", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], jW.prototype, "rendererBehavior", void 0);
    jW = u([R({
        is: "ytd-premium-browse-footer-renderer",
        disableElementRegistration: !0
    })], jW);
    U(jW, "ytd-premium-browse-footer-renderer", function() {
        if (Qec !== void 0)
            return Qec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><yt-formatted-string class=\"title style-scope ytd-premium-browse-footer-renderer\" text=\"[[data.title]]\">\n</yt-formatted-string>\n<yt-formatted-string class=\"subtitle style-scope ytd-premium-browse-footer-renderer\" text=\"[[data.subtitle]]\">\n</yt-formatted-string>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Qec = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j022") ? 1 : 2
    });
    var Sec;
    var Tec = RD({
        buttonViewModel: QB(MC)
    })
      , Uec = RD({
        toggleableImageButtonViewModel: function(a) {
            var b = a.buttonIndex
              , c = a.selectedIndex
              , d = a.data
              , e = d.text
              , h = d.backgroundColorDarkMode;
            d = d.backgroundColor;
            var l = Mr(function() {
                a.onSelect(a.data.onSubmitCommand)
            });
            Mr(function() {
                return !0
            });
            var m = Zqb()
              , p = {
                borderRadius: "16px"
            }
              , q = b === c;
            b = c !== -1 && !q;
            var r = null;
            d && h && (r = "background: linear-gradient(180deg," + jy(h, "1") + "," + jy(d, "1") + ") border-box;");
            return F("yt-toggleable-image-button-view-model", {
                class: lC("toggleable-image-button-view-model-wiz", ""),
                style: "opacity:" + (b ? .4 : 1),
                tabindex: 0,
                "aria-label": e == null ? void 0 : e.content,
                "aria-pressed": q,
                role: "button",
                "on:keydown": m,
                "on:click": l
            }, F($p, null, function() {
                if (a.data.logo) {
                    var x;
                    OB(a.data.logo, Object.assign({}, {
                        alt: (x = e == null ? void 0 : e.content) != null ? x : "",
                        className: lC("toggleable-image-button-view-model-wiz__image", r && "toggleable-image-button-view-model-wiz__circular-radius", q && r ? "toggleable-image-button-view-model-wiz__gradient-ring" : "")
                    }, q && r && {
                        style$: r
                    }))
                }
                rC(p)
            }), F("p", {
                class: lC("toggleable-image-button-view-model-wiz__label", q ? "toggleable-image-button-view-model-wiz__bold-text" : void 0)
            }, TD(e)))
        }
    });
    eC(function(a) {
        var b = g(EC({
            index: -1,
            command: {}
        }))
          , c = b.next().value
          , d = b.next().value;
        b = c.index === -1 ? "disabled" : "active";
        var e, h = A((e = a.data) == null ? void 0 : e.submitButton, cv);
        h && (h.state = b === "disabled" ? "BUTTON_VIEW_MODEL_STATE_DISABLED" : "BUTTON_VIEW_MODEL_STATE_ACTIVE");
        var l;
        return F("yt-nudge-form-view-model", {
            class: "nudge-form-view-model-wiz"
        }, F("div", {
            class: "nudge-form-view-model-wiz__form-options"
        }, ((l = a.data) == null ? void 0 : l.inputFields) && a.data.inputFields.map(function(m, p) {
            return Uec(m, {
                toggleableImageButtonViewModel: {
                    buttonIndex: p,
                    selectedIndex: c.index,
                    onSelect: function(q) {
                        d({
                            index: p,
                            command: q
                        })
                    }
                }
            })
        })), TD(a.data.subtitle, {
            className: "nudge-form-view-model-wiz__subtitle"
        }), F("div", {
            class: "nudge-form-view-model-wiz__submit"
        }, Tec(a.data.submitButton, {
            buttonViewModel: {
                config: {
                    onclick: function() {
                        HB(c.command)
                    }
                }
            }
        })))
    }, "yt-nudge-form-view-model", {
        propNames: ["data"]
    });
    var Vec = function() {
        var a = I.apply(this, arguments) || this;
        a.roundedContainer = !0;
        a.buttonUpdate = y("web_modern_buttons");
        a.isDarkMode = !1;
        a.actionMap = {
            "yt-dark-mode-toggled-action": "handleDarkModeToggledAction"
        };
        return a
    };
    k(Vec, I);
    f = Vec.prototype;
    f.computeNudgeStyle = function(a) {
        return a ? "modernized-nudge" : ""
    }
    ;
    f.handleDarkModeToggledAction = function(a) {
        this.isDarkMode = a
    }
    ;
    f.attached = function() {
        this.handleDarkModeToggledAction(document.documentElement.hasAttribute("dark"))
    }
    ;
    f.configureRendererStamper = function() {
        return {
            "data.contents": {
                id: "contents",
                mapping: {
                    chipCloudChipRenderer: "yt-chip-cloud-chip-renderer",
                    nudgeFormViewModel: "yt-nudge-form-view-model"
                }
            },
            "data.primaryButton": {
                id: "primary-button",
                mapping: {
                    buttonRenderer: "ytd-button-renderer"
                }
            },
            "data.secondaryButton": {
                id: "secondary-button",
                mapping: {
                    buttonRenderer: "ytd-button-renderer"
                }
            },
            "data.dismissButton": {
                id: "dismiss-button",
                mapping: {
                    buttonRenderer: "ytd-button-renderer"
                }
            },
            dismissedRenderer: {
                id: "dismissed-content",
                mapping: {
                    notificationTextRenderer: "ytd-notification-text-renderer",
                    notificationMultiActionRenderer: "ytd-notification-multi-action-renderer"
                }
            }
        }
    }
    ;
    f.computeIsHorizontalButtons = function(a) {
        return a ? !!a.applyModernizedStyle && !!a.enableHorizontalButtons && !!a.secondaryButton : !1
    }
    ;
    da.Object.defineProperties(Vec.prototype, {
        isHidden: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return !!this.ytdDismissibleItemBehavior.isHideEnclosingAction
            }
        },
        trimStyle: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                var a;
                return ((a = this.data) == null ? void 0 : a.trimStyle) === "FEED_NUDGE_TRIM_STYLE_NO_TRIM" ? "no-trim" : "gradient-trim-1"
            }
        },
        backgroundStyle: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                var a, b;
                return (b = (a = this.data) == null ? void 0 : a.backgroundStyle) != null ? b : "FEED_NUDGE_BACKGROUND_STYLE_UNKNOWN"
            }
        },
        contentsLocation: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                var a, b;
                return (b = (a = this.data) == null ? void 0 : a.contentsLocation) != null ? b : "FEED_NUDGE_CONTENTS_LOCATION_UNKNOWN"
            }
        },
        noShadow: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                var a;
                return !((a = this.data) == null || !a.disableDropShadow)
            }
        },
        noIcon: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                var a;
                return !((a = this.data) == null ? 0 : a.lightIconImage)
            }
        }
    });
    var kW = Vec;
    u([J(X.YtRendererBehavior), v("design:type", Object)], kW.prototype, "ytRendererBehavior", void 0);
    u([J(fC.YtRendererstamperBehavior), v("design:type", Object)], kW.prototype, "ytRendererstamperBehavior", void 0);
    u([J(Zz), v("design:type", Object)], kW.prototype, "ytdDismissibleItemBehavior", void 0);
    u([J(EA.YtActionHandlerBehavior), v("design:type", Object)], kW.prototype, "actionHandlerBehavior", void 0);
    u([P({
        reflectToAttribute: !0
    }), L("isHideEnclosingAction"), v("design:type", Boolean), v("design:paramtypes", [])], kW.prototype, "isHidden", null);
    u([P(), v("design:type", Object)], kW.prototype, "data", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], kW.prototype, "roundedContainer", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], kW.prototype, "buttonUpdate", void 0);
    u([P({
        reflectToAttribute: !0,
        computed: "computeNudgeStyle(data.applyModernizedStyle)"
    }), v("design:type", String)], kW.prototype, "nudgeStyle", void 0);
    u([P({
        reflectToAttribute: !0
    }), L("data.trimStyle"), v("design:type", String), v("design:paramtypes", [])], kW.prototype, "trimStyle", null);
    u([P({
        reflectToAttribute: !0
    }), L("data.backgroundStyle"), v("design:type", String), v("design:paramtypes", [])], kW.prototype, "backgroundStyle", null);
    u([P({
        reflectToAttribute: !0
    }), L("data.contentsLocation"), v("design:type", String), v("design:paramtypes", [])], kW.prototype, "contentsLocation", null);
    u([P({
        reflectToAttribute: !0
    }), L("data.disableDropShadow"), v("design:type", Boolean), v("design:paramtypes", [])], kW.prototype, "noShadow", null);
    u([P({
        reflectToAttribute: !0
    }), L("data.lightIconImage"), v("design:type", Boolean), v("design:paramtypes", [])], kW.prototype, "noIcon", null);
    u([P({
        reflectToAttribute: !0,
        computed: "computeIsHorizontalButtons(data)"
    }), v("design:type", Boolean)], kW.prototype, "isHorizontalButtons", void 0);
    u([P({
        reflectToAttribute: !0,
        value: !1
    }), v("design:type", Object)], kW.prototype, "isDarkMode", void 0);
    kW = u([R({
        is: "ytd-feed-nudge-renderer",
        disableElementRegistration: !0
    })], kW);
    U(kW, "ytd-feed-nudge-renderer", function() {
        if (Sec !== void 0)
            return Sec;
        var a = document.createElement("template");
        G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"dismissible\" class=\"style-scope ytd-feed-nudge-renderer\">\n  <div id=\"dismiss-button\" class=\"style-scope ytd-feed-nudge-renderer\"></div>\n  <div id=\"content-wrapper\" class=\"style-scope ytd-feed-nudge-renderer\">\n    <div id=\"header-container\" class=\"style-scope ytd-feed-nudge-renderer\">\n      <div id=\"image-container\" hidden=\"[[!data.lightIconImage]]\" class=\"style-scope ytd-feed-nudge-renderer\">\n        <yt-img-shadow id=\"nudge-image\" height=\"32\" thumbnail=\"[[data.lightIconImage]]\" class=\"style-scope ytd-feed-nudge-renderer\">\n        </yt-img-shadow>\n      </div>\n    </div>\n    <div id=\"text-container\" class=\"style-scope ytd-feed-nudge-renderer\">\n      <div id=\"title-container\" class=\"style-scope ytd-feed-nudge-renderer\">\n        <yt-formatted-string id=\"title\" text=\"[[data.title]]\" class=\"style-scope ytd-feed-nudge-renderer\"></yt-formatted-string>\n      </div>\n      <div id=\"subtitle-container\" class=\"style-scope ytd-feed-nudge-renderer\">\n        <yt-formatted-string id=\"subtitle\" split-lines=\"\" text=\"[[data.subtitle]]\" class=\"style-scope ytd-feed-nudge-renderer\"></yt-formatted-string>\n      </div>\n    </div>\n    <div id=\"contents\" hidden=\"[[!data.contents]]\" class=\"style-scope ytd-feed-nudge-renderer\"></div>\n    <div id=\"button-container\" hidden=\"[[!data.primaryButton]]\" class=\"style-scope ytd-feed-nudge-renderer\">\n      <div id=\"primary-button\" class=\"style-scope ytd-feed-nudge-renderer\"></div>\n      <div id=\"secondary-button\" class=\"style-scope ytd-feed-nudge-renderer\"></div>\n    </div>\n  </div>\n</div>\n<div id=\"dismissed\" class=\"style-scope ytd-feed-nudge-renderer\">\n  <div id=\"dismissed-content\" class=\"style-scope ytd-feed-nudge-renderer\"></div>\n</div>\n");
        a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
        return Sec = a
    }, {
        mode: Sz("kevlar_poly_si_batch_j022") ? 1 : 2
    });
    var Wec;
    var Xec = function() {
        var a = I.apply(this, arguments) || this;
        a.removeMaxWidth = !0;
        return a
    };
    k(Xec, I);
    f = Xec.prototype;
    f.configureRendererStamper = function() {
        return {
            "data.menu": $C,
            dismissedRenderer: {
                id: "dismissed-content",
                mapping: {
                    notificationMultiActionRenderer: "ytd-notification-multi-action-renderer",
                    notificationTextRenderer: "ytd-notification-text-renderer"
                }
            }
        }
    }
    ;
    f.onDataChanged = function() {
        this.updateInlinePreviewHoverListeners()
    }
    ;
    f.attached = function() {
        this.updateInlinePreviewHoverListeners()
    }
    ;
    f.detached = function() {
        this.clearInlinePreviewHoverListeners()
    }
    ;
    f.updateInlinePreviewHoverListeners = function() {
        if (this.isShort || this.isSlimShort)
            this.clearInlinePreviewHoverListeners(),
            this.JSC$15117_inlinePreviewHoverListener = eE({
                mediaRenderer: this,
                lockupElement: this.JSC$15117_dismissibleMedia,
                thumbnailElement: this.thumbnail,
                videoPreviewOpts: Rrb
            })
    }
    ;
    f.clearInlinePreviewHoverListeners = function() {
        var a;
        (a = this.JSC$15117_inlinePreviewHoverListener) == null || hE(a)
    }
    ;
    f.onRendererTap = function() {
        var a, b, c = (a = this.data) == null ? void 0 : (b = a.serviceEndpoints) == null ? void 0 : b[0];
        A(c, Lu) && this.componentBehavior.resolveCommand(c)
    }
    ;
    f.onDetailsClick = function(a) {

      },
        handleYPCGetCartEndpointWithPrefetch_: function(a, b) {
            var c = this;
            Lq("ttcr", void 0, "commerce_transaction");
            b = b.ypcGetCartEndpoint;
            var d = b.prefetchConfig.ypcGetCartPrefetchResponseDataConfig
              , e = d.encryptedPurchaseParams
              , h = d.serializedTransactionFlowLoggingParams
              , l = d.serializedPaymentsClientParams
              , m = this.createGetCartResponseFromParams_(d, b.offerParams, h);
            this.changeButtonState(a, !0);
            $i(this.openWalletDialog(a, e, d.ypcLogWalletAnalyticDataEndpoint, h, function() {
                c.changeButtonState(a, !1)
            }, function() {
                c.changeButtonState(a, !1)
            }, l).then(function(p) {
                return c.handleBuyFlowCompleteCallback_(a, m, p)
            }, function() {
                return c.handleOnLoadError(m)
            }).then(function(p) {
                return void c.handlePostPurchaseSuccess_(a, m, p)
            }, function(p) {
                return void c.handlePostPurchaseError_(p)
            }), function() {
                c.changeButtonState(a, !1);
                a instanceof Element && zv(a, "yt-commerce-action-done")
            })
        },
        createGetCartResponseFromParams_: function(a, b, c) {
            var d = a.completeTransactionEndpoint
              , e = a.handleTransactionEndpoint;
            b = {
                data: {
                    offerParams: window.btoa(b),
                    serializedTransactionFlowLoggingParams: c
                }
            };
            e ? b.data.handleTransactionEndpoint = e : b.data.completeTransactionEndpoint = d;
            a.onCartDismissCommand && (b.data.onCartDismissCommand = a.onCartDismissCommand);
            return b
        },
        onGetCartServiceRequestCompleted_: function(a, b) {
            var c = this
              , d = a.target;
            if (b && b.data && b.data.messageRenderer)
                lE(this.hostElement),
                this.handleMessageRenderer_(b.data.messageRenderer),
                this.changeButtonState(d, !1);
            else {
                var e = this.get("data.encryptedPurchaseParams", b)
                  , h = this.get("data.upgradeDialogRenderer.ypcUpgradeDialogRenderer", b)
                  , l = this.get("data.ypcLogWalletAnalyticDataEndpoint", b)
                  , m = this.get("data.serializedPaymentsClientParams", b)
                  , p = this.getLoggingParams_(b);
                if (p || e || h)
                    a.stopPropagation(),
                    Lq("ttcr", void 0, "commerce_transaction"),
                    e || lE(this.hostElement),
                    this.changeButtonState(d, !1),
                    h ? Dv(this.hostElement, "yt-open-popup-action", [{
                        openPopupAction: {
                            popupType: ak("openPopupConfig").popupTypeMap.ypcUpgradeDialogRenderer,
                            popup: {
                                ypcUpgradeDialogRenderer: h
                            }
                        }
                    }, this]) : e && (this.changeButtonState(d, !0),
                    a = null,
                    a = this.openWalletDialog(d, e, l, p, function() {
                        lE(c.hostElement);
                        c.changeButtonState(d, !1)
                    }, function() {
                        lE(c.hostElement);
                        c.changeButtonState(d, !1)
                    }, m),
                    $i(a.then(function(q) {
                        return c.handleBuyFlowCompleteCallback_(d, b, q)
                    }, function() {
                        return c.handleOnLoadError(b)
                    }).then(function(q) {
                        return c.handlePostPurchaseSuccess_(d, b, q)
                    }, function(q) {
                        return c.handlePostPurchaseError_(q)
                    }), function() {
                        c.changeButtonState(d, !1);
                        zv(d, "yt-commerce-action-done")
                    }))
            }
        },
        onServiceRequestSent_: function(a, b) {
            b && b.endpoint && b.endpoint.ypcGetCartEndpoint && !b.endpoint.ypcGetCartEndpoint.prefetchConfig && (this.get("commandLifeCycleConfig.onStartCommand", b.endpoint.ypcGetCartEndpoint) && Gv(this.hostElement, [this.get("commandLifeCycleConfig.onStartCommand", b.endpoint.ypcGetCartEndpoint)], a.target),
            kE(this.hostElement),
            this.changeButtonState(a.target, !0))
        },
        onServiceRequestError_: function(a, b) {
            if (b && b.params && b.params.length) {
                b = g(b.params);
                for (var c = b.next(); !c.done; c = b.next())
                    if ((c = c.value) && c.ypcGetCartEndpoint) {
                        this.get("commandLifeCycleConfig.onFailureCommand", c.ypcGetCartEndpoint) && Gv(this.hostElement, [this.get("commandLifeCycleConfig.onFailureCommand", c.ypcGetCartEndpoint)], a.target);
                        lE(this.hostElement);
                        this.changeButtonState(a.target, !1);
                        break
                    }
            }
        },
        handleBuyFlowCompleteCallback_: function(a, b, c) {
            var d = c.integratorData;
            return d == null || d === "" || c.error != null ? (d = this.getLoggingParams_(b),
            String(c.error) === "-1" ? (b.data.onCartDismissCommand && Gv(this.hostElement, [b.data.onCartDismissCommand], a),
            Xi(new i6("TRANSACTION_ERROR_TYPE_YPC_BUYFLOW_COMPLETE_FAILURE",d,!0))) : Xi(new i6("TRANSACTION_ERROR_TYPE_YPC_BUYFLOW_COMPLETE_FAILURE",d))) : b.data.handleTransactionEndpoint ? M2c(this.hostElement, b.data.handleTransactionEndpoint, {
                payments_payload: d,
                funds_guarantee_callback_client_data: c.integratorClientCallbackData
            }) : this.completeTransaction(b, c)
        },
        handlePostPurchaseSuccess_: function(a, b, c) {
            b = c.data;
            var d = !1, e, h;
            if (b && ((e = b.command) == null ? 0 : (h = e.commandExecutorCommand) == null ? 0 : h.commands)) {
                var l, m;
                e = (l = b.command) == null ? void 0 : (m = l.commandExecutorCommand) == null ? void 0 : m.commands;
                for (l = 0; l < e.length; l++)
                    if (A(e[l], zXa)) {
                        d = !0;
                        break
                    }
            }
            d || (b && b.gtmDatas && b.gtmDatas.length ? Cy(b.gtmDatas[0]) : Cy("{\"event\": \"purchased\", \"purchaseStatus\": \"success\"}"));
            c.data && c.data.actions && (b = ERc(c.data.actions),
            c = FRc(c.data.actions),
            b.length && Hv(this.hostElement, b),
            c.length && Gv(this.hostElement, c, a))
        },
        handlePostPurchaseError_: function(a) {
            a && a.payload && a.payload.isUserDismiss || Fm(Error("Error occurred during buyflow."))
        },
        handleOnLoadError: function(a) {
            a = this.getLoggingParams_(a);
            return Xi(new i6("TRANSACTION_ERROR_TYPE_LOAD_FAILURE",a))
        },
        getLoggingParams_: function(a) {
            return this.get("data.serializedTransactionFlowLoggingParams", a)
        },
        handleMessageRenderer_: function(a) {
            var b = Fr(a, "renderer")
              , c = ak("openPopupConfig");
            b === "confirmDialogRenderer" && c && Dv(this.hostElement, "yt-open-popup-action", [{
                openPopupAction: {
                    popupType: c.popupTypeMap[b],
                    popup: a
                }
            }, this])
        },
        handleYPCFixInstrumentEndpoint_: function(a, b) {
            var c = this
              , d = b.ypcFixInstrumentEndpoint;
            b = d.encryptedFixInstrumentParameters;
            this.logFixFopEvent_(d, "FIX_FOP_EVENT_TYPE_START");
            this.changeButtonState(a, !0);
            this.openFixFlowDialog(b, function(e, h) {
                c.onFixFlowCompleteCallback_(d, e, h)
            }, function() {
                return c.changeButtonState(a, !1)
            }, function() {
                c.changeButtonState(a, !1);
                c.logFixFopEvent_(d, "FIX_FOP_EVENT_TYPE_FAILURE", "FIX_FOP_ERROR_TYPE_LOAD_FAILURE")
            })
        },
        onFixFlowCompleteCallback_: function(a, b, c) {
            var d = Pa("payments.business.integration.scenario.FixInstrument");
            if (b == d.IntegratorCallbackType.ON_COMPLETE) {
                b = "FIX_FOP_EVENT_TYPE_CANCEL";
                var e = null;
                c.error != null ? c.error != d.OnCompleteCallbackError.USER_CANCELLED && (Gv(this.hostElement, [a.errorAction], this.hostElement),
                b = "FIX_FOP_EVENT_TYPE_FAILURE",
                e = "FIX_FOP_ERROR_TYPE_UNSPECIFIED") : (Gv(this.hostElement, [a.successAction], this.hostElement),
                b = "FIX_FOP_EVENT_TYPE_SUCCESS");
                Gv(this.hostElement, [a.onFinishAction], this.hostElement);
                this.logFixFopEvent_(a, b, e)
            }
        },
        logFixFopEvent_: function(a, b, c) {
            (a = a.serializedFixFopLoggingParams) ? (b = {
                eventType: b,
                serializedFixFopLoggingParams: a
            },
            c != null && (b.errorType = c),
            Xk("fixFopFlow", b),
            Em()) : Fm(Error("Fix Fop Logging params not provided."))
        },
        changeButtonState: function(a, b) {
            y("enable_ypc_spinners") && a && (a.is === "yt-button-renderer" || a.is === "ytd-button-renderer") && (a.disabled = b)
        }
    }];
    var a3c = function(a) {
        this.JSC$27337_clientRoot = a;
        this.feedbackCollectorActionMap = {
            "yt-help-dialog-requested": V2c,
            "yt-feedback-dialog-requested": W2c,
            "yt-signal-action-help": X2c,
            "yt-signal-action-send-feedback": Y2c,
            "yt-send-feedback-action": Z2c,
            "yt-user-feedback-endpoint": $2c
        };
        Ir(Gr.getInstance(), this.feedbackCollectorActionMap, this.JSC$27337_clientRoot)
    }, b3c;
    function W2c(a) {
        a = a === void 0 ? {} : a;
        sm().resolve(ysb).showFeedbackDialog(a.customProductData, a.feedbackContent, a.onFeedbackSubmitted, a.bucket)
    }
    function V2c(a) {
        a = a === void 0 ? {} : a;
        sm().resolve(ysb).showHelpDialog(a.helpContext, a.articleId, a.productData)
    }
    function X2c() {
        V2c()
    }
    function Y2c() {
        W2c()
    }
    function Z2c(a, b, c) {
        var d, e, h, l, m, p, q;
        return t(function(r) {
            switch (r.nextAddress) {
            case 1:
                d = A(a, qNc);
                if ((e = d) == null ? 0 : e.productId) {
                    p = {
                        productId: d.productId,
                        bucket: d.bucket,
                        enableAnonymousFeedback: (m = d.enableAnonymousFeedback) != null ? m : !0,
                        allowNonLoggedInFeedback: !0
                    };
                    q = {
                        feedbackChoice: c.feedbackChoice
                    };
                    if (!y("web_collect_offline_state")) {
                        r.jumpTo(8);
                        break
                    }
                    va(r, 9);
                    return n(r, Xyb(q), 11)
                }
                l = {
                    bucket: (h = d) == null ? void 0 : h.bucket
                };
                if (!y("web_collect_offline_state")) {
                    r.jumpTo(4);
                    break
                }
                l.customProductData = {};
                va(r, 5);
                return n(r, Xyb(l.customProductData), 7);
            case 7:
                ya(r, 4);
                break;
            case 5:
                za(r);
            case 4:
                W2c(l);
                r.jumpTo(0);
                break;
            case 11:
                ya(r, 8);
                break;
            case 9:
                za(r);
            case 8:
                msb(q),
                lsb("GFEEDBACK", q),
                d.productId === "5295751" && (q.client_attestation = Number(ak("CATSTAT", 0))),
                d.productId === "5295751" && (q.client_time = Date.now() / 1E3 / 3600),
                d.productId === "5295751" && (q.original_playback_id = h5a || ""),
                DSa(p, q),
                ta(r);
            }
        })
    }
    function $2c(a) {
        if (a = A(a, WVa)) {
            var b = {
                bucket: a.bucketIdentifier
            };
            a.additionalDatas && (b.customProductData = {},
            a.additionalDatas.forEach(function(c) {
                if (c = c.userFeedbackEndpointProductSpecificValueData)
                    b.customProductData[c.key] = c.value
            }));
            W2c(b)
        }
    }
    ;var n3c = function(a) {
        this.JSC$27342_clientRoot = a;
        this.downloadManagerActionMap = {
            "yt-signal-action-delete-all-downloads-prompt": c3c.bind(null, this.JSC$27342_clientRoot),
            "yt-signal-action-delete-all-downloads": d3c,
            "yt-signal-action-delete-download": e3c,
            "yt-signal-action-delete-playlist-download": f3c,
            "yt-signal-action-install-pwa": g3c,
            "yt-signal-action-refresh-downloads": h3c,
            "yt-offline-video-endpoint": i3c,
            "yt-offline-playlist-endpoint": j3c,
            "yt-update-local-app-setting-command": k3c,
            "yt-offline-orchestration-action-command": l3c,
            "yt-signal-action-undo-delete-download": m3c
        };
        Ir(Gr.getInstance(), this.downloadManagerActionMap, this.JSC$27342_clientRoot);
        yk.instance = new yk
    }, o3c;
    function c3c(a) {
        var b = Gr.getInstance();
        var c = Mv("DELETE_ALL_DOWNLOADS_PROMPT", void 0, "Delete all downloads?");
        var d = Mv("DELETE", void 0, "Delete")
          , e = Mv("CANCEL", void 0, "Cancel");
        c = sxb(c, void 0, d, e, {
            signal: "DELETE_ALL_DOWNLOADS"
        });
        Hr(b, [{
            openPopupAction: c
        }], a)
    }
    function d3c() {
        return t(function(a) {
            return a.nextAddress == 1 ? n(a, sm().resolve(HI), 2) : n(a, jzb(), 0)
        })
    }
    function e3c(a) {
        var b, c;
        return t(function(d) {
            return d.nextAddress == 1 ? (c = (b = A(a, Br)) == null ? void 0 : b.targetId) ? n(d, sm().resolve(HI), 3) : d.jumpTo(0) : n(d, sm().resolve(GI).deleteVideo(c), 0)
        })
    }
    function f3c(a) {
        var b, c;
        return t(function(d) {
            return d.nextAddress == 1 ? (c = (b = A(a, Br)) == null ? void 0 : b.targetId) ? n(d, sm().resolve(HI), 3) : d.jumpTo(0) : n(d, izb(sm().resolve(GI), c), 0)
        })
    }
    function m3c(a) {
        var b, c;
        return t(function(d) {
            return (c = (b = A(a, Br)) == null ? void 0 : b.targetId) ? n(d, hzb(c), 0) : d.jumpTo(0)
        })
    }
    function h3c() {
        y("kevlar_woffle_refresh_dl_load_killswitch") || lzb()
    }
    function g3c() {
        y("kevlar_woffle") && yk.instance && hoa()
    }
    function i3c(a) {
        var b;
        if ((b = A(a, $u)) == null || !b.videoId)
            return !1;
        tzb(sm().resolve(GI), A(a, $u), a.clickTrackingParams);
        return !0
    }
    function j3c(a) {
        var b;
        if ((b = A(a, Zu)) == null || !b.playlistId)
            return !1;
        szb(sm().resolve(GI), A(a, Zu), a.clickTrackingParams);
        return !0
    }
    function k3c(a) {
        var b = A(a, XWa);
        (b == null ? void 0 : b.settingItemId) !== "SMART_DOWNLOADS_ENABLED" && (b == null ? void 0 : b.settingItemId) !== "SMART_DOWNLOADS_OPT_IN_BANNER_DISMISSED" || vzb(sm().resolve(GI), A(a, XWa))
    }
    function l3c(a) {
        a = A(a, bWa);
        var b;
        (a == null ? 0 : (b = a.actions) == null ? 0 : b.length) && wzb(a)
    }
    ;var p3c = function() {
        var a = I.apply(this, arguments) || this;
        a.actionMap = {
            "yt-get-mdx-status": "handleGetMdxStatus_",
            "yt-add-to-remote-queue-action": "handleAddToQueueAction_",
            "yt-clear-remote-queue-action": "handleClearQueueAction_",
            "yt-insert-in-remote-queue-action": "handleInsertInQueueAction_",
            "yt-remove-from-remote-queue-action": "handleRemoveFromQueueAction_"
        };
        a.remoteApi_ = null;
        return a
    };
    k(p3c, I);
    f = p3c.prototype;
    f.ready = function() {
        y("polymer_enable_mdx") && (RQc({
            device: "Desktop",
            app: "youtube-desktop",
            appId: this.appId,
            loadCastApiSetupScript: y("mdx_load_cast_api_bootstrap_script"),
            enableDialLoungeToken: y("enable_dial_short_lived_lounge_token"),
            enableCastLoungeToken: y("enable_cast_short_lived_lounge_token")
        }),
        mm("yt-remote-connection-change", this.handleConnectionChange_, this),
        mm("yt-remote-receiver-availability-change", this.handleReceiverAvailabilityChange_, this),
        (this.remoteApi_ = YQc()) && this.remoteApi_.subscribe("remoteQueueChange", this.handleRemoteQueueChange_, this))
    }
    ;
    f.handleGetMdxStatus_ = function() {
        return {
            connected: this.mdxConnected,
            receiverAvailable: this.receiverAvailable,
            receiverName: this.receiverName
        }
    }
    ;
    f.handleConnectionChange_ = function(a) {
        (this.mdxConnected = a) ? (a = UQc(),
        !a && bQc() && cQc() && (a = {
            key: "cast-selector-receiver",
            name: cQc()
        }),
        a = a.name) : a = null;
        this.receiverName = a;
        ni(this.remoteApi_);
        (this.remoteApi_ = YQc()) && this.remoteApi_.subscribe("remoteQueueChange", this.handleRemoteQueueChange_, this)
    }
    ;
    f.handleReceiverAvailabilityChange_ = function() {
        var a = TQc();
        bQc() && ay("yt-remote-cast-available") && a.push({
            key: "cast-selector-receiver",
            name: "Cast..."
        });
        this.receiverAvailable = a.length > 0
    }
    ;
    f.handleRemoteQueueChange_ = function() {
        var a = this.currentVideoId_
          , b = this.currentListId_
          , c = R5(this.remoteApi_);
        this.currentVideoId_ = c.videoId;
        this.currentListId_ = c.listId;
        this.currentVideoId_ && Dv(this.hostElement, "yt-sync-with-remote-video", [this.currentVideoId_, y("polymer_enable_mdx_queue") ? this.currentListId_ : null, a, b])
    }
    ;
    f.handleAddToQueueAction_ = function(a) {
        a = A(a, MNc);
        this.remoteApi_ && (a.videoId ? this.remoteApi_.addVideo(a.videoId) : a.playlistId && this.remoteApi_.addPlaylist(a.playlistId))
    }
    ;
    f.handleClearQueueAction_ = function() {
        this.remoteApi_ && this.remoteApi_.clearPlaylist()
    }
    ;
    f.handleInsertInQueueAction_ = function(a) {
        a = A(a, NNc);
        this.remoteApi_ && a.videoId && this.remoteApi_.insertVideo(a.videoId)
    }
    ;
    f.handleRemoveFromQueueAction_ = function(a) {
        a = A(a, ONc);
        this.remoteApi_ && a.videoId && this.remoteApi_.removeVideo(a.videoId)
    }
    ;
    var V$ = p3c;
    u([J(EA.YtActionHandlerBehavior), v("design:type", Object)], V$.prototype, "ytActionHandlerBehavior", void 0);
    u([P(), v("design:type", Object)], V$.prototype, "appId", void 0);
    u([P(), v("design:type", Boolean)], V$.prototype, "mdxConnected", void 0);
    u([P(), v("design:type", Boolean)], V$.prototype, "receiverAvailable", void 0);
    u([P(), v("design:type", Object)], V$.prototype, "receiverName", void 0);
    u([P(), v("design:type", Object)], V$.prototype, "currentVideoId_", void 0);
    u([P(), v("design:type", Object)], V$.prototype, "currentListId_", void 0);
    V$ = u([cz({
        is: "yt-mdx-manager",
        disableElementRegistration: !0
    })], V$);
    U(V$, "yt-mdx-manager", void 0, {
        mode: 2
    });
    var q3c;
    var r3c;
    var s3c = function() {
        var a = I.apply(this, arguments) || this;
        a.APP_IDS = {
            ytr: 3,
            ytm: 5
        };
        a.JSC$18940_timeoutId_ = 0;
        a.actionMap = {
            "yt-open-create-family-dialog": "open"
        };
        return a
    };
    k(s3c, I);
    f = s3c.prototype;
    f.created = function() {
        RMb(2200)
    }
    ;
    f.detached = function() {
        this.observer_ && this.observer_.disconnect()
    }
    ;
    f.open = function(a, b) {
        var c = this
          , d = a.serializedYpcFamilyCreateLoggingParams;
        this.JSC$18940_timeoutId_ = setTimeout(this.abort_.bind(this, a.postFlowErrorEndpoint, d), 3E4);
        b && (this.onReadyCallback_ = b);
        var e = T(this.hostElement).querySelector("#unicorn-iframe");
        d && d && U9a("ypcFamilyCreateFlowStarted", d);
        VYa("family_creation", function() {
            var h = Pa("gapi.config.update")
              , l = Pa("gapi.family_creation.render");
            h("iframes/family_creation/url", c.getFamilyCreationUrlWithUnicornParams_());
            h = 3;
            a.appId && a.appId in c.APP_IDS && (h = c.APP_IDS[a.appId]);
            h = {
                authUser: ak("SESSION_INDEX") || 0,
                clientId: h,
                darkmode: document.documentElement.hasAttribute("dark") ? 1 : 0,
                hl: ak("HL"),
                initialflow: [4, 5, 6, 7],
                m: c.isMobile ? 1 : 0,
                onFlowComplete: c.onUnicornFlowComplete_.bind(c, a.postFlowSuccessEndpoint, d),
                onError: c.onUnicornFlowError_.bind(c, a.postFlowErrorEndpoint, d),
                onReady: c.onUnicornFlowReady_.bind(c, a.referencePcidParams)
            };
            l(e, h)
        })
    }
    ;
    f.close = function() {
        T(this.hostElement).querySelector("#dialog").close();
        this.observer_ && this.observer_.disconnect()
    }
    ;
    f.onUnicornFlowComplete_ = function(a, b) {
        this.close();
        b && b && U9a("ypcFamilyCreateFlowSucceeded", b);
        zv(this.hostElement, "yt-navigate", {
            endpoint: a
        })
    }
    ;
    f.onUnicornFlowError_ = function(a, b) {
        this.close();
        b && U9a("ypcFamilyCreateFlowCancelled", b);
        zv(this.hostElement, "yt-navigate", {
            endpoint: a
        })
    }
    ;
    f.onUnicornFlowReady_ = function(a) {
        var b = this;
        this.clearTimeout_();
        if (this.onReadyCallback_)
            this.onReadyCallback_();
        a && Pa("gapi.family_creation.setConfig")(0, a);
        this.observer_ = new MutationObserver(function() {
            T(b.hostElement).querySelector("#dialog").fit()
        }
        );
        this.observer_.observe(T(this.hostElement).querySelector("#unicorn-iframe").querySelector("iframe"), {
            atttributes: !0,
            attributeFilter: ["style"]
        });
        T(this.hostElement).querySelector("#dialog").open()
    }
    ;
    f.getFamilyCreationUrlWithUnicornParams_ = function() {
        return ak("YTR_FAMILY_CREATION_URL")
    }
    ;
    f.getCurrentUrl_ = function() {
        return document.location.href
    }
    ;
    f.abort_ = function(a, b) {
        this.clearTimeout_();
        this.onUnicornFlowError_(a, b)
    }
    ;
    f.clearTimeout_ = function() {
        clearTimeout(this.JSC$18940_timeoutId_)
    }
    ;
    var W$ = s3c;
    u([J(EA.YtActionHandlerBehavior), v("design:type", Object)], W$.prototype, "ytActionHandlerBehavior", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], W$.prototype, "isMobile", void 0);
    u([P(), v("design:type", Object)], W$.prototype, "onReadyCallback_", void 0);
    u([P(), v("design:type", Object)], W$.prototype, "observer_", void 0);
    W$ = u([cz({
        is: "yt-create-family-dialog",
        disableElementRegistration: !0
    })], W$);
    U(W$, "yt-create-family-dialog", function() {
        if (r3c === void 0) {
            var a = document.createElement("template");
            G(a, "<!--css-build:shady--><!--css-build:shady--><tp-yt-paper-dialog id=\"dialog\" with-backdrop=\"\" class=\"style-scope yt-create-family-dialog\">\n  <div id=\"unicorn-iframe\" class=\"style-scope yt-create-family-dialog\"></div>\n</tp-yt-paper-dialog>\n");
            a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
            var b = a.content
              , c = b.insertBefore;
            q3c === void 0 && (q3c = document.createElement("template"));
            var d = q3c;
            c.call(b, d.content.cloneNode(!0), a.content.firstChild);
            r3c = a
        }
        a = r3c;
        return a
    }, {
        mode: 2
    });
    var t3c;
    var u3c;
    function v3c(a) {
        setTimeout(function() {
            requestAnimationFrame(a)
        }, 80)
    }
    var w3c = function() {
        var a = I.apply(this, arguments) || this;
        a.enableRefreshSignatureMomentsWeb = y("enable_cairo_refresh_signature_moments_web");
        a.STEP = 1;
        a.BLOCK_ON = 80;
        a.MIN_PROGESS = 0;
        a.MAX_PROGESS = 100;
        return a
    };
    k(w3c, I);
    f = w3c.prototype;
    f.created = function() {
        this.boundNextProgress_ = this.nextProgress_.bind(this)
    }
    ;
    f.ready = function() {
        this.progress_ = this.MIN_PROGESS;
        this.hostElement.hidden = !0;
        this.hostElement.setAttribute("aria-valuemin", String(this.MIN_PROGESS));
        this.hostElement.setAttribute("aria-valuemax", String(this.MAX_PROGESS));
        sm().addProvider({
            provide: NRc,
            useValue: this
        })
    }
    ;
    f.start = function() {
        this.progress = this.MIN_PROGESS;
        this.hostElement.hidden = !1;
        window.requestAnimationFrame(this.boundNextProgress_)
    }
    ;
    f.finish = function() {
        var a = this;
        this.progress = this.MAX_PROGESS;
        v3c(function() {
            a.progress == a.MAX_PROGESS && (a.hostElement.hidden = !0)
        })
    }
    ;
    f.nextProgress_ = function() {
        this.progress >= this.BLOCK_ON || (this.progress += this.STEP,
        window.requestAnimationFrame(this.boundNextProgress_))
    }
    ;
    da.Object.defineProperties(w3c.prototype, {
        progress: {
            configurable: !0,
            enumerable: !0,
            set: function(a) {
                this.progress_ = a;
                var b = "scaleX(" + a / this.MAX_PROGESS + ")"
                  , c = T(this.hostElement).querySelector("#progress").style;
                c.transform = b;
                c.webkitTransform = b;
                this.hostElement.setAttribute("aria-valuenow", String(a))
            },
            get: function() {
                return this.progress_
            }
        }
    });
    var X$ = w3c;
    u([J(JA.YtComponentBehavior), v("design:type", Object)], X$.prototype, "ytComponentBehavior", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], X$.prototype, "enableRefreshSignatureMomentsWeb", void 0);
    X$ = u([cz({
        is: "yt-page-navigation-progress",
        disableElementRegistration: !0
    })], X$);
    U(X$, "yt-page-navigation-progress", function() {
        if (u3c === void 0) {
            var a = document.createElement("template");
            G(a, "<!--css-build:shady--><!--css-build:shady--><div id=\"progress\" class=\"style-scope yt-page-navigation-progress\"></div>\n");
            a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
            var b = a.content
              , c = b.insertBefore;
            t3c === void 0 && (t3c = document.createElement("template"));
            var d = t3c;
            c.call(b, d.content.cloneNode(!0), a.content.firstChild);
            u3c = a
        }
        a = u3c;
        return a
    }, {
        mode: 2
    });
    var x3c = {
        padding: "10px 16px",
        "font-size": "32px",
        "font-weight": "bold",
        background: "linear-gradient(135deg, rgba(131, 58, 180, 1) 0%, rgba(253, 29, 29, 1) 50%, rgba(252, 176, 69, 1) 100%)",
        color: "#fff",
        "text-shadow": "1px 1px 3px rgba(255, 255, 255, 0.3)",
        "border-radius": "15px"
    }
      , y3c = {
        "font-size": "12px",
        "font-style": "italic"
    }
      , z3c = {
        padding: "8px 0",
        "font-size": "14px",
        "font-weight": "bold",
        color: "#f00"
    };
    function A3c(a) {
        return Object.entries(a).map(function(b) {
            return b.join(":")
        }).join(";")
    }
    ;function B3c(a) {
        var b, c, d;
        t(function(e) {
            if (e.nextAddress == 1)
                return n(e, C3c(), 2);
            b = e.yieldResult;
            c = Tv.instance;
            switch (b) {
            case "granted":
                d = a.getLocationCommand;
                break;
            case "denied":
                d = a.openDeniedDialogAction;
                break;
            case "prompt":
                d = a.openCollectionDialogAction;
                break;
            default:
                d = a.openCollectionDialogAction;
            }
            d && c.resolveCommand(d);
            ta(e)
        })
    }
    function C3c() {
        var a, b;
        return t(function(c) {
            if (c.nextAddress == 1)
                return a = "prompt",
                navigator.permissions ? n(c, navigator.permissions.query({
                    name: "geolocation"
                }), 3) : c.jumpTo(2);
            c.nextAddress != 2 && (b = c.yieldResult,
            a = b.state);
            return c.return(a)
        })
    }
    ;function D3c() {
        var a, b, c;
        return t(function(d) {
            if (d.nextAddress == 1)
                return a = sm().resolve(dx),
                a ? n(d, Ww(a, {
                    signalServiceEndpoint: {
                        signal: "GET_DATASYNC_IDS"
                    }
                }), 2) : (Gm(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),
                d.return(void 0));
            if (b = d.yieldResult) {
                if (b.errorMetadata)
                    return Gm(Error("Datasync IDs fetch responded with " + b.errorMetadata.status + ": " + b.error)),
                    d.return(void 0);
                c = b.datasyncIds;
                owb = c.length;
                return d.return(c)
            }
            Gm(Error("Network request to get Datasync IDs failed."));
            return d.return(void 0)
        })
    }
    ;function E3c(a) {
        a = a.match(/(.*)::.*::.*/);
        if (a !== null)
            return a[1]
    }
    function F3c(a) {
        if (nnc()) {
            var b = Object.keys(window.sessionStorage);
            b = g(b);
            for (var c = b.next(); !c.done; c = b.next()) {
                c = c.value;
                var d = E3c(c);
                d === void 0 || a.includes(d) || self.sessionStorage.removeItem(c)
            }
        }
    }
    function G3c() {
        if (!nnc())
            return !1;
        var a = Jk()
          , b = Object.keys(window.sessionStorage);
        b = g(b);
        for (var c = b.next(); !c.done; c = b.next())
            if (c = E3c(c.value),
            c !== void 0 && c !== a)
                return !0;
        return !1
    }
    ;function H3c() {
        D3c().then(function(a) {
            a && (spa(a),
            upb(a),
            K8a(a),
            F3c(a))
        })
    }
    function I3c(a) {
        Ei.addLowPriorityJob(function() {
            var b, c, d, e, h;
            return t(function(l) {
                switch (l.nextAddress) {
                case 1:
                    if (y("ytidb_clear_optimizations_killswitch")) {
                        l.jumpTo(2);
                        break
                    }
                    b = Jk("clear");
                    if (b.startsWith("V") && b.endsWith("||")) {
                        var m = [b];
                        spa(m);
                        upb(m);
                        K8a(m);
                        F3c(m);
                        return l.return()
                    }
                    c = L8a();
                    d = G3c();
                    return n(l, vpb(), 3);
                case 3:
                    return e = l.yieldResult,
                    n(l, tpa(), 4);
                case 4:
                    if (h = l.yieldResult,
                    !(c || d || e || h))
                        return l.return();
                case 2:
                    a.isNetworkAvailable() ? H3c() : a.listenOnce("publicytnetworkstatus-online", H3c),
                    ta(l);
                }
            })
        })
    }
    ;function Y$(a) {
        a = {
            openPopupAction: {
                popupType: "TOAST",
                popup: {
                    notificationActionRenderer: {
                        responseText: Yw(a)
                    }
                }
            }
        };
        Tv.instance && Tv.instance.resolveCommand(a)
    }
    function J3c(a, b) {
        if (a) {
            var c = er();
            fr(c, 3854, void 0, {
                layer: 0,
                parentLayer: 4
            });
            switch (a) {
            case 1:
                var d = 176798;
                break;
            case 2:
                d = 176799;
                break;
            case 3:
                d = 176801;
                if (b)
                    for (a = g(b),
                    b = a.next(); !b.done; b = a.next())
                        if (b = b.value,
                        $f(b, qf(b, gGc, 3)) === 4 && $f(b, 2) === 1) {
                            d = 176800;
                            break
                        }
                break;
            case 6:
                d = 184594;
            }
            d && (d = hr(c, {
                veType: d
            })) && jr(c, d)
        }
    }
    function K3c(a) {
        if (a) {
            var b = er();
            fr(b, 3854, void 0, {
                layer: 0,
                parentLayer: 4
            });
            switch (a) {
            case 1:
                var c = 176802;
                break;
            case 2:
                c = 176803;
                break;
            case 8:
                c = 184594;
                break;
            case 7:
                c = 186860;
                break;
            case 3:
            case 4:
            case 5:
                c = 176804;
            }
            c && (a = hr(b, {
                veType: c
            })) && jr(b, a)
        }
    }
    function L3c(a) {
        switch (a.latencyType) {
        case 0:
            Kq("dma_consent_flow");
            Lq("cpit", a.timestampEpochMillis, "dma_consent_flow");
            break;
        case 3:
            Lq("cpist", a.timestampEpochMillis, "dma_consent_flow");
            break;
        case 5:
            Lq("cprtif", a.timestampEpochMillis, "dma_consent_flow");
            break;
        case 4:
            Lq("cprtli", a.timestampEpochMillis, "dma_consent_flow");
            break;
        case 6:
            Lq("cprt", a.timestampEpochMillis, "dma_consent_flow");
            break;
        case 7:
            Lq("cpdt", a.timestampEpochMillis, "dma_consent_flow");
            break;
        case 8:
            Lq("cpjct", a.timestampEpochMillis, "dma_consent_flow");
        }
    }
    function M3c(a, b) {
        var c, d, e, h, l, m, p, q, r, x, z, C, E, K, N, Q, V, ca, Z;
        return t(function(ba) {
            switch (ba.nextAddress) {
            case 1:
                va(ba, 2);
                c = A(a, $Mc);
                e = (d = c) == null ? void 0 : d.serializedConsentRequest;
                h = void 0;
                e && (h = cGc(ge(e)));
                if (h === void 0)
                    return ba.return();
                m = uGc({
                    request: h
                });
                m.latencyCallback = L3c;
                b && vGc(m, function() {
                    b.then(function(ia) {
                        ia.pauseVideo();
                        new vxa().increment()
                    })
                });
                return ((p = c) == null ? void 0 : p.consentAction) === "CONSENT_ACTION_PREWARM" ? n(ba, AGc(m), 5) : n(ba, EGc(m), 6);
            case 6:
                l = ba.yieldResult;
                q = Hf(l, X3);
                if (q === 1) {
                    if (((r = cg(l, V3, 1, X3)) == null ? void 0 : $f(r, 1)) === 1 || ((x = cg(l, V3, 1, X3)) == null ? void 0 : $f(x, 1)) === 2 || ((z = cg(l, V3, 1, X3)) == null ? void 0 : $f(z, 1)) === 3)
                        y("enable_dma_post_enforcement") ? Y$(Mv("DMA_CONSENT_CONFIRMATION2", {}, "Your choices have been saved. You can change your choices anytime in your Google Account.")) : Y$(Mv("DMA_CONSENT_CONFIRMATION", {}, "Your choice will take effect on March 6, 2024. You can change your choices anytime in your Google Account."));
                    J3c((C = cg(l, V3, 1, X3)) == null ? void 0 : $f(C, 1), Jf(l, fGc, 3, vf()))
                } else
                    q === 2 ? (((E = Y3(l)) == null ? void 0 : $f(E, 1)) === 5 ? Y$(Mv("DMA_CONSENT_RECORD_ERROR", {}, "Something went wrong and your choices were not saved")) : ((K = Y3(l)) == null ? void 0 : $f(K, 1)) === 1 || ((N = Y3(l)) == null ? void 0 : $f(N, 1)) === 4 ? Y$(Mv("DMA_CONSENT_GENERAL_ERROR", {}, "Something went wrong while loading")) : ((Q = Y3(l)) == null ? void 0 : $f(Q, 1)) === 7 && ((V = h) == null ? void 0 : (ca = If(V, U3, 4)) == null ? void 0 : $f(ca, 4)) !== 1 && Y$(Mv("DMA_CONSENT_GENERAL_ERROR", {}, "Something went wrong while loading")),
                    K3c((Z = Y3(l)) == null ? void 0 : $f(Z, 1))) : Y$(Mv("DMA_CONSENT_GENERAL_ERROR", {}, "Something went wrong while loading"));
                ba.jumpTo(5);
                break;
            case 5:
                ya(ba, 0);
                break;
            case 2:
                za(ba),
                Y$(Mv("DMA_CONSENT_GENERAL_ERROR", {}, "Something went wrong while loading")),
                ta(ba);
            }
        })
    }
    ;var N3c = new Map;
    function O3c() {
        if (!N3c.has("Worker")) {
            N3c.set("Worker", !0);
            var a = {
                api: "BROWSER_API_WEB_WORKER"
            };
            a.available = "Worker"in window ? !0 : !1;
            Xk("apiTest", a)
        }
    }
    ;var Doa = function(a, b) {
        var c = this;
        this.handleError = a;
        this.logEventInternal = b;
        this.hasUnloaded = !1;
        self.document === void 0 || self.addEventListener("beforeunload", function() {
            c.hasUnloaded = !0
        });
        this.shouldLogTransactionEndedThisSession = Math.random() <= .2
    };
    Doa.prototype.logError = function(a) {
        this.handleError(a)
    }
    ;
    Doa.prototype.logEvent = function(a, b) {
        switch (a) {
        case "IDB_DATA_CORRUPTED":
            y("idb_data_corrupted_killswitch") || this.logEventInternal("idbDataCorrupted", b);
            break;
        case "IDB_UNEXPECTEDLY_CLOSED":
            this.logEventInternal("idbUnexpectedlyClosed", b);
            break;
        case "IS_SUPPORTED_COMPLETED":
            y("idb_is_supported_completed_killswitch") || this.logEventInternal("idbIsSupportedCompleted", b);
            break;
        case "QUOTA_EXCEEDED":
            P3c(this, b);
            break;
        case "TRANSACTION_ENDED":
            this.shouldLogTransactionEndedThisSession && Math.random() <= .1 && this.logEventInternal("idbTransactionEnded", b);
            break;
        case "TRANSACTION_UNEXPECTEDLY_ABORTED":
            a = Object.assign({}, b, {
                hasWindowUnloaded: this.hasUnloaded
            }),
            this.logEventInternal("idbTransactionAborted", a);
        }
    }
    ;
    var P3c = function(a, b) {
        YI.getInstance().estimate().then(function(c) {
            c = Object.assign({}, b, {
                isSw: self.document === void 0,
                isIframe: self !== self.top,
                deviceStorageUsageMbytes: Q3c(c == null ? void 0 : c.usage),
                deviceStorageQuotaMbytes: Q3c(c == null ? void 0 : c.quota)
            });
            a.logEventInternal("idbQuotaExceeded", c)
        })
    };
    function Q3c(a) {
        return typeof a === "undefined" ? "-1" : String(Math.ceil(a / 1048576))
    }
    ;var R3c = window;
    function S3c() {
        var a = R3c.uaChPolyfill.state;
        if (a.type === 0)
            Xk("clientHintsPolyfillEvent", {
                clientHintsSupported: !1
            });
        else {
            var b = navigator.userAgent
              , c = a.syntheticUa !== void 0 && a.syntheticUa === b
              , d = {
                clientHintsSupported: !0,
                uaAccessedBeforePolyfill: a.didAccessUaBeforePolyfillAvailable,
                syntheticUaMatches: c
            };
            a.didAccessUaBeforePolyfillAvailable && (d.uaAccessBeforePolyfillCount = a.uaAccessBeforePolyfillCount,
            a.firstAccessUaError && (d.firstUaAccessStack = String(a.firstAccessUaError.stack).replace(/\n/g, ""),
            Fm(a.firstAccessUaError)),
            d.polyfillAvailabilityDelayMs = a.polyfillAvailabilityDelay);
            Xk("clientHintsPolyfillEvent", d);
            c || (b = {
                syntheticUa: a.syntheticUa,
                ua: b
            },
            b.brand = a.data.brands.map(function(e) {
                return "\"" + e.brand + "\"; v=\"" + e.version + "\""
            }),
            b.mobileness = a.data.mobile,
            a = a.data.values,
            a.architecture && (b.platformArchitecture = a.architecture),
            a.model && (b.model = a.model),
            a.platform && (b.platformBrand = a.platform),
            a.platformVersion && (b.platformVersion = a.platformVersion),
            a.uaFullVersion && (b.fullVersion = a.uaFullVersion),
            Xk("clientHintsPolyfillDiagnostics", b))
        }
    }
    var T3c = !1;
    function U3c() {
        var a;
        ((a = R3c.uaChPolyfill) == null ? void 0 : a.state.type) === 1 ? T3c || (R3c.uaChPolyfill.onReady = U3c,
        T3c = !0) : R3c.uaChPolyfill && S3c()
    }
    ;function V3c(a, b) {
        DRc(new CRc(A(b, bOc).addToken,A(b, bOc).commonToken)).then(function() {
            zv(a, "yt-invoke-instrument-manager-action-completed")
        }, function(c) {
            zv(a, "yt-invoke-instrument-manager-action-error", c)
        })
    }
    ;var Z$ = function() {
        var a = I.apply(this, arguments) || this;
        a.tabGesturesIsActive = !1;
        a.topbarIsAboveChipbar = !1;
        a.hasDelegation = !1;
        a.darkerDarkTheme = y("web_darker_dark_theme");
        a.frostedGlass = y("web_frosted_glass");
        a.scrollAtTop = !0;
        a.guideScrollTop = 0;
        a.isTheaterModeSession = bk("START_IN_THEATER_MODE");
        a.isFullWindowSession = bk("START_IN_FULL_WINDOW_MODE");
        a.hasCreateFamilyDialog = !1;
        a.mastheadHeight = 56;
        a.networkStatusManager = new Vl;
        a.actionMap = {
            "yt-command-executor-command": "handleCommandWithCommandHandler",
            "yt-dark-mode-toggled-action": "onDarkModeToggledAction",
            "yt-edu-dismiss-action": "handleEduDismissAction",
            "yt-edu-impression-action": "handleEduImpressionAction",
            "yt-navigate-action": "onYtNavigateAction",
            "yt-navigate-home-action": "onYtNavigateHomeAction",
            "yt-player-fullscreen": "onPlayerFullscreen",
            "yt-register-create-family-dialog": "onYtRegisterCreateFamilyDialog",
            "yt-select-country-command": "handleSelectCountryCommand",
            "yt-select-language-command": "handleSelectLanguageCommand",
            "yt-clear-url-param-command": "handleClearUrlParamCommand",
            "yt-set-cookie-command": "onSetCookieCommand",
            "yt-set-pref-storage-entry-command": "onSetPrefStorageEntryCommand",
            "yt-set-local-storage-command": "onSetLocalStorageCommand",
            "yt-set-push-notifications-enabled-command": "onSetPushNotificationsEnabledCommand",
            "yt-signal-action-copy-debug-data": "onYtSignalActionCopyDebugData",
            "yt-signal-action-enable-chrome-notifications": "onYtSignalActionEnableChromeNotifications",
            "yt-signal-action-toggle-restricted-mode-on": "onYtSignalActionToggleRestrictedModeOnAction",
            "yt-signal-action-toggle-restricted-mode-off": "onYtSignalActionToggleRestrictedModeOffAction",
            "yt-signal-action-confirm-mentions-edu": "onYtSignalActionConfirmMentionsEdu",
            "yt-signal-action-record-mentions-edu-impression": "onYtSignalActionRecordMentionsEduImpression",
            "yt-signal-action-show-keyboard-shortcut-dialog": "onYtSignalActionShowKeyboardShortcutDialog",
            "yt-signal-action-skip-navigation": "onYtSignalActionSkipNavigation",
            "yt-signal-action-request-persistent-storage": "onYtSignalActionRequestPersistentStorage",
            "yt-timed-command": "onYtTimedCommand",
            "yt-window-resized": "onWindowResized",
            "yt-window-scrolled": "onWindowScrolled",
            "yt-persist-subscriptions-display-preferences-command": "handlePersistSubscriptionsDisplayPreferencesCommand",
            "yt-invoke-instrument-manager-action": "onInvokeInstrumentManagerAction",
            "yt-entity-update-command": "handleEntityUpdateCommand",
            "yt-web-native-share-command": "handleWebNativeShareCommand",
            "yt-confirm-dialog-endpoint": "handleConfirmDialogEndpoint",
            "yt-ad-feedback-endpoint": "handleOpenPopupNavigationEndpoints",
            "yt-create-backstage-post-dialog-endpoint": "handleOpenPopupNavigationEndpoints",
            "yt-manage-purchase-endpoint": "handleOpenPopupNavigationEndpoints",
            "yt-modal-endpoint": "handleOpenPopupNavigationEndpoints",
            "yt-unlimited-family-flow-endpoint": "handleOpenPopupNavigationEndpoints",
            "yt-ypc-cancel-survey-endpoint": "handleOpenPopupNavigationEndpoints",
            "yt-register-promo-command": "handleYtRegisterPromoCommand",
            "yt-location-collection-command": "onYtLocationCollectionCommand",
            "yt-get-location-command": "onYtGetLocationCommand",
            "yt-log-flow-logging-event-command": "logFlowLoggingEventCommand",
            "yt-save-command-to-session-storage-action": "handleSaveCommandToSessionStorage",
            "yt-show-dma-consent-flow-command": "handleShowDmaConsentFlow",
            "yt-signal-action-show-dma-consent-flow": "handleShowDmaConsentFlow",
            "yt-signal-action-toggle-dark-theme-on": "handleSignalActionToggleDarkThemeOn",
            "yt-signal-action-toggle-dark-theme-off": "handleSignalActionToggleDarkThemeOff",
            "yt-signal-action-toggle-dark-theme-device": "handleSignalActionToggleDarkThemeDevice",
            "yt-select-active-identity-endpoint": "handleSelectActiveIdentityEndpointInternal",
            "yt-update-permission-role-command": "handleUpdatePermissionRoleCommand",
            "yt-channel-creation-form-endpoint": "handleYtChannelCreationFormEndpoints",
            "yt-google-payment-billing-command": "handleCommandWithCommandHandler",
            "yt-place-miniplayer-in-app": "handlePlaceMiniplayerInApp"
        };
        a.dynamicActionMap = {
            "yt-run-attestation-command": function(b) {
                var c = ftb.instance;
                return (b = A(b, FSa)) ? y("use_rta_manager_for_async") && atb() ? jtb(c, b) : htb(c, b) : Xi(Error("Bad Command: no runAttestationCommand"))
            }
        };
        return a
    };
    k(Z$, I);
    f = Z$.prototype;
    f.created = function() {
        var a = sm();
        y("kevlar_clear_duplicate_pref_cookie") && Lk(Ei, function() {
            var b = mi.get("PREF");
            b && !/f\d=/.test(b) && (b = pk("kevlar_duplicate_pref_cookie_domain_override"),
            document.cookie = b ? "PREF=null;domain=" + b + ";expires=Thu, 01 Jan 1970 00:00:01 GMT" : "PREF=null;domain=.www.youtube.com;expires=Thu, 01 Jan 1970 00:00:01 GMT")
        });
        y("gzip_gel_with_worker") && Oqa();
        y("jspb_serialize_with_worker") && kta();
        y("web_worker_availability_check") && O3c();
        y("nwl_init_killswitch") || Qra().then(function() {
            Ei.addLowPriorityJob(aRc)
        });
        this.pageManagerAttachedPromise = Zi();
        this.ytdAppBehavior.loadDepsPromise = Yi([this.ytdAppBehavior.loadDepsPromise, this.pageManagerAttachedPromise.promise]);
        this.scrollThrottle = new rt(this.onThrottledScroll,200,this);
        y("external_fullscreen") && (this.fullscreen = !1);
        this.ephemeralResponseStore = a.resolve(pA);
        this.boundOnTouchStart = this.onTouchStart.bind(this);
        Coa();
        j9a = !!Pa("ytappsettings.initialized");
        oy = Pa("ytappsettings.previousValue");
        k9a = Pa("ytappsettings.previousSnapshotTime");
        j9a || (j9a = !0,
        l9a());
        ARc();
        BRc();
        Yj("DEFERRED_DETACH", y("kevlar_tuner_should_defer_detach"));
        Yj("REUSE_COMPONENTS", !0);
        Yj("STAMPER_STABLE_LIST", !0);
        Yj("SCHEDULED_LAZY_LIST", !0);
        Yj("openPopupConfig", eSc);
        y("kevlar_shell_cleanup") && Ei.addLowPriorityJob(e8a.bind(this, Na.caches));
        bk("IS_SHELL_LOAD") && Jq({
            shellStartupDurationMs: Math.round(ol() - Cq())
        });
        I3c(this.networkStatusManager);
        y("kevlar_is_hiring") && (console.log("%cYouTube.com is hiring!", A3c(x3c)),
        console.log("%cYouTube.com is the second largest website in the world, with hundreds of\nmillions of users and watch-hours per day. It makes you laugh, learn, and leaves\nyou amazed. Are there things that you love about YouTube? Things that you don't?\nHelp us make it better!", A3c(y3c)),
        console.log("%cVisit http://go/join-youtube-web to apply today.", A3c(z3c)));
        y("web_ua_ch_polyfill_enabled") && U3c();
        eBb(a.resolve(dBb))
    }
    ;
    f.ready = function() {
        this.guide.addEventListener("transitionend", this.processDrawerIronSelect.bind(this));
        this.guideInnerContent.addEventListener("scroll", this.ytRendererBehavior.markDirty.bind(this));
        var a = SYa();
        a && !y("external_fullscreen_killswitch") && document.addEventListener(a, this.setFullscreen.bind(this));
        (a = window.matchMedia("(prefers-color-scheme: dark)")) && a.addEventListener && a.addEventListener("change", this.onDeviceThemeChanged.bind(this));
        this.onDeviceThemeChanged()
    }
    ;
    f.attached = function() {
        var a = this;
        fx().processSignal("ci");
        y("kevlar_passive_event_listeners") ? this.hostElement.addEventListener("touchstart", this.boundOnTouchStart, Qia ? {
            passive: !0
        } : void 0) : this.hostElement.addEventListener("touchstart", this.boundOnTouchStart);
        hv(bYa(), "SUCCESS");
        this.updateIconSet();
        PTb(this.guideInnerContent, !1);
        Xx().initVisibilityObserver();
        this.guideService.guideElement = this.guide;
        var b = document.createElement("ytd-miniplayer")
          , c = T(this.hostElement).querySelector("#content");
        T(this.hostElement).insertBefore(b, c);
        fx().processSignal("ma");
        sm().resolve(hx).init(b);
        bk("IS_SHELL_LOAD") && (c = document.createElement("ytd-network-status-banner"),
        T(this.hostElement).insertBefore(c, b));
        y("kevlar_right_click_on_lockups") && hM._onCaptureClick && document.addEventListener("contextmenu", hM._onCaptureClick.bind(hM), !0);
        var d = function() {
            var e = OA("yt-page-navigation-progress");
            T(a.hostElement).appendChild(e)
        };
        setTimeout(function() {
            fx().parkOrScheduleJob(d, 0, "eocs", 16)
        }, 0);
        y("service_worker_push_enabled") && Lk(Ei, N9a);
        Ir(Gr.getInstance(), this.dynamicActionMap, this.hostElement);
        zv(this.hostElement, "ytd-app-attached");
        fx().processSignal("aa");
        bUb(this.hostElement);
        Oa("gapi.load", VYa);
        this.networkStatusManager.listen("publicytnetworkstatus-online", this.onlineHandler.bind(this));
        this.networkStatusManager.listen("publicytnetworkstatus-offline", this.offlineHandler.bind(this));
        this.networkStatusManager.isNetworkAvailable() || this.offlineHandler();
        Lk(Ei, function() {
            var e = document.createElement("ytd-video-preview");
            T(T(a.hostElement).querySelector("#video-preview")).appendChild(e)
        });
        this.updateIsInlinePreviewDisabled();
        if (ry() && this.isAppDarkTheme() !== qy())
            this.onDarkModeToggledAction();
        else
            b = py() === "USER_INTERFACE_THEME_DARK",
            this.isAppDarkTheme() !== b && Gm(new Hk("Theme was not applied",this.getThemeSettingsToLog())),
            this.standalone || (pSc = new oSc(this.hostElement)),
            o3c = new n3c(this.hostElement),
            b3c = new a3c(this.hostElement),
            MSc = new LSc(this.hostElement),
            y("web_enable_miniplayer_refactor") && sm().resolve(hx).install(this.hostElement)
    }
    ;
    f.handlePlaceMiniplayerInApp = function(a) {
        var b = T(this.hostElement).querySelector("#content");
        this.hostElement.insertBefore(a, b)
    }
    ;
    f.getThemeSettingsToLog = function() {
        var a = py() === "USER_INTERFACE_THEME_DARK";
        a = ry() ? qy() ? "os-dark" : "os-light" : a ? "dark" : "light";
        return {
            appTheme: this.isAppDarkTheme() ? "dark" : "light",
            prefsTheme: a,
            cookiesEnabled: Bk()
        }
    }
    ;
    f.detached = function() {
        RTb(this.guideInnerContent);
        Ei.cancelJob(SM);
        SM = 0;
        Ei.cancelJob(TM);
        TM = 0;
        dm(aUb);
        aUb.length = 0;
        $Tb = ZTb = null;
        Xx().dispose();
        y("kevlar_passive_event_listeners") && this.hostElement.removeEventListener("touchstart", this.boundOnTouchStart);
        Jr(Gr.getInstance(), pSc.playlistHandlerActionMap, pSc.JSC$27040_clientRoot);
        Jr(Gr.getInstance(), o3c.downloadManagerActionMap, o3c.JSC$27342_clientRoot);
        Jr(Gr.getInstance(), b3c.feedbackCollectorActionMap, b3c.JSC$27337_clientRoot);
        for (var a = g(MSc.eventListeners), b = a.next(); !b.done; b = a.next()) {
            var c = g(b.value);
            b = c.next().value;
            c = c.next().value;
            c = g(c);
            for (var d = c.next(); !d.done; d = c.next()) {
                var e = g(d.value);
                d = e.next().value;
                e = e.next().value;
                b.removeEventListener(d, e)
            }
        }
        Jr(Gr.getInstance(), MSc.autonavPauseActionMap, MSc.JSC$17896_clientRoot);
        y("web_enable_miniplayer_refactor") && sm().resolve(hx).uninstall()
    }
    ;
    f.updateIsInlinePreviewDisabled = function() {
        this.isInlinePreviewDisabled = Ek().getFlag(186)
    }
    ;
    f.computeIsInlinePreviewEnabled = function(a, b, c) {
        return !c && Xyc({
            miniplayerIsActive: a,
            miniplayerPlaybackState: b
        })
    }
    ;
    f.isInlinePreviewEnabledChanged = function() {
        this.ytdReduxBehavior.dispatch(y0a(this.isInlinePreviewEnabled));
        this.ytdReduxBehavior.dispatch(Wv({
            type: "SET_SHARED_INLINE_PREVIEW_ENABLED",
            payload: this.isInlinePreviewEnabled
        }));
        this.ytdReduxBehavior.dispatch(Wv({
            type: "SET_SHARED_ANIMATED_THUMBNAIL_ENABLED",
            payload: !this.isInlinePreviewDisabled
        }))
    }
    ;
    f.onlineHandler = function() {
        this.ytdReduxBehavior.store.dispatch(A0a(!0))
    }
    ;
    f.onYtSignalActionRequestPersistentStorage = function() {
        if (!y("request_persistent_storage_killswitch")) {
            var a = sm().resolve(LAb);
            a.cachedPersistStatePromise || (a.cachedPersistStatePromise = NBb())
        }
    }
    ;
    f.handleYtChannelCreationFormEndpoints = function(a) {
        a && this.ytComponentBehavior.resolveCommand(a)
    }
    ;
    f.offlineHandler = function() {
        this.ytdReduxBehavior.store.dispatch(A0a(!1))
    }
    ;
    f.initIconDefs = function(a, b, c) {
        var d = document.createElement("iron-iconset-svg");
        d.name = a;
        a = document.createElementNS("http://www.w3.org/2000/svg", "svg");
        d.appendChild(a);
        a.appendChild(b);
        if (c)
            for (var e in c)
                d[e] = c[e];
        document.body.appendChild(d);
        return d
    }
    ;
    f.onWindowResized = function() {
        Dv(this.hostElement, "yt-close-popup-action", ["yt-tooltip-renderer"]);
        var a = WTb.getInstance();
        a.documentWidth_ = document.body.clientWidth;
        XTb(a)
    }
    ;
    f.onWindowScrolled = function() {
        var a = sm().resolve(bx).getCurrentPage();
        a != null && a.getScrollTop && this.ytdReduxBehavior.dispatch(Wv({
            type: "SET_SCROLL_AT_TOP",
            payload: a.getScrollTop() <= 0
        }))
    }
    ;
    f.guideIsVisibleButNotPersistentSelectorChanged = function() {
        var a = sm().resolve(bx).getCurrentPage();
        this.getCurrentPageScrollableElementType() === "HTML" && this.guideIsVisibleButNotPersistent ? (document.body.style.overflowY = "scroll",
        this.guideScrollTop = a.getScrollTop(),
        document.body.classList.add("lock-scrollbar"),
        document.body.style.top = "-" + this.guideScrollTop + "px") : document.body.classList.contains("lock-scrollbar") && (document.body.style.overflowY = "",
        document.body.style.top = "",
        document.body.classList.remove("lock-scrollbar"),
        a.setScrollTop(this.guideScrollTop));
        Ev(this.hostElement, "yt-rich-grid-layout-refreshed")
    }
    ;
    f.getCurrentPageScrollableElementType = function() {
        var a = sm().resolve(bx).getCurrentPage();
        if (a && a.getPageScrollingElement())
            return a.getPageScrollingElement().nodeName
    }
    ;
    f.observeGuideVisibility = function() {
        var a = WTb.getInstance()
          , b = this.miniGuideVisible;
        a.guidePersistentAndVisible_ = this.guidePersistentAndVisible;
        a.miniGuideVisible_ = b;
        XTb(a)
    }
    ;
    f.handleEduDismissAction = function(a) {
        a && a.eduDismissAction && (Dv(this.hostElement, "yt-close-popup-action", ["yt-bubble-hint-renderer"]),
        W5a.getInstance(),
        Dx.set("" + a.eduDismissAction.key + "-dismissed", !0))
    }
    ;
    f.handleEduImpressionAction = function(a) {
        if (a && a.eduImpressionAction) {
            var b = W5a.getInstance();
            a = a.eduImpressionAction.key;
            b.JSC$9311_eduDisplayedThisLoad_[V5a[a].setKey || a] = !0;
            Dx.set("" + a + "-impression", parseInt(Dx.get("" + a + "-impression") || 0, 10) + 1)
        }
    }
    ;
    f.onYtSignalActionConfirmMentionsEdu = function() {
        Dv(this.hostElement, "yt-close-popup-action", ["yt-bubble-hint-renderer"]);
        QM.getInstance();
        PM.set("edu-dismissed", !0)
    }
    ;
    f.onYtSignalActionRecordMentionsEduImpression = function() {
        QM.getInstance();
        var a = PM.set
          , b = parseInt(PM.get("edu-impressions"), 10);
        a.call(PM, "edu-impressions", (isFinite(b) ? b : 0) + 1)
    }
    ;
    f.onYtPageManagerAttached = function(a) {
        var b;
        ((b = fz(a)) == null ? void 0 : b.id) === "page-manager" && this.pageManagerAttachedPromise.resolve()
    }
    ;
    f.onInvokeInstrumentManagerAction = function(a, b) {
        V3c(b, a)
    }
    ;
    f.updateIconSet = function() {
        var a = this.hostElement.querySelector("#masthead");
        if (a) {
            var b = qz(a)
              , c = b.querySelector("g#yt-logo-updated");
            c && (a = document.createElementNS("http://www.w3.org/2000/svg", "defs"),
            a.appendChild(c.cloneNode(!0)),
            (b = b.querySelector("g#yt-logo-red-updated")) && a.appendChild(b.cloneNode(!0)),
            this.initIconDefs("yt-logos-ext", a))
        }
    }
    ;
    f.updateMastheadData = function() {
        var a = this, b, c, d, e;
        return t(function(h) {
            if (h.nextAddress == 1) {
                b = a.data;
                c = a.hostElement.querySelector("#masthead");
                if (!c)
                    return h.return();
                ht(a, function() {
                    c.data = a.topbarData;
                    c.topbarIsAboveChipbar = a.topbarIsAboveChipbar
                });
                return a.get("response.topbar", b) && a.get("response.topbar.responseContext.maxAgeSeconds", b) !== 0 ? (d = sm().resolve(xI)) ? n(h, d(), 7) : a.ephemeralResponseStore ? n(h, a.ephemeralResponseStore.put("service:topbar:fallback", new qA({
                    innertubeResponse: a.get("response.topbar", b)
                })), 0) : h.jumpTo(0) : h.jumpTo(0)
            }
            return (e = h.yieldResult) ? n(h, e.put("service:topbar:fallback", new qA({
                innertubeResponse: a.get("response.topbar", b)
            })), 0) : h.jumpTo(0)
        })
    }
    ;
    f.computeTopbarData = function(a) {
        if (!a)
            return null;
        var b;
        return this.isShortsPage && this.topbarData && !A((b = a.response) == null ? void 0 : b.topbar, yNc) ? this.topbarData : a.response && "topbar"in a.response ? A(a.response.topbar, yNc) || null : null
    }
    ;
    f.computeChipbarIsBelowTopbar = function(a) {
        if (a == null || !a.response)
            return !1;
        a = a.response;
        var b, c, d;
        if (!((b = a.contents) == null ? 0 : (c = b.twoColumnBrowseResultsRenderer) == null ? 0 : (d = c.tabs) == null ? 0 : d.length))
            return !1;
        var e;
        if ((e = a.header) == null ? 0 : e.pageHeaderRenderer)
            return !1;
        b = a.contents.twoColumnBrowseResultsRenderer.tabs[0];
        var h, l, m;
        if (!(b == null ? 0 : (h = b.tabRenderer) == null ? 0 : (l = h.content) == null ? 0 : (m = l.richGridRenderer) == null ? 0 : m.header))
            return !1;
        var p;
        return !!A((p = b.tabRenderer.content.richGridRenderer) == null ? void 0 : p.header, rPb)
    }
    ;
    f.onSetTheaterModeEnabled = function(a, b) {
        this.isTheaterModeSession = b.enabled;
        this.setTheaterModeStyles(b.enabled)
    }
    ;
    f.setTheaterModeStyles = function() {
        this.setMastheadTheme()
    }
    ;
    f.onDarkModeToggledAction = function() {
        gd(window.location.href);
        var a = !!gk(window.location.href).themeRefresh;
        a && Gm(new Hk("themeRefresh param is in url.",this.getThemeSettingsToLog()));
        if (!a) {
            l9a();
            a = {
                themeRefresh: 1
            };
            var b = sm().resolve(bx);
            if (b.isOnWatch()) {
                var c, d;
                b = ((c = b.getPlayerFromWatch()) == null ? void 0 : (d = c.getPlayer()) == null ? void 0 : d.getCurrentTime()) || 0;
                b >= 1 && (a.time_continue = Math.floor(b))
            }
            Bk() || py() !== "USER_INTERFACE_THEME_DARK" || (a.theme = "dark");
            ny(hk(window.location.href, a))
        }
        y("web_appshell_refresh_trigger") && Na.caches && this.refreshAppShellResponse();
        c = jd(window.location.href);
        sm().resolve(Dgb).replaceUrl(sd(c, "theme"))
    }
    ;
    f.onYtSignalActionToggleRestrictedModeOnAction = function() {
        this.setRestrictedMode(!0)
    }
    ;
    f.onYtSignalActionToggleRestrictedModeOffAction = function() {
        this.setRestrictedMode(!1)
    }
    ;
    f.onPlayerFullscreen = function(a) {
        yv();
        this.playerFullscreen = a
    }
    ;
    f.setRestrictedMode = function(a) {
        var b = Ek();
        Gk(0, 58, a);
        b.save();
        sm().resolve(Wx).reload()
    }
    ;
    f.onPageChanged = function(a) {
        a.detail.newPageType === "ytd-watch-flexy" || a.detail.newPageType === "ytd-watch-fixie" || a.detail.newPageType === "ytd-watch-grid" ? this.ytdReduxBehavior.dispatch($v("WEB_PAGE_TYPE_WATCH")) : a.detail.newPageType === "ytd-shorts" ? this.ytdReduxBehavior.dispatch($v("WEB_PAGE_TYPE_SHORTS")) : y("enable_playables_fullscreen_refactor") && a.detail.newPageType === "ytd-browse" && a.detail.newPageSubtype === "mini_app" ? this.ytdReduxBehavior.dispatch($v("WEB_PAGE_TYPE_MINI_APP")) : this.ytdReduxBehavior.dispatch($v("WEB_PAGE_TYPE_UNKNOWN"));
        a.detail.oldPageType && this.setMastheadTheme();
        this.isFullWindowSession && this.setFullscreen();
        this.updateIsInlinePreviewDisabled()
    }
    ;
    f.onSetCookieCommand = function(a) {
        if (a = A(a, uNc)) {
            var b = Ek();
            a.flagNum && typeof a.value === "boolean" ? (Gk(0, a.flagNum, a.value),
            b.save()) : a.key && typeof a.stringValue === "string" && (b.set(a.key, a.stringValue),
            b.save())
        }
    }
    ;
    f.onSetPrefStorageEntryCommand = function(a) {
        var b = A(a, wNc);
        b && rw.getInstance().then(function(c) {
            c !== void 0 && b.key !== void 0 && c.set(b.key, b.value)
        })
    }
    ;
    f.onSetLocalStorageCommand = function(a) {
        (a = A(a, vNc)) && window.localStorage && typeof a.key === "string" && typeof a.value === "string" && (window.localStorage[a.key] = a.value)
    }
    ;
    f.onGuideToggleTap = function() {
        zv(this.hostElement, "yt-guide-toggle")
    }
    ;
    f.onGuideToggleHover = function() {
        zv(this.hostElement, "yt-guide-hover")
    }
    ;
    f.isTheaterMode = function() {
        return this.isWatchPage && this.isTheaterModeSession
    }
    ;
    f.isAppDarkTheme = function() {
        return document.documentElement.hasAttribute("dark")
    }
    ;
    f.setMastheadTheme = function() {
        var a = qz(this.hostElement).querySelector("#masthead");
        a && (a.dark = a.isDarkThemeForced || this.isTheaterMode() || this.isAppDarkTheme(),
        a.isDarkThemeForced = !1)
    }
    ;
    f.onRequestPanelModeChange = function(a, b) {
        this.hideHeaderShadow = b.mode !== "seamed"
    }
    ;
    f.onGuideOpenButtonHover = function() {
        this.renderGuide = !0
    }
    ;
    f.onDrawerIronSelect = function(a) {
        fz(a).id === "guide" && this.processDrawerIronSelect()
    }
    ;
    f.processDrawerIronSelect = function() {
        this.ytRendererBehavior.markDirty();
        var a = "closed";
        this.guide.opened && (this.renderGuide = !0,
        this.guide.persistent || (a = "opened"));
        zv(this.hostElement, "yt-autonav-pause-guide-" + a)
    }
    ;
    f.onAddElementToApp = function(a) {
        T(this.hostElement).appendChild(a.detail)
    }
    ;
    f.onThrottledScroll = function() {
        var a = sm().resolve(bx).getCurrentPage();
        a && (this.scrollAtTop = a.getScrollTop() <= 0);
        this.mastheadHidden = this.canHideMasthead()
    }
    ;
    f.canHideMasthead = function() {
        return this.scrollAtTop && !!this.fullscreen
    }
    ;
    f.setFullscreen = function() {
        if (y("external_fullscreen") || !this.isWatchPage) {
            var a = y("kevlar_fullerscreen_root_only_killswitch") ? !!yv() : !!yv() && yv() === document.documentElement;
            a = (this.isWatchPage || y("web_fullscreen_shorts") && this.isShortsPage || y("enable_playables_fullscreen_refactor") && this.isMiniAppPage) && (a || this.isFullWindowSession);
            this.fullscreen !== a && ((this.fullscreen = a) && Ev(this.hostElement, "yt-close-all-popups-action"),
            this.isShortsPage && Aw.dispatch(Wv({
                type: "SET_IS_FULLSCREEN",
                payload: {
                    isFullscreen: this.fullscreen
                }
            })),
            this.toggleFullscreenStyles(this.isWatchPage && this.fullscreen, this.isMiniAppPage && this.fullscreen, this.isShortsPage && this.fullscreen),
            Dv(this.hostElement, "yt-fullscreen-change-action", [this.fullscreen]))
        }
    }
    ;
    f.updateMastheadCssHeight = function() {
        var a = this.mastheadHeight;
        this.fullscreen && (a = 0);
        tz(this.hostElement, {
            "--ytd-masthead-height": a + "px"
        })
    }
    ;
    f.updateNetworkStatusBannerDisplayStatus = function() {
        var a = "unset";
        this.fullscreen && (a = "none");
        tz(this.hostElement, {
            "--ytd-network-status-banner-display": a
        })
    }
    ;
    f.updateNetworkStatusBannerCssHeight = function() {
        var a = "unset";
        this.fullscreen && (a = "0px");
        tz(this.hostElement, {
            "--ytd-network-status-banner-max-height": a
        })
    }
    ;
    f.toggleFullscreenStyles = function(a, b, c) {
        var d = sm().resolve(bx).getCurrentPage();
        a || b ? (document.body.classList.add("no-scroll"),
        d.pageScrollElement = this.hostElement,
        this.scrolling = !0,
        this.hostElement.addEventListener("scroll", MA(this, this.onScroll)),
        d.setScrollTop(0),
        tz(this.hostElement, {
            "--ytd-app-fullerscreen-scrollbar-width": WM() + "px"
        })) : c ? zv(this.hostElement, "yt-guide-close") : (this.isShortsPage && zv(this.hostElement, "yt-guide-show"),
        document.body.classList.remove("no-scroll"),
        d.pageScrollElement = null,
        this.scrolling = !1,
        this.hostElement.removeEventListener("scroll", MA(this, this.onScroll)));
        this.mastheadHidden = a || b || c;
        this.updateMastheadCssHeight();
        y("network_status_banner_display_none") ? this.updateNetworkStatusBannerDisplayStatus() : this.updateNetworkStatusBannerCssHeight()
    }
    ;
    f.onScroll = function() {
        this.ytRendererBehavior.markDirty();
        this.scrollThrottle.fire()
    }
    ;
    f.onYtMastheadHeightChanged = function(a, b) {
        this.mastheadHeight = b.height;
        this.updateMastheadCssHeight()
    }
    ;
    f.onYtNavigateAction = function(a) {
        a = this.get("navigateAction.endpoint", a);
        zv(this.hostElement, "yt-navigate", {
            endpoint: a
        })
    }
    ;
    f.onYtRegisterCreateFamilyDialog = function() {
        if (!this.hasCreateFamilyDialog) {
            var a = document.createElement("yt-create-family-dialog");
            T(this.hostElement).appendChild(a);
            this.hasCreateFamilyDialog = !0
        }
    }
    ;
    f.onSetPushNotificationsEnabledCommand = function(a) {
        var b = this
          , c = A(a, xNc);
        c && typeof c.enabled === "boolean" && (Notification.permission !== "granted" ? y9a().then(function() {
            Notification.permission === "granted" ? (a9a(!c.enabled).then(f9a),
            c.successAction && Hv(b.hostElement, [c.successAction])) : c.failureAction && Hv(b.hostElement, [c.failureAction])
        }) : (a9a(!c.enabled).then(f9a),
        c.successAction && Hv(this.hostElement, [c.successAction])))
    }
    ;
    f.onYtSignalActionEnableChromeNotifications = function() {
        v9a(!0)
    }
    ;
    f.onFocusSearchBox = function() {
        var a = this.hostElement.querySelector("ytd-searchbox");
        a && a.focus()
    }
    ;
    f.onOpenHotkeyDialog = function() {
        this.topbarData.hotkeyDialog && this.ytOpenPopupBehavior.openPopup({
            openPopupAction: {
                popupType: "DIALOG",
                popup: {
                    hotkeyDialogRenderer: A(this.topbarData.hotkeyDialog, BNc)
                }
            }
        })
    }
    ;
    f.onYtSignalActionShowKeyboardShortcutDialog = function() {
        Dv(this.hostElement, "yt-close-popup-action", ["ytd-multi-page-menu-renderer"]);
        this.onOpenHotkeyDialog()
    }
    ;
    f.onYtEndpointChangeHandler = function(a, b) {
        var c = Oo(Vx);
        c.pendingPrefetchJob_ && (b = !(!b || b.autonav != "1"),
        c.pendingPrefetchJob_.resolve(a && j6a(a) ? k6a(a, b) : ""),
        c.pendingPrefetchJob_ = null);
        Dv(this.hostElement, "yt-pause-active-page-context");
        Dv(this.hostElement, "ytd-log-youthere-nav");
        Dv(this.hostElement, "yt-prepare-page-dispose")
    }
    ;
    f.handleClearUrlParamCommand = function(a) {
        if (a.clearUrlParamCommand && a.clearUrlParamCommand.paramKeys) {
            var b = a.clearUrlParamCommand.paramKeys;
            a = Xn(window.location.href);
            b = g(b);
            for (var c = b.next(); !c.done; c = b.next())
                a.JSC$7652_queryData_.remove(c.value);
            window.history.replaceState(window.history.state, document.title, a.toString())
        }
    }
    ;
    f.handleCommandWithCommandHandler = function(a, b) {
        Tv.instance.resolveCommand(a, {
            form: {
                element: b
            }
        })
    }
    ;
    f.onYtTimedCommand = function(a) {
        var b = this;
        a = A(a, gNc);
        var c = a.command;
        c && Nk(Ei, function() {
            var d = A(c, CWa);
            d ? (Tv.instance.resolveCommand(c),
            b.maybeLogGetAnswerRequestTick(d)) : Gv(b.hostElement, [c], b.hostElement)
        }, a.timeoutMs || 0)
    }
    ;
    f.maybeLogGetAnswerRequestTick = function(a) {
        a && a.isFirstRequest && (Kq("search_overview_answer"),
        Lq("so_rq", void 0, "search_overview_answer"))
    }
    ;
    f.onYtSignalActionSkipNavigation = function() {
        var a = sm().resolve(bx).getCurrentPage();
        Yl(a)
    }
    ;
    f.onYtSignalActionCopyDebugData = function() {
        lgb()
    }
    ;
    f.handleEntityUpdateCommand = function(a) {
        zw(A(a, STa).entityBatchUpdate, this.ytdReduxBehavior.store)
    }
    ;
    f.logFlowLoggingEventCommand = function(a) {
        if (a = A(a, LQb))
            if (a.eventType === "FLOW_LOGGING_EVENT_CLASSIFICATION_START_EVENT") {
                var b = a.flowEventNamespace
                  , c = a.flowEventType
                  , d = a.flowType;
                d && b && c && G5a(tx(b, c, a.flowEventMetadata), d)
            } else {
                b = sx();
                c = a.flowEventNamespace;
                d = a.flowEventType;
                var e = a.flowType;
                e && c && d && ux(b, tx(c, d, a.flowEventMetadata), e, a.flowNonce)
            }
    }
    ;
    f.onGuideTouchStart = function() {
        this.guideScrolledByTouch = !0
    }
    ;
    f.onGuideTouchEnd = function() {
        this.guideScrolledByTouch = !1
    }
    ;
    f.onTouchStart = function() {
        var a = aN();
        nq() && lr(a.JSC$13131_screenManager, {
            visualElement: a.ve
        })
    }
    ;
    f.handleWebNativeShareCommand = function(a) {
        navigator.share({
            url: A(a, sNc).url
        }).catch(function() {})
    }
    ;
    f.handleSelectCountryCommand = function(a) {
        if (a = A(a, oNc).gl) {
            var b = {
                persist_gl: 1,
                gl: a
            }
              , c = Ek();
            c.set("gl", a);
            c.save();
            a = Fca(b);
            ny(a)
        }
    }
    ;
    f.handlePersistSubscriptionsDisplayPreferencesCommand = function(a) {
        if (a = A(a, mNc)) {
            var b = Ek();
            Gk(0, 155, a.useListView);
            b.save()
        }
    }
    ;
    f.handleSelectLanguageCommand = function(a) {
        if (a = A(a, pNc).hl) {
            var b = Ek();
            b.set("hl", a);
            b.save();
            sm().resolve(Wx).reload()
        }
    }
    ;
    f.handleConfirmDialogEndpoint = function(a) {
        (a = this.ytOpenPopupBehavior.getNavigationEndpointPopupAction(a)) && this.ytOpenPopupBehavior.openPopup(a)
    }
    ;
    f.handleOpenPopupNavigationEndpoints = function(a, b) {
        y("web_button_rework") && (a = this.ytOpenPopupBehavior.getNavigationEndpointPopupAction(a)) && this.ytOpenPopupBehavior.openPopup(a, b)
    }
    ;
    f.handleSaveCommandToSessionStorage = function(a) {
        if (a = A(a, KSa)) {
            var b = a.key;
            b && a.command && window.sessionStorage.setItem("" + b, JSON.stringify(a.command))
        }
    }
    ;
    f.hardReloadWithShellPurge = function(a) {
        a = a === void 0 ? {} : a;
        a = Object.assign({}, a, {
            purge_shell: 1
        });
        a = Fca(a);
        ny(a)
    }
    ;
    f.refreshAppShellResponse = function() {
        navigator.serviceWorker && navigator.serviceWorker.ready.then(function(a) {
            a && a.active && a.active.postMessage({
                type: "refresh_shell"
            })
        }).catch(function(a) {
            a.name !== "SecurityError" && Fm(a)
        })
    }
    ;
    f.onDeviceThemeChanged = function() {
        var a = qy();
        Gk(Ek(), 185, a);
        Ek().save()
    }
    ;
    f.handleYtRegisterPromoCommand = function(a) {
        if (A(a, tNc)) {
            var b = sm().resolve(bx).getCurrentPage() || this.hostElement;
            xRc().registerPromoCommand(A(a, tNc), b)
        }
    }
    ;
    f.onYtNavigateHomeAction = function() {
        if (!y("kevlar_miniplayer_navigate_home_from_app_killswitch")) {
            var a, b, c, d, e = (d = (a = this.topbarData) == null ? void 0 : (b = a.logo) == null ? void 0 : (c = b.topbarLogoRenderer) == null ? void 0 : c.endpoint) != null ? d : Dw;
            this.ytComponentBehavior.resolveCommand(e)
        }
    }
    ;
    f.onYtLocationCollectionCommand = function(a) {
        B3c(A(a, LNc))
    }
    ;
    f.onYtGetLocationCommand = function(a) {
        gSc(A(a, KNc), this)
    }
    ;
    f.updateRenderGuideFromBinding = function(a) {
        this.renderGuide = a.detail.value
    }
    ;
    f.updateGuidePersistentAndVisibleFromBinding = function(a) {
        this.guidePersistentAndVisible = a.detail.value
    }
    ;
    f.updateMiniGuideVisibleFromBinding = function(a) {
        this.miniGuideVisible = a.detail.value
    }
    ;
    f.onThemeSelected = function(a, b) {
        var c = Ek(), d = a || b ? a : qy(), e;
        if (e = d && this.getCurrentTheme() !== "USER_INTERFACE_THEME_DARK" || !d && this.getCurrentTheme() !== "USER_INTERFACE_THEME_LIGHT")
            gd(window.location.href),
            e = !0;
        Gk(0, 165, a);
        Gk(0, 174, b);
        c.save();
        e && Dv(this.hostElement, "yt-dark-mode-toggled-action", [d]);
        Dv(this.hostElement, "yt-close-popup-action", ["ytd-multi-page-menu-renderer"])
    }
    ;
    f.getCurrentTheme = function() {
        return ry() ? this.isAppDarkTheme() ? "USER_INTERFACE_THEME_DARK" : "USER_INTERFACE_THEME_LIGHT" : py()
    }
    ;
    f.handleSignalActionToggleDarkThemeOn = function() {
        this.onThemeSelected(!0, !1)
    }
    ;
    f.handleSignalActionToggleDarkThemeOff = function() {
        this.onThemeSelected(!1, !0)
    }
    ;
    f.handleSignalActionToggleDarkThemeDevice = function() {
        this.onThemeSelected(!1, !1)
    }
    ;
    f.handleShowDmaConsentFlow = function(a) {
        var b = this, c, d;
        return t(function(e) {
            if (e.nextAddress == 1) {
                try {
                    c = (d = xA()) == null ? void 0 : d.getPlayerPromise()
                } catch (h) {}
                return n(e, M3c(a, c), 2)
            }
            Dv(b.hostElement, "yt-close-popup-action", ["ytd-multi-page-menu-renderer"]);
            ta(e)
        })
    }
    ;
    f.handleSelectActiveIdentityEndpointInternal = function(a) {
        W8a();
        a = A(a, QSb);
        if (a != null && a.supportedTokens) {
            a = g(a.supportedTokens);
            for (var b = a.next(); !b.done; b = a.next())
                b = b.value,
                b.accountSigninToken && ny(b.accountSigninToken.signinUrl, void 0, void 0, window.top)
        }
    }
    ;
    f.handleUpdatePermissionRoleCommand = function(a) {
        if (a = A(a, rWa)) {
            var b;
            this.hasDelegation = !((b = A(a.renderer, qWa)) == null || !b.status)
        }
    }
    ;
    da.Object.defineProperties(Z$.prototype, {
        csiServiceName: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                return "youtube"
            }
        }
    });
    da.Object.defineProperties(Z$, {
        template: {
            configurable: !0,
            enumerable: !0,
            get: function() {
                if (D2c === void 0) {
                    var a = document.createElement("template");
                    G(a, "<!--css-build:shady--><!--css-build:shady--><yt-guide-manager id=\"guide-service\" disabled=\"[[standalone]]\" guide-persistent-and-visible=\"[[guidePersistentAndVisible]]\" mini-guide-visible=\"[[miniGuideVisible]]\" render-guide=\"[[renderGuide]]\" on-guide-persistent-and-visible-changed=\"updateGuidePersistentAndVisibleFromBinding\" on-mini-guide-visible-changed=\"updateMiniGuideVisibleFromBinding\" on-render-guide-changed=\"updateRenderGuideFromBinding\" class=\"style-scope ytd-app\">\n</yt-guide-manager>\n<yt-mdx-manager class=\"style-scope ytd-app\"></yt-mdx-manager>\n<yt-playlist-manager class=\"style-scope ytd-app\"></yt-playlist-manager>\n<yt-hotkey-manager class=\"style-scope ytd-app\"></yt-hotkey-manager>\n<div id=\"content\" class=\"style-scope ytd-app\">\n  <div id=\"masthead-container\" class=\"style-scope ytd-app\">\n    <slot name=\"masthead\" class=\"style-scope ytd-app\"></slot>\n  </div>\n  <tp-yt-app-drawer id=\"guide\" align=\"start\" role=\"navigation\" class=\"style-scope ytd-app\">\n    <div id=\"guide-wrapper\" class=\"style-scope ytd-app\">\n      <div id=\"guide-spacer\" class=\"style-scope ytd-app\"></div>\n      <div id=\"guide-content\" class=\"style-scope ytd-app\">\n        <div id=\"header\" hidden=\"[[guidePersistentAndVisible]]\" class=\"style-scope ytd-app\">\n          \n          <yt-icon-button id=\"guide-button\" aria-label$=\"[[menuStrings.GUIDE_ALT_LABEL]]\" pressed=\"true\" toggleable=\"true\" on-mouseenter=\"onGuideToggleHover\" on-tap=\"onGuideToggleTap\" class=\"style-scope ytd-app\">\n            <yt-icon id=\"guide-icon\" icon=\"yt-icons:menu\" class=\"style-scope ytd-app\"></yt-icon>\n          </yt-icon-button>\n          <ytd-topbar-logo-renderer country-code=\"[[topbarData.countryCode]]\" data=\"[[topbarData.logo.topbarLogoRenderer]]\" disable-upgrade$=\"[[guideIsVisibleButNotPersistent]]\" class=\"style-scope ytd-app\">\n          </ytd-topbar-logo-renderer>\n        </div>\n        <div id=\"guide-inner-content\" on-touchstart=\"onGuideTouchStart\" on-touchend=\"onGuideTouchEnd\" class=\"style-scope ytd-app\">\n          <template is=\"dom-if\" if=\"[[renderGuide]]\" class=\"style-scope ytd-app\">\n            <ytd-guide-renderer id=\"guide-renderer\" class=\"style-scope ytd-app\">\n              <slot name=\"guide-links-primary\" slot=\"guide-links-primary\" class=\"style-scope ytd-app\"></slot>\n              <slot name=\"guide-links-secondary\" slot=\"guide-links-secondary\" class=\"style-scope ytd-app\"></slot>\n              <slot name=\"vat-notice\" slot=\"vat-notice\" class=\"style-scope ytd-app\"></slot>\n              <slot name=\"copyright\" slot=\"copyright\" class=\"style-scope ytd-app\"></slot>\n            </ytd-guide-renderer>\n          </template>\n        </div>\n      </div>\n    </div>\n  </tp-yt-app-drawer>\n  <ytd-mini-guide-renderer disable-upgrade$=\"[[!miniGuideVisible]]\" hidden=\"[[!miniGuideVisible]]\" visible=\"[[miniGuideVisible]]\" class=\"style-scope ytd-app\">\n  </ytd-mini-guide-renderer>\n  <ytd-page-manager id=\"page-manager\" class=\"style-scope ytd-app\"></ytd-page-manager>\n</div>\n<ytd-permission-role-bottom-bar-renderer class=\"style-scope ytd-app\"></ytd-permission-role-bottom-bar-renderer>\n<ytd-popup-container class=\"style-scope ytd-app\"></ytd-popup-container>\n<ytd-third-party-manager class=\"style-scope ytd-app\"></ytd-third-party-manager>\n<div id=\"video-preview\" class=\"style-scope ytd-app\"></div>\n");
                    a.content.insertBefore(W().content.cloneNode(!0), a.content.firstChild);
                    D2c = a
                }
                a = D2c;
                return a
            }
        }
    });
    var $$ = Z$;
    $$.prototype.onOpenHotkeyDialog = $$.prototype.onOpenHotkeyDialog;
    $$.prototype.onFocusSearchBox = $$.prototype.onFocusSearchBox;
    $$.prototype.onYtMastheadHeightChanged = $$.prototype.onYtMastheadHeightChanged;
    $$.prototype.setFullscreen = $$.prototype.setFullscreen;
    $$.prototype.onAddElementToApp = $$.prototype.onAddElementToApp;
    $$.prototype.onDrawerIronSelect = $$.prototype.onDrawerIronSelect;
    $$.prototype.onGuideOpenButtonHover = $$.prototype.onGuideOpenButtonHover;
    $$.prototype.onRequestPanelModeChange = $$.prototype.onRequestPanelModeChange;
    $$.prototype.onPageChanged = $$.prototype.onPageChanged;
    $$.prototype.onSetTheaterModeEnabled = $$.prototype.onSetTheaterModeEnabled;
    $$.prototype.updateMastheadData = $$.prototype.updateMastheadData;
    $$.prototype.onYtPageManagerAttached = $$.prototype.onYtPageManagerAttached;
    $$.prototype.observeGuideVisibility = $$.prototype.observeGuideVisibility;
    $$.prototype.guideIsVisibleButNotPersistentSelectorChanged = $$.prototype.guideIsVisibleButNotPersistentSelectorChanged;
    $$.prototype.isInlinePreviewEnabledChanged = $$.prototype.isInlinePreviewEnabledChanged;
    u([J(Xz), v("design:type", Object)], $$.prototype, "ytdReduxBehavior", void 0);
    u([J(FD.YtEventForwardingBehavior), v("design:type", Object)], $$.prototype, "ytEventForwardingBehavior", void 0);
    u([J(Oy.YtOpenPopupBehavior), v("design:type", Object)], $$.prototype, "ytOpenPopupBehavior", void 0);
    u([J(EA.YtActionHandlerBehavior), v("design:type", Object)], $$.prototype, "ytActionHandlerBehavior", void 0);
    u([J({
        _noAccessors: !0,
        actionRouterIsRoot: !1,
        created: function() {
            this.actionRouter_ = Gr.getInstance();
            this.actionRouterNode = this.actionRouterIsRoot ? document.body : this;
            this.onYtActionBoundListener_ = this.onYtAction_.bind(this);
            this.actionRouterListenersRegistered_ = !1;
            y("action_router_attached_only_killswitch") && this.registerActionRouterEventListeners_()
        },
        attached: function() {
            this.registerActionRouterEventListeners_()
        },
        detached: function() {
            this.unregisterActionRouterEventListeners_()
        },
        registerActionRouterEventListeners_: function() {
            if (!this.actionRouterListenersRegistered_) {
                this.actionRouterListenersRegistered_ = !0;
                var a;
                ((a = this.actionRouterNode.hostElement) != null ? a : this.actionRouterNode).addEventListener("yt-action", this.onYtActionBoundListener_)
            }
        },
        unregisterActionRouterEventListeners_: function() {
            this.actionRouterListenersRegistered_ = !1;
            var a;
            ((a = this.actionRouterNode.hostElement) != null ? a : this.actionRouterNode).removeEventListener("yt-action", this.onYtActionBoundListener_)
        },
        onYtAction_: function(a) {
            this.actionRouter_.handleAction(a.detail)
        }
    }), v("design:type", Object)], $$.prototype, "ytActionRouterBehavior", void 0);
    u([J(RRc.YtdAppBehavior), v("design:type", Object)], $$.prototype, "ytdAppBehavior", void 0);
    u([J(KA.YtEndpointBehavior), v("design:type", Object)], $$.prototype, "ytEndpointBehavior", void 0);
    u([J(U2c.YtEndpointHandlerWithYpcBehavior), v("design:type", Object)], $$.prototype, "ytEndpointHandlerWithYpcBehavior", void 0);
    u([J(E2c.YtLogYpcFlowCommandsBehavior), v("design:type", Object)], $$.prototype, "ytLogYpcFlowCommandsBehavior", void 0);
    u([J(X.YtRendererBehavior), v("design:type", Object)], $$.prototype, "ytRendererBehavior", void 0);
    u([J(JA.YtComponentBehavior), v("design:type", Object)], $$.prototype, "ytComponentBehavior", void 0);
    u([P({
        selector: Pfb
    }), v("design:type", Object)], $$.prototype, "tabGesturesIsActive", void 0);
    u([P(), v("design:type", Boolean)], $$.prototype, "renderGuide", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], $$.prototype, "guidePersistentAndVisible", void 0);
    u([P({
        selector: Ifb
    }), v("design:type", Boolean)], $$.prototype, "guideIsVisibleButNotPersistent", void 0);
    u([P({
        value: !1,
        reflectToAttribute: !0
    }), v("design:type", Boolean)], $$.prototype, "standalone", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], $$.prototype, "miniGuideVisible", void 0);
    u([P({
        selector: Ofb
    }), v("design:type", Number)], $$.prototype, "miniplayerPlaybackState", void 0);
    u([P({
        selector: hA,
        reflectToAttribute: !0
    }), v("design:type", Boolean)], $$.prototype, "miniplayerIsActive", void 0);
    u([P({
        computed: "computeIsInlinePreviewEnabled(miniplayerIsActive, miniplayerPlaybackState, isInlinePreviewDisabled)"
    }), v("design:type", Boolean)], $$.prototype, "isInlinePreviewEnabled", void 0);
    u([P(), v("design:type", Boolean)], $$.prototype, "isInlinePreviewDisabled", void 0);
    u([P({
        reflectToAttribute: !0,
        value: function() {
            return bk("START_IN_FULL_WINDOW_MODE")
        }
    }), v("design:type", Boolean)], $$.prototype, "mastheadHidden", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], $$.prototype, "playerFullscreen", void 0);
    u([P({
        value: !1,
        reflectToAttribute: !0
    }), v("design:type", Boolean)], $$.prototype, "hideHeaderShadow", void 0);
    u([P({
        value: {
            GUIDE_ALT_LABEL: Mv("GUIDE_ALT_LABEL", void 0, "Guide")
        }
    }), v("design:type", Object)], $$.prototype, "menuStrings", void 0);
    u([P({
        computed: "computeTopbarData(data)"
    }), v("design:type", Object)], $$.prototype, "topbarData", void 0);
    u([P({
        computed: "computeChipbarIsBelowTopbar(data)"
    }), v("design:type", Object)], $$.prototype, "topbarIsAboveChipbar", void 0);
    u([P({
        selector: Kfb
    }), v("design:type", Boolean)], $$.prototype, "isWatchPage", void 0);
    u([P({
        selector: Lfb,
        reflectToAttribute: !0
    }), v("design:type", Boolean)], $$.prototype, "isShortsPage", void 0);
    u([P({
        selector: function(a) {
            return a.ui.currentPageType === "WEB_PAGE_TYPE_MINI_APP"
        }
    }), v("design:type", Boolean)], $$.prototype, "isMiniAppPage", void 0);
    u([P({
        reflectToAttribute: !0,
        value: y("web_background_colors_update")
    }), v("design:type", Boolean)], $$.prototype, "backgroundRefresh", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], $$.prototype, "scrolling", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], $$.prototype, "hasDelegation", void 0);
    u([P({
        reflectToAttribute: !0,
        value: !1
    }), v("design:type", Boolean)], $$.prototype, "guideScrolledByTouch", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Object)], $$.prototype, "darkerDarkTheme", void 0);
    u([P({
        reflectToAttribute: !0
    }), v("design:type", Boolean)], $$.prototype, "frostedGlass", void 0);
    u([Sy("guide"), v("design:type", Object)], $$.prototype, "guide", void 0);
    u([Sy("guide-service"), v("design:type", A6)], $$.prototype, "guideService", void 0);
    u([Sy("guide-inner-content"), v("design:type", HTMLDivElement)], $$.prototype, "guideInnerContent", void 0);
    u([Wy("isInlinePreviewEnabled"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $$.prototype, "isInlinePreviewEnabledChanged", null);
    u([O("guideIsVisibleButNotPersistent"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $$.prototype, "guideIsVisibleButNotPersistentSelectorChanged", null);
    u([O("guidePersistentAndVisible", "miniGuideVisible"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $$.prototype, "observeGuideVisibility", null);
    u([M("attached"), v("design:type", Function), v("design:paramtypes", [Event]), v("design:returntype")], $$.prototype, "onYtPageManagerAttached", null);
    u([O("data"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype", Promise)], $$.prototype, "updateMastheadData", null);
    u([M("yt-set-theater-mode-enabled"), v("design:type", Function), v("design:paramtypes", [CustomEvent, Object]), v("design:returntype")], $$.prototype, "onSetTheaterModeEnabled", null);
    u([M("yt-page-type-changed"), v("design:type", Function), v("design:paramtypes", [CustomEvent]), v("design:returntype")], $$.prototype, "onPageChanged", null);
    u([M("yt-request-panel-mode-change"), v("design:type", Function), v("design:paramtypes", [Event, Object]), v("design:returntype")], $$.prototype, "onRequestPanelModeChange", null);
    u([M("yt-guide-hover"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $$.prototype, "onGuideOpenButtonHover", null);
    u([M("app-drawer-transitioned"), v("design:type", Function), v("design:paramtypes", [Event]), v("design:returntype")], $$.prototype, "onDrawerIronSelect", null);
    u([M("yt-add-element-to-app"), v("design:type", Function), v("design:paramtypes", [CustomEvent]), v("design:returntype")], $$.prototype, "onAddElementToApp", null);
    u([M("yt-set-fullerscreen-styles"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $$.prototype, "setFullscreen", null);
    u([M("yt-masthead-height-changed"), v("design:type", Function), v("design:paramtypes", [CustomEvent, Object]), v("design:returntype")], $$.prototype, "onYtMastheadHeightChanged", null);
    u([M("yt-focus-searchbox"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $$.prototype, "onFocusSearchBox", null);
    u([M("yt-open-hotkey-dialog"), v("design:type", Function), v("design:paramtypes", []), v("design:returntype")], $$.prototype, "onOpenHotkeyDialog", null);
    $$ = u([R({
        is: "ytd-app"
    })], $$);
    fx().processSignal("eor")
}
).call(this);
    
