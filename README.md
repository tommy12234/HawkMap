{::nomarkdown}
<!-- HTML CODE-->
<html>

<head>
    <title>HawkMap</title>
    <div class="topHeader">
        <h6>HAWKMAP</h6>
        <div id="logo">
            <img src="mshsLogo.png" alt="logo" /> <!-- Maine South Logo -->
        </div>
    </div>
</head>

<body>



    <link href='https://fonts.googleapis.com/css?family=Advent Pro' rel='stylesheet'>


    <div class="popup" id="popup">
        <!-- Puts the popup that will be available for each room in the html -->
        <span class="popuptext" id="myPopup"> </span>
        <!-- Text of the popup -->
    </div>

    <input type="text" id="searchbar" onkeyup="filterSearch()" placeholder="Search for a room..." title="Type in a room.">

    <table id="tableOfRooms">
        <!-- The table of rooms for the user to use -->
        <tr class="header">
            <th style="width:40%;">Room Type</th>
            <th style="width:60%;">Room Name</th>
        </tr>
    </table>

    <link rel="stylesheet" type="text/css" href="hawkMap.css">
    <!-- Links to other files of the map -->
    <script type='text/javascript' src='raphael.js'></script>
    <!-- Enables use of Raphael -->
    <script type='text/javascript' src='raphael.min.js'></script>
    <script type='text/javascript' src='hawkMap.js'></script>

</body>

</html>
{:/}
