var elements = [];
function recurse(element) {
    if (element.childNodes.length > 0) 
        for (var i = 0; i < element.childNodes.length; i++) 
            recurse(element.childNodes[i]);

    if (element.nodeType == Node.TEXT_NODE && element.nodeValue.trim() != '') 
        elements.push(element);
}
var html = document.getElementsByTagName('html')[0];
recurse(html);

// your code here
