/**********************************
    MEDIA QUERIES : BREAKPOINTS    
***********************************/
/*
https://getbootstrap.com/docs/4.3/layout/grid/#grid-options
No media query for EXTRA SMALL DEVICES (less than 576px), since this is the default in Bootstrap - The 'mobile-first approach'
*/

/* SMALL DEVICES (landscape, 576px and up) */
@media (min-width: 576px) {
    .sm-item {}
    .item-sm {}
}

/* SMALL DEVICES ONLY! */
@media screen and (min-width: 576px) and (max-width: 767px) {
    .sm-item {}
    .item-sm {}
}

/* MEDIUM DEVICES (tablets, 768px and up) */
@media (min-width: 768px) {
    .md-item {}
    .item-md {}
}

/* MEDIUM DEVICES ONLY! */
@media screen and (min-width: 768px) and (max-width: 991px) {
    .md-item {}
    .item-md {}
}

/* LARGE DEVICES (desktops, 992px and up) */
@media (min-width: 992px) {
    .lg-item {}
    .item-lg {}
}

/* LARGE DEVICES ONLY! */
@media screen and (min-width: 992px) and (max-width: 1199px) {
    .lg-item {}
    .item-lg {}
}

/* EXTRA LARGE DEVICES (large desktops, 1200px and up) */
@media (min-width: 1200px) {
    .xl-item {}
    .item-xl {}
}
