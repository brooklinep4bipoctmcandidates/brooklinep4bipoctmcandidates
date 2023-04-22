#
# install custom bootstrap css and js
#
BOOTDISTDIR=/home/pfh/Desktop/bootstrap/dist

bootstrap: \
    css/bootstrap.min.css          \
    css/bootstrap.min.css.map      \
    js/bootstrap.bundle.min.js     \
    js/bootstrap.bundle.min.js.map

css/bootstrap.min.css:          ${BOOTDISTDIR}/css/bootstrap.min.css
	cp $< $@
css/bootstrap.min.css.map:      ${BOOTDISTDIR}/css/bootstrap.min.css.map
	cp $< $@
js/bootstrap.bundle.min.js:     ${BOOTDISTDIR}/js/bootstrap.bundle.min.js
	cp $< $@
js/bootstrap.bundle.min.js.map: ${BOOTDISTDIR}/js/bootstrap.bundle.min.js.map
	cp $< $@
