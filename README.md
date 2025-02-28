Main Structure
The entire page is structured within the <body> element, with no overall container wrapping everything.
Top-Level Structure

Navigation Bar Section

.navbar div (parent)

.part-one div (child)

.logo div (grandchild)
.location div (grandchild)


.part-second div (child)

.search-container div (grandchild)

.dropdown div (great-grandchild)
.search-input input (great-grandchild)
.search-button button (great-grandchild)




.part-third div (child)

.flag div (grandchild)
.account-section divs (grandchild - appears twice)
.cart div (grandchild)

.cart-icon div (great-grandchild)








Secondary Navigation

.secondary-nav div (parent)

Multiple .nav-item divs (children)
Special .nav-item.prime-item div (child)




Main Content Area

.main-img div (parent)

.home-img img (child)




Product Grid Sections

Two identical .container divs (parent)

Each contains four .category-card divs (children)

.category-title h2 (grandchild)
.product-grid div (grandchild)

Four .product-item divs (great-grandchild) each containing:

.product-image img (great-great-grandchild)
.product-name span (great-great-grandchild)




.see-more a (grandchild)






Footer Sections

.back-to-top div (parent)
.footer-content div (parent)

.footer-container div (child)

Four .footer-column divs (grandchildren)

h3 heading (great-grandchild)
ul list (great-grandchild)

Multiple li items with a links (great-great-grandchildren)








.footer-logo div (parent)

img (child)


.language-selection div (parent)

.language-btn button (child)
.country-btn button (child)


.services-container div (parent)

.services-grid div (child)

Multiple .service-item divs (grandchildren)

h4 heading (great-grandchild)
p paragraph (great-grandchild)






.footer-bottom div (parent)

ul list (child)

li items with a links (grandchildren)


p paragraph (child)
