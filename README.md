JSON editor jQuery plugin
=========================

A JSON editor forked from [DavidDurman/FlexiJsonEditor](https://github.com/DavidDurman/FlexiJsonEditor)

CHANGELOG
============
Use to preview json string.

INSTALLATION
============

Include these lines into your HTML:

        <link rel="stylesheet" href="jsoneditor.css"/>
        <script src="jquery.min.js"></script>
        <script src="jquery.jsoneditor.js"></script>


USAGE
=====


        var myjson = { any: { json: { value: 1 } } };
        var opt = { 
            change: function(data) { /* called on every change */ },
            propertyclick: function(path) { /* called when a property is clicked with the JS path to that property */ }
        };
        /* opt.propertyElement = '<textarea>'; */ // element of the property field, <input> is default
        /* opt.valueElement = '<textarea>'; */  // element of the value field, <input> is default
        $('#mydiv').jsonEditor(myjson, opt);


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/DavidDurman/flexijsoneditor/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

