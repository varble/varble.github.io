<html>
    <script type="text/javascript">
    function search_navigate() {
        var obj = document.getElementById("navbar_search");
        var keyword = obj.value;
        var dst = "https://scryfall.com/random?q=legal:commander+t:creature+mana=" + keyword;
        window.location = dst;
    }
    </script>
    
    <form action="javascript:search_navigate()">
        <input type="text" placeholder="Search mana costs.." id="navbar_search" />
        <input type="submit" id="navbar_submit" value="Submit" />
    </form>
    <p style="font-size: 5px;color:#DBDBDB">V1.0</p>
</html>
