<html>

<script type="text/javascript">
function search_navigate() {
    var obj = document.getElementById("navbar_search");
    var keyword = obj.value;
    var dst = "https://scryfall.com/random?q=legal:commander+t:creature+mana=" + keyword;
    window.location = dst;
}
</script>

// Get the textbox element
// const textbox = document.getElementById('navbar_search');
// Add an event listener for the 'keydown' event
// textbox.addEventListener('keydown', function(event) {
 // Check if the ENTER key (key code 13) is pressed
 // if (event.key === 'Enter') {
 // Prevent the default action (e.g., new line in a textarea)
 // event.preventDefault();
// Submit the form
// document.getElementById('myForm').submit();
// }
// });

<form action="search_nagivate()">
    <input type="text" placeholder="Search mana costs.." id="navbar_search" onEnter="search_navigate<>" pattern="[0-9WwUuBbRrGgCcPp]*" />
    <input type="submit" style="display: none" />
    <input type="button" id="navbar_submit" value="Submit" onClick="search_navigate()" />
</form>form>
</html>
