# Bootstrap5_Walker_Nav_Menu
walker class for bootstrap 5


## Documentation: 
file to use bootstrap5-walker-nav-menu-pk.php
### To use megamenu
	- #### To use Megamenu use ( megamenu ) class to megamenu item class. To set collumn use ( collumn-1 , collumn-2 , collumn-3 , collumn-4 ) class.

### Css to use for search option:
<code>
	
/* main menu search icon */
li.search-bar {
	position: relative;
	margin-left: 25px;
}
li.search-bar a {
	width: 20px;
}
li.search-bar input {
	display: none;
}
li.search-bar .fa.fa-search {
	position: absolute;
	right: 10px;
	top: 50%;
	transform: translate(0, -50%);
	z-index: 9;
}
li.search-bar input {
	position: absolute;
	right: 0;
	top: 50%;
	transform: translate(0,-50%);
	padding: 20px;
	min-width: 400px;
}
li.search-bar input.show-search {
	display: block;
}
</code>
