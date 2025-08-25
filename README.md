<!DOCTYPE html>
<html>

<script type="text/javascript">
function search_navigate() {
    var obj = document.getElementById("navbar_search");
    var keyword = obj.value;
    var dst = "https://scryfall.com/random?q=t:creature+mana=" + keyword;
    window.location = dst;
}
</script>
<input type="search" placeholder="Search creatures.." id="navbar_search" onEnter="search_navigate<>" />
<input type="button" id="navbar_submit" value="Submit" onClick="search_navigate()" />
</html>
