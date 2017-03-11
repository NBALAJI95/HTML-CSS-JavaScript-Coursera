For this part, two types of interactive behavior need to be added. These interactive behaviors are demonstrated in the accompanying video.

Style rules are added so that the label and input elements become significantly larger when the mouse is moved over them (and return to normal size when the mouse moves away from them). This can be easily achieved by using the hover pseudo-class for all label and input elements e.g. label:hover and input:hover. For example, label:hover { font-size:40px }. Add these in the style section of the web page.  
The following <script> instruction needs to be added before </body> , near the end of the file. It is a link to some JavaScript code. After this is added the face image will be immediately shown in the web page after the user selects a file using the file selector (the first input element). The JavaScript code shows the selected image in an img element with id="preview" (which should be shown under the file selector). Therefore, please ensure you use this id for your img.

<script src="https://www.cse.ust.hk/~rossiter/dating_web_site.js"></script>
