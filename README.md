# JQUERY-Template
Call from app - or download and embed in you app
<script   src="http://code.jquery.com/jquery-3.2.1.min.js"   integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4="   crossorigin="anonymous"></script>

Copy Past this code
//Get the details from the object you are clicking on
let getEventTarget = (e) => {
    e = e || window.event;
    return e.target || e.srcElement; 
}
Appending ID to this base can use ID number instead of name...(
Appending Span 
//URL for rest call
let singleIDURL = baseurl+span;
