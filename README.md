<html>

<script type="text/javascript">
function search_navigate() {
    var obj = document.getElementById("navbar_search");
    var keyword = obj.value;
    var dst = "https://scryfall.com/random?q=legal:commander+t:creature+mana=" + keyword;
    window.location = dst;
}
</script>
<input type="text" placeholder="Search mana costs.." id="navbar_search" onEnter="search_navigate<>" pattern="[0-9WwUuBbRrGgCcPp]*" />
<input type="button" id="navbar_submit" value="Submit" onClick="search_navigate()" />
</html>
